# PMIP7 experiment status and potential contributions

| expt | protocol | running | uploaded | analysed | 
|---|---|---|---|---|
| [abrupt-127k](#abrupt-127k) | ✅ | ☐ | ☐ | ☐ |
| [latePliocene](#pliomip3) | ✅ | ✅ | ☐ | ☐ |
| [earlyPliocene](#pliomip3) | ✅ | ✅ | ☐ | ☐ |
| [past2k](#past2k) | ☐ | ☐ | ☐ | ☐ |
| [midHolocene](#Interglacials) | ☐ | ☐ | ☐ | ☐ |
| [lig127k](#Interglacials) | ✅ | ☐ | ☐ | ☐ |
| [lgm](#lgm) | ☐ | ☐ | ☐ | ☐ |
| [eocene-5x](#deepmip) | ✅ | ☐ | ☐ | ☐ |
| MioMIP2 | ✅ | ☐ | ☐ | ☐ |
| HighResPMIP | ☐ | ☐ | ☐ | ☐ |
| PMIP-carbon | ☐ | ☐ | ☐ | ☐ |
| __Affiliated Efforts__| | | | |
| _WhatIfMIP_ | ☐ | ☐ | ☐ | ☐ |
| _IMPACTS_ | ☐ | ☐ | ☐ | ☐ |
| _D-O-MIP_ | ☐ | ☐ | ☐ | ☐ |


## abrupt-127k

**Protocol**: The experimental protocol has been developed and approved by CMIP. Initial description of it can be found on the [Assessment Fast Track webpage](https://wcrp-cmip.org/cmip-phases/cmip7/fast-track/). The full protocol, along with suggested analyses, is published in GMD as [Sime et al. (2026)](https://gmd.copernicus.org/articles/19/5881/2026/).

**Contributors**

| # | Name | Email address | Institution | Model | Notes |
|---|---|---|---|---|---|
| 1 | Christian Stepanek | Christian.Stepanek@awi.de | AWI | AWI-ESM3 | |
| 2 | Christian Stepanek | Christian.Stepanek@awi.de | AWI | AWI-ESM2 | |
| 3 | Sandeep Narayanasetti | sandeep.cat@tropmet.res.in | IITM | CCCR-IITM | |
| 4 | Masakazu Yoshimori & Takashi Obase | masakazu@aori.u-tokyo.ac.jp & tobase@jamstec.go.jp | MIROC | MIROC7 | Aiming to start in Jul 26 |
| 5 | Qiong Zhang | Qiong.zhang@natgeo.su.se | Stockholm | EC-Earth4 | |
| 6 | John Dunne & Lore Sentman | John.Dunne@noaa.gov & Lori.Sentman@noaa.gov | NOAA-GFDL | GFDL-ESM4 | |
| 7 | Kohe Yoshida & Yasuto Watanabe| kyoshida@mri-jma.go.jp  &  ywatanabe@mri-jma.go.jp | MRI | MRI-ESM3 | |
| 8 | Chris Jones | Chris.d.jones@bristol.ac.uk | Bristol | HadCM3-Bris | |
| 9 | Evgeny Volodin | volodinev@gmail.com | INM | INMCM6 | |
| 10 | Matt Pollock | matt.pollock.24@ucl.ac.uk | UCL | UKESM1.3 | Not started |
| 11 | Shih-Yu Lee | shihyu@gate.sinica.edu.tw | AS-RCEC | TaiESM | |
| 12 | Kira Rehfeld | kira.rehfeld@uni-tuebingen.de | Tübingen | ICON | Simulation complete but hoping to re-run with final-final model |
| 13 | Louise Sime & Xu Zhang | lsim@bas.ac.uk | BAS-UK | UKCM2 | |
| 14 | Sophia Macarewich & Bette Otto-Bliesner | ottobli@ucar.edu | NCAR | CESM3 | Model close to release in Jul 26 |

## Interglacials

The simulation roster will again be organized in Tiers.
* Tier 0 (PMIP Quaternary Interglacials "DECK")
  *  piControl (slight updates since PMIP4 due to slight changes in the CMIP7 piControl configuration)
  * midHolocene (slight updates in those settings that refer to piControl, see above)
  * abrupt-127k (slight updates in those settings that refer to piControl, as mentioned in the revised protocol paper)
  * lig127k (based on abrupt-127k)
* Tier 1 (studying different expressions of Quaternary Interglacial intensity in a multi-model ensemble)
  * mis11c (408k orbital forcing, modern geography)
  * mis31 (1072k orbital forcing, modern geography)
* Tier 2: testing sensitivity to
  * freshwater forcing
  * vegetation
  * ice sheets
  * land sea mask
  * transient climate forcing

So, modelling groups could run all Tier 0 experiments based on only three simulations (that is, if they just extend abrupt-127k towards equilibrium). If they have the capacity for two more simulations (without the need to change any model geography) they could also fulfill Tier 1. Tier 2 simulations will cater for diverse interests. _It is not expected that every group will run all (or even any) of these simulations._ Yet, the protocol is available for interested groups to further explore specific aspects of Quaternary Interglacial sensitivity to different aspects of model forcing and boundary conditions.

**Contributors**

| Experiment | Institution | Model | Contact |
|---|---|---|---|
| lig127k | BAS-UK | UKCM2 | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |
| lig127k | BAS-UK | HadGEM3-GC5-LL | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |
| lig127k | NCAR | CESM3 | Sophia Macarewich & Bette Otto-Bliesner (ottobli@ucar.edu) — model close to release in Jul 26 |
| lig127k | AWI | AWI-ESM3 | Christian Stepanek (Christian.Stepanek@awi.de) |
| midHolocene | BAS-UK | UKCM2 | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |
| midHolocene | BAS-UK | HadGEM3-GC5-LL | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |
| midHolocene | NCAR | CESM3 | Sophia Macarewich (macarew@ucar.edu) — model close to release in Jul 26 |
| midHolocene | AWI | AWI-ESM3 | Christian Stepanek (Christian.Stepanek@awi.de) |

## PlioMIP3

**Overview**: PlioMIP3 is progressing well, though the timeline has slipped somewhat from initial intentions. The first phase of simulations is expected to be uploaded by end of June 2026, with more complex models running considerably later. A [special issue](https://www.sciencedirect.com/special-issue/10JFLHTHPZH) is open for model description papers, and many of the intercomparison papers will also be submitted there.

**Main experiments**: As well as the pre-industrial control, there are two time period experiments and a suggested set of sensitivity/factorisation experiments. The Late Pliocene (LP) experiment is identical to PlioMIP2, so existing PlioMIP2 LP simulations will carry over to PlioMIP3. Some additional new LP experiments are also planned. The Early Pliocene includes the additional of an open Central American Seaway

**Planned intercomparison papers** (targeting before March 2027):
1. A new Late Pliocene paper incorporating both PlioMIP2 simulations and new PlioMIP3 additions
2. An Early Pliocene paper focusing on the effects of opening the Central American Seaway (CAS) and raised CO₂


### Contributing Groups

The table below is based on a spreadsheet provided by the PlioMIP3 coordinators. It is not a perfect representation of the current state, but provides a good indication of planned contributions.

| # | Group | Model | Contact | Timescale / Notes |
|---|---|---|---|---|
| 1 | Leeds | HadCM3 | Julia Tindall (earjcti@leeds.ac.uk) | Core runs completed Jan 2025; LP_pi_EAIS expected Apr/May 2025 |
| 2 | Leeds | HadGEM2 | Julia Tindall (earjcti@leeds.ac.uk) | Uncertain whether runs will be completed |
| 3 | Bergen | NorESM1-F | Z. Zhang | |
| 4 | Bergen | NorESM2 | Z. Zhang | |
| 5 | UCL | HadGEM3/UKESM1 | Charlie Williams (charles.williams@ucl.ac.uk) | |
| 6 | Stockholm | EC-Earth | Qiong Zhang (Qiong.zhang@natgeo.su.se) | |
| 7 | Tokyo | MIROC4m | Wing-Le Chan (wlchan@aori.u-tokyo.ac.jp) | Core, extension and most optional runs finished as of summer 2025 |
| 8 | UNSW | ACCESS-ESM1.5 | Hutchinson/Santra | |
| 9 | NCAR-UCONN | iCESM1.2 | Ran Feng (ran.feng@uconn.edu) | |
| 10 | NCAR-UCONN | iCESM1.3 | Ran Feng (ran.feng@uconn.edu) | Target March/April 2025 |
| 11 | NCAR-UCONN | CESM2 | Ran Feng (ran.feng@uconn.edu) | Target March/April 2025 |
| 12 | NCAR-UCONN | CESM3 | Ran Feng (ran.feng@uconn.edu) | Will take most of 2025 |
| 14 | AWI | AWI-ESM2 | Christian Stepanek (Christian.Stepanek@awi.de) | Core runs by March 2025; further runs to follow; focus on vegetation dynamics sensitivity |
| 15 | AWI | AWI-ESM3 | Fernanda Matos (Fernanda.Matos@awi.de) | Core runs by March 2025; additional runs to follow |
| 16 | NASA-GISS | ModelE2.1.2 | Linda Sohl (les14@columbia.edu) | Core runs by Dec 2025; extent of additional runs uncertain |
| 17 | NASA-GISS | ROCKE-3D | Linda Sohl (les14@columbia.edu) | To be run with both GISS radiation and SOCRATES schemes |
| 18 | Utrecht | CESM1.05 (CCSM4-Utr) | | |
| 19 | Toronto | CCSM4-UoT | | |
| 20 | LSCE | IPSLCM6A-LR | A-C Sarr | Currently no plans; A-C Sarr starting new position in France early 2026 and will attempt runs then |
| 24 | MRI | MRI-CGCM 2.3 | Kohe Yoshida & Yasuto Watanabe (kyoshida@mri-jma.go.jp & ywatanabe@mri-jma.go.jp) | |

## DeepMIP

DeepMIP-Eocene is focused on the early Eocene climatic optimum (EECO), with its main simulation being eocene-5x. The protocol describing this experiment is [Lunt et al, 2026](https://gmd.copernicus.org/articles/19/6143/2026/).They maintain a relatively up-to-date [website](https://www.deepmip.org/model-working-group/), from which the table below is taken.

| # | Institution | Model | Contact |
|---|---|---|---|
|1| Bristol | UKESM/HadGEM3 | Zikun Ren (zikun.ren@bristol.ac.uk) |
|2| Bristol | HadCM3 | Dan Lunt (dan.lunt@bristol.ac.uk) |
|3| IPSL | IPSL-CM5A2 | Ladant|
|4| | UVIC | Meissner|
|5| UNSW | GFDL | Hutchinson|
|6| UNSW | ACCESS | Hutchinson/Santra|
|7| Bergen | NORESM | Z. Zhang|
|8| AWI | | Niezgodzki|
|9| Tokyo | MIROC | Chan/Abe-Ouchi|
|10| | CESM1.2 | De Boer|
|11| | FGOALS | Zhao|
|12| | ICON | Kelemen|
|13| NCAR-UCONN | CESM2/CESM3 | Zhu / Otto-Bliesner|
|14| | PlaSim | Rehfeld|
|15| Stockholm | EC-Earth | Qiong Zhang (Qiong.zhang@natgeo.su.se) |
|16| | cGENIE | Ridgwell|
|17| EC-Earth-Consortium | EC-Earth4 | Coppo/Davini|

## past2k

The protocol paper draft is well advanced and will be share soon with the modelling center.

The preliminary list of groups interested in running the simulations is past2K simulations

1. IPSL, Myriam Khodri
2. EC-Earth4, Qiong Zhang (Qiong.zhang@natgeo.su.se)
3. ICON, Sebastian Wagner & Johann Jungclaus
4. MIROC6-iso, Kei Yoshimura
5. iCESM1.3, Liang Ning (Nanjing)

## lgm

| Institution | Model | Contact | Notes |
|---|---|---|---|
| NCAR | CESM3 | Jiang Zhu (jiang.zhu@ucar.edu) | Model close to release in Jul 26 |