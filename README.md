# 🌍 Tourist Place Explorer

**An interactive web application to search, explore, and learn about top tourist destinations using React!** 

[![React](https://img.shields.io/badge/React-17.0.2-blue.svg)](https://reactjs.org/) [![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0.2-purple.svg)](https://getbootstrap.com/)

---

## 🎯 **Overview**

This project provides users with a seamless experience to:
- Search for tourist destinations from an extensive list.
- View detailed information about each location.
- Explore an engaging, responsive, and well-designed interface.
- Utilize a dynamically updated Excel-based dataset for information.

---

## 🔧 **Features**

- **Search Functionality**: 
  - A responsive search bar with a dropdown for place recommendations.
  - Filters and shows matching results as you type.
  
- **Dynamic Place Details**: 
  - Displays detailed information (name, description, image, location) for selected places.
  - Auto-updates place details when new places are searched.

- **Excel-Based Data Loading**:
  - Reads place data from an Excel file (`tourist.xlsx`), including attributes like name, description, image, and more.

- **Responsive Design**: 
  - Built with Bootstrap for mobile-first responsiveness and clean UI.
  
---

## 🏗 **Tech Stack**

This project leverages the following technologies and libraries:

- **Frontend**: 
  - [React.js](https://reactjs.org/): Component-based UI library for building user interfaces.
  - [Bootstrap 5](https://getbootstrap.com/): For styling and layout, ensuring responsive design.
  
- **Utilities**: 
  - [readExcel](https://www.npmjs.com/package/xlsx): For reading Excel files and converting them into JSON data.
  - [react-icons](https://react-icons.github.io/react-icons/): Icons for improving UI/UX.

---

## 🚀 **Installation and Setup**

Follow these steps to get the project up and running on your local machine:

### **1. Clone the Repository**
bash
git clone https://github.com/your-username/tourist-place-explorer.git
cd tourist-place-explorer
2. Install Dependencies
Make sure you have Node.js installed, then run:

bash
Copy code
npm install
3. Start the Application
To start the app locally on localhost:3000, use:

```bash
Copy code
npm start
4. Add the Excel File
Place your tourist.xlsx file containing place data in the public folder or wherever specified in your code.

📂 Project Structure
Here's a quick breakdown of the major files and directories in the project:

plaintext
Copy code
tourist-place-explorer/
├── public/
│   └── tourist.xlsx         # Excel file with place data
├── src/
│   ├── components/
│   │   ├── SearchBar.js     # Search functionality with filtering
│   │   ├── PlaceDetails.js  # Display detailed place info
│   │   └── App.js           # Main container component
│   ├── utils/
│   │   └── readExcel.js     # Utility function for reading Excel data
│   └── index.js             # Entry point for the app
├── App.css                  # Global styles
└── README.md                # This file
```
## 📝 How to Use
Search for a Place:

Start typing in the search bar to get a list of matching places from the Excel dataset.
Click on any place in the dropdown to view detailed information.
View Place Details:

After selecting a place, view its name, description, image, and other related details on the same page.
Responsive and Accessible:

The interface is responsive and accessible across devices with smooth transitions and clean layouts.
🛠 Key Components
SearchBar: Handles user input and displays filtered places in real-time from the Excel dataset.
PlaceDetails: Shows detailed information (place name, description, image, etc.) when a place is selected.
readExcel Utility: Reads and converts the Excel file into a usable format for rendering place details.
🔍 Search Example
plaintext
Copy code
Search for 'Paris' to explore the Eiffel Tower, its location, and other details!
🎉 Demo
🚀 Check out the live demo of the project at: Live Demo Link

👨‍💻 Contributing
Feel free to submit a Pull Request for any bug fixes or improvements. To contribute:

Fork the repository.
Create a new branch (feature/my-new-feature).
Commit your changes.
Push the branch.
Create a Pull Request.
📧 Contact
Developer: Anan (GitHub: your-github-profile)
Email: your-email@example.com
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

Built with 💙 by Anan for travelers who love to explore!
