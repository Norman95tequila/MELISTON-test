<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="meliston logo.png" type="image/x-icon">
    <title>Meliston - Αρχική Σελίδα</title>
    <style>
        body {
            font-family: Proxima Nova, Cambria;
            margin: 0;
            padding: 0;
            background-color: #F5EFEE;
            color: #17202A;
        }
        header {
            background-color: #F5EFEE;
            color: #17202A;
            padding: 20px 0;
            text-align: center;
        }
        header img {
            width: 30px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            padding: 5px 10px;
        }
        nav a:hover {
            background-color: #575757;
            border-radius: 5px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px 0;
        }
        h1, h2 {
            color: #444;
        }
        .products, .gallery, .articles {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product, .photo, .article {
            flex: 1 1 calc(33.333% - 40px);
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 20px;
            background-color: #fff;
        }
        .contact {
            background-color: #2d2d2d;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

<header>
    <img src="meliston logo.png" alt="MelistonLogo">
</header>

<nav>
    <a href="Products.html">Προϊόντα</a>
    <a href="about.html">Σχετικά</a>
    <a href="contact.html">Επικοινωνία</a>
    <a href="articles.html">Άρθρα</a>
</nav>

<div class="container">
    <!-- Ενσωμάτωση βίντεο -->
    <h2>Καλωσήρθατε στο Meliston!</h2>
    <video width="100%" controls>
        <source src="IMG_0020.mov" type="video/mp4">
        Το πρόγραμμα περιήγησής σας δεν υποστηρίζει την ετικέτα βίντεο.
    </video>
</div>

<footer>
    <p> &copy; 2024 Meliston.</p> 
</footer>

</body>
</html>
