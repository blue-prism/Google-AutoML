# Google AutoML
A BluePrism skill providing integration with Google AutoML Natural Language API
This asset interacts with the web service exposed by Google AutoML Natural Language at <https://automl.googleapis.com/>. Further actions may be added in the future.

## Usage
You will first need a create a machine learning model which you can use to make inference. This asset provides the below action for performing the model inference.

* **Predict**

Refer <https://cloud.google.com/automl/docs> on how to create custom models

Further details about the API can be found at <https://cloud.google.com/automl/docs/reference/rest/v1beta1/projects.locations.models/predict>

## Configuration

* Download or clone this repository. Extract the *.bprelease file* and import it into your Blue Prism environment
* Create an account at <https://cloud.google.com/>
* Follow steps as outlined in <https://cloud.google.com/automl> to create your model
* Enter the API Key into the "BluePrism Google AutoML" in credential manager
* Use the Predict action to make model inference

## Help

If issues are encountered, please submit a new issue on the Issues tab for this repository:

https://github.com/blue-prism/Google-AutoML/issues

