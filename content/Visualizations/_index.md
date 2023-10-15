---
title: "Visualizations"
featured_image: '/images/cleavage.jpg'
---

## Interactive visualizations
I've recently been using ObservableHQ to create interactive data visualizations.

### Solar, wind, and hydro power plants in California

Here's a visualization of the net productivity of different power plants in California. The background map is a Voronoi plot, which partitions the map into regions closest to each power plant. Each solar, wind, and hydro power plant appears as a dot, and by toggling between the different options, you can explore how different types of plants are distributed throughout the state. The date slider allows you to explore the variation in the plant's productivity over time: dot size and colour scales to net productivity. Can you notice any seasonal variations?

<iframe width="100%" height="894" frameborder="0"
  src="https://observablehq.com/embed/2126681278699f29@494?cells=viewof+type_str%2Cviewof+date%2Ccolorbar%2Cchart"></iframe>

Here's the same visualization, made in Tableau:

<div class='tableauPlaceholder' id='viz1697243431393' style='position: relative'><noscript><a href='#'><img alt='NetMWh - August 2021 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CA&#47;CA_plants&#47;NetMWh&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CA_plants&#47;NetMWh' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;CA&#47;CA_plants&#47;NetMWh&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1697243431393');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


### BART ridership
Here's an animated map I made using monthly BART ridership data from 2018 onwards. Each dot is a BART station. The size represents the ridership that month, the color represents rate of change of ridership (warmer colors = increasing ridership, cooler colors = decreasing ridership). Where are the stations that show the most change located? What's going on there? (Note that each station is normalised by subtracting its mean and dividing by its standard deviation so that stations with vastly different ridership can still be compared).

<figure>
<iframe width="100%" height="734" frameborder="0" src="https://observablehq.com/embed/0e081d57afa9e7b2?cells=viewof+date%2Cmap"></iframe>
<figcaption>Data from (https://www.bart.gov/about/reports/ridership)<\figcaption>
<\figure>


## Oklahoma Wastewater Injection and Earthquakes

Wastewater from fracking is toxic enough that most states will not allow it to be stored or disposed of in-state. Oklahoma and Ohio are exceptions and allowed wastewater to be injected into the ground. 
The injected fluid can activate old faults and cause earthquakes where there hadn’t been in our recorded history. This is an animation showing 7 years of injection data and earthquake occurrence. The tonal sound corresponds to the injection rate, the cracking sounds are a direct sonification of the earthquakes. 

{{< vimeo 644949109 >}}


## The Geysers geothermal field

The extraction of geothermal energy, a CO2-free resource, also produces earthquakes, but with minimal risk of groundwater contamination, and the scale is far smaller, in area and magnitude.

Here is a similar movie from The Geysers geothermal field in Northern California, the largest actively producing field in the world, generating about 800 MW of electricity. As above, tonal sound corresponds to the injection rate, the cracking sounds are a direct sonification of the earthquakes. This time, there are two injection wells (shown by red and green squares) and the sound is panned left and right so you can distinguish injection rate at each site.

{{< vimeo 578487217 >}}


## Kilauea Volcano
The large eruption in Hawaii that dominated the news in 2018 was the culmination of a decade of activity at Kilauea summit volcano. Below is an animation that explores this eruption from different spatial and temporal scales. [Here](https://eos.org/science-updates/earth-is-noisy-why-should-its-data-be-silent) is the accompanying paper in EOS magazine. 

{{< vimeo 828509475 >}}

To see more of my artwork, you can check out my personal page at [Magma Arta](https://magmaarta.com)

And I’d love to hear from you! 

Email: barthac@gmail.com

<head>

<title>Visualizations | Anna Barth</title>

</head>