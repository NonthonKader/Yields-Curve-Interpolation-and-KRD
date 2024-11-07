# Yields Curve Interpolations techniques and Key Rates Duration analysis

This work draws on the Harvard Business School case study “Deutsche Bank: Finding Relative-Value Trades,” which examines the strategic and analytical operations of Deutsche Bank’s Fixed Income Research Group, led by Jamil Baz in August 2003.

The Fixed Income Research Group holds a pivotal role at Deutsche Bank, uncovering opportunities in bond markets and interest rate derivatives. Balancing long-term macroeconomic perspectives with short-term, actionable trade ideas, the team uses a proprietary three-factor yield curve model to evaluate U.S. Treasury bonds and identify relative-value trades. Their aim is to detect mispriced assets that can yield profitable returns.

In our project, we use Deutsche Bank’s data and findings as a foundation. Our objective is to bootstrap zero-coupon bond yields from a set of coupon-bearing bond prices provided by the Deutsche Bank team, contextualizing our work in August 2003.

Once we’ve extracted the yield curve, we apply various interpolation techniques to create a continuous discount function, focusing particularly on cubic spline interpolation and the Nelson-Siegel yield curve description function. We then compare our findings to Deutsche Bank’s model results, exploring how, under the assumption of accurate model outputs, one might implement strategies to capitalize on market mispricings. 

Additionally, we evaluate key rate duration for portfolios, a crucial metric for pricing and hedging interest rate-sensitive products.

All results and discussions are documented in the final Jupyter notebook.
