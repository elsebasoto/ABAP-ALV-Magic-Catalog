# ABAP-ALV Magic Catalog
Class to create an ALV OO Fieldcat from his output structure

## How to use it:

### 1.- Create the instance with `CONSTRUCTOR`

#### OUTPUT
* `ZCL_ALV` object instance

### 2.- Call `FILL_CATALOG_MERGE` method

_This method read the output structure and fill the LVC table_

#### INPUT
* `STRUCTURE`: Output table structure type
* `TEXTS`: Flag to get DDIC texts
* `CONVEXIT`: Flag to get DDIC Convertion Exits
* `TABNAME`: Name of the internal table to show in the ALV

#### OUTPUT
* `FIELDCAT` LVC_T_FCAT fieldcat filled
