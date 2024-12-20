# Attendance System based face Recognition
Developed a Face Recognition-Based Attendance Management System using Python and OpenCV, integrating a Tkinter GUI for student registration, facial data training, real-time attendance marking, and record management. 
The system enhances efficiency and accuracy, streamlining administrative tasks through automated processes and reducing manual errors.

## Project Workflow
#### 1. System Initialization
* Launch the program.  </br>
* Select "Register New Student" to register a face. </br>
#### 2. Face Registration
- Enter Student ID and Name in the pop-up window.
- Click "Take Image" to capture up to 50 face images using the webcam.
- Captured images are stored in the TrainingImage folder.  <br/>
#### 3. Model Training
- Click "Train Image" to process and train the model.
- Images are converted into numeric format for machine understanding.
- Training time depends on the system's performance. <br/>
#### 4. Automatic Attendance
- Click "Automatic Attendance" and enter the Subject Name.
- The system recognizes faces using the trained model and records attendance.
- Attendance is saved in a .csv file, organized by subject <br/>
#### 5. Viewing Attendance
- Click "View Attendance" to display attendance records in a tabular format.
- Data is subject-specific and stored for future reference.

## Steps to follow
1. **Clone the Repository**: Download or clone the repository to your local machine.  
2. **Install Dependencies**: Run `pip install -r requirements.txt` in the terminal to install all the necessary packages.  
3. **Set Up Training Folder**: Create a `TrainingImage` folder in the project directory to store training data.  
4. **Update File Paths**: Open `attendance.py` and `automaticAttendance.py`, and update the file paths as per your system configuration.  
5. **Run the Application**: Execute the `attendance.py` file to start the system.  
