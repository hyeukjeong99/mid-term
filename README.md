# mid-term
#3주차

strVal = 'data science'               # 문자열 변수

nVal = 12345                          # 정수형 변수

fVal = 1.2                            # 실수형 변수

lVal = ['data', 'science']            # 리스트

dVal = {'lecture' : 'data science'}   # 딕셔너리

bVal = True                           # 논리형 변수(참/거짓)


''' 
이런 형태의 주석도 많이 사용
'''


strVal

nVal

fVal

lVal

dVal

bVal

print('strVal : ', strVal)

print('nVal : ', nVal)

print('fVal : ', fVal)

print('lVal : ', lVal)

print('dVal : ', dVal)

print('bVal : ', bVal)

print('strVal : ', type(strVal))

print('nVal : ', type(nVal))

print('fVal : ', type(fVal))

print('lVal : ', type(lVal))

print('dVal : ', type(dVal))

print('bVal : ', type(bVal))



nVal = 16                          # 정수형 변수

fVal = 3.14                        # 실수형 변수

print('10진수 표현 : ', nVal)       # 10진수

print('2진수 표현 : ', bin(nVal))  # 2진수

print('8진수 표현 : ', oct(nVal))  # 8진수

print('16진수 표현 : ', hex(nVal))  # 16진수



btVal = True                           # 논리형 변수(참)

bfVal = False                          # 논리형 변수(거짓)

btVal = TRUE                          # 논리형 변수(참) - 오류

bfVal = FALSE                          # 논리형 변수(거짓) - 오류

btVal = true                          # 논리형 변수(참) - 오류

bfVal = false                          # 논리형 변수(거짓) - 오류

10 == 11

10 != 11

10 >= 11

10 <= 11

10 > 11

10 < 11

nBig = 100

nSmall = 10

print(nBig == nSmall)

print(nBig != nSmall)

print(nBig >= nSmall)

print(nBig <= nSmall)

print(nBig > nSmall)

print(nBig < nSmall)

print(nBig =< nSmall)     # 오류

print(nBig => nSmall)     # 오류



strData = 'data'               # 문자열 변수

strSci = "Science"             # 문자열 변수

strLecture = strData + strSci

strLecture

strLecture = strData +" "+ strSci

strLecture

strLecture.split()              # split()으로 공백을 기준으로 문자열 구분

lSeperate = strLecture.split() # split()으로 공백을 기준으로 문자열 구분아혀 lSeperate 변수에 저장

type(lSeperate)

strHello = "안녕하세요. 반갑습니다."

strHello.find("반갑")       # 문자열을 찾기 위해 find() 함수를 이용



strHello.find("hello")    # 문자열이 없으면, -1을 리턴

"반갑" in strHello          # in 명령어를 사용하여 확인 가능 : if 조건문에서 활용

strHello.replace('.', '?')    # .을 모두 ?로 변경

strHello.replace('.', '?')                  

strHello.replace("하세요", "하셔유")       # 안녕하셔유? 가 될까요?

strHello                      # 원본 데이터는 변하지 않음

strNewHello = strHello.replace('.', '?')                    # strHello를 replace하여 strNewHello에 저장   

strNewHello = strNewHello.replace("하세요", "하셔유")       # strNewHello를 replace하여 strNewHello에 저장

strNewHello

strHello.strip('반갑습니다.')    # strip()함수를 이용하여 "반갑습니다."를 제거

strHello                    # 역시 원본 데이터는 변하지 않음



lnData = [1,2,3,4,5]     # lnData를 리스트로 생성



print(lnData)

print('type : ', type(lnData))

print(lnData[0])    # lnData 리스트의 0번 인덱스의 값 출력

print(lnData[3])    # lnData 리스트의 3번 인덱스의 값 출력

lnData[0] = lnData[4]   # lnData[4]의 값을 lnData[0]에 저장

print(lnData)           # lnData 리스트를 출력

print(lnData[2:4])      # lnData[4]에 저장된 5는 출력되지 않음

lnData = [1,2,3,4,5]

lstrData=['a', 'b', 'c']



lnData + lstrData

