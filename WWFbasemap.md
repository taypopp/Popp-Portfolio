# World Wildlife Fund: A Custom Basemap

## The Bid

Download a printable version of the bid [here].

## Map Style

![palette](https://taypopp.github.io/Popp-Portfolio/palette.png)

I pulled inspiration for the map's style from the WWF website. There is simplicity in WWF's branding, with only solid black and white in the logo itself. The orange color is used for text and buttons on the site, as well.

Beyond that, there aren't any colors that are consistently used by WWF. Given the nature of the organization, green comes up a lot; I pulled this green from one of the images on the site.

I also included two shades of gray. While there are more interesting colors used across the homepage (the image with the heading "People and communities," for instance), but shades of gray with a couple pops of color feels more consistent with WWF's brand.

### How To Use This Style

To embed this style into the organization's existing web maps, team members can download the following JSON file. This file contains all relevant information for the style and can be quickly applied to an online map application, particularly in Google cloud based services. Within the organization's Google Cloud Console, go to map styles and create a new project. There will be an option to "Use the legacy JSON Styling Wizard." Select that option, click the three dots in the upper right corner, and select "Import JSON." From there, simply open the JSON style document as a text file, copy all code within the file, and paste it in the box for importing JSON files. Now your map will include your custom style!

<a href="/WWFbasemap.json" download>Download the Style</a>

## In Action

Below you can see how the map looks at three different zoom extents. There are no scale indicators in the Styling Wizard.

### Countries and Continents

![countries](https://taypopp.github.io/Popp-Portfolio/countries.png)

### States and Provinces

![province](https://taypopp.github.io/Popp-Portfolio/province.png)

### Places and Parks

![place](https://taypopp.github.io/Popp-Portfolio/place.png)

## The Specifics

| Feature Type | Element Type | Stylers |
| ------------- | ------------- | ------------- |
| All | Geometry | Color: Black (#000000) |
| All | Geometry/Stroke | Color: White (#FFFFFF) |
| All | Labels/Text Fill | Color: Orange (#C95B20) |
| All | Labels/Text Outline | Color: Black (#000000) |
| Administrative | Geometry | Color: Light Gray (#999999) |
| Administrative | Geometry/Stroke | Color: Light Gray (#999999) |
| Country | Geometry/Fill | Color: White (#FFFFFF) |
| Country | Geometry/Stroke | Color: White (#FFFFFF) |
| Country | Lables/Text Fill | Color: Light Gray (#999999) |
| Province | Geometry/Stroke | Color: Light Gray (#999999) |
| Locality | Labels/Text Fill | Color: Light Gray (#999999) |
| Land Parcel | All | Color: Light Gray (#999999) |
| Land Parcel | Geometry/Fill | Color: Dark Gray (#332F26) |
| Points of Interest | Labels/Text Fill | Color: Light Gray (#999999) |
| Park | Geometry | Color: Dark Gray (#332F26) |
| Park | Labels/Text Fill | Color: Green (#728F1A) |
| Park | Labels/Text Outline | Color: Black (#000000) |
| Road | Geometry/Fill | Color: Light Gray (#999999) |
| Road | Labels/Text Fill | Color: Light Gray (#999999) |
| Highway | Geometry | Color: Light Gray (#999999) |
| Controlled Access | Geometry | Color: Light Gray (#999999) |
| Arterial | Geometry | Color: Light Gray (#999999) |
| Local | Labels/Text Fill | Color: Light Gray (#999999) |
| Transit | Labels/Text Fill | Color: Dark Gray (#332F26) |
| Water | Geometry | Color: Dark Gray (#332F26) |
| Water | Labels/Text Fill | Color: Green (#728F1A) |
