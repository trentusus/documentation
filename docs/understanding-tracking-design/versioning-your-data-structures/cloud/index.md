---
title: "Versioning Data Structures in BDP Cloud"
date: "2023-03-01"
sidebar_position: 10
---

# Versioning in BDP Cloud

If you are a BDP Cloud customer, you will have used our Data Structure Builder to create your custom Data Structures for your Events and Entities.

![](../../managing-data-structures-with-data-structures-builder/images/data-structures-2.png)

**Breaking and non-breaking changes**

At the point of publishing a data structure, there are two options for versioning:
- **Non-breaking** - a non-breaking change is backward compatible with historical data and your warehouse loader.
- **Breaking** - a breaking change is not backwards compatible with historical data and/or your warehouse loader.

The Data Structure builder will automatically select how to version up your data structure depending on the changes you have just made.

![](images/data-structures-1.png)
![](images/data-structures-2.png)