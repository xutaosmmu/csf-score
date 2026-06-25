# CSF Score Calculator

> **English** · [中文](README.zh.md)

**Cerebrospinal System Failure Score (CSF Score)**  
A pre-specified prognostic scoring framework for leptomeningeal metastasis (LM) from non-small cell lung cancer (NSCLC), developed from a neurosurgical perspective to support exploratory risk stratification and external validation.

> The acronym **CSF** is intentional: it designates both *Cerebrospinal System Failure*, the conceptual framework, and *cerebrospinal fluid*, the biological medium at the center of the disease process.

> **Research use only.** This calculator has not undergone external multicenter validation and should not be used as a standalone clinical decision-making tool.

---

## Conceptual Framework

The CSF Score conceptualizes leptomeningeal metastasis not merely as tumor dissemination, but as a progressive failure of the CSF circulatory system. Tumor cells seeding the subarachnoid space may obstruct CSF outflow pathways, elevate intracranial pressure, impair intrathecal drug distribution, and contribute to neurological decline.

This framework has direct relevance to neurosurgical assessment. Ommaya reservoir placement can provide access for intrathecal therapy and serial CSF sampling, while ventriculoperitoneal shunting may relieve symptomatic hydrocephalus in selected patients. The CSF Score was developed as a research framework to explore how functional status, molecular treatment access, anatomical burden, CSF dynamics, and intrathecal biological activity jointly shape prognosis.

---

## Scoring System

Total score range: **0–10 points** across five dimensions.

A **KPS-based gatekeeper** operates in parallel: patients with KPS <60 are classified directly as High Risk regardless of total score, reflecting the clinical consensus that severely impaired functional status limits the benefit of aggressive intervention.

---

### D1 · Host Resilience (0–3 pts)

Captures the patient's capacity to tolerate disease and treatment.

**Karnofsky Performance Status (KPS)**

- ≥80: normal activity, minor symptoms → **0 pts**
- 60–70: ambulatory, requires occasional assistance → **1 pt**
- <60: requires considerable assistance → **2 pts + gatekeeper activation**

**LM-specific Core Neurological Deficit (LM-CND)**  
Defined as at least one major cranial nerve or spinal cord deficit directly attributable to LM, not pre-existing or caused by parenchymal metastases. Examples include CN VI/VII palsy, CN VIII hearing loss, limb weakness from spinal LM, or cauda equina syndrome.

- Absent → **0 pts**
- Present → **1 pt**

**Extracranial Disease Progression at LM diagnosis**  
Reflects systemic disease status at the time of the qualifying lumbar puncture.

- Stable or responding → **0 pts**
- Progressive → **1 pt**

---

### D2 · Molecular Engine (0–2 pts)

Captures the availability of CNS-penetrant targeted therapy with LM-specific clinical evidence. The score reflects **therapeutic access**, not mutation status alone — currently available CNS-active targeted therapy is the dominant prognostic driver.

- **Effective CNS-active TKI available → 0 pts**  
  e.g. 3rd-generation TKI for EGFR (osimertinib, aumolertinib, furmonertinib), including switch after 1st/2nd-gen TKI with T790M+ or dose escalation; lorlatinib for ALK; entrectinib/lorlatinib/repotrectinib for ROS1; targeted therapy for other actionable alterations (MET, RET, BRAF, NTRK).

- **Suboptimal or uncertain CNS activity → 1 pt**  
  e.g. EGFR after 1st/2nd-gen TKI failure switching to Amivantamab + pemetrexed + platinum; ALK after 1st/2nd-gen TKI failure switching to alectinib/ceritinib/brigatinib; HER2 or other alterations with limited CNS evidence.

- **No effective CNS-active option → 2 pts**  
  e.g. EGFR post-3rd-gen TKI resistance with no CNS-active regimen; ALK fully resistant; ROS1 fully resistant; or KRAS, STK11, and other non-AGA patients without approved CNS-active targeted therapy — reliant on chemotherapy or immunotherapy.

---

### D3 · Anatomical Burden (0–2 pts)

Captures structural tumor load within the CSF compartment and brain parenchyma.

**MRI Leptomeningeal Enhancement Pattern**  
Classified according to the EANO-ESMO typology.

- No enhancement or Linear enhancement (Type A) → **0 pts**
- Nodular or combined / Type B–C → **1 pt**

**Concurrent Parenchymal Brain Metastases**

- 0–3 lesions → **0 pts**
- ≥4 lesions or miliary pattern → **1 pt**

---

### D4 · Fluid Dynamics (0–2 pts)

Captures the physical integrity of CSF circulation, the dimension most directly related to CSF-directed neurosurgical assessment.

**Evans Index (EI)**  
Measured as the maximum width of the frontal horns divided by the maximum internal biparietal skull diameter on the same axial MRI slice.

- EI <0.27 → **0 pts**
- EI ≥0.27 → **1 pt**

**CSF Opening Pressure / Symptomatic Hydrocephalus**  
Measured at diagnostic lumbar puncture in the lateral decubitus position. Score 1 point if either criterion is met.

- OP ≤250 mmH₂O and no symptomatic hydrocephalus → **0 pts**
- OP >250 mmH₂O or symptomatic hydrocephalus requiring neurosurgical consultation → **1 pt**

> The 250 mmH₂O threshold represents a neurosurgically relevant level of intracranial hypertension that may prompt evaluation for CSF diversion in the appropriate clinical context.

---

### D5 · Biological Toxicity (0–1 pt)

Captures active intrathecal tumor secretion using a CSF-specific biological activity measure that does not require advanced molecular diagnostics.

**Tumor Marker Index (TMI)**  
TMI = CSF tumor marker concentration ÷ paired serum marker concentration from the same diagnostic episode.

Marker hierarchy:

- CEA for adenocarcinoma
- CYFRA 21-1 for squamous cell carcinoma
- NSE for tumors with neuroendocrine features

Score 1 point only if **both** criteria are met:

- TMI >3
- Absolute CSF value exceeds the laboratory upper reference limit

TMI >3 was selected to reduce the likelihood that the signal reflects passive blood-CSF barrier leakage alone.

---

## Risk Stratification

| Risk Group | Score |
|---|---:|
| **Low** | 0–2 |
| **Intermediate** | 3–6 |
| **High** | ≥7, or KPS <60 |

This score is a structured prognostic assessment tool. Clinical management decisions should be guided by multidisciplinary evaluation and individualized clinical judgment.

---

## Calculator

Available in English and Chinese. Both versions are single self-contained HTML files with no external dependencies. They can be opened locally in any modern browser or deployed online.

- [English version](index.html)
- [中文版](index-zh.html)

---

## Version

**CSF-Score v1.0**  
Corresponding to the preprint version, May 2026.

A DOI link will be added after the preprint is available.

---

## Citation

Citation information will be updated upon preprint release or journal publication.

Please cite the original publication when using this framework in research.

---

## Disclaimer

This calculator is provided for **research and exploratory risk assessment only**. It has not undergone external multicenter validation and should not be used as a standalone clinical decision-making tool. It is not a substitute for clinical judgment or multidisciplinary evaluation.
