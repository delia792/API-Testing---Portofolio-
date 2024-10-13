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
 
### Steps to Run the Test 
1. In Postman, insert the Endpoint. 
2. Set parameters (q: Ethereum). 
3. Tet the API_KEY variable with your API key from NewsAPI (c8b8bf32aaf54e389ba12d29121e6d4e). 
4. Click on the "Run" or "Send" button to execute the test.
5. Review the test results in Postman’s console, where you will see which tests passed or failed.

### Test Details

1. Response Status Code: Verifies that the API returns a 200 / Success status code, indicating the request was successful.
2. Articles Exist: Ensures that the API returns a list of relevant articles, not an empty list.
3. Article Relevance: Checks that each returned article contains the term "Ethereum" in the title or description, confirming the relevance of the results.

### Test Results

- If all tests pass successfully, the API correctly returns articles about Ethereum.
- If there are any errors, Postman will display which test failed and provide details about the failure.

### Exemple 

 ![Screenshot 2024-10-13 195833](https://github.com/user-attachments/assets/849826a3-c61c-423d-b66e-54a048252cf2)
