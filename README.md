# CLI
测试结果如下
### 1.selpg -s1 -e1 input_file  
  ![1](/image/1.png)  
### 2.selpg -s1 -e1 < input_file  
  ![2](/image/2.png)  
### 3.other_command | selpg -s10 -e20  
  ![3]/image/(3.png)  
### 4.selpg -s10 -e20 input_file >output_file  
  ![4](/image/4.png)  
### 5.selpg -s10 -e20 input_file 2>error_file  
  ![5](/image/5.png)  
### 6.selpg -s10 -e20 input_file >output_file 2>error_file  
  ![6](/image/6.png)  
### 7.selpg -s10 -e20 input_file >output_file 2>/dev/null  
  ![7](/image/7.png)  
### 8.selpg -s10 -e20 input_file >/dev/null  
  ![8](/image/8.png)  
### 9.selpg -s10 -e20 input_file | other_command  
  ![9](/image/9.png)  
### 10.selpg -s10 -e20 input_file 2>error_file | other_command  
  ![10](/image/10.png)  