lnData.append(10)   # 10을 맨 뒤에 추가

lnData

lnData.insert(0, 'python')  #'python'문자열을 0번 인덱스에 추가하고, 기존 인덱스에 저장된 데이터는 하나씩 뒤로 밀림(인덱스가 +1 추가)

lnData

lnData.remove('python')     # 'python' 데이터를 삭제

lnData

del lnData[5]              # del 명령어를 통해 인덱스를 지정하여 삭제

lnData

lnData

lnData.pop(0)     # 0번 인덱스의 데이터를 삭제

lnData

lnData.pop()     # 인덱스 지정이 없으면, 마지막 인덱스의 값을 삭제

lnData

lnData.clear()  # 리스트의 모든 데이터를 삭제

lnData



tVal = ("사과", "딸기", "바나나", "토마토", "키위")

print(tVal)

print(type(tVal))

tVal[0] = "포도"



tData = ( 1, 2, 3, 1, 2, 3, 4, 5, 1, 2, 7)

tData.count(1)

len(tVal)

len(tData)

print(tData[2:5])

tTuple = tVal+ tData

print(tTuple)

tData * 2

tData

tData2 = tData * 2

print(tData2)

print("tVal memory = ", hex(id(tVal)))

tVal = tVal * 2

print("tVal memory = ", hex(id(tVal)))

print(tVal)

print("tVal memory = ", hex(id(tVal)))

tVal = tVal + tVal

print("tVal memory = ", hex(id(tVal)))

print(tVal)



sVal = {1, 2, 3, 4, 5}

print(sVal)

print(type(sVal))

sVal[1:2]



sVal.add(100)

print(sVal)

sVal.update([200, 300])

print(sVal)

sVal.remove(200)

print(sVal)

sVal.clear()

print(sVal)



sVal = {100, 200, 300, 400, 500}

sData = {"a", "b", "c", "c", 100, 300}

print(sVal)

print(sData)

sVal.intersection(sData)

sVal.difference(sData)

sVal - sData

sVal.union(sData)

sVal + sData


sVal.symmetric_difference(sData)



dVal = {

'name' : '이컴공',

'email' : 'computer@hoseo.edu',

'address' : '충남 아산시'

}

print(dVal)

print(type(dVal))



dData = {

"사과" : 300, 

"포도" : 200, 

"배" : 500,

"키위" : 100

}
print(dData["배"])

dData.get("배")

dData["딸기"] = 100

print(dData)

dData.pop("사과")

dData

dData.pop()

sorted(dData)

sorted(dData.values())

dData



def f(x):

return x + 10

f(2)



#4주차



strText = input("아무 문장이나 입력하세요 : ")

print(strText)

flVal = [1.0, 2.0, 3.14, 4.2, 5.1]  

arVal = [flVal, flVal, flVal]

arVal

arVal[0]

arVal[1]

arVal[1][2]

arVal[0] = 'python'

arVal

arVal[0][2]

arVal[0] = 'python programming'

arVal



import numpy as np

arData = np.array([1.0, 2.0, 3.14, 4.2, 5.1])

arData

arData.sum()

arVal.sum()

print(type(arVal))

print(type(arData))

arData.std()

arData.cumsum()

arData * 2

arData ** 2

np.sqrt(arData)

arVal = np.array([arData, arData ** 2])

arVal

arVal.sum(axis=0)

arVal.sum(axis=1)

np.array([[0,0,0],[0,0,0]])

arZero = np.zeros((2,3), dtype = 'i') 

arZero



import pandas as pd



pandas_series = pd.Series([30, 20, 10], index=['국어', '영어', '수학'])

print(type(pandas_series))

pandas_series

pandas_series[1:]

pandas_series[0]

pandas_series[0][1]



df = pd.DataFrame([30,20,10], columns=['score'], index=['국어', '영어', '수학'])

df

df.index

df.columns

df.loc['국어'] 

df.sum()

df.score ** 2

df['score2'] = (50, 50, 50)

df

df['score2'] = pd.DataFrame([90,90,90], index=['국어', '영어', '수학'])

df

del df['score']

df['score2'] = (90, 90, 90, 100)

