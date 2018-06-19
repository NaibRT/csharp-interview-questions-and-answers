# C# Müsahibə sualları və cavabları

<<<<<<< HEAD
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
13. “static” keywordu C#-da izah edin.
>Biz hər hansı bir clasın memberlərindən istifadə etmı istəyiriksə onda həmin clasdan obyekt yaratmaq məcburiyyətindəyik.Amma
əgər həmin memberə instance olmadan access etmə istəyiriksə onda onu static ilə təyin edirik.bu zaman həmin dəyişən və ya method artıq clasın memberi olmur və ona clasın adı ilə müraciət olunur.Bir növ static ilə təyin olunan dəyisən qlobal olur.
=======
1. C# nədir? 


> C# 2000 - ci ildə "Andres Heilsberg" - tərəfindən Microsoft - da Java - ya Rəqib Olaraq İnkişaf Etdirilən müasir Abyekt Yönümlü Bir     Programlama Dilidir. C# - Microsoftun Java Uzərində Dəyişiklik Etməsini İstəmədiyi Ücün Yaradıldı. C# - İlk Yaradildigi Gündən Bəri     Sürətli Bir Şəkildə Böyüdü və Hal-hazırda Dünyanın Ən Populyar Programlama Dillərindən Biridir. Microsoft Platformunda Program           Təminatlari İnkişaf Etdirmək Üçün Dizayn Edilmiş Ümumi Məqsədli bir dildir ve Windows Üzərində İşləmək Üçün .NET Framework Tələb Edir.   C# - in Yaradilmasinda C ve C++ - dan İstifade Edilib və Buna Gorədə C#  C və C++ - in Hibrididir. .NET Framework Bir Çox Programlama   Dilini Dəstəkləsədə C# Sürətli Bir Şəkildə Ən Populyar OlanlardanBiri Halına Gəldi. C#  - Demək Olar ki  Hər Şey Yaratmaq Üçün           İstifade Olunur ama Özəlliylə windows Masaüstü Program Teminatlari və Oyunlar Yazmaq Üçcün Daha Yaxşıdır. C# - Həmçinin Web-Tətbiqlər   Yaratmaq Üçündə İstifade Olunur amma özəlliklə Mabil Tətbiqlər İnkişaf Etdirmək üçündə get-gede daha Populyar Hala Gəlmişdir.Xamarin     Kimi Cross-Platform alətlər(tool-lar) C# - da Yazılan Tətbiqləri Demək Olar ki Bütün Mabil Cihazlar-da İstifadə Olunmasını Təmin Edir.

> C# - Günümüzdə Ən Papulyar Oyun Mühərriki olan Unity Oyun Mühərrikini İstifadə Edərək Oyunlar Yaratmaqı Təmin Edir. En Yaxşı Oyunların   3/1 - dən Çoxu Unity İlə Yaradıldı ve Unity Muhherikini İstifadəsi İlə Yaradılan Təqribən 770 milyon aktiv Oyun İstifadecisi Var. C# -   Bu Tətbiqləri Yaratmaq Üçün Populyar Bir Alətdir Programçı ve Programlamaya Yeni Başlayanlar Üçün-də Mükəmməl Bir Seçimdir.C# -         həmçinin Statik Olaraq Yazılmış Bir Dil-dir  və Bu Səbəblə Bir Təminata(exe) - Çevrilmədən Öncə Yoxlanilir. Bu Yeni Başlayanlar Üçün     Xüsusilə Praktik Ola Biləcəy Xətaları Tapmaqı Asanlaşdlrır. C# - Qarmaşıq Bir Dil-dir və Bu Dildə Master Olmaq Bəzi Sade Dillər         ilə(Pyton) Müqayisede Daha Çox Vaxt Alır. Bu O Demək-dir ki Programçının İrəli Səviyyəli Programlar Yazmaqi Üçün Daha Çox Kod           Öyrənməyi Lazımdır ve Bu Yeni Başlayanlar Üçün Sinir Bozucu Ola Bilər. Güclü Əsnək və Microsoft Tərəfindən Dəstəklənmiş Olması C# - ı   Movcud Olan Ən Yaxşı Programlama Dillərindən Biri Halına Gətirmişdir.Bu Gün C# - Ən Yaxşı Programlama Dilləri Arasında 4 - cü Sırada     Yer Alır ve Teqribi Developerlərin 31 faizi Bu Dili Müntəzəm Olaraq İsitfadə Edir. Həmçinin C# Stack-overflovda(Hansıki C# - ilə         Yaradıldi) 1.1 milyondan çox mövzu ilə 3-cü sırada yer alır. Bu Populyarlıq İnkişaf Etmiş İş Bazarına Çevrilir. Hər Ay 17000 - dən Çox   C# - işləri Elan Edilir və Ortalama 72000$ - dan çoc maaş - ilə. Sadəcə Birləşmiş Ştatlar-da Hər ay 92000$ - lıq Maaşla 6 mindən Çox     İş Elan Edilir.





