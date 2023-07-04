<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Creator</title>
    <link rel="icon" type="image" href="/images/Logo.jpeg">
    <link rel="stylesheet" href="Style2.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>

<body>
    <div class="root">
        <!--------------------------  NAV BAR   --------------------->
        <div class="navbar" id="navbar">
            <div class="logo">
                <div class="icon"><img src="images/Logo.jpeg" alt="DC" height="150px" width="150px"></div>
                <div class="text">Digital Creator</div>
            </div>
            <ul>
                <div class="navItems" id="HomeN" onclick="openHome()" style="color: var(--skin-color);"><i
                        class="fa fa-home"></i>&nbsp; Home</div>
                <div class="navItems" id="AboutN" onclick="openAbout()"><i class="fa fa-user"></i>&nbsp;About Me</div>
                <div class="navItems" id="CourcesN" onclick="openCourses()"><i class="fa fa-book"></i>&nbsp;Courses
                </div>
                <div class="navItems" id="PerksN" onclick="openPerks()"><i class="fa fa-briefcase"></i>&nbsp; Perks
                </div>
                <div class="navItems" id="ContactN" onclick="openContact()"><i class="fa fa-comment"></i>&nbsp; Contact
                    Me</div>
            </ul>
        </div>
        <!-------------------------  BACKGROUND  ------------------->
        <div class="container" id="container">
            <div class="Bg_Circlea"></div>
            <div class="Bg_Circleb"></div>
            <div class="Bg_Circlec"></div>
            <div class="Bg_Circled"></div>
            <div class="Bg_Circlee"></div>
            <div class="Bg_Circlef"></div>

            <div class="DayMode" id="Day" onclick="openDay()"><img src="images/sun.png" alt="Day" style="color:var(--skin-color);height: inherit;
                width: inherit;"></div>

            <div class="NightMode" id="Night" onclick="openNight()"><img src="images/moon.png" alt="Night" style="    height: 20px;
                width: 20px;"></div>
            <div class="theme">
                <div class="theme-content">
                    <div class="themeI" id="red" onclick="setRed()"></div>
                    <div class="themeI" id="blue" onclick="setBlue()"></div>
                    <div class="themeI" id="green" onclick="setGreen()"></div>
                    <div class="themeI" id="orange" onclick="setOrange()"></div>
                </div>
            </div>
            <!------------------------   LANDING PAGE  ------------------>
            <section class="quote" id="Lander" style="color: var(--skin-color);">
                "Success is not only for the elite . Success is there for those who want it, plan for it , and take
                action to achieve it"
            </section>
            <!--------------------------  ABOUT PAGE  -------------------->
            <section class="AboutPage" id="AboutH">
                <div class="Head">About Me
                    <div class="onel"></div>
                    <div class="twol"></div>
                </div>
                <div class="content-container">
                        <div class="home-info">
                            <div class="home-items">
                            <h3 class="hello">Hello, my name is <span class="Name">Riya Singh</span></h3>
                            <h3 class="my-profession">I'm a <span class="typing">Affiliate Marketor and Digital Creator</span></h3>
                            <p>We produces online content across various platforms.
                            This could include social media, blogs, podcasts, or videos. 
                            We create and share content that is authentic to them and their brand 
                            and they usually have a specific niche or audience they target.</p>
                        </div></div>
                        <div class="home-img">
                            <div class="img">
                            <img src="images/Riya.png" alt="">
                        </div>
                        </div>
                </div>
            </section>
            <!-------------------------  COURCES PAGE  -------------------->

            <section class="CourcePage" id="course">
                <div class="Head">Cources Available
                    <div class="onel"></div>
                    <div class="twol"></div>
                </div>
                <div class="content-container">
                    <div class="Branding" id="Branding">
                        <div class="Subject" style="    display: flex;
                        align-items: center;
                        justify-content: center;
                        width: 70%;border-bottom: 1px solid var(--skin-color);
                        font-size: 4.5vh;color: var(--skin-color);">Branding Mastery</div>
                        <div class="title" style="font-size: 3.5vh;margin-top: 15px;">Cource Contents</div>
                        <div class="box">
                            <ul style="margin-left: 15%;">
                                <li>Personality Development</li>
                                <li>Video Superstar</li>
                                <li>Millionaire Success Blueprint</li>
                                <li>Facebook Marketing</li>
                                <li>Basic Instagram Mastermind</li>
                                <li>Spoken English</li>
                                <li>Affilate Marketing Mastermind</li>
                            </ul>
                            <div class="button"><a href="https://bizgurukul.com//Signup.aspx?id=oYPViZV/GDw=&ref=pp9B04qzyYoWrPOUDsSrsg==">Apply Now</a></div>
                        </div>
                    </div>
                    <div class="Traffic" id="Traffic">
                        <div class="Subject" style="    display: flex;
                        align-items: center;
                        justify-content: center;
                        width: 70%;border-bottom: 1px solid var(--skin-color);
                        font-size: 4.5vh;color: var(--skin-color);">Traffic Mastery</div>
                        <div class="title" style="font-size: 3.5vh;margin-top: 15px;">Cource Contents</div>
                        <div class="box">
                            <ul style="margin-left: 15%;">
                                <li>Intermediate Instagram Mastermind</li>
                                <li>Facebook Ads Mastermind</li>
                                <li>Youtube Mastermind</li>
                                <li>Google Ads Mastermind</li>
                                <li>Excel Mastery</li>
                                <li>E-Mail Marketing Mastery</li>
                                <li>LinkedIn Mastery</li>
                                <li>MS Word</li>
                                <li>MS Powerpoint</li>
                            </ul>
                            <div class="button"><a href="https://bizgurukul.com//Signup.aspx?id=lPC2QdX4/P0=&ref=pp9B04qzyYoWrPOUDsSrsg==">Apply Now</a></div>
                        </div>
                    </div>
                    <div class="Influence" id="Influence">
                        <div class="Subject" style="    display: flex;
                        align-items: center;
                        justify-content: center;
                        width: 70%;border-bottom: 1px solid var(--skin-color);
                        font-size: 4.5vh;color: var(--skin-color);">Influence Mastery</div>
                        <div class="title" style="font-size: 3.5vh;margin-top: 15px;">Cource Contents</div>
                        <div class="box">
                            <ul style="margin-left: 15%;">
                                <li>Master Public Speaking</li>
                                <li>Copywriting Mastermind</li>
                                <li>Content Marketing</li>
                                <li>Podcast Mastery</li>
                                <li>Sales Mastery</li>
                                <li>Become a Best-Selling Author</li>
                                <li>Advance Instagram Mastermind</li>
                            </ul>
                            <div class="button"><a href="https://bizgurukul.com//Signup.aspx?id=aBdsUosgN7I=&ref=pp9B04qzyYoWrPOUDsSrsg==">Apply Now</a></div>
                        </div>
                    </div>
                    <div class="Marketing" id="Marketing">
                        <div class="Subject" style="    display: flex;
                        align-items: center;
                        justify-content: center;
                        width: 70%;border-bottom: 1px solid var(--skin-color);
                        font-size: 4.5vh;color: var(--skin-color);">Marketing Mastery</div>
                        <div class="title" style="font-size: 3.5vh;margin-top: 15px;">Cource Contents</div>
                        <div class="box">
                            <ul style="margin-left: 15%;">
                                <li>Digital Marketing </li>
                            </ul>
                            <div class="button"><a href="https://bizgurukul.com//Signup.aspx?id=+IE6GzOTU90=&ref=pp9B04qzyYoWrPOUDsSrsg==">Apply Now</a></div>
                        </div>
                    </div>
                    <div class="Finance" id="Finance">
                        <div class="Subject" style="    display: flex;
                        align-items: center;
                        justify-content: center;
                        width: 70%;
                        font-size: 4.5vh;border-bottom: 1px solid var(--skin-color);color: var(--skin-color);">Finance
                            Mastery</div>
                        <div class="title" style="font-size: 3.5vh;margin-top: 15px;">Cource Contents</div>
                        <div class="box">
                            <ul style="margin-left: 15%;">
                                <li>Stock Market Mastery (BEGINNER)</li>
                                <li>Stock Market Mastery (ADVANCE)</li>
                            </ul>
                            <div class="button"><a href="https://bizgurukul.com//Signup.aspx?id=KRl5o+bvMnw=&ref=pp9B04qzyYoWrPOUDsSrsg==">Apply Now</a></div>
                        </div>
                    </div>
                </div>
                <div class="content-nav">
                    <div class="nav" id="Cone" onclick="openBranding()"></div>
                    <div class="nav" id="Ctwo" onclick="openTraffic()"></div>
                    <div class="nav" id="Cthree" onclick="openInfluence()"></div>
                    <div class="nav" id="Cfour" onclick="openMarketing()"></div>
                    <div class="nav" id="Cfive" onclick="openFinance()"></div>
                </div>
            </section>
            <!-----------------------  PERKS PAGE    ----------------------------------->
            <section class="PerkContainer" id="Perks">
                <div class="Head">Perks of Bizgurukul
                    <div class="onel"></div>
                    <div class="twol"></div>
                </div>
                <div class="content-container">
                    <div id="Cources" class="Cources">
                        <span class="HeadPC"
                            style="font-size: 4.5vh;border-bottom: 1px solid var(--skin-color);color: var(--skin-color);">Cources</span>
                        <ul>
                            <li>Access to Trending skill-based cources.</li>
                            <li>Regular updation of cources.</li>
                            <li>Addition of new cources in existing bundles without any extra fees.</li>
                            <li>Strengthen your resume by qualifying course tests and getting certified from Bizgurukul
                            </li>
                            <li>Personal guidance through Live Q&A Sessions from our experienced trainers</li>
                            <li>Sunday special training for holistic development of students.eg. money management,
                                health,
                                fitness, graphology, time management, sales and much more.</li>
                            <li>Training in English and Hindi language.</li>
                            <li>Access to our recorded training sessions in case you miss a liv session.</li>
                            <li>Guidance to help you monetize cources through multiple channels.</li>
                            <li>Weekly Fb live sessions by our expert management to solve your problems.</li>
                            <li>Learner's community is our exclusive space where regular quizzes, contents and
                                activitiees
                                provide an opportunity to grow together. You can freely ask questions related to all
                                cources
                                here. You can win prizes too!!!</li>
                        </ul>
                    </div>
                    <div id="Community" class="Community">
                        <span class="HeadP"
                            style="font-size: 4.5vh;border-bottom: 1px solid var(--skin-color);color: var(--skin-color);">Community</span>
                        <ul>
                            <li>You can be a part of our community on various social media platforms and get to connect
                                with
                                like-minded people where people share their success and hustle stories and get inspired
                                to
                                grow together.</li>
                            <li>One Stop Solution for all queries....
                                <ol>
                                    <li>Customer support team - handle all technical issues. Active from Monday to
                                        Saturday,9:30 am to 6:00 pm.</li>
                                    <li>Payment Support Team - to clear all payment queries. Active from Monday to
                                        Sunday,9:30 am to 6:00 pm</li>
                                    <li>Affiliate support team - is always available to support you to build your
                                        business
                                        from day one by well trained team . Active from Monday to Saturday , 9:30 am to
                                        6:00
                                        pm.</li>
                                </ol>
                            </li>
                        </ul>
                    </div>
                    <div id="Rewards" class="Rewards">
                        <span class="HeadR"
                            style="font-size: 4.5vh;border-bottom: 1px solid var(--skin-color);color: var(--skin-color);">Rewards</span>
                        <ul>
                            <li>
                                Easy targets to win Bizgurukul Merchandise. eg. T-Shirts, Badges, Hoodies, Certificates.
                            </li>
                            <li>
                                Opportunity to win fully sponsored National / International trips through our Fly with
                                Bizgurukul Program .
                            </li>
                            <li>Opportunity to interact with our top management through our exclusive meetups. </li>
                            <li>Opportunity to buy your own car through our Car Superstar Program</li>
                            And Much more...... <br>
                            Bizgurukul is a family and we'll give our best to make your future brighter.
                        </ul>
                    </div>
                    <div id="Affilate" class="Affilate">
                        <span class="HeadA"
                            style="font-size: 4.5vh;border-bottom: 1px solid var(--skin-color);color: var(--skin-color);">Affiliate
                            Program</span>
                        <ul>
                            <li>
                                Bizgurukul provides a platform to learn and earn upto 70% commision and start your
                                journey
                                to become a millionare.
                            </li>
                            <li>Professional marketing tools to grow your business.</li>
                            <li>Regular offers to boost your business.</li>
                            <li>Passive income through exclusive Prime Subscription.</li>
                            <li>Three step Pracical training---
                                <ol>
                                    <li>A well designed Steps to success video series for Biginners by marketing
                                        head,Bizgurukul</li>
                                    <li>Regular practical training to help you create massive results by those who have
                                        created 3 lac to 50 lac plus capital in our ecosystem .</li>
                                    <li>Prime training for advance knowledge by industry experts.</li>
                                </ol>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="perks-nav">
                    <div class="nav" id="one" onclick="openCourc()"></div>
                    <div class="nav" id="two" onclick="openCommunity()"></div>
                    <div class="nav" id="three" onclick="openRewards()"></div>
                    <div class="nav" id="four" onclick="openAffilate()"></div>
                </div>
            </section>
            <!-----------------------------   CONTACT ME SECTION   ------------------------------>
            <section class="Contactme" id="Contact">
                <div class="Head">Contact Me
                    <div class="onel"></div>
                    <div class="twol"></div>
                    <div class="text" style="    font-size: 2.6vh;
                    width: 230px;">You can contact me and I will try to
                        reach you within 24 hours.....</div>
                </div>
                <!--------------------------------  PERSONAL HANDLES  -------------------------------------->
                <div class="body">
                    <div class="perinfo-contain">

                        <div class="message">
                            <div class="head" style="color: var(--skin-color);">Contact Information</div>
                            <div class="text" style="font-size: 2.5vh;margin-left: 25%;">You can reach me at.....
                            </div>
                        </div>
                        <div class="info">
                            <div class="data">Mail : Creatord509@gmail.com</div>
                            <div class="data">Contact : +91 9999999999</div>
                            <div class="data" style="height: 40%;">Address : <br>dsgjfbiuhnsnsquxhjnxqj <br>Panipat,
                                <br>Haryana, <br> India
                            </div>
                        </div>


                    </div>
                    <!---------------------------== CONTACT FORM  ==----------------------------------------------->
                    <div class="formCont">
                        <div class="message">
                            <div class="head" style="color: var(--skin-color);">Contact Form</div>
                        </div>
                        <div class="form">
                            <form action="https://formspree.io/f/mgebaqde" method="POST">
                                <input type="text" name="Name" id="Name" placeholder="Your Name Here" required>
                                <input type="email" name="Email" id="Email" placeholder="Your-Email here" required>
                                <textarea name="Message" id="Message" cols="30" rows="10"
                                    placeholder="Your Message Here"></textarea>
                                <br>
                                <button type="submit">Submit</button>
                                <button type="reset">Reset</button>
                            </form>
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </div>
    <script src="script2.js"></script>
</body>
<!-----<div class="social">
                                <div class="icon" id="Insta"><a href="#">Instagram</a></div>
                                <div class="icon" id="Whats"><a href="#">Whatsapp</a></div>
                                <div class="icon" id="Lin"><a href="#">LinkedIn</a></div>
                                <div class="icon" id="FB"><a href="#">Facebook</a></div>
                                <div class="icon" id="Youtube"><a href="#">Youtube</a></div>
                            </div>-->

</html>
