# data
Contains sample datasets in different formats.

Most of this is based on well known sample databases, like *Northwind*. The data is either directly retrieved from the sourse repositories or from another repo who has done some conversion (e.g. from a SQL Server database to CSV or Excel). No responsibility of the quality or accuracy of the data data will be assumed as the data is converted as-is and no values or table columns are modified or added. In some cases, data is removed that were ot essential (like blob representation or links), and entries were fixes where the CSV or imports would not be properly structured (e.g. interpretation of addresses with commas that would be split on import wr fixed by wrapping them in quotes in the csv).

Samples are not intended to be interpreted as live data, but can be used to test certain scenarios in PowerBI. 