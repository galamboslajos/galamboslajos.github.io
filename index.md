---
layout: default
---

<nav>
  <ul style="list-style-type: none; display: flex; justify-content: center; padding: 10px; background-color: #f4f4f4;">
    <li style="margin: 0 15px;"><a href="#about" onclick="showSection('about')">About</a></li>
    <li style="margin: 0 15px;"><a href="#investment-management" onclick="showSection('investment-management')">Investment Management</a></li>
    <li style="margin: 0 15px;"><a href="#forest-escapes" onclick="showSection('forest-escapes')">Forest Escapes</a></li>
    <li style="margin: 0 15px;"><a href="#blog" onclick="showSection('blog')">Blog</a></li>
  </ul>
</nav>

<div id="about" class="section">
  <h2>ABOUT</h2>
  <img src="./IMG_3785.HEIC" alt="Profile Picture" style="width:150px; border-radius:50%; display:block; margin:auto;">
  <p>Hello! I'm Lajos Galambos, an investment manager specializing in wealth management, portfolio analysis, and sustainable investment projects. I have extensive experience in financial markets and currently oversee diverse asset classes, including equities, real estate, and eco-tourism ventures.</p>

  - **LinkedIn:** [Lajos Galambos](https://www.linkedin.com/in/lajosgalambos)
  - **GitHub:** [galamboslajos](https://github.com/galamboslajos)
  - **Email:** [info@galamboscapital.com](mailto:info@galamboscapital.com)

  [Download My CV](./Lajos_Galambos_CV.pdf)
</div>

<div id="investment-management" class="section" style="display:none;">
  <h2>Investment Management</h2>
  <p>I actively manage investment portfolios focusing on long-term wealth growth and risk-adjusted returns. Below is a recent performance chart of my portfolio:</p>
  <img src="./portfolio_cumulative_returns.png" alt="Portfolio Performance" style="width:100%;">
</div>

<div id="forest-escapes" class="section" style="display:none;">
  <h2>Forest Escapes - Eco Tourism Project</h2>
  <p>One of my latest projects is <strong>Forest Escapes</strong>, an eco-tourism initiative aimed at sustainable and luxurious getaways in nature.</p>
  <img src="./Forest1.png" alt="Forest Escapes" style="width:100%;">
</div>

<div id="blog" class="section" style="display:none;">
  <h2>Blog</h2>
  <p>Latest Posts _(New posts will be added on top)_</p>
  <strong>Post Title 1</strong> *(March 5, 2025)*  
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla quis lorem ut libero malesuada feugiat.</p>

  <strong>Post Title 2</strong> *(March 3, 2025)*  
  <p>Sed porttitor lectus nibh. Nulla quis lorem ut libero malesuada feugiat.</p>
</div>

<script>
function showSection(sectionId) {
  document.querySelectorAll('.section').forEach(section => section.style.display = 'none');
  document.getElementById(sectionId).style.display = 'block';
}
</script>
