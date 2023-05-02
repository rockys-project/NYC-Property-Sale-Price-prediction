# NYC-Property-Sale-Price-prediction

##About Dataset
###Context
This dataset is a record of every building or building unit (apartment, etc.) sold in the New York City property market over a 12-month period.

###Content
This dataset contains the location, address, type, sale price, and sale date of building units sold. A reference on the trickier fields:

**BOROUGH:** A digit code for the borough the property is located in; in order these are Manhattan (1), Bronx (2), Brooklyn (3), Queens (4), and Staten Island (5).
**BLOCK;** LOT: The combination of borough, block, and lot forms a unique key for property in New York City. Commonly called a BBL.
**BUILDING CLASS AT PRESENT and BUILDING CLASS AT TIME OF SALE:** The type of building at various points in time. See the glossary linked to below.
For further reference on individual fields see the Glossary of Terms. For the building classification codes see the Building Classifications Glossary.

**Note** that because this is a financial transaction dataset, there are some points that need to be kept in mind:

Many sales occur with a nonsensically small dollar amount: $0 most commonly. These sales are actually transfers of deeds between parties: for example, parents transferring ownership to their home to a child after moving out for retirement.
This dataset uses the financial definition of a building/building unit, for tax purposes. In case a single entity owns the building in question, a sale covers the value of the entire building. In case a building is owned piecemeal by its residents (a condominium), a sale refers to a single apartment (or group of apartments) owned by some individual.

###Acknowledgements
This dataset is a concatenated and slightly cleaned-up version of the New York City Department of Finance's Rolling Sales dataset.

###Inspiration
What can you discover about New York City real estate by looking at a year's worth of raw transaction records? Can you spot trends in the market, or build a model that predicts sale value in the future?
