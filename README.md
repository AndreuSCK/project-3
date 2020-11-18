# Project 3 App
<br>

## Description
-   This app will let users create their own canvas and organize it as they want.
-   Add headers, lists, pictures, text etc in a customized canvas ready to be used in your daily projects.
-   This easy-to-use and straightforward app will be your favourite once you try it!

## MVP
The MVP will cover the following:

-   Homepage
-   Working Canvas app
-   Profile
-   Signup
-   Login

## User Stories

-  **404:** As an anon/user I can see a 404 page if I try to reach a page that does not exist so that I know it's my fault
-  **Signup:** As an anon I can sign up in the platform so that I can start playing into competition
-  **Login:** As a user I can login to the platform so that I can play competitions
-  **Logout:** As a user I can logout from the platform so no one else can use it

## Backlog
-  Add online features to support multiple users.
-  Multiple language support.
-  Drag and drop the user options.

<br>


# Client / Frontend

## React Router Routes (React App)
| Path                      | Component            | Permissions                 | Behavior                                                     |
| ------------------------- | -------------------- | --------------------------- | ------------------------------------------------------------ |
| `/`                       | SplashPage           | public `<Route>`            | Home page                                                    |
| `/signup`                 | SignupPage           | anon only  `<AnonRoute>`    | Signup form, link to login, navigate to homepage after signup |
| `/login`                  | LoginPage            | anon only `<AnonRoute>`     | Login form, link to signup, navigate to homepage after login |
| `/tournaments`            | TournamentListPage   | user only `<PrivateRoute>`  | Shows all tournaments in a list                              |
| `/tournaments/add`        | TournamentListPage   | user only `<PrivateRoute>`  | Edits a tournament                                           |
| `/tournaments/:id`        | TournamentDetailPage | user only `<PrivateRoute>`  | Details of a tournament to edit                              |
| `/tournament/:id`         | n/a                  | user only `<PrivateRoute>`  | Delete tournament                                            |
| `/tournament/players`     | PlayersListPage      | user only  `<PrivateRoute>` | List of players of a tournament                              |
| `/tournament/players/add` | PlayersListPage      | user only `<PrivateRoute>`  | Add a player to the tournament                               |
| `/tournament/players/:id` | PlayersDetailPage    | user only `<PrivateRoute>`  | Edit player for tournament                                   |
| `/tournament/players/:id` | PlayersListPage      | user only  `<PrivateRoute>` | Delete player from tournament                                |
| `/tournament/tableview`   | TableView            | user only  `<PrivateRoute>` | Games view and brackets                                      |
| `/tournament/ranks`       | RanksPage            | user only `<PrivateRoute>`  | Ranks list                                                   |
| `/tournament/game`        | GameDetailPage       | user only `<PrivateRoute>`  | Game details                                                 |






## Wireframes
- https://i.imgur.com/vnt62ki.png

## Links
- **Trello**
- https://trello.com/b/ZGO8q74U/proyecto-3

- **Git**

- [Gihub Repo URL](https://github.com/AndreuSCK/project-3/)
