# OracleTableCopy
Copying a partitioned table from one Oracle database into an other.


Parameters

p_FORRAS_SEMA VARCHAR2 -- source table schema

p_FORRAS_TABLA VARCHAR2 -- source table name

p_CEL_SEMA VARCHAR2 -- target table schema

p_CEL_TABLA VARCHAR2 -- target table name

p_TRUNCATE BOOLEAN DEFAULT FALSE -- truncate target table TRUE/FALSE

p_TND_SZURES DATE DEFAULT NULL -- TND filter
