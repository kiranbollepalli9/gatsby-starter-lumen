---
template: post
title: 'How DSP, SSP and AdExchange works?'
slug: adtech
draft: true
date: 2020-05-13T00:39:52.636Z
description: Describes about ad loading mechanism
category: Adtech
tags:
  - adtech
  - DSP
  - SSP
  - AdExchange
---
From a technical point of view, two parties are involved in the process of purchasing advertising in programmatic. They are the **sell-side** and **buy-side**.

On the seller’s side, there are **SSP** (Supply / Sell Side platform, a platform for selling advertising space on publisher sites), Ad Exchanges and Ad Networks.

In its turn, **[DSP](http://ubidex.io/ "ubidex.io")(**Demand Side Platform)is working in the interests of the buyer.

**Ad Exchange** is a kind of virtual marketplace. Publishers (SSPs) fill Ad Exchange platforms with ad space offerings. Advertisers (DSPs), in turn, choose the offers that best suit them.

![ad exchange](/media/ad-exchange.jpeg "ad exchange")

###### **source:**<https://www.quora.com/topic/Supply-Side-Platform-SSP>

**Process:**

* User opens the website
* Website sends request to display ad to Ad exchange through SSP.
* SSP places information about ad request on Ad Exchange, in which DSP's will participate
* DSP's will check received user information in their own database (DSP's can also purchase data from DMPs)
* DSP makes a bet ( if user meets requirement of advertiser/buyer)  Based on: Data specified in SSP, own DSP data, data from DSP
* SSP selects highest bid from offered options
* The website will receive ad from auction winner and show it to user who has been targeted.
