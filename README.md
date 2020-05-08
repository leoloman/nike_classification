# nike_classification

Aim:
To create a neural network image classifier of nike trainers.

Steps:
- Scrape Stock X's site for all links to nike trainers hosted on their site
- Iterate over all the links getting all the required information for each shoe
- Download 6 images per shoe and have them moved into their relevant folder structure
- Construct Neural network

Scrape the Nike Links ()

In this notebook I scrape down all the Nike links from Stock X's website, I utilise Selenium as Stock X uses Javascript and you cant use requests and beautiful soup without accessing the site with Selenium first.

Information scrape:

I iterate over each link pulling down information about the shoe:

Category 1, Category 2, Colourway, Image of the shoe facing right, Retail Price, Release Date, Stock X Name, Style Code,

I found that the structure of the shoe image links are all number based and to get the angles of the shoe that I wanted I could just later the first image's hyperlink.


Link to the original unmodified image set, [here](https://drive.google.com/open?id=1TJoR2zJ3yjGUH0NYz671-QeGWbbF2YXo) 

Link to the trained neural network h5 file, [here](https://drive.google.com/open?id=1-37qj9cSdAva4DqnErpNp1MeUJzurUqU)
