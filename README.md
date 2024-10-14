# API-Testing-Portofolio
## API Test for Searching Articles Containing *Ethereum* on https://newsapi.org 

### Description: 
This project contains an automated test for the NewsAPI.org /v2/everything endpoint, which searches for articles containing the keyword "Ethereum." 
The test is designed to verify if the API response is correct, the returned articles contain the desired term, and if their structure follows the API specifications.

### Tested Endpoint: 
GET https://newsapi.org/v2/everything 

### Parameters: 
- q: The search term, in this case, "Ethereum."
- apiKey: A valid API key from NewsAPI.org.

### Project Structure: 
- **API Test in Postman**: The test is configured in Postman and can be run directly from the application.
- **Tests include**:

    - Verifying the response status code (200 - Success).
    - Checking for the existence of articles in the response.
    - Ensuring that the title and/or description of each returned article contains the term "Ethereum."
 
### Steps to Run the Test: 
1. In Postman, insert the Endpoint. 
2. Set parameters (q: Ethereum). 
3. Tet the API_KEY variable with your API key from NewsAPI (c8b8bf32aaf54e389ba12d29121e6d4e). 
4. Click on the "Run" or "Send" button to execute the test.
5. Review the test results in Postman’s console, where you will see which tests passed or failed.

### Test Details:

1. Response Status Code: Verifies that the API returns a 200 / Success status code, indicating the request was successful.
2. Articles Exist: Ensures that the API returns a list of relevant articles, not an empty list.
3. Article Relevance: Checks that each returned article contains the term "Ethereum" in the title or description, confirming the relevance of the results.

### Test Results:

- If all tests pass successfully, the API correctly returns articles about Ethereum.
- If there are any errors, Postman will display which test failed and provide details about the failure.

### Exemple 

 ![Screenshot 2024-10-13 195833](https://github.com/user-attachments/assets/849826a3-c61c-423d-b66e-54a048252cf2) 


 ------------------- 

## API Test for Retrieving Weather in Chicago using api.openweathermap.org  

### Description: 
This project contains an automated test for the OpenWeatherMap API - /data/2.5/forecast endpoint, which retrieves the current weather for Chicago. The test is designed to verify if the API responds correctly, retrieves weather data for the correct city, and if the structure of the response matches the API specifications.

### Tested Endpoint: 
GET https://api.openweathermap.org/data/2.5/forecast 

### Parameters: 
- q: The city name, in this case, "Chicago." 
- apiKey: A valid API key from https://openweathermap.org
- (Optional) units: Units for temperature (metric), default is Kelvin.

### Project Structure: 
- **API Test in Postman**: The test is configured in Postman and can be run directly from the application.
- **Tests include**:

    - Verifying the response status code (200 - Success).
    - Checking that the response contains weather data for Chicago.
    - Verifying that key fields such as temperature, humidity, and weather are present in the response.
 
### Steps to Run the Test: 
1. In Postman, insert the Endpoint https://api.openweathermap.org/data/2.5/forecast. 
2. Set parameters (q: Chicago, units: metric). 
3. Tet the API_KEY variable with your API key from api.openweathermap.org (62dbc2af0464c0087f6876020d4cba64). 
4. Click on the "Run" or "Send" button to execute the test.
5. Review the test results in Postman’s console, where you will see which tests passed or failed.

### Test Details:

1. **Response Status Code**: Verifies that the API returns a 200 / Success status code, indicating the request was successful.
2. **Correct City**: Ensures that the weather data returned is specifically for Chicago by checking the name field in the response.
3. **Weather Data Fields**: Verifies that the response contains essential fields like temperature, humidity, weather description, and wind speed.

### Test Results:

- If all tests pass successfully, the API is correctly returning weather data for Chicago.
- If there are any errors, Postman will display which test failed and provide details about the failure.

### Exemple 

![Screenshot 2024-10-13 203034](https://github.com/user-attachments/assets/a93fda69-f3e7-4b44-b6e6-602bcb91a33f)

--------------------- 


## API Test for Searching Articles Containing Tesla (October 1 - October 10, 2024) on https://newsapi.org 

### Description: 
This project contains an automated test for the NewsAPI.org /v2/everything endpoint, which searches for articles containing the keyword "Tesla" within a specific date range: October 1, 2024, to October 10, 2024. The test verifies that the API responds correctly, returns relevant articles, and the structure of the response follows the API specifications.

### Tested Endpoint: 
GET https://newsapi.org/v2/everything 

### Parameters: 
- **q**: The search term, in this case, "Tesla."
- **from**: The start date for the search, "2024-10-01."
- **to**: The end date for the search, "2024-10-10."
- **apiKey**: A valid API key from NewsAPI.org.

### Project Structure: 
- **API Test in Postman**: The test is configured in Postman and can be run directly from the application.
- **Tests include**:

    - Verifying the response status code (200 - Success).
    - Checking for the existence of articles in the response.
    - Verifying that the articles returned contain the term "Tesla" and are within the specified date range. 
 
### Steps to Run the Test: 
1. In Postman, insert the Endpoint. 
2. Set parameters (q: Ethereum). 
3. Tet the API_KEY variable with your API key from NewsAPI (c8b8bf32aaf54e389ba12d29121e6d4e). 
4. Click on the "Run" or "Send" button to execute the test.
5. Review the test results in Postman’s console, where you will see which tests passed or failed.

### Test Details:

1. Response Status Code: Verifies that the API returns a 200 / Success status code, indicating the request was successful.
2. Existence of Articles: Ensures that the API returns a list of articles relevant to Tesla within the given date range.
3. Article Relevance: Verifies that the articles contain the keyword "Tesla" in the title or description and that they are published between October 1 and October 10, 2024. 

### Test Results:

- If all tests pass successfully, the API is correctly returning articles about Tesla within the specified date range. 
- If there are any errors, Postman will display which test failed and provide details about the failure.

### Exemple 
