# Plan Of Action

- create Wireframe
    draw.io to create a wireframe 

- set up the base HTML structure 
    include html, head, body and script header in the index.html
    hello world in the index.js to check if it's running

- Import Google maps into the window (index.html page)
    https://developers.google.com/maps/solutions/store-locator/clothing-store-locator (get snipped of code)
    made changes to style.cc to add width and height
    index.js file to add the location function

- Add the text store locator
    you can only have one ID in the html file. but can have multiple classes
    create a div for store locator 

- Add search/input box
    https://fontawesome.com/ to find the search icon
    create a div for the search bar

- Add store list container (white box under the search bar contains the list of stores)
    stores-list-container = is the white box 
    stores-list = is the actual list of the stores
    
- Add individual store container and Style the individual store item in the store list
    margin is the above the box and padding-right/left is within the box 
    for the horizontal line you can use border botton or create a tag <hr> 
    to create a line break you can use tag <br /> wherrever you want a line break
    line break: if you span tag in the style css to have create a diplay: block

- Show all the stores in the stores list based on real world data
    <script src="js/store-data.js"></script>
    <script src="js/index.js"></script>
    store-data.js comes first then index.js b/c we need to see the store data first(otherwise you will not see it)

- Show the marker on real world store data
    https://developers.google.com/maps/solutions/store-locator/clothing-store-locator (snip of codes from here)

- Show the info window 
    red marks on the maps are the info windows

- style the marker info window

- Show the info window when you click on the individual store 
    console.log(); -> console log everything to check you logic and see if it works
    create function setOnClickListener()

- allow a user to search for the stores in a zip code 
    create function searchStores()

- Add a beautiful transtition on the hover of the individual store 
    create a div store-container-background