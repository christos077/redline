# Redline research summary

Compiled 2026-11-22 from four parallel research agents (Sonnet), each capped at 12 searches / 15 page reads:

- [who-has-pain.md](who-has-pain.md): real people hurt by contract terms
- [what-goes-wrong.md](what-goes-wrong.md): clause types that burn people
- [what-exists.md](what-exists.md): existing contract-review products
- [who-would-pay.md](who-would-pay.md): segments and willingness to pay

**Read this first.** The research was badly limited by access. Reddit, BiggerPockets, Blind, Indie Hackers, G2, ConsumerAffairs and Clio all blocked the fetch tool. As a result, **no first-person account of someone harmed by a clause they missed was found**. That is a gap in what we could see, not evidence that the pain doesn't exist. Every claim below traces to a URL in the agent files. Where a figure came only from a search snippet, I say so.

---

## Bottom line

**The evidence does not yet support building Redline as described.** It doesn't refute it either. Three findings work against the current hypothesis:

1. **The best-quantified pain isn't a reading problem.** The most-measured harm is freelancer nonpayment, and most freelancers don't have a contract to upload in the first place.
2. **People sign without reading because of time, confusing language and low leverage, not legal cost.** "Plain English" fits that. A per-clause counter-offer assumes leverage that much of the target audience doesn't have.
3. **Free tools already cover two of the four use cases.** LeaseChat covers leases for free, Rocket Lawyer offers free AI review to small businesses, and general chatbots are free.

The one clear opening is **freelancers**. The tools that serve them today are numerous, untested and unreviewed. Even there, nobody has measured willingness to pay.

---

## 1. The three sharpest pain points

None of the quotes below is a personal testimony. Agent 1 found no qualifying first-person account. These are the strongest sourced statements available.

### Pain 1: Freelancers don't get paid
> "One in every two freelancers had trouble collecting payment in 2014 … The average unpaid freelance worker loses almost $6000 annually – which accounts for 13% of their total income."

Source: https://blog.freelancersunion.org/2015/12/10/costs-nonpayment/ (2014 data)

> "Nearly 1 in 4 freelancers have had a hard time getting a client to sign their contract … freelancers reported losing money due to a contract mistake the most."

Source: https://blog.adobe.com/en/publish/2023/08/29/importance-contracts-business-real-world

The nearest first-person evidence is a freelancer who caught an IP clause before signing. He walked away from the job, so he wasn't harmed:
> "The clause said that anything I brought into the project including tools, libraries, and code I'd written before the engagement would become the exclusive property of the client upon completion."

Source: https://dev.to/not_varunkv/the-contract-clause-that-almost-cost-me-my-entire-codebase-j9d

### Pain 2: People don't know what they agreed to
> "More than 75 percent of consumers surveyed did not know whether they were subject to an arbitration clause"

Under 7% understood that such a clause barred them from suing in court. Companies used the clause to block class actions 65% of the time.

Source: https://www.consumerfinance.gov/about-us/newsroom/cfpb-study-finds-that-arbitration-agreements-limit-relief-for-consumers/ (2015, financial products only)

> "nearly one in four business owners surveyed report signing contracts exactly as presented"

Source: https://www.rocketlawyer.com/the-briefing-room/1-in-4-business-owners-sign-contracts-as-is

This is the closest match to Redline's core premise: people sign things they don't understand.

### Pain 3: Recurring charges and junk fees
> "in 2024 the Commission received nearly 70 consumer complaints per day on average, up from 42 per day in 2021."

This is about subscription and auto-renewal practices. Source: https://www.ftc.gov/news-events/news/press-releases/2024/10/federal-trade-commission-announces-final-click-cancel-rule-making-it-easier-consumers-end-recurring

> "Nearly as many (87%) stated that landlords charge excessive late fees"

This comes from a survey of 95 tenant attorneys, not renters. Source: https://www.nclc.org/too-damn-high-new-report-examines-role-of-junk-fees-in-skyrocketing-rents/

---

## 2. Clause types that matter most, ranked

No source ranks clause types against each other. Agent 2 combined numbers that measure different things, so treat this order as indicative only.

| Rank | Clause type | Who it hits | Evidence |
|---|---|---|---|
| 1 | Payment terms / nonpayment / late payment | Freelancers | Quantitative, 2014 data |
| 2 | Auto-renewal / hard-to-cancel subscriptions | Consumers | Quantitative: FTC complaint volume |
| 3 | Lease late fees and junk fees | Renters | Quantitative, but surveys advocates, not renters |
| 4 | Security deposit retention | Renters | Weak: a 2013 survey, snippet only |
| 5 | Mandatory arbitration / class-action waiver | Consumers | How common, and how few people know about it. No complaint counts |
| 6 | Non-competes | Employees | How common only (30M workers). The FTC rule is not in effect |
| 7 | Vague scope / unlimited revisions | Freelancers | Weak: a secondhand statistic |
| — | IP assignment, indemnity, liability caps, kill fees, net-60/90, unilateral termination or change of terms | Various | **No quantitative evidence found.** These appear only on practitioner checklists |

Several of the clauses the hypothesis names (IP assignment, indemnity, liability caps, unilateral termination) had **no frequency evidence at all**. They may still matter, but the research doesn't show it.

---

## 3. Where existing tools are weak

