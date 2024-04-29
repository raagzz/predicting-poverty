# Predicting Poverty
    Based on Predicting Poverty using Satellite Imagery and Machine Learning by Jean et al. (2016) and https://github.com/nealjean/predicting-poverty.

The objective is to use abundant sources of data (satellite imagery and nightlights data) to predict poverty levels on the order of a local level (single village). For some background, every few years the World Bank conducts surveys in developing countries to understand their living situations. As you might expect, this process is very time-consuming. If we can make a model that only uses abundant sources of data to predict values that otherwise have to be measured through expensive human efforts, then several possibilities arise:

    1. Prediction during "off-years" (when no surveys are collected).
    2. Real-time monitoring of poverty conditions.
    3. Potential for early-warning systems.

## Results

|Country| Year	 |R^2	|
|-------|--------|-------|
|Nigeria|	2013	|0.19|

![nigeria_results](https://github.com/raagzz/predicting-poverty/assets/87406829/36c64082-ed0d-4f76-bd93-9ce68cc7ce3a)

## Activation Map

Activation map visually depict what a CNN focusses on. We can infer roads tend to be a key area of focus, and the edges of bodies of water tend to be identified.

![img1](https://github.com/raagzz/predicting-poverty/assets/87406829/afc62a37-17fc-49d2-b974-4016a51e3976)![activations1](https://github.com/raagzz/predicting-poverty/assets/87406829/fb43dc9a-2e76-4ffb-be1d-48a7f689de30)

![img2](https://github.com/raagzz/predicting-poverty/assets/87406829/a4e9dd71-374d-4c53-b8fe-55016706c7f6)![activations2](https://github.com/raagzz/predicting-poverty/assets/87406829/d5a27a95-01ba-4f83-8dcb-340d47be53d0)
