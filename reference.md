## Reference URL    

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


### geopandas  
https://datascienceschool.net/view-notebook/ef921dc25e01437b9b5c532ba3b89b02/  
-> geopandas 설명자료  
http://geopandas.org/   
-> geopandas 공식 설명자료  
https://stackoverflow.com/questions/38961816/geopandas-set-crs-on-points  
-> geoDataframe의 crs 관련 질문 (스택오버플로우)  
https://gis.stackexchange.com/questions/269243/create-a-polygon-grid-using-with-geopandas  
=> python에서 shp파일 읽어서 polygon에 대한 격자 grid 생성하기  
https://stackoverflow.com/questions/40818679/geopandas-difference-methode-between-polygon-and-points  
=> geopandas로 한 점에 대한 buffer 생성  
https://gis.stackexchange.com/questions/253224/geopandas-buffer-using-geodataframe-while-maintaining-the-dataframe  
=> geopandas buffer 쉬운 예제  
http://geopandas.org/mapping.html  
=> geopandas 공식 사이트  
https://gis.stackexchange.com/questions/301251/geopandas-import-csv-make-polygons-from-x-y-coordinates-based-on-id  
=> 그냥 pandas로 csv 읽어서 mapping을 이용해 geodataframe 생성하기  
https://gis.stackexchange.com/questions/80881/what-is-unit-of-shapely-length-attribute  
=> 두 Point간의 직선거리 계산 (shapely)  
https://stackoverflow.com/questions/11015252/countig-points-in-boxes-of-a-grid  
=> 2차원 그래프에서 grid를 만들고 해당 grid에 포함된 것 카운팅  
https://gis.stackexchange.com/questions/319546/converting-list-of-polygons-to-multipolygon-using-shapely  
=> 여러개의 폴리곤을 멀티폴리곤으로 만들기  
https://gis.stackexchange.com/questions/322589/rasterizing-polygon-grid-in-python-geopandas-rasterio?noredirect=1&lq=1  
=> python에서 grid 폴리곤 만들기  
https://stackoverflow.com/questions/38961816/geopandas-set-crs-on-points  
=> geopandas 좌표 정의 및 프로젝션  
https://gis.stackexchange.com/questions/306674/geopandas-spatial-join-and-count  
http://geopandas.org/reference/geopandas.sjoin.html  
=> geopandas spatial join  
https://www.biz-gis.com/index.php?mid=QnA&document_srl=224858   
=> 좌표계 5174 -> 5179 안맞는 오류  
https://gis.stackexchange.com/questions/299379/superposing-two-plots-with-geopandas-with-non-fill-colours-in-one-of-them  
=> Geodataframe 여러개의 레이어 겹쳐 그리기  
https://gis.stackexchange.com/questions/342512/intersection-tolerance-error-with-shapely   
=> Polygon의 각 변(edge)를 linestring으로 뽑아내기  
https://stackoverflow.com/questions/24415806/coordinates-of-the-closest-points-of-two-geometries-in-shapely   
=> 가장 가까운 거리에 해당하는 좌표점 구하기  
https://stackoverflow.com/questions/39338550/cut-a-polygon-with-two-lines-in-shapely  
=> line으로 polygon 짜르기!!!!!!!!!!  
https://gis.stackexchange.com/questions/277334/shapely-polygon-union-results-in-strange-artifacts-of-tiny-non-overlapping-area?rq=1  
=> shapely로 polygon 결합 (dissolve 하는 방법)  

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


