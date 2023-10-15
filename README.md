
# Map with Red Marker

This is a simple web application that displays a map with a red marker at a specified location using OpenLayers. The marker's properties, such as size and color, can be customized to fit your requirements.

## Prerequisites

- Web browser with JavaScript enabled

## Usage

1. Clone the repository or download the ZIP file.

2. Open the `index.html` file in a web browser.

3. The map will initially be centered at the default location (London, UK). To specify a different location, modify the `longitude` and `latitude` variables in the `<script>` section of the HTML file.

   ```javascript
   var longitude = -0.1276; // Replace with your desired longitude
   var latitude = 51.5074; // Replace with your desired latitude
   ```

4. The red marker will be displayed on the map at the specified location.

## Customization

- To use a custom red icon for the marker, replace the `src` property value in the `iconStyle` object with the path to your own red icon image.

   ````javascript
   var iconStyle = new ol.style.Style({
     image: new ol.style.Icon({
       src: 'path/to/red-icon.png', // Replace with the path to your red icon image
       scale: 0.5 // Adjust the scale of the icon as desired
     })
   });
   ```

- You can adjust other properties of the marker, such as size and shape, by modifying the values within the `iconStyle` object. Refer to the OpenLayers API documentation for more details on available options.

## License

This project is licensed under the [MIT License](LICENSE).

```

