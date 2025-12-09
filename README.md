# Administraciòn bàsica auditoria

# Auditoría básica MySQL

- Revisar usuarios con:
  ```sql
  SELECT user, host FROM mysql.user;

SHOW GRANTS FOR 'dba_junior'@'%';
