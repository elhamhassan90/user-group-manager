# User-Group-Manager

## Project Overview

User-Group-Manager is a Bash-based script designed for managing users and groups on a Linux-based system. It utilizes an easy-to-use menu interface powered by `whiptail` for interactive user management tasks. The project includes features such as adding, deleting, modifying users and groups, as well as enabling/disabling accounts, all while logging actions for auditing.

## Features

- **Add User**: Add a new user to the system.
- **Delete User**: Remove an existing user and their home directory.
- **Modify User**: Modify an existing user's username.
- **List Users**: List all normal users on the system.
- **List User Details**: Get detailed information about a specific user.
- **Add Group**: Add a new group.
- **Modify Group**: Modify an existing group and its members.
- **List Groups**: List all groups on the system.
- **Enable User**: Unlock a user account.
- **Disable User**: Lock a user account.
- **Delete Group**: Remove a group from the system.
- **Change Password**: Change a user's password.
- **Exit**: Exit menu.
## Project Structure

user-group-manager/
├── menu              # Main script to launch the interactive menu
├── functions         # Contains all the core functions for user/group management
├── install           # Script to install necessary dependencies
├── logs/             # Directory for storing log files
├── screenshots/      # Directory for storing screenshots for documentation
└── README.md         # Project documentation


## Installation

To get started with User-Group-Manager, follow the installation steps below.

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    cd user-group-manager
    ```

2. **Run the installation script**:
    ```bash
    bash install
    ```

This will install all the necessary dependencies and ensure the script works properly on your system.

## Usage

Once the installation is complete, you can execute the script as follows:

1. **Run the script**:
    ```bash
    bash menu
    ```

2. The script will present a menu with various options for managing users and groups.

## Logging

All actions performed using the script will be logged to the `logs/` directory for auditing purposes. Each log entry includes details about the action taken, such as the username/group, timestamp, and the action performed (e.g., user added, user deleted, etc.).

Logs can be viewed using the following command:

```bash
cat logs/user-group-manager.log



## Screenshots

The following screenshots demonstrate the GUI interface of the User-Group-Manager script:

1. **Main Menu**:
   ![Main Menu Screenshot](screenshots/1.png)

2. **Add User**:
   ![Add User Screenshot](screenshots/2.png)

3. **Delete User**:
   ![Delete User Screenshot](screenshots/3.png)

4. **Modify User**:
   ![Modify User Screenshot](screenshots/4.png)

5. **List Users**:
   ![List Users Screenshot](screenshots/5.png)

6. **List a User and Groups**:
   ![List a User and All Groups Screenshot](screenshots/6.png)

7. **Add & Modify a Group**:
   ![Add & Modify a Group Screenshot](screenshots/7.png)

8. **Enable & Disable a User**:
   ![Enable & Disable a User Screenshot](screenshots/8.png)

9. **Delete Group**:
   ![Delete Group Screenshot](screenshots/9.png)

10. **Change Password**:
   ![Change Password Screenshot](screenshots/10.png)

11. **Exit**:
   ![Exit Screenshot](screenshots/11.png)

12. **Logs Operations File**:
   ![Logs Screenshot](screenshots/12logs.png)

13. **Vido of Result**:
    ![Showing Result Video](screenshots/usergroupmanager.asf)

## Summary

User-Group-Manager is a powerful and interactive Bash script designed to simplify user and group management on Linux-based systems. By leveraging a friendly whiptail menu interface, it allows administrators to easily add, delete, and modify users and groups while logging every action for transparency and auditing. This tool is ideal for system management enthusiasts and professionals looking to streamline administrative tasks.

## Author Information

- **Name:** Elham Hasan Gouda Tammam Kedwany
- **LinkedIn:** [Your LinkedIn URL](https://www.linkedin.com/in/elham-hasan-6b029433a)
- **GitHub:** [Your GitHub URL](https://github.com/elhamhassan90)
