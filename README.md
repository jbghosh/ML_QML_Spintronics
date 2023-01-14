# Classical and quantum machine learning in spintronics.
In this project we demonstrate the applications of classical and quantum machine learning in spintronics. For details see `Classical and quantum machine learning applications in spintronics', Kumar Ghosh, Sumit Ghosh [arXiv:2207.12837].



## Relevant files for Classical ML:

Classical ML is implemented in RF_fit.ipynb

Train.npy contains training data.

Test.npy contains testing data for 3 specific configuration used in Fig.3 of main text. Each set contains 201 data points.

#### Data structure for Classical ML:

Column

[1-16] Magnetic configurations of the 16 magnetic sites ( $\pm1$ ).
  [17] Energy (0.0->200.0).
  [18] Transmission coefficient (0.0->2.0).
  [19] Non-equilibrium $S_x$ component of 6th magnetic site (-2.0->2.0).
  [20] Non-equilibrium $S_y$ component of 6th magnetic site (-2.0->2.0).


## Relevant files for Quantum ML:

Quantum ML is implemented in QSVM.ipynb

The relevant data file for quantum machine learning is TrainQ.npy. This data is used to generate Fig.6.

#### Data structure for Quantum ML:

Coloumn 

[1] Rashba parameter (0.05->0.25).
[2] Transmission energy (0.0->2.0).
[3] Sign of non-equilibrium $S_x$ component of 6th magnetic site ( $\pm1$ ).
[4] Sign of non-equilibrium $S_y$ component of 6th magnetic site ( $\pm1$ ).
