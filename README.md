The Citi Bike system in New York operates over 900 stations
and 14,000 bikes, serving millions of riders annually[1].
A key operational challenge is overnight rebalancing: operators
must reposition bikes to ensure adequate supply at each
station for the next day[2]. Inaccurate forecasts lead to either
bike shortages (lost revenue, customer dissatisfaction) or overallocation
(excess maintenance and storage costs). This project
targets ≥ 99% daily coverage while minimizing operational
costs. This project addresses the prediction challenge through four
core research questions: (RQ1) Can Citi Bike stations be
spatially clustered into at least 20 operationally meaningful
clusters based on geographic proximity? (RQ2) Can timeseries
models, accurately predict hourly pickups and dropoffs
for each cluster over the next 24 hours? (RQ3) Can
these forecasts be used to compute optimal bike allocations
per cluster to minimize shortages over the following day via
cumulative net demand calculations? (RQ4) Can safety-stock
levels be optimized to minimize total operational costs, given
asymmetric penalties of 3$ per missed ride versus 0.5$ per
excess bike?

To address these questions, we employ clustering for station
segmentation and develop a custom lagged-feature linear
regression model designed to capture multi-seasonal demand
patterns. Beyond the mandatory tasks, an exploratory research
question investigates whether integrating weather data into
the forecasting models can improve prediction accuracy and
operational outcomes. Weather-informed residual regression
models with day/night differentiation are evaluated for their
potential to enhance demand forecasts and generate economic
value for Citi Bike.
