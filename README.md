# G-Code syntax highlighting and snippets for Kate

This is the best tool to edit g-code files.

Advantages of using Kate to edit g-code files are numerous.
Just a few are it's ease of use and low learning curve,
has versions for LINUX, WINDOWS and MAC,
support code folding and is very easy to edit the
syntaxing colors and snippets.

G-Code syntax highlighter and snippets for Kate were developped with
LinuxCNC in mind but should work with any g-code version.


1. Installation
--------------------------------------------------------------------------------
1. Download gcodeHL.xml and G-Code-snippets.xml in the folder of your choice

2. Copy gcodeHL.xml in
	~/.kde/share/apps/katepart/syntax
	(for windows use  C:\Users\%name%\AppData\Local\katepart5\syntax)

3. Copy G-Code-snippets.xml in
	~/.kde/share/apps/ktexteditor_snippets/data
	(for windows use  C:\Users\%name%\AppData\Local\ktexteditor_snippets\data)

2. Configuration
--------------------------------------------------------------------------------
	Start Kate
	Select Settings->Configure Kate...
	Select Application->Plugins
	Check Code snippets

	Select Editor Component->Open/Save
	Select Modes & Filetypes
	Click New
	Name : G-Code
	Section : Other
	Highlighting : Other/G-Code
	Indentation Mode : Normal
	File extensions : *.ngc (or what is your format)
	MIME type : text/ngc
	Priority : 0

	Click Apply/OK
	Restart Kate and open one of your files or the demos

3. Suggestion
--------------------------------------------------------------------------------
My recommendations for configuration are :
	Plugins : documents, Search and replace
	Appearance : Dynamic Word Wrap -> No
	Editing/General : Static word wrap -> Yes; marker -> Yes; Auto Brackets -> Yes
	Editing/Indentation : Indent using Tabulators;
		Backspace key in leading blank space unindents
		Action : Increase indentation level if in leading blank space
	Auto Completion : Enable -> Yes
	Open/Save : Encoding -> UTF-8

4. Note
--------------------------------------------------------------------------------
	You may delete snippets that are not supported by your Kate version - sub-endsub and return