2. C# - ın özəlliklərini İzah Edin?

> 1.C# - ı İstədiyiniz Editor-da Yaza Bilərsiniz
>  2.C# - ı Açıq Qaynaqli Dildir
>  3.C#  - Vindovs Mac ve Linux - da İşləyir
>  4.C# - Vindovs Müştəri Tətbiqləri Vindovs Mağaza Tətbiqləri İOS Tətbiqləri  Android Tətbiqləri və Həmçinin (backend  framevork           library) - lar Yaratmaq Üçün İstifade Olunurş
>  5.Bütün IDE'leri ve editorlar-ı dəstəkləyirş
>  6.Fiks Etme Yenidən Düzənləmək və Kod Yaratmaq Aletleri(cw+tab+tab)destekleyir.
>  7.C# - 7 -- tuplesleri  Rekord  ve Pattern - leri Destekleryir
>  8.C# - gəncdir ve inkişaf edir.
>  9.C# - Obyekt Yönümlüdür
>  10.C# - sade-dir.
>  11.C# - strukturlu programlama dilidir.
>  12.C# - Type safe(güvenli yazı)
>  13.C# - Birlikte Calisabilirklik(Interoperability)
  
  
 
3. C#-ın üstünlüklərindən ən vaciblərini sadalayın.

4. What are IDE’s provided by Microsoft for C# development?

> Visual Studio 2017

5. C# - daki Kamentariya Tiplərini İzah Edin

> c#-da Kamentariyalar Bizə Kod Hissəciylərini Başa Düçməyimizə Kömək Edir. Kamentariyalar Compiler Terefinden Tamamən Yox Sayilir

> C#-da 3 Kamentariya Tipi Vardırş

>1.Single Line Comments(Tək Sətir Kamentlər)
 2.Multi Line Coments(Çox Sətirli Kamentlər)
 3.XML Comments(XML Kamentlər)

 > 1) Tək Sətirlər Kamentlər Cüt Slaş ilə Başlayır , Compiler " // " - dan Sonra Sətirin Altina Düçənə Qədər Yazilan Hər Şeyi Yox Sayır 
   
       int a = 5  // 5 və 7 - ni Toplayır
   
> Tək Sətirli Kamentariyalar Ayrı Bir Sətirdə və ya Kodlarla Eyni Sətirdə Yazıla Bilər  Ama Ayrı Bir Sətirdə Yazmaq Daha Yaxşıdır.
   

 > 2) Cox Sətirli Kamnentariyalar " /* " - ilə Başlayır və  " *\ " Bitir. Çox Sətirli Kamentariyalar Birdən Çox Sətirə Yayıla Bilər.


  > 3)XML - Bilmirəm Hələki

  > Kamentariyalar Kod Hissəciklərini izah Etmək Üçün İstifade Olunur Ama Çox İstifade Etmək Olmaz

 > 1)Kamentariyalar Qarışıq Algoritmaları İzah Etmək Üçün İstifade Edilməsi Daha Düzgündür.
 > 2)Kamentariyalar Uzun Bir açıqlama Yerinə qısa və kankret olmalıdır.

   

6. C# - daki Sealed Klasını İzah Edin?

> Sealed Klass Obyekt Yönümlü Programlamanın İnheritance(miras) Xüsusiyyətini Ləğv Edir. Sealed Klasin İxtira Olunmasinin Səbəbi Odur ki Həmin Klasin Genişləndirilməyə Ehtiyyacinın Olmadığını deyirikk. Bu Klass İnheritance Ala Bilməz. C# - da "sealed" keywordu Klasın Sealed Klas Olduğunu Müəyyən Edir. Əgər Sealed Tətin Olunmuş Klas-dan İnheritance Almaqa Cehd Etsək Compile Error Verəcək.
 


