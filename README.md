
# Enhancing-Attendance-Management-through-Real-Time-Face-Detection.

### Here are the setup instructions, simplified:
- Get the Code: Download or clone the repository to your local machine.
- Install Dependencies: Open your command prompt and run pip install -r requirements.txt.
- Create Folder: Make a new folder named TrainingImage inside the main project directory.
- Update Paths: Open both attendance.py and automaticAttendance.py, and change the file paths to match your system's setup.
- Launch: Run the attendance.py script to start the program.

### Here is a streamlined version of the project flow:

- Registration: Click "Register New Student," enter your ID and name, then click Take Image.
- Image Capture: The system captures multiple photos of your face (default is 50) and saves them in the TrainingImage folder to build your recognition profile.
-Model Training: Click Train Image to process and convert the captured photos into numerical data, allowing the system to accurately recognize you in the future.
- Automated Attendance: Click Automatic Attendance and enter the subject name. The system will then use your trained profile to verify your face and log your attendance.
- Data Export: The system automatically generates and organizes a separate .csv file for each subject.
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- View Records: Click View Attendance to display the recorded data in a tabular format.
