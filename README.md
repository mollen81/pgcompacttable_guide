pgcompacttable --all - очистка всех доступных БД от раздувания
pgcompacttable --dbname dbname - очистка всех схем БД dbname
pgcompacttable --dbname dbname -n public - очистка всех таблиц БД dbname, принадлежащих схеме public
pgcompacttable --dbname dbname -n public -t table - очистка таблицы table в схеме public БД dbname

ФЛАГИ:
-h - имя хоста, на котором крутится кластер Postgres
-U - имя user
-W - пароль user'а
-i - initial reindex перед обработкой pgcompacttable
