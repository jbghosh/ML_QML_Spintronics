# Classical and quantum machine learning in spintronics.
In this project we demonstrate the applications of classical and quantum machine learning in spintronics. 

Classical ML is implemented in RF_fit.ipynb

### Relevant files for classical ML:

Train.npy contains training data.

Test.npy contains testing data for 3 specific configuration

used in Fig.3 of main text. Each set contains 201 data points.

### Data structure for Classical ML:

First 16 coloumns (in +1,-1) describe the magnetic configurations of the 16 magnetic sites.

17th column describes energy (between 0 and 200).

18th column represents the transmission.

19 and 20 column are spin-components $Sx$ and $S_y$ for 6th magnetic site respectively.

#### Quantum ML is implemented in QSVM.ipynb

The relevant data file for quantum machine learning is TrainQ.npy

First 2 coloumns of the dataset represent Rashba parameter ( $t_R$ ) and the transmission energy ( $E$ ) respectively. The third column onwards represent different class columns, the sign of non-equilibrium $S_{x,y}$ on each site as the two output classes.
