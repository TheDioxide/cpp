before compiling:


Project -> Build options... -> Compiler settings -> Compiler flags <br />
	enable [-std=c++11] <br />
<br />
Project -> Build options... -> Linker settings <br />
	Link libraries: <br />
		gdi32 <br />
	Other linker options: <br />
		-Iwinmm <br />