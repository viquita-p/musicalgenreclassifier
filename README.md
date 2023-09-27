# Musical Genre Classifier

This is a musical genre classifier based on rough path theory. I used the signature transform to extract a feature set from a musical waveform, and then trained a neural net on that feature set to recognize musical genre. 

This depository contains both the project code and a project report. I used the GTZAN dataset, which consists of 1,000 songs across 10 genres, with 100 songs per genre. 

The main issue with this project is the efficiency of the signature transform. If I ever revisit this project, the signature transform will be made more efficient to allow for greater resolution (in terms of the raw waveform) and depth (in terms of levels of the signature transform). 
