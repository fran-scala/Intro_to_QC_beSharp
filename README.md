# Hands-on Quantum Computing @ beSharp
This repository contains the code for the hands-on session of the Quantum Computing workshop at beSharp.   

The code is developed by [Francesco Scala](https://it.linkedin.com/in/fran-scala) and [Stefano Mangini](https://it.linkedin.com/in/stfnmangini) (PhD stuents @ University of Pavia). 

The hands-on session is divided in two parts: 

1. **Programming quantum computers**: this first part is focused on the basiscs of quantum computing programming, where we show how to program quantum computers and run circuits both on classical simulators as well as on real quantum computing hardware available through AWS's Braket.  
Notebook: `beSharp_1.ipynb`

2. **Variational quantum algorithms**: in this second part we use a class of new quantum algorithms, namely **variational quantum algorithsm** to showcase two applications of quantum computing technology: chemistry and classification.  
Notebook: `beSharp_2.ipynb`  

You can clone this repository to download the files and follow the tutorial acively running live the code with us.  

## Usage  

All quantum computing libraries, apart for very few execptions, are based on `python`. In this hands-on we'll use two different quantum packages:
- `braket` (by Amazon) used in the 1st and 2nd part
- `pennylane` (by Xanadu) used in the 2nd part

In order to follow the tutorials we suggest to create a new python environment (we use `conda` distribution). If using `conda`, you can run the following on the terminal to create an environment and install the necessary standard libraries:

```
conda create --name QCday python=3.8
conda activate QCday
conda install pip jupyter matplotlib 
```

and the quantum computing libraries
```
pip install amazon-braket-sdk
pip install pennylane
pip install amazon-braket-pennylane-plugin
```

Other libraries will be installed in the notebooks!


⚛️ *Have a great quantum coding session!* ⚛️ 



