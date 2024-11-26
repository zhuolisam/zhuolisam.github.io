---
title : "General Prediction Framework at Uber"
date: 2024-11-27T00:00:00+08:00
publishDate : 2024-11-27T00:00:00+08:00
draft : false
tags : ["tech", "dynamic-pricing", "case-study"]

---


I often sees icon showing estimated price and estimated delivery time in Grab app or other ride-hailing apps. I was kind of interested of knowing how dynamic pricing and general predictions in ride-hailing apps or food-delivery apps works. Hence I started reading some articles. 

There're two interesting reads particularly. One to understand concept of dynamic pricing, and another on one possible implementation of dynamic pricing or general prediction.
- [How does Uber do Surge Pricing using Location Data? | by Anubhav Pattnaik | Medium](https://anubpattnaik.medium.com/how-does-uber-do-price-surge-using-location-data-cfee03415022)
- [Engineering Uber Predictions in Real Time with ELK | Uber Blog](https://www.uber.com/en-ID/blog/elk/)



Some new things I've learned:
1. Rather than optimizing for company profit, surge-pricing, or dynamic pricing in e-hailing services are actually designed to rearrange supply and demand. The changes it brings into the market are:
	1. Reduces the demand for cars
	2. Shift supply of drivers to areas of high demand.
	3. Encourage new stream of supply
2. Consider using unsupervised-learning algorithm to solve data cold starts.
3. When searching in huge data space, rearranging queries can optimize the performance and throughput a lot.