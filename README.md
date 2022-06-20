# Vajir
website

html code 










<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vajir</title>
    <!-- custom css file link  -->
    <link rel="stylesheet" href="style.css">

</head>
<body>
    
<!-- header section starts  -->

<header>

    <div id="menu-bar" class="fas fa-bars"></div>

    <a href="#" class="logo">V<SPan>AJIR</SPan></a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#book">book</a>
        <a href="#packages">packages</a>
        <a href="#services">services</a>
        <a href="#gallery">gallery</a>
        <a href="#review">review</a>
        <a href="#contact">contact</a>
    </nav>

    <div class="icons">
        <i class="fas fa-search" id="search-btn"></i>
        <i class="fas fa-user" id="login-btn"></i>
    </div>

    <form action="" class="search-bar-container">
        <input type="search" id="search-bar" placeholder="search here...">
        <label for="search-bar" class="fas fa-search"></label>
    </form>

</header>

<!-- header section ends -->


<!-- home section starts  -->

<section class="home" id="home">

    <div class="content">
        <h3>adventure is worthwhile</h3>
        <p>dicover new places with us, adventure awaits</p>
        <a href="#" class="btn">discover more</a>
    </div>

    <div class="controls">
        <span class="vid-btn active" data-src="images/rajgad.mp4"></span>
        <span class="vid-btn" data-src="images/waterfall.mp4"></span>
        <span class="vid-btn" data-src="images/rajgad2.mp4"></span>
        <span class="vid-btn" data-src="images/rajgad3.mp4"></span>
        <span class="vid-btn" data-src="images/rain.mp4"></span>
    </div>

    <div class="video-container">
        <video src="images/rajgad.mp4" id="video-slider" loop autoplay muted></video>
    </div>

</section>

<!-- home section ends -->


<!-- book section starts  -->

<section class="book" id="book">

    <h1 class="heading">
        <span>b</span>
        <span>o</span>
        <span>o</span>
        <span>k</span>
        <span class="space"></span>
        <span>n</span>
        <span>o</span>
        <span>w</span>
    </h1>

    <div class="row">

        <div class="image">
            <img src="images/book-img.svg" alt="">
        </div>

        <form action="savedata.php" method="post">
            <div class="inputBox">
                <h3>where to</h3>
                <input type="text" placeholder="place name" name="whereTo">
            </div>
            <div class="inputBox">
                <h3>how many</h3>
                <input type="number" placeholder="number of guests" name="HowMany">
            </div>
            <div class="inputBox">
                <h3>arrivals</h3>
                <input type="date" name="Arrivals">
            </div>
            <div class="inputBox">
                <h3>leaving</h3>
                <input type="date" name="Leaving">
                <div class="inputBox">
                    <h3>phone number</h3>
                    <input type="text" name="phone">
            </div>
            <input type="submit" class="btn" value="book now">
        </form>

    </div>

</section>

<!-- book section ends -->

<!-- packages section starts  -->

