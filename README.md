<p align = "center"><img align = "center" src = "https://miro.medium.com/max/1200/1*9I6EIL5NG20A8se5afVmOg.gif" /></p>


<p align = "center"><img align = "center" src = "https://i.pinimg.com/564x/f0/e3/81/f0e381d0f933aa7a6695491c0615e026.jpg" /></p>

# Business **Problem** Statement

Lots of Business Hours of Customer Support are Wasted due to Some Q&A,Doubt Resolution and Other Stuffs . So to Provide and Take Every request from the customers , Company resources are inefficiently increased and it's impact business of the company. 


# Aim / Goal

- To automate customer service.
- Reduce Costing and Increases Efficiency by Providing Support in More Regional Languages


# MegatronBot - Let's Chat

MegatronBot is a fully fleged chatbot with easy to update, integrate with website, easy to deploy in any cloud services like AWS, GCP and azure with a capibility to work in production enviorment.Megatron accepts various formats of inputs you can give a text input, you can also give a Speech as a input.You can Ask in any language that is accepted by Google.

## What is the need of ChatBot?

**Megatron** was build by the team of ineuron.ai where I have worked upon a task of Intent Classification and State Tracking.The need of the MegatronBot came as ineuron.ai has a overwhemling responses and queries asked by the student over their newly released courses, as their is a Skype Support team to clarify their queries always but they cant be available 24x7 hours due to this ineuron.ai wants to build a such a great solution where the user can clarify their queries anytime without waiting in a queue for hours.


## How I have apporached to such Solution?

Building a Megatron like ChatBot requires a huge amount of data and various state of the art components.So, the first task is to get a large data,The dataset was creatd by scaraping the queries and answers asked by students over a year to their Skype support team, the dataset include of 20k sentences which were transformed and added to CSV and json format.

I have tried many State of the art language models from BERT-large to DialoGPT to RoBERTa but got an awesome results over Distilled BERT Models with ELMO embeddings.The model then trained over the 20k queries after preprocessing then adding tokens like [SEP], [START], [END] and [EOS].
  
## The Architecture of MegatronBot: -

<p align="center">
  <img width="1010" height="700" src="Megatron-ChatBot@2x (1).png">
</p>


## Below are some results: 

<p align = "center"><img align = "center" src = "NewGIF.gif" /></p>