7. Give an example of using sealed class in C#?
8. List out the differences between Array and ArrayList in C#?
9. C# da "using" nə üçün istifadə olunur
10. Explain namespaces in C#?
11. Why to use keyword “const” in C#? Give an example.

> Fərz edək ki Bir dəyişənimiz var  və biz bu dəyişənimizin dəyərinin heç bir yerdə dəyişilməməsini sabit qalmasını istəyə bilərik.Bu     zaman Bize (const) - keyvordu komək edir. Const keyvordunun Qaydaları.
> 1. Const keyüordu local Dəyişənlərə və Filed-lərə Təyin Edilə Bilər.
> 2. Const keyüordu yalnız primitiv dəyərlərə təyin edilə bilər(int double).
> 3. Constant təyin etdiyimiz (field ve dəyişənlərə) declaration anında dəyər təyin etməliyik.
> 4. Constant dəyişənlər (const) - keyüordu ilə təyin edilir.

12. What is the difference between “constant” and “readonly” variables in C#?
13. Explain “static” keyword in C#?
>>>>>>> 970ed31c1aee64edee4736109e8a34ce521635eb
14. What is the difference between “dispose” and “finalize” variables in C#?
>
15. How the exception handling is done in C#?
>
16. Can we execute multiple catch blocks in C#?
>
17. C#-da nəyə görə Finally blogundan istifadə olunur?
>
18. What is the difference between “finalize” and “finally” methods in C#?
>
19. What is the difference between “throw ex” and “throw” methods in C#?
>
20. Can we have only “try” block without “catch” block in C#?
>
21. C#-da error növlərini səralayın.
>C#-da 3 error növü mövcuddur.Syntax Error,Logic Error,Run-Time Error.
Syntax Error kod yazarkən qarşımıza cıxır və bu bizim kodumuzun sintaks olaran yanlış yazdigimizi göstərir.
Logic Error program isləyərkən baş verir və bizim istəmədiyimiz tam fərqli resullarla nəticələnə bilir.
Run-Time Error program compile olunduqdan ve run olunduqdan sonra görünən xetalardir ki
22. Do we get error while executing “finally” block in C#?
>
23. Mention the assembly name where System namespace lies in C#?
>
24. Static, public və void arasındkı fərqləri nədir?
>Static vasitəsilə yaradılan hər hansı method,dəyisən obyekt yaradilmadan programın istənilən yerində access oluna bilər.
Public method və ya dəyisən programin hər yerində access oluna bilər obyect yaratmaqla.
Void isə methodlard istifadə olunur və bu methodlarin heç bir return olmur.
25. “out” və “ref” parameterləri arasındkı fərq nədir?
>out parametr olaraq ötürülməzdən əvvəl dəyər təin olunmaya bilər lakin ref -də əvvəlcədən dəyər təyin olnmas program error verəcək.
26. Jagged Arrayləri izah edin.
>Jagged arraylər o arraydir ki həmin arrayin elementləri özü də bir arraydir və hər bir element arraylarinin index ölçüləri fərqlidir.
27. C#-da static methodun icində this istifadə oluna bilər?
>this istifadə oluna bilməz çünki static method clasın memberi syılmır.
28. C#-da dəyər tipləri hansılardır?
>C# -da dəyər tipləri aşagıdakılardır.
İnt,Uint,Byte,Sbyte,Long,Ulong,Short,Ushort,Decimal,Float,Double,Bool,Char
30. C#-da referans tiplər hansılardır?
>C# -da referans tipləri aşagıdakılardır.
Object,String,Dynamic
31. Can we override private virtual method in C#?
>
32. “protected internal” access modifieri izah edin.
>protected internal vasitəsi ilə həm eyni assembly daxilində hemdə child class daxilində access olunur.
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
<<<<<<< HEAD
>
93. What is Method Hiding in C# ?
>
94. What is Abstract Class in C#?
>
95. What is Sealed Classes in c# ?
>
=======

