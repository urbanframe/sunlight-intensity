<img width="128" height="128" alt="image" src="https://github.com/user-attachments/assets/7968de98-6374-4b1e-977a-df659aa61c53" />

# Sunlight Intensity 

Add sunlight intensity to your dashboards and automations with this integration. **Sunlight Intensity** provides a percentage for each of your property’s walls, based on the suns direction (Azimuth).

As the Sun moves around your house, each wall sensor will display a percentage of how much sunlight is on that wall. When the sun is at 90° to a wall, the entity will be at 100%.

<img width="338" height="342" alt="image" src="https://github.com/user-attachments/assets/fcacff10-415b-45b9-852c-eb2fcbba7ef1" />

# Usage and Automation Ideas

 🤖: Close Blinds at rear of house when Back Wall Intensity reaches 80%
 
 🤖: Turn on Fan when Right Wall Intensity exceeds 50%


# Installation

**Sun Intensity** can be installed via HACS or by copying the sun-intensity folder to the [custom_components](https://github.com/urbanframe/sun-intensity/tree/main/custom_components/sun_intensity) folder within Home Assistant.

# Configuration

Configuration requires the longitude, latitude and rotation of your property. This information can be obtained from [Google Earth](https://earth.google.com).

In Google Earth change the latitude and longitude format to decimal within the settings.  

<img width="336" height="427" alt="image" src="https://github.com/user-attachments/assets/5750ecb5-b3b1-484f-ba22-80c384f3500f" />


The longitude and latitude can be seen in the bottom right hand corner. Ensure your coridinates are positive or negative nubers with the table below.

|Coordinate|Bearing|Decimal|
|-|-|-|
|Latitude|N|Positive|
|Latitude|S|Negative|
|Longitude|E|Positive|
|Longitude|W|Negative|


Eg, 51.501079°N 0.142612°W would be:
* Longitude: 51.501079
* Latitude: -0.142612

test?

Using the measure tool, draw a line parallel with the sides of your property from the rear to the front. The rotation will be displayed as the heading in the measure toolbox.


<img width="1280" height="1044" alt="image" src="https://github.com/user-attachments/assets/3338f357-1322-4a61-984d-6c438c3dc776" />


