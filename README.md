# README for dlews_flu_V2.ipynb | Documentation

## Folder Structure

/content/
├──ewstools/
  ├──saved_classifiers/
    ├──bury_pnas_21/
      ├──len500/ # contains pre-trained DL models from general dynamical systems (bury et al. ) of length 500
├──EWSofInfectiousDiseases/
  ├──Trained_DL_models_and_testing/
    ├──trained_DL_models_and_DL_apply/ # contains pre-trained DL models
├── state_data/ # stores the pre-processed flu hospitalization .csv file for each state/location, ready to be used by DL model
├──predictions2/ # "predictions_path" used to dump the output DL predictions from DL model, organized by state
  ├──ensemble/ # contains the ensemble DL predictions, organized by state
├──state_data_epyestim/ # contains the flu .csv files that will be used by the EPYESTIM library for estimating R(t)
├──predictions_image_plots/ #contains the image (.jpg or .png) images of combined DL predictions and raw state data, organized by state/location
├──rt_crossings.csv # contains the points at which the time series EpyEstim used, has R(t) crossing 1


