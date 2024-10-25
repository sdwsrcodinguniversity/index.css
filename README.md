/* Universal Reset and Body Styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    color: #333;
    background-color: #f1f2ef;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0;
}

/* Header Styling */
header {
    width: 100%;
    background-color: #ccff00;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    color: #000;
}

.top-bar {
    display: flex;
    justify-content: space-between;
    padding: 0.5rem 1rem;
    background-color: #fff;
    color: #0e0e0e;
}

.social-login a, .contact-info span {
    color: #0e0e0e;
    text-decoration: none;
    margin-left: 1rem;
}

/* Navbar Styling */
.navbar ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 0;
    background: #ffffff;
}

.navbar li {
    margin: 0 1rem;
}

.navbar a {
    color: #000;
    text-decoration: none;
    font-size: 1rem;
}

.navbar a:hover {
    text-decoration: underline;
}

/* Main Content Area */
main {
    width: 80%;
    max-width: 1200px;
    padding: 2rem;
    text-align: center;
}

h2, h3, h4 {
    color: #000;
    margin: 1rem 0;
}

p {
    line-height: 1.6;
    margin: 1rem 0;
}

/* Sidebar and Main Content Area */
.side, .content {
    display: flex;
    padding: 20px;
    margin: 20px 0;
}

.side {
    flex: 1;
    background-color: #333;
    color: #fff;
    padding: 15px;
}

.side ul {
    list-style-type: none;
    padding: 0;
}

.side a {
    color: white;
    text-decoration: none;
    display: block;
    padding: 8px;
}

.side a:hover {
    background-color: #575757;
}

/* Footer Styling */
footer {
    width: 100%;
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
}

footer a {
    color: #4CAF50;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}

/* Responsive Adjustments */
@media (max-width: 768px) {
    .navbar ul, .content {
        flex-direction: column;
        align-items: center;
    }

    .navbar li {
        margin: 0.5rem 0;
    }

    .side, .content {
        width: 100%;
    }
}
