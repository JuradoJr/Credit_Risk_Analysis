# Credit_Risk_Analysis
## Overview of the analysis:
In this project, we conducted supervised machine learning to be able to determine a user’s credit risk. We did this by creating models, training the models, then evaluating the models through various sampling methods such as over-sampling, under-sampling, and combination sampling.



## Results:
The Naive Random Over-sampling results show that there is low precision due to a low positivity percentage and high recall percentage as well as the accuracy test being midrange. 
<img width="889" alt="Screen Shot 2022-10-16 at 11 45 40 AM" src="https://user-images.githubusercontent.com/104862099/196053079-c6c08029-edc2-4d81-b615-34c03ed45ec3.png">

The SMOTE over-sampling results show that there is low precision due to a low positivity percentage and a midrange recall percentage as well as the accuracy test being midrange.
<img width="896" alt="Screen Shot 2022-10-16 at 11 45 49 AM" src="https://user-images.githubusercontent.com/104862099/196053083-d549502d-3478-40ee-b1e6-78b395787e13.png">


The Under-sampling results show that there is high precision due to a high positivity percentage and a mid to low recall percentage as well as the accuracy test being midrange.
<img width="909" alt="Screen Shot 2022-10-16 at 11 46 19 AM" src="https://user-images.githubusercontent.com/104862099/196053087-068ff5d9-80b0-47f3-95ab-52b4dd8ad030.png">

The combination results show that there is high precision due to a high positivity percentage and a midrange recall percentage as well as the accuracy test being midrange.
<img width="884" alt="Screen Shot 2022-10-16 at 11 46 44 AM" src="https://user-images.githubusercontent.com/104862099/196053091-05558380-6f8b-447a-9033-82cb1b302a20.png">

The Balanced Random Forest Classifier results show that there is high precision due to a high positivity percentage and a high recall percentage as well as the accuracy test being high.
<img width="901" alt="Screen Shot 2022-10-16 at 11 47 14 AM" src="https://user-images.githubusercontent.com/104862099/196053094-fb752c52-8d10-48bc-8af4-5c9469d11274.png">

The Easy Ensemble AdaBoost results show that there is high precision due to a high positivity percentage and a high recall percentage as well as the accuracy test being high.
<img width="907" alt="Screen Shot 2022-10-16 at 11 47 26 AM" src="https://user-images.githubusercontent.com/104862099/196053096-b6a8f9f8-e8ae-4fff-9686-9d7b0d87d2a3.png">



## Summary: 

Within our six total models, for the first two models we used over-sampling using the SMOTE and Naive method, the next model was under-sampled, the one after that was a combination of both, and the final two were the balanced random first classifier model and Easy Ensemble AdaBoost model. In conclusion, we noticed that out of all the six different types of models, the Easy Ensemble AdaBoost Classifier model had the best results due to its high precision, accuracy, and recall scores. 
