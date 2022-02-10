## Problems and solutions

### Problem 1
Could not find module `Daml.Script'
It is not a module in the current program, or in any known package

https://discuss.daml.com/t/no-daml-script-import/22

### Solution
The other possible cause is that DAML Studio (/VS Code) has to be opened on the directory containing the daml.yaml file. For example, you have a foo/bar/daml.yaml project root, and open VS Code in foo, it will fail to resolve the DAML Script library