# bancodedados

USE Master
GO
CREATE DATABASE Nome_do_Banco_de_Dados
ON
( NAME = nome_dat,
FILENAME = 'C:\Program Files\Microsoft SQL
Server\MSSQL11.MSSQLSERVER\ MSSQL\DATA\nome.mdf',
SIZE = 10,
MAXSIZE = 50,
FILEGROWTH = 5 )
LOG ON
( NAME = nome_log,
FILENAME = 'C:\Program Files\Microsoft SQL
Server\MSSQL11.MSSQLSERVER\ MSSQL\DATA\nomelog.ldf',
SIZE = 5MB,
MAXSIZE = 25MB,
FILEGROWTH = 5MB ) .
GO 
