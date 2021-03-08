# Saying Goodbye to Dependency Hell with Git and Modern CMake (And a Shell Script)

## Abstract 

Aiming at reusability and maintainability in large scale projects automatically leads to the desire to split the code base into a large number of small modules. This puts more burden on configuration management. The version control system Git allows to address this task via plugins or the built-in submodule management, but these solutions come with some drawbacks regarding performance and usability which leads to acceptance issues and might generate friction in the highly sensible field of collaboration. Fortunately, Modern CMake has some useful features that help to overcome these issues and can make configuration management seamless for both, developers and integrators.

This talk presents a solution proposal that is easy to apply, integrates seamlessly with Git and CMake, and gives developers the flexibility they need for development while maintaining well-defined release management. 

## Speaker

Markus Werle is an aeronautics engineer who became C++ addicted because he needed Expression Templates for the automatic generation of finite element solvers. 

For more than a decade Markus worked in the automotive sector, creating algorithms and a wide range of data processing libraries and tools in C++, C++/CLI, and C#. The focus was on robust, reusable core libraries and addressing complexity by modularity. Markus was responsible for code organization and streamlining a certified agile software development process.

In the current position as CTO at [Ducktrain / DroidDrive GmbH](https://ducktrain.io), Markus develops semi-autonomous vehicles for fun and profit.