### Algorithm  
https://www.slideshare.net/ssuserd6c109/ss-125788862  
-> 머신러닝과 사이킷런의 이해 : 개념적인 글 (잘 설명이 되어 있음)  
https://nonmeyet.tistory.com/entry/Python-Kmeans-clustering-%EA%B5%AC%ED%98%84  
=> k-means 클러스터링 간단히 구현 방법  
https://datascienceschool.net/view-notebook/2205ad8f0c5947c08696e8927b466341/  
=> k-means 조금 자세한 설명  
https://www.codeit.kr/questions/7823  
https://pinkwink.kr/1127  
=> 추세선 그리기 (날짜가 X일때는 위의 timestamp를 이용해야함)  
https://docs.scipy.org/doc/numpy/reference/generated/numpy.polyfit.html  
=> np.polyfit 함수 : 최소제곱법을 이용한 회귀식(추세선) 
https://stackoverflow.com/questions/893657/how-do-i-calculate-r-squared-using-python-and-numpy  
=> linear_regression 좀더 자세히  
https://datascience.stackexchange.com/questions/24405/how-to-do-stepwise-regression-using-sklearn  
=> Python에서 stepwise regression 사용자 정의함수 만들기  
https://datascienceschool.net/view-notebook/36176e580d124612a376cf29872cd2f0/  
=> 다중공선성과 변수선택 in python  
https://datascienceschool.net/view-notebook/e6c0d4ff9f4c403c8587c7d394bc930a/  
=> scipy를 이용한 확률분포 (CDF, 누적 확률분포함수 찾다가)  
https://datascienceschool.net/view-notebook/4d74d1b5651245a7903583f30ae44608/  
=> 확률밀도함수, 확률분포함수 기초 개념   
https://bcho.tistory.com/1205  
https://untitledtblog.tistory.com/146  
=> DBSCAN (밀도기반 클러스터링)  
https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html  
=> 사이킷런 DBSCAN 설명  
https://m.blog.naver.com/PostView.nhn?blogId=wjddudwo209&logNo=220864977498&proxyReferer=https%3A%2F%2Fwww.google.com%2F  
=> sklearn decision tree 결정경계 뽑아내기  
https://datascienceschool.net/view-notebook/e335aec955e844a981b41e4e11f79174/  
=> DBSCAN 자세한 설명  
https://forensics.tistory.com/19  
=> 시그모이드 함수, 프로빗 함수(CDF, 누적정규분포함수)  
https://m.blog.naver.com/PostView.nhn?blogId=yshmisopia&logNo=60152050508&proxyReferer=https%3A%2F%2Fwww.google.com%2F  
=> Rtree 구조  
https://www.crocus.co.kr/1288  
=> convex hull 알고리즘  
https://m.blog.naver.com/PostView.nhn?blogId=bloodsoda&logNo=221029163536&proxyReferer=https%3A%2F%2Fwww.google.com%2F  
=> convex hull 알고리즘 조금 쉬운 설명  
https://stackoverflow.com/questions/28260962/calculating-angles-between-line-segments-python-with-math-atan2  
=> 두 line 사이의 각도 구하기(math 라이브러리를 이용한, atan, 기울기 활용)  


### 시각화  
https://wikidocs.net/23258  
-> numpy, matplotlib 히스토그램, 구간값 범주형만들기  
https://rfriend.tistory.com/411  
-> 파이썬 막대그래프 모든 것 matplotlib.pyplot 활용 자세하게 다 되어 있음  
https://stackoverflow.com/questions/35072400/how-to-set-a-secondary-y-axis-in-python  
-> y축 두개로 그래프 겹쳐 그리는 방법  
https://stackoverflow.com/questions/14344063/single-legend-for-multiple-axes  
-> y축 두개일때, legend 생성하는 방법  
https://kongdols-room.tistory.com/86  
=> plt.grid()  
https://stackoverflow.com/questions/30228069/how-to-display-the-value-of-the-bar-on-each-bar-with-pyplot-barh  
=> 막대그래프(bar plot)에 text 표시하기  
https://wikidocs.net/4761  
=> subplot 예시  


### 기타  
https://data-flair.training/blogs/pandas-function-applications/  
-> 위 링크에서 발견한 pipe 함수  
http://blog.naver.com/PostView.nhn?blogId=tipsware&logNo=221056424237&categoryNo=50&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=search  
-> sleep함수 (시간을 지연시키져는 함수)  
http://pythonstudy.xyz/python/article/202-MySQL-%EC%BF%BC%EB%A6%AC  
https://ssoonidev.tistory.com/71  
https://myjamong.tistory.com/53  
-> pymysql 모듈, 파이썬 mysql 연동  
https://stackoverflow.com/questions/44166555/python-making-random-combinations-of-values-from-two-lists  
=> random.choice로 임의의 값 뽑기(파라미터 조정시)  
https://wikidocs.net/30  
=> 예외처리  
https://stackoverflow.com/questions/179369/how-do-i-abort-the-execution-of-a-python-script  
=> 스크립트 실행 중단시키기, sys.exit()  
https://hashcode.co.kr/questions/278/%ED%8C%8C%EC%9D%BC-%EC%83%9D%EC%84%B1%EC%9D%BC%EC%9D%B4%EB%9E%91-%EC%88%98%EC%A0%95%EC%9D%BC-%EC%95%8C%EC%95%84%EB%82%B4%EB%8A%94-%EB%B2%95  
=> 파일 생성일 수정일 알아내기 python  
https://python.bakyeono.net/chapter-11-5.html   
=> 웹url 가져오기, json파일 가져오기  
https://pythonhosted.org/planar/polygon.html  
=> 도형 접선 그릴때 유용한(tangent) planar 라이브러리  


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


