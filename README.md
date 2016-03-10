# G-Code syntax highlighting/snippets for Kate

This is the best tool to edit g-code files.

A few advantages of using Kate to edit g-code files are :
	supports code folding and completion,
	has versions for LINUX, WINDOWS and MAC,
	ease of editing the syntaxing colors and snippets
	ease of use and learning curve

G-Code syntax highlighter and snippets for Kate were developped with
LinuxCNC in mind but should work with any g-code version.
Some snippets and highlight are specific to LinuxCNC.

--------------------------------------------------------------------------------

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
1. Start Kate
2. Select Settings->Configure Kate...
3. Select Application->Plugins
4. Check : use Code snippets
5. Select Editor Component->Open/Save
		Select Modes & Filetypes
		Click New
		Edit fields :
			Name : G-Code
			Section : Other
			Highlighting : Other/G-Code
			Indentation Mode : Normal
			File extensions : *.ngc (or whatever as per your need)
			MIME type : text/ngc
			Priority : 0

6. Click Apply/OK
7. Restart Kate and open one of your files or the demos

Note : you may delete snippets that are not supported by your Kate version - sub-endsub and return