# MGA Enhanced Automated Reporting Schema

In 2019 the Malta Gaming Authority published **Directive 6 - Enhanced Automated Reporting Platform (Land-Based) Directive** 
to regulate the reporting by land based operators. The directive can be dopwnloaded from here(https://www.mga.org.mt/legislations-regulations/#gamingindustrydirectives)

This is the repo with the latest versions.
## Latest Version:  20210201


## Version 20210201

###  MGATypes
* Changed  regex for **OperatorMTLicence"** to MGA/XXX/NNNN/YYYY (X=any word-char, N=numeric, YYYY = year)


## Version 20200420
### CommonTypes
* Removed `<minOccur>` from `MonetaryAmount` element in **commonTypes** Schema.
* Changed **PlayerTypes1** to include only Land Based Player types
* Added **PlayerTypes2** to include all types of Players

### B2BType3SmryCompliance
* Updated Pool Types. Can be used to report Pari Mutuel and Bingo.

### SmryLiveTables
* Removed `<TtlResult>` from **SmryLiveTables** Schema

### MGATypes
* Changed  **Sports** type to **SportsTypes**
* Changed maxoccur to unbounded in SummaryCashFlowByTableType1LiveTable
* Corrected **BetTypes** to include missing elements
* Changed **Type3PoolGamesSummary** to include new elements
* changed **BettingMarkets** to **BettingVerticals**


## Version 20200312

* Added **SmryLiveTables** Schema for Live Gaming Tables Reporting
* Added `<SummaryCashflowByType1LiveTable>` in **MGATypes** Schema
