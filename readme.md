<p align="center">
    <img  alg="Eclipx" src="http://eclipxgroup.com/wp-content/themes/reverie-master/img/template/eclipx-group-logo.png" />
</p>

# {'role': 'fullstack-web-dev'}
The purpose of this challenge is to evaluate your knowledge and skills in fullstack web development role at Eclipx.

# Goal
1. Create a new repo in any public repo you like (Github/Gitlab/Bitbucket), as long as you can share it with us.
2. Create NodeJS API to handle few checkout calculation logic
3. Create SPA with (React.js / Vue.js) for a simple checkout page
    - Utilize flexbox as much as possible

# Criteria
1. Create API endpoint to return product list, refer to [product list](data/products.json)
2. Create **extendable** API discount logic with the following initials:
    - A customer who has cart total over $1000, gets a discount of 10% on the whole order.
    - For category "2", when you buy five, you get sixth for free
    - For category "1", you will get 20% discount on cheapest product
3. SPA checkout application, with the following features:
    - Add line item button
    - Product selection
    - Quantity input
    - Total $ amount per line item
    - Cart Total 

# Acceptance Criteria
1. SPA fetching product data via API
2. App is easy to install and run locally
3. Code Quality
    - Your code must be clean, well-structured, commented and easy to understand

# Bonus Point
- UX - your app is easy to use and working well
- UI - your app looking clean and great
- CI pipeline, i.e: eslint, prettier
- Deployed somewhere 
- Unit tested
- Webpack / tree shaking
- Readme on code design, 3rd party library and the use in your app

# Rules
It's all about the the result, but here are few rules:
- Feel free to use any 3rd party library you like
- It's encouraged to look for any inspirations, **BUT** if you are taking the lazy route of copy and pasting from Internet, We'll know!