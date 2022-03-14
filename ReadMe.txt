
//To compile the Code:

gcc -Wall hw3 -o hw3.c

//To run the Code. //Replace ${dir} with file path.

	./hw3 -S ${dir}

	./hw3 -s ${minSize} ${dir}

	./hw3 -t d ${dir}

	./hw3 -t f ${dir}

	./hw3 -f ${format} ${dir}

	./hw3 -s 1024 -e "ls -l" ${dir}

	./hw3 -f c -e "ls -l" ${dir}

	./hw3 -f jpg -E "tar cvf jpg.tar" ${dir}

	./hw3 -s 1024 -e "wc -l" ${dir}

//To run the code using Make file.


         make <aliasname>  // as given in the makefile.

