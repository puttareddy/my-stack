# Performance Tools
Tools to explore for Performance Testing

### Definitions
SM(Synthetic monitoring)
RUM (Real user monitoring) 
ND(Network diagnostics)


### Sites can useful
cavisson http://www.cavisson.com/
Note: Evaluated cavisson , newrelic , wily and Dynatrace for APM and UEM capabilities and Dynatrace is leading the race.

Apimetrics-> http://apimetrics.io/ 
Very good tool and can configure url for API monitoring with synthetic transactions [PAID]

apigee -> https://apigee.com 
Have UI you can configure the API path there. Currently in Beta version [PAID]

App Dynamics 
Can write python scripts to write Synthetic transaction. [PAID]
(https://www.runscope.com/) for API monitoring 

The easiest and cheapest solution is “Pingdom”. https://www.pingdom.com/
There is also an option for a 14 Day Trial. They will test from different geolocations (not as much as Gomez) and have the option to create simple transactions.
Also they offer dashboards for performance and option to alert on thresholds.


Can be used Site confidence & Gomez which primarily offer synthetic monitoring capabilities

There are few tools which you can explore based on the type of testing. If you are looking for pure backend performance tests there is blazemeter (cloud version of Jmeter) which can inject load from different locations(Mainly the locations which has AWS or Google Cloud. You can also customize the location if you have a server hosted there through which you can route the traffic). For 50 user load is free then you have to buy the license. 

If you are looking for a front end performance test based on user journeys you can create your custom scripts and execute it on Saucelabs or browserstack which also provide different locations based on AWS and google cloud. 

“New Relic” https://newrelic.com/  tool can help you for this. 
New Relic : The pricing model is based on cpu cores + Ram and hours used
Dynatrace : Consumption based pricing model, pay as you go.

New Relic |	Dynatrace
--- | --- 
SAAS deployment Solution |	Both SAAS and on-prem deployment
New Relic samples and reports detailed traces for a few representative transactions This is lightweight and focusses on more on the monitoring part | 	Monitors and provides detailed trace for each and every transaction,very helpful for analyzing performance of the application
Wide variety of APM plugins available for in depth insights	| strong set of APM for in depth insights
Provides infrastructure monitoring and alerting	| Provides infrastructure monitoring and alerting
Easy setup comes with a variety of packaged solutions which could be implemented  |	Provides flexible configuration
Provides synthetic monitoring to simulate user behavior to track down issues |	Synthetic monitoring for your infrastructure
More intended towards application monitoring and alerting |	More intended towards performance measurement and metrics for the application
Provides insight into Database transactions and slow queries, focus on database operations | Detailed and in-depth database monitoring for on-prem database management systems (relational & nosql)
New Relic insights provide real time analytics. collects data and metrics from other new relic products and provides you with a consolidated view |	Provides real time business insights. provides big data analytics for full stack

Pricing models


