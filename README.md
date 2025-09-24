# designing controller for robot

<img width="975" height="513" alt="image" src="https://github.com/user-attachments/assets/7f73e9e4-3c6c-43c5-afc6-fa735268f207" />  


---

**In this project, I first designed a model for the robot’s motors.**

<img width="1318" height="512" alt="image" src="https://github.com/user-attachments/assets/f4072c72-34e3-47dd-8c48-8344ac9b523d" />

 
**Then I applied a 48-volt input to each motor for 3 seconds.**

<img width="975" height="499" alt="image" src="https://github.com/user-attachments/assets/62aaefc5-c162-4335-ba01-f55e351cb019" />

**Joint States**

<img width="1358" height="742" alt="image" src="https://github.com/user-attachments/assets/7512e4e1-4a3a-4bff-b93e-abf41a2571ec" />

<img width="1368" height="836" alt="image" src="https://github.com/user-attachments/assets/f505115b-e226-4498-b3cd-79a1fb8b6af6" />

<img width="1356" height="890" alt="image" src="https://github.com/user-attachments/assets/3242401f-cd0f-401d-bfe4-a52aa084c400" />

---
**In the Third part, I designed a PID controller for each joint so that they meet these requirement:**

- settling time is about 1 second
-  the overshoot is less than 5%.

**Which resulted in following controllers:**

First & Second Joints

<img width="1254" height="500" alt="image" src="https://github.com/user-attachments/assets/50352350-e110-4649-bad2-64227e606cad" />

Third Joint

<img width="1260" height="502" alt="image" src="https://github.com/user-attachments/assets/938ec3ee-1a2a-427e-9aaf-4aa44dab25d8" />

---
**In the final stage, I implemented a trajectory on the robot with the designed controller:**

<img width="975" height="1056" alt="image" src="https://github.com/user-attachments/assets/3d8b6645-4c3c-4302-96a0-6a9128916c67" />






