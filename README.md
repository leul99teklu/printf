![](https://www.alxafrica.com/wp-content/uploads/2022/01/header-logo.png)

## printf()
printf function by Leul Gebremariam and Misganaw Tenaw, were the function named "_printf" imitates the actual "printf" command located in the stdio.h library.

_printf() is a function that performs formatted output conversion and print data. Its prototype is the following:

	int _printf(const char *format, ...)

Where **format** contains the string that is printed. As _printf() is variadi function, it can receives n arguments that replace by n tags written inside the string.

The format tags prototype is the following:
	
	%[flags][length]specifier

If the program runs successfully, the **return value** is the amount of chars printed.
