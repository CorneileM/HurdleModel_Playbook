# A hurdle model playbook

A guide (with example data) to implementing highly versatile hurdle models using MCMCglmm in R (Python coming soon).

Many real-world phenomena follow a process characterised by abundant opportunities that rarely convert (zero-inflated binary response), and if the opportunity converts, it converts at a variable magnitude (count or continuous).

For example, let's say we want to model the success of a free trial subscription initiative. Every customer that starts a free trial will have the opportunity to either continue with a paid subscription or end the trial and opt out (binary response = paid or opt-out). We would expect most customers to opt out, with a minority of customers converting to a paid subscription. Within the group of customers that convert, we would also expect the magnitude of the conversion (number of months on paid subscription) to vary widely between customers. Both the binary (whether customers convert to paid) and magnitude (number of months on paid) response data contain valuable information on the factors that affect the success and failure of the free trial subscription initiative.

Hurdle models are great at modelling these processes.

[incomplete]
