# Melanoma Dtection using CNN



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
---

---
## General Information

- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
---

---
## Conclusions

- The final model had total 400970 paramerers
- The model was only trained for 30 epochs due to computational restraints
- the modle accuracy was 89.08% when compared to the validation accuracy of 88.55% 

---
- The under fitting of the first model was tackled by the final model
- The second model was grossly under fitting due to class imbalance which was rectified using Augmentor
- The number of training images increased due to the use of class rebalance techniques using Augmentor library
---
- The model seemed to perform well
- To be applicable on a deployable level the model needs more training data
and needs to be run for higher number of epochs 
---

---
## Technologies Used
- tensorflow
- matplotlib
- pathlib
- glob
- PIL
- sys
- os




## Contact
Created by [@abhishek-vmishra] - feel free to contact me!


