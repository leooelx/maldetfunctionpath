# Linux Malware Detect v1.6.4 functions path

This version have a issue on the file internal/functions, at function monitor_check() that can't parse directories and/or files with whitespaces on name. The line 1569 was chaged to get the correct path/file name to be scaned by clamscan command.
