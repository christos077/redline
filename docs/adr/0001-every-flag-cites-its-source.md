# ADR 0001: Every risk flag cites its source sentence

Status: Accepted · Date: 2026-11-22

## Decision
Every risk flag Redline shows must quote the exact sentence from the uploaded document that it came from.
The quote is checked word for word against the stored text before it is shown.
A flag whose source sentence cannot be shown is a bug, not a formatting preference. It is withheld, never shown uncited.

## Alternatives
- **The model describes risks in its own words, with no quote.** Easiest to build and the most readable, but the reader has no way to tell a real risk from an invented one.
- **Cite a section or clause number instead of the sentence.** Cheaper, but numbering is often missing or inconsistent, and the reader still has to find and interpret the text.
- **Quote where possible, paraphrase otherwise.** Covers more risks, but makes the guarantee unreliable: the reader can no longer tell which flags they can check.
- **Highlight a passage in the document without a quote.** Good for reading, but on its own it doesn't prove which words the claim rests on.

## Why
A reader can verify each flag for themselves without trusting Redline:
- Find the quoted sentence in their own copy of the document and confirm it is really there, unchanged.
- Read it in context and judge whether the flag's explanation and severity follow from it.
- Notice when Redline flagged nothing about a clause they care about, because every flag is tied to a visible sentence.
This matters because general chatbots are known to reword or invent clauses (see `research/summary.md`). A quote checked word for word is the difference Redline offers.

## Consequences
- **Rules out risks that no single sentence states.** Examples are risks that come from what's missing, such as having no termination right, or from how several clauses combine. These need their own design decision before they can ship.
- **Rules out OCR and any lossy text extraction.** A citation is only as good as the extracted text it points at.
- **Fewer flags.** A real risk is withheld if the model can't quote it exactly. We accept missing some risks in exchange for never showing an unsupported one.
- **Text handling must be precise.** Sentences must be matched against the stored text despite differences in whitespace, curly quotes and hyphenation from the source file. Any normalisation must still let the reader find the sentence in their own copy.
- **Testing:** every flag in every test output gets a word-for-word substring check. A single uncited or reworded flag fails the test.
- **Counter-offers and Q&A answers inherit the rule.** Each one points back to the sentence it responds to.
