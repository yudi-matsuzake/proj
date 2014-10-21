proj
====

Small local C/C++ projects manager.

##Commands

1. proj

	Creates a simple project that contains.
	
* one sources folder (src/)
* one headers folder (headers/)
* Makefile

	proj [OPTIONS] [SOURCES]

* Options

	-p		Sets the project name
	-h		Header name
	-m		Main name
	-+		c++ project
	
**Example**
proj -p test -m teste.c -h functions functions.c

2. projrm

	Removes a project.
	
	projrm project_name

3. projls
	
	Lists the projects created by proj.
	
	projls
	
4. projdir

	Prints the project's path directory.
	
	projdir project_name.

