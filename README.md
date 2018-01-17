# mapbox-gl-json-to-mapnik-xml

Convert mapbox gl json to mapnik xml

## TODO:

* Create CLI interface. So far can start by modifying test/test.js (change input file name) and run `node test/test.js`
* Create web service API (via expressjs perhaps)
 http://<host>/converter/mbToCartoMobileXml?style=<mb-style-url-with-token> 
 returns ZIP file with style.xml, assets (fonts and sprites) which can be used in CARTO SDK
 