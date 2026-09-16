# bias_solar_energy_prediction
Analysis of bias effect on a solar-energy prediction neuron
# Bias in Solar Energy Prediction Neuron

## Objective
To analyze how bias affects the pre-activation value of a neuron used for solar-energy prediction.

## Formula
Pre-activation value:

z = (weight × input) + bias

## Methodology
1. Give an input value to the neuron.
2. Apply a fixed weight.
3. Test different bias values.
4. Calculate the pre-activation value.
5. Compare the resulting decision response.

## Bias Values Tested
- Bias = -3
- Bias = 0
- Bias = 2
- Bias = 5

## Result
Changing the bias shifts the neuron's pre-activation value.

A negative bias shifts the response downward, while a positive bias shifts it upward.

## Decision Response
A threshold is used to observe how changing the bias can change the neuron's decision from LOW to HIGH.

## Conclusion
Bias provides an adjustable shift to the neuron's response. Proper bias adjustment helps the neuron produce predictions within the desired range.

## Tools Used
- Python
- Google Colab
- GitHub
- Matplotlib
- ## Graph

![Effect of Bias on Neuron Output](Screenshot%202026-09-16%20231731.png)
