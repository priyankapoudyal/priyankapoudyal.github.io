+++
draft = false
author = "Priyanka Poudyal"
title = "Framing concept in machine learning"
date = "2022-06-12"
description = "A detailed blog post that explain framing concepts in machine learning."
featured = false
comment = true
toc = true
categories = [
"Machine Learning"
]
tags = [
"ML",
"Framing",
]
images = [
]
+++

This article explains basic concept of framing used in machine  learning. Also, it describes different method to create framing using python.

<!--more-->

## Introduction 

In simple words, machine learning is using data to answers queestions. Machine learning is about creating models from  inputs, to provide output froms predictions which might be previously seen or unseen. 
label : label is  a output of data. label are future prediction. in labeled example both features and labels are included. i.e   
                 labeled examples: {features, label}: (x, y)
labled examples is use to train the model. 
unlabeled example: this includes only features but not a label. once labeled example trains the model then unlabeled example can use model to predict the label. 
                 unlabeled examples: {features, ? }: (x, ?) 
                  