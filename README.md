# Navbar
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>flexbox</title>
    <style>
        .logo img{
            width: 164px;
            cursor:pointer;
        }
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            font-family: "Segoe UI";
        }
        nav1 {
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            align-items: center;
            font-family: "Segoe UI";
            gap:20px}
        nav2 {
            display: flex;
            align-items:center;
            justify-content:center ;
            font-family: "Segoe UI";
            }
        .small{
            font-size:15px;
        }
        span{
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 25px;
        }

        .right ul {
            display: flex;
            align-items: center;
            gap: 34px;
            list-style: none;
            cursor: pointer;
        }
        .right ul li span{
            padding: 0 5px;
        }
        .container{
            background-color:rgb(255, 255, 255);
            display: grid;
            grid-template-columns: 200px 200px 200px;
            grid-template-rows:50vh 50vh;
            justify-content: center;
            gap: 34px;
            margin: 20px;
        }
        .item{
            display:flex;
            flex-direction: column;
            gap:34px;
            background-color:rgba(185, 158, 158, 0.049);
            margin:2px;
            font-size: 30px;
            font-style: italic;
            display:flex;
            justify-content: center;
            align-items: center;
        }
        button{
            cursor:pointer;
            color:White;
            background-color: rgba(47, 131, 234, 0.788);
            border: none;
            border-radius: 7px;
            font-weight: bolder;
            font-size: 25px;
        }
    </style>
</head>
<body>
        <nav>
            <div class="logo">
                <img src="https://www.ultraedit.com/wp-content/uploads/2023/01/Dark-logo.png" alt="">
            </div>
            <div class="right">
                <ul>
                    <li><span>Products </span>
                        </li>
                    <li><span>Pricing </span>
                        </li>
                    <li><span>Resources </span>
                        </li>
                    <li><span>About Us </span>
                        </li>
                    <li>
                        <img src="https://www.ultraedit.com/wp-content/themes/Divi_Child/img/Lang.png" alt=""></div>

                    </li>
                </ul>
            </div>
        </nav>
        <nav1>
        <div class="right">
            <ul>
                <li><span>Download UltraEdit for Windows  Reviews</span></li>
            <li><img src=https://www.ultraedit.com/wp-content/uploads/2022/10/Reviews.png" alt=""></li></ul></div>
            
        <span>Download and try UltraEdit before you buy it!</span>
            <span>This download includes the full Windows version of the text editor.</span>
        </div>
        <div><button>Download MAC OR LINUX VERSION</button></div></nav1>
        <nav2><div><img src="https://www.ultraedit.com/wp-content/uploads/2023/01/UE-Logo-1.webp" alt=""></div>
        <div><span>Download UltraEdit</span></div>
        <div><span class="small"> v2023.2(released 2023/12/15) | Hotfix</span></div></nav2>
        <body>
           <div class="container">
            <div class="item">English <button>Download</button></div>
            <div class="item">Italino<button>Download</button></div>
            <div class="item">Espanol<button>Download</button></div>
            <div class="item">French<button>Download</button></div>
            <div class="item">Korean<button>Download</button></div>
            <div class="item">Hindi<button>Download</button></div>
           </div>
        
</body>

</html>
