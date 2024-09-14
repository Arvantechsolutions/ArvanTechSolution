/* Global Styles */
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #0a1f44;
    color: white;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    padding: 20px;
    background-color: #051836;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 24px;
    font-style: italic;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-style: italic;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background-color: #052454;
    background-image: url('hero-bg.jpg');
    background-size: cover;
}

.hero-content {
    max-width: 600px;
}

.hero h1 {
    font-size: 48px;
    font-style: italic;
}

.hero p {
    font-size: 20px;
    margin: 20px 0;
}

.hero .btn {
    padding: 10px 20px;
    background-color: #1b64f9;
    color: white;
    border: none;
    font-size: 18px;
    cursor: pointer;
    text-decoration: none;
    border-radius: 5px;
}

.hero .btn:hover {
    background-color: #134bbd;
}

/* About Section */
.about {
    padding: 80px 20px;
    background-color: #0a1f44;
    text-align: center;
}

.about h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.about p {
    max-width: 800px;
    margin: 0 auto;
    font-size: 18px;
}

/* Services Section */
.services {
    padding: 80px 20px;
    background-color: #051836;
    text-align: center;
}

.services h2 {
    font-size: 36px;
    margin-bottom: 40px;
}

.service-cards {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.card {
    background-color: #0a2454;
    padding: 20px;
    margin: 10px;
    width: 30%;
    min-width: 250px;
    border-radius: 8px;
}

.card h3 {
    font-size: 24px;
    margin-bottom: 15px;
    font-style: italic;
}

.card p {
    font-size: 16px;
}

/* Team Section */
.team {
    padding: 80px 20px;
    background-color: #051836;
    text-align: center;
}

.team h2 {
    font-size: 36px;
    margin-bottom: 40px;
}

.team-members {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.member {
    background-color: #0a2454;
    padding: 20px;
    margin: 10px;
    width: 40%;
    min-width: 200px;
    border-radius: 8px;
}

.member h3 {
    font-size: 24px;
    font-style: italic;
}

/* Contact Section */
.contact {
    padding: 80px 20px;
    background-color: #0a1f44;
    text-align: center;
}

.contact h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

form {
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

form input, form textarea {
    padding: 10px;
    margin-bottom: 20px;
    background-color: #052454;
    color: white;
    border: none;
    border-radius: 5px;
}

form button {
    padding: 10px;
    background-color: #1b64f9;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 18px;
    border-radius: 5px;
}

form button:hover {
    background-color: #134bbd;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background-color: #051836;
}

footer p {
    font-size: 14px;
}

/* Responsive Design */
@media (max-width: 768px) {
    .service-cards, .team-members {
        flex-direction: column;
        align-items: center;
    }
}

