# Aproplan module refactor
Simple python script which purpose is:

 - To remove module keyword from each files within a specific folder
 - Add `import { export } from "module";` statements to each file within a same specific folder

# How to

 - Install Python: https://www.python.org/
 - Edit `path` var in the script to match the folder in which your files are
 - Edit calls to `use_imports` and
	 - module path to look for
	 - corresponding folder containing the exported members
	 - exported class
In the current file, all controllers modules path will be replaced by `imports` of the specified controller class.
