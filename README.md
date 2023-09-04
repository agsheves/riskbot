# The Riskbot Project
A project to build an interactive risk manager using desktop tools assisted by LLMS and agents. The intent is to provide on-demand data and support for risk managers. Capabilities must include:

- [x] **ALPHA** General guidance on risk and crisis management to answer theoretical queries or questions *(Compelted as stand-alone bot)*
- [ ] **BETA** A risk assessment assistant to help assess the risks associated with threats
- [ ] **GAMMA** General country information
- [ ] **DELTA** Updated country news
- [ ] **EPSILON** Crisis planning tools
- [ ] **ZETA** Reporting and governance reminders and prompts
- [ ] **OMEGA** Is the integration requirement

[The project roadmap is here](https://github.com/users/agsheves/projects/1)

## Status as at  Sunday, August 20, 2023

### ALPHA
*General guidance on risk and crisis management to answer theoretical queries or questions*

**Status** - ✅ 
 - A stand is the first demo of a riskbot from June 2023. The bot runs in [botpress](https://botpress.com/) and there is a demo [here](https://agsheves.github.io/riskbot/). This version used my books (Beyond The Spreadsheet and the risk management system build handbook) as data sets. As a fallback, the model would pass the request to ChatGTP if the model returned the answer 'I don't know' from a search of the built-in datasets.
 - This chatbot has been integrated into the DCDR and CrisisDojo tools and woks reasonably well and consistently. See the bot on [CrisisDojo here](https://crisisdjo.ai)

---

### BETA
*A risk assessment assistant to help assess the risks associated with threats*

---

### GAMMA
*General country information*

---

### DELTA
*Updated country news*

---

### EPSILON
*Crisis planning tools*

**Status** - ✅ *as standalone tool*
 - CrisisDojo tools work reasonably well and consistently. See the tools on the [CrisisDojo app here](https://app.crisisdjo.ai)

 ---

### ZETA
*Reporting and governance reminders and prompts*

---

Here's a sketch of how the components will fit together

```mermaid
flowchart TD
    A[AIRMS\n AI Risk Management System] -->|Speed up and simplify\nrisk-based decision making| B(Functional tool set)
    B --> C{Generation}
    B --> G{Analysis}
    B --> H{Automation}
    B --> P{Operations}
    C --> E[Threat Scenario\nGeneration\nfa:fa-check-square]
    C --> D[Exercise Material\nGenerations\nfa:fa-check-square]
    G --> I[News feed\nfa:fa-check-square]
    G --> J[Country Data\nfa:fa-minus-square]
    G --> K[Country Risk\nRating\nfa:fa-minus-square]
    H --> L[Governance Report\nCompliation\nfa:fa-minus-square]
    H --> M[Trigger Alerts\nCompliation\nfa:fa-check-square]
    M --> Q
    H --> O[Crisis Response\nToolkit\nfa:fa-check-square]
    O --> Q
    P --> Q[Crisis Response\nToolkit\nfa:fa-minus-square]
    E --> R(Risk Assessment\nToolkit\nfa:fa-check-square)
    I --> R
    J --> R
    K --> R
```

### OMEGA
*Integration*



