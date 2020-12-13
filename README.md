# SIFMA Municipal Swap Index Curve 

SIFMA (Securities Industry and Financial Markets Association) is a trading organization in US. The SIFMA Municipal Swap Index, formerly the Bond Market Association Index, is a market index composed of tax-exempt variable rate demand obligations (VRDOs). VRDOs are municipal bonds with floating interest rates. The SIFMA index is issued weekly. 

The SIFMA rate for each interest payment period is equal to the weighted average of the SIFMA index value. Both SIFMA and LIBOR are popular floating rate index. The SIFMA rate represents the average interest rate payable on tax-exempt variable rate demand obligations, while the LIBOR rate represents the interest rate payable on non-tax exempt demand obligations. In general, the SIFMA rate trades as a proportion of LIBOR rate.

The coupon rates of many floating rate bonds or floating rate callable bonds refer to SIFMA index. The change of index has quite impact on the bond values. Thus, the SIFMA curve is major used to price various bonds, such as municipal bonds, municipal debts, bond purchase agreements, etc.

A SIFMA curve is shown below:

CurveName	Instrument	ValuationDate	Tenor	Value
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.1Y	2020-03-26	1Y        	0.006
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.2Y	2020-03-26	2Y        	0.00555
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.3Y	2020-03-26	3Y        	0.00535
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.4Y	2020-03-26	4Y        	0.00525
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.5Y	2020-03-26	5Y        	0.00515
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.7Y	2020-03-26	7Y        	0.00485
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.10Y	2020-03-26	10Y       	0.00455
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.12Y	2020-03-26	12Y       	0.0044
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.15Y	2020-03-26	15Y       	0.0041
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.20Y	2020-03-26	20Y       	0.00375
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.25Y	2020-03-26	25Y       	0.0035
USD_SIFMA3M_BASIS	BasisSpread.USD.SIFMA3M-LIBOR3M.30Y	2020-03-26	30Y       	0.0032


You can find more details at
https://finpricing.com/lib/IrSifmaCurve.html
