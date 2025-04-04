A personal portfolio website built using HTML, CSS, and JavaScript to showcase my skills and projects.

Prerequisites
Before you begin, ensure you have met the following requirements:

Basic understanding of HTML, CSS, and JavaScript.

Bootstrap 5 is used for styling. You can include it in your project as shown below:

html
Copy
Edit
<!-- Bootstrap 5 CSS CDN Link -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" />
<!-- Bootstrap JavaScript CDN Link -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
JQuery is included for some interactivity:

html
Copy
Edit
<!-- jQuery CDN Link -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
Bootstrap Icons are used for UI elements:

html
Copy
Edit
<!-- Bootstrap Icons CDN Link -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" />
AOS Animation Library Installation
To add animations to the page, I used the AOS (Animate On Scroll) library. Here’s how to integrate it:

Add Styles in the <head>:

html
Copy
Edit
<link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
Add the Script just before the </body> tag and initialize AOS:

html
Copy
Edit
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>
How to Use AOS?
Initialize the AOS library:

javascript
Copy
Edit
AOS.init({
  duration: 1000,  // Animation duration
  offset: 50,      // Trigger point of animation
});
Set animation using the data-aos attribute:

html
Copy
Edit
<div data-aos="fade-in"></div>
For more guidance, you can check the AOS Documentation.

Features
Sticky, responsive navigation bar

Hero section

Skills & expertise section with progress bars

Working portfolio section

Contact form section

Footer section

Fully responsive for all devices

Font Family
I’ve used Google Fonts - Josefin Sans for the text:

html
Copy
Edit
<!-- Google Fonts Link -->
<link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
Run Locally
To run the Portfolio locally, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/carolinekibaara/portfoliowebsite.git
Navigate into the project folder:

bash
Copy
Edit
cd portfoliowebsite
Open index.html in your browser.





