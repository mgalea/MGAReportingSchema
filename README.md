# MGA Enhanced Automated Reporting Schema

In 2019 the Malta Gaming Authority published **Directive 6 - Enhanced Automated Reporting Platform (Land-Based) Directive** 
to regulate the reporting by land based operators. The directive can be dopwnloaded from here(https://www.mga.org.mt/legislations-regulations/#gamingindustrydirectives)

This is the repo with the latest versions.

## Version 20200420
### CommonTypes
* Removed `<minOccur>` from `MonetaryAmount` element in **commonTypes** Schema.

### B2BType3SmryCompliance
* Added Pari Mutuel Reporting in **B2BType3SmryCompliance** Schema.

### SmryLiveTables
* Removed `<TtlResult>` from **SmryLiveTables** Schema

### MGATypes
* Changed  **Sports** type to **SportsTypes**
* Changed **PlayerTypes1** to include only Land Based types
* Added **PlayerTypes2** to include all types of Players
* Corrected **BetTypes** to include missing elements
* Changed **Type3PoolGamesSummary** to include new elements


## Version 20200312

* Added **SmryLiveTables** Schema for Live Gaming Tables Reporting
* Added `<SummaryCashflowByType1LiveTable>` in **MGATypes** Schema
