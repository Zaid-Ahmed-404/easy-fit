# Easy-Fit – Conference Management System

**Easy-Fit** is a robust, scalable, and secure web-based **Conference Management System (CMS)** built with **Laravel**. It simplifies the entire lifecycle of organizing conferences – from user registration and paper submission to session scheduling, reviewing, and analytics – all powered by **AWS** infrastructure.

---

## Features

### User Management
- User registration and profile management (name, affiliation, contact info)
- Role-based access control (RBAC):
  - Author
  - Super Chair
  - Track Chair
  - Reviewer
  - Sub Reviewer

### Paper Submission
- Submit papers or abstracts via a submission portal
- Upload documents securely to **AWS S3**
- Track submission status in real-time

### Review and Selection
- Assign papers to reviewers/sub-reviewers
- Scoring system with reviewer feedback
- Automated paper selection based on review scores

### Conference Schedule
- Manage schedules for sessions, workshops, and events
- Assign speakers and topics to time slots dynamically

### Conference Analytics
- Reports on:
  - Attendee demographics
  - Submission statistics
  - Session popularity
- Track registration and revenue performance

### Communication and Notifications
- Messaging system for organizers, speakers, and attendees
- Automated notifications via **AWS SNS** and **AWS SES**

### Accessibility and Inclusivity
- Accessibility features for participants with special needs
- Multi-language support for global events

### Mobile Responsiveness
- Responsive UI using **Laravel Blade** and **Bootstrap**

---

## Tech Stack

### Frontend / UI
- Laravel Blade Templates
- Bootstrap CSS
- Mobile-first responsive design

### Authentication and Authorization
- JWT-based API authentication
- Role-based access (RBAC)

### Database
- MySQL with **Eloquent ORM**
- Hosted on **AWS RDS**

### DevOps and AWS Infrastructure
- Containerization with **AWS ECR**
- CI/CD pipeline using **AWS CodeBuild**
- Deployed with **AWS ECS**
- Secrets and credentials managed via **AWS Secrets Manager**
- Fine-grained permissions using **AWS IAM**

### Security
- HTTPS enforced
- Input sanitization and validation
- Protection against XSS, CSRF, and SQL injection

### Architecture and Scalability
- Follows **Clean Architecture** principles
- Optimized database queries and caching
- Scalable for large conferences and multiple users

### Images

