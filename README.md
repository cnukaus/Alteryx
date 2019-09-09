# Alteryx
Bugs found by cnukaus:

version 2018.1
Output tool to Excel xlsx:
If create fresh sheet, it caused this Error (trading deck). But if manually create sheet, then refresh in Excel is fine.)

Alteryx bug2 (dynamic input can only generate Select because it add hidden select * (your full statement)
Error: Dynamic Input (8): DataWrapOCI: Unable to prepare the query: "SELECT * FROM delete from table where "DATE"='29-Mar-19'" Error: ORA-00903: invalid table name

Found from Alteryx Forum: One way to accomplish **Auto Email Read**  is by linking the Outlook folder (s) to an Access database table (s) and then to read the Access database with Alteryx


因为很多人不是Windows, Alteryx不直接支持，解决办法要么IOS用本地虚拟机Bootcamp（免费内置）,VMware/Parallel,要么在Microsoft cloud等开一个虚拟机（前几个月免费），结束后关掉。 或者可以下载同类工具Knime  https://www.knime.com/downloads/download-knime

Dynamic Rename: chose which fields (by sequence possible and specify a subset by list too) to rename

Excel Pivot table best practice:
Excel pivotchart/table best way to dynamic update (if data sourcesheet range changed). User Power Query as data connection to read external CSV file, create Pivot table/chart feeeding from connection, this will refresh and recognised new CSV file as whole range
