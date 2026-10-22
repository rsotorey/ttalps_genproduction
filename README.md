# Cards for gridpacks production for ttALPs

Gridpacks are generated using the [`genproductions_scripts`](https://gitlab.cern.ch/cms-gen/genproductions_scripts) repository, using cards stored in the [`genproductions_cards`](https://gitlab.cern.ch/cms-gen/genproductions_cards) repository (for central requests).


This repository contains the cards defining the process to be generated and the desired cuts and settings:

- `tta_XGeV_proc_card.dat`: indicates the process to be generated

- `tta_XGeV_run_card.dat`: defines the particular options on how the generator will run and generate the process (collider type and energy, PDF set...), and kinematic cut values.

- `tta_XGeV_extramodels.dat`: declares the non-SM Lagrangians that need to be used for the generation.

- `tta_XGeV_customizedcards.dat`: sets the values of parameters of the model.

The cards are based on the ones in [kerstinlovisa/ttalps_MC_production](https://github.com/kerstinlovisa/ttalps_MC_production/tree/main)
