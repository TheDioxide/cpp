before compiling:


Project -> Build options... -> Compiler settings -> Compiler flags
	enable [-std=c++11]

Project -> Build options... -> Linker settings
	Link libraries:
		gdi32
	Other linker options:
		-Iwinmm