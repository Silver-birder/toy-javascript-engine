# toy-javascript-engine

```
$ cd build
$ cmake ..
$ make
$ ./main
```

```
$ clang -S -emit-llvm -O2 src/main.cc
$ lli main.ll
$ llc main.ll
$ gcc main.s -o main
$ ./main
$ echo $?
```
# Links

* https://github.com/maekawatoshiki/rapidus
* https://github.com/ndreynolds/flathead
