# hello-world
$ ls
hello.c
$ clang hello.c
$ ls
a.out*  hello.c
$ ./a.out
hello, world
$ clang -o hello hello.c
$ ls
a.out*  hello*  hello.c
$ ./hello
hello, world
$ make hello
clang -fsanitize=signed-integer-overflow -fsanitize=undefined -ggdb3 -O0 -std=c11 -Wall -Werror -Wextra -Wno-sign-compare -Wno-unused-parameter -Wno-unused-variable -Wshadow    hello.c  -lcrypt -lcs50 -lm -o hello
$ ./hello
hello, world
$ make hello
clang -fsanitize=signed-integer-overflow -fsanitize=undefined -ggdb3 -O0 -std=c11 -Wall -Werror -Wextra -Wno-sign-compare -Wno-unused-parameter -Wno-unused-variable -Wshadow    hello.c  -lcrypt -lcs50 -lm -o hello
$ ./hello
hello, world
$ ./hello
hello, world
