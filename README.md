# [shpe-main](https://gcbens.github.io/shpe-main/)
## SHPE Website
### Description / Abstract
As part of our Software Development II course with Dr. Anca, our team has been developing SHPE Georgia, a modern web application designed to support the local chapter of the Society of Hispanic Professional Engineers (SHPE) in Georgia. The goal of this project is to develop a web app that lets SHPE Georgia distribute information online and be able to automate their activities. So far, our team has created a functional login/signup/logout function, which will allow members and sponsors to log into using their unique member ids. We have a navigation system that enables users to navigate from page to page without any issues. We have essentially finished most of the groundwork for future teams to build upon this. With this in mind, the scalable of our structure allows future extensions such as admin dashboards, resource uploads, and automated event reminders. The impact of this project lies in its ability to streamline chapter operations, strengthen community connection, and support the academic and professional growth of SHPE members across Georgia.

With this in mind, the scalable of our structure allows future extensions such as admin dashboards, resource uploads, and automated event reminders. The impact of this project lies in its ability to streamline chapter operations, strengthen community connection, and support the academic and professional growth of SHPE members across Georgia.

### Updates Spring 2026

During the Spring 2026 semester, our team enhanced an existing platform by implementing secure role based access control with four user roles: Super Admin, Admin, Sponsor, and Member. Each role has defined permissions to ensure proper access to features and data.

We also introduced a Resume Dropbox feature that allows members to upload resumes while restricting access to administrators for viewing and exporting. In addition, we improved the user interface for better navigation and overall user experience.

Our team followed Agile practices using Jira to manage development, track progress, and organize tasks. These improvements strengthen the platform’s ability to manage chapter operations, increase engagement, and support professional development for SHPE members.

