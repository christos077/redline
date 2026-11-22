# Redline customer discovery: who has this pain (Agent 1)

## Method note
- Web searches used: 5 of 12 (stopped searching because page cap was reached).
- Pages read (fetch attempts): 15 of 15. Only 3 returned readable content (dev.to x2, Hacker News x1); 11 were blocked (HTTP 402/403/404/redirect) including Reddit-adjacent, BigPockets, Justia, Blind, Indie Hackers, Moneywise, UniversalHub, AOL.
- Result: 0 of the 8 target findings met the bar. Below are 2 sourced items I actually read, and both are NEAR-MISS or adjacent evidence, NOT people hurt after signing. Treat as weak.
- No quotes below come from search-result snippets; all are from pages fetched. Note: fetch tool summarizes pages via a small model, so quotes are as returned by it, not independently diffed against raw HTML.

## Findings

### 1. Freelance developer who found an IP-grab clause BEFORE signing (near-miss, not hurt)
- Who: Varun Krishnan, freelance fullstack developer (self-described).
- Verbatim quote: "The clause said that anything I brought into the project including tools, libraries, and code I'd written before the engagement would become the exclusive property of the client upon completion."
- Also: "I pushed back. Told the client the clause needed to be amended before I could sign."
- Term: "pre-existing materials" IP assignment.
- Cost/consequence: He walked away from the project when the client got defensive; lost the job, kept his tools. No monetary figure stated.
- Source: https://dev.to/not_varunkv/the-contract-clause-that-almost-cost-me-my-entire-codebase-j9d
- Caveat: He caught it; shows the risk exists and that reading is what saved him, but he was not harmed by missing it.

### 2. Freelance web developer, payment-triggered IP clause (clause worked in his favor; adjacent, not pain)
- Who: Belal Zahran, freelance web developer.
- Verbatim quote: "All intellectual property rights to the deliverables shall transfer to the Client only upon receipt of full payment."
- Context: on "a $20,000 web development project" the client "would not be paying the final $15,000 installment"; "They paid within a week."
- Term: IP transfer on full payment.
- Cost/consequence: $15,000 at risk, recovered. Shows a clause the author knew to include; the pain is what would have happened without it, which he does not document.
- Source: https://dev.to/belal_zahran/the-freelance-contract-clause-that-saved-me-15000-4ja2
- Caveat: Not a person hurt by terms they misunderstood.

## Patterns (only what evidence shows)
- Freelancers publicly write about IP-assignment clauses as a recurring hazard, and in both readable cases the writer had the knowledge/habit to catch or draft the clause. That is weak evidence the pain is real for people who lack that habit; it is not evidence of harm.
- Hacker News item 8654629 (https://news.ycombinator.com/item?id=8654629) was read and contained no first-person harm account.

## What I could not find
- Any first-person, verbatim account of someone actually hurt by a clause they did not read or understand, with a cost. Zero qualifying findings.
- Reddit (r/legaladvice, r/freelance, r/smallbusiness, r/Renters, r/personalfinance): searches returned no Reddit threads; none read.
- Tenant accounts (auto-renewal, cleaning fees, early termination): I saw search-result snippets pointing to a Blind post (https://www.teamblind.com/post/apartment-lease-automatically-renews-itself-urgent-help-needed-dtbv1cnf), BiggerPockets threads, and a Salt Lake City cleaning-fee story (Moneywise/AOL), but all were blocked or 404, so I cannot quote them and have excluded them as findings. They are leads only, unverified.
- Indie Hackers, Trustpilot, CFPB/FTC complaint text: not read (blocked or not reached). FTC v. Greystar hidden-fee coverage appeared in a search snippet only; unverified.
- Small business owners and consumers (ToS/arbitration/auto-renew): no sourced personal accounts obtained.
- Suggested next step: rerun with a browser tool (Chrome/Playwright MCP) that can load Reddit, BiggerPockets, Blind, Indie Hackers, or use Reddit's public JSON endpoints; the fetch tool is blocked on most of these sites.
