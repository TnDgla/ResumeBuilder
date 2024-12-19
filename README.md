### **Project Name: AI Resume Builder App**

The **AI Resume Builder App** is a web application designed to help users create professional resumes effortlessly. Leveraging AI for personalized summaries, the app allows users to generate resumes with features like real-time previews, dynamic styling, and social media sharing.

---

### **Mission and Objectives**

#### **Mission:**
To provide users with an intuitive, efficient, and feature-rich platform for creating customized resumes powered by AI.

#### **Objectives:**
1. **User Authentication:**
   - Implement secure login and registration using Clerk.
   - Support multiple social media authentication options.

2. **Resume Management:**
   - Allow users to create, edit, and delete resumes.
   - Provide real-time preview and customization options.

3. **AI Integration:**
   - Use AI to generate professional summaries and bullet points.

4. **Responsive Design:**
   - Ensure seamless functionality across devices.

5. **Deployment:**
   - Deploy the application on Hostinger and Render for public access.

---

### **Technology Stack**

#### **Frontend**
1. **React.js with Vite**
   - **Why?**: Optimized performance and fast builds.
   - **Use Case**: Builds dynamic user interfaces and real-time previews.

2. **Tailwind CSS**
   - **Why?**: Simplifies styling with utility-first classes.
   - **Use Case**: Creates a responsive and aesthetically pleasing design.

3. **ShadCN UI**
   - **Why?**: Provides pre-built, customizable components.
   - **Use Case**: Implements components like buttons, modals, and forms.

---

#### **Backend**
1. **Strapi**
   - **Why?**: Flexible CMS for managing content.
   - **Use Case**: Manages resume data and user-generated content.

2. **Node.js**
   - **Why?**: Ensures efficient server-side development.
   - **Use Case**: Handles API requests and connects the frontend with the database.

3. **MySQL**
   - **Why?**: Provides robust data storage and management.
   - **Use Case**: Stores user information and resume details.

4. **OpenAI (Generative AI)**
   - **Why?**: Powers AI-based summary generation.
   - **Use Case**: Generates personalized content for resumes.

---

#### **Deployment**
1. **Frontend Hosting: Vercel**
   - **Why?**: Optimized for React apps.
   - **Use Case**: Deploys the client-side application.

2. **Backend Hosting: Render and Hostinger**
   - **Why?**: Reliable platforms for backend services.
   - **Use Case**: Hosts APIs and the database.

---
#### **Flowchart**

