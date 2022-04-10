# week1homework

In the HTML code, attributes were missing for <img>. 


In CSS, cleaned up things that didn't have to be repeated. 

Things that were deleted and combined:

1. 
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}
.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

turned into... 

.benefit-lead, 
.benefit-brand,
.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

2. 
.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}
was shortened to...

h3 {
    margin-bottom: 10px;
    text-align: center;
}

3. 
.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
was shortened to... 
.benefits img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

4.
.search-engine-optimization, {
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
was shortened by adding all the classes into one line... 
.search-engine-optimization,
.online-reputation-management,
.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

5.
.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}
was shortened by using content h2... 
.content h2 {
    margin-bottom: 20px;
    font-size: 36px;
}