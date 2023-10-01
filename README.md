


<h1 align="center">VelProfES</h1>

<p align="center" style="font-size: 15px;">by</p>

<h4 align="center" style="font-size: 5px; font-weight: bolder;">Anushka Joshi, Ph.D.</h4>

<h4 align="center" style="font-size: 5px; font-weight: bold;">Indian Institute of Technology, Roorkee</h4>

<h4 align="center" style="font-size: 5px; font-weight: bold;">October 2023</h4>


## Description

<p align="center">
<img src="Image/VelProfESArchitecture.jpg" alt="Model Architecture" width="600" height="1000">
</p>


VelProfES (Velocity Profiler using Ensemble ML models), a stacked ensemble machine learning model that utlizes the synthetic dataset generated using conditional tabular generative adversarial networks and ensemble of various models to predict the shear wave velocity.
1. Input: [ $S_c$, $S_t$, $S_{c1}$, $S_{c2}$, $S_a$, $N$]
2. Output: $V_s$ 
### Executing program

The program can be executed in the Google Colaboratory, Jupyter Notebook, or any other platform that runs Python code.

## Result
The result file named as 'Velocity_Result.csv' is generated after the execution of the code. The file consists of the predictions from all the selected individual machine learning models and the VelProfES model.

## Help

The following advices are suggested while executing the program:
1. The file location should be changed accordingly. The authors have used their respective file locations.
2. The tasks performed by the following functions are described below:
```python
# Python function
def read_Syn():
```
Is used to read the test dataset provided in it. It returns the X_test and y_test array that consists of input features and actual output prediction.
```python
# Python function
def Testing_on_Dataset()
```
Is the function that predicts the shear wave velocity ($V_s$) using the VelProfES model.
3. The file named 'Test_Dataset' is given as an input file for the prediction of $V_s$. The Table represents the name of the input features used in the VelProfES model to predict Vs and their terminologies given in the manuscript.

| Name               | Abbreviation used in manuscript         | 
| ---------------------|-----------------|
| bold                 | $S_c$ | 
| italic               | $S_t$     | 
|Strikethrough         |  $S_{c1}$       |  
|Bold and nested italic| $S_{c2}$ |  
|All bold and italic   | $S_a$       |   
|All bold and italic   | $N$      |   
|All bold and italic   | $V_s$      |   

# Author

**Anushka Joshi (corresponding author)**

- Email: anushka_j@cs.iitr.ac.in
- LinkedIn: https://www.linkedin.com/in/anushka-joshi-iitr/
- Website: https://anushkajoshi.wixsite.com/anushka-joshi
- Contact address: Machine Vision and Intelligence Labs, IIT Roorkee, 
  Department of Computer Science and Engineering, IIT Roorkee, 
  Uttarakhand, India, 247667; 

**Contributors**

- Prof. Balasubramanian Raman
- Prof. C Krishna Mohan
- Prof. Linga Reddy Cenkeramaddi

## Acknowledgments

The author thanks the PMRF funding agency for supporting the research.

