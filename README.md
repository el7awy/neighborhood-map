## Neighborhood Map (React)

 a single page application featuring a map of Alexandria neighborhood . this map including highlighted locations, third-party data from wikipedia API about those locations and various ways to browse the content.
 
 see the demo at https://neighborhood-map-reactjs.herokuapp.com/
 
 ## Installition
 
 1. download the files ,Click `"Clone in Desktop" / "Download ZIP"`.
 2. extract the files.
 3. Change to root directory.
 4. Install dependencies: `npm install`.
 5. Start the app: `npm start`(will open the browser on http://localhost:3000).
    **notice :** the service worker will only cache the app when production mode running.
 
 ## Requirments
 
 should be internet connection to load Google Map API and information about the places from wikipedia Api.
 
 ## Production Mode
 
 to run the app in production mode open command window at the root directory ,then type `npm run build`
 
 ## Wikipedia API
 
 [wikipedia api](https://www.mediawiki.org/wiki/API:Main_page) used in the app to get information a history of the place .
 
 ## Google Maps API
 
 [google maps api](https://developers.google.com/maps/documentation/) used in the app to load the Map and markers on places.