<section class="packages" id="packages">

    <h1 class="heading">
        <span>p</span>
        <span>a</span>
        <span>c</span>
        <span>k</span>
        <span>a</span>
        <span>g</span>
        <span>e</span>
        <span>s</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <img src="images/rajgad.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Rajgad </h3>
                <p>The fort has stood witness to many significant historic events including the birth of Chatrapati Shivaji Maharaj's son Rajaram I, the death of Chatrapati Shivaji Maharaj's Queen Saibai, the return of Chatrapati Shivaji Maharaj from Agra, the burial of Afzal Khan's head in the Mahadarwaja walls of Balle Killa, the strict words of Sonopant Dabir to Chhatrapati Shivaji Maharaj.[citation needed]
                    The Rajgad Fort was also one of the 12 forts that Chatrapati Shivaji Maharaj kept when he signed the Treaty of Purandar in 1665, with the Mughal general Jai Singh I, leader of the Mughal forces. Under this treaty, 23 forts were handed over to the Mughals.Rajgad has been the first capital of the Maratha empire and continued to be the capital for 26 years. Rajgad is the first fort built by Chatrapati Shivaji. Important Historical Records of Rajgad.ajgad stands tall with its citadel measuring 1400 meters high in altitude. Aurangzeb’s army attacked the fort on 4th February 1703 and emerged victorious”.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">₹ 899.00 <span>1200.00</span> </div>
                <a href="#book" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="images/torana.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Torana </h3>
                <p>This fort is believed to have been constructed by the Shiva Panth in the 13th century. A Menghai Devi temple, also referred to as the Tornaji temple, is situated near the entrance of the fort.
                    In 1646, Chhatrapati Shivaji Maharaj captured this fort at the age of sixteen[citation needed], thus making it one of the first forts that would become one of the forts of the Maratha empire. Chhatrapati Shivaji Maharaj renamed the fort ' 'Prachandagad' ' as Torna, and constructed several monuments and towers within it.[2]
                     In the 18th century, the Mughal empire briefly gained control of this fort after the assassination of Chhatrapati Shivaji Maharaj's son Chhatrapati Sambhaji raje. Aurangzeb, the then Mughal emperor, renamed this fort Futulgaib in recognition of the difficult defense the Mughals had to overcome to capture this fort. It was restored to the Maratha confederacy by the Treaty of Purandar.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">₹ 999.00 <span>1500.00</span> </div>
                <a href="#book" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="images/rohida.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Rohida </h3>
                <p>This fort was built during Yadava period. According to the inscription on the third gate, Mohammed Adil Shah of Bijapur had repaired this fort on May 1656. Chhatrapati Shivaji Maharaj won the fort from the hands of Bandal-Deshmukh of Rohida in a close battle. The conflict resulted in the death of Krishnaji Bandal. After the battle, many officials along with Bajiprabhu Deshpande, a chief administrator of Bandals, were inducted into the Swarajya movement. Rohida was among the 23 forts chhatrapati Shivaji handed over to Mughals(to Aurangzeb Alamgir) during the Treaty of Purandar(1665). On 24 June 1670, this fort was again captured by chhatrapati Shivaji. The Kanhoji Jedhe had patronage over the entire Bhor state and half of the Rohida Fort along with some patches of land. Further Mughals captured this fort. This fort was under the control of Pantsachiv of Bhor State, until Indian independence.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">₹ 649.00 <span>1000.00</span> </div>
                <a href="#book" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="images/purandar.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Purandar </h3>
                <p>The oldest known reference to the Purandar dates back to the Yadava dynasty in the 11th century.[citation needed]
                    After the defeat of the Yadavas by the Persian invaders,[citation needed] the territory surrounding the fort fell into the hands of the Persians who further fortified the Purandar Fort in 1350 A.D. During the early rule of the Bijapur and Ahmednagar kings, The Purandar Fort was among the forts directly under the Government rule and was never entrusted to Jagirdars.[3]
                    Under the rule of the Berar Sultanate, the fort was besieged several times. To prevent the Purandar Fort from ever falling again, a sacrificial ritual was performed where a man and a woman were buried alive under one of the fort bastions to appease its patron deity.[4] Another ritual was soon performed where the king ordered a minister to bury a first-born son and his mother into the foundation of the bastion which was promptly done with a further offering of gold and bricks. When the bastion was finished, The minister, Yesaji Naik, was given possession of the Purandar Fort and the father of the sacrificed boy was rewarded with two villages.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">₹ 1199.00 <span>1500.00</span> </div>
                <a href="#book" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="images/sinhgad.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Sinhagad </h3>
                <p>The Sinhagad Fort was initially known as "Kondhana" after the sage Kaundinya. The Kaundinyeshwar temple coupled with the caves and carvings indicates that the fort had probably been built around two thousand years ago. It was seized by Muhammad bin Tughlaq from the Koli king Nag Naik in 1328 AD.
                    Shahaji Bhosale, as the commander of Ibrahim Adil Shah II, was entrusted with the control of the Pune region. His son Chatrapati Shivaji, refused to accept the Adilshahi and initiated the task of setting up Swarajya. Chatrapati Shivaji gained control of Kondana in 1647 by convincing Siddi Amber, the Adilshahi Sardar who controlled the fort, that he, the son of Shahaji Bhosale, could manage the fort's defenses optimally. Bapuji Mudgal Deshpande played a key role in this activity. Adil Shah jailed Siddi Amber for this treasonous act and schemed to get it back. He imprisoned Shahaji Bhosale for a concocted crime and informed Chatrapati Shivaji. In 1649, Adil Shah traded the fort for Shahaji's release. Shivaji recaptured it in 1656 again with the help of Bapuji Mudgal Deshpande who convinced the Fort commander by giving land in the Khed Shivapur village.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">₹ 499.00 <span>700.00</span> </div>
                <a href="#book" class="btn">book now</a>
            </div>
        </div>

        <div class="box">
            <img src="images/visapur.jpg" alt="">
            <div class="content">
                <h3> <i class="fas fa-map-marker-alt"></i> Visapur </h3>
                <p>It was built during 1713-1720 CE by Balaji Vishwanath, the first Peshwa of Maratha Empire.[1][2] Visapur fort was built much later than Lohagad but the histories of the two forts are closely linked.
                    In 1818, when reducing the Peshwa's forts, the strength of Lohagad and its fame as the treasury of the Maratha kingdom, caused the English to make special preparations for its attack. A detachment of 380 European and 800 native soldiers, with a battering train, summoned from Konkan, were joined by artillery from Chakan, and two other British battalions. On 4 March 1818, Visapur was attacked and occupied.
                    Making use of its higher elevation and proximity to Lohagad, the British troops set up their cannons on Visapur and bombarded Lohagad, forcing the Marathas to flee. Thus, in 1818, Lohagad-Visapur was taken over by the British in 1818 AD and placed under the command of a Colonel Prother.[4] Considering, the strategic importance of Visapur, both the north (Konkan) and the south (Deccan) gateways were blown up, and except a few huts, nothing was left standing.[3] In contrast, most of Lohagad fort is still intact.</p>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="far fa-star"></i>
                </div>
                <div class="price">₹ 1699.00 <span>2000.00</span> </div>
                <a href="#book" class="btn">book now</a>
            </div>
        </div>

    </div>

