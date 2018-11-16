# specifications-ITS-BMM

BMM schemas for use with openEHR systems and tools. The repository is structured as follows:

----
/original					# BMMs from original openEHR, prior to separated components
/example					# BMM containing documentation on format with examples
/components
	/BASE					# BMMs for BASE component
		/Release-1.0.0 		# BMMs for Release-1.0.0 of BASE
		/etc
	/LANG					# BMMs for LANG component
		/Release-1.0.0 		# BMMs for Release-1.0.0 of LANG
		/etc
	/RM						# BMMs for RM component
		/Release-1.0.3 		# BMMs for Release-1.0.3 of RM
		/Release-1.0.4 		# BMMs for Release-1.0.4 of RM
		/etc
	/PROC					# BMMs for PROC component
		/Release-1.0.0 		# BMMs for Release-1.0.0 of PROC
		/etc
----

To use these files in tools, the recommended approach is to point the tool to the `components` directory of a clone checkout area, and to manage a table of files identified by schema id (determined by meta-data inside the files), and to resolve the include references via this table.

