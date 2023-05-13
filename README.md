<!DOCTYPE html>
<html>
<head>
  <title>Yoarmes Manga</title>
  <link rel="stylesheet" href="styles.css"> <!-- External CSS file for styling -->
  <style>
    /* Style for the search bar */
    .search-form {
      display: flex;
    }
    
    .search-input {
      padding: 8px;
      border: none;
      border-radius: 4px;
      flex: 1;
      font-size: 16px;
    }
    
    .search-submit {
      padding: 8px 16px;
      background-color: #ff0000;
      color: #fff;
      border: none;
      border-radius: 4px;
      font-size: 16px;
      margin-left: 8px;
      cursor: pointer;
    }
    
    .search-submit:hover {
      background-color: #800000;
    }
    
    .logo {
      text-align: center;
      margin-top: 20px;
    }
    
    .logo img {
      max-width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="Screenshot_20230513_122024.jpg" alt="Yoarmes Manga Logo">
    </div>
    <nav>
      <form class="search-form">
        <input type="text" id="search" name="search" class="search-input" placeholder="Search...">
        <input type="submit" value="Submit" class="search-submit">
      </form>
    </nav>
  </header>
  
  <main>
    <!-- Content here -->
  </main>
  
  <footer>
    <p>&copy; 2023 Yoarmes Manga. All rights reserved.</p>
  </footer>
</body>
</html>
