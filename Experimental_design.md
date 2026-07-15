# PMIP7 experimental design

The structure of CMIP7 is slightly different than it has been in previous iterations. This time around there is an ['Assessment Fast Track'](https://wcrp-cmip.org/cmip-phases/cmip7/fast-track/) with endorsed and vetted experiments. And then it is left up to community MIPs to determine their own experiments and hierarchy within them. 

It is hoped that many CMIP7 models perform the Assessment Fast Track experiment, even if they do not choose to enter PMIP itself. To be considered part of CMIP7, a model must complete the extended DECK. This requires running the amip, abrupt4xCO2, piControl (and esm-piControl for ESMs) and 1pctCO2 for CMIP6, as well as a historical, piClim-control, piClim-anthro, piClim-4xCO2 simulations. 

As an entry card for PMIP7, models must perform an experiement that allows model development to be tracked through multiple generations of PMIP. Functionally, this would be midHolocene, lgm, lig127k or Pliocene. They must also perform a piControl simulation and distribute that output. Models participating in PMIP7 do not also have to participate in CMIP7. Although previously (in PMIP4) a model was not included in the paleoclimate component of the [IPCC Interactive Atlas](https://interactive-atlas.ipcc.ch/permalink/vb8Lecgj) unless they were part of CMIP6 and had also uploaded experiment output onto the ESGF.

## CMIP7 Fast Track
- [abrupt-127k](https://wcrp-cmip.org/wp-content/uploads/2023/12/Revised-PMIP-proposal-for-CMIP-fast-track.pdf)
  - 100 year-long simulation, which starts from the piControl and abruptly imposes observed values for the insolation distribution and greenhouse gases. It focuses on the impact of the strong insolation anomaly on sea ice (up to 70 Wm-2 in the Arctic). This run length is justified as the Arctic sea ice response can be reached within 30 years. This protocol [(Sime et al, 2026)](https://gmd.copernicus.org/articles/19/5881/2026/) mimics abrupt-2xCO2 and can be used for process-based comparison of past and future forcings.
  - For groups for which 100 years is challenging even a 30-year simulation may be sufficient to test the sea ice response to the radiative forcing of 127 000 years ago.

## PMIP7 Tier 1 
- [Mid-Holocene](https://www.pmip-interglacials.de/model-intercomparison-protocol/proposed-simulations/)
  - A protocol paper for this experiment is yet to written. It is being coordinated by the [Interglacials Working Group](https://www.pmip-interglacials.de). Unless there is strong community demand for any changes, this will follow the protocol of the PMIP4 midHolocene experiment defined by Otto-Bliesner et al [(Geosci. Model Dev., 2017)](https://doi.org/10.5194/gmd-10-3979-2017) with its [(supplement)](https://www.geosci-model-dev.net/10/3979/2017/gmd-10-3979-2017-supplement.zip).   
- Last Glacial Maximum
  - There will be an lgm experiment. It may have an updated ice sheet, but will otherwise follow the PMIP4 protocol
- Last Millennium
  - New forcing datasets are currently being created to support a past1000 simulation for PMIP4.
- Last Interglacial
  - A formal protocol paper for this experiment is yet to written. It is being coordinated by the [Interglacials Working Group](https://www.pmip-interglacials.de). It will be an extension of the abrupt-127k Fast Track experiment, whose epxeriemtnal design is described on the [CMIP7 webpage](https://wcrp-cmip.org/wp-content/uploads/2023/12/Revised-PMIP-proposal-for-CMIP-fast-track.pdf)
- Late Pliocene
  - This experiment is described in [Haywood et al. 2024](https://www.sciencedirect.com/science/article/pii/S0921818123002904). It was previously called midPliocene-eoi400 in CMIP6. 
- Miocene
  - The experimental protocol is submitted. The boundary conditions are available on [Zenodo](https://zenodo.org/records/20646213).
- Eocene
  - The experimental protocol is published by [Lunt et al. (2026)](https://gmd.copernicus.org/articles/19/6143/2026/). This is an early Eocene simulation with 5xCO2.

## PMIP7 Tier 2 
_The nature of the Tier 2 experiments are still under consideration, and will be primarily administered by the individual working groups. Some example experiments are_
- Transient Holocene: extensions of past2k, with an ensemble of opportunity already available although this is not curated and under-utilised
- HiRes PMIP: using high resolution models for paleo
- 8.2ka: a possible mirror of WhatIfMIP’s N. Atlantic hosing expts   
- Last Deglaciation: transient experiments that start from the lgm condition
- PMIP-Carbon: a glacial experiment aimed at understanding carbon cycle changes  
- MIS3: exploring internal Dansgaard-Oeschger events
- MIS11: simulating the interglacial most like Holocene
- MIS31: interesting interglacial prior to 100 kyr world
- earlyPliocene: similar to latePliocene, but with a Central American Seaway
- Eocene-Oligocene: exploring the transition from a hothouse to an icehouse world



---

# PMIP4 experimental design

## PMIP4 experiments for CMIP6

The experimental design for the PMIP4-CMIP6 experiments is summarized in [Kageyama et al, Geosci. Model Dev., 2018](https://doi.org/10.5194/gmd-11-1033-2018)

The following pages and references give further detail on the experimental set-up for each period and access to the files required to implement the boundary conditions.

- [Mid-Holocene](https://pmip4.lsce.ipsl.fr/doku.php/exp_design:mh)
  - Otto-Bliesner et al [(Geosci. Model Dev., 2017)](https://doi.org/10.5194/gmd-10-3979-2017) with its [(supplement)](https://www.geosci-model-dev.net/10/3979/2017/gmd-10-3979-2017-supplement.zip)
- [Last Millennium](https://pmip4.lsce.ipsl.fr/doku.php/exp_design:lm)
  - Jungclaus et al [(Geosci. Model Dev., 2017)](https://doi.org/10.5194/gmd-10-4005-2017) with its [supplement](https://www.geosci-model-dev.net/10/4005/2017/gmd-10-4005-2017-supplement.zip)
- [Last Glacial Maximum](https://pmip4.lsce.ipsl.fr/doku.php/exp_design:lgm)
  - Kageyama et al [(Geosci. Model Dev., 2017)](https://doi.org/10.5194/gmd-10-4035-2017) with its [supplement](https://www.geosci-model-dev.net/10/4035/2017/gmd-10-4035-2017-supplement.zip)
- [Last Interglacial](https://pmip4.lsce.ipsl.fr/doku.php/exp_design:lig)
  - Otto-Bliesner et al [(Geosci. Model Dev., 2017)](https://doi.org/10.5194/gmd-10-3979-2017) with its [supplement](https://www.geosci-model-dev.net/10/3979/2017/gmd-10-3979-2017-supplement.zip)
- [Mid Pliocene Warm Period](http://geology.er.usgs.gov/egpsc/prism/7_pliomip2.html)
  - Haywood et al [(Clim. Past, 2016)](https://dx.doi.org/10.5194/cp-12-663-2016) with its [supplement](http://www.clim-past.net/12/663/2016/cp-12-663-2016-supplement.pdf)

## PMIP4 experiments

- [Last Deglaciation](https://pmip4.lsce.ipsl.fr/doku.php/exp_design:degla)
  - Ivanovic et al [(Geosci. Model Dev., 2016)](https://dx.doi.org/10.5194/gmd-9-2563-2016)
- [Penultimate Deglaciation](https://pmip4.lsce.ipsl.fr/doku.php/exp_design:degla_t2)
  - Menviel et al [(Geosci. Model Dev., 2019)](https://dx.doi.org/10.5194/gmd-12-3649-2019) with its [(supplement)](https://www.geosci-model-dev.net/12/3649/2019/gmd-12-3649-2019-supplement.zip)
- [DeepMIP](http://www.deepmip.org/)
  - Lunt et al, [(Geosci. Model Dev., 2017)](https://dx.doi.org/10.5194/gmd-10-889-2017) with its [(supplement)](https://www.geosci-model-dev.net/10/889/2017/gmd-10-889-2017-supplement.zip)

## Boundary conditions data

The _BC_ datasets mentioned in the design pages are available on the [PMIP4 data](https://pmip4.lsce.ipsl.fr/doku.php/data:index) page.
