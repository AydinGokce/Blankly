## Pending documentation changes
### Incorrect
- None
### Needed
- Variables parameter for the price events to initialize the variables defaults. This is across all event types
- Add `count_decimals` to the utils
- get_price_derivative has been removed due to sklearn dependency
- `fit_parabola` has been removed due to just being old 



## Requirements for new CONTRIBUTING.md
- Redo [CONTRIBUTING.md](http://CONTRIBUTING.md) with good contributions
  - Upgrade caching system
  - Order PNL from a list of blankly orders
  - How to get started integrating your exchange
- Show that blankly only requires
  - Scheduling
  - Order execution
  - Price data
  - To take advantage of the full features
  
Run programmatic screeners across entire markets with rich results