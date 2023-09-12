# A Critical Robustness Evaluation for Referring Expression Comprehension Methods

In this hub，we display our referring expression comprehension robustness dataset and eval code for example. 
(Note, if you want evaluate your methods on our dataset, please change your *dataload.py* accoding to our dataset number id)

# The dataset

In this work, we propose a novel dataset and benchmark for the word-level adversarial robustness of Referring Expression Comprehension task. In total, we generated 338 images from 1,364 images filtered for annotation and in refcoco we generated 122 annotated images from 676 referring expression cases, in refcoco+ we generated 103 annotated images from 304 images,and in refcocog we generated 119 annotated cases from 384 raw cases (You should check it when you are going to evaluate you method.)

We divided the C2C and C2R, two parts. So you can only test your model in one type or final rate.

# The eval
`python eval.py`

We only provide the example eval code, please change your *dataload.py* to run.