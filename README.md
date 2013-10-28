Review DPLA Geocodes
==================
                    
The Digital Public Library of America (http://dp.la) aggregates cultural heritage data from libraries, museums, and archives across the United States. 

As part of the aggregation process, the DPLA assigns geocodes to each item based on location data within in the item's metadata. The geocode assignment is not 100% accurate, and it would be useful to be able to identify items that have been geocoded incorrectly. 

This code was developed during the 2013 DPLAFest Hackathon to explore a way to address this problem by bringing human intelligence into the equation. The web page displays a randomly selected record from the DPLA alongside a map of the United States that shows where the records's DPLA-assigned geocode would place it. The user says whether the assignment is accurate or not. Rinse and repeat.
                                           
This concept could be incorporated into a crowdsourcing application of your choosing (Mechanical Turk, etc.)

*Installation instructions*

* Add your DPLA API key to dpla-map.js (http://dp.la/info/developers/codex/policies/#get-a-key)
* Open index.html in your browser

*Future development and known issues*

* A new item is loaded anytime the map viewport moves
* Clicking the Yes/No/Maybe buttons doesn't actually do anything
                                                                                                                                                              
Thanks to @edsu (Ed Summers) for the mapping code on which this was based (https://github.com/edsu/dpla-map)

