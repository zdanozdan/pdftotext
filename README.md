Usage: 
       pdftotext [options] <PDF-file> [<text-file>]

       -zdanozdan <int>   : zdanozdan
       -f <int>           : first page to convert
       -l <int>           : last page to convert
       -layout            : maintain original physical layout
       ## This is changed comparing to original XPDF version ####
       -sep <string>      : adds separator to help build csv or other separation type
       #########################################################
       -fixed <fp>        : assume fixed-pitch (or tabular) text
       -raw               : keep strings in content stream order
       -htmlmeta          : generate a simple HTML file, including the meta information
       -enc <string>      : output text encoding name
       -eol <string>      : output end-of-line convention (unix, dos, or mac)
       -nopgbrk           : don't insert page breaks between pages
       -opw <string>      : owner password (for encrypted files)
       -upw <string>      : user password (for encrypted files)
       -q                 : don't print any messages or errors
       -cfg <string>      : configuration file to use in place of .xpdfrc
       -v                 : print copyright and version info
       -h                 : print usage information
       -help              : print usage information
       --help             : print usage information
       -?                 : print usage information