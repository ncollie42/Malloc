Malloc

/*
	Use: Have a program that uses Malloc.

    Run this cript before running that program
   /*
        #!/bin/sh
        export DYLD_LIBRARY_PATH=.
        export DYLD_INSERT_LIBRARIES="libft_malloc.so"
        export DYLD_FORCE_FLAT_NAMESPACE=1
        $@
    */

    $> sh script.sh ./a.out

	------------
    If using the test.c, Don't compile with the helper functions ex. show_alloc_mem(), It needs the function from the .so that we didn't include.
*/