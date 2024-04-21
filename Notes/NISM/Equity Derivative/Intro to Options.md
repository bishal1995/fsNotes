
An option is a contract that gives the holder of the option the right, but not an obligation, to buy or sell the underlying asset on or before a stated date/day, at a predetermined price.
The option buyer or holder has the right but no obligation with regards to buying or selling the underlying asset, while the option writer has the obligation in the contract.

Options may be categorised into two main types:
* Call Options - buyer/holder a right to buy the underlying asset
* Put Options - buyer/holder a right to sell the underlying asset

Opening a position - adds to or creates a new trading position, can be either a purchase or a sale
* Opening purchase (Long on option): A transaction in which the purchaser’s intention is to create or increase a long position in a given series of options.
* Opening sale (Short on option): A transaction in which the seller’s intention is to create or increase a short position in a given series of options

Closing a position - reduces or eliminates an existing position by an appropriate offsetting purchase or sale. This is also known as “squaring off”
* Closing purchase: A transaction in which the purchaser’s intention is to reduce or eliminate a short position in a given series of options. This transaction is frequently referred to as “covering” a short position.
* Closing sale: A transaction in which the seller’s intention is to reduce or eliminate a long position in a given series of options.

**Moneyness of an option** - This classification helps the trader to decide which strike to trade, given a particular circumstance in the market.
* **In-the-money (ITM)** option: This option would give the option holder a positive cash flow, if it were exercised immediately. ITM options contracts have higher premiums than other options that are not ITM.
	* Call Option : The option holder can buy the security below its current market price.
	* Put Option : The option holder can sell the security above its current market price.
* **At-the-money (ATM)** option: At-the-money option would lead to zero( or minimum ) cash flow if it were exercised immediately.
* **Out-of-the-money (OTM)** option: An out-of-the-money option is one with a strike price worse than the spot price for the holder of option. In other words, this option would give the holder a negative cash flow if it were exercised immediately. It usually will have a lower premium.
	* Call Option : The option would have a higher strike price than the market price of the stock.
	* Put Option : The option would have a lower strike price than the market price.

**Option premium, defined above, consists of two components - intrinsic value and time value.**
* The **intrinsic value** of an option refers to the amount by which the option is in-the- money i.e., the amount an option buyer will realise, before adjusting for premium paid, if he exercises the option instantly. Therefore, only in-the-money options have intrinsic value whereas at-the-money and out-of-the-money options have zero intrinsic value. The intrinsic value of an option can never be negative because an option holder is not bound to exercise an option if such exercise will result in a loss to him.
	* Intrinsic Value of a Call option = Spot Price – Strike Price 
	* Put option Intrinsic value = Strike Price – Spot price
* **Time value( Extrinsic value )**: It is the difference between the premium and intrinsic value, if any, of an option. ATM and OTM options have only time value because the intrinsic value of such options is zero. 
	* The time decay causes an option to lose extrinsic value or premium as it approaches its expiration date.

Payoff Charts for Options


Risk and return profile of option contracts
.                       Risk                       Return
Long           Premium paid       Unlimited
Short          Unlimited              Premium received    


![[Pasted image 20240329232510.png]]

**Option Greeks**
* Delta : Measures how an options value changes with respect to the change in the underlying(the rate of change of premium for every unit change in the underlying).
	* Between 0 and 1( 0 to 100) for a call option
	* Between -1 and 0 (-100 to 0) for a put option
	* OTM options have a delta value between 0 and 0.5, ATM option has a delta of 0.5, and ITM option has a delta between 0.5 and 1.
	* ![[Pasted image 20240330121001.png]]
* Gamma : Gamma captures the rate of change of delta.
* Theta : All options – both Calls and Puts lose value as the expiration approaches. The Theta or **time decay factor** is the rate at which an option loses value as time passes. Theta is expressed in points lost per day when all other conditions remain the same.
* Vega measures the rate of change of premium concerning the change in volatility. Estimated by the standard deviation.
