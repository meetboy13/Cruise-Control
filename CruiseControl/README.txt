How to run the assignment:
1.)Extract the contents of the zip into a directory.
2.)then run
	$ cd [directory]/CruiseControl
where [directory] is the location you have extracted to.
3.)then run
	$ make CruiseControl.xes
	$ ./CruiseControl.xes


If for whatever reason, the make says the file is already up to date,
do
	$ make clean
then make the xes file again.


To change the parameters of the assignment, edit the macros in the CruiseControl.h file.
To change the Kp, Ki or ThrottleSatMax parameters, edit the static constant floats of the functions in the CruisControl_data.c file.

