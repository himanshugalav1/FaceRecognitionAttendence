<h1 align='center'>Face Recognition Attendence System</h1>
<h4 align='center' >A project based on face recognition based attendance system that provides real time update with firebase database</h4>
<br/>
<div>
  
![Screenshot (143)](https://github.com/himanshugalav1/FaceRecognitionAttendence/assets/107814705/73dcf065-ee33-4f74-928f-c0507ee433e1)
</div>
<h2 align='center'>Key Features</h2>
The Face Detection Attendance System application utilizes a webcam or scanner to capture and record the faces of students in a database. The system relies on the Firefall database and a face recognition library for its functioning. Here's an overview of the system:

1. Enrollment: Students are required to enroll by providing their details and allowing the system to capture their face using a webcam or scanner. The captured face images are processed and stored in the Firefall database along with the associated student information.

2. Face Detection: The system continuously captures the live video feed from the webcam or scanner. The face detection algorithm, integrated with the face recognition library, scans each video frame in real-time to detect the presence of faces.

3. Face Recognition: Once a face is detected, the face recognition library compares it with the enrolled faces stored in the Firefall database.

4. Attendance Marking: Upon successful recognition, the system marks the student as present and logs the attendance data in a secure database. The system can also capture the timestamp to record the exact time when the attendance was marked.

5. Attendance Reporting: The attendance data can be accessed by authorized personnel, such as teachers or administrators, who can generate reports to view the attendance records. These reports can display the students' details, attendance status, and timestamps.

6. Real-Time Monitoring: The system can provide real-time monitoring of the attendance process, displaying the recognized faces on the screen as students enter or leave the designated area covered by the webcam or scanner. This feature allows for immediate verification and helps in ensuring the accuracy of attendance records.

<h2 align='center'>Steps to use</h2>

1. Create a project in pycharm and copy the code files in the same project.

2. Install the libraries - 

    2.1. opencv using 'pip install opencv-python'

    2.2. face_recognition using 'pip install face-recognition'

    2.3. firebase using 'pip install firebase-admin'

    2.4. numpy using 'pip install numpy'

3. Change the firebase credentials and get your firebase key

4. Change the images and data according to you
