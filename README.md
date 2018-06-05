# Evolenttask
Evolent Health Assignment 


1.Create new DB in SQL Server "EvolentTask"


2.Create New Table "ContactDetails" in the above DB OR Execute the below script

 


USE [EvolentTask]
GO

 
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[ContactDetails](
	[ContactID] [int] IDENTITY(1,1) NOT NULL,
	[FirstName] [nvarchar](50) NULL,
	[LastName] [nvarchar](50) NULL,
	[Email] [nvarchar](50) NULL,
	[PhoneNumber] [int] NULL,
	[Status] [bit] NULL,
 CONSTRAINT [PK_ContactDetails] PRIMARY KEY CLUSTERED 
(
	[ContactID] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON) ON [PRIMARY]
) ON [PRIMARY]

GO

3.Open the solution file "EvolentTaskApplication.sln" from folder.


4.Change the Web.config connection string with your local/server details.

5.Build the solution and Run it.





