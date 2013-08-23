# Outline
## Outline

> The importance of third country policy representation in the ex-ante assessment of FTAs

1. Motivation
2. Trade diversion/creation; measuring impacts on welfare and trade patterns
3. Modelling TRQs in equilibrium models
4. Simple theoretical model of international trade
5. Large-scale equilibrium model of global agriculture: CAPRI
6. Conclusions


# Research Objective 
## Research Objective 

How important is the policy representation of third countries when assessing and FTA?

* Focusing on ex-ante assessments made with Applied Equilibrium Models (AEM)
* Current state: often simplified in "real life" impact assessments
* How big is the bias induced by the simplification/ignorance?

How to assess?

* Pick one policy instrument (TRQ) and analyze the impacts in depth
* Contrast different TRQ implementation techniques in AEMs
* Impacts in a small theoretical equilibrium framwork
* Impacts in a large-scale ("mainstream") equilibrium model

# Motivation
## Motivation

Global trade liberalisation through PTAs?

* WTO negotiations are stalled
* Are PTAs the second best alternative in thriving for multilateral trade liberalisation?
* Some analysts (optimists) already say:

	> Free trade agreements [...] are the likeliest pathway to multilateral trade liberalisation.

* Increasing number of PTAs have been negotiated in the last few years
* Two large-scale PTAs are ahead of us: EU-US, Trans-Pacific Partnership
* The ex-ante toolbox for impact assessment needs to be revised


# Methodological framework
## Methodological framework

Hypothetic FTA scenario in an equilibrium framework under different TRQ implementations

* Start in small: first evaluate with a small theoretical modell (3 regions, 1 commodity)
* Extend: realistic EU-US trade deal scenarios with the CAPRI model

Measure the impacts on welfare and trade patterns

* Trade diversion:
 
	> Shift of imports from low cost third country producers to higher cost producers enjoying trade preferences

* Trade creation:

	> Higher cost domestic goods are substituted with lower cost imports from new partners


## Welfare decomposition and changes in trade 

Replace the standard Vinerian framework with _money metric_ and measures of _changes in traded volumes_


### Money metric

> Income equivalent (expenditure) of the utility at constant prices of the initial point


### Trade diversion

> Shift in imported volumes from third countries to the members of the FTA

### Trade creation

> Replacement of domestically produced goods with preferential imports in the consumption bundle


# Modelling TRQs in equilibrium models 
## Modelling TRQs in equilibrium models 

Two approaches are in widespread use:

1. Simplified to a fixed tariff equivalent (ad valorem, AVE)
2. Variable tariff rate depending on imports vs. quota limit


Practical problems with tariff calculations (general)

* Selection of correct _Unit Value_ (convert specific to ad valorem)
* Suitable _aggregation_ method to the level of commodities in the model

Practical problems (TRQ related)

* Set a _shadow tariff_ that correctly represents the border protection of marginal imports provided by the TRQ 
* With explicit TRQ representation this becomes a calibration issue


## Variable tariffs under TRQ (sigmoid)

### Smooth approximation of the two-tiered tariff regime
\centerline{\includegraphics[height=1.3in]{sigmoid_family.png}}

* Family of sigmoid functions
* Applied tariff is the function of imports, pref. and MFN rates
* Great flexibility for calibration
* Used in CAPRI (see later)


## Variable tariffs under TRQ (orthogonality constraints)

### Complementarity Slackness conditions in an MCP framework

$$ Q - I_{in} \ge 0  \: \bot  \: r \ge 0 $$
$$ t_{MFN} - t_{Pref} \ge r \: \bot \: I_{out} \ge 0 $$
$$ I \ge I_{in} - I_{out} \: \bot \: I_{in} \ge 0 $$


###

* Interpreted as Market regimes under TRQ (under-, overfill)
* Calibration to non-zero shadow rate is only possible when the quota is filled
* => shifting effective quota levels to handle data errors
* Used in most CGE models (e.g. IMPACT, GLOBE)

# Simple theoretical model of international trade
## Simple theoretical model of international trade

Model Features:

