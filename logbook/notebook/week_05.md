

This lesson explains how Python programs are written using **script files** and how code can be reused using **modules**.

Instead of typing code directly into the Python interpreter, larger programs are saved as **text files with a `.py` extension**. These files are called **scripts** and are executed from the command line using the Python interpreter. Unlike interactive mode, scripts require the use of `print()` to display output.

When running a script, users can pass **command line arguments**. These arguments are accessed in the program using `sys.argv`, which stores them as a list of strings. This allows programs to receive input values when they are executed.

Python files can also be used as **modules**. A module is any `.py` file that contains functions, variables, or classes and is imported into another program using the `import` statement. When a module is imported, its statements are executed once to initialise it.

There are different **methods of importing** modules:

* Importing the whole module
* Importing with an alias
* Importing specific functions or variables
* Using wildcard imports (not recommended due to name clashes)

Python searches for modules using the **module search path (`sys.path`)**, which includes built-in modules, the current directory, and directories defined in the system environment.

The built-in `dir()` function helps list the names defined in a module, mainly useful in interactive mode.

Finally, the special variable **`__name__`** allows a file to detect whether it is being run as a script or imported as a module. This makes it possible to write flexible programs that work in both ways.