</section>

<!-- packages section ends -->

<!-- services section starts  -->

<section class="services" id="services">

    <h1 class="heading">
        <span>s</span>
        <span>e</span>
        <span>r</span>
        <span>v</span>
        <span>i</span>
        <span>c</span>
        <span>e</span>
        <span>s</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <i class="fas fa-hotel"></i>
            <h3>affordable hotels</h3>
            <p>hotel provides clean rooms that are safe and meet the basic needs of a guest. Extra amenities may be available, but for an extra cost</p>
        </div>
        <div class="box">
            <i class="fas fa-utensils"></i>
            <h3>food and drinks</h3>
            <p>Eating and drinking healthier makes a big difference to your body. we provide good food and drinks without extra charges</p>
        </div>
        <div class="box">
            <i class="fas fa-bullhorn"></i>
            <h3>safty guide</h3>
            <p>1)Don't Trek Alone
                2)Keep Your Trekking Essentials Handy
                3)Don't Rely Heavily on Mobile-Phones
                4)Don't Leave the Designated Trail
                5)Pack Light 6)Learn How to Survive an Animal Attack:</p>
        </div>
        <div class="box">
            <i class="fas fa-globe-asia"></i>
            <h3>around the world</h3>
            <p>Around maharashtra from east to west, or west to east, thus crossing all meridians. we sailed around the maharashtra.</p>
        </div>
        <div class="box">
            <i class="fas fa-plane"></i>
            <h3>fastest travel</h3>
            <p>You have been dreaming of a vacation for some time.Let us make your holidays dream come true with our unmatched services and expertise in travel.</p>
        </div>
        <div class="box">
            <i class="fas fa-hiking"></i>
            <h3>adventures</h3>
            <p>tourism involving travel to remote or exotic locations in order to take part in physically challenging outdoor activities.</p>
        </div>

    </div>

