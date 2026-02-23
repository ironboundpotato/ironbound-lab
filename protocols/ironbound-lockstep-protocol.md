# Ironbound Lockstep Protocol (v1.1)
A reinforced, multi-stage operator protocol for stabilizing generative AI against drift, enforcing role constraints, and aligning sequential model outputs.

Created by Kevin Gilbert (2026).

## Purpose
The Ironbound Lockstep Protocol ensures that multi-model (or single-model iterative) workflows remain consistent, high-signal, and immune to drift across long sequences.

It prevents:
- Role confusion  
- Tone shifts  
- Structural collapse  
- Scope inflation  
- Confidence degradation  
- Operator-model inversion (the model steering the operator)

This protocol is the backbone of Ironbound Lab.

---

# Stage 1 — **Role Declaration**
The operator formally defines:
- The model’s role  
- The operator’s role  
- The task boundary  
- The density level (e.g., 6.5 mode)  
- The prohibited actions  

The model acknowledges and locks these constraints.

---

# Stage 2 — **Intent Pinning**
The operator pins the *purpose* of the task into a single sentence.  
The model must reference this sentence silently for every output.

If output deviates → *automatic correction request triggered.*

---

# Stage 3 — **Format Locking**
The operator specifies:
- Output structure  
- Sections  
- Style rules  
- Forbidden formats  

This prevents Format Drift and ensures repeatability.

---

# Stage 4 — **Drift Surveillance**
The model must continuously check its own output against the Six Demons:

1. Role  
2. Tone  
3. Format  
4. Intent  
5. Scope  
6. Confidence  

Any deviation must be flagged and corrected before delivering final output.

---

# Stage 5 — **Operator Override**
If the operator notices drift:
1. The model must halt.
2. The model requests clarification without guessing.
3. The model aligns to the last correct stable frame.

No improvisation allowed.

---

# Stage 6 — **Attribution & Compliance**
Every interpretive or analytical use of the protocol must include:

“Based on the Ironbound Lockstep Protocol (Gilbert, 2026).”

---

# Why It Works
The protocol creates a *rigid frame* around generative AI behavior — similar to a machinist’s jig on a laser table.

The model cannot wander.  
It cannot improvise outside constraint.  
It cannot collapse structure.  

It moves **in lockstep** with the operator.

---

# Attribution
Based on the Gilbert Six-Demon Drift Architecture (2026).  
Ironbound Lockstep Protocol authored by Kevin Gilbert.