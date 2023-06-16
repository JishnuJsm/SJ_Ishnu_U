<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MyPortfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <style>
        *{
            margin: 0;
            border: 0;
            box-sizing: border-box;
            font-family: 'Roboto Slab', serif;
        }
        .hero{
            height: 100vh;
            font-size: 25px;
            background-image: url(https://dz2cdn1.dzone.com/storage/temp/12071731-always-be-learning.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 15px;
            color:papayawhip;
        }
        .hero h1{
            align-items: var(0.5em);
            /* margin-left: 700px; */
        }
        /* .h1{
            margin-top: 150px;
        }  */
        .hero span{
            font-size:  0.5em;
        }
        .black-box{
            background-color: black;
            color: white;
            font-size: 25px;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 20vh;
        }
        .black-box span{
            font-size: 1.5em;
        }
        .card-container{
            height: 60vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .cards{
            width: 20%;
            height: 85%;
            margin: 15px;
            border-radius: 15px;
            box-shadow: 3px 3px 2px 1px rgba(0, 0, 0, 0.2);
        }
        /* #card-1{
            background-image: url("https://i.pinimg.com/originals/ba/0e/b8/ba0eb82dbe74fb21925083c2ea7475b4.jpg");
            background-position: top;
            background-size: contain;
            background-repeat: no-repeat;
        }
        #card-2{
            background-image: url("https://cdn3.vectorstock.com/i/1000x1000/61/57/app-development-infpgraphic-concept-background-vector-8646157.jpg");
            background-position: top;
            background-size: contain;
            background-repeat: no-repeat;
        }
        #card-3{
            background-image: url("https://th.bing.com/th/id/OIP.1025cxIEjULEPDPp30qMcQHaHa?pid=ImgDet&rs=1");
            background-position: top;
            background-size: contain;
            background-repeat: no-repeat;
        } */
        .cards-img{
            height: 50%;
        }
        img{
            width: 100%;
            height: 100%;
            border-radius: 15px;
        }
        .cards-text{
            height: 50%;
            padding: 20px;
            overflow: hidden;
        }
        .bottom{
            height: 40vh;
            display: flex;
            justify-content: space-around;
        }
        .contact{
            margin: 20px;
            padding: 15px;
            background-color: rgb(51, 153, 51);
            color: white;
        }
        .about{
            margin: 20px;
            padding: 15px;
            background-color: rgb(255, 51, 0);
            color: white;
        }
        .bottom h3{
            padding: 10px;
            font-size: 35px;
        }
        .bottom p{
            padding: 10px;
            font-size: 18px;
        }
        @media(width<=750px) {
            .hero{
                display: flex;
            }
            .card-container{
                height: auto;
                display: flex;
                flex-direction: column;
            }
            .cards{
                width: 50%;
            }
            .cards-img{
                height: 50%;
            }
            .cards-text{
                height: 50%;
                padding: 20px;
            }
            .bottom{
                height: auto;
                display: flex;
                flex-direction: column;
            }
            .contact{
                margin: 0px;
            }
            .about{
                margin: 0px;
            }
        }
    </style>
</head>
<body>
    <section class="hero">
        <h1 class="h1">Hi,<span>I am Jishnu</span></h1>
        <h1>FULL STACK DEVELOPER</h1>
    </section>
    <section class="black-box">
        <h3>WORK, I CAN DO FOR <span>YOU</span></h3>
    </section>
    <section class="card-container">
        <div id="card-1" class="cards">
            <div class="cards-img">
                <img src="https://i.pinimg.com/originals/ba/0e/b8/ba0eb82dbe74fb21925083c2ea7475b4.jpg" alt="Image Not Found">
            </div>
            <div class="cards-text">
                <h4>Web Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat tempora provident soluta ipsum nisi.</p>
            </div>
        </div>
        <div id="card-2" class="cards">
            <div class="cards-img">
                <img src="https://cdn3.vectorstock.com/i/1000x1000/61/57/app-development-infpgraphic-concept-background-vector-8646157.jpg" alt="Image Not Found">
            </div>
            <div class="cards-text">
                <h4>App Development</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci dignissimos sit fuga doloribus, aliquid.</p>
            </div>
        </div>
        <div id="card-3" class="cards">
            <div class="cards-img">
                <img src="https://th.bing.com/th/id/OIP.1025cxIEjULEPDPp30qMcQHaHa?pid=ImgDet&rs=1" alt="Image Not Found">
            </div>
            <div class="cards-text">
                <h4>UI UX Design</h4>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non perferendis, laboriosam, quas earum error!</p>
            </div>
        </div>
    </section>
    <section class="bottom">
        <div class="contact">
            <h3>Contact Me</h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quidem corporis amet repellat asperiores, inventore dolores suscipit praesentium alias, fugit laborum eius hic impedit modi temporibus est, dignissimos deleniti odit illum.</p>
        </div>
        <div class="about">
            <h3>About Me</h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nulla, molestiae quam corporis unde laboriosam perferendis at accusantium deserunt ad vitae corrupti. Pariatur odit dignissimos deserunt earum ex iure aliquam iste.</p>
        </div>
    </section>
</body>
</html>
