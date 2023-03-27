#NLP_coverLetter

This application utilizes openAI APIs to generate smart cover letters based on the given resume and job description.

The user can set the estimated length of the letter as well.

Two versions of the applications are provided: desktopApp and webApp.

The desktopApp receives the "jobDescription.txt" and "resume.txt" files (located in the same location as the desktopApp.py) and generates and saves the cover letter on the computer.
The webApp offers a web application where the required field are given in the text fields, and the application returns the corresponding cover letter.

##Note! The application uses OPENAI_API_KEY to authenticate your openAI account. 
It sould be stored into the System Environment before running the code.
To export your export OPENAI_API_KEY into the System Environment, run the following command in the terminal:

##OPENAI_API_KEY=<your_api_key_here>


required libraries: flask, openai