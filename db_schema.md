
# Cars Database

## Table Name

- cars


## Table Columns

- id | PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT NULL
- model_name | VARCHAR(20), NOT NULL
- features | TEXT, NULL
- engine | VARCHAR(20), NULL
- category | VARCHAR(20), NULL
- exterior_color | VARCHAR(20), NULL
- interior_color | VARCHAR(20), NULL
- image | VARCHAR(255), NULL
- model_years | VARCHAR(20), NULL
- registration_year | SMALL, NULL
- production_country | VARCHAR(20), NULL
- driving_side | VARCHAR(20), NULL
- plate | VARCHAR(20), UNIQUE, NULL
- price | DECIMAL(12, 2), NOT NULL
- km | MEDIUMINT, NULL
- description | TEXT, NULL
- is_available | TINYINT, DEFAULT(0)
- tank_capacity | VARCHAR(10), DEFAULT(0)
- seats | TINYINT, DEFAULT(0)
- shift | VARCHAR(30), NULL
- owners_number | TINYINY, DEFAULT(1)
- notes | TEXT, NULL
- shipping | TINYINT, DEFAULT(0)
