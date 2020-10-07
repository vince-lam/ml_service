# Deploying Machine Learning Models with Django

This project follows the tutorial at https://deploymachinelearning.com/

The web service allows Machine Learning models to be available with REST API. The scope of the project includes:
- keeping the ML models in the web service
- allowing several ML models to be avalable at the same endpoint with different versions
- allowing many endpoint addresses to be defined
- storing information about requests to the ML models, allowing for future model testing and auditing
- testing of ML code and server code
- running A/B tests between different versions of ML models.

## The project structure
In the research directory there are:
- code for training machine learning models
- code for simulating A/B testing

In the backend directory there is a Django application.

In the docker directory there are dockerfiles for running the service in the container.
