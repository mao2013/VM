VM
==

The Variability Modeling and Configuration Language 

### VM v2.0

 * Initial commit 23/07/2013 by Mauricio Alferez
 
### VM special features
_The most common types of additional information supported by VM are:_
  - **Default** values that help to complete partial configurations, 
  - **Deltas** to discretise real domains, 
  - controlled **descriptions** in natural language about the model itself, features, attributes and constraints, 
  - **multi-ranges** and **multi-deltas** that allow to use several ranges and deltas to define the domain of the values of an attribute,
  - **not translatable** tags a purely informative feature or attribute,
  - **not decidable** tags a feature or attribute that do not help to differentiate products, 
  - **runtime** tags a feature or attribute that vary only at runtime,
  - **objective functions** allow to filter validate configurations. For example, generating only low cost product configurations.

_Also VM supports the most advanced characteristics in extended feature models, for example_:
  - Attributed feature models
  - Packages and import mechanisms
  - metainformation of the main model
  - metainformation of features and attributes
  - Specification of configurations of feature and attributes values using tables.
  - Constraints that support features, attributes, values and a rich set of operations and functions.
  - Quantification when expressing constraints and global functions.
 
 ### How to Use VM v2.0 source code plugins 
  - Close or uninstall all the projects org.xtext.example.vm.* in your workspace or plugins directory. Those plugins represent the previous version 1.0 of VM
  - Import all the projects fr.inria.lang.vm.* from the VM repository
  - Right click on fr.inria.lang.vm
  - Click on "Run As..." 
  - Click on the default "Eclipse Application" or your own Eclipse Launch Configuration.
  - Create a new project in the new Eclipse Application instance.
  - Create a file with extension "vm" in the new project.
  - Click "yes" if Eclipse asks you if you want to add the "Xtext nature" to the project.
  - Get familiar with VM by understanding some examples (e.g., mobilePhone_v1.vm in fr.inria.lang.vm.examples.Mobile).
