# Predicting a Pulsar Star

**<center>Outline</center>**
**Part I** - *What is a Pulsar Star?*<br>
**Part II** - *Dataset information*<br>
**Part III** - *Variables analysis*<br>
**Part IV** - **Machine Learning analysis**<br>
            *a. Model setting*<br>
            *b. Random Forest Classifier*<br>
            *c. Logistic Regression Classifier*<br>
            *d. Decision Tree & Extra Tree Classifier*<br>
            *e. Gradient Boosting Classifier*<br>
            *f. Gaussian NB Classifier*<br>
            *g. K-NN Classifier*<br>

## **Part I - What is a Pulsar Star?** <br>
### Definition
In the field of *Astronomy* and *Physics*, The ***Pulsar*** or Pulsar star is a special type of stellar stars that is a highly magnetised rotating neutron star emits beams of EMR out of its magnetic poles. However, the radiation can only be observed when a beam of emission is pointing towards Earth, like a lighthouse.<br>

### Formation
According to the Stellar Evolution Theory, the **formation** of a pulsar begin when the core of a massive star is compressed during a supernova, which collapses into a neutron star.

### Density and pressure
Overall densities ~ 3.7 x 10^17 ~ 5.9 x 10^17 kg/m^3 - 10^14 g/cm^3

### Applications
#### Maps
Because pulsars are emitting very regular pulses of radio waves and its radio transmissions do not require daily corrections. Pulsar positioning could create a spacecraft navigation system independently.
#### Precise clocks
ms pulsars' regularity of pulsation is even more precise than an atomic clock.
#### Probes of the interstellar medium
#### Probes of space-time
#### Gravitational waves detectors

### Famous pulsars
1. PSR B1919+21 - 1st radio pulsar with the period of 1.337s
2. PSR 1913+16 - 1st binary pulsar
3. Vela Pulsar - brightest pulsar
4. PSR B1937+21 - 1st ms pulsar

## **Part II - Dataset information** <br>
The **HTRU2** (**High Time Resolution Universe Survey**) dataset collects a total of 17,898 observations - 1,639 are positive examples and 16259 are negative. There are 8 continuous variables and one attribute of target class: <br>

a. Mean of the integrated profile<br>
b. Standard deviation of the integrated profile<br>
c. Excess kurtosis of the integrated profile<br>
d. Skewness of the integrated profile<br>
e. Mean of the DM-SNR curve;<br>
f. Standard deviation of the DM-SNR curve<br>
g. Excess kurtosis of the DM-SNR curve<br>
h. Skewness of the DM-SNR curve<br>
i. target class - uses "1" represents candidates identified positively as pulsar and 0 otherwise<br>

Variables a - d are Stats for pulsar detection and variables e - h are Stats generated from DM-SNR curve. The 'target class' is the discrete variable to determine star candidates is pulsar or not.<br>

## **Part III - Data analysis**
Data dimensions: 17898 rows with 9 columns
Data information: 17898 non-null values of float 64

## **Part IV - Machine Learning analysis**<br>
Please see ***Predicting a Pulsar.ipynb*** for more information.<br>
*a. Model setting*<br>
*b. Random Forest Classifier*<br>
*c. Logistic Regression Classifier*<br>
*d. Decision Tree & Extra Tree Classifier*<br>
*e. Gradient Boosting Classifier*<br>
*f. Gaussian NB Classifier*<br>
*g. K-NN Classifier*<br>

## **Summary**<br>
To compare six classifiers above,
List of accuracy score:<br>
a. ***Random Forest***: 0.9773<br>
b. ***Logistic Regression***: 0.9763<br>
c. ***Decision Tree Extra Tree***: 0.9642 - 0.9639<br>
d. ***Gradient Boosting***: 0.9752<br>
e. ***Gaussian NB***: 0.9380<br>
f. ***K-NN***: 0.9695<br>
## **Reference**<br>

H-R diagram from wikipedia
https://en.wikipedia.org/wiki/Hertzsprung%E2%80%93Russell_diagram

Pulsar from wikipedia
https://en.wikipedia.org/wiki/Pulsar

Predicting-pulsar-star
https://github.com/Smarty2298/Predicting-pulsar-star

Predicting pulsar star in the universe
https://www.kaggle.com/pavanraj159/predicting-pulsar-star-in-the-universe/comments

Neutron stars
https://apatruno.wordpress.com/neutron-stars/

Neutron star
https://en.wikipedia.org/wiki/Neutron_star#Structure
