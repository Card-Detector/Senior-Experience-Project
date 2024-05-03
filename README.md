# Senior-Experience-Project
**CS-4360 Card Detector Project**

Team Members: Fred Brace, Jonathan Dye, Brooke Menard, and Max Guzarivich

This is our project for the Senior Experience class at MSU Denver. The project is a card detector Game Suite that uses a webcam to detect playing cards and display the card's rank and suit, and uses that info to assist users with various card games. The project is written in Python using the OpenCV library for image processing and Machine Learning for accurate card identification.

## Version 1.3: A Product with some games
Our implementation of the card suite. 

## Features
The list of features that our card suite has as of Version 1.3.
- Opening Splash Screen with the colors of a card table
- The game of War
- A custom game Crazy 4's
- Texas Hold 'em
- A machine learning model for card detection 
  
## Getting Started
To get started with the project, you will need to install the following dependencies:
- Python 3.7
- OpenCV (cv2) (Image Processing)
- Numpy (Array Mathmatics)
- Tinker (GUI's)
- PyTorch (torch) (Machine Learning)

## Running the Program
To run the program, follow these steps:
1. Clone the repository to your local machine. 
   
   https://github.com/Card-Detector/Senior-Experience-Project.git
2. Install Dependencies (Python 3.7, OpenCV, Numpy, Tinker, and PyTorch)
3. Download the necessary files. Those are `selector2.py`, `war.py`, `Crazy4s.py`, and `TexasHoldEm.py`. You will also need the file `best_model.pth`. This is the model to get the card recognition to work
4. Launch the Program: Open the project in your preferred IDE (we use Visual Studio Code) or command line, and run the `selector2.py` file to start the application.

### Enjoy the Game Suite!

**It should be noted that each .py file can be run individually
   Below is a list of .py files with a brief description
      CardDetection\TorchModel.py -- This is our Machine Learning Program that builds the model that we used to detect the cards (librarys are included in the `CardDetection\CompTemplates` and `CardDetection\Templates` directories)
      CardDetection\TemplateBuilder.py -- This is the photo capture code that we used to create the CompTemplates library to be used with our model.  It detects/crops/saves card objects.
      CardDetection\CardDetection.py -- This is our initial program that uses the model to detect cards.
      CardDetection\Crazy4s.py -- Game implementation of Crazy4s
      CardDetection\TexasHoldem.py -- Game implementation of TexasHoldem
      CardDetection\Blackjack.py -- Game implementation of Blackjack
      War.py -- Game implementation of war
      Selector.py -- initial but outdated shell program game suite
      Selector2.py -- Current game suite
