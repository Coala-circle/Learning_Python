# 기본 문법

파이썬에서 사용되는 기본적인 문법들을 공부해 봅시다



## 입력 출력

	Print()	//출력

	input(“하고싶은 말”) //입력
	
```python 
print(“안녕”)	
A = input(“하고싶은 말”) 
```



##	변수형

	int //정수형	
	
	float //유리수형 
	
	str(string) //문자열형

```python 
Ex) A = int(input(“하고싶은 말”)) 
```



##	기초문법

	a+=1 //변수 A의 값에 1 더하기

	a-=1 // 변수 A의 값에 1 빼기
	
```python 
X > Y
X < Y
X == Y
X <= Y
X >= Y
X != Y
```	



##	조건 반복절

	if(): //조건절, 괄호 안의 수가 0보다 크거나 연산이 참이면 주어진 명령을 수행함
	
	else: //앞선 if문이 거짓일때 명령을 수행함
	
	elif(): //if문이 거짓, 괄호 안의 수가 1이상  연산이 참이면 명령을 수행함
	
```python 
if(A<0):
  print(A)
elif(A=0):
  print("A=0")
else:
  print("양수")
```



	while 조건: //반복문, 괄호 안의 수가 0보다 크거나 연산이 참이면 명령을 반복
	            꼭 반복문 내에 조건을 거짓으로 만들 수 있는 명령을 넣어줘야함

```python 
while A<5:
  print(A)
```	
			 


	for 변수 in 리스트 //리스트 대신 주로 range() 사용. 변수가 리스트 안에 속한다면 
	명령 반복 증가량이 주어지지 않았을 경우 한번 시행할 때마다 변수+=1을 수행한다. 
	    
	range(처음 값, 끝 값, 증가량(생략가능)) //처음 값과 끝 값이 주어진 리스트, 
	      for문에서는 for문 내부에서 시행되는 값 증가의 계수를 정해줄 수 있다.

```python
for A in range(3, 5):
  print(A)
```
