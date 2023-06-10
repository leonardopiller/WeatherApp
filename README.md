# WeatherApp
A Weather App was developed where users can enter a city name, and it will display the current temperature, humidity, and wind speed for that location. The app utilizes an open and free API from https://openweathermap.org/api to fetch weather data.

To begin, the necessary variables are defined. Then, an asynchronous JavaScript function called checkWeather(city) is used to retrieve the JSON response from the API.

![image](https://github.com/leonardopiller/WeatherApp/assets/121625024/8397ec12-cab3-4e13-89d8-29ef7440d213)


In order to visualize the JSON response in the DevTool, a console.log(data) statement was inserted and later removed in the final version of the project.

![image](https://github.com/leonardopiller/WeatherApp/assets/121625024/7cab6137-f120-4332-9733-6b435cd71c2b)

As shown in the response, various data properties are available to access specific weather information about the user's requested city. In this project, the City Name, Temperature, Humidity, and Wind Speed are accessed using the following properties: data.name, data.main.temp, data.main.humidity, and data.wind.speed, respectively.

![image](https://github.com/leonardopiller/WeatherApp/assets/121625024/c9f4af90-6841-4feb-818d-47a622de1172)


Finally, the weather icon is displayed by accessing the property data.weather[0].main, and the content div appears in the DOM with display: block.

![image](https://github.com/leonardopiller/WeatherApp/assets/121625024/dd8de3ce-4a74-4572-93f5-a0d281d51db3)


The 'checkWeather' function is triggered when the search box is clicked, taking the city typed in the input as a parameter.

![image](https://github.com/leonardopiller/WeatherApp/assets/121625024/149647b7-3e01-4510-88da-244288863036)



SCREENSHOTS


![weatherApp-open](https://github.com/leonardopiller/WeatherApp/assets/121625024/d322d9a0-524a-4400-b9c0-9152170254ff)

Screenshot of the WeatherApp before the first query.


![weatherApp-london](https://github.com/leonardopiller/WeatherApp/assets/121625024/3348e863-5acc-4b9b-a323-55254a7740a4)

Screenshot of the WeatherApp displaying weather information for London.

Additional screenshot examples can be found in the screenshots folder of this repository.