df['score2'] = pd.DataFrame([90, 90, 90, 100], index=['국어', '영어', '수학', '윤리'])

df

df1 = pd.DataFrame([1, 2, 3], columns = ['A'])

df2 = pd.DataFrame([10, 11, 12, 13], columns = ['B'])

df = df1.join(df2, how='outer')

df

df_inner = df1.join(df2, how='inner')

df_inner

df = pd.DataFrame(np.random.randn(5,5))

df.columns = ['A', 'B', 'C', 'D', 'E']

df

df.max()

df.min()

df.mean()

df.std()

df.cumsum()

df.describe()

df['division'] = ['X', 'Y', 'X', 'Y', 'Z']

df

df.groupby(['division']).mean()



#5주차



import pandas as pd



sr = pd.Series([100, 200, 300, 400])

sr.index = ['A', 'B', 'O', 'AB']

sr

sr1 = pd.Series([10, 20, 30])

sr1

df = pd.DataFrame({'키':[170, 180, 175], '몸무게':[65, 78, 70]})

df.index = ['스파이더맨', '닥터스트레인지', '아이언맨']

df

df = pd.read_csv('scores.csv', encoding='cp949')

df

df.head()

df.tail()

df.sample(3)

df.info()

df.shape

len(df)

df.isnull().sum()

df_dropna = df.dropna()

df_dropna

df_fillna = df.fillna(50)


df_fillna



df.describe()

df['국어'].sum()

df.value_counts('영어')

df['국어']

df[['국어', '영어']]



df.loc[1]

df.loc[[1,2,3]]



df.iloc[2]

df.iloc[2:5]

df.loc[2:5]

df

df.iloc[1,3]

df.iloc[1:3, 1:3]



#6주차



!sudo apt-get install -y fonts-nanum

!sudo fc-cache -fv

!rm ~/.cache/matplotlib -rf

import matplotlib as mpl

import matplotlib.pyplot as plt

import numpy as np



%matplotlib inline

plt.rc('font', family='NanumBarunGothic')

plt.rc('axes', unicode_minus = False)

x = ['1월', '2월', '3월', '4월', '5월']

y = [7, 10, 17, 20, 23]

plt.plot(x,y)

plt.show()

x = ['1월', '2월', '3월', '4월', '5월']

y = [7, 10, 17, 20, 23]

plt.plot(x,y, color="blue", marker = 'o', linestyle = ':')

plt.title('월별 평균 온도', fontsize=15)

plt.ylabel('온도(도)')

plt.grid(linestyle = ':')

plt.show()

aVal = np.random.standard_normal(40)

aVal

type(aVal)

index = range(len(aVal))

plt.plot(index, aVal)

plt.xlim(0, 20)

plt.ylim(np.min(aVal) -1, np.max(aVal) + 1)

plt.show()

type(index)

plt.figure(figsize=(7,4))

plt.plot(aVal.cumsum(), 'b', lw= 1.5)

plt.plot(aVal.cumsum(), 'ro')

plt.xlabel('index')

plt.ylabel('aVal')

plt.title('Line Plot')

plt.show()

value = np.random.standard_normal((30, 2))

value

value[0]

plt.figure(figsize=(10,4))

plt.plot(value[:,0], lw= 1.5)

plt.plot(value[:,1], lw= 1.5)

plt.plot(value, 'ro')

plt.grid(True)

plt.xlabel('index')

plt.ylabel('value')

plt.title('Line Plot')

plt.figure(figsize=(10,5))

plt.subplot(211)


plt.plot(value[:,0], lw = 1.5, label = '1st')

plt.plot(value[:,0], 'ro')

plt.grid(True)

plt.legend(loc = 0)

plt.ylabel("value")

plt.title('Line Plot 3')

plt.subplot(212)

plt.plot(value[:,1], 'g', lw = 1.5, label = '2nd')

plt.grid(True)

plt.legend(loc=0)

plt.axis('tight')

plt.ylabel('value')

plt.figure(figsize=(13,5))

plt.subplot(231)

plt.plot(value[:,0], lw= 1.5, label = '1st')

