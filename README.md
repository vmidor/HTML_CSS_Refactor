# HTML_CSS_Refactor



In Index.html file was able to identify a broken code in "content" class. It was missing "id" description, causing an issue when clicking the button. Please see example below:

div class="content-name" FIXED WITH div id="search-engine-optimization" class="content-name"

CSS file: in this cascading style sheets we will find how we can use as less criterias to apply to as many blocks.

Was able to refactor the code by merging 3 classes under one with a generic name keeping the same requirements 
In the example below "search-engine-optimization", "online-reputation-management" and "social-media-marketing" were replaced by “content-name” class:

.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

          Replaced by:

.content-name {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

Similar to the example above was able to merge "img" and "h2" as below:

.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

          Replaced by:

.content-name img {
    max-height: 200px;
    margin-bottom: 20px;
    font-size: 36px;
}

Please see the style.css for more details.