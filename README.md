# TeamNotice
Trapeace Team Notices

1. DB utility 0 DBeaver
>> https://dbeaver.io/
 
2. Trimming ID number when SQL Data import.

>> update woainfo set id_no = REGEXP_REPLACE(id_no, '^\s+', '');