</section>

<!-- services section ends -->

<!-- gallery section starts  -->

<section class="gallery" id="gallery">

    <h1 class="heading">
        <span>g</span>
        <span>a</span>
        <span>l</span>
        <span>l</span>
        <span>e</span>
        <span>r</span>
        <span>y</span>
    </h1>

    <div class="box-container">

        <div class="box">
            <img src="images/g1.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>Always amazing to visit Sinhagad fort. Great place for walk, hiking, food, beautiful views and lovely people.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g2.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p> Formerly known as Murumdev, the fort was the capital of the Maratha Empire under the rule of Chatrapati Shivaji Maharaj.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g3.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>One of the closest forts from Pune city
                    An amazing fort with beautiful views all around
                    The fort is pretty huge spread on the hill</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g4.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>Beautiful trek to top of mountain. Awesome during monsoons. Good work done by grassroutes tying up with locals.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g5.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>This point commands a view of Shivaji maharaj's fort,.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g6.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>it's a wonderful place to visit with your family. It's a crowded place.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g7.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>It was awesome place and no word to express it, awesome to visit, The place is peace full and during night vision looks very nice.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g8.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>This all-day community festival features arts, crafts, food, beer, rides for the kids, and live entertainment.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>
        <div class="box">
            <img src="images/g09.jpg" alt="">
            <div class="content">
                <h3>amazing places</h3>
                <p>Very green and clean. This park is a must visit while in city. Overall maintained nicely and can spend some time here.</p>
                <a href="#" class="btn">see more</a>
            </div>
        </div>

    </div>

</section>

<!-- gallery section ends -->

<!-- review section starts  -->

<section class="review" id="review">

    <h1 class="heading">
        <span>r</span>
        <span>e</span>
        <span>v</span>
        <span>i</span>
        <span>e</span>
        <span>w</span>
    </h1>

    <div class="swiper-container review-slider">

        <div class="swiper-wrapper">

            <div class="swiper-slide">
                <div class="box">
                    <img src="images/ri1.jpg" alt="">
                    <h3>Aniket Gade</h3>
                    <p>the place was amazing and we made memorise with Vajir team</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="images/ri2.jpg" alt="">
                    <h3>Aniket Jadhav</h3>
                    <p>I searched ALOT of Indian trekking companies and something about this one really drew me in. It was first the fantastic communication and developing an experience individual to what I wanted or had time for. Later, during the trip, it became the amazing work ethic and attention to detail. I felt completely safe because that was always made priority before and during the trip. The sense of adventure and providing a true raw experience is clearly part of their mission. One of the best decisions of my life- to trek with Himalayan High!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>  
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="images/ri3.jpg" alt="">
                    <h3>Snehal Wadane</h3>
                    <p>It was a great experience.... With our trek leaders...Awesome places to go and enjoy.... mostly we had no worries....They were encouraging and patient with us......A must do Trek for All!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>
            <div class="swiper-slide">
                <div class="box">
                    <img src="images/ri4.jpg" alt="">
                    <h3>Sahil Narale</h3>
                    <p>It was my first ever trekking experience and choosing Vajir was my best decision. With such amazing organisation and people around you there was no chance of anything going wrong. The best specialty of himalayanhigh is the supportive and loving staff and trek leader and the food provide to you is always fresh and hot as of what u need in the cold breeze . If you want your trekking experience to be memorable , Vajir is your option!</p>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="far fa-star"></i>
                    </div>
                </div>
            </div>

        </div>

    </div>

</section>

<!-- review section ends -->

<!-- contact section starts  -->

<section class="contact" id="contact">
    
    <h1 class="heading">
        <span>c</span>
        <span>o</span>
        <span>n</span>
        <span>t</span>
        <span>a</span>
        <span>c</span>
        <span>t</span>
    </h1>

    <div class="row">

        <div class="image">
            <img src="images/contact-img.svg" alt="">
        </div>

        <form action="formData.php" method="post">
            <div class="inputBox">
                <input type="text" placeholder="name" name="n">
                <input type="email" placeholder="email" name="e">
            </div>
            <div class="inputBox">
                <input type="number" placeholder="number" name="p">
                <input type="text" placeholder="subject" name="s">
            </div>
            <textarea placeholder="message" id="" cols="30" rows="10" name="msg"></textarea>
            <input type="submit" class="btn" value="send message">
        </form>

    </div>
    
