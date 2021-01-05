# Fire Track

This is a small React app I created with the help of a tutorial. It utilizes React to power the page and is component based. There are components for the Map being pulled in from Google Maps API, to create location icons, to utilize the data from the NASA EONET API and filter for wildfires once the data is gathered, and then to mark them on the existing map via coordinate data provided in the NASA data pull.

You can click any of the fire icons and recieve it's EONET ID number and the title of the fire provided by the EONET system.

I also implemented the early loading screen and dial gif to deal with any possible load times created by the async/await interaction while REACT grabs the data from NASA.
