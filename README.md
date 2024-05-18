# Joey's Password Manager Showcase

A Password Manager to locally store passwords in a safe way, created in Python with a MySQL database.

## Features

User registration and login, user password and salt hashing, service password hashing, MySQL database integration, live updating database when changing service name, username, password, or removing a service account. Right click copy password context menu, random password generator, service name or username search feature.

## Demonstrations

### Registration and Login Process

Implemented user registration using MySQL database integration. User passwords are securely hashed using the SHA-256 hashing algorithm along with a randomly generated salt to enhance security against attacks. The hashed password and salt are stored in the database for authentication during the login process.

![Registration and Login Process](https://imgur.com/aYFMpfQ.gif)  

### Accessing and Managing Passwords

Passwords are automatically hidden, and can be toggled via the "Show" button. The search filter allows querying the manager for services and usernames. Below the search filter you can submit new entries into the password manager. Entries can be removed using the delete button, which will also remove them from the database.

![Accessing and Managing Passwords](https://imgur.com/rCabGvg.gif)  

### Utilizing the Random Password Generator

The random password generator allows you to quickly generate a complex password between 4 and 20 characters long. The password generator allows you to include symbols, numbers, and uppercase letters in your generated password. You can also quickly copy the generated password to your clipboard.

![Utilizing the Random Password Generator](https://imgur.com/eONIG8I.gif)  

### Live Database Updating and Security Features

The password manager is integrated with MySQL database, and updates live with changes made within the GUI. Such as when a user makes an update to a service name, username, password, or when an entry is deleted by the user. 

![Live Database Updating and Security Features](https://imgur.com/JnkgqvT.gif)  