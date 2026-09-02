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
| [MioMIP2](#miomip2) | ✅ | ☐ | ☐ | ☐ |
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
| 1 | Laurie Menviel | l.menviel@unsw.edu.au | UNSW | ACCESS-ESM1.6 | |
| 2 | Christian Stepanek | Christian.Stepanek@awi.de | AWI | AWI-ESM2 | |
| 3 | Christian Stepanek | Christian.Stepanek@awi.de | AWI | AWI-ESM3 | |
| 4 | He Zhang | zhanghe@mail.iap.ac.cn | CAS | CAS-ESM | Aiming for Dec 2026 |
| 5 | Weipeng Zheng | zhengwp@mail.iap.ac.cn | CAS | CAS-FGOALS | Aiming for Dec 2026 |
| 6 | Sandeep Narayanasetti | sandeep.cat@tropmet.res.in | IITM | CCCR-IITM | Not started |
| 7 | Sophia Macarewich & Bette Otto-Bliesner | ottobli@ucar.edu | NCAR | CESM3 | Model close to release in Jul 26 |
| 8 | Qiong Zhang | Qiong.zhang@natgeo.su.se | Stockholm | EC-Earth4 | T255 |
| 9 | John Dunne & Lori Sentman | John.Dunne@noaa.gov & Lori.Sentman@noaa.gov | NOAA-GFDL | GFDL-ESM4 | Pre-Dec 2026 |
| 10 | Allegra LeGrande | allegra.n.legrande@nasa.gov | NASA | GISS-E2.1 | Completed |
| 11 | Allegra LeGrande | allegra.n.legrande@nasa.gov | NASA | GISS-E3.1 | Not started |
| 12 | Chris Jones | Chris.d.jones@bristol.ac.uk | Bristol | HadCM3-Bris | Not started |
| 13 | Kira Rehfeld | kira.rehfeld@uni-tuebingen.de | Tubingen | ICON | Simulation complete but hoping to re-run with final-final model |
| 14 | Evgeny Volodin | volodinev@gmail.com | INM | INMCM6 | Completed |
| 15 | Masa Kageyama | masa.kageyama@lsce.ipsl.fr | LSCE | IPSL-CM7 | Not started |
| 16 | Masakazu Yoshimori & Takashi Obase | masakazu@aori.u-tokyo.ac.jp; tobase@jamstec.go.jp | MIROC | MIROC7 | Aiming to start in Aug 26 |
| 17 | Kohe Yoshida & Yasuto Watanabe | kyoshida@mri-jma.go.jp; ywatanabe@mri-jma.go.jp | MRI | MRI-ESM3 | |
| 18 | Jian Cao | jianc@nuist.edu.cn | NUIST | NESM4 | not sure if before Dec |
| 19 | Shih-Yu Lee | shihyu@gate.sinica.edu.tw | AS-RCEC | TaiESM | |
| 20 | Louise Sime & Xu Zhang | lsim@bas.ac.uk | BAS-UK | UKCM2 | |
| 21 | Ed Blockley | matt.pollock.24@ucl.ac.uk | UKMO | UKESM1.3 | Underway |

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
| lig127k | AWI | AWI-ESM3 | Christian Stepanek (Christian.Stepanek@awi.de) |
| lig127k | NCAR | CESM3 | Sophia Macarewich & Bette Otto-Bliesner (ottobli@ucar.edu) — model close to release in Jul 26 |
| lig127k | Stockholm | EC-Earth4 | Qiong Zhang (Qiong.zhang@natgeo.su.se) |
| lig127k | BAS-UK | HadGEM3-GC5-LL | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |
| lig127k | Tubingen | ICON | Kira Rehfeld & Group (kira.rehfeld@uni-tuebingen.de) — also hoping for some sensitivity runs |
| lig127k | INM | INMCM6 | Evgeny Volodin & Polina Morozova (volodinev@gmail.com; morozova_polina@mail.ru) — possibly |
| lig127k | LSCE | IPSL-CM7 | Masa Kageyama (masa.kageyama@lsce.ipsl.fr) |
| lig127k | BAS-UK | UKCM2 | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |
| midHolocene | AWI | AWI-ESM3 | Christian Stepanek (Christian.Stepanek@awi.de) |
| midHolocene | NCAR | CESM3 | Sophia Macarewich (macarew@ucar.edu) — model close to release in Jul 26 |
| midHolocene | BAS-UK | HadGEM3-GC5-LL | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |
| midHolocene | INM | INMCM6 | Evgeny Volodin & Polina Morozova (volodinev@gmail.com; morozova_polina@mail.ru) |
| midHolocene | BAS-UK | UKCM2 | Louise Sime & Xu Zhang (lsim@bas.ac.uk) |

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
| 1 | UNSW | ACCESS-ESM1.5 | Gabriel Pontes (g.pontes@leeds.ac.uk) | |
| 2 | AWI | AWI-ESM2 | Christian Stepanek (Christian.Stepanek@awi.de) | Core runs by March 2025; further runs to follow; focus on vegetation dynamics sensitivity |
| 3 | AWI | AWI-ESM3 | Fernanda Matos (Fernanda.Matos@awi.de) | Core runs by March 2025; additional runs to follow |
| 4 | CAS | CAS-FGOALS | Weipeng Zheng (zhengwp@mail.iap.ac.cn) | complete |
| 5 | Toronto | CCSM4-UoT | | |
| 6 | Utrecht | CESM1.05 (CCSM4-Utr) | | |
| 7 | NCAR-UCONN | CESM2 | Ran Feng (ran.feng@uconn.edu) | Target Sept 2026 |
| 8 | NCAR-UCONN | CESM3 | Michelle Dvorak (mtdovark@uw.edu) | |
| 9 | Stockholm | EC-Earth4 | Qiong Zhang (Qiong.zhang@natgeo.su.se) | T255 |
| 10 | Leeds | HadCM3 | Julia Tindall (earjcti@leeds.ac.uk) | Core runs completed Jan 2025; LP_pi_EAIS expected Apr/May 2025 |
| 11 | UCL | HadGEM3/UKESM1 | Charlie Williams (charles.williams@ucl.ac.uk) | |
| 12 | NCAR-UCONN | iCESM1.3 | Ran Feng (ran.feng@uconn.edu) | Completed |
| 13 | LSCE | IPSLCM6A-LR | A-C Sarr | Not certain |
| 14 | Tokyo | MIROC4m | Wing-Le Chan (wlchan@aori.u-tokyo.ac.jp) | Core, extension and most optional runs finished as of summer 2025 |
| 15 | MRI | MRI-CGCM 2.3 | Kohe Yoshida & Yasuto Watanabe (kyoshida@mri-jma.go.jp; ywatanabe@mri-jma.go.jp) | |
| 16 | Bergen | NorESM1-F | Z. Zhang | |
| 17 | Bergen | NorESM2 | Z. Zhang | |
| 18 | NASA | ROCKE-3D | Linda Sohl (les14@columbia.edu) | To be run with both GISS radiation and SOCRATES schemes |

## DeepMIP

DeepMIP-Eocene is focused on the early Eocene climatic optimum (EECO), with its main simulation being eocene-5x. The protocol describing this experiment is [Lunt et al, 2026](https://gmd.copernicus.org/articles/19/6143/2026/).They maintain a relatively up-to-date [website](https://www.deepmip.org/model-working-group/), from which the table below is taken.

| # | Institution | Model | Contact | Notes |
|---|---|---|---|---|
|1| UNSW | ACCESS | David Hutchinson (david.hutchinson@unsw.edu.au) | Not certain |
|2| | CESM1.2 | De Boer | |
|3| NCAR-UCONN | CESM2/CESM3 | Zhu / Otto-Bliesner | |
|4| | cGENIE | Ridgwell | |
|5| EC-Earth-Consortium | EC-Earth4 | Renata Coppo (r.coppo@isac.cnr.it) | T63 not T255 |
|6| | FGOALS | Zhao | |
|7| UNSW | GFDL | David Hutchinson (david.hutchinson@unsw.edu.au) | End of 2026 |
|8| Bristol | HadCM3 | Dan Lunt (dan.lunt@bristol.ac.uk) | |
|9| | ICON | Kelemen | |
|10| INM | INMCM6 | Evgeny Volodin (volodinev@gmail.com) | |
|11| LSCE | IPSL-CM5A2 | Jean-Baptiste Ladant (jean-baptiste.ladant@lsce.ipsl.fr) | |
|12| Tokyo | MIROC | Chan/Abe-Ouchi | |
|13| Bergen | NORESM | Z. Zhang | |
|14| | PlaSim | Rehfeld | |
|15| Bristol | UKESM/HadGEM3 | Zikun Ren (zikun.ren@bristol.ac.uk) | |
|16| | UVIC | Meissner | |
|17| AWI | | Niezgodzki | |

## past2k

The protocol paper draft is well advanced and will be share soon with the modelling center.

The preliminary list of groups interested in running the simulations is past2K simulations

1. EC-Earth4, Qiong Zhang (Qiong.zhang@natgeo.su.se) — T159 not T255
2. iCESM1.3, Liang Ning (Nanjing)
3. ICON, Sebastian Wagner & Johann Jungclaus
4. INMCM6 (INM), Evgeny Volodin & Polina Morozova (volodinev@gmail.com; morozova_polina@mail.ru) — would prefer past1000
5. IPSL-CM7 (IPSL), Myriam Khodri (myriam.khodri@locean.ipsl.fr)
6. MIROC6-iso, Kei Yoshimura

## lgm

| Institution | Model | Contact | Notes |
|---|---|---|---|
| UNSW | ACCESS-ESM1.5 | Himadri Sinai (himadri.saini@unimelb.edu.au) | |
| NCAR | CESM3 | Jiang Zhu (jiang.zhu@ucar.edu) | Model close to release in Jul 26 |
| Stockholm | EC-Earth4 | Qiong Zhang (qiong.zhang@natgeo.su.se) | T255 |
| INM | INMCM6 | Evgeny Volodin & Polina Morozova (volodinev@gmail.com; morozova_polina@mail.ru) | |
| LSCE | IPSL-CM7 | Masa Kageyama (masa.kageyama@lsce.ipsl.fr) | fingers crossed |

## MioMIP2

| Institution | Model | Contact | Notes |
|---|---|---|---|
| CAS | CAS-FGOALS | Weipeng Zheng (zhengwp@mail.iap.ac.cn) | complete |
| UNSW | GFDL | David Hutchinson (david.hutchinson@unsw.edu.au) | with MioMIP1 boundary conditions |