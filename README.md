# CBS Tech & Home Solutions Ltd Website

This is a fully functional website for CBS Tech & Home Solutions Ltd, featuring pages for services, a blog, a contact form, and an interactive homepage with a slider.

## Features
- **Homepage Slider** (JavaScript-based)
- **Service Pages** (Swimming Pool, Water Treatment, Water Fountains, General Contracting)
- **Blog Page**
- **Contact Form with PHP Processing**
- **SEO Optimized**
- **Responsive Design**
- **GitHub Usability**

## Project Structure
```
/ (Root)
│── index.html           # Landing page with slider
│── services/
│   │── swimming-pool.html
│   │── water-treatment.html
│   │── water-fountains.html
│   │── general-contracting.html
│── blog.html            # Blog page
│── contact.html         # Contact page
│── form.html            # Quote request page
│── submit_form.php      # PHP form handler
│── style.css            # CSS for styling
│── script.js            # JavaScript for interactivity
│── images/              # Image assets
│── README.md            # Project documentation
```

## Implementation Instructions

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/cbs-tech-home-solutions.git
cd cbs-tech-home-solutions
```

### 2. Setup a Local Server (for PHP processing)
You need a local web server such as XAMPP, WAMP, or MAMP to run PHP scripts.

- Install XAMPP/WAMP/MAMP
- Place the project folder inside the `htdocs` (for XAMPP) or `www` (for WAMP)
- Start Apache and MySQL services

### 3. Update `submit_form.php`
Open `submit_form.php` and update the `$to` email address:
```php
$to = "your-email@example.com"; // Replace with your actual email
```

### 4. Run the Website Locally
- Open your browser
- Go to `http://localhost/cbs-tech-home-solutions`

### 5. Deploying to GitHub Pages (Static Content Only)
1. Commit and push the project to GitHub
2. Go to **Settings > Pages** in the GitHub repository
3. Set the branch to `main` and directory to `/ (root)`
4. Click **Save**

For full functionality (PHP forms), host on a web server like:
- **cPanel Hosting** (e.g., Bluehost, SiteGround)
- **Cloud Hosting** (e.g., DigitalOcean, AWS, Heroku)

### 6. Access the Live Website
- If hosted via GitHub Pages: `https://your-username.github.io/cbs-tech-home-solutions/`
- If hosted on a server: `https://yourdomain.com`

## Contact
For any inquiries, visit [CBS Tech & Home Solutions Ltd](mailto:info@cbsths.com).
