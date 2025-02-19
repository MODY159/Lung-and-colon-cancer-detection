# Fossil Age Prediction Dataset

## About Dataset
The Fossil dataset was created to provide a comprehensive and realistic foundation for training and evaluating machine learning models aimed at predicting fossil ages. The dataset is of intermediate difficulty and includes a variety of geological, chemical, and physical attributes that are significant in the study of fossil formation and preservation.

## Sources
The initial data was sourced primarily from PaleoBioDB, with additional private sources contributing to the dataset. After creating a small, initial dataset, a deep learning model was employed to expand and generate a synthetic version. This synthetic dataset simulates realistic scenarios, making it a valuable tool for data scientists and researchers in the field.

## Features

- **uranium_lead_ratio**: Ratio of uranium to lead isotopes in the fossil sample.
- **carbon_14_ratio**: Ratio of carbon-14 isotopes present in the fossil sample.
- **radioactive_decay_series**: Measurement of the decay series from parent to daughter isotopes.
- **stratigraphic_layer_depth**: Depth of the fossil within the stratigraphic layer, in meters.
- **isotopic_composition**: Proportion of different isotopes within the fossil sample.
- **fossil_size**: Size of the fossil, in centimeters.
- **fossil_weight**: Weight of the fossil, in grams.
- **geological_period**: Geological period during which the fossil was formed.
- **surrounding_rock_type**: Type of rock surrounding the fossil.
- **paleomagnetic_data**: Paleomagnetic orientation data of the fossil site.
- **stratigraphic_position**: Position of the fossil within the stratigraphic column.
- **age**: Calculated age of the fossil based on various features, in years.

## Usage

- Train and evaluate regression models to predict the age of fossils.
- Study the influence of geological, chemical, and physical attributes on fossil age.
- Enhance understanding of fossil formation and preservation processes.

## Applications

- Useful for paleontological research and educational purposes.
- Valuable for developing predictive models in geochronology and related fields.
- Can aid in improving methods for fossil dating and understanding historical geology.

## Sample Data

| uranium_lead_ratio | carbon_14_ratio | radioactive_decay_series | stratigraphic_layer_depth | geological_period | paleomagnetic_data | inclusion_of_other_fossils | isotopic_composition | surrounding_rock_type | stratigraphic_position | fossil_size | fossil_weight | age  |
|--------------------|-----------------|--------------------------|---------------------------|-------------------|--------------------|---------------------------|-----------------------|-----------------------|-----------------------|-------------|---------------|------|
| 0.738061           | 0.487707        | 0.907884                 | 91.17                     | Cretaceous        | Normal polarity    | False                     | 0.915951              | Conglomerate          | Middle                | 50.65       | 432.00        | 43523 |
| 0.560096           | 0.341738        | 1.121302                 | 165.44                    | Cambrian          | Normal polarity    | False                     | 0.803968              | Limestone             | Top                   | 48.85       | 353.29        | 44112 |
| 0.424773           | 0.218493        | 0.103855                 | 218.98                    | Cambrian          | Normal polarity    | True                      | 0.792441              | Shale                 | Bottom                | 37.66       | 371.33        | 43480 |
