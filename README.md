# mtlcafes
A Map of some Montreal Cafes: https://raphaelletseng.github.io/mtlcafes/

To run locally: `python3 -m http.server 8000` to load at http://localhost:8000/index.html

## Add your own favourite cafe:
Feel free to make a PR with your own cafe recommendations!
Add a feature to the `mtlcafes.geojson` with the following data:
```
        { "type": "Feature", "id": "__", "properties": { "Name": "_____", "Address": "____", "City": "____", "Country": "____", "Latitude": "___", "Longitude": "___", "Website": "____" }, "geometry": { "type": "Point", "coordinates": [ __long__, __lat__ ] }}
```

Resources and pulling inspiration from:
- Larry Buchanan & Nilkanth Patel's [101 Places to Find Great Coffee in New York](https://www.nytimes.com/interactive/2014/05/06/dining/101-places-to-get-good-coffee-in-new-york.html?_r=0)
- Kelly Waldron and Mission Local's [Cannabis Permits](https://missionlocal.github.io/interactives/cannabis-permits/)