> Override miras yolu ilə təməl sinifin referansını istifadə edərək fərqli siniflərə aid metodları çağırmağımıza icazə verən bir xüsusiyyətdir.C# - bizə (override) əməliyyatını həyata keçirmək üçün 2 keyüord verir. (virtual və override).
Bir Metod yalnız (virtual) keyvordu ilə təyin olundugu halda biz miras alınmış sinifdə onu (override) - edə bilərik.(override) base clasda olan virtual metodu (override) - edir. Override Ozəlliyi Programçılara Təməl Sinifdə (virtual) memberi miras almış sinifdə yenidən tətbiq etməyə icazə verir. Override miras alan sinifdə dəyişilməyə ehtiyyacı olan (metod property indexer və ya event) - lər ilə işlənə bilər. override xüsusiyyəti C# - da polymoprhism qavramını tətbiq etmək üçün dizayn edilmişdir.

93. What is Method Hiding in C# 

> Derived Sinif İçərisində təməl(base) Sinifə aid bir metodu (override) etmeden təkrar Tanimlasanız base(temel) sinifdəki halı qorunacaqdır. Bu Hala Metod Hiding Deyilir.

    class Product

    {

        public int İd { get; set; }

        public string Name { get; set; }

 

        public void Test()

        {

            Console.WriteLine("Product Sinifinin Memberiyəm");

        }

    }
    
    
    
    
    class Book : Product

    {

        public string Author { get; set; }

 

        public void Test()

        {

            Console.WriteLine("Kitab Sinfinin Memberiyəm");

        }

    }


> Burada Book Sinifinde Olan Test() Metodu  Temel Product Sinifinde Olan Test() Metodu İle Eynidir Buna Gore  Base Sinifdə Olan Test()     Metodu  Gizlenir ve Book - da Olan Metod İşləyir ama Compiler Bizə Xeberdarlıq Verir. Buna Görədə Metod hiding Eederek Bu xeberdarlıqı   Aradan Qaldırırıq. nev keyvordu istifade ederek yoxlayaq.
 
      
    class Book : Product

    {

        public string Author { get; set; }

 

        //new public void Test() şeklinde de yazabiliriz.

        public new void Test()

        {

            Console.WriteLine("Kitab Sinifinin Memberiyem");

        }

    }
    
Bele Daha Düzgündür Artıq Base(təməl) Sinifdəki Metod Gizləndi. 

94. What is Abstract Class in C#?

> Abstract Siniflər .NET Tərəfindən təmin edilən təməl davranışlardan biridir. Ümumi olaraq yalnız təməl Sinifləri təmsil edən və hər hansı birinin bu Siniflərdən Obyekt yaratmasını istəmədiyimiz siniflər yaratmaq istəyə bilərsiz. c# - da (abstract) istifade ederek Astract Sinifləri Tətbiq edə Bilərik. Abstrackt sinifin mənası bu sinif - də obyekt yaradıla bilməz ama miras alına bilər.

    abstract class absClass
    {
     
    }

> Abstract Sinif (abstract) olan və (abstract) olmayan metodlar saxlaya bilər. Abstract memberlərin (abstract) sinif içərisində heç bir tətbiqi olmur ama ondan miras alan sinifə bu özəlli təmin edilir.


         abstract class absClass
         {
             public abstract void absMethod();
         }

> Dediyimiz kimi Abstract Siniflərin İçərisində abstract olmayan memberlər - də ola bilər.

    public void Show()
    {
       
    }

> Abstract metod və Abstract Sinif-dən başqa heç bir yerdə təyin edilə bilməzlər. Abstract metodlar derive olundğu sinif-də (override) olunmalıdırlar. Abstract metodların (body) - si Olmur.

> Abstract- da Bəzi Qaydalar

> 1.Abstract Sinif (selaed) - olaraq təyin edilə bilməz
> 2.Abstract metodlar yalnız abstract sinifdə ola bilər
> 3. Abstract metodlar private ola bilməz
> 4.Abstract Sinifin (Access Modifieri) həm Abstract Sinifdə həmdə ondan miras almış sinifdədə eyni olmalıdır
> 5.Abstract metodun (virtual) keyvordu olmur. Çünki Abstract metod onsuzda virtual olur.

95. What is Sealed Classes in c# ?

