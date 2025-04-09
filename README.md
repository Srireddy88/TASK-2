# TASK-2 DAY-2

# Task 2: CI/CD Pipeline with Jenkins & Docker

This project demonstrates a basic CI/CD setup using **Jenkins**, **Docker**, and **GitHub**, centered around a simple Node.js application.

##  Objective

- Automate the process of building, testing, and deploying a Node.js app.
- Use Jenkins to trigger the pipeline on each code commit.
- Containerize the app using Docker and optionally push to DockerHub.

---

##  Tools & Services Used

- **Jenkins** – For CI/CD pipeline automation.
- **Docker** – For containerizing the application.
- **GitHub** – Code repository & version control.
- **DockerHub** – To store built images (integration with Jenkins configured).

---

##  What I Did
![Screenshot 2025-04-09 212853](https://github.com/user-attachments/assets/10d81bff-679b-40c9-a903-678cfd4a8478)

1. **Set up Jenkins on a local/cloud machine.**(http://3.82.188.220:8080/)
2. **Connected Jenkins to GitHub** using credentials to pull code from the repo.
3. **Added DockerHub credentials** to Jenkins for pushing images.
4. **Created a Jenkinsfile** with stages: Clone → Build → Test → Docker Build → Deploy.
5. ![Screenshot 2025-04-09 212649](https://github.com/user-attachments/assets/4774edd2-19c4-4ce8-95ee-9c5ad0fd082b)
![Screenshot 2025-04-09 212633](https://github.com/user-attachments/assets/e46fbea1-58f2-4576-8ab7-ea2d0c40b011)

6. ![Screenshot 2025-04-09 212713](https://github.com/user-attachments/assets/0807b5ef-5742-4dfb-a5d1-91fa7246d7eb)
![Screenshot 2025-04-09 212539](https://github.com/user-attachments/assets/8b8fbcda-c845-480e-80ef-306be4969cb9)

7. Faced **2 failed pipeline runs** due to incorrect Node.js environment and `Dockerfile` issues.
8. On the **3rd attempt**, fixed the pipeline and successfully built, tested, and deployed the application.
9. ![Screenshot 2025-04-09 212748](https://github.com/user-attachments/assets/91bed3ff-ca56-4058-b4bc-77b71051e24e)

10. ![Screenshot 2025-04-09 212808](https://github.com/user-attachments/assets/d5a04426-c7e9-49c4-8098-8e28a71467d8)
11. CI/CD Pipeline is created.

---


