<!DOCTYPE html><html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Selvalakshmi | Portfolio</title><!-- Favicon & External CSS (served statically) -->
<link rel="icon" href="favicon.ico" type="image/x-icon" />
<link rel="stylesheet" href="css/p_main1.css" />

<!-- Boxicons -->
<link
  href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
  rel="stylesheet"
/>

<!-- Page-specific styles (keep or move to css/p_main1.css) -->
<style>
  * {
    padding: 0;
    margin: 0;
    font-family: sans-serif;
    box-sizing: border-box;
    scroll-behavior: smooth;
  }

  :root {
    --bg-color: #051b29;
    --second-bg-color: #112e42;
    --text-color: #ededed;
    --main-color: #00abf0;
    --third-bg-color: #051b24;
  }

  body {
    background: var(--bg-color);
    color: var(--text-color);
  }

  /* ---------- Header ---------- */
  .header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 20px 10%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 100;
    background: var(--bg-color);
  }

  .logo {
    font-size: 25px;
    color: var(--text-color);
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s ease;
  }
  .logo:hover {
    color: #9370db;
  }

  .navbar {
    display: flex;
    align-items: center;
  }
  .navbar a {
    font-size: 15px;
    color: var(--text-color);
    text-decoration: none;
    font-weight: 500;
    margin-left: 35px;
    transition: color 0.3s;
  }
  .navbar a:hover {
    color: var(--main-color);
  }

  #menu-icon {
    color: var(--text-color);
    font-size: 2rem;
    cursor: pointer;
    display: none;
  }

  @media (max-width: 768px) {
    .navbar {
      display: none;
      flex-direction: column;
      position: absolute;
      top: 70px;
      right: 0;
      width: 100%;
      background: var(--bg-color);
      padding: 20px 0;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .navbar.active {
      display: flex;
    }
    .navbar a {
      margin: 10px 0;
      font-size: 18px;
    }
    #menu-icon {
      display: block;
    }
    .header {
      padding: 20px 5%;
    }
  }

  section {
    min-height: 100vh;
    padding: 5rem 9% 2rem;
  }

  /* ---------- Home ---------- */
  .home {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 10%;
    background: linear-gradient(
        rgba(0, 0, 255, 0.1),
        rgba(100, 200, 255, 0.1)
      ),
      url("images/image2.jpeg") no-repeat center/cover;
  }

  .home-content {
    max-width: 600px;
    display: flex;
    flex-direction: column;
    margin-left: 5rem;
  }
  .home-content h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
  }
  .home-content p {
    font-size: 1rem;
    margin-bottom: 2rem;
  }

  .btn {
    display: inline-flex;
    justify-content: center;

