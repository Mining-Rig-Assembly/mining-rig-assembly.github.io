---
layout: page
title: About
permalink: /about/
---

## Introduction

[Mining Rig Assembly](http://rigassembly.web.engr.illinois.edu/) is a Web-based Application that allows the users to browse different parts of a mining rig, store rig setups, and estimate the performance of their setups on one integrated site. Users can set their expected payback periods for the setups, and our application will calculate the potential proﬁts of them based on real-time price information, and notify the user when their expected payback periods can be achieved. Whats more, this website can visualize the performance comparison between different setups and components for speciﬁc users.

## Description
1. There are several websites that help users assemble mining rigs for bit-coin, but few of them focus on Ether. Our website targets the Ether investors.
2. Users can know when their expected payback period will be met. Our website will calculate the payback period of different setups dynamically, and send an email to the users once the payback period meet the expectation.
3. Users can obtain the performance comparisons between their setups and components. We not only visualize the performance of the setups and the components, but also the comparison between setups and components. This is a practical function for users as they can view and choose their setup more intuitively.

## Functionality
1. Display list of components in the database(CPU, GPU, motherboard, power supply, RAM).
2. Store user setup speciﬁed in user input.
3. Display speciﬁed component information.
4. Calculate total price and payback period.
5. Compare component parts between different setups with visualization.

## Advanced Functions

1. Calculate payback period of the mining rig investment 
	- This function is the core of this application. It allows the users to plan their investments without having to monitor every little aspect of the market at all time. It is especially useful, and convenient to have in the current situation because of how rapidly the prices are changing. This function is advanced because it requires additional data from GPU such as hash rate and power consumption. Also, it update ETH price and component price in the database automatically and send email notiﬁcation to user if they subscribe the set they created.
2. Comparisons between different parts/setups with visualization 
	- This can help user easier to understand the trade-off of different setups and choose the best setup based on the comparison. This function is advanced because it needs to summarize data into useful information such as total price of the setup and the payback period for each user setups for comparison.
