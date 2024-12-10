<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Empowering Birth Choices</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Empowering Birth Choices</h1>
        <p>Your guide to informed, compassionate birthing options</p>
    </header>
    <nav>
        <a href="#homebirth">Homebirth Benefits</a>
        <a href="#csections">C-Section Facts</a>
        <a href="#doulas">Doula Support</a>
        <a href="#resources">Resources</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="homebirth">
        <h2>Benefits of Homebirth</h2>
        <p>Discover the advantages of planned homebirths: lower intervention rates, cost savings, and empowering environments for mothers and families.</p>
    </section>
    <section id="csections">
        <h2>C-Section Statistics</h2>
        <p>Learn about the rising rates of C-sections, when they're necessary, and how to prevent unnecessary surgeries through advocacy and support.</p>
    </section>
    <section id="doulas">
        <h2>Doula Support</h2>
        <p>Understand how doulas provide continuous emotional and physical support, reducing stress and improving outcomes for mothers and families.</p>
    </section>
    <section id="resources">
        <h2>Resources</h2>
        <ul>
            <li><a href="https://www.ncbi.nlm.nih.gov/pubmed/" target="_blank">Studies on Homebirth Safety</a></li>
            <li><a href="https://www.who.int/news-room/fact-sheets/detail/caesarean-section-rates" target="_blank">WHO Data on C-Sections</a></li>
            <li><a href="https://evidencebasedbirth.com" target="_blank">Evidence-Based Birth Resources</a></li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Empowering Birth Choices</p>
    </footer>
    <script>
        // FAQ Toggle
        document.querySelectorAll('.faq h3').forEach(faq => {
            faq.addEventListener('click', () => {
                const content = faq.nextElementSibling;
                content.style.display = content.style.display === 'block' ? 'none' : 'block';
            });
        });
    </script>
</body>
</html>
