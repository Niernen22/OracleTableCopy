# OracleTableCopy
Copying a partitioned table from one Oracle database into an other.

Parameters
p_FORRAS_SEMA VARCHAR2 -- source table shema
p_FORRAS_TABLA VARCHAR2,
p_CEL_SEMA VARCHAR2,
p_CEL_TABLA VARCHAR2,
p_TRUNCATE BOOLEAN DEFAULT FALSE,
p_TND_SZURES DATE DEFAULT NULL
