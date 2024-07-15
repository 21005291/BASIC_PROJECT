# BASIC_PROJECT

AIM:
Design a Website like the one given below using CSS.

Program:
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROOPTECH</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">ROOPTECH</div>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-box">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>"Driving progrss through precision engineering and boundless creativity."</h1>
            <div class="buttons">
                <button class="login">Log In</button>
                <button class="signup">Sign Up</button>
            </div>
        </section>
    </main>
    <footer>
        <p>Designed and Developed By Sai Vardhan(212221040022)</p>
    </footer>
</body>
</html>
```

Contact.html
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Products - ROOPTECH</title>
        <link rel="stylesheet" href="styles1.css">
    </head>
    <body>
        <header>
            <div class="logo">ROOPTECH</div>
            <nav>
                <ul>
                    <li><a href="index.html">HOME</a></li>
                    <li><a href="products.html">PRODUCTS</a></li>
                    <li><a href="council.html">PEOPLE</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
                <div class="search-box">
                    <input type="text" placeholder="Enter to Search">
                    <button>Search</button>
                </div>
            </nav>
        </header>

        <main>
            <div class="contact-container">
                <div class="contact-form">
                    <h2>Contact Us</h2>
                    <form>
                        <label for="name">Your Name</label>
                        <input type="text" id="name" name="name" required>
                        <label for="email">Your Email</label>
                        <input type="email" id="email" name="email" required>
                        <button type="submit">Submit</button>
                    </form>
                </div>
                <div class="contact-info">
                    <h2>Contact Information</h2>
                    <p><strong>Address:</strong> Mydukur,Kadapa,Andhra Pradesh,516172.</p>
                    <p><strong>Email:</strong> sai@gmail.com</p>
                    <p><strong>Phone:</strong> 1235643789</p>
            </div>
        </main>
    
        <footer>
            <p>All Rights Reserved</p>
        </footer>
    </body>
    </html>
```

council.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>People - ROOPTECH</title>
    <link rel="stylesheet" href="styles2.css">
</head>
<body>
    <header>
        <div class="logo">ROOPTECH</div>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-box">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="people">
            <div class="person">
                <img src="1.jpeg" alt="Roop Sagar">
                <h2>SAI</h2>
                <p>Founder</p>
            </div>
            <div class="person">
                <img src="2.jpeg" alt="Ratan Tata">
                <h2>MOTHISH</h2>
                <p>CEO</p>
            </div>
            <div class="person">
                <img src="3.jpeg" alt="Steve Jobs">
                <h2>VARDHAN</h2>
                <p>HR</p>
            </div>
            <div class="person">
                <img src="4.jpeg" alt="Sundar">
                <h2>SIDDARTH</h2>
                <p>Director</p>
            </div>
            <div class="person">
                <img src="5.jpeg" alt="Walt Disney">
                <h2>NANDAN</h2>
                <p>Manager</p>
            </div>
            <div class="person">
                <img src="6.jpeg" alt="Elon Musk">
                <h2>SAAHO</h2>
                <p>Employee</p>
            </div>
        </section>
    </main>

    <footer>
        <p>All Rights Reserved</p>
    </footer>
</body>
</html>
```

product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - ROOPTECH</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body>
    <header>
        <div class="logo">ROOPTECH</div>
        <nav>
            <ul>
                <li><a href="index.html">HOME</a></li>
                <li><a href="products.html">PRODUCTS</a></li>
                <li><a href="council.html">PEOPLE</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
            <div class="search-box">
                <input type="text" placeholder="Enter to Search">
                <button>Search</button>
            </div>
        </nav>
    </header>

    <main>
        <section class="products">
            <div class="product">
                <h2>JavaScript</h2>
                <p>Precision Meets JS Programming</p>
            </div>
            <div class="product">
                <h2>Python</h2>
                <p>Precision Meets JS Programming</p>
            </div>
            <div class="product">
                <h2>SQL</h2>
                <p>SQL is a standard language</p>
            </div>
            <div class="product">
                <h2>C++</h2>
                <p>Efficiently Redifinesd/p>
            </div>
        </section>
    </main>

    <footer>
        <p>All Rights Reserved</p>
    </footer>
</body>
</html>
```

styles.css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:#000;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}

.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background:black;
    text-align: center;
}

.hero h1 {
    font-size: 50px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}
.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: #f00;
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}

```
styles1.css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:black;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}
nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}

.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background:black;
    text-align: center;
}
.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}

.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: #f00;
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}
.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.product {
    background-color: #222;
    padding: 20px;
    border-radius: 10px;
    width: 200px;
    text-align: center;
}

.product h2 {
    color: #f00;
}

.product p {
    color: #aaa;
}
```
styles2css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color: #fff;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:black;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}
.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background:black;
    text-align: center;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}
.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: rgb(54, 95, 146);
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}

.people {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.person {
    text-align: center;
    color: #fff;
}

.person img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
}

.person h2 {
    margin: 10px 0 5px;
}

.person p {
    color: rgb(187, 209, 15);
}
```
styles3.css
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #000;
    color:black;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color:antiquewhite;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

.search-box {
    display: flex;
    align-items: center;
}

.search-box input {
    padding: 5px;
    border: none;
    border-radius: 3px;
}

.search-box button {
    padding: 5px 10px;
    border: none;
    border-radius: 3px;
    margin-left: 5px;
    background-color: #00f;
    color: #fff;
    cursor: pointer;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    background:black;
    text-align: center;
}

.hero h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.buttons {
    display: flex;
    gap: 20px;
}

.buttons button {
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.login {
    background-color: #f00;
    color: #fff;
}

.signup {
    background-color: #0f0;
    color: #000;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #111;
    color: #fff;
}

.contact {
    padding: 20px;
    text-align: center;
    color: #fff;
}

.contact h1 {
    margin-bottom: 20px;
}

form {
    max-width: 600px;
    margin: 0 auto;
    text-align: left;
}

.form-group {
    margin-bottom: 15px;
}

label {
    display: block;
    margin-bottom: 5px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 5px;
    box-sizing: border-box;
}

button[type="submit"] {
    display: block;
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 5px;
    background-color: #00f;
    color: #fff;
    font-size: 16px;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #0055cc;
}

```

Output:
![Screenshot 2024-07-15 133958](https://github.com/user-attachments/assets/7cd5550c-09a4-4155-9d6a-f7e8d4f02ac6)

![Screenshot 2024-07-15 134008](https://github.com/user-attachments/assets/42f3e7f6-3428-409f-b490-1ca2d3cfcc7a)

![Screenshot 2024-07-15 134017](https://github.com/user-attachments/assets/84b36e11-f3f6-4bdb-b7bd-1715f263a30a)

![Screenshot 2024-07-15 134026](https://github.com/user-attachments/assets/07ce5a7d-5031-4882-8269-80843166e48a)


Result:
Therefore, the code was executed successfully and web page was created.
