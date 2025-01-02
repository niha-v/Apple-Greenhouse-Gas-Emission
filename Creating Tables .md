# Creating tables in SQL 

-- Table for GreenHouse Gas Emission 
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

-- Table for Carbon Footprint By Product
```sql 
 CREATE TABLE CarbonFootprintByProduct (
    ReleaseYear INT,
    Product VARCHAR(100),
    BaselineStorage VARCHAR(50),
    CarbonFootprint FLOAT
);

--- Table Normalizing Factors
```sql
CREATE TABLE NormalizingFactors (
    FiscalYear INT,
    Revenue FLOAT,
    MarketCapitalization FLOAT,
    Employees INT
);
