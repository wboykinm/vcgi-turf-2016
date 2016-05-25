<!--__Use 'http://www.macwright.org/biggie'__-->

# Geoprocessing in a Web Browser for Fun and Profit

---

using [turf.js](http://turfjs.org/) for spatial data crunching

---

Plan:
- *How we got here*
- Client side geoprocessing
- Server side geoprocessing

---

1993: Xerox PARC

![xerox](https://pbs.twimg.com/media/CjP7iSwUgAAJ0Ib.jpg)

---

1998: ArcIMS

![arcims](http://webhelp.esri.com/arcims/9.3/general/mergedprojects/arcxmlguide/elements/images/config_file_d1.gif)

---

2004: Competition

- ArcGIS Server
- PostGIS + UMN MapServer

---

2005: Year G

![goog](http://blogoscoped.com/files/google-museum/48.jpg)

---

"GIS in the browser"

2010:

---

![biden](http://images.mentalfloss.com/sites/default/files/styles/insert_main_wide_image/public/giphy.gif)

---
2016: 

It's actually a thing: 

---

![buffer](https://www.dropbox.com/s/71c9b3yyibimmnm/dropchop1.gif?dl=1)

---

[Try it out on the great state of Vermont](http://dropchop.io/?gist=e1028889229343fa8ed8a6e74d21f5d0)

---

Powered by turf.js

---

A javascript library for geoprocessing

---

GeoJSON

---
```
{
  "type": "Feature",
  "properties": {
    "marker-color": "#ab4ca9",
    "marker-size": "large",
    "marker-symbol": "town-hall",
    "name": "Vermont State Capitol"
  },
  "geometry": {
    "type": "Point",
    "coordinates": [
      -72.5805115699768,
      44.26252006240964
    ]
  }
}
```

---

Looks like [this](http://geojson.io/#id=gist:wboykinm/3f29b2d623992fa604b99523019a7aac&map=18/44.26249/-72.58071):

---

![cap](https://www.dropbox.com/s/6g0181ky5u7o702/Screenshot%202016-05-24%2021.26.48.png?dl=1)

---

- How we got here
- *Client side geoprocessing*
- Server side geoprocessing

---

Again, GIS in the web browser. LOL.

---

_What do end users care about geoprocessing?_

---

Analysis in support of a task, or to tell a story

---

Working from [Vermont data](http://vcgi.vermont.gov/opendata) and a great [example of turf in use](https://www.mapbox.com/help/analysis-with-turf/)
---

- How we got here
- Client side geoprocessing
- *Server side geoprocessing*

---

A more complicated problem, wth bigger data, needs more power than a browser can provide.

---

This time working from [a critical real-world example](https://github.com/morganherlocker/nepal-damage-analysis). . .

---

![nepal](https://www.dropbox.com/s/fk4b1drr1xcma7q/Screenshot%202016-05-24%2017.10.57.png?dl=1)

---

. . . and [adapting the process for some local data](https://github.com/morganherlocker/nepal-damage-analysis).