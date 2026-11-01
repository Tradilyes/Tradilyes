### Ilyes M. Trad

I design AI workflows for in-house legal teams — in Arabic, French and English, for the Gulf and
France — and I measure them against the strongest models. Background in the courts and in
legal-tech design; lecturer and doctoral researcher in law and artificial intelligence (MANAR
University).

**How I build.** A language model does the reading: it finds the facts wherever they are phrased,
judges what the words mean, explains. Code does what code does better: the rules of the law and of
the company's playbook, with a source for each; the checks that do not tire (two language versions,
deadlines, quotes); a routing that stays the same from one day to the next. Where the model doubts a
rule, it writes a note for the lawyer instead of overriding it.

**What it gives, measured** (synthetic documents, answer keys written by hand, every run public):

| Task for an in-house team | Strongest model alone (Claude Opus 5.5) | My system with a small model (Claude Haiku 5.5) |
|---|---|---|
| Triage 12 NDAs, 7 in English and Arabic | 24 / 24 right routings, with Anthropic's own skill · $0.055 each | 24 / 24 · $0.0045 each |
| Review 8 AI vendors against policy and Gulf/EU law | 14 / 16 right decisions · $0.060 each | 15 / 16 · $0.0045 each |
| Compare very long bilingual contracts (1,151 clauses) | 59 / 60 discrepancies · $1.12 each | 60 / 60 · $0.22 each |
| Gulf data-protection rules in force on 1 November 2026 | 11 / 20; 19 / 20 with web search ($0.59) | 20 / 20 · $0.004 |

Where the strongest model is already excellent — short NDAs — the tables say so. The gain is
reliability at a fraction of the cost, verifiable quotes, and the law that changed after the model
was trained.

**[courtproof](https://github.com/Tradilyes/courtproof)** — contract review in Arabic, English and
French: an NDA-triage agent, bilingual parity, laws repealed or renumbered (UAE Civil Transactions
Law, June 2026), exact Gregorian and Hijri deadlines.

**[compliance-atlas](https://github.com/Tradilyes/compliance-atlas)** — vendor intake for in-house
teams: can we give this AI vendor our data? On a sourced atlas of ten data-protection regimes of the
Gulf and the EU, and the EU AI Act.

**[travail-fr](https://github.com/Tradilyes/travail-fr)** — French employment-litigation assistant
for Claude Code and Codex: verified official sources, local calculations, deadlines, drafting, an
independent reviewer.

Each project comes with playbooks a legal team can follow: a four-week pilot with success measures
set in advance, a template sweep after a law is renumbered, a hosting answer for a new AI vendor,
the first 24 hours of a data breach, due diligence on a legal-AI vendor, an AI-use policy.

I write with the help of AI assistants and publish the tests that check the result.
