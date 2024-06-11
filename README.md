# Sleep-Stage-Scoring-Using-EEG
The precise determination of sleep stages is a foundational element in the quantitative 
assessment of polysomnographic data. Conventionally, this task has been performed manually 
by experts through visual recognition of patterns, a method that can be both time-intensive and 
inherently subjective. Intending to surmount these obstacles, there is an increasing impetus for 
the adoption of automated classification techniques. In our research, we have engineered and 
assessed various machine learning models, such as Random Forest (RF), Support Vector 
Machine (SVM), and an integrated Convolution Neural Network and Long Shor Term memory 
(CNN-LSTM) framework, utilizing feature-based approaches alongside Artificial Neural 
Networks (ANNs) that process both features and raw data. Our findings indicate that the 
performance of most algorithms is on par with the level of agreement typically seen between 
human raters, especially in healthy individuals. 
Our analysis utilized a dataset[15] that conforms to the Rechtschaffen and Kales guidelines for 
systematic sleep stage classification, containing 197 full-night polysomnographic sleep studies 
featuring EEG, chin EMG, and EOG, along with select event markers. Additionally, subsets of 
this data include variables such as respiration and body temperature. The hypnograms 
associated with these PSG recordings have been meticulously scored by skilled technicians 
adhering to the 1968 Rechtschaffen and Kales manual.  
The evaluation of our proposed model yielded an impressive accuracy rate: 98% for WAKE 
stages, 91% for NREM stages, and 76% for REM stages. These figures notably surpass the 
accuracy rates of SVM and RF, which are approximately 90% and 94%, respectively. This 
demonstrates the superior capability of our model over some of the existing methodologies, 
including SVM and RF, in classifying sleep stages accurately. 
