## CMakeMulti

Conan generator used to switch Debug/Release builds from the IDE.

This version fixes a link error due to missing library directories.
It appends to link_directories release/debug lib directories to ensure.