</section>

<!-- footer section  -->

<section class="footer">

    <div class="box-container">

        <div class="box">
            <h3>about us</h3>
            <p>About Us
                Established in 2021, "Trekking in India" is a subsidiary of Vajir Tours Pvt. Ltd. and is regarded as one of the most trusted Adventure Tour Operators in the country. We believe in the philosophy of wholeheartedly serving our customers and make travel fun, in the literal sense.</p>
        </div>
        <div class="box">
            <h3>branch locations</h3>
            <a href="#">Pune</a>
            <!-- <a href="#">Mumbai</a>
            <a href="#">Satara</a>
            <a href="#">Kolhapur</a> -->
        </div>
        <div class="box">
            <h3>quick links</h3>
            <a href="#home">home</a>
            <a href="#book">book</a>
            <a href="#packages">packages</a>
            <a href="#services">services</a>
            <a href="#gallery">gallery</a>
            <a href="#review">review</a>
            <a href="#contact">contact</a>
        </div>
        <div class="box">
            <h3>follow us</h3>
            <a href="#">facebook</a>
            <a href="https://www.instagram.com/invites/contact/?i=1x7n14ouy4r3v&utm_content=3dxesek">instagram</a>
            <a href="#">twitter</a>
            <a href="https://www.linkedin.com/in/akshay-gaikwad-3b618a208?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BWbDkbmZiQGqPPnphxanTng%3D%3D">linkedin</a>
        </div>

    </div>

    <h1 class="credit"> created by <span> Akshay Gaikwad </span> | all rights reserved! </h1>

</section>
<!-- custom js file link  -->
<script src="script.js"></script>

</body>
</html>


#css code
  
  
  
  :root{
  --orange:#3dcfe9;
}

*{
  font-family: 'Nunito', sans-serif;
  margin:0; padding:0;
  box-sizing: border-box;
  text-transform: capitalize;
  outline: none; border:none;
  text-decoration: none;
  transition: all .2s linear;
}

*::selection{
  background:var(--orange);
  color:#fff;
}

html{
  font-size: 62.5%;
  overflow-x: hidden;
  scroll-padding-top: 6rem;
  scroll-behavior: smooth;
}

section{
  padding:2rem 9%;
}

.heading{
  text-align: center;
  padding:2.5rem 0
}

.heading span{
  font-size: 3.5rem;
  background:rgba(207, 46, 162, 0.2);
  color:var(--orange);
  border-radius: .5rem;
  padding:.2rem 1rem;
}

.heading span.space{
  background:none;
}

.btn{
  display: inline-block;
  margin-top: 1rem;
  background:var(--orange);
  color:#fff;
  padding:.8rem 3rem;
  border:.2rem solid var(--orange);
  cursor: pointer;
  font-size: 1.7rem;
}

.btn:hover{
  background:rgba(215, 82, 16, 0.2);
  color:var(--orange);
}

header{
  position: fixed;
  top:0; left: 0; right:0;
  background:#333;
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding:2rem 9%;
}

header .logo{
  font-size: 2.5rem;
  font-weight: bolder;
  color:#fff;
  text-transform: uppercase;
}

header .logo span{
  color:var(--orange);
}

header .navbar a{
  color:#fff;
  font-size: 2rem;
  margin:0 .8rem;
}

header .navbar a:hover{
  color:var(--orange);
}

header .icons i{
  font-size: 2.5rem;
  color:#fff;
  cursor: pointer;
  margin-right: 2rem;
}

header .icons i:hover{
  color:var(--orange);
}

