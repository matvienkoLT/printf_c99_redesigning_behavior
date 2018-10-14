# FT_PRINTF

[![N|Solid](https://static.licdn.com/sc/h/al2o9zrvru7aqj8e1x2rzsrca)](https://www.linkedin.com/in/lyubomir-matvienko-1a790b166/)

The ft_printf funciton sends the characters to the standard output stream stdout.

    Used functions and system calls for this project are: write, malloc, free, 
    and the functions of stdarg(3)
 
 The ft_printf function is prototyped as follows:
 
 ```
        int ft_printf(const char *format, ...);
```

Description and aim this project you can find here -> [Tasks](https://gitlab.com/ramm4/printf_c99_redesigning_behavior/blob/master/ft_printf.en.pdf).
# Behavior
The function  is realated to fprintf, but sends the characters to the standart output.
stream stdout.
Others description you can find in the

                man printf 
or [here](http://www.cplusplus.com/reference/cstdio/printf/)

### Screenshots
![](https://gitlab.com/ramm4/printf_c99_redesigning_behavior/raw/88750596c80000ad95156d0757a8c0208c2c586a/Screenshot_2018-07-03_08-42-04.png)
![](https://gitlab.com/ramm4/printf_c99_redesigning_behavior/raw/master/Screenshot_2018-07-03_08-56-28.png)

### How can I use these functions?
    Create library libftprintf.a
    make
    
    Rebuild library
    make re

    Delete *.o file and temp files
    make clean
    
#### Then include the "libftprintf.h" on your .c file, and finally compile your program like this:
            gcc example.c -o example -L. -lftprintf -I includes