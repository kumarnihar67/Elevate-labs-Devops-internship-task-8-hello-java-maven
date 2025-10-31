# 🚀 Task 8: Run a Simple Java Maven Build Job in Jenkins

## 🎯 Objective
The goal of this task is to **use Jenkins to build a simple Java application using Maven**, demonstrating the fundamentals of Continuous Integration (CI).

---

## 🧰 Tools and Technologies Used

| 🛠️ Tool | ⚙️ Version | 💡 Purpose |
|----------|-------------|-------------|
| ☕ **Java JDK** | 8 or 11 | Compile and run Java code |
| 🧩 **Apache Maven** | 3.8+ | Build automation tool |
| 🧱 **Jenkins** | LTS | Continuous Integration server |
| 🐙 **Git & GitHub** | Latest | Source code management |
| 💻 **Windows 10/11** | Local environment | Jenkins host machine |

---

🧩 1. Setup Environment
Installed Java JDK 21

Installed Apache Maven 3.9.11

Installed Jenkins LTS (Windows Service)

Verified installations:

bash
java -version
mvn -version
📦 2. Created the Java Maven Project
Wrote a simple HelloWorld.java program and created pom.xml

Uploaded both files to GitHub

🧱 3. Configured Jenkins
Accessed Jenkins at 👉 http://localhost:8080
Manage Jenkins → Global Tool Configuration
✅ Added JDK path

✅ Added Maven (auto-installed)

🧰 4. Created Jenkins Freestyle Project
New Item → Freestyle Project → "Hello-java-maven"

Under Source Code Management:

Selected Git

Repo URL: https://github.com/kumarnihar67/Elevate-labs-Devops-internship-task-8-hello-java-maven.git

Under Build → Invoke top-level Maven targets:

Goals: clean package

POM: pom.xml

▶️ 5. Build Execution
Clicked Build Now

Jenkins cloned the repo, ran Maven, and built the project.

🧹 6. Troubleshooting
Fixed missing POM path error (pom.xml)

Solved SSL & dependency download issues in Maven configuration.

🖼️ Screenshots

<img width="1920" height="1080" alt="task8 1" src="https://github.com/user-attachments/assets/00a89e47-6259-4091-be8c-a4fd89e2d08a" />

<img width="1920" height="1080" alt="task8 3" src="https://github.com/user-attachments/assets/0e35bb31-fb55-4ed8-a175-db223ec74eab" />

<img width="1920" height="1080" alt="task8 5" src="https://github.com/user-attachments/assets/32134718-598b-42d8-87b4-f9a43acbc381" />

<img width="1920" height="1080" alt="task8 4" src="https://github.com/user-attachments/assets/6e3a5e82-ab75-4858-91a3-4a2fd54a5349" />





