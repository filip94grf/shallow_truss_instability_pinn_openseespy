Shallow-Truss-Instability-PINN

This repository contains Physics-Informed Neural Network models for prediction of Von Mises shallow truss instability, using three algorithms including:
1. Adaptive moment estimation (Adam)
2. Nesterov-accelerated adaptive moment estimation (Nadam)
3. EvoLved Sign Momentum (Lion)
Also it contains the programming code in software OpenSeesPy, to get the results from numerical modeling

!!!Files contained Python scripts for complete reproduction of the developed PINN models!!!

!!!Before you run the analysis you must specify the geometrical and material properties, as well as spring stiffness: E1, E2, A1, A2, Lleft, Lright, h, Ks!!!

!!!To make completely the same results results are freezed using random.seed(seed_value), for each slope, material and geometrical properties!!!

Meaning of labels: PINN_ALGORITHM(SLOPE)_MATERIAL.ipynb where:
                   ALGORITHM: ADAM, NADAM or LION
                   SLOPE: 5, 15 or 25 degree
                   MATERIAL: E1E2 - when both bars are of the same stiffness ; E1 - when bar 1 is with higher stiffness ; E2 - when bar 2 is with higher stiffness

                   JBD25_OPENSEESi_VonMisesTruss_Nonlinear where:
                   OPENSEESi has values from 1 to 9 based on different structural models

Cite the article: Đorđević, F. and Marinković, M. (2024), “PINN Surrogate Model for Nonlinear Equilibrium Path Analysis of Von Mises Shallow Truss”, Journal of Big Data, Elsevier.
