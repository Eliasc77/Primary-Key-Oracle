# Primary-Key-Oracle
#### Es un campo o varios que identifican a un registro unico en una tabla, para un valor de un campo clave existe solo ese registro es decir el valor de una llave primaria deben ser valores unicos en esa tabla e irrepetibles  en ninguna otra fila.

```sql
create table usuarios(
nombre varchar(20) not null,
clave varchar2(10) not null,
primary key(nombre)
);
```

[InformatiConfig](https://www.youtube.com/watch?v=fXhw9B_n7Sg&list=PL2Z95CSZ1N4HM7gzW8gK1Jt3lGWQO0k_G&index=14&ab_channel=INFORMATICONFIG "Video Referencia")
