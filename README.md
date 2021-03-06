Source : https://www.digitalocean.com/community/tutorials/how-to-add-login-authentication-to-react-applications

Many web applications are a mix of public and private pages. Public pages are available to anyone, while a private page requires a user login. You can use authentication to manage which users have access to which pages. Your React application will need to handle situations where a user tries to access a private page before they are logged in, and you will need to save the login information once they have successfully authenticated.

In this tutorial, you’ll create a React application using a token-based authentication system. You’ll create a mock API that will return a user token, build a login page that will fetch the token, and check for authentication without rerouting a user. If a user is not authenticated, you’ll provide an opportunity for them to log in and then allow them to continue without navigating to a dedicated login page. As you build the application, you’ll explore different methods for storing tokens and will learn the security and experience trade-offs for each approach. This tutorial will focus on storing tokens in localStorage and sessionStorage.

By the end of this tutorial, you’ll be able to add authentication to a React application and integrate the login and token storage strategies into a complete user workflow.

### Step 1 - Building a Login Page
### Step 2 - Creating a Token API
### Step 3 - Storing a User Token with sessionStorage and localStorage