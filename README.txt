Open Context Data [Deprecated, see below]

Rationale:
Why not? GitHub seems like a good way to share these data in a way that allows for easier transformation, forking, duplication, etc. It will probably be years before someone does something interesting with this dataset, but it's still worth sharing via GitHub.

NOTE ABOUT DEPRECATION:
--------------------------------------------
We're still experimenting and trying to work out the best way to use GitHub for data version controll.
After July 2012, we started experiencing problems updating this GitHub repository. The repository contains
about 300K XML documents and as growing above 3 GB. We had trouble adding more data and making commits. GitHub
returned HTTP 500 range errors when we tried to push these changes. 

After consulting colleagues and online help, we decided to share data via GitHub using multiple smaller repositories.
This may not be an ideal solution, but at least it is functional. Please check my list of repositories to get access
Open Context data in GitHub (https://github.com/ekansa?tab=repositories). Alternativly, you can find links directly
to datasets in GitHub directly from project descriptions in Open Context (http://opencontext.org/projects/).

--------------------------------------------

About these XML Files:
In the "data" directory, different directories are named by the project
ID. Each project directory has an XML file with metadata about the project.
Each project directory will have a "subjects" director (with subject XML
documents belonging to that project). They may also have media and document directories. All the XML documents where checked to be valid/well-formed when exported.They should all be in UTF-8 encoding.

Licence Information: 
Each XML document has a Creative Commons license. Most XML documents a Creative Commons Attribution License, but some have the (dreaded) Non-Commercial restriction. Please respect these licenses for linked media files (mainly pictures). These images are not stored in GitHub but can be discovered through their links.

Source Code:
Open Context source code is available here:
https://github.com/ekansa/open-context-code




