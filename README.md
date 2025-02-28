# CRUD_OPERATION_WITH_DATATABLE_AND_PDF_IN_PHP_WITH_SOURCE_CODE-
CRUD Operation with DataTables and PDF in PHP

Overview

This project implements a CRUD (Create, Read, Update, Delete) system in PHP using DataTables for interactive tables and TCPDF for generating PDF reports.

Features

Create, Read, Update, and Delete (CRUD) operations

Uses DataTables for dynamic table management

Generates PDF reports using TCPDF

User-friendly interface

MySQL database integration

Installation Guide

Prerequisites

XAMPP/WAMP or any local server

PHP 7+ and MySQL

Web browser

Steps to Install

Clone the repository:

git clone https://github.com/yourusername/crud-datatable-tcpdf-php.git
cd crud-datatable-tcpdf-php

Move the project folder to your local server directory:

For XAMPP: Move to htdocs/

For WAMP: Move to www/

Create a database:

Open phpMyAdmin

Create a new database named mydatabase

Import the provided SQL file (mydatabase.sql)

Configure database connection:

Open config.php

Update the database credentials:

$servername = "localhost";
$username = "root";
$password = "";
$dbname = "mydatabase";

Run the project:

Open your browser and go to:

http://localhost/crud-datatable-tcpdf-php/

Usage

Add new records using the Add New button.

Edit existing records using the Edit button.

Delete records if necessary.

Generate PDF reports using the Export to PDF button.

Project Structure

CRUD with PDF PHP/
│── crud_datatable_tcpdf/  # Main project folder
│── READ ME FIRST !!!!.txt  # Setup instructions
│── terms-and-condition.pdf # Additional document
