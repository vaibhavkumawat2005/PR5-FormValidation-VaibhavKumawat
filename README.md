<h1>README</h1>

  <h2>Project Overview</h2>
  <p>
    This project is a simple user registration form and data management system built using React. It allows users to input personal information, validate the data, and store it in local storage.
  </p>

  <h2>Features</h2>
  <ul>
    <li>User Registration with form validation.</li>
    <li>Data persistence using browser's local storage.</li>
    <li>Ability to view, edit, and delete user data.</li>
  </ul>

  <h2>Screenshots and Video</h2>
  
  
![Screenshot 2025-01-10 181839](https://github.com/user-attachments/assets/8b28aeee-ccec-4bf6-8a14-d497bcaa58b6)
![Screenshot 2025-01-10 181902](https://github.com/user-attachments/assets/832bdfb9-a1ed-4da6-8143-3144f35616c9)


  <h2>Setup Instructions</h2>
  <ol>
    <li>Clone the repository to your local machine:</li>
    <pre><code>git clone https://github.com/your-repo-link.git</code></pre>

   <li>Navigate to the project directory:</li>
    <pre><code>cd your-project-directory</code></pre>

  <li>Install dependencies:</li>
    <pre><code>npm install</code></pre>
    <li>Start the development server:</li>
    <pre><code>npm start</code></pre>
    <li>Open the application in your browser at:</li>
    <pre><code>http://localhost:3000</code></pre>
  </ol>

  <h2>Usage</h2>
  <p>
    After launching the application, you can:
  </p>
  <ul>
    <li>Fill out the registration form and submit it.</li>
    <li>View the registered users in a table format.</li>
    <li>Edit or delete user entries as needed.</li>
  </ul>

  <h2>Form Fields</h2>
  <ul>
    <li><strong>Username:</strong> User's name (required).</li>
    <li><strong>Email:</strong> Valid email address (required).</li>
    <li><strong>Password:</strong> Minimum 8 characters with at least one uppercase, one lowercase, one number, and one special character (required).</li>
    <li><strong>Phone:</strong> User's phone number (required).</li>
    <li><strong>Hobby:</strong> Checkbox selection of hobbies (required).</li>
    <li><strong>Gender:</strong> Radio button selection (required).</li>
    <li><strong>Address:</strong> User's address (required).</li>
    <li><strong>City:</strong> Dropdown selection of cities (required).</li>
  </ul>

  <h2>File Structure</h2>
  <pre><code>
  src/
  ├── components/
  │   ├── Form.js        // Main form and logic
  │   ├── View.js        // Table to view user data
  ├── App.js            // Root component
  ├── index.js          // Entry point
  └── styles.css        // Optional custom styles (if used)
  </code></pre>

  <h2>Technologies Used</h2>
  <ul>
    <li>React (Functional Components)</li>
    <li>JavaScript (ES6+)</li>
    <li>Local Storage (Browser API)</li>
  </ul>

  <h2>Future Improvements</h2>
  <ul>
    <li>Implement a backend for persistent data storage.</li>
    <li>Add more robust error handling and notifications.</li>
    <li>Enhance the UI with better styling.</li>
  </ul>

  <h2>License</h2>
  <p>
    This project is open-source and available under the MIT License.
  </p>
