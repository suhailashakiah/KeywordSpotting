# Keyword Spotting
Keyword spotting for trigger words in speech recognition systems. 

Used the Google Speech Commands Dataset. The task is to classify the words into 12 classes: yes, no, up, down, left, right, on, off, stop, go, silence, unknown

Accuracy achieved: 85.6%

<img width="576" alt="loss" src="https://user-images.githubusercontent.com/18056877/35026130-272fbd86-fb17-11e7-8ba0-9b11ec9dc903.png">

<img width="576" alt="normalized_cm" src="https://user-images.githubusercontent.com/18056877/35026166-53a65c08-fb17-11e7-9931-e9d6baa257f0.png">

### Code Hierarchi 

1. Collecting files and organizing data, making noise samples.ipynb
2. Creating noised data.ipynb
3. Data augmentation - Time shifting noised and unnoised data.ipynb	
4. Augmenting classes 0 to 9.ipynb
5. MFCC EXTRACTION.ipynb
6. Neural network.ipynb
7. Kaggle testing set performance.ipynb
