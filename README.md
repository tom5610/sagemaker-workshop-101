# Getting Started with Amazon SageMaker

This repository accompanies a hands-on training event to introduce data scientists (and ML-ready developers / technical leaders) to core model training and deployment workflows with [Amazon SageMaker](https://aws.amazon.com/sagemaker/).

## Agenda

* [00 Getting Started](00-getting-started):  Get started using the lab environment through event engine.
* [01 demo: Builtin algorithm, HPO, Tabular](01-demo-builtin_algorithm_hpo_tabular): Demonstrating how to use (and tune the hyperparameters of) a **pre-built, SageMaker-provided algorithm** (Applying XGBoost to tabular data)
* [02 lab:  SKLearn, Foundational](02-lab-custom_sklearn_rf): Introductory example showing how to bring your own algorithm, using SageMaker's SKLearn container environment as a base (Predicting housing prices)
* [03 lab:  AutoPilot, Customer Churn](03-lab-auto_pilot_customer_churn): Demonstrating how to **use SageMaker Autopilot** model selection
* [04 lab: migration_challenge_keras_image](04-lab-migration_challenge_keras_image): A challenge to use what you've learned to **migrate an existing notebook** to SageMaker model training job and real-time inference endpoint deployment (Classifying MNIST DIGITS images)
* [05 demo:  Tensorflow, Keras, NLP](05-demo-custom_tensorflow_keras_nlp): Demonstrating how to **bring your own algorithm**, using SageMaker's TensorFlow container environment as a base (Classifying news headline text)
