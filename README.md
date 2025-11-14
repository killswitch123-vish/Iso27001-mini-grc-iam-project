# ISO 27001 Mini GRC & IAM Project

This mini-project is part of my **100-day journey into GRC, IAM, and AI security**.  
The goal was to practise reading **ISO 27001:2022 Annex A controls**, translate them into
plain language, and connect them to **realistic risks and mitigations**.

---

## Scope

This project focuses on a small but important subset of Annex A controls:

- **A.5.3 – Segregation of Duties**
- **A.5.15 – Access Control**
- **A.5.16 – Identity Management**
- **A.6.3 – Information Security Awareness, Education & Training**
- **A.6.6 – Confidentiality / Non-disclosure Agreements**
- **A.8.2 – Privileged Access Rights**
- **A.8.5 – Secure Authentication**
- **A.8.15 – Logging**
- **A.8.24 – Use of Cryptography**
- **A.8.32 – Change Management**

These were selected to line up with **GRC + IAM** responsibilities (access governance, identity lifecycle,
logging, training, crypto, etc.).

---

## Files in this repo

### `iso27001-control-mapping.xlsx`
A table where I:

- interpret each control in my own words  
- describe how a company could realistically implement it  
- explain the **risk if the control is missing**

Columns:

- Control ID  
- Control Name  
- My Explanation  
- How the Company Implements It  
- Risk if Missed  

### `iso27001-risk-register.xlsx`
A small **risk register** that links real risks to the controls above.

Columns:

- Risk ID  
- Risk Description  
- Likelihood / Impact / Risk Rating  
- Linked Control(s)  
- Mitigation  
- Status (Open, In-progress, Mitigated)

The risks include things like:

- weak authentication  
- broken access control  
- orphaned accounts  
- lack of logging  
- weak encryption  
- poor user awareness

---

## 🎯 What I practised

- Reading ISO 27001:2022 Annex A and extracting the **intent** of each control  
- Translating audit-style language into **clear, practical explanations**  
- Mapping risks → controls → mitigations  
- Thinking like a **GRC / IAM analyst**, not just memorising definitions  

---

## 🚀 Next steps

- Expand this to cover more Annex A controls (suppliers, third parties, backups, etc.)
- Turn some of these ideas into a **Lemonav-style IAM governance scenario**
- Build a simple dashboard to visualise risk ratings over time

If you have feedback or suggestions, feel free to open an issue or message me on LinkedIn.
