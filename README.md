# CUSF Landing Predictor - Tawhiri / Leaflet Version

Cambridge University Spaceflight landing predictor - a web-based tool for predicting the flight path and landing location of latex meteorological sounding balloons. 

This fork of the [original predictor](https://github.com/jonsowman/cusf-standalone-predictor) contains a continuation of the original CUSF predictor, which utilises the [Tawhiri API](https://github.com/projecthorus/tawhiri/), and also uses Leaflet for mapping instead of Google Maps. 

A live version of the predictor intended for non-commercial use is available at http://tawhiri.stratoflights.yktaero.space/ , hosted by the [Sakha Aerospace Systems, LLC](https://www.yksa.space).

## Added/planned features in this fork:
- API address changed to use YKSA-hosted Tawhiri.
- Ascent and descent rates can be defined as altitude-rate curves (note: requires changes [to the backend](https://github.com/YKSA-Sakha-Aerospace-Systems/tawhiri))
- Time-altitude chart for last prediction
- (Planned) CSV curve editor
- (Planned) Deprecate cookie locations and move to localStorage

## License

This work is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or any later version. This work is distributed in the hope that it will be useful, but without any warranty; without even the implied warranty of merchantability or fitness for a particular purpose.  

## Credits & Acknowledgments
Credit as detailed in individual files, but notably:  

* Rich Wareham - The new predictor and the hourly predictor system  
* Fergus Noble, Ed Moore and many others  
* Adam Grieg
* Jon Sowman

Work to switch the predictor across to Tawhiri, and addition of other features by:
* Mark Jessop - <vk5qi@rfhead.net>
