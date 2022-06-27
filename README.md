# MVCSimpleCRUDvNet5
ASP.NET MVC Simple CRUD 

Berikut adalah Solution/Project visual studio 2020 untuk simple CRUD

Applikasi ini di buat dengan C# ver 5.0 

Database mengunakan MS-SQL server 2015

Nama Databasenya adalah [waDVTechTest]

DML/Data manipulation language serta 'sample' data tidak disertakan.
Untuk membuat data data struktur database tersebu dapat menjalankan DML berikut ini:

USE [USE [waDVTechTest];
GO;

CREATE TABLE [dbo].[Student] (
    [NomerId] NCHAR (10) NOT NULL,
    [Nama]    NCHAR (25) NOT NULL
);

dan data dapat di isi dengan data sample berikut ini:

INSERT INTO [dbo].[Student] ([NomerId], [Nama]) VALUES (N'123       ', N'Iqbal                    ');

INSERT INTO [dbo].[Student] ([NomerId], [Nama]) VALUES (N'124       ', N'Reza                     ');

