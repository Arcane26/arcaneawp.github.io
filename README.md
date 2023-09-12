# EDGGG : A Catalog for Green Gas Giants in Elite Dangerous
*EDGGG* is a passion project of mine, with a goal of organizing and cataloging all of the known 'Green Gas Giants', a rare bugged planet subtype in the videogame Elite: Dangerous. So far there are many spreadsheets that are documenting these objects. My mission is to make
the data (and knowledge about them in general) more accessible to curious minds, displaying all necessary information about them in an orderly (and visually attractive) manner.

I am currently teaching myself web development, and as I progress through my courses and become more comfortable with different concepts, I will attempt to improve the page and make it look more appealing, reactive and interactive.
## Features
The main flow of the site is going to involve a 'Search' function that will give the user the ability to quickly search for a planet through 'Known Classes'. Later on will be able to type a query into a text field to fetch known planets, or sort them based on Discovery
Date, Region, Distance to Sol, K10-Type Anomalies present, or Alphabetically by procedural-generation name. After a search, a list of planets matching the resulting query will be displayed, along with their discovery date and discovering CMDR, allowing the user to click on one. This will take them to that planet's 
*Information Page*, where all information about that planet will be available.

Ideally when this site is completed, it will be fully automated, detecting a new GGG codex entry, giving it a GGG#, creating an Information Page, as well as submitting it into its appropriate Class Category. A 'Missing' Image
will be displayed until a photo, taken in correct format, is procured.

### Other Add-ons
Other features that are or will be included in the future are:
* New GGGs This Year
* Total GGGs Known Counter
* GGGs Discovered On This Day

#### New GGGs This Year
This section will be located on the site's index.html landing page. It will be an almost-fully automated process, detecting new GGGs discovered via EDDN and adding it to this portion of the webpage. At the beginning of each year, this section
will reset to be empty for new ones to be added.

#### Total GGGs Known Counter
This will be a separate counter, located either in the header or somewhere near the top of main in index.html. It will increase by one with every new GGG added to the site.

#### GGGs Discovered On This Day
A separate section that will take the date on the user's computer and see if any of the GGGs on the database match the month/day, then display them. They will be clickable and will take the user to that specific GGG page.
## How To Use (Currently)
Upon landing at EDGGG's index.html page, there is a 'Search' section and a 'New GGGs This Year' section, currently for 3309. 

### Search
All known GGG Classes are located here, which when clicked will take you to that class' results page, where all GGGs of that class will be shown. Clicking any of those planets will take you to its corresponding Info Page, however
**at the current time, only one page works** Class III -> Byoomao LY-G d11-9374 A 4. The page layout is still undergoing design changes.

### GGGs Discovered This Year
GGGs found during the in-game year of 3309 will show up here. Only one works.

### Nav Bar
The Nav Bar is currently present across the entire site. Clicking 'About' will in the future bring you to an informational about what exactly these planets are, their history, as well as how to use the site. Clicking 'Search' returns you to index.html to the
'Search' area for classes. Clicking 'New This Year' will bring you to the bottom of index.html where new GGGs are listed.

The nav bar might not be included in the future.

## Technologies
Currently EDGGG is not fully interactive, only using HTML and vanilla CSS.