> Sealed Siniflər Obyekt Yönümlü Programlaşdırmanın inheritance(miras) xüsusiyyətini ləğv eiliyir. Sealed Sinifinin İxtira olunmasının məqsədi odur ki biz bu sinifə deyirkki sənin genişləndirlməyə Ehtiyyacın Yoxdur. Sən miras ala Bilməzsən

>>>>>>> 970ed31c1aee64edee4736109e8a34ce521635eb
96. What is an Interface in C# ?
>
97. What is a Constructor in C# ?
<<<<<<< HEAD
>
98. What is a Destructor in C# ?
>
=======

> Qurucular Xüsusi Metodlardır və Sinifdən örnəy(abyekt) yaratdıgımız anda işə düşürlər.Qurucuların Əsas Məqsədi Sinifin Örnəyi Yaranan Anda Sinifdə Olan (private) gizli field-lari Başlatmaqdır. Əgər Biz Özümüz Qurucu Metod Yazmasaq (Compiler) Avtomatik Olaraq Default Qurucu Metodu İşə Salacaq. Default(varsayılan) qurucular Sinfidəki (numerik) field-lərə  zero(0) (string və object) - filed-lərə isə (null) - dəyəri Təyin Edir.  Qurucularda Bəzi Vacib Nöqtələr Vardır.

> 1.Sinifin Birdən Çox Qurucu Metodu Ola Bilər
> 2.Bir Qurucu Metodun Hansısa (return) Tipi Yoxdur (void) - də Daxil Olmaqla. Çünkü Obyekt return Edir.
> 3.Statik Qurucular Parameter Qəbul Edə Bilməzlər.
> 4.Bir Sinif İçərisində Yalnız Bir Statik Qurucu Ola Bilər.

> Qurucular 5 Tipə Bölünür.

> 1.Default(varsayılan) Qurucular
> 2.Parametreli Qurucular
> 3.Copy Qurucular
> 4.Statik Qurucular
> 5.Private Qurucular

> 1.1)Hər Hansı Bir Parametresi Olmayan Qurucular varsayılan(defult) qurucular adlanır.bu cür qurucuların parametresi olmur.Bunun mənfi cəhəti odur ki default(varsayılan) qurucu hər obyekt yarananda eyni dəyərlər Təyin Edir.
Hər Obyekt Yaradanda Ferqli Deyerler Teyin Etmek Mümkün Deyil. Varsayılan Qurucu Aşagıdakı Dəyərləri Təyin Edir

 1.Bütün Numerik Filedlər-ə (0) - ı
 2.Bütün (string ve object) dəyərlərə (null) - u
 
> 2.2)Ən az Bir Parametresi Olan Qurucuya Parametreli Qurucu Deyilir. Parametreli Qurucunun Müsbət Cəhəti Odur ki Hər obyekt yaradanda fərqli dəyərlər Təyin Ede Bilərsiz.

    public class Employee 
    {
       public int a,b;
       
       public Employee(int x , int y)
       {
         this.a = x;
         this.b = y;
       }
    }
    
> 3.3)Başqa bir obyektden dəyişənləri kopyalayaraq bir obyekt yaradan qurucuya (copy) qurucu deyilir.(Copy) qurucunun Əsas Məqsədi         Mövcud Olan Obektin Dəyərləri ilə Yeni Obyekt Yaratmaqdır.  
  
  > 1.Statik Qurucuların Parameteri və Access Modifieri Olmur
  > 2.Statik qurucu işə düşdüyündə istifadeci onu idarə edə bilməz
  
  
  
  

   
     public class Employee 
    {
       public string Name
       public int Age
       
       public Employee(Employee emp)
       {
         this.Name = emp.Name;
         this.Age = emp.Age;
       }
    }
    
    
> 4.4)Qurucu Statik olaraq təyin olunarsa  Bütün Obyektlər Üçün Bir dəfə Çağırılır və Sinifin ilk Obyekti Yaradilan Anda işə düşür         Statik Bir Qurucu Sinifin Statik Olan Üzvlərini Başlatmaq və Sadəcə Bir dəfə run olunacaq kodu İşə salmaq üçün İstifade Olunur.

98. What is a Destructor in C# ? 
99. What is CLR in c# ?
100. What is Garbage Collecter in C#?
>>>>>>> 970ed31c1aee64edee4736109e8a34ce521635eb
