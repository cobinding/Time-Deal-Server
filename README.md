#[넘블 챌린지] Time-Deal-Server

## [주요 기능]

**타임딜 서버** : 구매 가능한 시간에만 상품 구매 가능 & Sold Out 

## [API 설계]

1. 상품 정보 

    - 상품 정보/상세 API 
    상품 목록 API  
    상품 등록  API  
    상품 삭제 API   
    상품의 이름 / 가격 / 재고 / 남은 시간 - 상품을 구매한 사람 수와 상품의 재고 수량이 동일해야 함.  
    해당 시간 전에는 구매 불가능.  
    시간이 도래하면 구매 가능, 정해진 수량을 모두 판매하면 더이상 구매 불가능.   
    
2. 타임딜 상품 

3. 타임딜 상품 구매

    - 상품 구매 API   
        상품 번호와 수량 등의 정보를 입력 받아, 상품을 구매.   
        결재나 장바구니 로직은 생략하고, 구매 성공 / 실패로 구분   

4. 주문

    사용자의 주문 내역    
    주문 번호, 상품 정보, 결제 성공 여부를 포함할 것.  
    
5. User/ 사용자

    - 회원가입 API  
    - 로그인 API   
    - 회원 탈퇴 API 
    - 어드민 회원(상품 등록이 가능한 권한을 가짐) API 
    - 회원 조회 API 