* 3 countries (R1,R2,R3), 1 traded commodity (X1)
* Maximize producer and consumer surplus increased with tariff revenues
* Demand side: Generalized Leontief expenditure system
* Supply side: behavioural functions derived from Normalized Quadratic profit func.
* Elasticities are subject to regulatory conditions
* Armington approach for modelling bilateral trade
* The strucuture mimics that of the CAPRI market module

## Baseline and scenario assumptions

* Hypothetical scenario: region R1 and R2 negotiate an FTA
* R1 has a TRQ with R3 (third country, rest of the world)
* 3 implementations for the TRQ:
	* fixed AVE
	* explicit representation with sigmoid function 
	* explicit representation with orthogonality conditions
* Equal border protection in basline, 25% ad valorem
* Baseline assumption on TRQ:
	* binding quotas with 100% fill rate
	* shadow tariff is half the 25% (SA later)
* Armington substitution elasticities:
	* first tier  = 4 (Arm1)
	* second tier = 7 (Arm2)
	
<!---
* traded volume is set around 10% of domestic supply in the baseline
* random noise added to the price levels to initialize the Armington system
-->

# Results of the simple theoretical model
## Impact on trade patterns in the theoretical model

* The TRQ prevents the drop in R1 imports from R3
* Trade diversion impacts are overestimated under AVE repr.
* Trade creation impacts are overestimated under explicit repr.
* No significant difference between the two explicit representations
* Trade creation > Trade diversion => overall positive welfare impact on R1?


<!---
table here: Impact on trade patterns
-->

\begin{table}[ht]
\centering
\begin{tabular}{llrrr}
  \hline
measure & region & AVE & Sigmoid & \specialcell{Orthog.\\cond.} \\ 
  \hline
trade diversion & R1 & 30.8 & 0.4 & 0.0 \\ 
  trade diversion & R2 & 19.8 & 23.9 & 24.0 \\ 
  trade creation & R1 & 109.7 & 116.4 & 116.2 \\ 
  trade creation & R2 & 104.7 & 101.6 & 101.6 \\ 
   \hline
\end{tabular}
\end{table}


## Closer look at agriculture (domestic side of the story)

* Domestic demand for domestic products decreases => domestic sales $\downarrow$

<!---
graph here
-->
\centerline{\includegraphics[height=2in]{figure/trade_div.png}} 


## Closer look at agriculture (foreign trade side of the story)

* Foreign demand for domestic goods increases => exports $\uparrow$
* The change in total demand for domestic production is the compound effect of the above two
* Bigger impacts on domestic sales with explicit TRQ representation:
	* drop in import price of marginal imports from R3
	* BUT the quota remains bound
	* bigger pressure on domestic sales by foreing trade
* Bigger impacts also on exports with explicit TRQ representation
* The overall impact on agricultural profits is ambigous 
	

## Impact on welfare in the theoretical model


* Welfare in R3 shrinks (TRQ rent, tariff revenues, agric. profit)
* Change in agr. profit in R1 is of different signs!


<!---
	* Loses most of the income from TRQ rent
	* Part of the tariff revenues are gone (decrease in imports)
	* Profit of agricultural sector decreases (decreasing exports)
table here: Impact on welfare
-->	

\begin{table}[ht]
\centering
\begin{tabular}{llrrr}
  \hline
region & item & AVE & sigmoid & orth \\ 
  \hline
R1 & CSSP & 5.3 & 6.9 & 6.9 \\ 
  R1 & ProfitAgr & 0.2 & -0.8 & -0.8 \\ 
  R1 & TrqRent\_government &  & -76.5 & -77.3 \\ 
  R1 & Tariff\_revenues & -81.1 & -100.0 & -100.0 \\ 
  R1 & Total & 1.8 & 2.6 & 2.6 \\ 
  R3 & CSSP & 2.3 & 1.2 & 1.2 \\ 
  R3 & ProfitAgr & -5.1 & -2.6 & -2.6 \\ 
  R3 & TrqRent\_exporters &  & -76.5 & -77.3 \\ 
  R3 & Tariff\_revenues & -9.0 & -4.2 & -4.1 \\ 
  R3 & Total & -0.2 & -0.4 & -0.4 \\ 
   \hline
\end{tabular}
\caption{Welfare impacts (percentage change relative to baseline)} 
\end{table}



# Sensitivity Analysis with the simple theoretical model
## Sensitivity Analysis on Armington elasticities


