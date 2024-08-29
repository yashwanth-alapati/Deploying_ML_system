This project was completed as part of a Machine Learning course and involved several key tasks:

Evaluation of the Existing Model:

I evaluated the model previously developed for classifying food images into various categories. The evaluation focused on both accuracy and latency, identifying areas for improvement.


I trained two models:
* Accuracy-Optimized Model(ResNet50V2): Focused on maximizing classification accuracy, even if it slightly increased inference time.
* Latency-Optimized Model(MobileNet): Focused on minimizing inference latency, even if it meant sacrificing some accuracy.
The models were fine-tuned using a dataset provided by GourmetGram, and saved for deployment.
Design and Evaluation of Deployment "Recipes":

I designed deployment "recipes" for both models using Kubernetes in a cloud environment.
The recipes were evaluated based on operational metrics such as inference time, resource usage, and cost efficiency.
Final Deliverables:

I prepared a set of slides summarizing my findings, which can be used to get an overview of the work done.
