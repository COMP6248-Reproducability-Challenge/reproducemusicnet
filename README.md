# reproducemusicnet
reproduce paper "Learning Features of Music from Scratch", ICLR 2017

Original code(https://github.com/jthickstun/thickstun2017learning) from the author included are 6 notebooks: one for each of the 5 non-convex models discussed in the paper, and a notebook outlining the experimental setup for the linear models. 

To run our code you need to install following dependencies on Python 2:
- intraveltree
- tensorflow (we use tensorflow-1.10.0-cp27-cp27m-win_amd64.whl)
- scikit learn
- others module required for evluation

And you need to download MusicNet from the website(http://homes.cs.washington.edu/~thickstn/start.html) and store locally. To run our code, you need to change the folder to where you store the file.

To reproduce from scratch, you need to change "restore_weights" to "False", otherwise trained weights will be deployed. If you want to test the optimal values, please go to original code and download related folders with npy files. In our folder, some w.npy is not uploaded due to the size limitation.
