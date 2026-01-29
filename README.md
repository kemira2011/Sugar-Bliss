<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Sugar Bliss</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: url('https://images.unsplash.com/photo-1578985545062-69928b1d9587?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
    background-size: cover;
    color: #333;
}

header {
    padding: 60px 20px;
    text-align: center;
    background: rgba(255, 255, 255, 0.85);
    border-bottom: 5px solid #f472b6;
}

header img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 15px;
    border: 4px solid #fcd34d;
    object-fit: cover;
}

h1 { color: #d81b60; font-size: 2.5em; margin-bottom: 5px; }

section {
    padding: 40px 20px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    background: rgba(255, 254, 243, 0.95);
    padding: 30px;
    border-radius: 20px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    max-width: 500px;
    width: 100%;
    text-align: center;
}

button {
    padding: 12px 25px;
    border: none;
    border-radius: 25px;
    background: #f472b6;
    color: white;
    font-weight: bold;
    font-size: 1rem;
    cursor: pointer;
    margin-top: 15px;
    transition: 0.3s;
}

button:hover { background: #d81b60; transform: scale(1.05); }

footer {
    padding: 30px;
    text-align: center;
    background: #333;
    color: white;
}

footer a { color: #fcd34d; text-decoration: none; font-weight: bold; }
</style>
</head>
<body>

<header>
    <img src="logo.jpg" alt="Sugar Bliss Logo"> 
    <h1>Welcome to Sugar Bliss</h1>
    <p style="font-style: italic; font-size: 1.2rem;">Sweet Treats | Cakes | Watalappan | Desserts</p>
    <p><a href="https://web.facebook.com/profile.php?id=61585231595875" target="_blank" style="color: #1877F2; text-decoration: none; font-weight: bold;">Visit our Facebook Page</a></p>
</header>

<section>
    <div class="card">
        <h2 style="color: #f472b6;">About Sugar Bliss</h2>
        <p>We create delicious homemade sweets, cakes, and traditional Sri Lankan desserts with love and care.</p>
    </div>

    <div class="card">
        <h2 style="color: #f472b6;">Our Specialties</h2>
        <p>Cakes, Watalappan, Sweet Treats, Customized Orders</p>
        <button onclick="alert('Contact: sugarbliss@example.com')">Order Now</button>
    </div>
</section>

<footer>
    <p>© 2026 Sugar Bliss | <a href="https://web.facebook.com/profile.php?id=61585231595875" target="_blank">Follow us on Facebook</a></p>
</footer>

</body>
</html>
