# designway-assessment

steps to run the project
 - Clone the project
 - Download the extentions
 - Update Settngs.js
 - Click on watch scss
 - Right click the index.html file and click on "Ope with Live server"

 
using vs code extention 
 - Live server
 - Live scss compiler


Add this code in setting.json ov vs code 
(this will create the css files on scss watch)
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/css"
        },
        {
            "format": "compressed",
            "extensionName": ".min.css",
            "savePath": "/css"
        }
    ],