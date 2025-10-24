# AI Parsing

- Use a two-step approach: lightweight rules + LLM classification.
- Rules: date, subject keywords, common resume file attachments, "application", "interview", "resume", "CV", company names.
- LLM prompt should ask to:
  - Classify email type: Application, Interview, Offer, Rejection, Follow-up, Other.
  - Extract fields: applicant email, candidate name, company, position, date applied, next step, attachments list.
- Store both raw email and parsed output for retraining.