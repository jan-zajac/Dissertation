# A Mathematical Model for Quorum Sensing in Pseudomonas aeruginosa Using Machine Learning

🎓This repository holds my final year and dissertation project during my time at the University of Leeds titled 'A Mathematical Model for Quorum Sensing in Pseudomonas aeruginosa Using Machine Learning' .

## Abstract

The harmful pathogen Pseudomonas aeruginosa has been researched for years, yet even with its increasing understanding, it continues to burden healthcare services and infect vulnerable patients. The bacteria use their population to regulate their genetics, controlling a variety of factors which aid its survival and ability to infect. The ability is known as quorum sensing and it allows Pseudomonas aeruginosa to remain undetected by the host’s immune defences until the size of their colony is large enough to overpower the immune system and result in infection.  

A mathematical model with 11 constant variables has been generated by researcher (Dockery, 2001), that illustrated the quorum sensing mechanism in action. It models the release of a chemical called an autoinducer. However, there are many internal and external factors which can alter the mechanism and consequently the rate at which the autoinducer molecule is released. It has been assumed that the modification of the constant variables is representative of changing conditions, affecting the quorum sensing characteristic.  

Within this project, modern machine learning methods have been used to enhance the mathematical model, to account for the inherent variability of the mechanism. The constructed model is a neural network capable of predicting up to 4 constants in a range of +/-40% from their original values used in the literature, when provided with time-series autoinducer concentration data. Moreover, as the problem at hand is unique in its nature, with research in the domain being sparse, simpler practice examples are detailed. These provided insights into the tools and methods which were employed in the final enhanced model.  

Further work in this field has the potential of being used in a medical application, where the ability to forecast the quorum sensing behaviour in Pseudomonas aeruginosa could be used in infection prevention and treatment planning.  

#### Dataset

The datasets used in this project were user-generated through the integration of ODEs (ordinary differential equations). The project details 3 different systems.

<p align="center">
  <b>Some Links:</b><br>
  <br><br>
  <![linearequation](https://latex.codecogs.com/gif.latex?%5Cfrac%7Bdy%7D%7Bdt%7D%3Dm)>
</p>

![linearequation](https://latex.codecogs.com/gif.latex?%5Cfrac%7Bdy%7D%7Bdt%7D%3Dm)

<p align="center">![\Large x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?x%3D%5Cfrac%7B-b%5Cpm%5Csqrt%7Bb%5E2-4ac%7D%7D%7B2a%7D)</p>

#### Libraries Used

* [SciPy](https://www.scipy.org/)
* [Keras](https://keras.io/)
* [Talos](https://github.com/autonomio/talos)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)

#### Notes

* Carried out in IDE (PyCharm CE)
* OS: macOS Mojave Version: 10.14.4
