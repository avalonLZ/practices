main程序依赖动态链接库libfunction1.so，且各自相关的头文件和c文件都已经被删除，main程序依然可以正常运行
说明，依赖某动态链接库的程序，在编译成功后，并不会依赖任何c文件或头文件
