<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SpotInvest</title>
    <link rel="stylesheet" href="index.css">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
</head>

<body>
    <!-- <svg id="background" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 1280 746.38">
        <defs>
            <style>
                .cls-1 {
                    fill: url(#linear-gradient);
                }
                .cls-2 {
                    fill: url(#linear-gradient-2);
                }
                .cls-3 {
                    opacity: 0.1;
                    isolation: isolate;
                }
            </style>
            <linearGradient id="linear-gradient" x1="353.73" y1="-19.08" x2="678.71" y2="692.23"
                gradientTransform="matrix(1, 0, 0, -1, 0, 748)" gradientUnits="userSpaceOnUse">
                <stop offset="0" stop-color="#3738eb" />
                <stop offset="1" stop-color="#3cbbef" />
            </linearGradient>
            <linearGradient id="linear-gradient-2" x1="573.9" y1="192.65" x2="569.92" y2="116.22"
                gradientTransform="matrix(1, 0, 0, -1, 0, 748)" gradientUnits="userSpaceOnUse">
                <stop offset="0" stop-color="#ffb696" />
                <stop offset="1" stop-color="#ff7a95" />
            </linearGradient>
        </defs>
        <path class="cls-1" d="M0,482S91,758,317,746,512,523,764,489s359-3,516-208V0H0" />
        <path class="cls-2" d="M617,634c-9.54,11.92-43,0-79-22s-2-43,6-47,37-23,57,0S625,624,617,634Z" />
        <path class="cls-3"
            d="M623,129c0,145.67,70.63,274.84,179.51,355.14,224.85-26.53,328.73-8.9,477.49-203.14V0H642.18A440.69,440.69,0,0,0,623,129Z" />
    </svg> -->
    <img src="images/Untitled-1-01.svg" alt="SVG background" id="svg-background">
    <svg id="mobile-background" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 730 320">
        <path fill="#0099ff" fill-opacity="1"
            d="M0,256L40,224C80,192,160,128,240,122.7C320,117,400,171,480,165.3C560,160,640,96,720,96C800,96,880,160,960,165.3C1040,171,1120,117,1200,128C1280,139,1360,213,1400,250.7L1440,288L1440,0L1400,0C1360,0,1280,0,1200,0C1120,0,1040,0,960,0C880,0,800,0,720,0C640,0,560,0,480,0C400,0,320,0,240,0C160,0,80,0,40,0L0,0Z">
        </path>
    </svg>
    <div class="container">
        <header class="main-header">
            <nav class="main-nav">
                <ul class="navbar">
                    <li><a href="#" class=navbar-item>HOME</a></li>
                    <li><a href="#pricing" class=navbar-item>PRICING</a></li>
                    <li><a href="faq.html" class=navbar-item>FAQ</a></li>
                </ul>
            </nav>
            <a href="#bottom" class="contact-button">CONTACT US</a>
        </header>
        <section class="call-to-action">
            <div class="call-to-action-text">
                <h1>SpotInvest</h1>
                <p>Make Spotify Yours.</p>
                <a href="#">Learn More</a>
            </div>
            <div class="call-to-action-photo">
                <img src="images/twophones.png" alt="">
            </div>
        </section>
        <div class="pricing-list" id="pricing">
            <div class="pricing-text">
                <h2>Our Plans</h2>
                <p>Get Paid the Double</p>
                <p>Our service allows investment with stable legal and recurrent incomes. Spotify pays you directly, so
                    all
                    you have to do is give your paypal address and you're ready to go! We'll do the rest.</p>
            </div>
            <div class="pricing-table">
                <div class="card">
                    <div class="table">
                        <div class="color-top"></div>
                        <span>BRONZE</span>
                        <div class="price"><span>$</span>100</div>
                        <div class="ROI">ROI: 200%</div>
                        <div class="you-get">You get: $200</div>
                        <hr>
                        <div class="border-radius-gradient">
                            <a href="#" class="buy-now">BUY NOW</a>
                        </div>
                    </div>
                </div>
                <div class="card">
                    <div class="table">
                        <div class="color-top"></div>
                        <span>SILVER</span>
                        <div class="price"><span>$</span>225</div>
                        <div class="ROI">ROI: 200%</div>
                        <div class="you-get">You get: $450</div>
                        <hr>
                        <div class="border-radius-gradient">
                            <a href="#" class="buy-now">BUY NOW</a>
                        </div>
                    </div>
                </div>
                <div class="card">
                    <div class="table">
                        <div class="color-top"></div>
                        <span>GOLDEN</span>
                        <div class="price"><span>$</span>325</div>
                        <div class="ROI">ROI: 208%</div>
                        <div class="you-get">You get: $675</div>
                        <hr>
                        <div class="border-radius-gradient">
                            <a href="#" class="buy-now">BUY NOW</a>
                        </div>
                    </div>
                </div>
                <div class="card important">
                    <div class="table">
                        <div class="color-top important-top"></div>
                        <span>PLATINUM</span>
                        <div class="price"><span>$</span>750</div>
                        <div class="ROI">ROI: 210%</div>
                        <div class="you-get">You get: $1575</div>
                        <hr>
                        <div class="border-radius-gradient">
                            <a href="#" class="buy-now"><span class="important-button">BUY NOW</span> </a>
                        </div>
                    </div>
                </div>
                <div class="card cutom">
                    <div class="table">
                        <div class="color-top"></div>
                        <span>CUSTOM</span>
                        <div class="price"><span>$</span>???</div>
                        <div class="ROI">CONTACT US</div>
                        <div class="you-get"></div>
                        <hr>
                        <div class="border-radius-gradient">
                            <a href="#" class="buy-now">BUY NOW</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <section class="bottom" id = "bottom">
        <div class="bottom-text container">
            <h2>Contact</h2>
            <p>Join our Discord Server</p>
            <p>Join the thousands of people interested in investing by clicking the button below. It will lead to a
                Discord server where we manage all inquiries and dealings. Let's get started.</p>
            <a href="#" class="discord-button animated pulse infinite"><img src="images/discord.png" alt="Discord logo">CLICK HERE</a>
        </div>
    </section>

    <footer>
        <p>Made with &#128151; by <a href="https://discordapp.com/invite/85ZFBNj">Cotton Studios</a></p>
        <p>Bivert &copy; 2020</p>
    </footer>
</body>

</html>
