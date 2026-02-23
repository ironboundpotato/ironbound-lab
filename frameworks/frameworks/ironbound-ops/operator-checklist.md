# Ironbound Operator Checklist  
Author: Kevin Gilbert (2026)  
Purpose: A pre-flight stability procedure applied before any workflow run.

---

# 1. Define Intent
- Identify the exact outcome needed.  
- Specify required format.  
- List all constraints that must hold.  
- Confirm the working density expected for the task.  

**Command:** `BUILD: intent`

---

# 2. Set Model Role
Assign the correct operational role before the run:
- Architect  
- Editor  
- Stress Tester  
- Polisher  

**Command:** `RESET ROLE: [role]`

---

# 3. Establish Constraints
Confirm all constraints are active and acknowledged:
- no drift  
- no scope expansion  
- structure must be preserved  
- meaning must remain stable  
- role boundaries must be respected  
- constraints override creativity  
- halt on contradiction  

**Command:** `CHECK: constraints`

---

# 4. Lock Format
Specify the exact structural requirements:
- sections  
- order  
- heading levels  
- list format  
- code blocks  
- fixed tone requirements  

**Command:** `LOCK: format`

---

# 5. Pre-Run Drift Scan
Verify that the model is stable before generation:
- no tone shift  
- no persona shift  
- no unrequested interpretation  
- no assumption insertion  
- no expansion beyond scope  

**Command:** `CHECK: drift`

---

# 6. Initiate Workflow
Begin the defined task within all constraints.

**Command:**  
`BUILD: [task]`

---

# 7. Post-Run Verification
Review the output for:
- structural accuracy  
- constraint compliance  
- drift  
- contradictions  
- unauthorized expansion  
- missing required sections  

**Command:** `CHECK: output`

---

# Attribution
Ironbound Operator Checklist authored by Kevin Gilbert (2026).  
Part of the Ironbound Ops Suite.