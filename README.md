This project allows users to enter/prompt (query) some key parameters which can be used to determine the 'fair value' of a European put/call option.

Next, the user can enter similar prompts to evaluate a given number of price paths which can be used to forecast plausible equity price paths. Consequently, 
the corresponding option's fair value can be determined. This does assume appropriate calibration and the disadvantages of the black-Scholes model are specified.
To re-state them, they are as below: 

- Volatility is typically not constant and prone to volatility clustering, with volatility responding not only to a shock's magnitude but direction too. Leading to
  asymmetric reactions in volatility to either negative shocks (leverage effect) or positive shocks (anti-leverage). In the case of equities, which are the focus of this
  project (underlying option asset), we anticipate leverage effects, when negative shocks lead to more volatility than positive ones of equivalent magnitude.

- No sudden jumps, meaning discrete market movements are not adequately simulated

- No transaction costs are accounted for

As such, this project exists for intellectual/educational processes and SHOULD NOT be viewed as investment advice, instead, this forms the buildings blocks
used by real financial professionals. Those looking for financial advice are typically not option investors, however, should the reader be interested in investigating 
options, they should address these concerns with an asset manager with chartered financial professionals. 
