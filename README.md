# ODK Survey
Configure GIS data collection applications to create a surveys by using ODK with [Cartoview](http://cartoview.org) and [GeoNode](http://geonode.org).

### Requirements
- Install [Cartoview](https://github.com/cartologic/cartoview)
- Install [ODK Aggregate Server](https://github.com/cartologic/cartoview_odk_connector)
- Install [ODK Connector App](https://github.com/cartologic/cartoview_odk_connector)

### Author your survey form 

ODK supports only xml format, and you have two options to create xml form:
- You can use ODK form builder to generate your form  http://build.opendatakit.org/
- You can create your form in xls format then convert it to xml format by using the online xls to xml converter http://opendatakit.org/xiframe/
For more details about creating XLS Form visit the following link https://opendatakit.org/use/xlsform/

Upload your form to ODK Aggregate through selecting "Form Management" tab and click "Add New Form" button then browse your form to be uploaded

### Download and configure ODK Collector on your mobile
- Download and install ODK Collect from Google Play
- After installation open "General Settings" from setting menu and select "Configure platform settings" and fill the fields as the following:

```sh
URL: http:// 72.249.76.10:8088/odkaggregate
Username: admin
Password: admin
```
- Back to home menu and click "Get Blank From" button to get the forms from the server
- Click "Fill Blank Form" and select the form and fill it
- Click "Send Finalized From" to send the completed forms

### Basic useful features
- Perform Survey easly from your mobile
- Create survey form in a few minutes
- View your result in GeoNode and ODK Aggregate 
- Export data as shapefile or kml 

