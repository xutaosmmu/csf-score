# CSF Score Calculator
 
**Cerebrospinal System Failure Score (CSF Score)**  
A prognostic scoring system for leptomeningeal metastasis (LM) from non-small cell lung cancer (NSCLC), developed from a neurosurgical perspective to guide treatment decision-making at the bedside.
 
> The acronym **CSF** is intentional: it designates both *Cerebrospinal System Failure* — the conceptual framework — and *cerebrospinal fluid*, the biological medium at the center of the disease process.
 
---
 
## Conceptual Framework
 
The CSF Score conceptualizes leptomeningeal metastasis not merely as tumor dissemination, but as a **progressive failure of the CSF circulatory system**. Tumor cells seeding the subarachnoid space trigger a cascade: they obstruct CSF outflow pathways, elevate intracranial pressure, impair drug delivery to the intrathecal compartment, and ultimately render the CSF system unable to sustain normal neurological function.
 
This framework has direct implications for neurosurgical decision-making. Two interventions — **Ommaya reservoir placement** (for intrathecal therapy access and CSF sampling) and **ventriculoperitoneal shunt (VPS) insertion** (for symptomatic hydrocephalus) — are potentially modifiable determinants of patient trajectory. Yet no existing tool helps the neurosurgeon determine, at the time of consultation, which patients are most likely to benefit from these procedures. The CSF Score was built to fill this gap.
 
---
 
## Scoring System
 
Total score range: **0 – 10 points** across five dimensions.
 
A **KPS-based gatekeeper** operates in parallel: patients with KPS < 60 are classified directly as High Risk regardless of total score, reflecting the clinical consensus that these patients are not candidates for aggressive intervention.
 
---
 
### D1 · Host Resilience (0 – 3 pts)
 
Captures the patient's capacity to tolerate disease and treatment.
 
**Karnofsky Performance Status (KPS)**
- ≥ 80: normal activity, minor symptoms → **0 pts**
- 60–70: ambulatory, requires occasional assistance → **1 pt**
- < 60: requires considerable assistance → **2 pts + gatekeeper activation**
 
**LM-specific Core Neurological Deficit (LM-CND)**  
Defined as at least one major cranial nerve or spinal cord deficit directly attributable to LM — not pre-existing or from parenchymal metastases (e.g. CN VI/VII palsy, CN VIII hearing loss, limb weakness from spinal LM, cauda equina syndrome).
- Absent → **0 pts**
- Present → **1 pt**
 
**Extracranial Disease Progression at LM diagnosis**  
Reflects remaining systemic treatment options at the time of the qualifying lumbar puncture.
- Stable or responding → **0 pts**
- Progressive → **1 pt**
 
---
 
### D2 · Molecular Engine (0 – 2 pts)
 
Captures the availability of CNS-penetrant targeted therapy with LM-specific clinical evidence. Score reflects **therapeutic access**, not mutation status alone — treatment generation supersedes raw genomic status as the prognostic driver in the modern era.
 
- Effective CNS-active TKI available (e.g. 1st-line osimertinib for EGFR-sensitizing mutations; lorlatinib for ALK/ROS1) → **0 pts**
- Suboptimal or uncertain CNS activity (e.g. later-line TKI after resistance, limited LM-specific data) → **1 pt**
- No effective CNS-active option (non-AGA patients, or exhausted targeted therapy lines) → **2 pts**
 
---
 
### D3 · Anatomical Burden (0 – 2 pts)
 
Captures structural tumor load within the CSF compartment and brain parenchyma.
 
**MRI Leptomeningeal Enhancement Pattern** (EANO-ESMO typology)
- Linear / Type A: thin, smooth enhancement — diffuse seeding without discrete deposits → **0 pts**
- Nodular or combined / Type B–C: discrete nodular deposits, higher risk of CSF flow obstruction → **1 pt**
 
**Concurrent Parenchymal Brain Metastases**
- < 4 lesions → **0 pts**
- ≥ 4 lesions or miliary pattern → **1 pt**
 
---
 
### D4 · Fluid Dynamics (0 – 2 pts)
 
Captures the physical integrity of CSF circulation — the dimension most directly relevant to neurosurgical decision-making.
 
**Evans Index (EI)**  
Measured as the maximum width of the frontal horns divided by the maximum internal biparietal skull diameter on the same axial MRI slice. Interobserver agreement κ = 0.63 (Le Rhun et al., Neuro-Oncology 2022).
- EI < 0.27 → **0 pts**
- EI ≥ 0.27 → **1 pt** (threshold validated as prognostically significant in LM by Le Rhun et al., Neurology 2024)
 
**CSF Opening Pressure / Symptomatic Hydrocephalus**  
Measured at diagnostic lumbar puncture (lateral decubitus, fully relaxed). Score 1 pt if *either* criterion is met:
- OP ≤ 250 mmH₂O and no symptomatic hydrocephalus → **0 pts**
- OP > 250 mmH₂O *or* symptomatic hydrocephalus requiring neurosurgical consultation → **1 pt**
 
> The 250 mmH₂O threshold represents the neurosurgically relevant level of frank intracranial hypertension at which VPS placement is typically considered.
 
---
 
### D5 · Biological Toxicity (0 – 1 pt)
 
Captures the degree of active intrathecal tumor secretion using a CSF-specific biological activity measure that does not require advanced molecular diagnostics.
 
**Tumor Marker Index (TMI)**  
TMI = CSF tumor marker concentration ÷ paired serum marker concentration (same diagnostic episode).  
Marker hierarchy: CEA (adenocarcinoma) → CYFRA 21-1 (squamous) → NSE (neuroendocrine features).
 
Score 1 pt only if **both** criteria are met:
- TMI > 3 (distinguishes active intrathecal secretion from passive blood-CSF barrier leakage, which typically produces ratios < 2–3)
- Absolute CSF value exceeds the laboratory upper reference limit
 
---
 
## Risk Stratification and Clinical Interpretation
 
| Risk Group | Score | Median OS | Clinical Approach |
|------------|-------|-----------|-------------------|
| **Low** | 0 – 2 | 20.5 months | Ommaya reservoir placement recommended — dual purpose: intrathecal therapy conduit and longitudinal CSF/TMI monitoring port. Aggressive TKI optimization. |
| **Intermediate** | 3 – 6 | 12.6 months | MDT evaluation. Consider Ommaya if molecular therapy is available. Assess VPS candidacy if symptomatic hydrocephalus present. |
| **High** | ≥ 7, or KPS < 60 | 4.5 months | Early goals-of-care discussion. Palliative VPS for symptomatic hydrocephalus. Aggressive intrathecal chemotherapy unlikely to provide meaningful benefit. |
 
---
 
## Calculator
 
Available in English and Chinese. Both versions are single self-contained HTML files with no external dependencies — download and open locally in any modern browser, or access online.
 
- 🌐 [English version](index.html)
- 🌐 [中文版](index-zh.html)
 
---
 
## Citation
 
> [To be updated upon publication]
 
Please cite the original publication when using this tool in clinical practice or research.
 
---
 
*For research and clinical decision support only. Not a substitute for clinical judgment or multidisciplinary evaluation.*
