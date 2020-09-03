# TITLE
HORISEON WEBSITE

## CONTENTS
* [OVERVIEW]
* [WORK ACOMPLISHED]
* [SUMMARY]


## OVERVIEW 
I was tasked with making a client's website more user accessable.
This was accomplished through multiple steps.

## WORK ACOMPLISHED
First, I organized their html in the index.html file.
I added descriptions above each major part of the code corresponding to the site.
An example would be in line 12 and 13 of index.html: 
<!-- Top left logo -->
    <h1>Hori<span class="seo">seo</span>n</h1>

Second, I replaced some elements with semantic html.
An example of this would be the nav section. Originally, the nav container was a <div>. 
After changing the <div> container to <nav> I had to change the css element to nav as well.
I made multiple changes like this. The changes are a huge step towards improving accessability.
    <nav>
        <ul>
            <li>
                <a href="#search-engine-optimization">Search Engine Optimization</a>
            </li>
            <li>
                <a href="#online-reputation-management">Online Reputation Management</a>
            </li>
            <li>
                <a href="#social-media-marketing">Social Media Marketing</a>
            </li>
        </ul>
    </nav>

Third, I noticed a link in the nav bar was inoperative.
Search engine optimization did not function as designed.
A quick fix for me. after comparing the working links to the inoperative, I noticed the SEO element was missing an "ID" attribute.
    <div id="search-engine-optimization" class="search-engine-optimization">

Fourth, I noticed none of the image elements contained "alt" tags. With accessability in mind, alt tags are necessary. I corrected each image element. 
    alt="search engine optimization"

Fifth, I organized the .css file to correspond in order with the .html file.
This was a longer process, I would list examples but I think it's self-explainatory.

## SUMMARY
In conclusion, I refactored this client's site to be more accessible.
Through 5 steps;
I labelled the containers in the html,
I added semantic html,
fixed inoperative links,
added "alt" tags,
and restructured the .css file to correspond with the html.





