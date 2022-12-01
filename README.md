# JointInversion
Jointly calibrate hydrofacies and hydraulic conductivity data points 

Folder :

Example in 2D :

2D-3facies_KandC_FieldSize : Code for section 4.2.

2D-3facies_KandC_NbHD : Code for section 4.3

2D-3facies_KandC_fixFacies : Used for section 4.4. Third and fourth columns of Table 4.

2D-3facies_KandC_NoBorehole : Used for section 4.4. Fifth column of Table 4.


Example in 3D :

3D-3facies_KandC : Code for section 5


Description of individual code present in each folder. They are all quite similar. Major changes concern the references and some technicalities mentioned in the article.

(Note : Cleaning is in progress.) 

covardm.m : compute covariance function

DensSpec1Ddl.m : Compute one-dimensional isotropic spectral density.

FigureCalibration.m : Programs to generate the figures presented in the article 

grille2.m and grille3.m : Generate coordinates on a 2D or 3D grid. 

KullbackLeibler.m : Compute the Kullback-Leibler

ObjFunc.m : Objective function used for the calibration

PGS_transform.m : Tranform the underlying Gaussian random fields to the categorical field

PGS_visuel_3facies.m : Visualize a pluriGaussian simulation

postcond.m : Perform post-conditoning by simple Kriging.

Reference_3facies.m : Aquifer reference

S_STBM_HD : calibration algorithm that replace the Gibbs sampler

S_STBM_nphases_GD.m : Joint calibration algorithm

StatisticsSimulation.m : Compute the statistics present in the article.

STBM.m , STBM_C.m and STBM_K.m : Generate Gaussian random fields for pluriGaussian simulation (STBM_C.m) and hydraulic conductivty fields (STBM_K.m) 

VanCorput.m : Generate a quasi-random sequence using the Van der Corput sequence.

varioFFT2D_dl.m : compute variogram using Fast-Fourier transform

Workplace.m : Place to lunch code.
