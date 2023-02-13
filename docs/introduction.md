# **Introduction**

## **What is Yuyu ?**

Yuyu is a plugin in openstack that makes it easy for you to manage your openstack bills.

---

## **What does yuyu count?**
Yuyu can set a price for the following OpenStack feature bellow :

### 1. Pricing

Yuyu can set a price for the following OpenStack feature.

### 2. Instance Flavor

You can set the price for each Flavor that you have. Each instance that uses a flavor will be counted for Billing. You still be charged for instance even if the instance is stopped unless you delete it.

### 3. Volume

You can set the price for each **volume type** per 1 GB. You will be charged for every allocation. The the space allocated will be rounded up before calculating the price. For example you have a volume of 2.3 GB, that volume will be counted as 3 GB.

### 4. Floating IP

You can set the price for each Floating IP that you allocate. 

### 5. Router

You can set the price for each Floating IP you allocate that has an external gateway set. Only router that has an external gateway that will be counted, router without external gateway will not be Counted

### 6. Snapshot

You can set the price for each snapshot you take per 1 GB. Same with volume, the space allocated will be rounded up before calculating the price.

### 7. Image

You can set the price for each image you create per 1 GB. Same with volume and Snapshot, the space allocated will be rounded up before calculating the price.
