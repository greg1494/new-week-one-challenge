<index.html>

Comments that were added include;

<!-- Header -->
<!-- Main Content -->
<!-- Additional Content -->
<!-- Footer -->

Changed the <div> for the <header>
Changed the <div> for a <nav>
Added meetingMainImage to the header section

In the main content; added a <main> tag to identify the group
Changed the class name for maninContent in the html and css
Changed the search-engine-optimization from a class to an id
Changed the online-reputation-management class/rules in CSS to an id
Changed the social-medi-marketing class/rules in CSS to an id
Added and "alt" to each img with a description
Removed the </img>

Added an <aside> tag to replace the benefits <div> tag
Changed the benefit-lead class to an id
Changed the benefit-cost class to an id
Changed the benefit-brand class to an id 


Added a <footer>


<css>

I wanted to provide rules that would simplify the css. These rules were only updated and were not deleted from the original css. 

Updated the <div> for a <nav> in the CSS
Updated .header nav CSS rule

Rules that were simplified: 

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}