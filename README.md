# Global Interpretation Weighted Median Value Replacement for Mitigating Sensitive Attribute Leakage in Neural Networks
Authors: Amit Joshi(@amitjoshi24), Priyal Belgamwar (@priyal2506), Nikhil Ajjarapu(@nikhil-ajjarapu)

## Overview
This project aims to address the issue of sensitive attribute leakage in neural networks, which can lead to biased predictions. The proposed solution is a post-processing technique called Weighted Median Value Replacement, which modifies neuron weights to reduce bias while maintaining accuracy.

## Introduction
Neural networks are increasingly used in various high-stakes applications, such as loan approvals and criminal sentencing. However, these models can propagate and even amplify societal biases, particularly when neurons in the network learn correlations between non-sensitive and sensitive input features, leading to sensitive attribute leakage. This project introduces a post-processing technique, weighted median value replacement, to mitigate this issue.

## Problem Statement
Sensitive attribute leakage occurs when features correlated with sensitive attributes (e.g., race, gender) inadvertently influence the predictions of a neural network. This can lead to biased outcomes, disadvantaging marginalized groups. The challenge is to enhance the fairness of neural networks without significantly compromising their accuracy.

## Proposed Solution
The proposed solution involves a post-processing technique called Weighted Median Value Replacement. This method adjusts the neuron values in the neural network to be closer to the median of corresponding values across different sensitive attribute subgroups. By doing so, it reduces the correlation between non-sensitive and sensitive features, thus mitigating sensitive attribute leakage.

## Conclusion
The proposed post-processing technique, Weighted Median Value Replacement, effectively mitigates sensitive attribute leakage in neural networks. This method improves fairness without compromising accuracy, making it a viable solution for enhancing the equity of machine learning models.
