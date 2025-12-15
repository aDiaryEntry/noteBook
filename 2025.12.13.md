### java：

&nbsp;	1.学习Arrays工具类

&nbsp;		public static String toString(T arr\[])将数组转化为字符串

&nbsp;		public static int binarySearch(T arr\[], T)二分查找算法查找，返回索引

&nbsp;		public static int\[] copyOf(T arr\[], int size)拷贝数组

&nbsp;		public static int\[] copyOfRange(T arr\[], int stratIndex, int endIndex)拷贝数组（指定范围）

&nbsp;		public static void fill(T arr\[], int o)填充数组

&nbsp;		public static void sort(T arr\[])快速排序算法排序

&nbsp;		public static void sort(T arr\[], Comparator<T> c)使用插入排序加二分查找进行排序，其中排序规则在Comparator接口中实现，接口需要实现compare方法两个参数

&nbsp;											public abstract int compare(T o1, T o2);排序顺序由返回值正负决定

&nbsp;	2.lambda表达式

&nbsp;		在实现接口时通常使用匿名类实现，代码繁琐，lambda表达式可以简化代码

&nbsp;		例如该方法：public static void function(Interface inter);

&nbsp;	  	      function(new Interface（参数列表）{

&nbsp;				逻辑......

&nbsp;				});

&nbsp;		使用lambda可以写为：

&nbsp;		function((参数列表)->{

&nbsp;				逻辑.....l.

&nbsp;				});



