# Instructions

This is a simple weather application. 

The current code uses your browser current location to trigger a request to the Weather API (https://openweathermap.org/api) and have the details related to your current temperature, humidity, sunrise/sunset hours and sky condition displayed

*NOTE: Please don't change the API key defined on the `.env` file*


You can do any number of challenges :smile: - keep in mind that each challenge builds upon the last one

Once you are done, submit a Pull Request with a brief description of your changes and let us know how many challenges you are addressing

****

## 1st Challenge

1. Allow users to provide the location to which they want to see the weather details from
2. Refresh the page every 30 seconds and also allow manual refresh
3. Centralize the card, fix the city name bar and replace the sky condition with an image (any image, but make sure to account for different types)
4. Make sure to cover basic edge cases (list those cases in the Pull Request description)

## 2nd Challenge

1. Based on the user browser location, display today's hourly weather (temperature, humidty & description)
2. Display a table of the next days temperature and description
   1. Bonus points if they are associated with an image representing the weather condition
3. Refresh the page every 30 seconds and also allow manual refresh
4. Both the table and the hourly display must look nice (we are not looking for a UI/UX expertise as much as making sure elements are not overlaping each other nor things are out of alignment)
5. Make sure to cover basic edge cases (list those cases in the Pull Request description)
6. Use this API in order to retrieve the data you will need: https://openweathermap.org/api/one-call-api


## 3rd Challenge
1. Combine 1st and 2nd challenge together :)
   1. Allow users to provide a location and display the hourly and weekly data (take a look on the 2nd Challenge)
   2. Refresh the page every 30 seconds and also allow manual refresh
2. Make sure to cover basic edge cases (list those cases in the Pull Request description)


**NOTE: Don't forget to add unit tests and to apply best practices ( :bulb: maybe having your render calling the API directly is not the best idea ;) )
**