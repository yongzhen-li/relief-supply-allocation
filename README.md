This project contains the source data for the paper "Robust Emergency Relief Supply Allocation with Supplier Selection and Inventory Pre-positioning".

DemPoints.txt records, for each demand node:
- the index
- the nominal value of demand volume
- the mean of demand volume for testing scenarios
- the STD of demand volume for testing scenarios
- unit penality cost

Facilities.txt records, for each facility:
- the index
- the fixed facility location cost
- the capacity
- the unit storage cost
- the unit holding cost
- the nominal value of the proportion of usable relief supplies after a disaster
- the mean of the proportion of usable relief supplies after a disaster for testing scenarios
- the STD of the proportion of usable relief supplies after a disaster for testing scenarios

Suppliers.txt records, for each Supplier:
- the index
- the production capacity
- the SPI storage capacity
- the committment quantity
- the compensation rate
- the maximal purchasing quantity
- the nominal value of the proportion of usable production capacity and SPI quantity
- the mean of the proportion of usable production capacity and SPI quantity for testing scenarios
- the STD of the proportion of usable production capacity and SPI quantity for testing scenarios

disFD.txt records the distance from facilities to demand nodes
disSD.txt records the distance from suppliers to demand nodes
disSF.txt records the distance from suppliers to facilities

hkn.txt records the unit procurement cost for each quantity interval and each supplier
SupPriceBpL.txt records the lower bound for each quantity interval and each supplier
SupPriceBpU.txt records the upper bound for each quantity interval and each supplier
unit procurement cost for each quantity interval and each supplier
hlkt.txt records the unit procurement cost for each lead time interval and each supplier
