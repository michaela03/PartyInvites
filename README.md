# 🎉 Party Invitations Management - ASP.NET Core MVC 💌

This is the README file for the Party Invitations Management project implemented using ASP.NET Core MVC. The purpose of this project is to create a web application that handles party invitations and allows users to indicate whether they will attend the party or not. If the status is set to attending, the application will display a list of other guests attending the party.

## Features 🌟

The Party Invitations Management application will have the following features:

1. **Invitation Creation**: Users can create party invitations by providing details such as the event name, date, time, and location.

2. **Guest List Management**: Users can add and remove guests from the invitation's guest list.

3. **RSVP**: Guests can indicate whether they will attend the party or not by updating their RSVP status.

4. **Guest List Display**: If a guest indicates that they are attending the party, the application will display a list of other guests who have also confirmed their attendance.

5. **Authentication and Authorization**: The application will have user authentication and authorization to ensure that only authorized users can create invitations and manage guest lists.

## Technologies Used 💻

The Party Invitations Management application is built using the following technologies:

- Framework: ASP.NET Core MVC
- Programming Language: C#
- Database: Entity Framework Core with SQL Server
- Front-end: HTML, CSS, JavaScript (with Razor syntax)
- Authentication and Authorization: ASP.NET Core Identity
- Version Control: Git, GitHub

## Getting Started 🚀

To get started with the project, follow these steps:

1. Clone the repository:

2. Set up the database:

- Open the project in Visual Studio or your preferred IDE.
- Modify the connection string in the `appsettings.json` file to point to your SQL Server instance.
- Open the Package Manager Console and run the following commands to create and apply the database migrations:

  ```
  Update-Database
  ```

3. Build and run the application.

4. Access the application in your browser at `http://localhost:5000`.

## Contributing 👥

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request.

## License 📄

This project is licensed under the MIT License. See the `LICENSE` file for more information.


