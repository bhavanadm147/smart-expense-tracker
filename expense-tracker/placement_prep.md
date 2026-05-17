# Placement Interview Prep - Sandesh Kalagi

## 1) Self Introduction (60-90 seconds)
Good morning, I am Sandesh Kalagi, an 8th semester Computer Science Engineering student. I am currently doing a Java Full Stack internship and actively preparing for software roles.

I recently built and deployed a full-stack Smart Expense Tracker project using Java Spring Boot, REST APIs, H2 database, and HTML, CSS, JavaScript with Chart.js. In this project, users can add and delete expenses, search records, export CSV, and view insights like total spending, monthly spending, top category, and visual charts.

I deployed the frontend on GitHub Pages and backend on Render. During deployment, I solved a real production issue where API calls failed due to localhost configuration, and fixed it by pointing the frontend to the deployed backend URL.

I enjoy backend logic, API design, and problem-solving. Right now, I am strengthening DSA, SQL, and Spring Boot fundamentals to contribute effectively as a software engineer from day one.

## 2) HR Questions and Strong Answers

### Q1. Tell me about yourself.
I am a final-year CSE student with hands-on experience in Java full-stack development through my internship and personal projects. My strongest project is Smart Expense Tracker, where I worked on end-to-end development, deployment, and debugging. I am currently focused on improving DSA, backend engineering, and interview readiness for software roles.

### Q2. Why should we hire you?
I bring a mix of fundamentals and execution. I can build complete features from frontend to backend, work with REST APIs and databases, and deploy applications. I am consistent, quick to learn, and I take ownership of issues until they are solved.

### Q3. What are your strengths?
My strengths are consistency, debugging under pressure, and clear communication. I break problems into smaller steps and complete them reliably.

### Q4. What is your weakness?
Earlier I used to spend too much time perfecting UI details. I improved this by setting time limits and prioritizing functionality first, then polishing in a second pass.

### Q5. Why do you want this job?
I want to start my career in a role where I can apply Java full-stack skills to real products, learn from experienced engineers, and grow through practical software development.

### Q6. Where do you see yourself in 3-5 years?
I see myself as a strong software engineer owning backend-heavy features, contributing to system design discussions, and mentoring junior teammates.

### Q7. Describe a challenge you faced.
In production, add/delete operations failed though local setup worked. I traced it to frontend API calls using localhost. I updated the API base URL to Render backend and verified end-to-end functionality. This taught me the importance of environment-specific configuration.

### Q8. Did you use AI in your project?
Yes, I used AI as a productivity assistant for faster iteration and UI improvements. But I personally understood, tested, integrated, and debugged every change. I can explain architecture, API flow, and logic end-to-end.

### Q9. Are you comfortable with deadlines?
Yes. I usually plan tasks in small milestones, complete core functionality first, and keep buffer time for testing and fixes.

### Q10. Any questions for us?
Yes. How does your engineering team support freshers during onboarding, and what does success look like in the first 3 months for this role?

## 3) Project Explanation Script (when interviewer asks)
My Smart Expense Tracker follows a client-server architecture.

Frontend sends HTTP requests using fetch:
- GET /expenses for list
- POST /expenses to create
- DELETE /expenses/{id} to delete
- GET /expenses/total for aggregate total

Backend has controller-service-repository flow:
- Controller handles API requests
- Service contains business logic
- Repository interacts with database

After add/delete, frontend refreshes table, stats, and charts. I also implemented search filtering and CSV export for better usability.

## 4) One-line Close Statement
I may be a fresher, but I already have hands-on full-stack deployment experience, strong learning ability, and I am ready to contribute from day one.
