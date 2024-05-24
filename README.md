# Athesto
This monorepo is a collection of different projects tools and packages

## FAQ
##### Difference between Packages and Tools folder<br>
###### packages Folder
**Purpose:**<br>
The packages folder typically contains libraries, dependencies, or code modules that the project uses. These libraries can be third-party or developed internally and are meant to be reusable across various projects or different parts of the same project.<br>

**Content:**<br>
Third-party packages installed via a package manager (like npm for JavaScript, pip for Python, composer for PHP).<br>
Internal modules of the project that are organized as packages for better modularity and maintenance.<br>

**Structure:**<br>
It usually has a specific structure depending on the language and the package manager being used. For example, in a Node.js project, the node_modules folder contains the packages installed via npm.<br>

###### tools Folder<br>
**Purpose:**<br>
The tools folder generally contains tools and utilities that assist in the development, building, testing, and deployment of the project. These tools are not part of the final product but are auxiliary to the development process.<br>

**Content:**<br>
Build scripts, like those used with make, gulp, Grunt, webpack, etc.<br>
Testing tools and linters, such as eslint, prettier, pytest, etc.<br>
Automation scripts, such as those that set up the development environment, deploy code to servers, or perform maintenance tasks.<br>

**Structure:**<br>
It can have a more varied and less defined structure, as it depends on the specific tools the project is using. It's common to find subfolders or scripts organized according to their purpose.<br>

###### Examples<br>
**packages Folder**<br>
`node_modules/` (Node.js): Contains all packages installed by npm.<br>
`vendor/` (PHP with Composer): Contains dependencies installed via Composer.<br>
`libs/` or `modules/`: Can contain internal modules or libraries of the project organized as packages.<br>

**tools Folder**<br>
`build/`: Scripts and configurations for building the project.<br>
`scripts/`: Scripts for task automation.<br>
`test/`: Tools and scripts for automated testing.<br>
`linting/`: Configurations and tools for linters.<br>

###### Summary<br>
In summary, the packages folder is intended to store dependencies and reusable modules that the project needs, whereas the tools folder contains tools and scripts that facilitate the development, building, and maintenance of the project. Both are essential but have clearly differentiated roles in the software development lifecycle.<br>

