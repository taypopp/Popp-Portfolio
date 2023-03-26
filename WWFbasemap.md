# World Wildlife Fund: A Custom Basemap

## The Bid

Download a printable version of the bid [here].

## Map Style

![palette](https://taypopp.github.io/Popp-Portfolio/palette.png)

I pulled inspiration for the map's style from the WWF website. There is simplicity in WWF's branding, with only solid black and white in the logo itself. The orange color is used for text and buttons on the site, as well.

Beyond that, there aren't any colors that are consistently used by WWF. Given the nature of the organization, green comes up a lot; I pulled this green from one of the images on the site.

I also included two shades of gray. While there are more interesting colors used across the homepage (the image with the heading "People and communities," for instance), but shades of gray with a couple pops of color feels more consistent with WWF's brand.

<a href="/WWFbasemap.json" download>Download the Style</a>

## In Action

Below you can see how the map looks at three different zoom extents.

### Countries and Continents

This is how the map looks at x zoom extent...

[countries picture here]

### States and Provinces

And y zoom extent...

[states picture here]

### Places and Parks

And Z zoom extent.

[closeup image here]

## The Specifics

| Feature Type | Element Type | Stylers |
| ------------- | ------------- | ------------- |
| All | Geometry | Color: Black |
| All | Geometry/Stroke | Color: White |
| All | Labels/Text Fill | Color: Orange |
| All | Labels/Text Outline | Color: Black |
| Administrative | Geometry | Color: Light Gray |
| Administrative | Geometry/Stroke | Color: Light Gray |
| Country | Geometry/Fill | Color: White |
| Country | Geometry/Stroke | Color: White |
| Country | Lables/Text Fill | Color: Light Gray |
| Province | Geometry/Stroke | Color: Light Gray |
| Locality | Labels/Text Fill | Color: Light Gray |
| Land Parcel | All | Color: Light Gray |
| Land Parcel | Geometry/Fill | Color: Dark Gray |
| Points of Interest | Labels/Text Fill | Color: Light Gray |
| Park | Geometry | Color: Dark Gray |
| Park | Labels/Text Fill | Color: Green |
| Park | Labels/Text Outline | Color: Black |
| Road | Geometry/Fill | Color: Light Gray |
| Road | Labels/Text Fill | Color: Light Gray |
| Highway | Geometry | Color: Light Gray |
| Controlled Access | Geometry | Color: Light Gray |
| Arterial | Geometry | Color: Light Gray |
| Local | Labels/Text Fill | Color: Light Gray |
| Transit | Labels/Text Fill | Color: Dark Gray |
| Water | Geometry | Color: Dark Gray |
| Water | Labels/Text Fill | Color: Green |
