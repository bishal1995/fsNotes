![[Screenshot from 2024-04-15 07-54-18.png]]
Replication in Derivatives : Replication is the creation of an asset or a portfolio from another asset, portfolio, and/or derivative. Example: stock + short forward = risk-free asset.

Option Greeks
- Delta : Sensitivity of the option price to the change in the underlying price
- Gamma : Sensitivity of the option delta to the change in the underlying price
- Vega : Sensitivity of the option price to the change in implied volatility 
- Theta : Expected change in the option price with the passage of time assuming risk-neutral growth in the asset
- Rho : Sensitivity of the option price to interest rates or dividend payout

Two perspective of derivative
* User : Interested in terminal values of a derivative
* Manufacturer : Dynamic Hedging

Derivatives are not always linear, convex or concave , A test of local linearity of a derivative security between asset prices S1 and S2 with 0 <  λ < 1, will satisfy the following equality .
 V( λS1  + (1- λ)S2 )= λV(S1) + (1 - λ)V(S2)
	 It will be convex if      V( λS1  + (1- λ)S2 ) <= λV(S1) + (1 - λ)V(S2)
	 It will be concave if    V( λS1  + (1- λ)S2 ) >= λV(S1) + (1 - λ)V(S2)
	
A linear security constantly behaves like a line, it will have a delta but no other greeks

![[Screenshot from 2024-04-15 08-28-07.png]]

Synthetic Security  : Linear combination of two or more primary instrument in the markets.For e.g. : A basket's prices derived from a weighted combination of existing primary intruments ( SnP500 ).



A contingent claim is another term for a derivative with a payout that is dependent on the realisation of some uncertain future event, For eg Options

A straight claim 

The Contamination( Or convexity ) Principal : If there is a possible spot in time and space capable of bringing a profit, then the areas surrounding it need to account for the affect. Convexity is that measure of value that gives the call option a non-zero value today. If the value of an at the money (ATM) call option is zero today then no one will buy the option and yet ATM calls are the most liquid and traded of all options in any asset class. In fact, almost all of this value for an ATM option comes from this notion of "convexity". So when you are buying an ATM option you are actually buying convexity or the gamma.
![[Screenshot from 2024-04-16 08-53-49.png]]
![[Screenshot from 2024-04-16 08-54-13.png]]

Hard and soft optionality : **Optionality** is a broad term used by trader to describe a non linearity on the payoff of an instrument. As an extension of the contamination principle , every item with optionality needs to trade at a premium and the shrinkage of the premium with the passage of time ( owing to the narrowing of the probability measure of events ) will mean that every item with opationality will have time decay.

It is convenient to call hard optionality the situation where a contract has a strike price and soft optionality the situation where the contract has a builtin convexity but no real strike price, Soft optionality presents generally milder gamma and other Greeks but will present more stable features across time.

