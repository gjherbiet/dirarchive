# dirarchive

## Version

	This is dirachive v. 0.2
	Copyright (c) 2012 Guillaume-Jean Herbiet  (http://herbiet.net)
	This is free software; see the source for copying conditions. There is NO
	warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

## Usage

	dirachive [-h|--help] [-V|--version] [-D|--debug] [-v|--verbose] [-N|--dry-run]
	    [-d|--directory <dest_directory>] [-p|--period <N[y|m|d|h|m|s]>]
	    [-a|--archive] [src_directory]
	
	  Archive directory content based on the "Date Added" value of the file.
	  All files of the directory with a date added older than the specified
	  period will be moved to the specified location.
	
	  Note: If your system has the non-enhanced version of 'getopt' (which is the
	  case by default on BSD systems, including Mac OS), only the short version
	  of the following options are available.
	
	    --help, -h       : Print this help, then exit.
	    --version, -V    : Print the software version, then exit.
	    --debug, -D      : Extended information about the script function.
	    --verbose, -v    : Display a summary of the executed operations.
	    --dry-run, -N    : Do not perform any actual action
		
	    --directory, -d  : Specifies the directory where the files will be saved
	                       (default: '/Users/Guillaume/Archive')
	    --period, -p     : Specifies the period for which files are kept
	                       (default: "30d" for 30 days)
	    --archive, a     : Create a Zip archive instead of a subdirectory at
	                       destination.

