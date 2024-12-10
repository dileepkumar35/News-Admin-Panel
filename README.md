# News-Admin-Panel

A web application showcasing a simple admin panel interface for a short news app.

## Install and Run

To install the required dependencies:  
```
cd admin-panel
npm install

```
For running a local development server
```
    cd admin-panel
    npm run dev
```

## Technologies Used

- **ReactJS**: Utilized for building the user interface, managing state, and integrating APIs.  
- **MUI (Material-UI)**: Provides pre-designed components, icons, and styling options to speed up development.  
- **React Router DOM**: Enables seamless client-side routing and navigation.  
- **D3.js**: Used for creating interactive and visually appealing graphs and charts.  

## Development Approach

The application leverages ReactJS APIs such as `useContext`, `createContext`, `useReducer`, and custom hooks for managing global state. The `useState` hook is employed for handling local state within components.  

Reusable components, including graphs and feed tables, are extensively utilized to ensure modularity and maintainability in the codebase.  

The `useEffect` hook is used within chart and graph components to handle efficient re-rendering whenever the application state changes.  

Client-side routing is implemented using the React Router DOM library, allowing for smooth navigation between different sections of the application.


