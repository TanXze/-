### C++

编译型语言

1. using std::xxx;

   使用命名空间std中的指定内容

   using std::cout;

   using std::endl;

2. g++ -o program main.cpp

   ./program

3. main函数：程序运行的入口

   #include：用于包含（引入）头文件

   iostream：程序输入输出流类库对应的头文件

   cout对象：程序流式输出对象

4. cin 对象连续读取多个变量时，默认以空格或者回车为分界

   cin 对象可以从键盘上连续读取多个输入

   要使用流式输入输出对象，必须使用它们对应的命名空间

5. 结果保留两位小数：cout << fixed << setprecision(2)

6. break：彻底结束整个单层循环

   continue：结束本次循环

   goto：跳转到指定的某个语句

7. 
