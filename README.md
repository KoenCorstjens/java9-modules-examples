Java9 modules examples build by maven.

This is an example on how to make a package hidden for other modules. 

- In this example module example2 has a dependency on module example1.
- Module 'example1' only exports the package eu.corstjens.example1.
So module 'example1' does not export package eu.corstjens.notexported
- Only classes that are exported in the module-info.java file are available to use in Example2. 
So you can not use the eu.corstjens.notexported.MainExample 2 class in module example 1.

