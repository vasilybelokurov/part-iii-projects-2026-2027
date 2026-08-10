# Writing a Good Part III / MASt Research Project Description

A practical guide for supervisors preparing a project for the Cambridge Part III /
MASt (Astrophysics) research-project booklet. It describes the required structure,
what a strong description looks like, and where to find models to copy.

---

## 1. Where to look first

- **The template** — `2026-27 Research Project Template.docx` in this folder. Fill it
  in; do not change its styles, headings, or section order. Every description must use
  the same skeleton so the booklet reads consistently.
- **Last year's booklet (66 projects)** — the single best source of worked examples and
  house style: <https://www.ast.cam.ac.uk/files/2025_26_research_project_booklet.pdf>.
  Skim a few projects near your topic before writing.
- **This folder's five 2026-27 descriptions** (`01_…`–`05_…docx`) — current examples in
  the intended voice: discovery-driven, "detect-then-interpret", validation built in.

## 2. Required structure

Use the template's sections, in this order. Suggested lengths are guidance, not limits.

| Section | Purpose | Length |
|---|---|---|
| **Project Title** | Concrete and inviting; name the data and the goal | 1 line |
| **Supervisor I / II / III, UTO** | Sup I is the primary contact; the UTO must be a University Teaching Officer (see booklet rules) | — |
| **Project Summary** | The whole project in one place: problem → method → what the student will produce | 1–2 paragraphs |
| **Background** | Why it matters, the key prior work, and why *now* / *this data* | 2–3 paragraphs |
| **Project details** | The actual plan as a short ordered list of steps, from setup to interpretation | 5–7 bullets |
| **Prerequisite skills required** | The honest minimum; keep the barrier low | 2–4 sentences |
| **Other skills used** | Skills the student will *gain* | 4–6 bullets |
| **Acceptable Programming Languages** | Usually "Python is preferred" | 1 line |
| **Useful references** | Key papers a student should read; every entry with a working DOI/ADS/arXiv URL | 5–8 |
| **General references** | Data releases, software, surveys referred to in the text | 3–5 |
| **Figures 1–5** | Optional; one good figure sells a project | as needed |

## 3. What makes a good project description

1. **A clear, single aim.** The reader should finish the Summary knowing exactly what
   will be discovered or measured. Avoid "explore X" without a deliverable.
2. **A concrete deliverable.** End the Project details with what the student hands over —
   a ranked candidate catalogue, a calibrated pipeline, a map, an upper limit.
3. **Detect-then-interpret.** Frame discovery work so that finding candidates and
   deciding what they are are separate steps. Keep an "uncertain" category; do not force
   every detection into a physical class.
4. **Validation is part of the plan.** Say how the method is tested *before* conclusions:
   known systems recovered, injected mocks, permutation nulls, control samples. This
   matches the department's "no conclusions without tests" expectation.
5. **An MVP with a stretch ladder.** Make the core, guaranteed-to-work part obvious, then
   list extensions. A student should not be able to fail by running out of the hardest
   task first.
6. **Realistic scope and data.** The core must be doable with data that exist *now* or on
   a known release date. If it depends on a future release, give a pilot that starts on
   current data (see project 04/05 in this folder).
7. **Low prerequisites, real skills gained.** Part III students arrive without research
   experience. State the true minimum and let the method be learned during the project.
8. **Honest, verified references.** Only cite real papers, each with a working link. No
   invented bibliographic details. Prefer ADS / arXiv / DOI.
9. **Distinct from recent projects.** Check last year's booklet: if a nearby project
   exists, say in the Background how yours differs (new data, new method, new regime).

## 4. Section-by-section tips

- **Title.** Name the survey/data and the science: e.g. "Discovering New Ultra-Faint
  Milky Way Satellites with Euclid DR1." A short evocative phrase plus a plain
  descriptor works well.
- **Summary.** Two paragraphs: (1) the problem and why it is hard; (2) the data, the
  method, and what the student produces. Put the enabling idea — the reason this is
  possible now — up front.
- **Background.** Establish the science case, cite the 3–5 papers that define the field,
  and end by explaining what makes the project timely (a new data release, a new method,
  a theoretical prediction to test).
- **Project details.** An ordered list from setup → sample → method → validation →
  interpretation. Bold a short lead phrase per bullet. Front-load the reliable steps.
- **Prerequisites vs. Other skills.** Prerequisites = what they need on day one; Other
  skills = what they will learn. Keep the first short and the second aspirational.
- **References.** Verify every link. Split *Useful* (read these) from *General* (data,
  code, surveys). Include the data-release documentation you rely on.

## 5. References policy (important)

- Every reference must be real and carry a working URL (DOI, ADS, or arXiv).
- Check the DOI resolves before submitting. Do not guess volume/page numbers.
- Cite the data releases and software you name in the text (e.g. Gaia DR3/DR4, AGAMA,
  the relevant survey overview papers).

## 6. Scope and timeline

Part III projects run across the year: reading and code-building in Michaelmas, the main
analysis in Lent, and writing up in Easter. Design the description so that:

- the **first term** produces a tested pipeline on existing/public data;
- the **main result** does not depend on a data release that might slip;
- there is always a **fallback** that yields a real result even if the ambitious
  extension fails.

See the booklet's front matter for the current rules on supervisors, the UTO
requirement, and the student–project matching process.

## 7. Final checklist

- [ ] Uses the template unchanged (styles, headings, section order).
- [ ] Title names the data and the goal.
- [ ] Summary states a single aim and a concrete deliverable.
- [ ] Background cites the defining papers and says why *now*.
- [ ] Project details = ordered steps ending in a deliverable, with validation included.
- [ ] MVP is doable on data that exist now; extensions are clearly optional.
- [ ] Prerequisites are the honest minimum.
- [ ] Every reference is real with a working DOI/ADS/arXiv link.
- [ ] Checked against last year's booklet for overlap; differences stated.
