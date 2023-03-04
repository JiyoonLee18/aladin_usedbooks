# aladin_usedbooks
저는 개인사정으로 인해 주기적으로 알라딘 중고매장에서 특정 책들을 구매하고 있습니다.  
해당 책들을 효율적으로 구입하기 위해서, 구매 이력이 있는 책들 재고가 가장 많은 스토어를 찾는 크롤링 코드를 만들었습니다.  

## Process  
### 1단계: 주문번호 및 주문상세url 수집
- 20개 정도로 많지 않음에 따라 LISTLY 활용함
![image](https://user-images.githubusercontent.com/98992915/222896938-49a1a101-76ac-4981-a778-5f16a678e72f.png)  

### 2단계: 주문상세url 에서 책 제목, 책 페이지url 수집
![image](https://user-images.githubusercontent.com/98992915/222897010-26142bab-9032-4217-8302-a5c9d9e9fdad.png)
![image](https://user-images.githubusercontent.com/98992915/222897028-04c7d997-489a-4f4c-b62a-d7074ebec9a7.png)  

### 3단계: 책 페이지에서 [중고모두보기]버튼 속에 있는 책재고 url 수집
![image](https://user-images.githubusercontent.com/98992915/222897061-6c9d067d-8ccc-4e11-a7a0-1f69254eec62.png)  

### 4단계: 책재고 url페이지에서 책 상태, 판매자, 가격 등의 정보 수집
![image](https://user-images.githubusercontent.com/98992915/222897107-780c6fa3-2174-4f7f-a9bb-7f5101ae048d.png)
![image](https://user-images.githubusercontent.com/98992915/222897134-b56f8d58-3137-4d9c-8de5-1f136c3ccc16.png)
