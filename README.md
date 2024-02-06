
<body>

  <section>
    <h1>Overview</h1>
    <p>This project aims to create a comprehensive online gaming platform with a focus on playing Pong versus other players. The website is designed with security, functionality, and user experience in mind.</p>
  </section>

  <section>
    <h1>Technology Stack</h1>
    <ul>
      <li>Backend: NestJS</li>
      <li>Frontend: TypeScript framework of your choice</li>
      <li>Database: PostgreSQL</li>
      <li>Deployment: Docker with a single launch command: <code>docker-compose up --build</code></li>
    </ul>
  </section>

  <section>
    <h1>Development Guidelines</h1>
    <ul>
      <li>Use the latest stable versions of all libraries and frameworks.</li>
      <li>Ensure the website is a single-page application for smooth navigation.</li>
      <li>Compatibility with the latest stable version of Google Chrome and one additional web browser of your choice.</li>
      <li>No unhandled errors or warnings during website browsing.</li>
    </ul>
  </section>

  <section>
    <h1>Security Concerns</h1>
    <ul>
      <li>Passwords stored in the database must be hashed.</li>
      <li>Protection against SQL injections.</li>
      <li>Implement server-side validation for forms and user input.</li>
      <li>Utilize a strong password hashing algorithm.</li>
      <li>Store sensitive information in a local <code>.env</code> file, not in version control, to avoid security risks.</li>
    </ul>
  </section>

  <section>
    <h1>User Account Management</h1>
    <ul>
      <li>Login using the OAuth system of 42 intranet.</li>
      <li>Choose a unique display name and upload an avatar.</li>
      <li>Enable two-factor authentication (e.g., Google Authenticator or text message).</li>
      <li>Add other users as friends, view their status, and display stats on the user profile.</li>
      <li>Maintain a Match History for 1v1 games, ladder, and other useful information.</li>
    </ul>
  </section>

  <section>
    <h1>Chat Functionality</h1>
    <ul>
      <li>Create public, private, or password-protected chat channels.</li>
      <li>Send direct messages to other users.</li>
      <li>Block other users to avoid receiving messages.</li>
      <li>Channel owners/administrators can manage channel settings, including passwords and user permissions.</li>
      <li>Invite other users to play Pong through the chat interface.</li>
      <li>Access other players' profiles within the chat interface.</li>
    </ul>
  </section>

  <section>
    <h1>Pong Game Integration</h1>
    <ul>
      <li>Play live Pong games directly on the website.</li>
      <li>Implement a matchmaking system for automatic player pairing.</li>
      <li>Offer customization options such as power-ups or different maps.</li>
      <li>Ensure the game is responsive, considering network issues like disconnection or lag.</li>
    </ul>
  </section>

</body>

