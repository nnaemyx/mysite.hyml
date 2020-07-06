<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>nnaemy media</title>
    <link href="https://fonts.googleapis.com/css2?family=Source+Sans+Pro&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="nav-wrapper">
            <div class="left-side">
                <div class="nav-link-wrapper active-nav-link">
                    <a href="mysite.html">Home</a>
                </div>

                <div class="nav-link-wrapper">
                    <a href="about.html">About</a>
                </div>
            </div>
        
            <div class="right-side">
                <div class="brand">
                    <div>JOHNPAUL EDEH</div>
                </div>
            </div>                 
        </div>

        <div class="content-wrapper">
            <div class="portfolio-items-wrapper">

                <div class="portfolio-item-wrapper">
                    <div class="portfolio-img-background" style="background-image:url(images/portfolio1.jpg)" alt=""></div>
                
                    <div class="img-text-wrapper">
                        <div class="logo-wrapper">
                            <img src="images/logos/quip.png">
                        </div>

                        <div class="subtitle">
                            i built the website called portfolio
                        </div>
                    </div>
                </div>

                
                <div class="portfolio-item-wrapper">
                    <div class="portfolio-img-background" style="background-image:url(images/portfolio2.jpg)" alt=""></div>
                
                    <div class="img-text-wrapper">
                        <div class="logo-wrapper">
                            <img src="images/logos/quip (2).png">
                        </div>

                        <div class="subtitle">
                            i want to enter university
                        </div>
                    </div>
                </div>

                
                <div class="portfolio-item-wrapper">
                    <div class="portfolio-img-background" style="background-image:url(images/portfolio3.jpg)" alt=""></div>
                
                    <div class="img-text-wrapper">
                        <div class="logo-wrapper">
                            <img src="images/logos/quip.png">
                        </div>

                        <div class="subtitle">
                            i want to become a front end developer
                        </div>
                    </div>
                </div>

                
                <div class="portfolio-item-wrapper">
                    <div class="portfolio-img-background" style="background-image:url(images/portfolio4.jpg)" alt=""></div>
                
                    <div class="img-text-wrapper">
                        <div class="logo-wrapper">
                            <img src="images/logos/quip (2).png">
                        </div>

                        <div class="subtitle">
                            am a software developer
                        </div>
                    </div>
                </div>

                
                <div class="portfolio-item-wrapper">
                    <div class="portfolio-img-background" style="background-image:url(images/portfolio5.jpg)" alt=""></div>
                
                    <div class="img-text-wrapper">
                        <div class="logo-wrapper">
                            <img src="images/logos/quip.png">
                        </div>

                        <div class="subtitle">
                            my name is JOHNPAUL
                        </div>
                    </div>
                </div>

                
                <div class="portfolio-item-wrapper">
                    <div class="portfolio-img-background" style="background-image:url(images/portfolio6.jpg)" alt=""></div>
                
                    <div class="img-text-wrapper">
                        <div class="logo-wrapper">
                            <img src="images/logos/quip (2).png">
                        </div>

                        <div class="subtitle">
                            i made a port
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
<script>
    const portfolioitems = document.querySelectorAll(".portfolio-item-wrapper")

    portfolioitems.forEach(portfolioitem => {
        portfolioitem.addEventListener('mouseover', () => {
            portfolioitem.childNodes[1].classList.add('img-darken');
        })

        portfolioitem.addEventListener('mouseout', () => {
            portfolioitem.childNodes[1].classList.remove('img-darken');
        })
    })
</script>
</html>
