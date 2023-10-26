body, h1, h2, p, ul, li, form {
    margin: 0;
    padding: 0;
}

body {
    background-color: #f2f2f2;
    color: #333;
    font-family: Arial, sans-serif;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

nav {
    background-color: #333;
    color: #fff;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 10px;
}

nav li {
    margin: 0 15px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    background-color: #007acc;
    color: #fff;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background-color: #005eaa;
}

form label {
    display: block;
    margin-top: 10px;
    font-weight: bold;
}

form input[type="text"],
form input[type="email"],
form input[type="password"] {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

@media (max-width: 768px) {
    header {
        padding: 10px;
    }
    nav ul {
        flex-direction: column;
        align-items: center;
    }
    nav li {
        margin: 5px 0;
    }
}