plt.plot(value[:,0], 'co')

plt.grid(True)

plt.legend(loc=0)

plt.ylabel('value')

plt.title('Line Plot 3')

plt.subplot(232)

plt.plot(value[:,0], 'g-.', lw=1.5, label='1st')

plt.grid(True)

plt.legend(loc=0)

plt.axis('tight')

plt.ylabel('value')'


plt.subplot(233)

plt.plot(value[:,0], 'g', lw=1.5, label='1st')

plt.plot(value[:,0], 'bD')

plt.grid(True)

plt.legend(loc=0)

plt.axis('tight')

plt.ylabel('value')

plt.subplot(234)

plt.plot(value[:,1], '*', lw=1.5, label='2nd')

plt.grid(True)

plt.legend(loc=0)

plt.axis('tight')

plt.ylabel('value')

plt.subplot(235)

plt.plot(value[:,1], 'b', lw=1.5, label='2nd')

plt.plot(value[:,1], 'ms')

plt.grid(True)

plt.legend(loc=0)

plt.axis('tight')

plt.ylabel('value')

plt.subplot(236)

plt.plot(value[:,1], 'r--', lw=1.5, label='2nd')

plt.grid(True)

plt.legend(loc=0)

plt.axis('tight')

plt.ylabel('value')



x = ['1월', '2월', '3월', '4월', '5월']

y = [7, 10, 17, 20, 23]

plt.bar(x,y)

plt.show()

x = ['1월', '2월', '3월', '4월', '5월']

y = [7, 10, 17, 20, 23]

plt.barh(x,y)

plt.show()

x = ['1월', '2월', '3월', '4월', '5월']

y = [7, 10, 17, 20, 23]

plt.bar(x,y, color="orange", width = 0.5, edgecolor = 'black', hatch = '/')

plt.title('월별 평균 온도', fontsize=15)

plt.ylabel('온도(도)')

plt.grid(linestyle = ':', axis = 'y')

plt.show()

import pandas as pd


df = pd.read_csv('scores.csv', encoding='cp949')

df

x = df['이름']

y_kor = df['국어']



plt.bar(x, y_kor)

plt.show()


x = df['이름']

y_kor = df['국어']

y_eng = df['영어']

plt.bar(x, y_kor, width = -0.4, align = 'edge', label = '국어')

plt.bar(x, y_eng, width = 0.4, align = 'edge', label = '영어')

plt.title('국어/영어 점수 비교', fontsize = 15)

plt.ylabel('점수')

plt.legend() 

plt.show()

value = np.random.standard_normal((500,2))

plt.plot(value[:,0], value[:,1], 'ro')

plt.grid(False)

plt.xlabel('value 1')

plt.ylabel('value 2')

plt.title('Scatter Plot 1')

plt.figure(figsize=(7,5))

plt.scatter(value[:,0], value[:,1], marker='o')

plt.grid(True)

plt.xlabel('value 1')

plt.ylabel('value 2')

plt.title('Scatter Plot 2')

color = np.random.randint(0,10,len(value))



plt.figure(figsize=(10,5))

plt.scatter(value[:,0], value[:,1], c=color, marker = 'o')

plt.colorbar()

plt.xlabel('value 1')

plt.ylabel('value 2')

plt.title('Scatter Plot 3')



import seaborn as sns


df = sns.load_dataset('tips')

df

df.head()

df.describe()

df.info()

x = df['total_bill']

y = df['tip']



sns.scatterplot(x,y)

sns.boxplot(x="day", y = "tip", hue="sex", data=df, palette="muted")



#7주차



import seaborn as sns

import matplotlib.pyplot as plt

import pandas as pd




%matplotlib inline    



iris = sns.load_dataset('iris')

iris

iris.groupby('species').size()

iris.describe()

type(iris)

sns.pairplot(iris)

plt.title("Iris Data Analysis")

sns.pairplot(iris, hue="species", diag_kind='kde')

sns.boxplot(x='species', y="petal_length", data=iris)

sns.boxplot(x='species', y="petal_width", data=iris)

iris.boxplot(by="species", figsize=(16,8))
