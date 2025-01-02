# SQL Analysis using pgAdmin

## Creating tables

```sql

DROP TABLE GreenhouseGasEmissions;
CREATE TABLE GreenhouseGasEmissions (
    FiscalYear INT,
    Category VARCHAR(50),
    Type VARCHAR(50),
    Scope VARCHAR(50),
    Description TEXT,
    Emissions FLOAT
);
