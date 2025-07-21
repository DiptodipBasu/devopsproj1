<h1>DevOps Project: CI/CD Pipeline with Jenkins, Docker, and Azure (Open Source)</h1>
<h3>Overview</h3>
This project demonstrates a full DevOps pipeline:<br>
•	Code from GitHub<br>
•	Build using Jenkins (Maven)<br>
•	Dockerize and push to Docker Hub<br>
•	Deploy to Azure VMs<br>
<h3>Tech Stack</h3>
•	Azure for infrastructure<br>
•	Jenkins for CI/CD<br>
•	Docker for containerization<br>
•	GitHub for source control<br>
•	Maven for Java build<br>
<h3>Steps</h3>
1.	Create the Main VM in Azure<br>
&nbsp;&nbsp;&nbsp;•	OS: Ububntu 22.04<br>
&nbsp;&nbsp;&nbsp;•	Open Ports: 22(SSH), 8080(Jenkins)<br>
2.	Install  and Setup Jenkins with Maven Plugin <br>
3.	Create Jenkins Pipeline<br>
&nbsp;&nbsp;&nbsp;•	Source: GitHub<br>
&nbsp;&nbsp;&nbsp;•	Build: Maven<br>
&nbsp;&nbsp;&nbsp;•	Add Docker build Script<br>
&nbsp;&nbsp;&nbsp;•	Confirm JAR file creation<br>
4.	Install Docker on the Main VM<br>
5.	Push Docker image on docker hub<br>
6.	Launch a new VM <br>
&nbsp;&nbsp;&nbsp;•	OS: Ububntu 22.04<br>
&nbsp;&nbsp;&nbsp;•	Open Ports: 22(SSH), 8080(View Website), 80(http)<br>
7.	Pull and Run Docker Image<br>
<h2>Outcome:</h2>
The application runs successfully on a second VM via a pulled Docker image.
