# SABR-calibration

In this project the SABR (Stochastic Alpha Beta Rho) model is calibrated to market option data and then used in a Monte Carlo simulation to price an Asian option.

I used the DAX (Top German stocks index) options data, exported from Bloomberg terminal, since this index does not pay dividends and has European style options, hence, it's perfect for calibrating the SABR model.

I perform a simple MonteCarlo simulation, discretizing the SABR processes with an Euler scheme to price an ATM Asian Option.
