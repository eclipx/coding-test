<p align="center">
    <img  alg="Eclipx" src="http://eclipxgroup.com/wp-content/themes/reverie-master/img/template/eclipx-group-logo.png" />
</p>

# {'role': 'fullstack-web-dev'}

The purpose of this challenge is to evaluate your knowledge and skills in fullstack web development role at Eclipx.

# Goal

1. Create a new repo in any public repo you like (Github / Gitlab / Bitbucket), as long as you can share it with us.
2. Create SPA with Vue.JS (preferred) or any of your choice for a simple map direction page
   - Utilize modern css technologies as much as possible
3. Create an API endpoint in Node.js

# Criteria

1. Create SPA Progressive Web Application:

   - Simple login screen via freeTier of Auth0/Okta/Firebase
   - Authenticated page with:
     - Input box integrated with Google Places API
     - Upon list selection,
       - Show google map with directions from current
         location to the selected location

2. Create a simple API call based on role of the user

   - Create admin user and read only user in the firebase auth
   - Based on the user role (admin)
     - response 200 for path /api/admin_only
     - response 401 for path /api/admin_only for readonly user

# Acceptance Criteria

1. App is easy to install and run locally
2. Code quality
   - Your code must be clean, well-structured, commented and easy to understand

# Bonus Point

- UX - your app is easy to use and working well
- UI - your app looking clean and great
- API - your app is functioning as per the requirement
- CI pipeline, i.e: eslint, prettier
- Deployed in any free JAM stack i.e: netlify / firebase
- Unit test
- Webpack / tree shaking
- Readme on code design, 3rd party library and the use in your app

# Rules

It's all about the the result, but here are few rules:

- Feel free to use any 3rd party library you like
- Elaborate your selection of 3rd party tools/libraries and coding principle you apply in your code
- Your code must be able to be compiled by us to review the app
