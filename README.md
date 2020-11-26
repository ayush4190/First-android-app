# ENHANCEMENT OF RECOMMENDATIONS BY USING INTERACTIVE AUGMENTED RECOMMENDER SYSTEMS AND NLP

### Steps to run the NLP API

* Download Postman from https://www.postman.com/downloads/
* Open Postman and then use the EndPoint https://monitoringappsih.herokuapp.com/nlp 
* Navigate to body section and select JSON format.
* In the editor provided use the format
  ```
  {
    "review" : "enter your comments here"
  }
  ```
* Click on the send button wait for few seconds then your result must look like 
  ```
  {
    "analysis": score
  }
  ```
