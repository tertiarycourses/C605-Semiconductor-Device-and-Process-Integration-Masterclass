# Learner Guide: Semiconductor Device and Process Integration Masterclass

**Course code:** C605

**Version:** 1.0

**Release date:** 1 Oct 2026

**Training provider:** Tertiary Infotech Academy Pte Ltd (UEN 201200696W)

This guide is the detailed learner reference for the two-day course. The slide deck is concept-led; detailed procedures, evidence requirements and acceptance criteria are kept here and in each individual activity folder.

## Learning outcomes

- LO1: Identify semiconductor manufacturing process flows based on device physics.
- LO2: Determine follow-up actions for process integration issues and performance.

## LU1: Fundamentals of Device Physics and Device Fabrication

PPT slides 9-280.

### Semiconductor materials and carrier physics (slides 9-31)

Semiconductors sit between conductors and insulators because the population and mobility of charge carriers can be controlled. Silicon is favoured because it is abundant, supports precise doping and forms a stable native oxide. Device behaviour follows from crystal bonding, allowed energy bands, carrier statistics and the creation or removal of electrons and holes.

- Intrinsic material has thermally generated electron-hole pairs; recombination removes a pair.
- Donor dopants create n-type material and acceptor dopants create p-type material.
- The Fermi level indicates occupancy probability and shifts toward the dominant carrier band after doping.
- Resistivity depends on carrier concentration and mobility; either may change with temperature or process damage.
- Crystal defects and contamination create electrical states that alter leakage, lifetime and yield.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### PN junctions and diode behaviour (slides 32-43)

A PN junction forms when p-type and n-type regions meet. Carrier diffusion leaves fixed ionised dopants, creating a depletion region and built-in electric field. Bias changes the barrier: forward bias enables current, reverse bias widens depletion, and excessive reverse field can trigger breakdown.

- At equilibrium, drift and diffusion balance and the Fermi level is continuous.
- Forward current rises strongly after the applied bias lowers the junction barrier.
- Reverse current is small until avalanche or Zener breakdown dominates.
- Junction depth, area, doping gradient and defects influence capacitance, leakage and breakdown voltage.
- Process decisions in implantation, diffusion, anneal and cleaning therefore set diode behaviour.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### MOSFET and BJT device operation (slides 44-97)

MOSFETs control a surface channel electrostatically through the gate oxide, whereas BJTs use injection and collection of minority carriers across two junctions. Their operating regions are not just circuit concepts: geometry, oxide quality, dopant profiles, contacts and thermal history determine threshold, gain, leakage and breakdown.

- A MOS capacitor progresses through accumulation, depletion and inversion as gate bias changes.
- MOSFET operation is commonly separated into off, linear and saturation regions.
- Threshold voltage depends on gate work function, oxide thickness, substrate doping, fixed charge and body bias.
- A BJT in forward-active mode has a forward-biased emitter-base junction and reverse-biased base-collector junction.
- Scaling improves density and speed but raises short-channel, leakage, field and reliability concerns.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Memory devices and integrated circuits (slides 98-111)

Integrated circuits combine devices into logic and memory structures. SRAM stores state in a latch, DRAM stores charge in a capacitor and non-volatile memories use persistent charge or structural states. Architecture determines the critical process features and the tests required at wafer sort.

- SRAM is fast and does not require refresh but uses more transistors per bit.
- DRAM provides high density but requires periodic refresh and sensitive capacitor integration.
- Flash memory uses a floating-gate or charge-trap structure and is organised in NOR or NAND architectures.
- Word lines, bit lines, sense amplifiers and cell arrays connect device physics to product function.
- Moore's law describes historical density scaling; integration choices determine whether scaling is manufacturable.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Wafer fabrication process modules (slides 112-241)

Wafer fabrication is a repeated pattern of surface preparation, film formation, lithographic definition, material removal or doping, thermal treatment and measurement. Every module leaves a physical state that constrains the next module, so local optimisation can damage total integration performance.

