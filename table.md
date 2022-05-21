короткая запись для HTML:
table.name1>caption.title-table+tr.row>th.name-unu*5 а потом tr.row*7>td.data*5
5 число колоник в каждой строке. а 7 число строк в таблице, строка с заголовкам идет отдельно с названием таблицы

можно совместить две записи в одну строку:

table.name1>(caption.title-table{NAME}+tr.row>th.name-unu{$}*5)+tr.row*7>td.data{data$}*5
