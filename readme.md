This is a web map showing the Airbnbs within Nashville TN. It is based off
our previous exercise, I felt it provided a good groundwork to base my map
off of. It honestly did help a lot having a template to create the project
but not as much as I thought. I got my data from InsideAirbnb, they have
a lot of valuable information on there site. I took the data provided on
InsideAirbnb for the Rental unit information as a .csv file and loaded it
into qgis. I got my map boundaries from Nashville Open Data website, they
are divided into districts. I then loaded this into qgis and used the count
points in polygon tool. I then exported this a geojson file. I imported this
into my new project file and worked from there. I was going to use number
of bedrooms instead of unit type, but I kept having issues when I would add
more sections of code, and the colors would all turn black. I figured a simple
working map is better than a more complex one that doesn't work. The cloropleth
section I changed around a lot of the values, because there are so many more
airbnbs in Nashville than in Asheville which is suprising. It will take a
long time to load because of this so be prepared for that, I believe there is
6300 Airbnbs in the city. I was going to orginally do nashville and public
water sources, but I kept running into issues with missing pieces of information
specfically data lacking cordinates, and instead having addresses, which would
be fine if I could use a batch geo-coder, but it seems you have to pay for
most of them.