* Trade diversion increases with the Armington elasticities
* Explicit repr.: trade diversion only when substitution between domestic and foreign is limited but substitution among trading partners is elastic

\centerline{\includegraphics[height=2in]{figure/unnamed-chunk-2.png}} 





## S.A. ctnd., shadow rate in the calibration point

Trade diversion occurs only if the shadow rate in calibration point is below 9% (by explicit TRQ representation)

\begin{table}[ht]
\centering
\begin{tabular}{rrrr}
  \hline
shadowrate & SIM\_AVE & sim\_sigm & sim\_orth \\ 
  \hline
2.50 & 30.78 & 23.78 & 23.78 \\ 
  3.50 & 30.78 & 20.53 & 20.53 \\ 
  4.50 & 30.78 & 17.20 & 17.20 \\ 
  5.50 & 30.78 & 13.81 & 13.81 \\ 
  6.50 & 30.78 & 10.34 & 10.34 \\ 
  7.50 & 30.78 & 6.82 & 6.82 \\ 
  8.50 & 30.78 & 3.23 & 3.23 \\ 
  9.50 & 30.78 & 0.90 & 0.00 \\ 
  10.50 & 30.78 & 0.63 & 0.00 \\ 
  11.50 & 30.78 & 0.51 & 0.00 \\ 
  12.50 & 30.78 & 0.44 & 0.00 \\ 
   \hline
\end{tabular}
\caption{Trade diversion in R1} 
\end{table}

# Intro to CAPRI and customization for the study
## Short introduction to CAPRI

* Comparative static, partial equilibrium model
* Iterative link between (a) supply models of the EU and (b) global market model
* PMP models for the EU supply
* Nonlinear system of equations solving for the Kuhn-Tucker conditions of maximizing consumer and producer surplus increased with tariff revenues
* Market module covers 77 countries and 47 commodities
* Two-stage Armington system for bilateral trade
* Explicit policy representation for 

    * bi- and multi lateral TRQs
    * export subsidies
	* public intervention
	* flexible levies
	* and the entry price system for fruits and vegetables in the EU


## Introducing AVE representation of EU tariffs

The AVE-rate of the TRQ depends on the fill rate:

* _below 90%:_ AVE=Preferential rate
* _90-99%:_ AVE=average(Preferential, MFN) 
* _above 99%:_ AVE=MFN rate

Reminder on unit values (UV) in CAPRI:

* Weighted average of single bilateral UVs and world UVs
* Weight: probability that the observed single unit values were created with a fitted normal distribution

Reminder on tariff aggregation in CAPRI:

* From HS6 to CAPRI commodities
* Combination of 3 weighting schemes:
	1 naive bilateral trade weighting
	2 weighting with average world import values
	3 simple arithmetic mean


# CAPRI scenario results
## EU-US FTA scenario with CAPRI

### Scenario setup (EU-US FTA):

* Full liberalisation for agricultural commodities 
* Same scenario is run with explicit TRQ repr. and AVE repr.
* NTBs and other sectors of the economy are not included (partial impacts)

### Impacts on trade patterns:

* EU imports from third countries decrease to a greater extent under AVE repr. ($\rightarrow$ trade diversion)
* Significant differences among commodities (market regimes differ)
* Most pronounced difference for meats (fall in 3rd country imports: -88% AVE, -1% sigmoid)


## EU-US FTA scenario with CAPRI

### Welfare impacts:

* Negligible total welfare impact
* BUT the sign of the change in agricultural profits is different in the two scens. (+ AVE, - sigmoid)
* Similar impacts as with the theoretical model, but more cross-effects

\centerline{\includegraphics[height=1.5in]{figure/welfare_EU.png}} 


## Conclusions

* Neglecting explicit policy representation might have a significant impact on simulation results (+/- Agric. profits)
* AVE representation overestimates trade diversion effects
* Explicit represenations overestimate trade creation impacts
* Impacts on agricultural profits are highly dependent on 
	* calibration point (shadow rate, fill rate, import shares, relative prices, ...)
	* policy representation with third countries
	* model parameters (Armington-, supply and demand elasticities, etc.)
	
* Demonstrated sensitivity to calibrated quota rents and Armington elasticities



