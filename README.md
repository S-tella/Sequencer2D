project of Vit using BiLSTM2D instead of self attention , all the project was trained over cifar10 dataset

In this repo there are 4 main Jupiter notebook files, with the implementation of a vision transformer architecture that use Bilstm2d instead of self attention. -1 is made by sequencer small (second seqBlock has 8 sequencers), and was trained over 10 and 5 classes

-1 is made by small sequencer size and was trained only over 2 classes -1 made by medium sequencer size (second sequencer block has 14 sequencers)and was trained over 5-10 classes -1 made by medium sequencer size (second sequencer block has 14 sequencers), was trained over 2 classes

The latter file named VanillaSequencer is an experiment using the same architecture vit with Bilstm plain.

The results achieved are not very good, accuracy still low and fluctuating even after 30 epochs of training.The accuracy for medium and small size over 5 classes training was of 21-30%,while for the one trained over 2 classes was about 56%, that is very low, especially for a binary classification tasks.

To Install— It is very easy, as it’s said in requirements.txt the only package needed to run the code are Pytorch , numpy, sklearn . It is needed to download the cifar10 dataset in order to run the project All the project was developed in python 3.8.5

P.s. more specific details about the architecture, the code and the issues are in the report file, and in the Jupiternotebooks as description to the code.
