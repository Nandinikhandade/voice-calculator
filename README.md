# Voice Calculator in Python
## Author : Nandini Khandade
## Overview

The *Voice Calculator* is a Python-based application that allows users to perform mathematical calculations using their voice commands. It leverages Python's speech recognition and text-to-speech capabilities to convert spoken input into arithmetic expressions, evaluate them, and return the result both in textual and spoken form.

## Features

- Voice input for performing basic arithmetic operations (addition, subtraction, multiplication, division).
- Speech output for the calculated result.
- Handles complex operations such as parentheses, powers, and more.
- Text input mode available as a fallback option.
- User-friendly interface.
  
## Technologies Used

- *Python 3.x*
- *SpeechRecognition*: For recognizing and interpreting the user’s voice input.
- *Pyttsx3*: For converting the calculated result into speech output.
- *Tkinter* (optional): To create a graphical user interface (GUI).
- *re*: For parsing and validating arithmetic expressions.

## Prerequisites

Before running the project, you need to have the following packages installed:

bash
pip install SpeechRecognition pyttsx3


If using the GUI version:

bash
pip install tkinter


## How It Works

1. The program listens to the user's voice input through the microphone.
2. It processes the input and recognizes the arithmetic expression using the *SpeechRecognition* library.
3. The recognized expression is then evaluated using Python’s eval() function.
4. The result is spoken back to the user using the *Pyttsx3* library and displayed on the screen.

## Usage

1. Clone the repository:

bash
git clone https://github.com/your-username/voice-calculator.git


2. Navigate to the project directory:

bash
cd voice-calculator


3. Run the Python script:

bash
python voice_calculator.py


4. Speak out the arithmetic operation you want to perform, such as "12 plus 5" or "25 divided by 5".
5. The result will be spoken and displayed.

## Example

*Input:*  
User says: "What is 15 times 3?"

*Output:*  
Spoken: "The result is 45"  
Displayed: 15 * 3 = 45

## Troubleshooting

- Make sure your microphone is properly configured and active.
- If the voice recognition isn't working, check your internet connection, as *SpeechRecognition* uses online services.
- Use clear and standard arithmetic phrases like "plus", "minus", "divided by", and "times".

## Future Improvements

- Add support for more complex mathematical operations (like square roots, logarithms).
- Enhance accuracy with local offline speech recognition models.
- Implement error handling for invalid expressions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
