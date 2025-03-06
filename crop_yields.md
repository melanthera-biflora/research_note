# Concepts that may come in handy
* **retrospective crop yield mapping**: Retrospective crop yield mapping refers to the process of estimating past crop yields using remote sensing data, historical crop records, and/or environmental variables.
* **phenology**: when and how crops grow during the season.
# Yield monitor technology
* **Hardware**: High-arcuracy GPS and on-board sensors to estimate grain weight and moistures to produce yield map (Deines, 2021)
# Problem in crop yields mapping
* Lack of ground truth data (Deines, 2021) due to the difficulty to acquired and concentrated in commercial systems.
# Current research direction in crop yield mapping:
* Maintain capacity for satellite yield estimation that do not rely on in-situ measurements for caliberation are crucial, particularly in small holder systems.
# Current solution:
## Estimate yields from satellite data:
* Scalable Crop Yields Mapper (SCYM), 1st application in 2015: From crop models simulations, statistical relationship are derived from modeled crop phenology an growing season climate to predict these simulation. Then it is applied on pixel-to-pixel basis across regional scales (map from gridded climate datasets and crop type maps)
    * SCYM use data from APSIM to generate pseudo-observation (interesting!):
      Yield = β₀ + β_VI * GCVI + β_w * W
    * GCVI in most of the applications use vector of length 2, 1st GCVI => maximum value in early season (Jun 14 - July 19), late season (July 20-Aug 28)
* 
# Available datasets:
## Yield data:
- Corteva Agriscience: Yield monitor data for 1.002.958 fields from 2008 to 2018 with available yield map.
