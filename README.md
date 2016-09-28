# Alfresco-wkhtml2pdf
An Alfresco transformer, which uses the `wkhtmltopdf` open source program, 
for improved conversion of HTML documents to PDF format

This is an Alfresco amp file with transformer configuration to use the 
wkhtmltopdf program to do better html to pdf transformations. 

Also implements a complex transformer to get from .eml files to pdf

## Installation

Go to http://wkhtmltopdf.org/ and install the `wkhtmltopdf` program.

In `alfresco-global.properties` set `wkhtmltopdf.exe` to the path to
the installed program, eg

    wkhtmltopdf.exe=C:/Alfresco/wkhtmltopdf/bin/wkhtmltopdf.exe

(the default) 

Note that after you install the program in windows, you can copy or move the 
entire install directory into your Alfresco structure

On Ubuntu Linux, you may want something like

    wkhtmltopdf.exe=/usr/local/bin/wkhtmltopdf
