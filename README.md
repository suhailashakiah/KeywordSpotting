# Keyword Spotting
Keyword spotting for trigger words in speech recognition systems. 

Used the Google Speech Commands Dataset. The task is to classify the words into 12 classes: yes, no, up, down, left, right, on, off, stop, go, silence, unknown

Accuracy achieved: 85.6%

<img width="576" alt="normalized_cm" src="https://user-images.githubusercontent.com/18056877/35025961-43ae89fc-fb16-11e7-819e-a5015e301f2e.png">

### Code Hierarchi 

1. Collecting files and organizing data, making noise samples.ipynb
2. Creating noised data.ipynb
3. Data augmentation - Time shifting noised and unnoised data.ipynb	
4. Augmenting classes 0 to 9.ipynb
5. MFCC EXTRACTION.ipynb
6. Neural network .ipynb
7. Kaggle testing set performance.ipynb

The model is provided as a json string in 'model12_json' for reconstruction. The trained weights are provided in 'model12_weights.h5'.

