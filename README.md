# SEDS (Specify and Extract Document Segments）
This project is used to retrieve partial content from documents in Word, Excel, PowerPoint, OFD formats, using regular expression or XML path.

## Environment
Integrated development environment: Visual Studio 2022

Language: C# (with .NET Framework 4.7.2)

## Main interface
<p align="center">
  <img width="640" height="400" src="/doc/Img/Main interface.png">
</p>

## Tool Functions
This tool can retrieve the following content according to various expression:

text in a paragraph from particular position in a Word document

text in a table from particular position in a Word document

text in a cell from particular sheet in an Excel document

text in a slide in a PowerPoint document

text in an object in a OFD document.


## Main libraries used
ICSharpCode.SharpZipLib 1.4.2.13

Microsoft.Office.Interop.Word 12.0.0

Microsoft.Office.Interop.Excel 12.0.0

Microsoft.Office.Interop.PowerPoint 12.0.0

Office 12.0.0

## Licenses
Apache 2.0 licenses
