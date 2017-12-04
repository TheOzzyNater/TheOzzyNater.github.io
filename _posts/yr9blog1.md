---
title: Google Sheets Virtual Shop - Lessons 1&2
layout: post
author: james.osborne
permalink: /google-sheets-virtual-shop---lessons-1&2/
source-id: 1-2QSOwOM-1VaqRPQs5KMwkK3U0g0PcQwDknLcQ0no-A
published: true
---
**4.12.17**

**Google Sheets Virtual Shop - Lessons 1&2**

In the previous lesson we set up our google sheet, we chose the items we wanted to  sell and put them in a column called stock, my shop is an Apple store so it has apple products(which are ridiculously overpriced). We put the prices in the column next to that. 

We also learnt how to create a validation box, in which you can choose something from stock and you use a vlookup formula to show the unit price in the box next to it.

In today's lesson we set up the tool which times the quantity of the product by the unit price to find a total price for this. We then did a sum to work out these prices added together. We also learned how to do discounts. For mine if you buy 5 items(which I put in it's own separate box) you get 35% off, I changed this into a decimal as they’re easier to work with. You can change the number of items needed to do get the discount in a box and it’ll change the price just like that. I used this code for it to work out the discount:

if(F33>=5,(G33*J2)) - It means that if the total quantity is greater than 5 it will work out the price of the sale with the discount.