- Crystal growth and wafer preparation establish orientation, defect density, flatness and starting resistivity.
- Oxidation, CVD, PVD and epitaxy form functional or protective films with controlled composition and thickness.
- Lithography defines location and critical dimension; mask polarity, resist response, focus and exposure affect fidelity.
- Wet etch, plasma etch and RIE trade isotropy, selectivity, damage and residue risk.
- Diffusion and ion implantation set dopant profiles; annealing repairs damage and activates dopants within a thermal budget.
- CMP provides planarity for multilevel integration but introduces dishing, erosion, scratches and particle-cleaning challenges.
- Metallisation and damascene integration require barriers, seeds, fill, planarisation and contact-resistance control.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### CMOS integration flows (slides 242-275)

A CMOS flow coordinates isolation, wells, gate stacks, source-drain structures, contacts and interconnects. The process is best understood as a sequence of structural transformations with verification gates, not as an isolated list of tool recipes.

- Isolation separates neighbouring devices; wells establish the body regions for NMOS and PMOS.
- The gate stack defines channel length, oxide field and threshold control.
- Self-aligned source-drain processing links spacer geometry, implant profiles and junction activation.
- Contacts and interconnects connect devices while controlling resistance, capacitance, stress and electromigration.
- Cross-sections are the primary integration language for checking whether each module creates the intended structure.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Layout and design rules (slides 277-280)

Layout converts electrical intent into mask geometry. Design rules set conservative minimum widths, spaces, overlaps and enclosures so normal process variation does not produce opens, shorts or unreliable structures.

- Masks are generated from layout layers and aligned through multiple lithography steps.
- Rules reflect lithography resolution, overlay capability, etch bias, diffusion and reliability margins.
- A design-rule check finds geometric violations before mask generation.
- Process design kits connect rules, models and verified device structures to circuit design.
- Manufacturability review considers systematic variation beyond simple minimum-rule compliance.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

## LU2: Process Integration Issues

PPT slides 281-415.

### Isolation, wells and self-aligned modules (slides 281-297)

Process integration begins with interactions that span modules. LOCOS, shallow trench isolation, well formation, self-aligned gates, extensions and silicides all trade geometry, stress, dopant placement, thermal budget and defect risk.

- LOCOS is simple but consumes lateral area through bird's-beak encroachment.
- STI improves density but introduces trench-fill, CMP, corner and stress-control requirements.
- Well schemes determine body isolation, latch-up margin and threshold control.
- Lightly doped drains or source-drain extensions reduce peak field but add series resistance and alignment sensitivity.
- Silicide lowers contact resistance but requires phase, consumption and bridging control.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Contamination, yield and process variation (slides 298-346)

Yield converts process performance into the fraction of good die. Contamination, defects, wafer handling and parameter variation accumulate across hundreds of operations, making clean environments, SPC, inspection and spatial analysis essential.

- Air, personnel, water, chemicals, gases, electrostatic charge and equipment are contamination sources.
- HEPA filtration, mini-environments, RCA cleaning and controlled drying reduce particle and molecular contamination.
- Yield loss may be random, systematic, edge-related, cluster-related or parametric.
- Wafer maps preserve spatial information that a lot average can hide.
- SPC distinguishes common-cause variation from special-cause signals and supports a disciplined reaction plan.
- Microscopy, SIMS, Auger, four-point probe and ellipsometry provide complementary physical and chemical evidence.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Device performance characterisation (slides 347-355)

Performance verification compares measured device behaviour with specification and process intent. Physical measurements explain structure, parametric electrical tests quantify device response, and wafer-sort patterns reveal whether the integration result is stable across the wafer and lot.

- Critical dimension and line-width measurements check pattern transfer.
- Film thickness, sheet resistance and oxide electrical tests verify material and interface properties.
- I-V and C-V measurements reveal threshold, mobility, leakage, breakdown and interface effects.
- A metric must have a definition, sampling plan, limit, measurement capability and reaction rule.
- Verification requires evidence that discriminates between competing mechanisms, not a plausible story alone.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Device reliability and failure mechanisms (slides 356-366)

