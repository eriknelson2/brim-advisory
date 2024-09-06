
<style>
    /* Import the fonts */
    @import url('https://fonts.googleapis.com/css2?family=Lexend:wght@600&family=Playfair+Display:wght@500&family=Spectral:wght@500&display=swap');

    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem 2rem;
        background-color: #D9D7D7; /* Light gray background */
        box-shadow: 0 2px 4px #646E8C; /* Subtle shadow for depth */
        position: sticky;
        top: 0;
        z-index: 1000; /* Ensures it stays on top */
    }

    .logo {
        max-height: 70px; /* Adjust this depending on your logo size */
    }

    .brand-text {
        font-family: 'Lexend', sans-serif; /* Apply Lexend to brand text */
        font-size: 2rem;
        font-weight: 600; /* Semi-bold for titles */
        color: #344373; /* Dark color for contrast */
    }

    .content-container {
        padding: 1rem; /* Adds spacing around the content */
        width: 100%; /* Ensure the container takes up full width */
        font-family: 'Spectral', serif; /* Apply Spectral to body text */
        font-weight: 500; /* Medium weight for body text */
    }

    .about-section {
        margin-bottom: 2rem; /* Adds space between sections */
        padding: 1rem;
        border-radius: 0.5rem;
        color: #D9D7D7; /* Ensure text is readable on dark background */
        width: 100%; /* Ensure each section takes up full width */
        box-sizing: border-box; /* Include padding in the width */
    }

    .about-header, .title, .footer-title {
        font-family: 'Lexend', sans-serif; /* Apply Lexend to headers */
        font-size: 2rem; /* Unified size for headers */
        font-weight: 600; /* Semi-bold for titles */
        margin-bottom: 1rem;
        color: #D9D7D7; /* Text color for headers */
        text-align: center; /* Centers the header */
    }

    .about-content {
        display: flex; /* Flexbox for image and text alignment */
        align-items: flex-start; /* Align items at the top */
    }

    .about-image {
        max-width: 150px; /* Set a maximum width for the image */
        margin-right: 1.5rem; /* Adds space between the image and text */
        border-radius: 8px; /* Optional: Add some rounding to the image */
    }

    .about-text {
        flex: 1; /* Allow the text to take up the remaining space */
        line-height: 1.6; /* Improves readability */
        font-family: 'Spectral', serif; /* Apply Spectral to text */
        font-weight: 500; /* Medium weight for text */
    }

    .about-text p + p {
        margin-top: 1rem; /* Adds space between the paragraphs */
    }

    /* Grid layout for bullet points */
    .bullet-list-container {
        display: flex;
        justify-content: center; /* Centers the grid container */
    }

    .bullet-list {
        display: grid;
        grid-template-columns: repeat(2, minmax(150px, 1fr)); /* Two equal-width columns */
        column-gap: 2rem; /* Space between columns */
        row-gap: 1rem; /* Space between rows */
        list-style-type: disc;
        padding-left: 0; /* Remove default padding */
        line-height: 1.8;
    }

    .bullet-list li {
        font-size: 1.1rem; /* Increases font size for emphasis */
        font-family: 'Spectral', serif; /* Apply Spectral to list items */
        font-weight: 500; /* Medium weight for list items */
    }

    .footer {
        background-color: #101418; /* Dark blue background */
        color: #D9D7D7; /* Light gray text for contrast */
        padding: 1rem; /* Reduced padding for a more compact footer */
        display: flex;
        justify-content: center; /* Center the content */
        align-items: center;
    }

    .footer-title {
        font-family: 'Lexend', sans-serif; /* Apply Lexend to footer title */
        font-size: 1.5rem;
        margin-bottom: 0.5rem;
        color: #D9D7D7;
        text-align: center; /* Center the title above the content */
        width: 100%; /* Ensures the title spans the full width of the footer */
    }

    .footer-content {
        display: flex;
        gap: 2rem; /* Space between each item */
        justify-content: center;
        align-items: center;
        flex-wrap: wrap; /* Allows wrapping on smaller screens */
    }

    .footer p {
        margin: 0;
        white-space: nowrap; /* Prevents line breaks within the text */
        font-family: 'Spectral', serif; /* Apply Spectral to footer text */
        font-weight: 500; /* Medium weight for footer text */
    }

    /* Additional styling */
    .justify-center {
        display: flex;
        justify-content: center;
    }

    .items-center {
        align-items: center;
    }

    .h-screen {
        height: 100vh;
    }

    .dark-blue {
        background-color: #344373;
    }

    .gray {
        background-color: #D9D7D7;
    }

    .medium-blue {
        background-color: #646E8C;
    }

    .text-primary-content {
        color: white;
    }

    .text-accent-content {
        color: lightblue;
    }

    .text-secondary-content {
        color: lightgray;
    }

    .grid {
        display: grid;
    }

    .place-content-center {
        place-content: center;
    }

    .rounded {
        border-radius: 0.5rem;
    }
</style>


<header>
    <div class="brand-text">BRIM ADVISORY</div>
    <img src="/brim-advisory-removebg-preview.png" alt="Brim Advisory Logo" class="logo" />
</header>

<div class="content-container">
    <!-- About Section -->
    <div class="about-section">
        <h2 class="about-header">About</h2>
        <div class="about-content">
            <img src="/dad.jpeg" alt="Bruce McGoogan" class="about-image" />
            <div class="about-text">
                <p>Bruce McGoogan is a seasoned leader with more than 25 years of global experience in the food
                and feed industries. He specializes in bridging technology and business, leading R&amp;D strategy,
                innovation, and business development. Bruce&#39;s career is marked by his ability to forge strong
                external partnerships and collaborate effectively across internal functions, driving significant
                business potential and growth from technology. His educational background includes a PhD in
                Nutrition from Texas A&amp;M University, an MS in Aquaculture from Louisiana State University, and
                a BS in Biology from University of North Carolina–Wilmington.</p>
                
                <p>In his recent role as VP Global Business Development at Cargill, Bruce led enterprise business
                strategy and investment projects ranging from a few million dollars to over $1.5 billion. His
                tenure at Cargill also includes roles such as Strategy and Innovation Director, Strategy and
                Business Development Lead in Europe, and Food Technology Leader in North America and
                Asia-Pacific. His contributions have significantly impacted strategic marketing, innovation
                portfolios, and R&amp;D leadership, demonstrating his expertise in driving technological
                advancements and business success.</p>
            </div>
        </div>
    </div>

    <!-- Consulting Focus Areas Section -->
    <div class="about-section">
        <h2 class="about-header">Consulting Focus Areas</h2>
        <div class="bullet-list-container">
            <ul class="bullet-list">
                <li>Business strategy</li>
                <li>Market/competitor intelligence and opportunity evaluation</li>
                <li>Innovation strategy</li>
                <li>Innovation portfolio development</li>
                <li>Commercialization planning</li>
                <li>Business development</li>
            </ul>
        </div>
    </div>
</div>

<!-- <footer class="footer bg-neutral text-neutral-content p-10">
    <nav>
        <h6 class="footer-title">Contact Information</h6>
        <p>Address: Fernandina Beach, Florida, USA</p>
        <p>Phone: (952)-338-7597</p>
        <p>Email: mcgoogs1@gmail.com</p>
    </nav>
</footer> -->
<footer class="footer">
    <nav>
        <h6 class="footer-title">Contact Information</h6>
        <div class="footer-content">
            <p>Fernandina Beach, Florida, USA</p>
            <p>Phone: (952)-338-7597</p>
            <p>Email: mcgoogs1@gmail.com</p>
        </div>
    </nav>
</footer>