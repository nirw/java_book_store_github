this is the JAVA-BS project readme file
-----------------------------------------

test line in RM file
test line2 in RM file


* Excluding the .git and .github folders from the zip file is highly important! Otherwise each commit will triger a full scan due to changes in the files under this folders
* To recursively exclude all files under any folder named "tests" for example, add the following to the -cx-flow.zip-exclude line:
--cx-flow.zip-exclude="\\.git\\/.\*,\\.github\\/.\*,tests\\/.\*,.\+\\/tests\\/.\*"
