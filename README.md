# dirarchive

## Version

	This is dirachive v. 0.1
	Copyright (c) 2012 Guillaume-Jean Herbiet  (http://herbiet.net)
	This is free software; see the source for copying conditions. There is NO
	warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

## Usage

	dirachive [-h|--help] [-V|--version] [-d|--debug] [-v|--verbose] [-N|--dry-run]
	    [-a|--archive <archive_dir>] [-p|--period <N[y|m|d|h|m|s]>]
	    [directory]
	
	  Archive directory content based on the "Date Added" value of the file.
	  All files of the directory with a date added older than the specified
	  period will be moved to an archived placed at the specified location.
	
	  Note: If your system has the non-enhanced version of 'getopt' (which is the
	  case by default on BSD systems, including Mac OS), only the short version
	  of the following options are available.
	
	    --help, -h       : Print this help, then exit.
	    --version, -V    : Print the software version, then exit.
	    --debug, -d      : Extended information about the script function.
	    --verbose, -v    : Display a summary of the executed operations.
	    --dry-run, -N    : Do not perform any actual action
	
	    --archive, -a    : Specifies the directory where the archive will be saved
	                       (default: '/Users/<USERNAME>/Archive')
	    --period, -p     : Specifies the period for which files are kept
	                       (default: "30d" for 30 days)

