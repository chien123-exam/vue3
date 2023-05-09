Route Vue
- Init define routes/index.js
- Define a route
    const routes = [
   {
     path: '/',
     component: Home
   },

   {
    path: '/about',
    component: About
   },

   {
    path: '/product',
    component: Product
   }
]

- <router-link to="/about">About</router-link> 
- <router-view></router-view> // Load content (componet) of route
- route name :  <router-link :to="{name: 'about'}">About</router-link>