Reliability addresses performance over time and stress. Hot-carrier degradation, time-dependent dielectric breakdown and electromigration affect different structures and produce different signatures, so stress conditions and failure analysis must match the suspected mechanism.

- Hot carriers create interface or oxide damage near high-field drain regions and shift transistor parameters.
- TDDB is progressive dielectric degradation under electric field and is evaluated statistically over time-to-failure.
- Electromigration moves metal under high current density and temperature, forming voids or extrusions.
- Accelerated tests require a defensible acceleration model and must avoid creating an unrelated failure mode.
- A reliability conclusion combines electrical signature, physical location, stress dependence and population statistics.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Assembly, packaging and final test (slides 367-399)

Back-end assembly transforms tested wafers into protected, connected products. Thinning, singulation, die attach, wire or flip-chip bonding, sealing and final test introduce mechanical, thermal and interfacial risks that interact with wafer-fabrication reliability.

- Wafer thinning and singulation control die strength, chipping and contamination.
- Die attach must manage adhesion, voiding, thermal conduction and stress.
- Wire bonding, tape automated bonding and flip chip use different interconnect geometries and failure modes.
- Moulding, sealing and plating protect the die while controlling moisture, corrosion and lead integrity.
- Burn-in and final test screen early failures and verify product performance after packaging.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

### Optimisation and emerging technologies (slides 400-415)

Integration optimisation is a controlled learning cycle: define the issue, contain risk, verify causes, change the process and prove effectiveness. Advanced packaging, heterogeneous integration, FinFETs, gate-all-around devices, vertical devices and new channel materials increase the importance of cross-module trade-offs.

- Yield improvement needs both defect reduction and tighter control of parametric variation.
- Corrective action removes a verified cause; preventive action changes the system to reduce recurrence elsewhere.
- Heterogeneous and 3D integration add bonding, thermal, alignment and known-good-die dependencies.
- FinFET and gate-all-around structures improve electrostatic control but complicate patterning, deposition and contact integration.
- Future technology claims should be assessed by manufacturability, variability, reliability, thermal behaviour and cost, not novelty alone.

Check your understanding: Explain how variation in this area could propagate to yield, performance or reliability, and name the evidence needed to verify the link.

## Detailed step-by-step activities

### Activity 1: Device Physics Evidence Map

**PPT alignment:** concept slides 11-97; activity overview slide 416

**Duration:** 35 minutes

**Goal:** Connect device-physics mechanisms to observable manufacturing controls and device consequences.

**Scenario:** A new process engineer must explain why doping, junction bias and oxide thickness matter before reviewing a CMOS traveller.

Before you start:

- Open `activities/01-device-physics-evidence-map/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Review the supplied device cross-sections and identify the semiconductor, oxide, junction and contact regions.
2. For each region, state the governing mechanism: carrier concentration, depletion, inversion, recombination or field-driven transport.
3. Map each mechanism to one controllable process input such as dose, energy, anneal temperature, oxide thickness or critical dimension.
4. Predict one electrical symptom when that input drifts high and one when it drifts low.
5. Mark the evidence that would confirm the prediction and record one uncertainty requiring follow-up.

Evidence to submit:

- Completed device-physics evidence map with at least six mechanism-control-consequence links.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- All four device regions are addressed
- At least six causal links are technically plausible
- Each prediction names a measurable symptom

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

### Activity 2: Process Module Architecture

**PPT alignment:** concept slides 112-241; activity overview slide 417

**Duration:** 40 minutes

**Goal:** Identify the major process loops, their purposes, inputs, outputs and control gates.

**Scenario:** A fab is onboarding a mixed-experience team and needs a common architecture view that separates FEOL, MOL, BEOL and packaging loops.

Before you start:

- Open `activities/02-process-module-architecture/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Sort the supplied process cards into FEOL, MOL, BEOL, wafer sort and assembly groups.
2. Arrange each group into a loop showing prepare, form, pattern, measure and release decisions.
3. Name the input and output of every process module.
4. Add the metrology or inspection gate that prevents a nonconforming wafer from advancing.
5. Annotate two feedback loops and explain what parameter each loop corrects.

