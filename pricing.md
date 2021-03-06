---

copyright:
  years: 2016,2018
lastupdated: "2018-01-03"

keywords: scylla, compose

subcollection: ComposeForScyllaDB

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# Pricing
{: #pricing}

## Base Configuration

An {{site.data.keyword.composeForScyllaDB_full}} service starts with three member nodes, each with 5 GB storage and 512 MB of memory, which is equal to five units of resources. The service _includes_ replication and high-availability, so each unit and the price per unit _includes_ the cost of the resources across all three nodes.

The base configuration also includes three HAProxy portals that provide connections to the cluster. Each HAProxy portal has 64 MB and supports authentication, HTTPS, and IP address whitelisting.

The base service configuration has a set price, which you can find for your local currency on the catalog tiles on {{site.data.keyword.cloud_notm}}. For example, the base price in US dollars is $90/month.

## Increasing resources

If you need more storage or memory for your service, you can increase the resources that are allocated in a 10:1 ratio of disk storage to memory unit. Increasing the disk space that is allocated to the deployment also increases the RAM allocated. A {{site.data.keyword.composeForScyllaDB}} unit consists of 1 GB of storage and 102 MB of memory, and each unit and the price per unit _includes_ the cost to increase the resources on all three of the cluster's nodes.

## Calculating the cost of your deployment
{: #tiered-pricing}

Each additional unit (1 GB storage/102 MB memory) has a per unit price, which is listed in your local currency on the {{site.data.keyword.cloud_notm}} catalog tile for the service. In US dollars each additional unit costs $18. As the _total_ size of all your {{site.data.keyword.composeForScyllaDB}} services increases, the per unit price decreases, as shown in the tiered pricing table.

Number of Units|Price per Unit
----------|-----------
5 - 9 units|Base price per unit - $18.00 USD/Unit
10 - 24 units|10% reduction - $16.20 USD/Unit
25 - 49 units|20% reduction - $14.40 USD/Unit
50 - 99 units|30% reduction - $12.60 USD/Unit
100 - 499 units|40% reduction - $10.80 USD/Unit
500 - 999 units|50% reduction - $9.00 USD/Unit
1,000 - 4,999 units|60% reduction - $7.20 USD/Unit
5,000+ units|70% reduction - $5.40 USD/Unt
{: caption="Table 1. {{site.data.keyword.composeForScyllaDB}} tiered pricing" caption-side="top"}
