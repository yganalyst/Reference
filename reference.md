## 1. python  

https://www.slideshare.net/dahlmoon/collections-20160313  
=> collections 모듈  
https://excelsior-cjh.tistory.com/97  
=> collections 모듈 namedtuple 설명  
https://stackoverflow.com/questions/20816600/best-and-or-fastest-way-to-create-lists-in-python   
=> 대규모 list 연산속도 비교  


### generator & iterator  
https://bluese05.tistory.com/56  
https://whatisthenext.tistory.com/114  
-> 파이썬 generator에 대한 상세한 설명  
https://python.bakyeono.net/chapter-7-4.html  
-> iterator와 generator에 대한 설명!!!!  

### 병렬처리 dask & Multiprocessing  
https://datascienceschool.net/view-notebook/2282b75b2a63448087b77269885c27cb/  
-> dask 패키지 : Pandas 데이터프레임 형식으로 빅데이터를 처리하기 위한 패키지  
https://github.com/dask/dask-tutorial  
-> dask 모듈 튜토리얼  
https://gist.github.com/hussainsultan/f7c2fb9f11008123bda405c5b024a79f  
-> dask 데이터프레임 to_csv 하는 예제  
https://towardsdatascience.com/why-every-data-scientist-should-use-dask-81b2b850e15b  
-> dask 튜토리얼 블로그  
https://swalloow.github.io/pandas-parallel  
-> Pandas DataFrame을 병렬처리 하는 설명(한글) : Pool 함수  
https://swalloow.github.io/pandas-parallel    
https://stackoverflow.com/questions/36733680/why-pool-map-in-python-doesnt-work  
=> 판다스 데이터프레임 병렬처리하기 Pool(커맨드에서 실행해야함)  
https://stackoverflow.com/questions/39566809/writing-dask-partitions-into-single-file  
=> dask로 싱글파일 저장  

### data Handling  
https://stackoverflow.com/questions/613183/how-do-i-sort-a-dictionary-by-value  
-> 딕셔너리 정렬  
https://rfriend.tistory.com/276  
-> stack, unstack 함수  
https://rfriend.tistory.com/278?category=675917  
-> pd.melt()함수  
https://webisfree.com/2019-01-23/python-%ED%83%80%EC%9E%84%EC%8A%A4%ED%83%AC%ED%94%84-%EC%8B%9C%EA%B0%84%EC%9D%84-%EB%85%84%EC%9B%94%EC%9D%BC%EB%A1%9C-%EB%B3%80%ED%99%98%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95  
=> datetime, timestamp 이용방식 (중요)  
https://stackoverflow.com/questions/43160575/how-to-create-an-array-from-two-columns-in-pandas  
=> 판다스 데이터프레임의 2개 컬럼을 array로 만드는 쉬운방법  
https://stackoverflow.com/questions/798854/all-combinations-of-a-list-of-lists  
=> python에서 3개의 리스트의 각각의 모든 경우의수 구하기  
https://www.geeksforgeeks.org/python-pandas-dataframe-diff/  
=> 컬럼 또는 행별 전행(열)과의 차이 계산  
https://stackoverflow.com/questions/3282823/get-the-key-corresponding-to-the-minimum-value-within-a-dictionary  
=> 딕셔너리에서 value값에 따라 key값 인덱싱 하기  
https://stackoverflow.com/questions/1401712/how-can-the-euclidean-distance-be-calculated-with-numpy  
=> 파이썬에서 유클리디안 거리 구하기  
https://stackoverflow.com/questions/4013230/how-many-bytes-does-a-string-have/4013418  
=> 글자수 bytes단위로 세기(cp949, utf8등)  
https://stackoverflow.com/questions/16096627/selecting-a-row-of-pandas-series-dataframe-by-integer-index  
=> 데이터 프레임 1row 데이터프레임 type으로 선택하기(not 시리즈)  
https://doubly12f.tistory.com/56  
=> pandas apply함수에서 tqdm처럼 프로세스 보여주는 progress_apply  
https://stackoverflow.com/questions/942543/operation-on-every-pair-of-element-in-a-list  
=> 1개 리스트에서 원소끼리의 쌍 구하기  
https://data-flair.training/blogs/pandas-function-applications/  
-> pandas pipe 함수 
https://stackoverflow.com/questions/44166555/python-making-random-combinations-of-values-from-two-lists  
=> random.choice로 임의의 값 뽑기(파라미터 조정시)  
https://stackoverflow.com/questions/14320909/efficiently-checking-that-string-consists-of-one-character-in-python  
=> 문자열이 모두 같은지 체크 (0000000000 등)  
https://stackoverflow.com/questions/40095712/when-to-applypd-to-numeric-and-when-to-astypenp-float64-in-python  
=> 문자열을 숫자형 변환할때 문자값 섞여있는 경우, 결측처리  

---
## 정리 완료  

