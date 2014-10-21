proj
====

Small C/C++ local projects manager.

##Commands

**proj**

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

```Shell
	proj -p test -m teste.c -h functions functions.c
```

**projrm**

	Removes a project.
```Shell
	projrm project_name
```

**projls**
	
	Lists the projects created by proj.
```Shell
	projls
```
	
**projdir**

	Prints the project's path directory.
	
```Shell
	projdir project_name.
```

