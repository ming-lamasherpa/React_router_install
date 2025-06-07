# React_router_install
Step-by-Step Instructions:
1. Install React Router DOM
=> Run this command in your project folder:
   npm install react-router-dom

 Or if you use Yarn:
 yarn add react-router-dom

2. Import Required Components
=> Open your App.jsx (or wherever you're setting up routes) and import:
import { BrowserRouter as Router, Routes, Route } from 'react-router-dom';

3. Wrap Your App in <Router>
=> Make sure your root component is wrapped in <Router>:
<Router>
  <Routes>
    <Route path="/" element={<Home />} />
    <Route path="/about" element={<About />} />
    {/* more routes */}
  </Routes>
</Router>

4.Use <Link> Instead of <a>
=> To navigate without page reload, use Link from react-router-dom:
import { Link } from 'react-router-dom';
<Link to="/about">About</Link>

✅ Optional: Check Version
To confirm it's installed:
=> npm list react-router-dom
You should see something like:
=> react-router-dom@6.22.3