header .search-bar-container{
  position: absolute;
  top:100%; left: 0; right:0;
  padding:1.5rem 2rem;
  background:rgb(115, 116, 111);
  border-top: .1rem solid rgba(255,255,255,.2);
  display: flex;
  align-items: center;
  z-index: 1001;
  clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
}

header .search-bar-container.active{
  clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
}

header .search-bar-container #search-bar{
  width:100%;
  padding:1rem;
  text-transform: none;
  color:#333;
  font-size: 1.7rem;
  border-radius: .5rem;
}

header .search-bar-container label{
  color:#fff;
  cursor: pointer;
  font-size: 3rem;
  margin-left: 1.5rem;
}

header .search-bar-container label:hover{
  color:var(--orange);
}

.login-form-container{
  position: fixed;
  top:-120%; left: 0;
  z-index: 10000;
  min-height: 100vh;
  width:100%;
  background:rgba(0,0,0,.7);
  display: flex;
  align-items: center;
  justify-content: center;
}

.login-form-container form{
  margin:2rem;
  padding:1.5rem 2rem;
  border-radius: .5rem;
  background:#fff;
  width:50rem;
}

.login-form-container form h3{
  font-size: 3rem;
  color:#444;
  text-transform: uppercase;
  text-align: center;
  padding:1rem 0;
}

.login-form-container form .box{
  width:100%;
  padding:1rem;
  font-size: 1.7rem;
  color:#333;
  margin:.6rem 0;
  border:.1rem solid rgba(0,0,0,.3);
  text-transform: none;

}

.login-form-container form .box:focus{
  border-color: var(--orange);;
}

.login-form-container form #remember{
  margin:2rem 0;
}

.login-form-container form label{
  font-size: 1.5rem;
}

.login-form-container form .btn{
  display: block;
  width:100%;
}

.login-form-container form p{
  padding:.5rem 0;
  font-size: 1.5rem;
  color:#666;
}

.login-form-container form p a{
  color:var(--orange);
}

.login-form-container form p a:hover{
  color:#333;
  text-decoration: underline;
}

.login-form-container #form-close{
  position: absolute;
  top:2rem; right:3rem;
  font-size: 5rem;
  color:#fff;
  cursor: pointer;
}

#menu-bar{
  color:#fff;
  border:.1rem solid #fff;
  border-radius: .5rem;
  font-size: 3rem;
  padding:.5rem 1.2rem;
  cursor: pointer;
  display: none;
}

.home{
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-flow: column;
  position: relative;
  z-index: 0;
}

.home .content{
  text-align: center;
}

.home .content h3{
  font-size: 4.5rem;
  color:#fff;
  text-transform: uppercase;
  text-shadow: 0 .3rem .5rem rgba(0,0,0,.1);
}

.home .content p{
  font-size: 2.5rem;
  color:#fff;
  padding:.5rem 0;
}

.home .video-container video{
  position: absolute;
  top:0; left: 0;
  z-index: -1;
  height: 100%;
  width:100%;
  object-fit: cover;
}

.home .controls{
  padding:1rem;
  border-radius: 5rem;
  background:rgba(0,0,0,.7);
  position: relative;
  top:10rem;
}

.home .controls .vid-btn{
  height:2rem;
  width:2rem;
  display: inline-block;
  border-radius: 50%;
  background:#fff;
  cursor: pointer;
  margin:0 .5rem;
}

.home .controls .vid-btn.active{
  background:var(--orange);
}

.book .row{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
  align-items: center;
}

.book .row .image{
  flex:1 1 40rem;
}

.book .row .image img{
  width:100%;
}

.book .row form{
  flex:1 1 40rem;
  padding:2rem;
  box-shadow: 0 1rem 2rem rgba(0,0,0,.1);
  border-radius: .5rem;
}

.book .row form .inputBox{
  padding:.5rem 0;
}

.book .row form .inputBox input{
  width:100%;
  padding:1rem;
  border:.1rem solid rgba(0,0,0,.1);
  font-size: 1.7rem;
  color:#333;
  text-transform: none;
}

.book .row form .inputBox h3{
  font-size: 2rem;
  padding:1rem 0;
  color:#666;
}

