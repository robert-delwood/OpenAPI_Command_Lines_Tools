# OpenAPI Command Lines Tools
A series of command line tools for OpenAPI that doesn't require additional installations

The following files dereference OpenAPI specifications.
* dereference-json
* dereference-yaml

These remove all $ref and anchors in the file directly with their text.
Some applications, such as linters, do not handle files with $ref statements well.
In the same way, it may be easier to post files to web servers without those statements, too.
These applications create deferenced and scrubbed files. 

Download the appropiate file type (JSON or YAML). Usage notes are included in the downloads.
The advantage of these files are that no additional installation of any libraries are needed. 
Typically, node or perhaps Redocly or Swagger CLI files need to be installed. 
Not with these files. The libraries are present but in the executables. That's why they're so large.
