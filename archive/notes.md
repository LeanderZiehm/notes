  /* Navbar styles */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 1.5rem;
      background: var(--card);
      border-bottom: 1px solid var(--border);
      border-radius: 12px;
      margin-bottom: 2rem;
      position: sticky;
      top: 0;
      z-index: 100;
    }

    .navbar a {
      margin-right: 1rem;
      color: var(--text);
      text-decoration: none;
      font-weight: 500;
    }

    .navbar a:hover {
      color: var(--accent);
    }

    .nav-logo {
      font-weight: 700;
      font-size: 1.2rem;
      color: var(--accent);
    }

    .nav-right a:last-child {
      margin-right: 0;
    }

    @media (max-width: 768px) {
      .navbar {
        flex-direction: column;
        align-items: flex-start;
      }
      .nav-right {
        display: flex;
        flex-wrap: wrap;
        gap: 0.5rem;
        margin-top: 0.5rem;
      }
    }









        <!-- Navigation Bar -->
    <nav class="navbar">
      <div class="nav-left">
        <a href="/" class="nav-logo">Leander Ziehm</a>
      </div>
      <div class="nav-right">
        <a href="/apis">APIs</a>
        <a href="/dotfiles">Dotfiles</a>
        <a href="https://blog.leanderziehm.com/">Blog</a>
        <a href="https://cv.leanderziehm.com/">CV</a>

   
        
        <!-- <a href="/sh">SH</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
        -->
      </div>
    </nav>
