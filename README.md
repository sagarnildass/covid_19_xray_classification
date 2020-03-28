# COVID_19_xray_classification

1. Please find the dataset here: https://drive.google.com/open?id=1odxJF4kyHEtBqhkvz3iXpV3iQK34m6z0

2. Please find the saved weights here: https://drive.google.com/open?id=1oUUk-_pg8xhEWv0Jqyn71ojqWpMcz0Fw

## Introduction

On March 2015, Mr. Bill Gates gave a TED talk titled : "The next outbreak? We're not ready.". On 18th March, 2015, he published a post on his blog, GatesNotes. The post includes his TED Talk. He wrote that the next global pandemic could be worse than the Ebola outbreak of 2014 to 2016 that killed about 11,000 people. 
Fast forwarding 5 years, we are witnessing a world which surpassed every imagination we could have had about an apocalytic world and made us face the ultimate existential crisis. All across the world, lockdowns are in order with death tolls increasing making this a crucial time for humanity to unite together.

Coronaviruses are a large family of viruses that cause illnesses ranging from the common cold to more severe diseases. An outbreak of a new strain, given the name "2019-nCoV" and known as "novel coronavirus", was identified in China in late December 2019. The virus causes the disease Covid-19.

As of 28 March 2020, there were nearly 650000 confirmed cases of Covid-19 worldwide, and close to 31000 deaths.
Source: ReutersAt this point, the best defence we can possibly deploy is to stay at our home and avoid social gatherings at all costs. Social distancing seems to be the only way forward at the present scenario. However, as the confirmed cases are showing an exponential growth, medical facilities in many nations are getting overwhelmed by the sheer number of patients and lack of a cure as of now. 

China recently developed a helmet powered by artificial intelligence which can measure the body temperature of people in crowds a distance of upto 5 meters away.



Other AI Based solutions are being extensively delved into and researched. But even though such models have been reported to have a high sensitivity and specificity, these models should not be left to operate in isolation and without human intervention because studies have shown that these models can have very volatile predictions when comparing COVID-19 against other types of viral illness. 

In this repo, we will explore the methodology of implementing such a process and analyze the results obtained. We will use a transfer learning process coupled with a visual attention mechanism so that the deep learning agent only gives attention to parts of the image instead of looking at every part of it with equal importance. 

The dataset has been compiled by Adrian Yijie Xu. This is a combination of Kaggle Chest X-ray dataset with the COVID19 Chest X-ray dataset collected by Dr. Joseph Paul Cohen of the University of Montreal. The dataset contains 4 categories:

1. COVID19: 60 train images, 9 test images
2. Normal: 70 train images, 9 test images.
3. Pneumonia (Bacterial): 70 train images, 9 test images
4. Pneumonia (Viral) : 70 train images, 9 test images
