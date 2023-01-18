# Movie Review NLP using IBM Cloud API and IBM Cloud Pipeline

This project utilizes the Natural Language Processing (NLP) capabilities of the IBM Cloud API to analyze movie reviews, and IBM Cloud pipeline to deploy the code. The API is used to determine the sentiment of a given review, as well as identify key entities and concepts mentioned in the review

![frontend (2)](https://user-images.githubusercontent.com/95765364/213115264-e0c1f6a2-294c-43fa-86df-bef89a867ba2.png)

![end (2)](https://user-images.githubusercontent.com/95765364/213115313-eda3126c-7a6f-42cf-b1bc-84a33e4a730f.png)


## Getting Started
- Sign up for an IBM Cloud account and create a new instance of the Natural Language Understanding (NLU) service.
- Obtain the API key for the NLU service and add it to your environment variables or code.
- Create a new pipeline in IBM Cloud, and connect your GitHub repository containing the code for the NLP analysis.
- Use the NLU service's API to analyze movie reviews by sending a POST request with the review text and desired features (e.g. sentiment analysis, entity recognition).
- Use the returned data to display the sentiment and key entities/concepts of the review.
- In pipeline configuration, add a deploy action and select the appropriate cluster and namespace.
- You can trigger the pipeline manually or configure it to trigger automatically when there is a new commit in the connected repository.

# Limitations
- The NLU service has a limit on the number of requests that can be made per month. Be sure to monitor usage to avoid going over this limit.
- The sentiment analysis provided by the NLU service is determined by the overall sentiment of the text, not the sentiment towards specific entities or concepts mentioned in the text.

# Conclusion
Using the IBM Cloud NLU service and IBM Cloud pipeline, it is possible to quickly and easily analyze movie reviews to determine sentiment and identify key entities and concepts. This can provide valuable insights for movie studios and reviewers. With pipeline, the deployment process is automated and streamlined, making it easy to manage different environments, and rollback if necessary.
