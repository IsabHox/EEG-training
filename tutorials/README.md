# Setting up your environment

Since we work mostly with Python, here are some steps to set up an environment with conda.

- Step 1: make sure that anaconda is installed on your computer
- Step 2: launch the anaconda prompt
- Step 3: to create an environment named eeg, type in the command line: `conda create --name eeg python=3.7`
- Step 4: Activate your newly create conda environment with source activate `eeg`. 
- Step 5: Install additional packages with `conda install -c anaconda notebook spyder numpy scipy matplotlib pandas scikit-learn`
- Step 6: Some additional packages require to be installed through pip like mne (`pip install mne`)

# Important notice for epoch visualization
On some occasions, we will want to visualize the raw data or epochs as time series. Depending on your computer, navigator and OS, the visualization in the notebook may not be optimal. If this is the case, you can open spyder instead and run your code from there.
