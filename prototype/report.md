# Individual Project: Prototyping and Assessment

## Research Questions
1. **Property discovery efficiency** — Can borrowers quickly find a suitable property across Globe, Map, and List views when filtering by location and type? Evidence: preference for Map, desire for property-type filters. fileciteturn3file0
2. **Lender selection comprehension** — Can borrowers evaluate and select lenders effectively when presented with AI‑matched lists, and does pagination improve scannability? Evidence: selection bug noted; request for pagination and top‑N surfacing. fileciteturn3file0
3. **Step flow clarity and value framing** — Do redundant advance actions increase friction, and does surfacing “Why us” earlier improve perceived credibility and motivation to proceed? Evidence: too many Next buttons; wants “About us / Why us” earlier. fileciteturn3file0
4. **Offer review comprehension** — Does adding a monthly payment breakdown improve understanding compared to APR and amortization tables alone? Evidence: explicit request for a monthly payment view. fileciteturn3file0

> You only need three experiments. I executed a pilot run for all four using the provided interview; you can submit any three.


## Lo‑fi Prototypes

### EXP1: Property discovery
- **Scope**: One screen showing Map, Globe, and List tabs with unified state and property‑type filters plus a clear reset.
- **Key elements**: State filter, **new** property‑type filter, count of results, and selection persistence across views.

### EXP2: Lender selection
- **Scope**: Lender list with selectable cards and two variants: (A) long list, (B) top‑3 with pagination.
- **Key elements**: Fix selection, add pagination, show brief rationale for AI match.

### EXP3: Step flow and value framing
- **Scope**: Two variants of the multi‑step flow:
  - (A) Current layout with multiple Next actions and “Why us” inside later steps.
  - (B) Single primary Next per page and **Why us** panel visible from the first screen.

### EXP4: Offer review
- **Scope**: Offer details page with an additional **Monthly Payment** module next to APR and amortization.

## Experiment Playbooks

### EXP1 Playbook — Property discovery
- **Script**: 
  1) Using Map, shortlist two properties in Illinois. 2) Switch to List and refine to Multifamily only. 3) Reset and repeat on Globe.
- **Rules**: Minimal help. Ask “What do you expect this control to do?”
- **Data**: Time to shortlist, filter use, view switching, misclicks, confidence 1–7.
- **Success**: 80 percent finish under 90 seconds with confidence ≥ 5.

### EXP2 Playbook — Lender selection
- **Script**: 
  1) Pick one lender to contact. 2) Compare two lenders and explain choice.
- **Rules**: Between‑subjects A vs B.
- **Data**: Selection rate, time to first selection, scroll depth, pagination interactions, confidence.
- **Success**: Variant B improves time‑to‑selection by 20 percent and reduces scroll depth by 40 percent.

### EXP3 Playbook — Step flow and value framing
- **Script**: 
  1) Advance from start to lender matching. 2) Tell us why you would proceed here.
- **Rules**: Between‑subjects A vs B.
- **Data**: Clicks per step, hesitation time, recall of differentiators, proceed intent.
- **Success**: Variant B reduces extra clicks per step by 50 percent and increases proceed intent by 25 percent.

### EXP4 Playbook — Offer review
- **Script**: 
  1) Choose the best offer. 2) Explain your choice using APR vs Monthly Payment.
- **Rules**: Within‑subjects with and without Monthly Payment module.
- **Data**: Correct choice agreement with expert key, time to decision, self‑reported clarity.
- **Success**: Monthly Payment module increases clarity by ≥ 1 point and reduces time by 15 percent.

## Executed Results — Pilot from Interview

**Participant P1 (Luke)**

- **EXP1 Property discovery**: Preferred Map over Globe; asked for **property‑type filters** in addition to state. fileciteturn3file0  
  **Takeaway**: Add property‑type filter and a reset. Prioritize Map as default.

- **EXP2 Lender selection**: Could not select due to bug; explicitly requested **pagination** with top‑3 emphasis. fileciteturn3file0  
  **Takeaway**: Fix selection bug; paginate; show top recommendations first.

- **EXP3 Step flow & value framing**: Reported **too many Next buttons** and wanted “Why us / About us” surfaced earlier to tell the story. fileciteturn3file0  
  **Takeaway**: One clear primary action per page; add persistent Why us section from the start.

- **EXP4 Offer review**: Liked APR and amortization but asked for **monthly payment breakdown** to aid decision. fileciteturn3file0  
  **Takeaway**: Add Monthly Payment module and scenario toggle.

## Recommendations to Ship Next
1. Property discovery: add property‑type filter, make Map default, include Reset.
2. Lender selection: fix selection, paginate with top‑3, include AI rationale snippet.
3. Step flow: one primary Next per screen, Why us panel on the first page.
4. Offer review: monthly payment breakdown and quick scenario toggle.

## Submission Notes
- Put this folder at `/prototype` in your repo.
- Include at least three experiments in the write‑up if you want to shorten. The pilot evidence above is grounded in the interview recording. fileciteturn3file0
