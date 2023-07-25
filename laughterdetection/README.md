Machine Learning Laughter Detection Model
===
This folder represents the work associated with a project I worked on for my audiovisual Machine Learning class in the Spring of 2023. More thorough documentation can be found in my official project writeup. Regardless, I use the Mel Frequency Cepstral Coefficients in two videos of John Mulaney's stand up comedy, manually label intervals of laughter, and then train a logistic regression model to detect occurences of laughter in the sound from the videos with 80% accuracy. Then, I use the model to detect laughter in a new, completely fresh video and overlay each occurence with its own laughter clip. The final product is riddled with false positives that I did not have time to parse through, but the proof of concept is there. I'm incredibly proud; generally, laughter detection models require much more data in order to function effectively.

The Google Colab file can be found here: (https://colab.research.google.com/drive/190BkfGk1uAwvf5vOuVl7GsXCsEBPtr1A?usp=sharing)

The output video can be found here: https://drive.google.com/file/d/1iy7bAvKDJpZqlbJwZ4-RbZkmXeJ8wW78/view?usp=sharing
