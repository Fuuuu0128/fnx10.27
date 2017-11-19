###  2017-10-27


# 故道白云
#### 0x00 [原理]
     kali虚拟机下的命令运用，sqlmap的使用
#### 0x01 [目的]
     了解kali系统下sqlmap的使用
#### 0x02 [环境]
     kali
#### 0x03 [工具]
     sqlmap
#### 0x04 [步骤]

1.首先打开address，提示为使用sqlmap完成sql注入

![](/files_for_wp/1_1.png)

2.先进行手工注入：</br>
  ①.检测注入点</br>
  
  ![](/files_for_wp/1_2.png)</br>
  
  正常回显</br>
  
  ![](/files_for_wp/1_3.png)</br>
  
  正常回显</br>
  
  ![](/files_for_wp/1_4.png)</br>
  
  不报错，无回显</br>
  
  ②.检测字段数:为2</br>
  
  ![](/files_for_wp/1_5.png)</br>

3.使用sqlmap注入
  ①暴库</br>
  ![](/files_for_wp/1_6.png)</br>
  
  ![](/files_for_wp/1_7.png)</br>
  
  ②暴表</br>
  ![](/files_for_wp/1_8.png)</br>
  
  ![](/files_for_wp/1_9.png)</br>
  
  ③暴字段</br>
  ![](/files_for_wp/1_10.png)</br>
  
  ![](/files_for_wp/1_11.png)</br>
  
  ④暴字段内容</br>
  ![](/files_for_wp/1_12.png)</br>
  
  ![](/files_for_wp/1_13.png)</br>

4.flag：SYC{HACKEr_By-cL0und}

#### 0x05 [总结]
    sqlmap使用
</br>
</br>
</br>
</br>
</br>






# 找规律

#### 0x00 [原理]
     编写代码
#### 0x01 [目的]
     通过编写代码，找到数列的规律
#### 0x02 [环境]
     windows
#### 0x03 [工具]
     Excel
#### 0x04 [步骤]

1.首先打开题目

![](/files_for_wp/2_1.png)

2.代码

![](/files_for_wp/2_2.png)</br>
![](/files_for_wp/2_3.png)</br>

3.运行结果

![](/files_for_wp/2_4.png)</br>

4.在Excel中运算

![](/files_for_wp/2_5.png)</br>

6.flag：SYC{4274885634120} 

#### 0x05 [总结]
编程能力   
