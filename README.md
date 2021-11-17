# TeamNotice
Trapeace Team Notices


1. Trimming ID number when SQL Data import.

>> update woainfo set id_no = REGEXP_REPLACE(id_no, '^\s+', '');
