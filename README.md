# OOP Programming - JAVA - Inheritance Design Lab
(Steps to Follow)

1. Unzip and open the file in Eclipse.<br>
2. In the src folder comment the public void work() method in Doctor.java, Nurse.java and Surgeon.java<br>
3. Run the Hospital.java file<br>
the expected output should be:<br>
Vito 123<br>
Michael 234 Heart<br>
Vincent 645 Brain Operating: true<br>
Sonny 789 has 6 patients.<br>
Vito works for the hospital.<br>
Michael works for the hospital.<br>
Vincent works for the hospital.<br>
Sonny works for the hospital.<br>
4. Now uncomment the work() method in the three files i.e. Doctor.java, Nurse.java and Surgeon.java and run the application again<br>
5. Since we have overridden the work() method, the output will be:<br>
Vito 123<br>
Michael 234 Heart<br>
Vincent 645 Brain Operating: true<br>
Sonny 789 has 6 patients.<br>
Vito works for the hospital.<br>
Michael works for the hospital. Michael is a(n) Heart doctor.<br>
Vincent works for the hospital. Vincent is operating now.<br>
Sonny works for the hospital. Sonny is a nurse with 6 patients<br>
