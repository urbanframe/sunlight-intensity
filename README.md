<img width="128" height="128" alt="image" src="https://github.com/user-attachments/assets/a1618b88-949a-4517-bc9c-53753430e59e" />

# Sun Intensity 

Home Assistant integration to display the intensity of the sun on each of your propertie's walls, based on the suns direction (Azimuth).

As the Sun moves around your house, each wall sensor will display a percentage of how much sunlight is on that wall. When the sun is at 90° to a wall, the entity will be at 100%.

<img width="338" height="342" alt="image" src="https://github.com/user-attachments/assets/fcacff10-415b-45b9-852c-eb2fcbba7ef1" />

# Usage and Automation Ideas

 🤖: Close Blinds at rear of house when Back Wall Intensity reaches 80%
 
 🤖: Turn on Fan when Right Wall Intensity exceeds 50%


# Installation

Sun Intensity can be installed via HACS or by copying the sun-intensity folder to the [custom_components](https://github.com/urbanframe/sun-intensity/tree/main/custom_components/sun_intensity) folder within Home Assistant.

# Configuration

Configuration requires the longitude, latitude and rotation of your property. This information can be obtained from [Google Earth](https://earth.google.com).

Change the latitude and longitude format to decimal, using the settings.  

<img width="336" height="427" alt="image" src="https://github.com/user-attachments/assets/5750ecb5-b3b1-484f-ba22-80c384f3500f" />

The longitude and latitude can be seen in the bottom right hand corner.

* Latitude ending with N = Positive number
* Latitude ending with S = Negative number
* Longitude ending with E = Positive number
* Longitude ending with W = Negative number

Eg, 51.501079°N 0.142612°W would be:
* Longitude: 51.501079
* Latitude: -0.142612



Using the measure tool draw a line parallel with the sides of your property from the rear to the front. The rotation will be displayed as the heading in the measure toolbox.


<img width="1280" height="1044" alt="image" src="https://github.com/user-attachments/assets/3338f357-1322-4a61-984d-6c438c3dc776" />

<img width="422" height="413" alt="image" src="https://github.com/user-attachments/assets/dc4cba10-f798-4010-ac25-058bbbcd73dd" />

Home Assistant integration to display the intensity of the sun on your house walls, based on the suns direction (Azimuth).

# Installation

Sun Intensity can be installed via HACS or by copying the sun-intensity folder to the custom_components folder within Home Assistant.

# Configuration

Configuration requires the longitude, latitude and rotation of your property. This information can be obtained from [Google Earth](https://earth.google.com).

Change the latitude and longitude format to decimal, using the settings.  

<img width="336" height="427" alt="image" src="https://github.com/user-attachments/assets/5750ecb5-b3b1-484f-ba22-80c384f3500f" />

The longitude and latitude can be seen in the bottom right hand corner.

* Latitude ending with N = Positive number
* Latitude ending with S = Negative number
* Longitude ending with E = Positive number
* Longitude ending with W = Negative number

Eg, 51.501079°N 0.142612°W would be:
* Longitude: 51.501079
* Latitude: -0.142612



Using the measure tool draw a line parallel with the sides of your property from the rear to the front. The rotation will be displayed as the heading in the measure toolbox.


<img width="1280" height="1044" alt="image" src="https://github.com/user-attachments/assets/3338f357-1322-4a61-984d-6c438c3dc776" />

<img width="422" height="413" alt="image" src="https://github.com/user-attachments/assets/dc4cba10-f798-4010-ac25-058bbbcd73dd" />
