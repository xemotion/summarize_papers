# summarize_papers
### 데이터 수집 
데이터 수집 사이트 
* http://riss.or.kr 
* http://scholar.google.com

데이터 수집에 필요한 라이브러리는 아래와 같고, chrome driver에서 버전이 맞지 않는 등 에러가 나올 경우에는 webdriver manager를 이용하여 제어할 수 있도록 함
아래 라이브러리를 설치해야 함 

```
pip install selenium, lxml, BeautifulSoup4, webdriver-manager

``` 

web-driver가 제어할 수 있도록 추가된 코드 

```
    driver = webdriver.Chrome(ChromeDriverManager().install()) 
    driver.get(URL)
``` 
