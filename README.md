
# Weather web application

A simple projects that displays the weather of the city entered by the user 


## API Reference
create an account on open weather website and generate your unique api key
#### Get item using open weather api based on city as a parameter

```http
  api.openweathermap.org/data/2.5/weather?q={city name}&appid={API key}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `city name`      | `string` | **Required**. Input of item to fetch |
| `API key` | `string` | **Required**. Your API key |

  #### used unsplash api to showcase background image

```http
   https://source.unsplash.com/1600x900/?landscape  
```
  #### manipulated dom using js and changed background image according to the input city
  ```http
   https://source.unsplash.com/1600x900/?" + input_city_name + " 
```

  