![Image](https://github.com/user-attachments/assets/8ae9fb05-0ea4-47de-bf05-3b158d4b4c70)

![Image](https://github.com/user-attachments/assets/2d7a94cc-625a-4123-b8bf-8fdfca640177)

### Admin Dashboard
![Image](https://github.com/user-attachments/assets/297776ee-4f96-44d7-b014-905f7d8ca045)

![Image](https://github.com/user-attachments/assets/8ba3bc48-0590-48c5-907c-dcfcffd0a568)

### Common Dashboard
![Image](https://github.com/user-attachments/assets/635fa5ba-54b7-4279-ab1d-f75760ca8de8)

![Image](https://github.com/user-attachments/assets/7c49edf4-4dc5-4390-8256-21d880f03fa1)

### Author Dashoboard
![Image](https://github.com/user-attachments/assets/6224d246-6f50-4a4b-9626-171db95172c5)

![Image](https://github.com/user-attachments/assets/9681c7b2-bc8d-437d-a4d4-f97dedb4b200)

![Image](https://github.com/user-attachments/assets/45b8afa0-3ef2-4b2c-98b0-cd2075c450bf)

![Image](https://github.com/user-attachments/assets/a6f39dd2-cc9b-40a2-87e0-e1f65251fd0a)

![Image](https://github.com/user-attachments/assets/0f7910e9-f2b4-4709-9cbc-c97aee9976ce)

![Image](https://github.com/user-attachments/assets/44bfec98-c393-428d-a2f2-9994eb3fb3bb)

![Image](https://github.com/user-attachments/assets/74f20336-d0e6-4722-b73d-4354666c2f6e)

![Image](https://github.com/user-attachments/assets/14e10358-1867-4b87-a7db-5f800e48fc23)

### Superchair Dashboard
![Image](https://github.com/user-attachments/assets/125cdae4-c9ee-4203-b438-2bfbffe81acc)

![Image](https://github.com/user-attachments/assets/274aeb16-aab6-48f2-9ccf-11f9466af137)

![Image](https://github.com/user-attachments/assets/d72d7aaa-88f7-4ce0-a9d5-eaf5a4002d07)

![Image](https://github.com/user-attachments/assets/69f61ee1-a12a-4a33-b51b-88c075530925)

![Image](https://github.com/user-attachments/assets/a9ca8947-5789-4154-ad66-dc32e2807cf8)

![Image](https://github.com/user-attachments/assets/1a927a33-bb9d-4fbb-9568-21b428c60f5e)

![Image](https://github.com/user-attachments/assets/655a88d7-e962-41ba-9ff5-86f76941fff9)

![Image](https://github.com/user-attachments/assets/d89a036b-80fd-46e7-b2a7-5005d10c4fe5)

![Image](https://github.com/user-attachments/assets/be9e1547-2078-4a1e-9515-0c4508acae3b)

![Image](https://github.com/user-attachments/assets/93e82ae2-8093-46ad-9829-0f8fd0151257)

![Image](https://github.com/user-attachments/assets/286154af-2196-4dc2-97bc-a9a03bbc5225)

![Image](https://github.com/user-attachments/assets/f166b3c3-3b8a-46ae-a56e-5309c339bec0)

![Image](https://github.com/user-attachments/assets/7f6dc41d-2091-4921-aba2-5e9d3c9d9ab0)

![Image](https://github.com/user-attachments/assets/e3719469-9fb3-430a-a93e-43490b2c9aca)

![Image](https://github.com/user-attachments/assets/6ff153bc-caea-41ae-b211-bf24b868b427)

![Image](https://github.com/user-attachments/assets/06fabdcf-cd86-4fc2-b058-41f737259654)

![Image](https://github.com/user-attachments/assets/32d4e7c3-3dd1-4e77-b9cf-5d2476e3f5c3)

![Image](https://github.com/user-attachments/assets/deb3a09a-2ea8-4f8e-be1d-8561ba2d91dc)

![Image](https://github.com/user-attachments/assets/f834aa33-b0c1-4293-a06f-f429701c98e8)

### Trackchair Dashboard
![Image](https://github.com/user-attachments/assets/ec298910-1e63-43eb-b9d8-6215f82acf86)

![Image](https://github.com/user-attachments/assets/d3676a5b-976f-429a-a59a-062b585fa0cc)

### Reviewer Dashboard
![Image](https://github.com/user-attachments/assets/5fd35b58-e995-4f82-a6fe-9b2bdd9768c8)

![Image](https://github.com/user-attachments/assets/ea3136f1-b6bb-4a32-9e41-9b57b7d867e4)

### Notification
![Image](https://github.com/user-attachments/assets/3422e9a5-3e98-49e4-ab31-31e175738a96)

![Image](https://github.com/user-attachments/assets/7df16f40-74ff-45c9-87b1-292ca6aaf43d)

![Image](https://github.com/user-attachments/assets/66ec507d-9e7c-4b0f-a3c6-60871541b633)

![Image](https://github.com/user-attachments/assets/87aa8748-8552-4dde-90af-222ffcc635b8)

![Image](https://github.com/user-attachments/assets/0fccf1cc-0586-43e7-bee2-bdf20acb1723)

![Image](https://github.com/user-attachments/assets/5c2d6178-a07a-456e-845e-d75a974665cb)

![Image](https://github.com/user-attachments/assets/0ff164a7-8e43-4ad9-9859-c75a1cd503ad)

![Image](https://github.com/user-attachments/assets/6edafb80-d8ff-49b4-b4a0-4d608673554c)

