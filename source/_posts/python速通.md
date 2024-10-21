---
title: python速通
tags:
  - python
  - 速通
date: 2024-05-04
---
# jieba库使用

 **选择|15
 填空|8
 编程|1**
# 编程
## 一维数据
```python
f=open()
ls=f.read().split()

```

## 算法
用函数来写

### 素数
```python
def prime(n):
	if n<2:
		return False
```
		
### 升降序数
```python
def jx(n):
	s=str(n)
	for i in range(len(n)-1):
		if s[i]>=s[i+1] :
			return False
	return True
```
### 最大公约数
### 最小公倍数
### 因子和
### 回文数
### 阶乘
#### 递归形式
#### 非递归形式



### 斐波那契数列
## 二维数据
```python
f=open("score.csv")
f.readline()

```
## 中文词频分析
# 理论
选择：15
	python基本概念（1）
	超星原题（5）
	数值计算（2）
		算数
		逻辑运算：/浮点除，出来浮点数
		“100”》“90”：字符比较，1跟9先比--False
		“100”《“190”True
		T or 对象=T
		T and 2=2
		False or 2=2
		False and 2= False
		pow，divmod，eval，ord（字符转ascll码），chr（ascll码转字符）int（4.5）=4，round（4.5）=4
	列表，元组（2）1道超星原题
		切片方式
		快速列表？
	字符串（2）
	字典，集合（1）
	控制结构（2）
	函数（3）
	文件（2）