## Technologies
- **Frontend:** [React.js](https://react.dev/), [Bootstrap](https://getbootstrap.com/)
- **Backend:** [Node.js](https://nodejs.org/) (18.17 or newer, 20.x LTS recommended), [Express.js](https://expressjs.com/), [Mongoose](https://mongoosejs.com/), [bcrypt.js](https://github.com/dcodeIO/bcrypt.js), [JSON Web Token (JWT)](https://jwt.io/)
- **Database:** [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- **Version Control:** [Git](https://git-scm.com/) / [GitHub](https://github.com/)
### Udpates Spring 2026
- Added [Postman](https://www.postman.com/downloads/) for end-to-end testing, and improved authentication and validation mechanisms.

## Working Features
- **Login System**

We implemented a functional login system that allows users to securely access the platform. This provides the foundation for more advanced access control later.

- **Event Calendar and Event System**

We created an event calendar where users can view upcoming events. The system supports adding, viewing, and updating events as needed.

- **Scalable Architecture**

The system is built in a way that supports future growth, such as higher membership counts and more event activity. New features can be added without major structural changes.

- **User-Friendly Interface**

We designed the interface to be simple and intuitive so all users, including first-time visitors, can navigate the site easily. The layout focuses on clarity and accessibility.

- **Fast Page Response**

Pages load smoothly and meet the expected performance target of loading within about five seconds under normal conditions. This improves the overall experience for users.

- **Maintainable Modular Design**

The system is organized into clear, modular components, making updates and debugging easier. Documentation supports future fixes and feature additions.

### Working Features Added by Team Oracle (Updates Spring 2026)
- **Role-Based Access Control**

Implemented a comprehensive role-based access system with four distinct roles: Super Admin, Admin, Sponsor, and Members. Each role has specific permissions and access levels, enabling secure and organized management of platform features and user data.

- **Resume Dropbox**

Created a centralized repository where members can upload and manage their resumes. This feature streamlines the process for sponsors to review member qualifications and for the platform to maintain organized documentation of member credentials.

- **Calendar UI Functionality**

Enhanced event management with full calendar integration allowing members to view, filter, and manage upcoming SHPE events. The calendar provides better visibility of the chapter's schedule and helps members plan their participation.

- **Admin Portal**

Built a dedicated administrative interface for managing platform operations, including user management, event administration, and content management. The portal provides super admins and admins with the tools needed to effectively oversee chapter activities and user accounts.

- **Instagram Feed Widget**

Added an interactive Instagram feed widget that dynamically displays the chapter’s social media posts directly on the homepage. This feature enhances user engagement by showcasing real-time updates, events, and community highlights while maintaining a seamless and visually appealing user experience.

## Installation Steps

Follow these steps to install and set up the SHPE Georgia web application from scratch.

### Prerequisites
Before starting, ensure you have the following installed:
- **Git** - https://git-scm.com/
- **Node.js (20.x LTS recommended)** - https://nodejs.org/ (includes npm)
- **MongoDB Account** - Create a free account at https://www.mongodb.com/cloud/atlas
- **VS Code (optional but recommended)** - https://code.visualstudio.com/

### Step-by-Step Installation

#### 1. Clone the Repository
```bash
git clone https://github.com/GGC-SD/shpe.git
cd shpe
```

#### 2. Set Up MongoDB Atlas
1. Go to https://www.mongodb.com/cloud/atlas
2. Create or log in to your account
3. Create a new cluster (free tier is available)
4. Create a database user with username and password
5. Get your connection string (you'll need this for the `.env` file)

#### 3. Create Backend Environment Variables
Create a `.env` file in the `my-mern-app/backend` directory with the following variables:
```
PORT=5000
MONGO_URI=
JWT_EXPIRE=
NODE_ENV=development
```

#### 4. Verify Installation
Check that all dependencies installed correctly by confirming that `node_modules` folders exist in both `backend` and `frontend-clean` directories.

## How to Run

### Running the Development Server

#### Terminal 1: Start the Backend Server
```bash
cd my-mern-app/backend
npm run dev
```

The backend will start on `http://localhost:5000` (or the port specified in your `.env` file).

#### Terminal 2: Start the Frontend Application
```bash
cd my-mern-app/frontend-clean
npm start
```

The frontend will automatically open in your browser at `http://localhost:3000`.

### Accessing the Application
- **Frontend:** http://localhost:3000
- **Backend API:** http://localhost:5000

## Client Information
**Client:** Gabe Kerven and Oliver Santiesteban Jair, SHPE - SHPE Georgia Professional Chapter

## Team: ☕️ CoffeeCoders ☕️
### Fall Semester 2025
* **Eli Dunmoye**
  1. _UI/UX design_ ☁️
  2. _Team Manager_ 💤
    
<img width="150" height="200" alt="image" src="https://github.com/user-attachments/assets/fa4ebf2b-9c1d-44b6-9895-1740165f00eb"/>

* **Shayla Pham**
  1. _Data Modeler_ 📊
  2. _Documentation Lead_ 📝

<img width="150" height="200" alt="image" src="https://github.com/user-attachments/assets/6743bc2c-8572-4578-bd93-10548e1269c7"/>

* **Ademola Akiwowo**
  1. _Testing lead_
  2. _Programmer_

<img width="150" height="200" alt="image" src="https://github.com/user-attachments/assets/70a65a70-b512-4a8a-a821-a7b6e6f94fff"/>

* **Razan Abdalla**
  1. _Code architecture/lead programmer_
  2. _Client liaison 30%_

## Team: 🧿 Oracle 🧿
### Spr-2026 🌟
<img
  src="https://media.licdn.com/dms/image/v2/D4E03AQG7ZIiRB9Cs_A/profile-displayphoto-shrink_400_400/B4EZWl5YQ9HUAo-/0/1742245043330?e=1778716800&v=beta&t=v-n8USoc_fBr-zRDZ2a_hLwO5i-dWXbw2ZNttNk-n6w"
  alt="Professional Portrait of Software Engineer Gabens Volmar"
  width="120"
  style="border-radius: 50%;"
/>

**Gabens Volmar**
1. _Programmer (20%)_
2. _Code Architecture / Lead Programmer (55%)_
3. _Team Manager (PM) (25%)_

---

<img
  src="https://plain-enam-prod-public.komododecks.com/202604/27/UuaiOHJjor3BE83Zx1x3/image.png"
  alt="Laureesh Volmar"
  width="150"
  height="200"
/>

**Laureesh Volmar**
1. _Programmer (20%)_
2. _Data Modeler (50%)_
3. _UI Designer (30%)_

---

<img
  src="https://i.postimg.cc/t4g7Jrj1/eyob.jpg"
  alt="Eyob Kabeto"
  width="150"
  height="200"
/>

**Eyob Kabeto**
1. _Programmer (20%)_
2. _Testing Lead (50%)_
3. _Documentation Lead (20%)_
4. _Client Liaison (10%)_

---

## Project Files and Documentation (Spring 2026)
- **Backend README:** [Backend Documentation](./my-mern-app/backend/README.md)
- **Frontend README:** [Frontend Documentation](./my-mern-app/frontend-clean/README.md)
- **Testing Instructions (Backend):** [Backend Testing Guide](./my-mern-app/backend/tests/Backend_Testing_Instructions.txt)
- **Testing Instructions (Frontend):** [Frontend Testing Guide](./my-mern-app/frontend-clean/tests/Frontend_Testing_Instructions.txt)

## Links
### Fall 2025
- **Deployed Project:** TBD
- **Documentation / Resources:** TBD
- **Final Vlog Demo:** https://www.youtube.com/watch?v=Ufed5_C3MjI&feature=youtu.be
- **Flyer:** https://github.com/user-attachments/assets/7ec86ede-7f47-46cf-888c-13f5d2a72bdd

### Updates Spring 2026
- **Final Vlog Demo:** https://youtu.be/Pl4xSoVsxTs?si=D53QjIav_ojCxUMN
- **Flyer:** https://github.com/user-attachments/assets/e6d90455-bf89-4185-9feb-a005d7421311


## License
This project is licensed under the MIT License (Modified for Educational Use).  
See [LICENSE.md](./LICENSE.md) for full details.
