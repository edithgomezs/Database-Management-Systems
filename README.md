# Statistical Analysis of the Effect of Denormalization on Query Resource Consumption and Performance
Final Project for Database Management Systems

In this paper we explore how denormalization may affect the factors above by performing an in depth comparative analysis of
query resource consumption and query execution performance before and after denormalization. Our hope is to derive general
insights which may be used by practitioners to more easily determine whether denormalization would provide sufficient
advantages in their particular context.

In order to obtain consistent results, we base our comparative analysis on the set of queries and relations provided by the
TPC-H benchmark. These queries were executed by the SQLite database system on the entire TPC-H dataset. Note that usage of
Sqlite is of particular interest given that it is designed to run in resource constrained environments and is thus likely not
traditionally a target for denormalization.
