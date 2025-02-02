# Jira Instructions

## Setting Up Jira with Docker
- Run the following command to build the Docker images and start the services:

``` bash
git clone git@github.com:WhiteboxHub/Classroom-Jira-codebase.git

docker-compose up -d
```

## Verify That the Container is Running
```bash
docker ps
```

## Open your web browser and go to
```bash
http://localhost:8080
```
## complete the setup Wizard :
-	During the setup, select PostgreSQL as the database type.
	-	Provide the following database connection details:
	-	Hostname: db
	-	Database: jiradb
	-	Username: jirauser
	-	Password: jirapassword
	-	Jira will automatically connect to the PostgreSQL database.
## **Create Admin Account:**
   - Create an admin account during the setup.
   - Hear are the detailed steps([How to create Admin Account](Jira_docker_setup.md) )
   

---

## 1. Create Project  ([Step_1](Steps/Step_1.md))
Set up the **Whitebox Learning (WBL)** Scrum project in Jira to manage tasks and track progress.

---

## 2. Define Epics ([Step_2](Steps/Step_2.md))
Break down the entire system into large, high-level **epics**, such as:
- Home Page
- Schedule Management
- Resources (Recordings, Presentations, Resume Builder)
- FAQ Page
- Contact Page
- User Authentication

 
---

## 3. Add Stories and Tasks ([Step_3](Steps/Step_3.md))
For each epic, write detailed **user stories** representing the specific features or functionality. Break these stories into actionable **tasks** to ensure clarity and manageability.

 
---

## 4. Assign Subtasks ([Step_4](Steps/Step_4.md))
Create detailed **subtasks** for each task and assign them to team members. Subtasks should focus on individual, actionable components of the larger task.
 
---

## 5. Plan and Execute Sprints ( [Step_5](Steps/Step_5.md))
Organize the **backlog** into **2-week sprints**:
- Assign tasks and stories to each sprint.
- Set sprint goals based on project priorities and deadlines.

---

## 6. Track Progress  ([Step_6](Steps/Step_6.md))
Utilize Jira tools to monitor the progress of the project:
- Use **Scrum boards** to visualize the status of tasks (e.g., To Do, In Progress, Done).
- Generate **reports** like Burndown Charts and Velocity Charts to track sprint performance.


---

## 7. Review and Retrospect ([Step_7](steps/Step_7.md))
At the end of each sprint:
- Analyze completed work and identify any blockers or areas for improvement.
- Hold a **sprint retrospective** to discuss what went well and what can be improved for the next sprint.
 



### Thank you for checking out this repository. Happy coding!