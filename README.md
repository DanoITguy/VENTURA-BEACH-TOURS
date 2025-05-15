The React route diagram of this project is a roadmap of the various pages and how they are all tied together. 
Specifically, the Home Page, the About Page, and the Products Page are properly setup, then the routes are configured
in the App.js file which is the anchor and foundation of our React application, as the website grows and evolves.

The code that we imported Routes and Route components from react-router-dom and then used them to declare the routes we want. 
All Routes are wrapped in the Routes tag, and these Routes have two major properties:

1) path: This identifies the path we want users to take to reach the set component. When we set the path to /about, for example, 
when the user adds /about to the URL link, it navigates to that page.

2) element: This contains the component that we want the set path to load. This is simple to understand, but remember to import 
any components we are using here, or else an error will occur.

Now create a standard Navigation bar component that can be used to navigate inside our application, as shown above.
Lastly, I will cover Lazy loading is a technique in which components that are not required on the home page are not loaded 
until a user navigates to that page, allowing our application to load faster than having to wait for the entire app to load 
at once. This contributes to improved performance, which leads to a positive user experience.

SUMMARY
1) I found that to implement lazy loading, go to App.js and wrap my routes with the Suspense component, along with a fallback 
props that are rendered on the screen until the component loads. Please note that is important for you to know that the 
fallback props can hold a component. I learned about routing and how to implement it in my React application. The React router 
is what allows my project to perform single-page routing without reloading the application.

