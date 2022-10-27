# <Challenge-02>

## Description

Took pre exsisting code and cleaned up sematics in the html and css files to make it earier to read more accessible

I changed this section of code

         <figcaption class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </figcaption>
    <div class="benefits">
        <div class="benefit-lead">


To this section
        <figure class="hero"></figure>
    <!--Added figure element-->
    <main class="content">
    <!--Added main element-->
        <section class="search-engine-optimization">
        <!--Added section element-->
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
        <section id="online-reputation-management" class="online-reputation-management">
        <!--Added section element-->
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>
        <section id="social-media-marketing" class="social-media-marketing">
        <!--Added section element-->
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </section>
    </main>
    
 
 /* renamed items to sidebar in html and reduced excessive amount of selector editors*/
.sidebar {
    margin-bottom: 32px;
    color: #ffffff;
}

.sidebar h3 {
    margin-bottom: 10px;
    text-align: center;
}

.sidebar img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}



header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}
/*Changed .header from class selector to element selector*/
header h1 {
    display: inline-block;
    font-size: 48px;
    color: #d9dcd6;
}

/*Changed .header from class selector to element selector*/
header nav {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}
/* deleted unnecessary section
header nav ul 
    list-style-type: none;
*/

## links




