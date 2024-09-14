<h1 align="center">VegaVerse: Netflix Clone</h1>

<p>VegaVerse is an immersive video streaming platform that replicates the seamless experience of Netflix with a vast library of movies, series, and documentaries. Built using a state-of-the-art tech stack, StreamHub offers users a smooth and personalized viewing experience, complete with secure authentication, dynamic content delivery, and efficient video streaming. Scalable and intuitive, StreamHub allows users to discover and enjoy content across all devices effortlessly.</p>

<h2 id="features">Features and Tech Stack</h2>
<ul>
  <li>
    <h4 id="Authentication">Secure Authentication: Implemented JWT-based authentication with Bcrypt.js password hashing, ensuring robust user account protection and secure sessions.</h4>
  </li>
  <li>
    <h4 id="Responsive-UI">Responsive Design: Crafted a fully responsive UI using Tailwind CSS, providing a seamless viewing experience across all devices, from desktops to mobile phones.</h4>
  </li>
  <li>
    <h4 id="Content-Management">Comprehensive Content Management: Integrated APIs to fetch and display a wide selection of movies and TV shows. Users can search for actors and titles, watch trailers, and receive personalized content suggestions.</h4>
  </li>
  <li>
    <h4 id="User-Features">Enhanced User Experience: Enabled features such as adding/removing items from watchlists, viewing search history, and getting recommendations for similar content based on preferences.</h4>
  </li>
  <li>
    <h4 id="Core-Pages">Essential Platform Pages: Developed key pages including an engaging landing page, homepage, login/register page, user dashboard, individual movie/TV series pages, "New & Popular" section, and personalized "MyList" page.</h4>
  </li>
  <li>
    <h4 id="State-Management">Efficient State Management: Utilized Redux for streamlined state management, ensuring a smooth and consistent user experience throughout the application.</h4>
  </li>
  <li>
    <h4 id="Conditional-Rendering">Dynamic Content Rendering: Implemented conditional rendering to tailor content and features based on user interaction and authentication status, enhancing personalization.</h4>
  </li>
</ul>

<h2 id="tech-stack">Tech Stack</h2>

<ul>
  <li>
    <h4 id="frontend">Frontend: <strong>React</strong>, <strong>Redux</strong></h4>
  </li>
  <li>
    <h4 id="backend">Backend: <strong>Node.js</strong>, <strong>Express.js</strong></h4>
  </li>
  <li>
    <h4 id="authentication-1">Authentication: <strong>JWT (JSON Web Tokens)</strong></h4>
  </li>
  <li>
    <h4 id="database-1">Database: <strong>MongoDB</strong></h4>
  </li>
  <li>
    <h4 id="css">CSS: <strong>Tailwind CSS</strong></h4>
  </li>
</ul>

### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secre
TMDB_API_KEY=your_tmdb_api_key
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```
