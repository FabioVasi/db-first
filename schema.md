# Cars Database

## Table Name

- Cars

## Table Columns

- id | BIGINT, AUTO_INCREMENT, UNIQUE
- producer | VARCHAR (255)
- model | VARCHAR (255)
- type | VARCHAR (255)
- plate | UNIQUE, VARCHAR (13)
- frame_number | UNIQUE, AUTO_INCREMENT, INT
- price | DECIMAL (7, 3) // 9.999.999,999
- is_avaiable | TINYINT
- note | TEXT