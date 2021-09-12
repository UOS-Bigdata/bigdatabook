# 데이터프레임


컴퓨터를 이용해서 자료를 처리하고 분석할 때 가장 많이 사용하는 형식은 MS EXCEL 의 스프레드 시트와 유사한 `dataframe` 형식이다.

`dataframe` 형식은 아래와 같은 특징을 가지고 있다.


- 행(row, 로우)은 전체 자료에서 하나의 구성 요소(entry, recored, unit)에 대한 데이터들로 이루어 진다.
- 열(column, 컬럼)로  전체 자료에서 하나의 특성을 나타내는 데이터로 이루어 진다. 열은 같은 형식의 자료들로서 구성된다. 
- 각 행과 열은 이를 지칭하는 **인덱스(index)** 을 가지고 있으며 인덱스는 숫자 또는 문자로 정의된다. 
  + 열을 나타내는 문자로 된 인덱스는 보통 **열이름(column name)** 이라고 부른다.


![dataframe](https://pandas.pydata.org/docs/_images/01_table_dataframe.svg)

데이터프레임은 `pandas` 라이브러리를 통해서 사용할 수 있다. 데이터프레임을 사용하는 경우 초기에 다음과 같이 `pandas` 라이브러리를 불러 주어야 한다.

```
import pandas as pd
```

`pandas` 라이브러리의 `dataframe`에 대한 기초적인 내용은 `pandas` 홈페이지의 
[데이터프레임 시작하기](https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html) 에 있으니 참고하자. 