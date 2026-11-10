# 2026-09-15 — CQA Presentation Preparation

> **Created:** Unrecorded  
> **Last updated:** 2026-10-18  
> **Version:** 0  
> **Status:** Draft  
> **Course:** Introduction to Medical Product Regulatory Science with Quality by Design  
> **Topic:** Potential CQAs and CQA Criticality Ranking for the atorvastatin group presentation  
> **Source or context:** Updated two-slide version supplied as screenshots on 2026-09-15. Replaces the active 2026-09-13 preparation. Content developed from [[2026-09-08-atorvastatin-group-work]].  
> **Tags:** #DRAP-5001 #atorvastatin #group-work #CQA #QbD #presentation

## Core presentation logic

The section follows one simple chain:

> The QTPP describes the product we want to achieve. The potential CQAs identify the measurable product properties needed to achieve it. The criticality ranking indicates where stronger controls and further knowledge are needed.

## Opening before Slide 1

> Building on the QTPP introduced in the previous slide, the next step is to translate our product targets into measurable quality attributes. These are the potential Critical Quality Attributes, or CQAs.
>
> In simple terms, a CQA is a property of the product that must remain within an appropriate limit or range to ensure the desired product quality.
>
> For our 20-milligram immediate-release atorvastatin tablet, we identified seven potential CQAs. I will briefly explain what each one measures and why it matters.

This opening intentionally gives only a short reminder of the definition because the seminar audience is already familiar with CQAs.

## Slide 1 — Potential CQAs

### 1. Identity

> Starting with identity, this confirms that the active ingredient present in the product is actually atorvastatin. A mix-up involving the wrong drug substance would make the batch unacceptable and could directly endanger patients.

**Why it matters:** Identity answers the most fundamental product question: is this the intended medicine?

### 2. Assay

> Assay measures the average amount of atorvastatin in the tablets and confirms that it corresponds to the labelled 20-milligram strength. Too little could reduce efficacy, while too much would give unintended exposure.

**Why it matters:** The product must deliver the labelled strength at batch level.

### 3. Uniformity of dosage units

> A batch can have the correct average assay while some individual tablets contain too much or too little drug. Uniformity testing therefore confirms that each tablet provides a consistent dose.

**Why it matters:** Assay cannot by itself show whether every patient receives a consistent dose from each tablet.

### 4. Dissolution

> Dissolution measures how much and how quickly atorvastatin is released from the tablet. This is especially important because atorvastatin calcium has limited aqueous solubility. Particle properties, formulation, lubrication and compression may all affect its release.

**Why it matters:** Inadequate or variable dissolution may change the amount of drug available for absorption and therefore affect product performance.

### 5. Related substances and degradation products

> Related substances can originate from API synthesis, while degradation products can form during tablet manufacture or storage. Excessive levels may affect safety and can indicate that the product is unstable.

**Why it matters:** The company must control both the initial impurity profile and any deterioration during the proposed shelf life.

### 6. Water content

> Excess moisture may accelerate degradation or change tablet properties, including dissolution. Water content also helps us evaluate whether the proposed moisture-protective packaging is adequate.

**Why it matters:** Moisture connects formulation and process control with stability, storage and packaging.

### 7. Microbial limits

> Microbial limits confirm that the non-sterile tablet has acceptable microbial quality and does not contain unacceptable levels of microorganisms or specified objectionable organisms.

**Why it matters:** A non-sterile product does not need to be sterile, but it still requires appropriate microbiological quality. For a dry oral solid, testing may only be reduced or omitted when process knowledge, component controls and validation data provide scientific justification.

## How to use the QTPP-to-CQA mapping box

Do not read every mapping aloud. Use one example to demonstrate the logic:

> For example, the target strength maps to identity, assay and uniformity of dosage units. This shows that the CQAs come directly from the intended product profile rather than being selected arbitrarily.

If time permits, add a second example:

> The shelf-life and packaging target maps to water content, assay, dissolution and degradation products because all four may change during storage.

## Closing Slide 1

> Together, these attributes cover the identity, dose, performance, purity and stability of the product. The mapping on the right shows how they come directly from the targets established in our QTPP.

## Transition to Slide 2

> After identifying the potential CQAs, the next question is whether they all require the same level of attention. We therefore made a preliminary criticality ranking based on the severity of a possible failure and the uncertainty in our current knowledge.

## Slide 2 — CQA Criticality Ranking

### Method statement

> Severity represents the possible effect of failure on patient safety, efficacy or product quality. Uncertainty represents gaps in our present product and process knowledge. These are preliminary qualitative judgements that should be reviewed when development and stability data become available.

Describe the table as a **preliminary criticality or control-priority ranking**. A complete ICH Q9 risk assessment would also consider probability or likelihood.

### 1. Identity — High priority

> Identity has high severity because the wrong active ingredient would directly affect patient safety and make the product unacceptable. Medium uncertainty reflects the limited product, process and supply-chain knowledge available at this stage.

**Control explanation:** The wording on the slide, “control at drug-substance step,” is too narrow. If the deck cannot be changed, say:

> We control identity at the drug-substance stage and verify it again in the finished drug product.

### 2. Related substances and degradation products — High priority

> This attribute has high severity because excessive or insufficiently characterised impurities may affect safety or quality. Medium uncertainty remains because the complete impurity and degradation profile develops through process and stability studies.

**Control explanation:** Control the drug substance and drug product at release, then continue to monitor degradation products during stability studies.

### 3. Uniformity of dosage units — Medium priority

> Uniformity remains important because variation between tablets could produce inconsistent dosing. The group rated its severity as medium because its consequence is considered less direct than wrong identity or harmful impurities. Uncertainty is low because the common causes and testing methods are well understood.

**Control explanation:** Use appropriate formulation and process controls, then confirm compliance through release testing.

### 4. Dissolution — Medium priority

> Dissolution has high severity because inadequate drug release may affect the amount available for absorption. Uncertainty is low because this relationship and the relevant testing approach are well established. Under the method used in this table, that combination produces a medium control priority.

**Control explanation:** Perform an appropriate dissolution test on the finished drug product at release and support the method through development data.

### 5. Assay — Medium priority

> Assay has high severity because incorrect average strength could affect efficacy or exposure. Uncertainty is low because validated assay methods and routine manufacturing controls provide a well-established way to measure and manage it.

**Control explanation:** Include assay in routine drug-product release testing.

### 6. Water content — Medium priority

> Water content has medium severity and uncertainty because its actual effect depends on the formulation and the stability data. Excess moisture may promote degradation or change tablet performance.

**Control explanation:** Manage it through manufacturing conditions, in-process monitoring, stability studies and moisture-protective packaging.

### 7. Microbial limits — Low priority

> Microbial limits receive the lowest priority because a dry oral solid manufactured under suitable GMP controls generally presents less opportunity for microbial proliferation. Low priority does not mean that microbiological quality can be ignored.

**Control explanation:** Establish an appropriate monitoring or testing strategy. Reduce or omit routine testing only when scientific justification and validation data support that decision.

## Closing Slide 2

> Overall, identity and impurity control receive the highest initial priority. The other attributes remain CQAs with defined controls, but the present knowledge and available testing methods reduce the need for additional investigation. We would update this ranking as formulation, process and stability knowledge develops.

## Accuracy safeguards for questions

1. Do not claim that severity plus uncertainty is the complete ICH Q9 definition of risk. ICH Q9 describes risk using severity and probability, while uncertainty affects confidence in the assessment.
2. Do not say that a low-uncertainty rating makes a severe failure harmless. It means the hazard and its controls are better understood.
3. Do not limit identity control to the drug substance. The finished drug product should also undergo appropriate identification testing.
4. Do not limit degradation-product control to release. Stability testing must evaluate what happens during storage.
5. Keep **potential** before CQAs when introducing the list. Development knowledge may refine the list and its priorities.

## Short answers for likely questions

- **Assay versus uniformity:** Assay measures average batch strength; uniformity checks dose consistency among individual tablets.
- **Why is dissolution important?** Atorvastatin calcium has limited aqueous solubility, and formulation or process variables may alter drug release.
- **Why is microbial risk lower?** A dry oral solid under GMP is less supportive of microbial proliferation, but any reduced-testing strategy still requires scientific justification.
- **What about polymorphic form?** It is principally an API material attribute that may affect dissolution. It is not automatically a separate finished-product CQA.
- **Why use uncertainty rather than likelihood?** This slide uses uncertainty for preliminary control prioritisation. A complete ICH Q9 risk assessment would also evaluate probability.

## Regulatory basis

- [ICH Q8(R2): Pharmaceutical Development](https://database.ich.org/sites/default/files/Q8%28R2%29%20Guideline.pdf) — CQA definition, typical solid-oral CQAs and iterative prioritisation.
- [ICH Q9(R1): Quality Risk Management](https://database.ich.org/sites/default/files/ICH_Q9%28R1%29_Guideline_Step4_2025_0115_0.pdf) — severity, probability, uncertainty and lifecycle risk review.
- [ICH Q6A: Specifications for New Drug Substances and Products](https://database.ich.org/sites/default/files/Q6A%20Guideline.pdf) — identification, assay, dissolution, uniformity, water-content and microbial-limit considerations.

## Working conclusion

The presentation should not read the two tables verbatim. It should explain the clinical or product-quality meaning of each CQA, connect that meaning to its preliminary priority and control, and make the QTPP-to-CQA-to-control logic visible. The opening and transitions provide the structure, while the seven short explanations supply the substance.

## Next move

- [ ] Practise the section aloud and measure the total time.
- [ ] Ask the group whether the identity-control wording can be corrected before presentation.
- [ ] Confirm how much speaking time Shine has for the two slides.

## Revision history

| Version | Date | Changes |
|:--------|:-----|:--------|
| — | Before tracking; see recorded dates | Legacy metadata retained: Status: Current draft |
| 0 | 2026-10-18 | Revision tracking introduced at baseline 0; earlier history incomplete. Standardised document metadata; content unchanged. Draft used because approval of this document is not established. |