.packages .box-container{
  display: flex;
  flex-wrap: wrap;
  gap:2rem;
}

.packages .box-container .box{
  flex:1 1 30rem;
  border-radius: .5rem;
  overflow: hidden;
  box-shadow: 0 1rem 2rem rgba(0,0,0,.1);
}

.packages .box-container .box img{
  height: 25rem;
  width:100%;
  object-fit: cover;
}

.packages .box-container .box .content{
  padding:2rem;
}

.packages .box-container .box .content h3{
  font-size:2rem;
  color:#333;
}

.packages .box-container .box .content h3 i{
  color:var(--orange);
}

.packages .box-container .box .content p{
  font-size:1.7rem;
  color:#666;
  padding:1rem 0;
}

.packages .box-container .box .content .stars i{
  font-size:1.7rem;
  color:var(--orange);
}

.packages .box-container .box .content .price{
  font-size: 2rem;
  color:#333;
  padding-top: 1rem;
}

.packages .box-container .box .content .price span{
  color:#666;
  font-size: 1.5rem;
  text-decoration: line-through;
}

.services .box-container{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
}

.services .box-container .box{
  flex: 1 1 30rem;
  border-radius: .5rem;
  padding:1rem;
  text-align: center;
}

.services .box-container .box i{
  padding:1rem;
  font-size: 5rem;
  color:var(--orange);
}

.services .box-container .box h3{
  font-size: 2.5rem;
  color:#333;
}

.services .box-container .box p{
  font-size: 1.5rem;
  color:#666;
  padding:1rem 0;
}

.services .box-container .box:hover{
  box-shadow: 0 1rem 2rem rgba(0,0,0,.1);
}

.gallery .box-container{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
}

.gallery .box-container .box{
  overflow: hidden;
  box-shadow: 0 1rem 2rem rgba(0,0,0,.1);
  border:1rem solid #fff;
  border-radius: .5rem;
  flex:1 1 30rem;
  height: 25rem;
  position: relative;
}

.gallery .box-container .box img{
  height: 100%;
  width:100%;
  object-fit: cover;
}

.gallery .box-container .box .content{
  position: absolute;
  top:-100%; left:0;
  height: 100%;
  width:100%;
  text-align: center;
  background:rgba(0,0,0,.7);
  padding:2rem;
  padding-top: 5rem;
}

.gallery .box-container .box:hover .content{
  top:0;
}

.gallery .box-container .box .content h3{
  font-size: 2.5rem;
  color:var(--orange);
}

.gallery .box-container .box .content p{
  font-size: 1.5rem;
  color:#eee;
  padding:.5rem 0;
}

.review .review-slider{
  padding-bottom: 2rem;
}

.review .box{
  padding:2rem;
  text-align: center;
  box-shadow: 0 1rem 2rem rgba(0,0,0,.1);
  border-radius: .5rem;
}

.review .box img{
  height:13rem;
  width:13rem;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}

.review .box h3{
  color:#333;
  font-size: 2.5rem;
}

.review .box p{
  color:#666;
  font-size: 1.5rem;
  padding:1rem 0;
}

.review .box .stars i{
  color:var(--orange);
  font-size: 1.7rem;
}

.contact .row{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
  align-items: center;
}

.contact .row .image{
  flex:1 1 35rem;
}

.contact .row .image img{
  width:100%;
}

.contact .row form{
  flex:1 1 50rem;
  padding:2rem;
  box-shadow: 0 1rem 2rem rgba(0,0,0,.1);
  border-radius: .5rem;
}

