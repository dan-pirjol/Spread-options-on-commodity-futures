# Spread-options-on-commodity-futures
A tutorial from CME Group on [calendar spread options on futures](https://www.cmegroup.com/education/courses/option-strategies/option-calendar-spreads.html) and their practical use.
These options are traded on many commodity futures: 

* [crude oil](https://www.cmegroup.com/markets/energy/crude-oil/light-sweet-crude.quotes.html)
* [natural gas](https://www.cmegroup.com/education/courses/introduction-to-energy/introduction-to-natural-gas/natural-gas-calendar-spread-options.html)
* [agricultural commodities](https://www.cmegroup.com/education/lessons/understanding-agricultural-calendar-spread-options.html)

There are two types of spread options:

* Options on the spread between two different assets. For example [WTI-Brent spread options](https://www.cmegroup.com/markets/energy/crude-oil/wti-brent-ice-bullet-swap-futures.quotes.html) which are linked to the difference of the two crude oil benchmarks: WTI and Brent.

* Calendar spread options: these are options on the spread between futures on the same asset with different maturities. For example, in the crude oil markets the most popular are [1-month CSO](https://www.cmegroup.com/markets/energy/crude-oil/light-sweet-crude.quotes.options.html#optionProductId=769) (Calendar Spread Options) which are linked to the price difference of two consecutive contracts, for example Apr-25 - May-25.

The project will study the pricing of these options, and their connection to the properties of the underlying futures. 

Data on spread options on futures is available from CME Group through the [Option Settlement Tool](https://www.cmegroup.com/tools-information/quikstrike/option-settlement.html)