Evidence to submit:

- Process architecture map with module boundaries, control gates and two feedback loops.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- FEOL, MOL, BEOL and post-fab stages are separated
- Every module has an input and output
- At least two feedback loops are justified

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

### Activity 3: CMOS Manufacturing Flow and Control Gates

**PPT alignment:** concept slides 242-280; activity overview slide 418

**Duration:** 50 minutes

**Goal:** Outline a coherent CMOS process flow and show where device physics constrains sequencing.

**Scenario:** A product transfer team must turn a high-level CMOS description into a controlled manufacturing flow for a pilot lot.

Before you start:

- Open `activities/03-cmos-manufacturing-flow/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Start from incoming silicon and place isolation, well formation, gate stack, source-drain, contacts and interconnect in order.
2. Insert the lithography, etch, clean, deposition, implantation, anneal and CMP modules required by each structural change.
3. Add hold points for overlay, critical dimension, film thickness, sheet resistance and defect inspection.
4. Identify three sequence dependencies that cannot be reversed and explain the physical reason.
5. Trace one wafer through the completed flow and check that every layer or junction has a formation and verification step.

Evidence to submit:

- One-page CMOS process flow with control gates and three device-physics sequence rationales.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- Flow begins with incoming wafer and ends with test-ready die
- Five required control gates are present
- Three irreversible dependencies are explained

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

### Activity 4: Lithography-Etch Interaction Case

**PPT alignment:** concept slides 131-202; activity overview slide 419

**Duration:** 45 minutes

**Goal:** Determine how variation propagates between lithography, etch, clean and contact modules.

**Scenario:** Contact resistance rises after a lithography focus excursion and a longer-than-normal plasma over-etch.

Before you start:

- Open `activities/04-lithography-etch-interaction/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Read the lot history and separate observations from assumptions.
2. Build an interaction matrix for resist thickness, focus, exposure, CD, etch bias, selectivity and residue.
3. Trace the most likely propagation path from lithography variation to contact resistance.
4. Identify the measurement that would discriminate between under-patterning, over-etch damage and post-etch residue.
5. Recommend an immediate containment action and one experiment that tests the suspected interaction.

Evidence to submit:

- Interaction matrix, causal chain and discriminating verification plan.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- At least three module interactions are identified
- Containment protects downstream lots
- The proposed test distinguishes competing causes

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

### Activity 5: Doping and Thermal-Budget Interaction

**PPT alignment:** concept slides 203-221; activity overview slide 420

**Duration:** 45 minutes

**Goal:** Analyse implantation, activation, diffusion and oxide interactions across the thermal budget.

**Scenario:** Threshold voltage drifts low after a revised rapid thermal anneal recipe is introduced to improve activation.

Before you start:

- Open `activities/05-doping-thermal-budget/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Compare the baseline and revised implant-plus-anneal travellers.
2. List the intended effect and possible side effect of dose, energy, tilt, temperature and time.
3. Calculate the cumulative thermal exposure using the worksheet's relative thermal-budget index.
4. Link each plausible mechanism to sheet resistance, junction depth, threshold voltage or leakage evidence.
5. Propose a split-lot experiment that isolates activation gain from unwanted diffusion.

Evidence to submit:

- Thermal-budget comparison, evidence map and split-lot experiment design.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- Implant and anneal variables are considered together
- At least three electrical or physical measures are selected
- Split-lot factors and response measures are explicit

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

### Activity 6: Yield and Performance Metric Verification

**PPT alignment:** concept slides 298-355; activity overview slide 421

**Duration:** 55 minutes

**Goal:** Select and interpret metrics that verify process-integration performance.

**Scenario:** A wafer-sort yield decline is concentrated near the edge while centre-die parametric results remain within specification.

Before you start:

- Open `activities/06-yield-performance-verification/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Inspect the supplied lot-level yield, wafer-map, CD, film-thickness and sheet-resistance data.
2. Calculate overall yield, edge-versus-centre yield, mean, range and the specified capability proxy.
3. Separate product-performance metrics from process-stability, yield and reliability metrics.
4. Test whether the spatial signature is consistent with coating, plasma, thermal or handling mechanisms.
5. State a verification conclusion, confidence level and the next measurement needed before disposition.

