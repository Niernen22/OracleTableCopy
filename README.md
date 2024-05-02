# OracleTableCopy
Copying a partitioned table from one Oracle database into an other.

Checks if tables exist in actual db (targer table's) and in ODSD (source table's, db link can be replaced if other needed). Checks if tables have columns in common. Copies a range/list partitioned table, partitioned by date/number datatype column. If tablespace(s) and/or partition(s) are missing, creates them before datacopy. Copies full table or TND filtered, if truncate is TRUE, truncates target table's fully or only TND filtered part before.


Parameters

p_FORRAS_SEMA VARCHAR2 -- source table schema

p_FORRAS_TABLA VARCHAR2 -- source table name

p_CEL_SEMA VARCHAR2 -- target table schema

p_CEL_TABLA VARCHAR2 -- target table name

p_TRUNCATE BOOLEAN DEFAULT FALSE -- truncate target table TRUE/FALSE

p_TND_SZURES DATE DEFAULT NULL -- TND filter
