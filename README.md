# Tamakan System
Tamakan is an extensive platform developed specifically to assist students get real-world work experience while they're still their academic journey. Tamakan  serves as a centralized hub where students can explore and obtain part-time job opportunities that align with their interests, abilities, and career goals. Tamakan can help them to build relationships that can be beneficial to their careers. include that Tamakan can help them to gain valuable work experience that they can use to boost their resumes and make them more competitive in the job market. 


The standout features of this system are:

- Handling the hiring process: The system handles the hiring process, which is carried out by the students and companies. This frees up time for both parties and makes it easier to find a mutually beneficial match.

- Reviews feature: The system incorporates a reviews feature where employers can offer feedback and reviews for job seekers/students upon the successful completion of their part-time engagements. This helps students to get valuable feedback on their work and to improve their skills and knowledge.

- AI-powered resources: The system incorporates a comprehensive suite of AI-powered resources to assist students in crafting compelling and professional resumes. This helps students to create resumes that are tailored to their specific skills and experience and that will help them to stand out to potential employers.

- Experience certificate: The job provider can add an experience certificate after the student is done with their training. This can be a valuable addition to the student's resume and can help them to get a job after graduation.

- Job alerts: Tamakan will send job alerts to the students' email addresses who are matched with the job criteria. This ensures that students are always up-to-date on the latest job openings and that they have the opportunity to apply for jobs that are a good fit for their skills and interests.

# Class Digram
![image](https://github.com/Mariamalmesfer/Java-Bootcamp-Tamakan/assets/65206318/1c0ae809-cdbf-4c81-a37d-d8cf2c3688e1)


# Use Case Digrams
- Job Seeker:
   ![image](https://github.com/Mariamalmesfer/Java-Bootcamp-Tamakan/assets/65206318/af4f7773-2c70-45d3-85bb-218635d5c929)

- Job Provider:
  ![image](https://github.com/Mariamalmesfer/Java-Bootcamp-Tamakan/assets/65206318/449d202d-a257-4dbf-b7c8-05548ecd1553)
  
# API Documentation
![image](https://github.com/Mariamalmesfer/Java-Bootcamp-Tamakan/assets/65206318/5029d072-9ff3-4e4d-b089-483f3b1cd603)
URL:https://documenter.getpostman.com/view/28987531/2s9YC2zDDy
# Figma
Job Provider: https://www.figma.com/file/kKWzfN1RqmZEZRwGyUsSwm/Tamakan-Job-Provider?type=design&node-id=0%3A1&mode=design&t=tlKUFYIySKYEsyFf-1
Job Seeker: https://www.figma.com/file/bSVDkRqbryoEFuZGzGXG8v/Tamakan-Job-Seeker?type=design&node-id=0%3A1&mode=design&t=aG1xdCNqiJm80ZfP-1

# Canva Presentation
https://www.canva.com/design/DAFuIerps88/OU0CPTI1rU1SGJOjQjHFrA/edit?utm_content=DAFuIerps88&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

# My Role
- Functions
  - get-application-by -Job-Id
  - get-application-by-job-uni-and-Job-Id
  - get-Application-by-major-and-job-id
  - get-apaplication-by-GPA
  - sort-job-application-by-GPA
  - get-application-by-status-and-job-id
  - get-application-by-status-and-jobseeker-id
  - accept-job-application-by-job-provide
  - regester-jobProvider
  - logout-jobProvider
  - update-job-provider
  - regester-jobSeeker
  - logout-jobSeeker
  - update-jobSeeker
  - send-email-to-jobSeekers

- Model
  - JobSeeker
  - JobProvider
  - User
  - JobProviderDTO
  - JobSeekerDTO
  - JobSeekerProfileDTO
    
- Relations
  - one to one (user and job seeker)
  - one to one(user and job provider)
  - one to one (job seeker and job seeker profile)
  - one to many (job seeker and job applications )

- Security
  - Applied Security Authority and Authentication for all my functions

- Junit testing
    -JobApplicationRepositoryTest