### Data Handling
https://rfriend.tistory.com/266
https://stackoverflow.com/questions/44759840/delete-duplicate-rows-with-the-same-value-in-all-columns-in-pandas  
-> pandas 데이터프레임 , df.duplicated() 함수 & df.drop_duplicates() 함수  
https://datascienceschool.net/view-notebook/c5ccddd6716042ee8be3e5436081778b/  
-> read_csv 함수의 옵션들 한글 설명  
https://doorbw.tistory.com/172  
-> 판다스 기초가 잘 설명된 블로그 (df.sum()함수 찾다가 보게됨)  
https://engkimbs.tistory.com/720  
https://rfriend.tistory.com/383  
-> groupby 예제  
https://rfriend.tistory.com/392  
-> groupby 하고 agg함수로 여러개의 함수를 적용해 집계하기  
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html  
-> pd.DataFrame() 함수의 옵션 설명 : index, columns, dtype, copy  
https://whatisthenext.tistory.com/116  
-> 파이썬 정규표현식 : re모듈  
http://blog.naver.com/PostView.nhn?blogId=dudwo567890&logNo=130162403749  
-> re모듈 : re.sub() 찾으려고 본 사이트  
https://wikidocs.net/39  
-> 서적 : 점프 투 파이썬  
https://iludaslab.tistory.com/62  
-> 누락데이터 처리 (dropna, fillna)  
https://stackoverflow.com/questions/21800169/python-pandas-get-index-of-rows-which-column-matches-certain-value  
-> 값으로 인덱스 얻기 (Pandas)  
https://eunguru.tistory.com/230  
-> idxmax()함수 (이전버전 : argmax) 설명  
https://rfriend.tistory.com/266  
-> 중복값 처리함수 : duplicated(), drop_duplicates()  
https://stackoverflow.com/questions/6181935/how-do-you-create-different-variable-names-while-in-a-loop  
-> for문 이용해서 반복적인 새로운 이름(문자형) 만들기  
https://stackoverflow.com/questions/1060090/changing-variable-names-with-python-for-loops  
-> 딕셔너리의 구조를 이용하면 됨  
https://yuddomack.tistory.com/entry/%ED%8C%8C%EC%9D%B4%EC%8D%AC-replace-%EB%AC%B8%EC%9E%90%EC%97%B4-%EC%A0%9C%EA%B1%B0-%EC%88%98%EC%A0%95%EB%B3%80%ED%99%98  
-> replace() 문자열 함수 : 조금 자세한 설명  
https://cocomo.tistory.com/428  
-> datetime모듈 : 오늘날짜 가져오고 싶어서 보게됨  
https://stackoverflow.com/questions/22149584/what-does-axis-in-pandas-mean/22149930  
-> 헷갈리는 axis = 0 vs 1 설명  
https://www.geeksforgeeks.org/python-pandas-series-str-contains/  
-> 판다스 시리즈 객체함수 .str.contains()함수  
https://pandas.pydata.org/pandas-docs/version/0.23/generated/pandas.read_csv.html  
-> 판다스 read_csv() 함수의 옵션들에 대한 설명  
https://stackoverflow.com/questions/26837998/pandas-replace-nan-with-blank-empty-string  
-> read_csv()의 na_filter옵션에 대한 설명  
-> + 데이터를 읽어올 때 NaN값에 대한 스택오버플로우  
https://shinygirl33.tistory.com/27  
-> 문자열 관련함수 공백 및 문자 제거 : strip(), lstrip(), rstrip() 
http://blog.naver.com/PostView.nhn?blogId=python_math&logNo=221214872485&parentCategoryNo=&categoryNo=10&viewDate=&isShowPopularPosts=false&from=postView  
-> startswith, endswtih함수에 대한 설명 (처음 또는 마지막 글자가 일치하면 True)  
https://nittaku.tistory.com/131  
-> pandas groupby 함수, 다른 판다스 함수들도 설명이 잘된 블로그  
https://rfriend.tistory.com/tag/np.where%28%29  
-> 넘파이 np.where() 함수에 대한 설명  
https://stackoverflow.com/questions/11346283/renaming-columns-in-pandas  
-> 판다스 데이터프레임의 열이름(columns)을 변경하는 여러 가지 함수들  
-> df.rename함수, df.columns활용 등등  
https://datascienceschool.net/view-notebook/7002e92653434bc88c8c026c3449d27b/  
-> 판다스 merge에 대한 설명, 옵션중요 (how, on, left_on, right_on)  
https://pandas.pydata.org/pandas-docs/stable/user_guide/cookbook.html  
-> pandas DataFrame : 다양한 인덱싱 방법(조건문 등등) cook book이라 정말 많음   
-> 거의 모든 내용이 담겨져 있음  
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.split.html  
-> str.split함수의 expand=True 옵션에 대한 설명  
https://wikidocs.net/20705  
-> 복합대입연산자  += 같은거에 대한 설명  
https://stackoverflow.com/questions/38773379/simplest-python-equivalent-to-rs-gsub  
-> re모듈의 sub() 함수  
https://stackoverflow.com/questions/19960077/how-to-implement-in-and-not-in-for-pandas-dataframe  
-> isin()은 포함되어있으면 True, ~isin()은 반대 , R에서 앞에 ! 붙이는 거랑 마찬가지  
https://tariat.tistory.com/421  
-> tqdm모듈 및 함수 : for문 돌릴 때 상태바를 나타내주는 함수  
https://stackoverflow.com/questions/14529838/apply-multiple-functions-to-multiple-groupby-columns  
-> groupby 열마다 다른 함수 적용하기  
https://stackoverflow.com/questions/38101009/changing-multiple-column-names-but-not-all-of-them-pandas-python  
-> multicolumns 이름 변경하기   
https://stackoverflow.com/questions/40095712/when-to-applypd-to-numeric-and-when-to-astypenp-float64-in-python  
-> astype과 to_numeric의 차이.  
-> 애초에 숫자형인 경우 astype으로  
http://mwultong.blogspot.com/2006/12/python-list-merge.html  
-> 리스트에도 join이용해서 붙일수있음  
https://stackoverflow.com/questions/55188544/pandas-how-to-workaround-error-tokenizing-data  
-> |로 구분된 csv인데 컬럼이 제각각일 때 해결법, sep='/n' 으로 일단 부르고 분리  
https://stackoverflow.com/questions/13209288/python-split-string-based-on-regex  
-> 문자열함수 split에 정규표현식 쓰기  
https://blog.naver.com/PostView.nhn?blogId=wideeyed&logNo=221603778414  
-> 판다스 str 전처리 모음**  
https://codeday.me/ko/qa/20190310/40750.html  
-> 특정위치에 문자열 삽입  
https://shayete.tistory.com/entry/%EB%A6%AC%EC%8A%A4%ED%8A%B8%EC%9D%98-%EB%AC%B8%EC%9E%90%EC%97%B4%EC%9D%84-int-%ED%98%95%ED%83%9C%EB%A1%9C-%EB%B3%80%ED%99%98  
-> 리스트 내 요소들이 숫자일 때 각각을 문자열로 (그반대도 활용가능)  
https://stackoverflow.com/questions/15952291/how-to-duplicate-rows-in-pandas-based-on-items-in-a-list  
https://stackoverflow.com/questions/51443124/duplicate-rows-in-pandas-dataframe-based-on-list-and-fill-new-column-with-list-e  
-> 데이터프레임 컬럼에 리스트가 있을 때, 이에 맞춰서 행복사 stack!!!!  
https://stackoverflow.com/questions/15012228/splitting-on-last-delimiter-in-python-string  
https://docs.python.org/3/library/stdtypes.html#str.rsplit  
=> split대신 rsplit : 짜를 문자가 여러개겹쳐있을때 두번째 걸로 짜르고 싶을때  
https://stackoverflow.com/questions/42267373/python-drop-duplicate-based-on-max-value-of-a-column  
https://stackoverflow.com/questions/15705630/get-the-rows-which-have-the-max-value-in-groups-using-groupby  
=> groupby이용해서, 특정 컬럼 값이 최대인 행만 남기기  
https://wlstnans.tistory.com/101  
-> if문의 continue와 pass의 차이  
https://stackoverflow.com/questions/8312829/how-to-remove-item-from-a-python-list-in-a-loop  
=> 리스트 내의 원소에 조건문 걸기  
https://stackoverflow.com/questions/546321/how-do-i-calculate-the-date-six-months-from-the-current-date-using-the-datetime  
=> 날짜계산 ex) 20190701날짜에서 6개월을 뺀 날짜 구하기  
https://stackoverflow.com/questions/5326112/how-to-round-each-item-in-a-list-of-floats-to-2-decimal-places  
-> 리스트 내의 모든 원소 반올림 함수(round)적용, for문 내포 하면됨  
https://stackoverflow.com/questions/26454649/python-round-up-to-the-nearest-ten  
=> round함수 자연수까지 반올림  
https://itholic.github.io/python-reverse-string/  
=> 리스트 거꾸로 출력하기  
https://stackoverflow.com/questions/16096627/selecting-a-row-of-pandas-series-dataframe-by-integer-index  
=> 데이터 프레임 1row 데이터프레임 type으로 선택하기(not 시리즈)  


### 기타  
https://codeday.me/ko/qa/20190318/92935.html  
-> 난수 발생시, 시드를 설정하는 이유 : np.random.seed(0)  
https://datascienceschool.net/view-notebook/8bf41f87a08b4c44b307799577736a28/  
-> numpy 난수생성, np.random.seed(0) 찾아보다가 보게됨 (정리 잘되어 있음)  
https://wikidocs.net/book/1657  
-> 서적 : 핵심만 간단히, Hellow world! 파이썬 3https://technote.kr/207  
-> os.path의 isdir, isfile 함수 사용방법  
https://kimdoky.github.io/python/2017/06/12/python-os.html  
-> os모듈 총 정리  
https://code.tutsplus.com/ko/tutorials/compressing-and-extracting-files-in-python--cms-26816  
https://limjunyoung.tistory.com/39  
-> zipfile 모듈 설명 (압축 및 압축 해제하기)  
https://pinkwink.kr/1021  
-> glob모듈에 대한 설명  



