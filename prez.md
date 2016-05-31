<!--__Use 'http://www.macwright.org/biggie'__-->

# Geoprocessing in a Web Browser for Fun and Profit

---

using [turf.js](http://turfjs.org/) for spatial data crunching

---

Plan:
- *How we got here*
- Client side geoprocessing
- Server side geoprocessing
- Where next?

---

1993: Xerox PARC

---

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

Powered by [turf.js](http://turfjs.org/)

---

A javascript library for geoprocessing

---

Instead of this:

---

![arcpro](http://pro.arcgis.com/en/pro-app/help/analysis/geoprocessing/basics/GUID-8C7480F4-4E44-4E9E-89BE-421E823B767C-web.png)

---

This:

---

![hull](https://www.dropbox.com/s/ggkw3j7q1npp24t/Screenshot%202016-05-31%2017.13.16.png?dl=1)

---

Javascript

---

![afraid](https://66.media.tumblr.com/3946cce1923abd7bb5e1c5bc16681d6d/tumblr_nwr31xQQLL1thdow0o1_500.gif)

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

Looks like [this](http://geojson.io/#id=gist:wboykinm/3f29b2d623992fa604b99523019a7aac&map=18/44.26249/-72.58071)

---

![cap](https://www.dropbox.com/s/6g0181ky5u7o702/Screenshot%202016-05-24%2021.26.48.png?dl=1)

---

- How we got here
- *Client side geoprocessing*
- Server side geoprocessing
- Where next?

---

Let's do a quick project, starting with [data creation](http://geojson.io/#map=8/43.997/-72.631)

---

Could you spot the server in there?

---

Again, GIS in the web browser. LOL.

---

_What do end users care about geoprocessing?_

---

Analysis in support of a task, or to tell a story

---

Nearest neighbor: [Post-swimming brews](http://wboykinm.github.io/vcgi-turf-2016/client/)

---

(Working from [Vermont data](http://vcgi.vermont.gov/opendata) and some [good documentation](https://www.mapbox.com/help/analysis-with-turf/))

---

Distance along a line: [Meet me halfway](http://wboykinm.github.io/midpoint/)

---

- How we got here
- Client side geoprocessing
- *Server side geoprocessing*
- Where next?

---

[node.js](http://nodejs.org/) is javascript, just built for servers. *turf works the same way [as a server-side tool](https://github.com/mapbox/turf-server-example)*

---

A more complicated problem, wth bigger data, needs more power than a browser can provide.

---

[tile-reduce](https://github.com/mapbox/tile-reduce)

---

[Comparing two gigantic datasets](https://www.mapbox.com/blog/updating-map-runkeeper/)

---

![run](https://farm1.staticflickr.com/697/20479186309_df83c4d759_b.jpg)

---

[A time-sensitive analysis to save lives](https://github.com/morganherlocker/nepal-damage-analysis). . .

---

![nepal](https://www.dropbox.com/s/fk4b1drr1xcma7q/Screenshot%202016-05-24%2017.10.57.png?dl=1)

---

- How we got here
- Client side geoprocessing
- Server side geoprocessing
- *Where next?*

---

[Offline geoprocessing](http://www.fulcrumapp.com/blog/advanced-geospatial-calculations-with-turf/)

---

[Realtime](https://www.mapbox.com/blog/geofencing-london/) [geoprocessing](https://www.mapbox.com/bites/00223/)

---

Resources to get you started:

- [javascript](https://www.codecademy.com/courses/getting-started-v2/0/1?curriculum_id=506324b3a7dffd00020bf661)
- [node.js](http://nodeschool.io/#workshopper-list)
- [turf.js](https://www.mapbox.com/help/analysis-with-turf/)
- [dropchop.io](http://dropchop.io/)
- [github](https://github.com/)

---

Questions?

---

Hit me up:

- bill@faraday.io
- @vtcraghead on Twitter