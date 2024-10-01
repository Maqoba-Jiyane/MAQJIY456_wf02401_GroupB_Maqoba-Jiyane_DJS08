# Project Brief: React Router 

🎥 INSERT LOOM PRESENTATION LINK: [https://www.loom.com/share/63848dbbd5ed4ecb8593aab5d1ba5c1b?sid=59e47358-93d3-47a9-a6f5-0120de40611c]

After cloning the repo, run `npm install` to install the dependencies 

Are you ready to get stuck into some React Router? For this challenge, you are required to code along with the lecturer from this lesson on Scrimba V1 [VanLife Project Bootstrapping](https://v1.scrimba.com/learn/react/introduction-to-react-router-6-coafa4877a450245212825034) or on Scrimba V2 click the link here [VanLife Project Bootstrapping](https://v2.scrimba.com/advanced-react-c02h/~02d)

The starter code has all the CSS styling required for the project; you will just need to link the corresponding classes as you code along. Jump into the start code here: [GitHub Repository](https://github.com/CodeSpace-Academy/StudentNo_Classcode_Group_Name-Surname_DJS08/tree/main).

The focus for this project will be to understand routing and present your code. Along with your code, you will need to submit a recorded presentation talking through the presentation points included below.

## React Routing Presentation Talking Points

For your recorded presentation, you will be discussing key concepts related to React Router, an essential tool for building single-page applications. To illustrate your understanding, address the following three questions in your presentation. These questions are designed to test your knowledge of the content from the "Advanced React Routing" Van Life Project, including setup, functionality, and application of React Router.

### Question 1: Explain the Setup and Basic Configuration of React Router

**What is the purpose of using React Router in a React application?**
- React Router manages dynamic routing, enabling single-page applications to navigate without full page reloads, enhancing user experience.

**How do you set up React Router using BrowserRouter as shown in the lessons?**
- Wrap your application in `<BrowserRouter>` in the main entry file (e.g., `main.jsx`), allowing you to use routing components within your app.

**Describe the role of the `<Routes>` and `<Route>` components in defining the navigation structure.**
- `<Routes>` defines the routing area, and `<Route>` specifies individual routes, mapping paths to components to render when the path matches.

### Question 2: Application of Route Parameters and Nested Routes

**Explain what route parameters are and how they are used in React Router, including the use of `useParams()` to access these parameters.**
- Route parameters are dynamic segments in the URL (e.g., `/user/:id`). Use `useParams()` to access these parameters in the component rendered by the route.

**Discuss the concept of nested routes as introduced in the lessons. What are nested routes, and how do they benefit the structure of a React application?**
- Nested routes allow components to render child routes, reflecting hierarchical structure and improving code organization and readability.

**Provide an example, such as the configuration for nested routes in the VanLife project.**
- Example:
  ```jsx
  <Routes>
    <Route path="vans" element={<Vans />}>
      <Route path=":vanId" element={<VanDetail />} />
    </Route>
  </Routes>
  ```

### Question 3: Implementation of Navigation Controls and Dynamic Linking

**How does the `<Link>` component enhance navigation within a React application?**
- `<Link>` enables client-side navigation, updating the URL and rendering new components without a full page reload.

**Describe the use of `NavLink` for active styling. What makes `NavLink` different from the basic `Link` component?**
- `NavLink` applies an active class/style to the link when its route is active, allowing for dynamic styling based on the current route.

**Discuss the use of search parameters and the `useSearchParams` hook to dynamically filter content, as seen in the VanLife project challenges.**
- `useSearchParams` provides methods to read and update query strings in the URL, enabling dynamic filtering and state preservation in the URL.

Be prepared to provide code snippets and real-world application examples from your Van Life Project to support your explanations.

Make sure to submit your project to the DJS08 Project Tab on the LMS. Include a link to your Loom Presentation in your README.


