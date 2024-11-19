# Exoscope

## Team NOBHOYAN:
# "N"
afiul Haque - Team Leader, Front-end Developer|
Shams Khan 
# "O"
mik - Front-end Developer|
# "B"
ayezid Bostami - Data Analyst|
# "H"
asib Khan - Back-end Developer|
Hritom Sarker 
# "O"
yon - Researcher|
# "Yan"
na Lorraine D. Tenorio - Designer

## About
We are a bunch of high-schoolers working hard to show you the starry-night in an alien planet.
Our team developed ExoScope, a scientifically accurate immersive web application designed to explore the night skies of distant exoplanets. The app offers two main features: the "Hopping" page, where users can navigate between the ExoHosts, i.e., the host systems of the exoplanets, and the "Planetarium" page, which allows them to view the sky as seen from an exoplanet’s surface. Here, users can draw constellations, name them, and export their sky maps as images or downloadable files. This interactive experience achieves the core objectives of the challenge while encouraging creativity. To enrich the experience, our app has some additional features that sets us apart. The users can analyze the stars in a specific region of the sky using a built-in data analysis tool, which enables them to plot and compare astronomical data, offering a taste of real scientific research. We also introduced "TaraBhai," a chatbot designed to assist users of all ages and backgrounds, ensuring that our app is both educational and engaging.

# Project Description
### HOPPING PAGE
Our Web App features two main sections: the Hopping page and the Exosky page. The Hopping page presents a 3D point cloud of 4,302 ExoHosts—stars that host exoplanets—using data from NASA’s Exoplanet Archive. These stars are plotted in 3D space based on their right ascension, declination, and parallax. Star sizes are determined by their radius, while colors are accurately mapped using temperature and BV index, ensuring a realistic and scientifically accurate visualization. Users can freely navigate through this stellar landscape, or search for specific stars using an intuitive search bar. Each star also comes with informative pop-ups, offering fascinating details when clicked.

Hopping Page with ExoHosts and orbiting Exoplanets

In addition to the stars, exoplanets orbiting these ExoHosts are rendered with custom textures for visual appeal. These planets are modeled using data such as radius, eccentricity, and semimajor axis, ensuring an immersive experience. Similar to the stars, users can click on exoplanets to access detailed information.

### EXOSKY PAGE

By double-clicking any exohost, users are seamlessly transported to the Planetarium page, where they can observe the night sky as it appears from the surface of that star's exoplanets. Utilizing data from the Gaia Catalogue and custom algorithms, we’ve ensured that star positions, sizes, and brightness are scientifically accurate. Users can zoom in and out for a closer look, manually set the planet's pole orientation, and access a range of tools to enhance their exploration.

The Tools menu includes options like:

Draw Constellation mode: Create and name custom constellations.
Drag & Research mode: Generate useful graphs, such as the HR Diagram, from selected star regions in the sky.
Save as Image: Capture stunning 360-degree panoramic shots.
Export as PDF: Create detailed sky charts for further exploration.
To make the experience more engaging, we’ve also integrated an AI chatbot called TaraBhai (or StarBro), designed to assist users of all ages and backgrounds, making the app accessible and educational for everyone.

## OUR AIM
Our goal is to spark curiosity and cultivate a deeper appreciation for astronomy by making space exploration more accessible. Growing up in countries where telescopes are a luxury and light pollution often obscures the beauty of the night sky, WebApps like Stellarium have been invaluable in fueling our fascination with the cosmos. We wanted to take that experience a step further by offering curious high school students like ourselves the chance to explore not only our own planet’s starry nights but also the skies of thousands of exoplanets. By allowing users to create their own constellations in these distant worlds, we aim to make the experience both educational and personal. If our project inspires even one person to explore the vast potential of the universe, we will consider all our efforts a success.

## Tools We Used
In building the WebApp, we used HTML, CSS, Bootstrap and JavaScript, with a particular focus on the Three.js library to render the stars and planets in both the Hopping page and the interactive Planetarium. 

For our chatbot, TaraBhai, we integrated Google Gemini's API to enhance user interaction. 

We used NASA Exoplanets Archive for exoplanet data. We processed the data using Python. Astroquery module was used to get Gaia data for each ExoHost. The data was processed in Google Colab on a Google Cloud Compute Engine. 

# Data Generation
1. GAIA Dataset
