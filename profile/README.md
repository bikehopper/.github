## Welcome to BikeHopper

BikeHopper is a navigation app for everything but cars. It gives you
directions that include riding a bike, taking transit, or both. We're
developing and testing in the San Francisco Bay Area, California, but
in principle it could be used anywhere in the world where transit info
is available in GTFS format.

BikeHopper uses:

- [OpenStreetMap](https://openstreetmap.org/) street data
- [Nominatim](https://nominatim.org/) and
  [Photon](https://github.com/komoot/photon) for geocoding
- A [modified version of
  GraphHopper](https://github.com/bikehopper/graphhopper), for routing
  (Thank you to the original
  [GraphHopper](https://www.graphhopper.com/))
- A React frontend for mobile and desktop layouts at
  [bikehopper-ui](https://github.com/bikehopper/bikehopper-ui)
- A lightweight Node.js proxy we've written called
  [bikehopper-web-app](https://github.com/bikehopper/bikehopper-web-app)
- [FormatJS](https://formatjs.io/) and [hosted
  Weblate](https://hosted.weblate.org/projects/bikehopper/bikehopper-ui/) for
  internationalization (WIP)
- _For the Bay Area instance:_ transit data from
  [511.org](https://511.org/open-data/transit)

BikeHopper is free software under the GNU Affero General Public
License, which requires the source to be kept open. We discourage
corporate uses of BikeHopper, but highly encourage self-hosted,
community instances in other regions. Get in touch if you'd like us to
help you be the first region beyond the Bay Area to set one up.
