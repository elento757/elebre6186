<!-- elebre6186 -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Elento Brent's Webpage">
    <meta name="keywords" content="Elento, webpage, Brent">
    <meta name="author" content="Elento Brent">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elento Brent's Webpage</title>
    <link href="styles.css" rel="stylesheet">
</head>

<body>

<header>
    <h1>Welcome to Elento's World</h1>
    <h2>COWBOYS NATION!!!</h2>

 <nav>
        <ul class="nav-menu">
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- Main Content Flexbox -->
<main class="main-content">

  <section id="about">
        <h2>About</h2>
        <p>This section provides information about the purpose of the webpage and the author.</p>
    </section>

<section id="projects">
        <h2>Projects</h2>

  <table>
            <caption>Sample Projects</caption>
     <colgroup>
                <col style="background-color: #f2f2f2;">
                <col>
                <col style="background-color: #f2f2f2;">
            </colgroup>

 <thead>
                <tr>
                    <th>Project Name</th>
                    <th>Description</th>
                    <th>Image</th>
                </tr>
            </thead>

   <tbody>
                <tr>
                    <td>Portfolio Website</td>
                    <td>A personal website showcasing my skills, projects, and contact information.</td>
                    <td>
                        <img src="placeholder.png" alt="Portfolio project image" width="100">
                    </td>
                </tr>
                <tr>
                    <td>Storefront Page</td>
                    <td>A sample online storefront built using HTML and CSS with Flexbox layout.</td>
                    <td>
                        <img src="placeholder.png" alt="Storefront project image" width="100">
                    </td>
                </tr>
            </tbody>

   <tfoot>
                <tr>
                    <td colspan="3">More projects coming soon!</td>
                </tr>
            </tfoot>
        </table>
    </section>

    <!-- Contact Section -->
<section id="contact">
        <h2>Contact</h2>

 <form class="contact-form">

 <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
            </div>

  <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
            </div>

   <div class="form-group">
                <label for="subject">Subject</label>
                <input type="text" id="subject" name="subject">
            </div>

 <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5"></textarea>
            </div>

<button type="submit">Send Message</button>

  </form>
    </section>

</main>

<footer>
    <p>&copy; 2025 Elento Brent's Webpage. All rights reserved.</p>
</footer>

</body>
</html>
