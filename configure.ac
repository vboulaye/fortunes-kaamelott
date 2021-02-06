#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([fortunes-kaamelott], [0.1], [vincent.boulaye@orange.com])


AC_ARG_VAR(CURL, [curl is needed to get the quotes from wikiquotes])
AC_ARG_VAR(JQ, [jq is used to parse the response json])
AC_ARG_VAR(HTML2TEXT, [html2text transforms the html quotes to formatted text])
AC_ARG_VAR(STRFILE, [strfile makes the index for the fortunes quotes (installed with the fortne package)])
# Checks for programs.
AC_PATH_PROG(CURL, curl)
AC_PATH_PROG(JQ, jq)
AC_PATH_PROG(HTML2TEXT, html2text)
AC_PATH_PROG(STRFILE, strfile)
# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
