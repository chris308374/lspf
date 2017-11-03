# lspf
Open source Linux version of IBM's z/OS ISPF Dialogue Manager written in C++

Application programs wishing to use DM Services, can be written in C++ or rexx (open object rexx).  Calls are made via a pApplication method or the ISPEXEC interface.

Most services are supported (missing services are mostly file tailoring, and LM*) as are dynamic input/output areas, tables and a large subset of the ISPF panel language.  See doc directory for more details.

This as been written as an exercise whilst learning C++ and OOP and I've put it on GitHub in case anyone wants to use/contribute to it.  There is a lack of applications, but there is a browser, an editor similar to the mainframe PDF editor that also supports macros written in OOREXX and syntax hilighting and a file list application.

Other features include split screen, application stacking, keylists, reflists, command tables, field expansion, command retrieve, cursor-sensitive help, keylist help etc. (see Help)

Screenshots:

https://user-images.githubusercontent.com/15121632/32369290-942fdd3e-c080-11e7-908b-379ff2acdaef.png

https://user-images.githubusercontent.com/15121632/32369287-920be2d2-c080-11e7-936e-69664450d4aa.png

https://user-images.githubusercontent.com/15121632/32369287-920be2d2-c080-11e7-936e-69664450d4aa.png