| Weakness | Evidence |
|---|---|
| **Serious tools are built for lawyers, not individuals.** Spellbook is custom-quoted, about $179/user/mo by a third-party estimate. Harvey is estimated at about $1,000–$2,800/seat/mo with about a 20-seat minimum. | what-exists.md §6–7 (estimates unverified) |
| **Freelancer tools are thin and untrusted.** ContractGuard, ClauseShield, ContractRev, ClauseCheck and Contract Review mostly offer 3 free reviews a month and $5–$79/mo paid plans, with almost no independent reviews. No dominant product exists. | what-exists.md §9 |
| **General chatbots invent or reword clauses.** One LLM asked to quote a liability clause verbatim changed its wording, and lawyers warn against relying on chatbots alone. Redline's plan to show the exact source sentence targets this weakness directly. | WorldCC, Lawpath, Construction Dive (snippets) |
| **Rocket Lawyer's free review sent follow-up questions to human lawyers.** In-app Q&A was only "planned" at launch. | rocketlawyer.com newsroom |
| **ToS;DR can't read a document you upload.** It only grades popular websites. | Wikipedia |
| **No accuracy benchmarks exist for any product.** | what-exists.md "not found" |

No product found combines all four of Redline's features: ranked clauses with the source sentence, counter-offer drafts, Q&A answered only from the document, and individual pricing. This comes from reading feature lists, not testing the products.

---

## 4. Who would plausibly pay, and roughly what

**Nobody has measured willingness to pay** for consumer or freelancer contract review: no survey, no pricing test, no stated price. The anchors below are what exists.

| Segment | Size / pain signal | Price anchors | Assessment |
|---|---|---|---|
| **Freelancers** | 72.9M US independent workers in 2025, a broad definition (MBO Partners). Nonpayment pain is quantified. | Lawyer review averages $390 flat (ContractsCounsel, 25 projects). Micro-tools charge $5–$79/mo. Genie AI Pro is $59–$75/mo. | **Most plausible segment.** Clear pain, a real lawyer price to undercut, and a market where no tool has earned trust yet. |
| **Small business owners** | 1 in 4 sign contracts as presented | Business contract review costs about $250–$900 per lawyer (snippet). Rocket Lawyer's AI review is **free**. | A free baseline already exists. |
| **Renters** | Junk fees and deposits, from advocate data | Lease review averages $300 flat (other pages say $450–$650). LeaseChat is **free**. | Weak. It's an occasional need, and a free university-backed tool already does it. |
| **Consumers (terms of service)** | Arbitration unawareness, auto-renewal complaints | None | Weak. Terms of service can't be negotiated, so counter-offers don't apply, and no prices were found. |
| Creators, employees, gig workers | Not researched with usable sources | One "$80/hr" influencer-review listing (snippet) | Unknown |

**Rough price range.** This is an inference from the anchors above, not measured demand. A freelancer tool would compete against a lawyer ceiling of roughly **$300–$400 per document** and existing AI tools at roughly **$10–$75/month**. Free tiers capped at about 3 documents a month are standard. Something in the **$10–$30/month or per-document** range is plausible, but nothing in the research confirms anyone will pay it.

---

## 5. What contradicts the hypothesis

1. **No first-person harm stories were found.** The hypothesis rests on people being hurt by terms they didn't notice. Access blocks prevented any such story from being collected, so this is the single biggest open risk. It needs a rerun with browser access to Reddit and similar sites, or direct interviews.

2. **The most-measured harm, nonpayment, is about enforcement more than understanding.** A client who doesn't pay usually isn't exploiting a clause the freelancer misread. And "only 28% of freelancers use a contract for any given gig" ([Freelancers Union, 2015](https://blog.freelancersunion.org/2015/12/21/why-do-only-28-freelancers-use-contract/)), so most freelance work has no document for Redline to read.

3. **Leverage, not comprehension, is often the blocker.** The Freelancers Union gives client refusal, industry norms and low bargaining power as the reasons freelancers go without contracts. A drafted counter-offer is of no use if the other side won't negotiate, and terms of service can't be negotiated at all.

4. **Cost isn't the stated reason people skip review.** Both surveys that were read cite time pressure and confusing language, not lawyer fees. The only "can't afford attorney fees" claim is a startup founder's assertion. This supports the plain-English summary, but weakens the "cheaper than a lawyer" argument.

5. **Free tools already cover two of the four document types.** LeaseChat (free, University of Chicago) covers leases with red flags, cited Q&A and letter drafting. Rocket Lawyer gives small businesses free AI review. Trying to cover contracts, leases, freelance agreements and terms of service all at once means competing with free products in at least two of them.

6. **There is regulatory and trust risk.** The FTC fined DoNotPay $193,000 over unsupported "robot lawyer" claims. A consumer product that drafts counter-offers will face the same scrutiny.

7. **Most numbers are dated or indirect.** Nonpayment data is from 2014, the deposit survey from 2013, the arbitration study from 2015. The renter data comes from advocates, not renters.

### What the evidence does support
- People really do sign without reading, because of time pressure and confusing language. That supports the plain-English summary.
- Chatbots rewording or inventing clauses is a documented problem. Showing the exact source sentence is a real differentiator.
- The freelancer segment has no trusted product.

### Gaps the next round of research should close
- First-person harm accounts from Reddit, BiggerPockets and Indie Hackers, using browser access.
- Any willingness-to-pay evidence, such as a pricing test, a survey or forum posts quoting lawyer fees.
- Whether freelancers actually receive contracts often enough, for example client-issued contracts from agencies or enterprises, to make a per-document tool worthwhile.