Evidence to submit:

- Metric dashboard worksheet with calculations, spatial interpretation and verification conclusion.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- All required metrics are calculated correctly
- The wafer-map pattern informs the conclusion
- Conclusion distinguishes verification from speculation

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

### Activity 7: Reliability Failure Analysis

**PPT alignment:** concept slides 356-366; activity overview slide 422

**Duration:** 45 minutes

**Goal:** Verify whether TDDB, hot-carrier degradation or electromigration best explains the evidence.

**Scenario:** Qualification finds early-life gate failures and resistance drift in upper-metal interconnects after accelerated stress.

Before you start:

- Open `activities/07-reliability-failure-analysis/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Classify each symptom by structure, stress condition, time dependence and electrical signature.
2. Compare the evidence against TDDB, hot-carrier and electromigration mechanism profiles.
3. Select the confirmatory stress test and physical-analysis method for each leading hypothesis.
4. Check whether the observed distribution supports a random defect, systematic process shift or wear-out mechanism.
5. Write a verification statement that names the supported mechanism and remaining evidence gap.

Evidence to submit:

- Failure-mechanism comparison and reliability verification statement.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- All three reliability mechanisms are differentiated
- Selected tests match the suspected structure
- The conclusion identifies an evidence gap

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

### Activity 8: Follow-Up Action and Integration Review

**PPT alignment:** concept slides 400-415; activity overview slide 423

**Duration:** 60 minutes

**Goal:** Determine proportionate containment, corrective, preventive and verification actions.

**Scenario:** The integration review board must disposition a yield loss involving etch overrun, dielectric stress and weak SPC reaction discipline.

Before you start:

- Open `activities/08-follow-up-action-review/README.md` or its same-folder PDF.
- Open the scenario brief, worksheet and evidence checklist in the same folder.
- Work individually first, then compare reasoning when instructed.
- Use only de-identified workplace examples and state assumptions explicitly.

Procedure:

1. Consolidate the causal chains from the earlier activities into one issue statement.
2. Rank risks by wafer exposure, defect escape, device impact and reversibility.
3. Define immediate containment for wafers, tools, recipes and downstream operations.
4. Assign corrective actions addressing recipe, integration sequence, metrology and control-plan weaknesses.
5. Specify owner, due date, evidence of completion and effectiveness metric for every action.
6. Run a peer challenge: test whether each action addresses a verified cause and whether restart criteria are objective.

Evidence to submit:

- Integration review action register with containment, CAPA, owners and effectiveness checks.
- Completed worksheet with assumptions, sources and calculations where applicable.
- Completed learner evidence checklist.

Acceptance criteria:

- Actions are tied to verified causes
- Containment and corrective action are distinct
- Every action has an owner and effectiveness measure

Troubleshooting:

- If several mechanisms fit, name the measurement that distinguishes them.
- If a process step has no input, output or control gate, the architecture is incomplete.
- If an action is not linked to a verified cause, classify it as a hypothesis test.
- If evidence conflicts, preserve the conflict and define the next check.

## Support

LMS: https://lms-tms.tertiaryinfotech.com/

Support: enquiry@tertiaryinfotech.com · +65 6100 0613
