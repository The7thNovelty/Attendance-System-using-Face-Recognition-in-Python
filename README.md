# Attendance-System-using-Face-Recognition-in-Python

This project aims to mark attendance based on the faces recognised by the machine.
The steps are:
  1. Connect camera with your system. 
  2. Codes for face detection and recognition
  3. Database to be created according to the schema
  4. Allow the camera to detect a face, and if the match is found, then add "Present" to the recognised person's attendance.
     This will be done until the system recognises all the faces in a room.
     Faces that are not recognised, but those present in the database are to marked as "absent".
  5. With every match it makes, the code gets better in matching the faces.
  6. Create an app, to display this information to the user.
  
  
  # Simple Example would be a classroom
    A separate app for teachers and students.
    Student Login:
      i. Login using id and password. Display the count of classes.
      ii. If absent on some day, reminder will be sent.
      iii. An option to write a remark of why he/she was absent for a particular class (this can be visible to the teacher).
    Teacher Login:
      i. Login using id and password. Display the number of students present on that day.
      ii. An option to re-mark attendance as "present" or "absent" with a proper remark text and justification.
      iii. An option to send a reminder for low attendance or frequent absence.
