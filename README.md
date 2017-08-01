## GuessTwo

You can look at the paper which was published at ACL 2017 [here](http://www.aclweb.org/anthology/P/P17/P17-1084.pdf).  

### Abstract

Understanding common entities and their attributes is a primary requirement for any system that comprehends natural language. In order to enable learning about common entities, we introduce a novel machine comprehension task, GuessTwo: given a short paragraph comparing different aspects of two realworld semantically-similar entities, a system should guess what those entities are. Accomplishing this task requires deep language understanding which enables inference, connecting each comparison paragraph to different levels of knowledge about world entities and their attributes. So far we have crowdsourced a dataset of more than 14K comparison paragraphs comparing entities from a variety of categories such as fruits and animals. We have designed two schemes for evaluation: open-ended, and binary-choice prediction. For benchmarking further progress in the task, we have collected a set of paragraphs as the test set on which human can accomplish the task with an accuracy of 94.2% on open-ended prediction. We have implemented various models for tackling the task, ranging from semantic-driven to neural models. The semantic-driven approach outperforms the neural models, however, the results indicate that the task is very challenging across the models.

### Examples

## Red Delicious, Granny Smith

Both X and Y are fruits and a variety of apples. X and Y are generally similar in size. X are dark red in color when ripe, while Y are a bright green color. X is sweeter and softer than Y in taste and texture, sometimes starchy. Y are tart and somewhat stringy. Y is often used in cooking, whereas X is not.

## Motorcycle, Helicopter

The X and Y are two types of vehicles. X is a smaller vehicle than Y. The X has two wheels while Y has none. The X travels on roadways and smooth surfaces, whereas Y is capable of flying. Only one or two people are able to ride on X at once, while Y can carry more people.

### Download

We are collecting more data and increasing the quality. The first version is comming soon! Please fill [this](https://goo.gl/forms/pHMlPZvrou8UIY3D3) form to get the data whenever it's ready!
