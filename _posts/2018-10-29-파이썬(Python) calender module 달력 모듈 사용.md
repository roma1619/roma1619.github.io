

```python
#calender 모듈 사용하기 

import calendar as cal 

print(" 달력 확인 ") 

year = int(input(" 태어난 년도 : ")) 
month = int(input(" 태어난 월 : ")) 
print(cal.month(year, month))
### 실행 화면  

달력 확인  
 태어난 년도 : 2000 
 태어난 월 : 6 
     June 2000 
Mo Tu We Th Fr Sa Su 
          1  2  3  4 
 5  6  7  8  9 10 11 
12 13 14 15 16 17 18 
19 20 21 22 23 24 25 
26 27 28 29 30
#요일 확인 


print(" 요일 확인 ") 
year = int(input(" 년도 : ")) 
month = int(input(" 월 : ")) 
day = int(input(" 일 : ")) 
week = ["월", "화", "수", "목", "금", "토", "일"] 
q = cal.weekday(year, month, day) 

print(week[q], "요일")
### 실행 화면  

 요일 확인  
 년도 : 2018 
 월 : 6 
 일 : 20 
수 요일 
>>> 

```
