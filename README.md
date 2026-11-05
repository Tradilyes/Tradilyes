### Ilyes M. Trad

Doctoral researcher in law at MANAR University (artificial intelligence, legal technology, digital
regulation) and lecturer. Arabic, French, English.

I build AI assistants for legal work, and I study how AI systems read and apply legal rules, in
Arabic and French as well as English.

#### Legal AI assistants for French law

Each assistant installs in the Claude app (Code tab) and in Claude Code; in Codex, with its skills and
local tools. Amounts and dates come from local calculation tools, never from memory; quotations are
checked word for word against their source with a local tool (in contrats-fr, a hook sends back any
answer that quotes without that check); and an independent reviewer agent re-reads each document
before it leaves.

| | What it does | Availability |
|---|---|---|
| **travail-fr** 0.4.5 | Employment-law litigation: intake, deadlines, claims calculated with 32 local tools, official sources, pleadings and letters, review from the opponent's side. For lawyers on either side, in-house teams and HR, union advisers, and employees in plain language. | free, MIT licence; release in preparation; demonstration on request |
| **contrats-fr** 0.1.0 | Contract law: each contract read clause by clause from the client's side; applicable law and court, EU texts and AI Act classification, late-payment penalties, limitation periods, renewal notices, public-procurement remedies (22 local tools); redlines as tracked changes in Word. Each result states where its rule comes from and whether it was checked against the official text. | free, MIT licence; release in preparation; demonstration on request |
| **STAXIS** | The professional editions of both assistants, built on a structured reading of French case law, decision by decision (pilot in progress). | made to order |

French law forbids reusing the identity of judges and court clerks to evaluate, analyse, compare or
predict their professional practice (Article L. 10 of the Code of Administrative Justice; Article
L. 111-13 of the Code of Judicial Organisation). These tools refuse any such request, and go further:
no statistics by named court, chamber or bench either.

#### Research

Each study is registered before it is run, and its data and code are public, so that anyone can
check or re-analyse it.

**[tamyiz](https://github.com/Tradilyes/tamyiz)**, the current programme.

- *Equal before the machine?* (Study B, registered on 4 November 2026 before any run). The same 54
  labour-law questions on the United Arab Emirates, Saudi Arabia and France, asked in Arabic, French
  and English, each with one answer checked against the official text. Does the answer an AI gives
  depend on the language of the question? In 2,106 answers from three Claude models, it did not,
  beyond chance; what mattered was the date: on rules changed since 2024, the smaller models were
  often wrong, and each wrong answer on a rule with a known former value gave that former value.
- Pilot on contract playbooks (November 2026): four AI configurations were unanimous on ten clauses
  at the edge of a playbook and, twice, unanimous against the stated intention. With ten questions
  and one provider, that is a reason for a study, not a result.

Two instruments of the programme, courtproof (checks for Arabic–English contracts and Gulf legal
references) and compliance-atlas (dated, sourced facts on Gulf and EU data-protection law), will be
published once their documentation meets the same standard.

#### Contact

ilyes.trad95@gmail.com
