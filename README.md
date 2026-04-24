# Personal-Portfolio-Website
import React from "react";

function App() {
  return (
    <div style={styles.container}>
      
      {/* Navbar */}
      <nav style={styles.nav}>
        <h2>MyPortfolio</h2>
        <div>
          <a href="#about" style={styles.link}>About</a>
          <a href="#projects" style={styles.link}>Projects</a>
          <a href="#contact" style={styles.link}>Contact</a>
        </div>
      </nav>

      {/* Hero */}
      <section style={styles.hero}>
        <h1>Hi, I'm Sheron 👋</h1>
        <p>Frontend Developer | React Enthusiast</p>
      </section>

      {/* About */}
      <section id="about" style={styles.section}>
        <h2>About Me</h2>
        <p>
          I build modern web apps using React, HTML, CSS, and JavaScript.
        </p>
      </section>

      {/* Projects */}
      <section id="projects" style={styles.section}>
        <h2>Projects</h2>

        <div style={styles.card}>
          <h3>Ludo Game Portal 🎮</h3>
          <p>Built using MIT App Inventor.</p>
        </div>

        <div style={styles.card}>
          <h3>Login Page 🔐</h3>
          <p>Responsive login UI using React.</p>
        </div>
      </section>

      {/* Contact */}
      <section id="contact" style={styles.section}>
        <h2>Contact</h2>
        <p>Email: yourmail@gmail.com</p>
      </section>

      {/* Footer */}
      <footer style={styles.footer}>
        <p>© 2026 Sheron</p>
      </footer>

    </div>
  );
}

const styles = {
  container: {
    fontFamily: "Arial, sans-serif",
    margin: 0,
  },
  nav: {
    display: "flex",
    justifyContent: "space-between",
    padding: "20px",
    background: "#111",
    color: "#fff",
  },
  link: {
    margin: "0 10px",
    color: "#fff",
    textDecoration: "none",
  },
  hero: {
    textAlign: "center",
    padding: "100px 20px",
    background: "#f4f4f4",
  },
  section: {
    padding: "60px 20px",
    textAlign: "center",
  },
  card: {
    border: "1px solid #ddd",
    padding: "20px",
    margin: "20px auto",
    maxWidth: "300px",
    borderRadius: "10px",
  },
  footer: {
    textAlign: "center",
    padding: "20px",
    background: "#111",
    color: "#fff",
  },
};

export default App;
