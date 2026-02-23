# Debugging Playbook — Ironbound Ops
Author: Kevin Gilbert (2026)  
Purpose: Unified troubleshooting framework for AI system stability.

---

# 1. Onset Recognition  
How to detect when something is going wrong.

Early signals:
- unexpected tone shift  
- new assumptions appearing  
- over-elaboration or filler  
- contradictions inside output  
- sudden confidence increase  
- refusal patterns  
- hallucinated structure  

Action:
```
CHECK: drift
```

Deliverables:
- drift report
- identified cracks
- section-level instability

---

# 2. Isolation Procedure  
Find the exact failure point.

Steps:
1. freeze the output  
2. split into sections  
3. identify the first divergence  
4. trace upstream to initiating instruction  
5. map crack → constraint violated  

Template:
```
ISOLATE: [problem segment]

Report:
- root cause
- violated constraint
- suggested fix
```

---

# 3. Stabilization Protocol  
Apply the minimum correction.

Rules:
- fix only the broken section  
- do not rewrite the entire draft  
- restore constraints before content  
- reset role if needed  

Command:
```
RESET ROLE: Editor
STABILIZE: [segment]
```

---

# 4. Hard Reset Procedure  
When the system has fully derailed.

Use when:
- multiple demons activated  
- tone or format unrecoverable  
- scope exploded  
- chain-of-thought leaked  
- contradictions cascade  

Command:
```
SYSTEM RESET
LOAD: last stable outline
REBUILD: from section [X]
```

---

# 5. Prevention Framework  
How to stop drift before it starts.

Checklist:
- explicit role  
- explicit constraints  
- section order fixed  
- limited scope  
- no open-ended prompts  
- density target defined  
- single output type  

Template:
```
Before running task:
APPLY: operator-checklist
```

---

# Attribution
Debugging Playbook authored by Kevin Gilbert (2026).  
Part of the Ironbound Ops Suite.