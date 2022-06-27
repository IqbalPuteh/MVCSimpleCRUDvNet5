# MVCSimpleCRUDvNet5
ASP.NET MVC Simple CRUD 

Berikut adalah Solution/Project visual studio 2020 untuk simple CRUD

Applikasi ini di buat dengan C# ver 5.0 

Database mengunakan MS-SQL server 2015

Nama Databasenya adalah [waDVTechTest]

Database sample dapat di download dari folder database atau menjalankan DML dibawah ini
DML/Data manipulation language Untuk membuat data data struktur database tersebut adalah sbb:

USE [USE [waDVTechTest];
GO;

CREATE TABLE [dbo].[Student] (
    [NomerId] NCHAR (10) NOT NULL,
    [Nama]    NCHAR (25) NOT NULL
);

dan data dapat di isi dengan data sample berikut ini:

INSERT INTO [dbo].[Student] ([NomerId], [Nama]) VALUES (N'123       ', N'Iqbal                    ');

INSERT INTO [dbo].[Student] ([NomerId], [Nama]) VALUES (N'124       ', N'Reza                     ');

