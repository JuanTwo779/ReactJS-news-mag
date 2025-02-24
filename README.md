# React Practice 1

- News magazine
- Display data from external API
- Bootstrap UI
- VITE server

### Vite
1. npm create vite@latest
2. npm run dev

### Notes
- racfe: Creates a React Arrow Function Component with ES7 module system
- bootstrap: insert link and script tag into index.html
- properties: can be variable or method e.g., useState
    - use {} to pass them in and use them in component
    - if method is passed in, use arrow function e.g., onClick={()=>setCategory("health")}
- useEffect update: add at end of code block i.e., useEffect(()=>{....},[category])