* Random strategies
	* https://www.youtube.com/watch?v=wZmpBQts8uM

* **Bullish Strategies**
	* Moderately bullish outlook ahead
		* [Bull Call Spread](https://zerodha.com/varsity/chapter/bull-call-spread/) 
			* Buy 1 ATM call option (leg 1)
			* Sell 1 OTM call option (leg 2)
			* Ensure the following
				* All strikes belong to the same underlying
				* Belong to the same expiry series
				* Each leg involves the same number of options
			* ![[Pasted image 20240402081549.png]]
		* [Bull Put Spread](https://zerodha.com/varsity/chapter/bull-put-spread/)
			* Buy 1 OTM Put option (leg 1)
			* Sell 1 ITM Put option (leg 2)
			* Ensure the following
				* All strikes belong to the same underlying
				* Belong to the same expiry series
				* Each leg involves the same number of options
			* Conditions
				* The markets have declined considerably (therefore PUT premiums have swelled)
				* The volatility is on the higher side
				* There is plenty of time to expiry
			* ![[Pasted image 20240402081606.png]]
	* Rightly Bullish outlook
		* [Call Ratio Back Spread](https://zerodha.com/varsity/chapter/call-ratio-back-spread/)
			* Buying two OTM call option
			* Selling one ITM call option
			* ![[Pasted image 20240402081521.png]]
		* [Bear Call Ladder](https://zerodha.com/varsity/chapter/bear-call-ladder/)
			* Selling 1 ITM call option
			* Buying 1 ATM call option
			* Buying 1 OTM call option
			* ![[Pasted image 20240402083647.png]]
		* [Synthetic Long and Arbitrage](https://zerodha.com/varsity/chapter/synthetic-long-arbitrage/) : The idea with a Synthetic Long is to build a similar long Future’s payoff using options - being bullish on the underlying.
			* Buy the ATM Call Option
			* Sell the ATM Put Option
			* Ensure the following
				* The options belong to the same underlying
				* Belongs to the same expiry
	* Call Butterfly
	* Synthetic Call
	* Straps
* **Bearish Spreads**
	* [Bear Call Spread](https://zerodha.com/varsity/chapter/bear-put-spread/)  : Moderately bearish
		* Buying an ITM Put option
		* Selling an OTM Put option
		* Ensure the following
			* Same expiry and same underlying
		* ![[Pasted image 20240403074249.png]]
	* Bear Put Spread
	* Bull Put Ladder
	* Put Ratio Back spread
	* Strip
	* Synthetic Put
* **Neutral Strategies**
	* Long & Short Straddles
	* Long & Short Strangles
	* Long & Short Iron Condor
	* Long & Short Butterfly
	* Box



* Spread Strategy : Multi leg strategies, 2 or more transaction is needed.
* [Put-Call Parity](https://www.investopedia.com/terms/p/putcallparity.asp) : Put-call parity states that simultaneously holding a short European put and long European call of the same class will deliver the same return as holding one [forward contract](https://www.investopedia.com/terms/f/forwardcontract.asp) on the same underlying asset, with the same expiration, and a [forward price](https://www.investopedia.com/terms/f/forwardprice.asp) equal to the option's strike price. If the prices of the put and call options diverge so that this relationship does not hold, an [arbitrage](https://www.investopedia.com/terms/a/arbitrage.asp) opportunity exists. This means that sophisticated traders can theoretically earn a risk-free profit. Such opportunities are uncommon and short-lived in liquid markets.
