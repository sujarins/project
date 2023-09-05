# HANGMAN HANDMAN
HANGMAN HANDMAN is a project in image analytics course, which is a required subject of a Master's degree. The project was done by my team (5 people including me).We would like to develop a game that can be played without the tools like a keyboard or mouse. We selected the Hangman game, in which a player has to guess a word by letter, one at a time until they fill in the word or lose. Instead of inputting letters by keyboard, the player has to draw alphabet letters in the air and we use the laptop's camera to detect the player's fingers and then predict that alphabet letter to guess a word in the game.

### Objective project: To apply image analytics (by using Tensorflow) to real practices.
#### Learning lessons: Python, TensorFlow, OpenCV, Numpy, MediaPipe, Pygame

#### Demo
https://github.com/sujarins/project/assets/56682174/0d1a046d-9cad-4a04-8f5d-2ee307fd0373

#### Dataset training model: EMNIST Letters: 145,600 characters. 26 balanced classes.
<img width="600" alt="emnist_letters_dataset" src="https://github.com/sujarins/project/assets/56682174/2ed25149-7c9e-4929-b6e9-6407d2d3e31f">
<img width="400" alt="emnist_letters_examples" src="https://github.com/sujarins/project/assets/56682174/15fa37b4-8aeb-49e8-8c22-fe4e1401864b">

#### How it works
<img width="600" alt="method" src="https://github.com/sujarins/project/assets/56682174/b2273530-9f62-4f1f-8824-f841651cc33b">

#### Limitation:
- Our model can only predict English letters.
- Our game still has to require a mouse at the start of the game to select word categories and at the end of the game to leave the game.
- Finger detection depends on your computer, camera, and light.
