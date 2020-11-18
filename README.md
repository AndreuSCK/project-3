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
| `/canvas/:id`             | UserCanvas           | user only `<PrivateRoute>`  | Canvas of the user.                                           |
| `/profile`                 | UserProfile         | user only `<PrivateRoute>`  | User profile                                            |
| `/gallery`                 | CanvasGallery       | user only `<PrivateRoute>`  | Gallery of the canvas uploaded by the community       |






## Wireframes
- https://i.imgur.com/vnt62ki.png

## Links
- **Trello**
- https://trello.com/b/ZGO8q74U/proyecto-3

- **Git**

- [Gihub Repo URL](https://github.com/AndreuSCK/project-3/)
