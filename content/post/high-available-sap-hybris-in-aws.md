+++
title = "High available SAP hybris in AWS"
draft = true
tags = ["aws", "hybris"]
date = "2017-03-03T14:03:52-05:00"
+++

# Plan
1. provide classical three-tier on promise hybris deployment
2. analyze approach for high availability for on demand solution
3. consider tier by tier how it should be transformed to be high available and cost efficient in AWS deployment
  * web tier. S3 ow even nothing.
  * app tier. Auto scale group (even to fulfill contract).
  * DB tier. Multi-AZ deployment.
4. What if everything goes wrong - DR.
  * analyze what is proposed by Amazon in their white paper
  * analyze how to have DR environment in another Region.
