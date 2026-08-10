# Project 1: Euclid DR1 ultra-faint satellite search — design

**Status:** Scientific concept approved in discussion; written specification awaiting review.

## Purpose

Produce an approximately one-and-a-half-page Part III project description with the working title **“Discovering New Ultra-Faint Milky Way Satellites with Euclid DR1”**. The project is discovery-led: its main aim is to find and characterise new ultra-faint dwarf-galaxy (UFD) candidates. Stellar streams are a natural but explicitly secondary extension.

## Scientific case

The faintest companions of the Milky Way are invisible in integrated light and must be recognised through small concentrations of individually resolved stars. Euclid DR1 combines exceptional depth with wide-area coverage, opening a regime that shallower surveys cannot reach. This gives the project a clear question: what previously unseen UFDs are present in the Euclid DR1 footprint?

## Core analysis

The student will begin with a simple, transparent search pipeline:

1. Use Euclid DR1 as the primary discovery data set, without making shallower ancillary imaging a prerequisite.
2. Select sources consistent with old, metal-poor isochrones shifted across a grid of plausible distances.
3. Construct maps of the selected stars and apply a Koposov-style difference-of-Gaussians spatial filter to identify significant overdensities.
4. Verify the method by recovering known systems in the footprint and use injected mock satellites to quantify the types of systems the search can detect.

The project should not become an exercise in optimising a complicated detection algorithm. The straightforward search above is the scientific core and an appropriate starting point for a Part III student.

## Candidate assessment and outputs

Every credible overdensity will be retained and ranked. The ranking will combine:

- the presence and coherence of an old, metal-poor colour–magnitude sequence;
- spatial concentration and persistence under modest changes to the stellar selection;
- Gaia astrometry for the brighter possible members, where available;
- the presence of a corresponding galaxy overdensity, which may reveal an unresolved-galaxy false positive; and
- checks for image artefacts or spatial variations in catalogue quality.

The principal output will be a ranked catalogue of credible UFD candidates. The strongest candidates will receive initial structural and stellar-population characterisation, including approximate distance, size, ellipticity, luminosity and membership probabilities where the data support them. Recovery tests and mock injections will provide the necessary context for interpreting both discoveries and non-detections, but the selection function supports the search rather than replacing it as the headline goal.

If time permits, the same isochrone-selected density maps can be searched for elongated, lower-surface-brightness features. This provides a concise extension to stellar streams without diluting the UFD focus.

## Literature synthesis

The description will give the main bodies of earlier work distinct, complementary roles:

- **Koposov et al. and Torrealba et al.** establish the classical resolved-star search strategy and demonstrate its discovery power.
- **Drlica-Wagner et al.** provide the modern completeness and selection-function framework needed to interpret a satellite search.
- **Cerny et al.** illustrate contemporary candidate assessment, follow-up prioritisation and the difficulty of distinguishing the faintest dwarf galaxies from star clusters.

These contributions should be woven into the motivation and method, not presented as a list of obligatory citations or allowed to displace the Euclid DR1 science case.

## Writing constraints

- Use British English and the tone and structure of the supplied Part III examples and the 2025–26 project booklet.
- Keep the prose scientifically nuanced, inviting and concrete rather than blunt or over-promissory.
- Explain the workflow at project-description level; omit implementation detail that belongs in the eventual research plan.
- Keep UFD discovery and characterisation unmistakably central, with streams confined to the final extension.
