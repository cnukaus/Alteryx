# Alteryx
Bugs found by cnukaus:

version 2018.1
Output tool to Excel xlsx:
If create fresh sheet, it caused this Error (trading deck). But if manually create sheet, then refresh in Excel is fine.)

Alteryx bug2 (dynamic input can only generate Select because it add hidden select * (your full statement)
Error: Dynamic Input (8): DataWrapOCI: Unable to prepare the query: "SELECT * FROM delete from table where "DATE"='29-Mar-19'" Error: ORA-00903: invalid table name
