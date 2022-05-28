# Automated-Car-Insurance-Claims
# Objective:
Use computer vision and deep learning techniques to accurately classify vehicle damage to facilitate claims triage by training convolution neural networks.
# Use Case:
The rapidly expanding automobile industry highly backs the equally fast-growing auto insurance market. Although until now this industry has been solely based on traditional ways to make repair claims. In case of an unfortunate accident, the claims for the car damage needs to be filed manually. An inspector is required to physically analyze the vehicles to assess the damage and obtain a cost estimate.Automating such a process with the help of deep learning and remote usage would make the process a lot more convenient.
# Solution:
The model accepts an input image from the user and processes it across 4 stages:
- Validates that given image is of a car.
- Validates that the car is damaged.
- Finds location of damage as front, rear or side
- Determines severity of damage as minor, moderate or severe.
# Different models we are using for training:
- Resnet50
- InceptionV3
- VGG16
- VGG19
