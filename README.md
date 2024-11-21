
# UniVerse 🌌  
**Your go-to platform for IGDTUW communications, collaborations, and resources**  

UniVerse is a web-based portal designed to simplify access to resources, portals, and events for students and faculty of IGDTUW. It integrates various functionalities, including a chat system (UniChat) built using Next.js, making collaboration effortless.
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160336.png)

---

## Features ✨  
### 1. **Home**  
- Highlights the university and the main features of UniVerse.

### 2. **Uni Chat**  
- Real-time messaging for university students.  
- Department-based groups to avoid message cluttering.  
- Built using the [Next.js Messenger Clone](https://github.com/Tannu-Rawat/Next-js---Messenger-Clone).  

### 3. **Resource Hub**  
- Store and access class notes semester-wise.  

### 4. **Event Calendar**  
- Save important dates like deadlines and events.  
- Never miss a deadline again.  

### 5. **Ask Indu**  
- An intelligent chatbot for accessing college information and details about societies.  
- Built with Flask, HTML, and other technologies.  

### 6. **Important Links**  
- Quick access to:  
  - College website  
  - ELMS  
  - ERP portal  
  - E-library  

### 7. **Help and FAQs**  
- Reach out to the admin for support.  

### 8. **Feedback**  
- Share your feedback through a dedicated form.  

### 9. **About Us**  
- Meet the team behind UniVerse.   

---


## **Tech Stack 🛠️**

### **Frontend**  
- **HTML, CSS, JS**: Core technologies for designing and structuring the UniVerse platform.  
- **Bootstrap 5**: Provides responsive, mobile-first UI components to enhance user experience.  
- **Google Fonts**: Incorporates visually appealing fonts like *Chewy*, *Pacifico*, and *Poppins* for a modern and stylish look.  

### **UniChat (Real-Time Chat System)**  
- **Next.js**: A React framework used for building a fast and real-time chat interface.  
- **Pusher API**: Enables real-time bi-directional communication for seamless messaging.  
- **NextAuth**: Ensures secure and easy authentication for users.  
- **MongoDB**: Serves as the database for storing user information and chat histories.
- **Node.js**: Backend runtime environment for building scalable, real-time messaging functionality.

### **Indu (Chatbot with NLP)**  
- **Python**: The primary language for building the NLP chatbot.  
- **Natural Language Processing (NLP)**:  
  - **Attributes**: Handles *categories*, *subcategories*, and *responses*.  
  - Implements **BFS (Breadth-First Search)** to traverse through categories and subcategories dynamically.  
  - Fetches responses directly from subcategories or based on keywords stored in the `more` column if mentioned repeatedly.  
  - Uses the **FuzzyWuzzy** library to handle minor spelling mistakes for keywords with more than four letters.  
- **Flask**: A lightweight web framework to deploy Indira as a web application for interaction.

---

## Project Images

![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160336.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160408.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160545.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160643.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160717.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160559.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160744.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160751.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160806.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20160858.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20161143.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20161152.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20161203.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20161210.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20161229.png)
![Screenshot](https://github.com/Tannu-Rawat/UNIVERSE/blob/main/Screenshot%202024-11-12%20161237.png)



---

## Installation and Setup

### **Steps to Clone and Run the UniVerse  Website**

1. **Clone the Repository**  
   Download the UniVerse HTML website repository by running:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Project Directory**  
   Change into the directory where the repository was cloned:
   ```bash
   cd universe-html
   ```

3. **Run the Website Locally**  
   Since this is an HTML-based website, no special build tools are required. You can use any method to serve static files locally, by using live server in vs code.

Here's how to run the **UniChat** (Messenger Clone) and **Aindu** projects on your local server:

### **For UniChat **
    Visit (https://github.com/Tannu-Rawat/Next-js---Messenger-Clone) to clone the project. All instructions are given here.
  **Connect with the UniVerse App**  
   Open the **UniVerse HTML project**, and ensure the **`localhost` link in your HTML** correctly points to `http://localhost:3000` where the Messenger Clone is running.  

### **For Ask Indu**

1. **Clone the Repository**  
   Download the Aindu project repository:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Directory**  
   Enter the folder where the project is stored:
   ```bash
   cd aindu
   ```

3. **Install Dependencies**  
   Run the following command to install dependencies:
   ```bash
   npm install
   ```

4. **Start the Server**  
   Start the local server:
   ```bash
   npm start
   ```
   By default, the app will run on `http://localhost:3002`.

5. **Update the UniVerse App Link**  
   Make sure the **`localhost` link** in your HTML for Aindu matches the port `3002`:
   ```html
   <a href="http://localhost:3002" target="_blank" class="nav-link text-white">Aindu</a>
   ```

6. **Test the Integration**  
   Open the UniVerse app and click the **Aindu** link to verify the functionality.

---

### **Common Issues and Solutions**

- **Ports Conflicts:**  
  If the default ports (`3000` or `3002`) are already in use, you can specify another port when starting the server:
  ```bash
  npm start -- --port <custom-port>
  ```
  Update the **UniVerse HTML file** to match the new port.

- **Missing Dependencies:**  
  If you encounter errors during `npm install`, ensure your Node.js version is up-to-date.

- **Testing in Browser:**  
  Open `index.html` of the **UniVerse app** in your browser to test all links.

## Future Enhancements 🌟  

- Full deployment of UniChat to a cloud platform like Vercel or Netlify for public access.  
- Improved user authentication and profile management.  
- Integration of additional IGDTUW-specific tools and resources.  

---

## License 📜  
This project is licensed under the MIT License.  

---
## Thank You :)