![image](https://github.com/user-attachments/assets/17fd77dd-0b5b-4f24-82a3-991e4b64dc23)

---

### **Program Overview**

This project is structured to ensure systematic development, focusing on incremental feature implementation for a smooth transition from basic to advanced functionalities.

**NOTE:** Participants are encouraged to customize designs and functionalities to enhance the application’s uniqueness.

---

## **Week-by-Week Learning Plan**

### **Week 1: Project Setup and UI Design**
- **Goal:** Set up the foundational structure and design the app UI.
- **Tasks:**
  1. Initialize the project using **React.js** with Vite.
     - **Reading:** [React.js Official Docs](https://reactjs.org/docs/getting-started.html)
     - **Video:** [React with Vite Setup](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
     - **Video:** [Nodejs tutorial](https://www.youtube.com/watch?v=BLl32FvcdVM&t=2s)
  2. Integrate **Tailwind CSS** and ShadCN UI components.
     - **Reading:** [Tailwind CSS Docs](https://tailwindcss.com/docs/installation)
     - **Video:** [Tailwind CSS Crash Course](https://www.youtube.com/watch?v=_9mTJ84uL1Q&t=5s)
  3. Build the landing page, login, and dashboard layouts.
     - **Reading:** [ShadCN UI Documentation](https://ui.shadcn.com/docs)
     - **Video:** [Building Responsive UIs with Tailwind](https://www.youtube.com/watch?v=H6GBwdGiOLM)

- **Deliverables:**
  - A responsive landing page and basic layouts for login and dashboard.

---

### **Week 2: User Authentication**
- **Goal:** Implement secure user authentication using Clerk.
- **Tasks:**
  1. Set up Clerk for social media authentication.
     - **Reading:** [Clerk Documentation](https://clerk.dev/docs)
     - **Video:** [Clerk Authentication Setup](https://www.youtube.com/watch?v=l2wyuYRN2K4)
  2. Protect routes for authenticated users.
     - **Reading:** [Protected Routes in React](https://reactrouter.com/en/main)
     - **Video:** [React Router Dom Tutorial](https://www.youtube.com/watch?v=Ul3y1LXxzdU)

- **Deliverables:**
  - Functional login/signup pages with social media authentication.

---

### **Week 3: Resume Creation Features**
- **Goal:** Develop the resume creation workflow.
- **Tasks:**
  1. Set up APIs for creating, fetching, and updating resumes in Strapi.
     - **Reading:** [Strapi Documentation](https://strapi.io/documentation)
     - **Video:** [Getting Started with Strapi](https://www.youtube.com/watch?v=6FnwAbd2SDY)
  2. Implement dynamic themes and real-time preview.
     - **Reading:** [React State Management](https://reactjs.org/docs/hooks-state.html)
     - **Video:** [React Context API Tutorial](https://www.youtube.com/watch?v=35lXWvCuM8o)
  3. Integrate AI-powered summary generation using OpenAI.
     - **Reading:** [OpenAI API Documentation](https://platform.openai.com/docs/)
     - **Video:** [OpenAI Integration Guide](https://www.youtube.com/watch?v=u2rvIO4n92s)

- **Deliverables:**
  - Core functionality for creating and customizing resumes.

---

### **Week 4: Dashboard and Management**
- **Goal:** Create a dashboard for managing resumes.
- **Tasks:**
  1. Build APIs for editing, deleting, and listing resumes.
     - **Reading:** [RESTful API Design](https://restfulapi.net/)
     - **Video:** [Building REST APIs with Node.js](https://www.youtube.com/watch?v=pKd0Rpw7O48)
  2. Design the dashboard interface with filters and sorting.
     - **Reading:** [React Table Components](https://react-table.tanstack.com/)
     - **Video:** [Building Dashboards in React](https://www.youtube.com/watch?v=SBvmnHTQIPY)

- **Deliverables:**
  - A functional dashboard for managing multiple resumes.

---

### **Week 5: Deployment and Final Touches**
- **Goal:** Deploy the application and refine features.
- **Tasks:**
  1. Deploy the frontend to Vercel and backend to Render.
     - **Reading:** [Deploying React Apps](https://vercel.com/docs)
     - **Video:** [Deploying Full-Stack Apps](https://www.youtube.com/watch?v=l134cBAJCuc)
  2. Test and optimize for performance and usability.
     - **Reading:** [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
     - **Video:** [Testing React Apps](https://www.youtube.com/watch?v=8Xwq35cPwYg)

- **Deliverables:**
  - Fully deployed AI Resume Builder app accessible online.

---
### Screenshots
![Screenshot (388)](https://github.com/user-attachments/assets/f3cdf7cf-55b4-461e-8822-6e96d7b99030)
![Screenshot (389)](https://github.com/user-attachments/assets/91278abd-eaeb-428d-b642-42c8350ef38d)
![Screenshot (390)](https://github.com/user-attachments/assets/3855cd2f-cf5b-4062-ba7d-be8b15659aab)
![Screenshot (391)](https://github.com/user-attachments/assets/68276f67-7ea3-4b65-a788-6414d001791f)
![Screenshot (392)](https://github.com/user-attachments/assets/e51e76ab-6971-4eba-a901-0708fffa22b6)
![Screenshot (393)](https://github.com/user-attachments/assets/f4e8b7dc-e046-478a-bc0e-22e91ca2f139)
![Screenshot (379)](https://github.com/user-attachments/assets/4c98aec4-01a3-4242-ad56-f376ba7abc69)
![Screenshot (380)](https://github.com/user-attachments/assets/9ca3dbf7-b46b-4eda-b587-44d1b6646710)
![Screenshot (381)](https://github.com/user-attachments/assets/3a3e8734-6cbe-44f5-af66-96b854f7e816)
![Screenshot (382)](https://github.com/user-attachments/assets/b6801a2d-fc57-477a-8cf9-5aaa5dcc5f13)
![Screenshot (383)](https://github.com/user-attachments/assets/16ebd52b-9738-4ad5-97eb-e136708a3c7f)
![Screenshot (384)](https://github.com/user-attachments/assets/e6daf293-d186-48e9-8081-bad0d4540ded)
![Screenshot (385)](https://github.com/user-attachments/assets/876822db-4018-4780-82e7-895d96d587d6)
![Screenshot (386)](https://github.com/user-attachments/assets/0cb45bc7-753c-4959-af5e-115d6118cf5f)
![Screenshot (387)](https://github.com/user-attachments/assets/21d2ad56-2684-46e3-bf1a-52617f6a61ae)


---

### **References**
1. [React Documentation](https://reactjs.org/docs/getting-started.html)
2. [Tailwind CSS Documentation](https://tailwindcss.com/docs/installation)
3. [Strapi Documentation](https://strapi.io/documentation)
4. [OpenAI API Documentation](https://platform.openai.com/docs/)
5. [Vercel Deployment Guide](https://vercel.com/docs)
6. https://www.youtube.com/watch?v=RiUh_8VTGYM
7. https://github.com/rrs301/AI-Resume-Builder

