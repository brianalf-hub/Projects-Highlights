# Data-science-portfolio

Welcome to my professional data science portfolio. My name is Brian Alfaro. As I am typing this text, I am still a PhD candidate at the University of New Mexico (UNM, Albuquerque), but if you are reading this a couple of months from my first addition, then I may already be holding my doctorate in plant ecological genetics. While my expertise is in experimental plant biology, throughout my career in graduate school I was/am involved in three academic big data projects in our department. <br />

<br />
<br />
<br />
<br />
<br />

<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/70289096/91906759-f5eca480-ec65-11ea-84bd-383c1be4b22c.png">
</p>

### Background. We examined how the association of oceanic environments and animal physiology interact to shape global patterns of biodiversity in our oceans. For this project, I mined and cleaned the data and was in charge of geographic information system (GIS) analysis that used more than 1 million data points (Grady et al. 2019, Science). 
### Results. The pattern of marine predator diversity is opposite the pattern of animals in land. In terrestrial environments, the highest diversity is in the tropics, while for marine predators the highest amount of species richness is in the polar regions. This pattern, while driven by environmental factors, is largely due to the physiology of marine predators and prey. In cold waters the capture of cold-blooded prey is easier, so warm-blooded predators tend to swarm polar regions. 

### Grady, J. M., B. S. Maitner, A. S. Winter, K. Kaschner, D. P. Tittensor, S. Record, F. A. Smith, A. M. Wilson, A. I. Dell, P. L. Zarnetske, H. J. Wearing, B. Alfaro, J. H. Brown. 2018. Metabolic asymmetry and the global diversity of marine predators. Science.
<br />
<br />
<br />
<br />
<br />

<p align="center">
  <img width="600" height="500" src="https://user-images.githubusercontent.com/70289096/91906991-4b28b600-ec66-11ea-9a9d-c1fbbe25a473.png">
</p>

### Background. Second to anthropogenic habitat degradation, invasive plants are a major factor for loss of global biodiversity. I used vegetation survey data collected by the U.S. Geological Survey from 1997 to 2007, and climate data from WorldClim (https://www.worldclim.org/data/worldclim21.html) to identify and predict climatic factors that affect the diversity of invasive plants in the southwestern United States. To combine the vegetation data (vector) with environmental data (raster), I used QGIS (Python) and R to extract and combine these two data sets. Then, I used a spatially-filtered model selection of climatic and anthropogenic variables via a maximum likelihood ratio approach, and to run Bayesian spatial modeling to create a GIS map prediction of annual and perennial invasive plants. 
### Results. I determined that the highest-ranked model was precipitation for annuals, and temperature for perennials. The next step is for me to rasterize the GIS model and then extract values to train a machine learning regression model to predict how annual and perennial invasive plants will spead several decades from our current time. 

<br />
<br />
<br />
<br />
<br />

<p align="center">
  <img width="900" height="350" src="https://user-images.githubusercontent.com/70289096/91903869-30a00e00-ec61-11ea-92ec-8b0fb9c5512e.png">
</p>

### Background. Agricultural crop yields are projected to become insufficient in the face of increasing world population and rapid global changes that include environmental and climatic factors. To determine how rapidly changing climate variation will affect canola oil yields, I used georeferenced USDA seed accession data to calculate regional averages of oil yields and climate data from WorldClim (https://www.worldclim.org/data/worldclim21.html). I then used the GIS capabilities of R to 1) perform a spatially-filtered model selection of climatic variables via a maximum likelihood ratio approach, and to 2) perform Bayesian spatial modeling to create a GIS map prediction of global oil yields. 
### Results. We found that mean annual temperature and seasonal temperature variation strongly affect canola yield when all species are pooled, but when projected to a predictive map, the hot spots of oil abundance (flame yellow in the figure above) coincides to regions with contrasting climates. Separate analyses (not shown) indicate that yield in different species respond differently to temperature variables, so I will use the predicted database from this GIS model to train regression models and use machine learning to predict how canola oil yield will respond to different future climate change scenarios. 


