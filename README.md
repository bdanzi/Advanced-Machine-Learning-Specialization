In this programming assignment, your task is to analyse the mass spectrum of particle decaying into muon-antimuon (dimuon) pairs and figure out the mass of Z boson. Of course, the mass of Z boson can be looked up at the PDG, but it would much more fun to measure it yourself!

At week1 release, you can find the CSV file with dimuon events. If you make a histogram of mass distribution, you can fit a mixture of parametrised signal and background distributions into the shape of the histogram. The signal corresponds to a peak-like shape. The background for simplicity we estimate as a flat level. The parameters of the mixture will be the mass of Z boson and other estimations of the significance and uncertainty of the measurement.

To pass this assignment you have to fit the mixture of 1) Gaussian distribution and 2) flat distribution using scikit-optimise toolkit as it is described in the notebook here. Thus you obtain parameters of those distributions: 1) centre of the Gaussian, it's peak height, and deviation; 2) level of the background. All those parameters you have to submit for the grading as described in the notebook.

The dataset for this assignment is taken from CERN opendata portal http://opendata.cern.ch/record/545
