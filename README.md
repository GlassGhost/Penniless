#Penniless
________

Nobody likes them, and as a US Taxpayer you are paying twice for every penny you touch since it cost 1.7 cents to manufacture(in 2016).

You or anyone you work with never has to touch a penny again, here are your equations:

SmartDenom = (MinDenom * (1 / (1 + TAX_RATE)))  
FinalPrice = (1 + TAX_RATE) * (ceil(MinPrice / SmartDenom) * SmartDenom)  
ActualPriceCharged = FinalPrice/(1 + TAX_RATE)  
Taxes = TAX_RATE*(FinalPrice/(1 + TAX_RATE))

These work in all situations were flat tax rates are charged.
___

#e.g. exempli gratia

In order to touch nothing smaller than a nickel = 0.05 in Texas with a tax rate of 8.25% or .0825  
The **FinalPrice** you show your customers **AFTER taxes** is **EXACTLY** $1.55 = 1.0825 * (ceil(1.40/0.04619) * 0.04619), on an item that you charge a minimum of $1.40 for. Where 0.04619 = SmartDenom

And when you are asked about why taxes aren't being payed on your items, you show them that the ActualPriceCharged is 1.43187=(1.55/1.0825) for the item. And you have the remaining Taxes $0.11813=.0825⋅(1.55/1.0825) ready to give to the state.

<object type="image/png" data="Pennt2012.png"></object>
