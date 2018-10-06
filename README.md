# MAX6675

The header files in C language for the MAX6675 Thermocouple to Digital Converter.
Written for ATMEGA 328P.
Check for change of register names if using with a different ATMEGA processor.

	1)Include the header file
	2)Initialize the SPI in the beginning of your code - init_spi
	3)Call the get Temp function anywhere in the code to get the current temperature - get_max6675_temp
