# TFastDict
TFastDict是COM版本的字典，速度很快，处理大量数据时非常有用。 This source code is the COM version of the dictionary. It's fast. Very useful when working with large amounts of data.      
   
测试增删100万数据结果：   
![image](https://github.com/bzmework/TFastDict/blob/master/test.jpg)      
由于封装成了COM DLL，性能有所损耗，在可接受的范围之内。   
   
编译环境：   
Windows 10   
Visual Studio 2019   
说明：支持vs6-vs2019所有版本编译，如果你要支持在xp上使用，请采用TFastDict.dsw，若有必要则进行升级，   
升级路线一般是：vs6升级到vs2005进行过渡然后升级到更高版本的vs编译环境。   
