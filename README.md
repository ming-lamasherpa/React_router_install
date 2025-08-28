# ⚛️ React Router Setup Guide

## 1️⃣ Install
```bash
npm install react-router-dom
# or
yarn add react-router-dom

2️⃣ Import in App.jsx
import { BrowserRouter as Router, Routes, Route, Link } from "react-router-dom";
import Home from "./Home";
import About from "./About";

function App() {
  return (
    <Router>
      <nav>
        <Link to="/">Home</Link> | <Link to="/about">About</Link>
      </nav>
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/about" element={<About />} />
      </Routes>
    </Router>
  );
}
export default App;


3️⃣ Use <Link> Instead of <a>
<Link to="/about">Go to About</Link>

4️⃣ Check Version (Optional)
npm list react-router-dom
