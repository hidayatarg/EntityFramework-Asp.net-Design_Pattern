# Entity Framework with Asp.net MVC
Create an new Project add a C# class library .net standard.
Install the entityFramework from nuget package to the ComicBookShared.
Move the data and Models folder to the comic book shared.
We need to add the reference to the console application.

>Note: You may (System.NotSupportedException: 'Model compatibility cannot be checked because the database does not contain model metadata. Model compatibility can only be checked for databases created using Code First or Code First Migrations.'
) The program thinks that our model may not be made with code first. 

>Solution: in __MigrationHistory_ if you check the context key you can find the context address that need to be update to ComicBookShared.Data.Context.

