# customer-profitability-sample

This is a Doku for customer profitability sample with Power BI.

Source: 
https://docs.microsoft.com/en-us/power-bi/sample-customer-profitability from http://obvience.com/

The dataset: [Click here](https://drive.google.com/file/d/1fHCwm3tEKIU89IOPXS3yK-vjsSCIOW3r/view?usp=sharing)

Before going further, we need understand the concept of the data model, please read the link below:
https://en.wikipedia.org/wiki/Data_model

This analysis contains 9 entity (table) and every table has to attribute.

1. state
* Attribute: StateCode,	State,	Region

2. executive
* Attribute: ID,	Name,	Img

3. industry
* Attribute: ID,	Industry,	Image

4. customer
* Attribute: Customer,	Name,	City,	Postal Code,	State,	Industry ID,	Country/Region

5. product
* Attribute: Product Key, 	Product


6. scenario
* Attribute: Scenario Key,	Scenario

7. date
* Attribute: YearPeriod,	Year,	Period,	Date,	Month,	QtrID,	Qtr

8. bu
* Attribute: BU Key,	BU,	Division,	Executive_id

9. factsales
* Attribute: YearPeriod,	Customer Key,	Product Key,	BU Key,	Scenario Key,	Revenue,	Material Costs,	Labor Costs Variable,	Taxes,
Rev for Exp Travel,	Travel Expenses,	Cost Third Party,	Subscription Revenue




### Let's make the data model from the 9 entity. Just drag every [Primary Key](https://en.wikipedia.org/wiki/Primary_key) of the entity in power pivot or power bi data model

![customer-profitability](https://user-images.githubusercontent.com/27078712/40879487-d82dcb9c-66a0-11e8-96b0-712875c4be90.PNG)



### After that, create [a measure in power bi or power pivot](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-create-measures)

Below are the measure of every graph,

Note! we use the format of table and attribut with [DAX language](https://docs.microsoft.com/en-us/power-bi/desktop-quickstart-learn-dax-basics) 

Extras: [Quick Guide DAX](https://support.office.com/en-us/article/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a?omkt=en-US&ui=en-US&rs=en-US&ad=US)

---------------------------------------------------------------------------
Drag this entity for every graph: 
.
.
.coming soon!
