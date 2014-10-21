proj
====

Small C/C++ local projects manager.

##Commands

**proj**

```Shell
	proj [OPTIONS] [SOURCES]
```

	Creates a simple project that contains:
	
* one sources folder (src/)
* one headers folder (headers/)
* Makefile

**Options**

**-p**		Sets the project name

**-h**		Header name

**-m**		Main name

**-+**		c++ project


**Example**

```Shell
	proj -p test -m teste.c -h functions functions.c
```

**projrm**

```Shell
	projrm project_name
```

	Removes a project.


**projls**

```Shell
	projls
```	

	Lists the projects created by proj.
	
**projdir**

```Shell
	projdir project_name.
```

	Prints the project's path directory.