.contact .row form .inputBox{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.contact .row form .inputBox input, .contact .row form textarea{
  width:49%;
  margin:1rem 0;
  padding:1rem;
  font-size: 1.7rem;
  color:#333;
  background:#f7f7f7;
  text-transform: none;
}

.contact .row form textarea{
  height: 15rem;
  resize: none;
  width:100%;
}

.brand-container{
  text-align: center;
}

.footer{
  background:#333;
}

.footer .box-container{
  display: flex;
  flex-wrap: wrap;
  gap:1.5rem;
}

.footer .box-container .box{
  padding:1rem 0;
  flex:1 1 25rem;
}

.footer .box-container .box h3{
  font-size: 2.5rem;
  padding:.7rem 0;
  color:#fff;
}

.footer .box-container .box p{
  font-size: 1.5rem;
  padding:.7rem 0;
  color:#eee;
}

.footer .box-container .box a{
  display: block;
  font-size: 1.5rem;
  padding:.7rem 0;
  color:#eee;
}

.footer .box-container .box a:hover{
  color:var(--orange);
  text-decoration: underline;
}

.footer .credit{
  text-align: center;
  padding:2rem 1rem;
  margin-top: 1rem;
  font-size: 2rem;
  font-weight: normal;
  color:#fff;
  border-top: .1rem solid rgba(255,255,255,.2);
}

.footer .credit span{
  color:var(--orange);
}
















/* media queries  */

@media (max-width:1200px){

  html{
    font-size: 55%;
  }

}

@media (max-width:991px){

  header{
    padding:2rem;
  }

  section{
    padding:2rem;
  }

}

@media (max-width:768px){

  #menu-bar{
    display: initial;
  }

  header .navbar{
    position: absolute;
    top:100%; right:0; left: 0;
    background: #333;
    border-top: .1rem solid rgba(255,255,255,.2);
    padding:1rem 2rem;
    clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
  }

  header .navbar.active{
    clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
  }

  header .navbar a{
    display: block;
    border-radius: .5rem;
    padding:1.5rem;
    margin:1.5rem 0;    
    background:#222;
  }

}

@media (max-width:450px){

  html{
    font-size: 50%;
  }

  .heading span{
    font-size: 2.5rem;
  }

  .contact .row form .inputBox input{
    width:100%;
  }

}
  
  
  
  #Javascript 
  
  
  
  let searchBtn = document.querySelector('#search-btn');
let searchBar = document.querySelector('.search-bar-container');
let formBtn = document.querySelector('#login-btn');
let loginForm = document.querySelector('.login-form-container');
let formClose = document.querySelector('#form-close');
let menu = document.querySelector('#menu-bar');
let navbar = document.querySelector('.navbar');
let videoBtn = document.querySelectorAll('.vid-btn');

window.onscroll = () =>{
    searchBtn.classList.remove('fa-times');
    searchBar.classList.remove('active');
    menu.classList.remove('fa-times');
    navbar.classList.remove('active');
    loginForm.classList.remove('active');
}

menu.addEventListener('click', () =>{
    menu.classList.toggle('fa-times');
    navbar.classList.toggle('active');
});

searchBtn.addEventListener('click', () =>{
    searchBtn.classList.toggle('fa-times');
    searchBar.classList.toggle('active');
});

formBtn.addEventListener('click', () =>{
    loginForm.classList.add('active');
});

formClose.addEventListener('click', () =>{
    loginForm.classList.remove('active');
});

videoBtn.forEach(btn =>{
    btn.addEventListener('click', ()=>{
        document.querySelector('.controls .active').classList.remove('active');
        btn.classList.add('active');
        let src = btn.getAttribute('data-src');
        document.querySelector('#video-slider').src = src;
    });
});

var swiper = new Swiper(".review-slider", {
    spaceBetween: 20,
    loop:true,
    autoplay: {
        delay: 2500,
        disableOnInteraction: false,
    },
    breakpoints: {
        640: {
          slidesPerView: 1,
        },
        768: {
          slidesPerView: 2,
        },
        1024: {
          slidesPerView: 3,
        },
    },
});

var swiper = new Swiper(".brand-slider", {
    spaceBetween: 20,
    loop:true,
    autoplay: {
        delay: 2500,
        disableOnInteraction: false,
    },
    breakpoints: {
        450: {
          slidesPerView: 2,
        },
        768: {
          slidesPerView: 3,
        },
        991: {
          slidesPerView: 4,
        },
        1200: {
          slidesPerView: 5,
        },
      },
});


  
