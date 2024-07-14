# Tech4City2024 - Entry Coding Challenge
![Tech4CityBanner](https://github.com/ej-hw/Tech4City2024/blob/main/Tech4City2024Banner.png?raw=true)

[Fork](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) now to participate!

## About

The annual Huawei Tech4City Competition presents a great opportunity for you to embark on a digital journey towards creating a more inclusive and sustainable Singapore. This competition will equip you with the tools you need to build and improve your prototypes, and turn your creative ideas and solutions into reality.

Find out more about the Huawei Tech4City 2024 competition on the [official website](http://tech4city.sg/2024)

## Entry Challenge:
Create an AI web application that allows user to input data, perform AI processing on the input, and displays the result. The application should also store past inputs and results in a lightweight local database, which can be viewed later on the frontend. Application needs to be runable using a 4vCPU, 16 GB Ram without GPU environment. 

Participants can choose one of the following AI use cases:
1. Sentiment Analysis
2. Image Classification
3. Object Detection

## Submission Requirements:
The challenge is expected to be performed using HTML, CSS, python and vanilla javascript with the basis to screen participants with fundamental knowledge of creating application using common coding languages and frameworks.  

### Repository Setup:
Create a repository with the following structure:
```
/frontend
  - index.html        # Create a form with appropriate input fields (text area for sentiment analysis, file input for image classification or object detection) and a submit button.
  - styles.css        # Style the form and results display area.
  - script.js         # Handle form submission and send input data to the backend API.
                      # Display the AI result returned from the backend.
                      # Fetch and display past inputs and results from the backend.

/backend
  - app.py            # main file for backend code for endpoints
                      # POST /analyze: Accepts user input, performs AI processing, stores the input and result in the database, and returns the result.
                      # GET /results: Retrieves all stored inputs and their results from the database.
  - model.py          # Implement a function to process the user input (e.g., classify sentiment, classify image, detect objects) using any AI/ML library (e.g., Huggingface, TensorFlow, PyTorch).
  - database.db       # Local lightweight database such as sqlite, duckdb, etc
  - requirements.txt  # File for python app dependencies

Dockerfile            # Provide a Dockerfile to containerize the application.
                      # The application should be accessible on port 8000.
                      
submission.md         # Provide your team name and other necessary information for the repository as deemed necessary
```

### Evaluation Criteria:
#### Frontend:
- User interface design and usability.
- Intuitive data submission and result display.
- Ability to review historical data submission and result

#### Backend:
- Proper implementation of API endpoints and adherence to REST principles.
- Effective data storage and retrieval using local database.
- Input validation and error handling.
- Database schema design and usage.
- API endpoints documentation using OpenAPI (Swagger) or equivalent.
  
#### AI Element:
- Use of appropriate techniques for AI processing.
- Proper integration & interfacing between the AI component, backend and frontend.
- Efficiency & effectiveness of the AI model

#### Docker:
- Correct setup and configuration of the Dockerfile.
- Successful execution of building and running the Docker container.
- Ability access application on port 8000 after running Docker container.

#### Overall Functionality:
- Completeness of the application and fulfillment of all specified requirements.
- Stability and absence of bugs or crashes.
- Innovation and creativity in the implementation.
- Code structure and readability

## Submission
You are required to submit your entry coding challenge artifacts (code, datasets, documents) as a [fork](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) to this repository. A submission form will also be made available for submission so that participants can include the link to the fork in the submission form.

After creating your own fork, clone your repository:
```
git clone git@github.com:<your-github-username>/Tech4City2024
```

Change to the directory:
```
cd Tech4City2024
```

Set upstream:
```
git remote add upstream git@github.com:ej-hw/Tech4City2024
```

...and start Hacking!!

Once you are ready to submit, create a pull request from your fork to us and include the link to your fork in your submission form.

*Please remember that your code will be publicly available, open-sourced licesed and free for the internet to use. Please ensure that you don't commit any sensitive information!*
