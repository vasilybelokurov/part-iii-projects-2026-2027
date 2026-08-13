# Part III / MASt Research Projects — 2026–27

Research-project descriptions for the Cambridge Part III / MASt in Astrophysics,
2026–27, offered by **Vasily Belokurov, Sergey Koposov, Dolev Bashi, Cathie J. Clarke,
Simon Hodgkin, Mika Kontiainen, Júlia Laguna Miralles,** and **Urvi Thakurdesai**. Each
project is a self-contained `.docx`. Projects 01–06 are written to the departmental
template; projects 07–10 (contributed by Dr Dolev Bashi) use their own document styling.

## Projects

| # | Title | Data | What the student does |
|---|-------|------|-----------------------|
| 01 | Discovering New Ultra-Faint Milky Way Satellites with Euclid DR1 | Euclid DR1 | Search for ultra-faint dwarfs with isochrone filtering and difference-of-Gaussians maps; measure the selection function by injection–recovery; rank candidates. Streams as an extension. |
| 02 | Stars on the Run: Discovering Hypervelocity and Runaway Stars with Euclid DR1 | Euclid DR1 (NISP slitless spectra) | Calibrate Euclid radial velocities empirically, then run a blind RV-outlier search and a Gaia tangential-velocity search; trace the fastest stars back to their origins. |
| 03 | Beyond the Clouds: Mapping the Smooth Halo and Discovering Stellar Substructure around the LMC and SMC with Euclid DR1 | Euclid DR1 | Map the old stellar population around the LMC and SMC with main-sequence turn-off stars; fit and subtract a smooth model; search the residuals for new substructure. |
| 04 | The 40-Second Sky: Discovering Minute-timescale Variables with Gaia DR4 | Gaia DR4 (per-CCD photometry) | Detect brightness changes within a single ~40 s Gaia transit; rank coherent multi-CCD events; map fast variability across the Hertzsprung–Russell diagram. |
| 05 | Archaeology in a Barred Galaxy: Discovering Inner-Halo Substructure with Gaia DR4, Jacobi Energy, and Chemistry | Gaia DR4 + spectroscopy | Recover ancient inner-halo debris in Jacobi energy H_J = E − Ω_b L_z paired with chemistry, where the bar smears the usual E–L_z map; measure contrast against permutation nulls; vet candidate relics. |
| 06 | Catching Black Holes in the Act: Discovering Dwarf-Galaxy AGN through Optical Variability with Gaia DR4 | Gaia DR4 + ZTF | Search Gaia DR4 epoch photometry for accretion-disc flicker (damped random walk) in dwarf galaxies, where BPT and broad-line selection fail; model and remove the Gaia scan-angle systematic; gate on Gaia–ZTF agreement; calibrate on known dwarf AGN; deliver a vetted candidate catalogue and selection function. |
| 07 | Are planetary systems aligned with their binary companions? A Gaia DR4 census | Gaia DR4 (NSS binaries) + exoplanet catalogues | Cross-match Gaia DR4 astrometric binaries with transiting planets; classify S-type/P-type architectures; test dynamical stability; compare planet-host binary inclinations with a matched control sample and an eclipsing-binary cross-check. |
| 08 | Uncovering Quintuple and Higher-Order Stellar Systems with Gaia DR4 | Gaia DR4 (resolved pairs + epoch astrometry/RV) | Build graphs from overlapping Gaia resolved-pair associations; search each node's epoch data for unresolved inner companions; assemble a vetted catalogue of 5+ component hierarchies; test stability with N-body integrations. |
| 09 | Characterising the neutron-star-to-black-hole mass gap with Gaia DR4 | Gaia DR4 (NSS orbits) + RV surveys | Select astrometric binaries with dark companions via the mass function; add radial velocities for joint orbit fits; infer companion masses and test single-NS/single-BH/unresolved-binary hypotheses; compare the Galactic mass-gap population with LIGO-Virgo-KAGRA. |
| 10 | The orbital architecture of 2+2 quadruple stars with Gaia DR4 epoch radial velocities | Gaia DR4 (epoch RV) | Search wide-binary components for inner close-binary RV signals; confirm the 2+2 quadruple enhancement with measured orbits and an injection-recovery detection model; test for correlated inner-binary properties and inner/outer orbital alignment. |

Projects 01–06 share a common house style: discovery-driven, "detect-then-interpret",
with validation built in — known systems recovered, injected mocks, and controlled nulls
before any conclusion. Projects 07–10, contributed by Dr Dolev Bashi
(`Part_III_Vasily_Dolev_project1-4.docx`), cover the same section content but use their
own Word styles rather than the departmental template; left as supplied.

## Repository layout

```
.
├── 01_…docx … 06_…docx                      # projects on the departmental template
├── Part_III_Vasily_Dolev_project1-4.docx    # projects 07–10, Dolev Bashi's own styling
├── 2026-27 Research Project Template.docx   # departmental template (do not restyle)
├── PROJECT_DESCRIPTION_GUIDE.md             # how to write a strong description
├── figures/                                 # illustration figures + CREDITS.md
├── docs/superpowers/specs/                  # design specs (project 1 so far)
└── README.md
```

## Writing a new description

Read [`PROJECT_DESCRIPTION_GUIDE.md`](PROJECT_DESCRIPTION_GUIDE.md) first. In short: fill in
the template without changing its styles, state one clear aim and a concrete deliverable,
build validation into the plan, keep the core doable on data that exist now, and cite only
real papers with working DOI/ADS/arXiv links. Check last year's booklet for overlap:
<https://www.ast.cam.ac.uk/files/2025_26_research_project_booklet.pdf>.

## Contact

Vasily Belokurov — <vasily@ast.cam.ac.uk>. Students interested in a project should email
with questions before the matching process.
