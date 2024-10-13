# API-Testing-Portofolio
## API Test for Searching Articles Containing *Ethereum* on https://newsapi.org 

### Description 
This project contains an automated test for the NewsAPI.org /v2/everything endpoint, which searches for articles containing the keyword "Ethereum." 
The test is designed to verify if the API response is correct, the returned articles contain the desired term, and if their structure follows the API specifications.

### Tested Endpoint: 
GET https://newsapi.org/v2/everything 

### Parameters 
- q: The search term, in this case, "Ethereum."
- apiKey: A valid API key from NewsAPI.org.

### Project Structure 
- **API Test in Postman**: The test is configured in Postman and can be run directly from the application.
- **Tests include**:

    - Verifying the response status code (200 - Success).
    - Checking for the existence of articles in the response.
    - Ensuring that the title and/or description of each returned article contains the term "Ethereum."
