#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([uboot-bootcount],
        [2.0.0],
        [thom.nichols@voltserver.com],
        [],
        [https://github.com/VoltServer/uboot-bootcount])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE([foreign])

# Checks for programs.
AC_PROG_CC

# Checks for libraries.
#LT_INIT([disable-shared])

# Checks for header files.
AC_CHECK_HEADERS([fcntl.h unistd.h sys/mman.h sys/stat.h sys/types.h])
AC_CHECK_HEADER_STDBOOL

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_OFF_T
AC_TYPE_SIZE_T
AC_TYPE_SSIZE_T
AC_TYPE_UINT8_T
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T

# Checks for library functions.
AC_FUNC_MMAP
AC_CHECK_FUNCS([strtoul memset])

AC_CONFIG_FILES([
  Makefile
  src/Makefile
])
AC_OUTPUT
