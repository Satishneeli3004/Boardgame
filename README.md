# BoardgameListingWebApp

## Description
## MainEnd2End Setup by owner>>https://medium.com/@gokulnath7876/automating-ci-cd-with-jenkins-and-kubernetes-a-devops-board-game-deployment-6599acc932bb#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6IjVhYWZmNDdjMjFkMDZlMjY2Y2NlMzk1YjIxNDVjN2M2ZDQ3MzBlYTUiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJhenAiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJhdWQiOiIyMTYyOTYwMzU4MzQtazFrNnFlMDYwczJ0cDJhMmphbTRsamRjbXMwMHN0dGcuYXBwcy5nb29nbGV1c2VyY29udGVudC5jb20iLCJzdWIiOiIxMDM3Njg5MzE5NjQ4ODYyODI1MjYiLCJlbWFpbCI6InNhdGlzaG5lZWxpMzAwNEBnbWFpbC5jb20iLCJlbWFpbF92ZXJpZmllZCI6dHJ1ZSwibmJmIjoxNzI3MzU5ODExLCJuYW1lIjoic2F0aXNoIG5lZWxpIiwicGljdHVyZSI6Imh0dHBzOi8vbGgzLmdvb2dsZXVzZXJjb250ZW50LmNvbS9hL0FDZzhvY0oyemJkdTRpRWM5YmZybkJVTERTOHZpNDlPUE1iQUlIZ0EwYWo3YVpuUjA0NEs1eFU9czk2LWMiLCJnaXZlbl9uYW1lIjoic2F0aXNoIiwiZmFtaWx5X25hbWUiOiJuZWVsaSIsImlhdCI6MTcyNzM2MDExMSwiZXhwIjoxNzI3MzYzNzExLCJqdGkiOiI1MjFlZDc5ZWZlNWM4ZDFiZTM4ZjNjNjRmMDNhNmNkMzY4YTBiNGViIn0.KQJKx9b7iN8mTTDIS-6scbcmd-abY4znsDa5w380PBZsHLzPV__OtVXn15Z4bez-jUbRWp95dmMw_udoYdXcK1pUcIfZe8YwGhrZYC2jjU3WXfR-uPCxaA336qKoOpAstFRd4772LLFwhib19vCnXxDc34uJvG5Vqc7M4SgN7jWaPiqM4vYkBdUI8e3WLKoNW_qyhH5dfBIrgHXV2Z0hAwBfuuU8CZsFK1DYVg0vXZ3UoU9QnO-IB1V2w3Kq62d2_xL9SvwhSR-iWH3Zjs1L31GogNLGl_i9BW-XPTA-pJVOQNghZgXaAH0dlDVc43LWZ9oYZU6h-RVnm-Doe5rnkw

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊
