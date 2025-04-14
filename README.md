# Contact Book

Contact Book is a contact management application built with **React** and **Redux Toolkit**. The project uses **Vite** as a modern bundler and connects to a backend hosted on [mockapi.io](https://mockapi.io/) to store contact data. The app allows you to add, display, filter, and delete contacts using asynchronous actions powered by `createAsyncThunk` and Axios.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributions](#contributions)
- [License](#license)

## Features

- **Add Contact:** Fill in the form to add a new contact. An alert is shown if the contact already exists.
- **Display Contacts:** View the list of contacts fetched from the backend.
- **Filter Contacts:** Filter contacts by name using a search input.
- **Delete Contact:** Remove a contact from the list and backend.
- **Asynchronous Operations:** Manage HTTP requests (GET, POST, DELETE) using Redux Toolkit’s `createAsyncThunk` and Axios.
- **Vite Proxy:** Avoid CORS issues in development by configuring a proxy in `vite.config.js`.

## Technologies

- **React**
- **Redux Toolkit**
- **Axios**
- **Vite**
- **CSS Modules**
- **mockapi.io** (backend)

## Design

![Screenshot 2025-04-12 223751](https://github.com/user-attachments/assets/f90948d0-da03-468b-b4ad-522ddbb47ea2)


## Project Structure

    goit-neo-react-hw-module7/
    ├── public/
    │   ├── favicon-16x16.png
    │   ├── favicon-32x32.png
    │   ├── favicon-48x48.png
    │   ├── AlexanderAndersen.jpg    
    │   └── index.html
    ├── src/
    │   ├── components/
    │   │   ├── App/
    │   │   │   ├── App.jsx
    │   │   │   └── App.module.css
    │   │   ├── ContactForm/
    │   │   │   ├── ContactForm.jsx
    │   │   │   └── ContactForm.module.css
    │   │   ├── ContactList/
    │   │   │   ├── ContactList.jsx
    │   │   │   └── ContactList.module.css
    │   │   └── Filter/
    │   │       ├── Filter.jsx
    │   │       └── Filter.module.css
    │   ├── redux/
    │   │   ├── contactsOps.js
    │   │   ├── contactsSlice.js
    │   │   ├── filtersSlice.js
    │   │   └── store.js
    │   ├── index.css
    │   └── main.jsx
    ├── vite.config.js
    └── package.json



## Installation

1. **Clonează repository-ul:**

   
   git clone https://github.com/username/goit-neo-react-hw-module7.git
   cd goit-neo-react-hw-module7


2. **Install Dependencies:**

    ```bash
   npm install


## Usage

1. **Run the App in Development Mode:**

   ```bash
   npm run dev


2. **Open in Browser:**

Open the URL displayed in the terminal (typically http://localhost:5173).

3. **Use the Application:**

Add a Contact: Fill out the form to add a new contact.

Filter Contacts: Use the filter input to search contacts by name.

Delete a Contact: Click the "Delete" button next to a contact to remove it.

## Testing
**UI Verification:**

Ensure the add contact form works correctly and new contacts appear in the list.

Test the filtering and deletion functionalities.

**Network & State Monitoring:**

Use the browser's DevTools Network tab to monitor HTTP requests and ensure there are no CORS or network errors.

Verify state updates using Redux DevTools.

**Production Build:**

    To build the application for production, run:

    
    npm run build

Then preview the build with:                                                                                        

    
    npm run preview


## Deployment
The app is deployed on Vercel. Visit the live application at:
https://your-app-url.vercel.app

Ensure that your production configuration is updated as needed for environment variables and deployment settings.

## Contributions
Contributions are welcome! Please follow these steps:

1. **Fork the repository.**

2. **Create a new feature branch:**

    ```bash
    git checkout -b feature/your-feature-name


3. **Commit your changes:**

    ```bash
    git commit -m "Add new feature"
    
4. **Push your branch:**

    ```bash
    git push origin feature/your-feature-name

5. **Open a pull request with your changes.**

## License
This project is licensed under the MIT License.

    ```pgsql
    Simply copy and paste the content above into a `README.md` file in your repository. You can customize sections (such as the live URL under Deploy) as needed.









