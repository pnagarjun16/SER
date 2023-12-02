# SER

# Authors:
Nagarjuna Padala
Trinadh kumar Atmuri

We have faced tensorflow related issue in jupyter notebook, hence we used visual studio code to run the whole code.

If you are using any other environment other than VS code then replace the % with ! while installing packages.

# Instructions:

Download the notebook and the data files in order to execute the code. The notebook's first cell contains all essential installs, and the necessary imports are located after that.

Please run the ipynb file.

# Dataset:

We have used four different audion datasets namely
1. RAVDESS dataset - https://zenodo.org/records/1188976
2. CREMA D dataset - https://paperswithcode.com/dataset/crema-d
3. SAVEE dataset - http://kahlan.eps.surrey.ac.uk/savee/
4. TESS dataset - https://tspace.library.utoronto.ca/handle/1807/24487

# Model:

We are using 1D convolution neural networks with varied amount of layers as our models.
We have also used LSTM, but it does not perform as expected, hence we are just commenting out the code.

# Results:
We achieved 64.32% accuracy for the one layered CNN.
We achieved 66.22% accuracy for the three layered CNN.

Model predicted very well for angry and sad, It also hard for the humans to evaluate the emotion



# References:
https://medium.com/@diego-rios/speech-emotion-recognition-with-convolutional-neural-network-ae5406a1c0f7
https://www.mdpi.com/1424-8220/23/13/6212
https://www.intechopen.com/chapters/65993


