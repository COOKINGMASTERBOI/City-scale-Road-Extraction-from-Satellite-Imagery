CS482-110 Project Report
Project Theme: Semantic Map from Road Detections
Group Members: Mingqi Zhang, Zihui Bai
Date of Submission: 06/25/2021


Environment Setup and Data Preparation
Initial Attempts
	When we started to set up the environment, we tried different methods. We first tried to use Docker, however, after we pulled the container from professor's docker hub and  tried to run the commands on the readme file, it did not work. Then we tried to build the environment on Google Colab by writing our own code. It failed as well. We successfully cloned the Cressi repository, installed Conda, and uploaded data into our Google Drive. After that we encountered some errors such as ‘‘module not found’. 

Attempts on Aaron’s Notebook
	After we scheduled the first meeting with the professor, we moved on by using Aaron’s Notebook. It took us several hours to build the first couple of steps, then we ran into several errors. Here we listed some of the errors and the way we solved them.

Error #1

	We tried to google it for an answer first, then we asked Aaron if he has any idea on how to solve this problem. He said this problem can be ignored.

	Error #2 & 3



	Two similar ‘operation not supported’ errors appeared. We resolved these errors by changing the paths to our local folders.
	
	Error #4

	
	This error was resolved by trying to remount Google Drive to Google Colab and changing all the paths to local folders. After this problem was solved, we had some output graphs generated to the drive fold.
	
Outputs: SN5- Mumbai 19 & 22







We then followed the step in the part 2 link in the readme section, modified the json file, and debugged it several times to make the format right. By completing this step, we successfully built the environment and prepared data necessary for training a model.
	




Model Training
	We encountered more problems when we tried to train the model. For the import error, we did some research on google and added one more line of code, then this error was gone. However, for the type error, even though we tried to find the solution by modifying the original code and changing the paths for many times, it did not help. Then we did research again on google, asked our classmate, posted a question on StackOverFlow, and asked our professor. We still couldn’t figure it out after many attempts.





(Model Testing)
	
	








Credit: Aaron Samuel’s Notebook:
https://colab.research.google.com/drive/1pA7JjwNptdhF4VJ9_ncM543EME0RVW5L 



