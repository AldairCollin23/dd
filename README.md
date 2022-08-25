create database db_gestion_tienda;
use db_gestion_tienda;

create table producto(

descripcion varchar(100),
precio double,
numero_de_existencias int(6)

);

create table cliente(

dni char(8),
nombre varchar(50) not null,
apellido varchar(50) not null,
direccion varchar(50) not null,
telefono varchar(12) not null


);

create table proveedor(

codigo char(8),
nombre varchar(50) not null,
apellido varchar(50) not null,
direccion varchar(50) not null,
provincia varchar(50) not null,
telefono char(12) not null


);

create table direccion(
codigo char(6),
nombre varchar(50) not null
);

create table telefono(
codigo char(6),
numtelefono varchar(12) not null
);
