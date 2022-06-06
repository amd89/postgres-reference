# Data types

## Numeric Types

| Type | Range | Precision |
| :--- | :---: |  :---: |
| SMALLINT | -32768 to 32767 | |
| INTEGER | -2147583648 to 2174483647 | |
| BIGINT | -9223372036854775808 to 9223372036854775807 | |
| SMALLSERIAL | 1 to 32767 | |
| SERIAL | 1 to 2174483647 | |
| BIGSERIAL | 1 to 9223372036854775807 | |
| DECIMAL / NUMERIC | | 13072 digits before the decimal point, 16383 after |
| REAL | 1E-37 to 1E37 | 6 digits |
| DOUBLE PRECISION | 1E-307 to 1E308| 15 digits|
| FLOAT | Same as REAL or DOUBLE | Same as REAL or DOUBLE |

## Character Types

| Type | Description |
| :--- | :--- |
| CHAR(x) | list of characters exactly length x padded with spaces |
| VARCHAR | String of any length |
| VARCHAR(x) | String up to length of x |
| TEXT | String of any length |

## Boolean Types

| State | Values |
| :--- | :--- |
| TRUE | true, 'yes' on, 1, t, y |
| FALSE | false, no, off, 0, f, n |
| NULL | null |
