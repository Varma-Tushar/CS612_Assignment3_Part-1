# OOP Programming - JAVA - Inheritance Design Lab
<strong>(Steps to Follow)</strong>

1. Unzip and open the file in Eclipse.<br>
2. Comment the <strong>work()</strong> method in the following files present under the <strong>src</strong> folder -> <strong>Doctor.java, Nurse.java and Surgeon.java</strong><br>
3. <strong>Run</strong> the <strong>Hospital.java</strong> file. The expected output should be:<br>
<pre>
Vito 123
Michael 234 Heart
Vincent 645 Brain Operating: true
Sonny 789 has 6 patients.
Vito works for the hospital.
Michael works for the hospital.
Vincent works for the hospital.
Sonny works for the hospital.
</pre>

4. Now uncomment the <strong>work()</strong> method in the three files i.e. <strong>Doctor.java, Nurse.java and Surgeon.java</strong> and <strong>run</strong> the application again<br>
5. Since we have <strong>overridden</strong> the work() method, the output will be:<br>
<pre>
Vito 123
Michael 234 Heart
Vincent 645 Brain Operating: true
Sonny 789 has 6 patients.
Vito works for the hospital.
Michael works for the hospital. Michael is a(n) Heart doctor.
Vincent works for the hospital. Vincent is operating now.
Sonny works for the hospital. Sonny is a nurse with 6 patients
</pre>
