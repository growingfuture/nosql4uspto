# NOSQL 4 USPTO
uspto patent data-pipeline for nosql system
--------------------------------------------
>
>
![image](https://www.commerce.gov/sites/commerce.gov/files/styles/scale_700w/public/media/images/branding/uspto_seal_full_color.jpg?itok=0CpME9vD)
>
>
## 프로젝트에서 중점사항
>
* 매년 150,000건 이상의 데이터를 issue하는 USPTO 빅데이터 활용
* 병렬구조로 수집하여 수집 속도를 향상시킴
* 
*
>
>
## 목차
>
1. 데이터 소개 및 수집 
2. 데이터 변환 및 저장 
3. 데이터 수집 결과 요약
>
>
## 1. 데이터 소개 및 수집
>
### 1.1. 데이터 소개
>
```
* USPTO 데이터 2018년 1-3월, 3개월간 생성된 특허 데이터
* 총 000건의 데이터 (데이터 크기)
```
>
>
### 1.2. 데이터 수집
>
```
1) 파일 수집 URL 생성
* USPTO에 2002년 이후에 생성된 데이터들은 xml 파일형식으로 가져올 수 있음
* 따라서, USPTO의 url에서 년도만(2002이후) 바꾸어 xml파일을 수집하는 형식으로 파이썬 문법 작성
* 본 프로젝트에서는 실험적으로 2018년 1-3월까지의 3개월 데이터만 가져옴
```
>
![image](https://user-images.githubusercontent.com/37169177/41616343-bcfe824e-7438-11e8-9a6a-ae6b8a9d5655.png)
>
```
2) zip을 풀어 xml 형태로 최종 수집
* USPTO에 올려져 있는 파일들은 zip 형태으로 되어 있음
* 따라서, zip을 풀어 xml 형태로 최종 수집

```
>
>
## 2. 데이터 변환 및 저장
>
### 2.1. 데이터 변환 : XML -> JSON
>
```
* Splunk와 Neo4j는 xml과 json 두 형식 모두 사용 가능하지만 MongoDB에서 JSON과 같은 형식(BSON)만 사용 가능
* 따라서, XML을 JSON형식으로 변환하여 세 시스템 모두 사용 가능하게 만들었음
* 변환방법
 * 몰라요아직~
```
>
>
### 2.2. 데이터 저장 
>
> * a sample record () for each system (image)
>
## 3. 데이터수집 결과 요약
>
> 

