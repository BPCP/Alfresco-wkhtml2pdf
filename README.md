# Alfresco-wkhtml2pdf
A transformer to implement the wkhtmltopdf open source program for improved conversion of HTML documents to PDF format

An Alfresco amp file with transformer configuration to use the wkhtmltopdf program to do html to pdf transformations. Go to http://wkhtmltopdf.org/ and install the wkhtmltopdf program.
Also implements a complex transformer to get from .eml files to pdf
In alfresco-global.properties
Set wkhtmltopdf.exe to your path
wkhtmltopdf.exe=C:\Alfresco\wkhtmltopdf\bin\wkhtmltopdf.exe
is the default (after you install in windows you can copy or move the entire install directory into your Alfresco structure)
wkhtmltopdf.exe=/usr/local/bin/wkhtmltopdf
is my Ubuntu setting
