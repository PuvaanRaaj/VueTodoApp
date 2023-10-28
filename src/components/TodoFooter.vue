<template>
    <footer id="footer">
      <p>&copy; 2023 Puvaan Raaj. All rights reserved.</p>
      <div class="social-icons">
        <a href="https://github.com/PuvaanRaaj" target="_blank" class="social-link">
          <i class="fab fa-github" style="color: black;"></i>
        </a>
        <a href="https://www.linkedin.com/in/puvaan-raaj/" target="_blank" class="social-link">
          <i class="fab fa-linkedin" style="color: black;"></i>
        </a>
      </div>
    </footer>
  </template>
  
  <style lang="scss" scoped>
  #footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    background-color: #f1f1f1;
    padding: 16px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-align: center; /* Center the text horizontally */
  
    .social-icons {
      display: flex;
      align-items: center;
      justify-content: center; /* Center the social icons horizontally */
  
      .social-link {
        text-decoration: none;
        color: inherit;
        margin: 0 10px;
      }
    }
  }
  </style>
  