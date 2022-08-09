<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="styles2.csss">
    <title>Dropdown Menu</title>
</head>
<body>
        <nav>
            <ul>
                <!--Home-->
                <li><a href="#"><i class="fa-solid fa-house"></i></a></li>                <!--Shop-->    
                <!--Shop-->
                <li class="dropdown">
                    <a href="#"><i class="fa-solid fa-cart-shopping"></i></a>
                            <ul class="dropsown-menu">
                                <li><a href="#">Clothing</a></li>
                                <li><a href="#">Accessories</a></li>
                                <li><a href="#">Shoes</a></li>
                        </ul>
                    </li>

                <li><a href="#"><i class="fa-solid fa-cart-shopping"></i></a></li>
<style>
    body {
    height: 1500px;
    position: relative;
}

ul {
    display: flex;
    justify-content: center;
}

li {
    display: inline;
    padding: 10px;
    list-style: none;
}

nav {
    background-color:aqua;
    position: fixed;
    width: 100%;
    padding: 10px;
}

a:hover {
    background-color: blueviolet
}

a {
    text-decoration: none;
}

.dopdown-menu {
    position: absolute;
    width: 50%;
    background-color: white;
    flex-direction: column;
    justify-content: flex-end;
    border: 2px solid blue;
    padding-left: 0;
    border-radius: 5px;
    opacity: 0;
    transition: 0.5s;
}

.dropsown:hover .dropdown-menu {
    opacity: 1;
}

.dropdown a:hover {
    cursor: pointer;
}

@media only screen and (maz-width: 768px) {
    ul {
        flex-direction: column;
    }
}
                </style>
