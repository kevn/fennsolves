# fennsolves
A geojson of Forrest Fenn Treasure Hunt solves from Reddit; source for the solve map at https://umap.openstreetmap.fr/en/map/t_474208#6/42.642/-109.248

# Add your own solve
Submit a pull request with your change to the `treasurespots.json` file.

The format of the file is geojson. It is a normal json file.

A new solve can be added by inserting a new entry into the `features` array. Here is an example entry:
```
        {
            "type": "Feature",
            "properties": {
                "name": "The Title of My Awesome Solve",
                "author": "My Name (just a normal string)",
                "profileurl": "https://reddit.com/user/fooptydooblecrom",
                "description": "The taco stand outside the Gotham City Police Station.",
                "url": "http://reddit.com/r/SomeLink/to/more/details"
            },
            "geometry": {
                "type": "Point",
                "coordinates": [
                    -108.621299,
                    44.896907
                ]
            }
        },
```
