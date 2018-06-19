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
* Big Data를 사용
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
> * USPTO 데이터 2018년 1-3월, 3개월간 생성된 특허 데이터
> * 총 000건의 데이터 (데이터 크기)
>
>
### 1.2. 데이터 수집
>
> * 병렬구조로 데이터를 수집
>
>
## 2. 데이터 변환 및 저장
>
### 2.1. 데이터 변환 : XML -> JSON
>
> * Splunk와 Neo4j는 xml과 json 두 형식으로 모두 사용 가능하지만 MongoDB에서 JSON과 같은 형식(BSON으로 부름)으로 사용
> * 따라서, XML을 JSON형식으로 변환하여 세 시스템 모두 사용가능하도록 만들었음
>
### 2.2. 데이터 저장 
>
> * a sample record () for each system (image)
>
## 3. 데이터수집 결과 요약
>
> 

