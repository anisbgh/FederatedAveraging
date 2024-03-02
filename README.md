
# Client Selection for (Hierarchical) Federated Learning

This project was achieved during my BSc thesis at the university of Tübingen - Germany.

- FL-LR: implementation of linear regression
- FedAvg_MNIST: implementation of FedAvg algorithm
- HierFedAvg_MNIST: implementation of HierFedAvg




## Appendix

Thesis was discussed and awarded the grade 1.3. All rights are reserved by the author.


## Authors

[@anisbgh](https://github.com/anisbgh)


## Abstract

In the last few years, machine learning has become more and more popular. It is
even now considered to be the standard and the backbone of numerous services
and applications used by millions of users around the world on a daily basis. The
popularity of machine learning comes from its robustness in solving problems like
statistical predictions, image recognition and classification and also natural language
processing, these capabilities can be applied to larger scales and combined to perform
tasks and design systems that are state of the art.
Machine learning depends heavily on data, designing and training machine learning
models to be as efficient as possible requires continuous data mining and storing it
centrally. This data mining process almost always, and sometimes even exclusively,
involves the end user, so collecting information and storing users’ data has become
a common practice in the field of machine learning.
With the noticeable increase in privacy awareness and the several breaches and
scandals, the centralization of data collection and storage in machine learning was
heavily criticized and challenged, mainly because it is done in non-controlled way
using invasive methods that caused concerns both morally and lawfully.
A new technique has then been introduced, called federated learning, which elim-
inates the need to store any user specific data centrally, but the machine learning
model would be trained locally on each client’s end and then aggregated without
exposing any sensitive information.
In this thesis we will introduce the mechanism and structure of a federated learning
model, survey its features and drawbacks and look at the effects of its different
parameters, mainly client selection, on its performance.
