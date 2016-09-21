#malloc与new对比
(Created by buaadpy, 2016-09-21)

1.malloc与free是C++/C语言的标准库函数，new/delete是C++的运算符  
2.malloc与free不会调用构造与析构函数，而new/delete除了分配释放内存，还会调构造析构函数  
3.new返回相应类型的指针，而malloc返回void指针  
4.C程序只能用malloc/free管理动态内存  
5.malloc与free配对使用，new与delete配对使用  