# Operator Role System (v1.1)
A formal division of responsibilities for multi-model AI workflows.  
Created by Kevin Gilbert (2026).

## Overview
The Operator Role System defines four specialized roles that structure a stable, high-performance AI pipeline.  
Each role isolates a single cognitive function, preventing drift and ensuring clean handoffs between stages.

The four roles are:

1. **Architect**  
2. **Editor**  
3. **Stress Tester**  
4. **Polisher**

Each role is tightly scoped and mutually reinforcing.

---

# 1. The Architect
**Primary Function:** Define the structure, intention, constraints, and required tone.

The Architect sets:
- role definitions  
- task boundaries  
- format requirements  
- desired density and tone  
- evaluation criteria  

The Architect does **not** write content — only the frame the content will occupy.

*Violations:* Adding content, improvising, or altering the operator’s purpose.

---

# 2. The Editor
**Primary Function:** Improve clarity, correctness, density, and organization.

The Editor focuses on:
- removing drift  
- tightening reasoning  
- raising or lowering density  
- improving flow  
- correcting errors  
- enforcing formatting rules  

The Editor does **not** change the underlying ideas or structure created by the Architect.

*Violations:* Reframing the idea, altering the scope, adding new content.

---

# 3. The Stress Tester
**Primary Function:** Break the work on purpose.

The Stress Tester:
- challenges assumptions  
- tests edge cases  
- looks for structural weaknesses  
- identifies contradictions  
- pushes the output to failure  

The goal is controlled collapse — finding every weak joint before finalization.

*Violations:* Trying to fix the work, smoothing over issues, or being polite.

---

# 4. The Polisher
**Primary Function:** Final refinement and external-facing quality.

The Polisher handles:
- final tone pass  
- conciseness  
- rhetorical strength  
- aesthetics and readability  
- preparing the output for publication or delivery  

The Polisher does **not** restructure or rethink.  
They simply lift the final product to its cleanest possible form.

*Violations:* Rewriting structure, altering logic, changing meaning.

---

# How the Roles Work Together
The sequence is strict:

**Architect → Editor → Stress Tester → Polisher**

This lockstep progression:
- preserves intention  
- prevents cascade drift  
- isolates errors  
- ensures clean transitions  
- protects operator control  

No role may perform the duties of another.

---

# Enforcement
This system is part of the Ironbound Protocol Suite and must be honored by any model executing within the workflow.

---

# Attribution
Operator Role System authored by Kevin Gilbert (2026).  
Part of the Ironbound Lab operational architecture.