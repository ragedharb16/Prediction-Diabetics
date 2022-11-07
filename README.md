# Prediction-Diabetics

Author: RAGED ABOU


date: 04/07/2022


![image](https://user-images.githubusercontent.com/98135268/162464148-8089e327-6ba4-4d37-9948-68eb883e79ea.png)


ANALYSIS:

What is Diabetes?

Closeup of dictionary page showing definition of diabetes With diabetes, your body either doesn’t make enough insulin or can’t use it as well as it should.

Diabetes is a chronic (long-lasting) health condition that affects how your body turns food into energy.

Most of the food you eat is broken down into sugar (also called glucose) and released into your bloodstream. When your blood sugar goes up, it signals your pancreas to release insulin. Insulin acts like a key to let the blood sugar into your body’s cells for use as energy.

If you have diabetes, your body either doesn’t make enough insulin or can’t use the insulin it makes as well as it should. When there isn’t enough insulin or cells stop responding to insulin, too much blood sugar stays in your bloodstream. Over time, that can cause serious health problems, such as heart disease, vision loss, and kidney disease.

There isn’t a cure yet for diabetes, but losing weight, eating healthy food, and being active can really help. Taking medicine as needed, getting diabetes self-management education and support, and keeping health care appointments can also reduce the impact of diabetes on your life.

Source: https://www.cdc.gov/diabetes/basics/diabetes.html#:~:text=Diabetes%20is%20a%20chronic%20


# Object:
In This project we are going to predict with the most accuaracy the probably to develop that desease that affects millions of people around the World



## Information about our Data:

* NoofPregnancies: Information about the number of pregnancy female had till date

* GlucoseLevel: Glucose level of patient generally higher glucose level shoes the chances of sugar

* DiastolicPressure: Diastolic pressure is specifically the minimum arterial pressure during relaxation and dilatation of the ventricles of the heart

* Insuline level: Insulin level of patient

* BMI: The full form of BMI is Body Mass Index. It is a method of measuring through which individuals are classified into the following categories

* RelativeHistory: History of the patient

* Age: Age of the patient

* Diabetic: 0 shows that patient doesn't have diabetes 1 shows patient have diabetes


  # The Relation betwen the GlucoseLevel and the Diabetic
  
  
  ![Screenshot (54)](https://user-images.githubusercontent.com/98135268/162474424-7f51ff07-0bb3-4dac-a5b6-a18f638d23f7.png)
  
  
  We can see here there is relations betwwen Glucose and insulin , also we can see relation with the glucose on the pass of the ages
  
  # Relatation between the Glucose and the Insulin
  
  ![Screenshot (55)](https://user-images.githubusercontent.com/98135268/162475310-59616d18-91f3-412e-a7a5-83e55060ebf5.png)
  
  We can notice here that as we have an increassing in the glucose, our insuline goes higher and higher
  
  
  # Age and glucolse Level

![download (4)](https://user-images.githubusercontent.com/98135268/162475798-d5f8541c-ffee-4c92-9c68-9e2a17bc74c1.png)

As soon we getting old as soon our glucose level is getting higher, as higher glucose higher insulin, as higher insuline diabetis appears
we can see here how is the chain reaction of this disease 

one we identify the problems we can findo a solution to decreasse the posibilitys of having diabetis in a future 

 # Results to predict Diabetis in a patience
 
 ![download (5)](https://user-images.githubusercontent.com/98135268/162476531-80ec92ad-8933-493f-afe9-0571340459cf.png)
 

## MACHINE LEARNING

**PREDICTION MODEL COMPARISION**

| MODEL       |  PRECISION | RECALL | F1 Macro Average| F1 Weighted Average |
| ----------- |  ----------- | ----------- | ----------- | ----------- |
| KNN WITH PCA | 0.79 | 0.78 | 0.71 | 0.73 |
| KNN WITHOUT PCA |  0.78 | 0.78  | 0.69 | 0.72 |
| XGB | 0.78 | 0.85 | 0.72 | 0.74 |
| RANDOM FOREST | 0.64 | 1.0 | 0.39 | 0.50 |


## Model Evaluation
Error Types

In every binary classification problem we select one class to be the 'positive' class and one to be the 'negative' class. The positive class should be the one you are most interested in finding. For our Metabolic Syndrome dataset the positive class will be the presence of metabolic syndrome and the negative class will be the absence of metabolic syndrome.

Type 1 error: If our model predicts that going to suffer from  is diabetis , but it in fact there is not , it will have made a type 1 error. This is also known as a false positive.

Type 2 error: If our model predicts that going to suffer from diabetis, when there is not, it will have made a type 2 error. This is is also known as a false negative

## Recommended Model

 The XGB model after review all the models is abble to predict the diabetic dessease in a patience within an accuaracy of 77% 
using the XGB model

Accurate prediction can lead to early diagnosis and treatment. Inaccurate prediction can delay diagnosis and treatment.

moving foward doctors can make recomendations about to prevent this ilnes that affects millons of people around the World


## Benefit of Early Diagnosis and Treatment
  
 healthy lifestyle and excersise are the first line of treatment to prevent diabetis . You may have to see a dietitian and a physical therapist to help find a diet and exercise plan that works for you. If healthy lifestyle changes do not work, you may need medicines preescripsions or weight loss surgery

 
