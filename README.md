# Ergogenesis

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Database Structure](#database-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

**Ergogenesis** is a comprehensive platform designed to facilitate students in uploading their documents, projects, and patents. Faculty members can then review these submissions and take appropriate actions, such as forwarding them to organizations, filing patents, or submitting publications to official sites like IEEE.

## Features

- **Student Dashboard:** Separate dashboard for students to manage their submissions.
- **Faculty Dashboard:** Separate dashboard for faculty to review and manage submissions.
- **Document Management:** Upload and manage projects, patents, and publications.
- **User Authentication:** Secure login and signup with OTP verification.
- **Alumni Display:** Showcase alumni and their achievements.
- **Theme Customization:** Update and personalize themes.
- **Responsive UI:** User-friendly interface with modern design.
- **Password Management:** Options to reset and forget passwords.
- **Email Notifications:** Send OTPs and other notifications via email.

## Images
![Screenshot_12-7-2024_85858_localhost](https://github.com/user-attachments/assets/1b549382-1beb-4576-b1fc-66f3ef4d7f1c)
![Screenshot_12-7-2024_85736_localhost](https://github.com/user-attachments/assets/1b9616b3-41af-4c31-b9d4-a3a8f8e3febe)
![Screenshot_12-7-2024_9423_localhost](https://github.com/user-attachments/assets/2edfada9-b905-4fb8-9392-7b9d76a2af5e)
![Screenshot_12-7-2024_9336_localhost](https://github.com/user-attachments/assets/9e9585d3-c924-4327-8494-776e276c17e4)



## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL (via XAMPP)
- **Email Service:** PHP Mailer or similar service for sending OTPs
- **Server Environment:** XAMPP

## Installation

### Prerequisites

- XAMPP installed on your local machine
- A web browser (Chrome, Firefox, etc.)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ergogenesis.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd ergogenesis
   ```

3. **Move project files to XAMPP directory:**
   Copy the project folder to the `htdocs` directory of your XAMPP installation.

4. **Start XAMPP:**
   Open the XAMPP control panel and start Apache and MySQL.

5. **Import the database:**
   - Open [phpMyAdmin](http://localhost/phpmyadmin).
   - Create a new database named `ergogenesis`.
   - Import the provided SQL file into the `ergogenesis` database.

6. **Configure the environment:**
   Update the database connection settings in the `config.php` file.

7. **Run the application:**
   Open a web browser and navigate to [http://localhost/ergogenesis](http://localhost/ergogenesis).

## Usage

1. **Student:**
   - Register and log in to access the student dashboard.
   - Upload documents, projects, patents, and publications.
   - View and manage your submissions.

2. **Faculty:**
   - Log in to access the faculty dashboard.
   - Review student submissions.
   - Forward submissions to organizations, file patents, or submit to publications.

## Project Structure

```
ergogenesis/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── config/
│   └── config.php
├── public/
│   ├── index.php
│   ├── login.php
│   ├── signup.php
│   └── dashboard/
│       ├── student.php
│       └── faculty.php
├── src/
│   ├── controllers/
│   ├── models/
│   └── views/
└── README.md
```

## Database Structure
![mermaid-diagram-2024-04-18-100138](https://github.com/user-attachments/assets/9d8284a0-a5d5-402f-a840-a92d45dcfce4)
![image_2024-05-02_20-46-01](https://github.com/user-attachments/assets/66f50ec3-df93-43b4-bf97-00a4f2006120)
![fPR1Kjmm38Rl_nIPlNFejISeknHcM61OfdVXYApQs4vjXUcsqtUlGumg4pBDJ4_](https://github.com/user-attachments/assets/78271b94-2e68-4412-b6ab-9eb1c7ceaf0c)



## Contributing

We welcome contributions from the community! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

- **Project Maintainer:** NITIN PRAJWAL R
- **Email:** nitinprajwalr@gmail.com
- **GitHub:** [/nitinprajwal](https://github.com/nitinprajwal)
