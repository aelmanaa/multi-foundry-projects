# multi-foundry-projects

Dummy project that contains multiple foundry projects. Each of these projects imports external libraries.
The goal is to test that you can have one github repo with multiple foundry projects.

For this setup to work, most important parts:

- Keep a single `.gitmodules` file at the root of the repository. This file will contain the list of all submodules for each project.
- Each project has its own `foundry.toml` file. This file will contain the remappings for the imported libraries.
