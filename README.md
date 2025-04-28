# 💼 AI Recruitment Agent Suite

A Streamlit application designed to revolutionize the hiring process by simulating an intelligent, full-service recruitment team. This application incorporates multiple AI agents, each specializing in a critical recruitment role, to automate and enhance various stages of the hiring workflow. From resume screening and technical evaluation to interview scheduling and communication, the system ensures an efficient, transparent, and responsive hiring experience.

Try out the application :[ https://agenthr.streamlit.app/](https://agenthr.streamlit.app/)
---

![image](https://github.com/user-attachments/assets/2c754bce-3cc7-42cb-b988-70780eb7d7d7)



## **Features**

### **Specialized AI Agents**

1. **Resume Analyzer Agent**
    - ATS integration for score-based resume analysis.
    - Role-specific skills and experience matching.
    - Selection and feedback generation.
2. **Communication Agent**
    - Drafts professional emails for both selection and rejection.
    - Provides constructive feedback to rejected candidates.
    - Handles follow-ups and ensures empathetic communication.
3. **Interview Scheduler Agent**
    - Automates interview scheduling using Zoom API.
    - Manages calendar integration and timezone handling.
    - Sends timely reminders and meeting details.
4. **Integrated ATS System**
    - Displays ATS scores, helping recruiters visualize skill matches.
    - Facilitates objective decision-making for better hiring outcomes.

---

## **End-to-End Recruitment Process**

- **Automated Resume Screening**: Quick and accurate resume analysis with real-time feedback.
- **Role-Specific Evaluation**: Ensures candidates meet job-specific requirements.
- **Streamlined Communication**: Sends personalized emails instantly after analysis.
- **Seamless Scheduling**: Coordinates interviews with minimal human intervention.

---

## **Business Impact**

The AI Recruitment Agent Suite addresses significant challenges in the HR industry:

- **Reduced Hiring Time**: Streamlines processes, allowing recruiters to focus on strategic tasks.
- **Enhanced Candidate Experience**: Candidates receive immediate results (selection/rejection), eliminating wait times.
- **Data-Driven Decisions**: ATS integration ensures fair and objective evaluation.
- **Improved Employer Branding**: Transparent and empathetic communication fosters a positive reputation.

For students or job seekers, this tool removes the anxiety of waiting for days to hear back after applying for a job. Instead, they receive results within minutes, enabling faster decision-making in their career journey.

---

## **Important Pre-Requisites**

1. **Create a Recruiter Email Account**
    - Use a dedicated Gmail account for recruitment communication.
    - Enable 2-Step Verification and generate an App Password.
    - App Passwords are 16-character codes generated via [Google App Passwords](https://support.google.com/accounts/answer/185833?hl=en).
2. **Set Up a Zoom Account**
    - Go to the [Zoom App Marketplace](https://marketplace.zoom.us/) and create a Server-to-Server OAuth App.
    - Obtain credentials: Client ID, Client Secret, and Account ID.
    - Add the required scopes for meeting and user management.
3. **OpenAI API Key**
    - Get an API key from [OpenAI](https://platform.openai.com/signup/).

---

## **How to Run**

### **1. Clone the Repository**

```bash
git clone <https://github.com/Bharath0726/AiRecruitingAgent>
cd AiRecruitingAgent
```

### **2. Install Dependencies**

```bash
bash
CopyEdit
pip install -r requirements.txt

```

### **3. Configure API Keys**

- Add OpenAI API Key, Zoom API credentials, and Email App Password in the Streamlit sidebar.

### **4. Run the Application**

```bash
bash
CopyEdit
streamlit run agent3.py

```

---

## **System Components**

### **Resume Analyzer Agent**

- **ATS Integration**: Analyzes resumes using an Applicant Tracking System to calculate a match score based on job-specific skills.
- **Skills and Experience Matching**: Evaluates resumes for both technical and practical skill alignment.
- **Feedback Generation**: Provides detailed feedback on matched and missing skills for transparency.

### **Communication Agent**

- **Email Drafting**: Sends professional, personalized emails for both selection and rejection outcomes.
- **Feedback for Rejection**: Delivers constructive advice to help candidates improve their skills.
- **Follow-Up Management**: Ensures timely communication with candidates, maintaining a positive experience.

### **Interview Scheduler Agent**

- **Zoom Integration**: Schedules interviews seamlessly using the Zoom API.
- **Calendar and Timezone Handling**: Ensures schedules accommodate global candidates by resolving timezone conflicts.
- **Reminders and Notifications**: Sends reminders to both candidates and recruiters to avoid missed meetings.

### **Integrated ATS System**

- **Transparent Evaluation**: Displays ATS scores directly in the interface for easy decision-making.
- **Data-Driven Selection**: Ensures objective hiring decisions by aligning candidate skills with role requirements.

---

## **Candidate Experience**

- **User-Friendly Interface**: Simple and intuitive platform for resume uploads and interaction.
- **Real-Time Feedback**: Candidates receive immediate ATS scores and hiring outcomes.
- **Transparent Communication**: Keeps candidates informed throughout the process, fostering trust and satisfaction.

---

## **Technical Stack**

- **Framework**: Streamlit
- **AI Model**: OpenAI GPT-4
- **Integration**: Zoom API, EmailTools
- **PDF Processing**: PyPDF2
- **State Management**: Streamlit Session State

---

## **Disclaimer**

This tool is designed to assist recruitment teams but is not a substitute for human judgment. Final hiring decisions should always be reviewed and approved by human recruiters.

---

## **Future Enhancements**  
- **Integration with Calendar Services**: Seamlessly sync with platforms like Google Calendar and Outlook for better scheduling.  
- **Gamified Skills Assessment**: Incorporate gamification techniques to evaluate technical and soft skills interactively.  
- **Integration with Job Portals**: Connect with popular job boards (e.g., LinkedIn, Indeed) for automatic resume collection and job postings.  
- **Data Analytics Dashboard**: Provide visual insights into the recruitment process, such as time-to-hire, role demand, and candidate demographics.  

