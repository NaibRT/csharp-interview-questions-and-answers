﻿# C# Müsahibə sualları və cavabları

1. C# nədir?
>C# Microsoft Corporation tərəfindən .Net platformu üçün yaradilan multi-paradigmali programlama dilidir.Bununla Windows Client Aplication,Xml Web Services,Client-Server Aplication və.s yazmaq mumkundur.
2. Explain the features of C#?
> Öyrənmək çox asandır
3. C#-ın üstünlüklərindən ən vaciblərini sadalayın.
>
4. What are IDE’s provided by Microsoft for C# development?
>
5. Explain the types of comments in C#?
>
6. C#-da sealed classı izah edin?
>Sealed classlar "sealed" keywordu ilə təyin olunur.Sealed claslarin xüsüsiyyəti onlarin inherit verə bilməməsidir.Bu baximdan sealed claslar base clas ola bilmirlər.Amma bu claslardan obyekt yaratmaq mumkundur ve eyni zamanda ozləri də inherit ala bilirlər.
7. C#-da sealed clasin istifadəsinə dair misal gostərin?
>
8. C#-da Array və ArrayList arasindaki fərqlər.
>Array strong tipdir.Yeni dəqiq bir tipdə data özündə tuta bilər amma Arraylistdə istənilən tipdə data tutmaq mümkündür.
Array təyin edərkə tutacaqi elementlərin sayını əvvəlcədən müəyyən etmək lazımdır amma Arraylistdə özü genişləyə bilir.
Arrayin tipi əvvəlcədən müəyyən olunacağı üçün onu cast etməyə ehtiyac yoxdur ancaq Arraylistdə cast etmək lazımdır.

9. C# da "using" nə üçün istifadə olunur?
>C# da using keywordunun istifadəsi 2 cürdür.Using Directive və using Statement.Using Directive hər hansı namespace-i yazdığımız programa daxil edib onun içindəki claslardan istifadə etmə üçün tətbiq olunur.
Using statement isə Garbage Collector əvvəl istifadə olunan clasi İDisposable interfacesinin Dispose methodu ilə silinməsi üçün istifadə olunur.
10. C#-da Namespaceni izah edin.
>Namespace hər şeydən əvvəl bizə hierarchical program yazmağımıza kömək edir.Bununla yanaşı C# da standart Library olmadigindan yazdıgımız bütün claslar və methodlar bir namespace altında toplanir və
sonra həmin namespaceni "using" keywordu vasitəsilə başqa programlarda istifadə etmək mümkündür.
11. Nəyə görə "const" keyvordu istifadə olunur? Misal gətirin.
>Program yazarkən dəyişməyəcək və hər zaman sabit qalacaq olan dəyişənlərimizi "const" keywordu ilə yaziriq.Həmin dəyər run time da dəyişmək mümkün olmur.

12. Constant və Readonly arasindaki fərq nədir?
>Constant static ilə declare oluna bilməz çünki defult olaraq statikdir amma Readonly static kimi təyin oluna bilər.
Constant compile time da müəyyən olunur ancaq Readonly run time da  müəyyən olunur.
Constant declear olundugu anda dəyər təyin olunmalıdır ancaq Readonly həm təyin olundugu anda həm də canstructor methodun içində sonradan təyin oluna bilər.
13. Explain “static” keyword in C#?
>
14. What is the difference between “dispose” and “finalize” variables in C#?
>
15. How the exception handling is done in C#?
>
16. Can we execute multiple catch blocks in C#?
>
17. Why to use “finally” block in C#?
>
18. What is the difference between “finalize” and “finally” methods in C#?
>
19. What is the difference between “throw ex” and “throw” methods in C#?
>
20. Can we have only “try” block without “catch” block in C#?
>
21. List out two different types of errors in C#?
>
22. Do we get error while executing “finally” block in C#?
>
23. Mention the assembly name where System namespace lies in C#?
>
24. What are the differences between static, public and void in C#?
>
25. What is the difference between “out” and “ref” parameters in C#?
>
26. Explain Jagged Arrays in C#?
>
27. Can we use “this” inside a static method in C#?
>
28. What are value types in C#? C#-da deyer tipleri nedir ne demekdir?
>
30. What are reference types in C#?
>
31. Can we override private virtual method in C#?
>
32. Explain access modifier – “protected internal” in C#?
>
33. In try block if we add return statement whether finally block is executed in C#?
>
34. What you mean by inner exception in C#?
>
35. C# da String Builder klasın izah edin.
>
36. What is the difference between “StringBuilder” and “String” in C#?
>
37. What is the difference between methods – “System.Array.Clone()” and “System.Array.CopyTo()” in C#?
>
38. Can you store multiple data types in an array?
>
39. How we can sort the array elements in descending order in C#?
>
40. Explain circular reference in C#?
>
41. List out some of the exceptions in C#?
>
42. Explain Generics in C#?
>
43. Explain object pool in C#?
>
44. What you mean by delegate in C#?
>
45. What are the types of delegates in C#?
>
46. What are the three types of Generic delegates in C#?
>
47. What are the differences between events and delegates in C#?
>
48. Can we use delegates for asynchronous method calls in C#?
>
49. What are the uses of delegates in C#?
>
50. What is Nullable Types in C#?
>
51. Why to use “Nullable Coalescing Operator” (??) in C#?
>
52. What is the difference between “as” and “is” operators in C#?
>
53. What is the difference between CType and Directcast in C#?
>
54. Is C# code is unmanaged or managed code?
>
55. Why to use lock statement in C#?
>
56. Explain Hashtable in C#?
>
57. How to check whether hash table contains specific key in C#?
>
58. What is enum in C#?
>
59. Which are the loop types available in C#?
>
60. What is the difference between “continue” and “break” statements in C#?
>
61. Write a sample code to write the contents to text file in C#?
>
62. What you mean by boxing and unboxing in C#?
>
63. Explain Partial Class in C#?
>
64. Explain Anonymous type in C#?
>
65. Name the compiler of C#?
>
66. Explain the types of unit test cases?
>
67. Explain Copy constructor in C#?
>
68. Explain Static constructor in C#?
>
69. Which string method is used for concatenation of two strings in c#?
>
70. Explain Indexers in C#?
>
71. What are the collection types can be used in C#?
>
72. Explain Attributes in C#?
>
73. List out the pre defined attributes in C#?
>
74. What is Thread in C#?
>
75. List out the states of a thread in C#?
>
76. Explain the methods and properties of Thread class in C#?
>
77. What is a class ?
>
78. What is an Object?
>
79. What are the Access Modifiers in C# ?
>
80. Explain Static Members in C# ?
>
81. What is Reference Type in C# ?
>
82. Define Property in C# ?
>
83. Explain Overloading in C# ?
>
84. What is Constructor Overloading in C# .net ?
>
85. What is Function Overloading in C# .net ?
>
86. What is Operator Overloading in C# .net ?
>
87. What is Data Encapsulation ?
>
88. Explain Inheritance in C# ?
>
89. Can Multiple Inheritance implemented in C# ?
>
90. What is Polymorphism in C# ?
>
91. Explain the use of Virtual Keyword in C# ?
>
92. What is overriding in c# ?
>
93. What is Method Hiding in C# ?
>
94. What is Abstract Class in C#?
>
95. What is Sealed Classes in c# ?
>
96. What is an Interface in C# ?
>
97. What is a Constructor in C# ?
>
98. What is a Destructor in C# ?
>
