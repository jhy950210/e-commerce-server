## 프로젝트

## Getting Started

### Prerequisites

#### Running Docker Containers

`local` profile 로 실행하기 위하여 인프라가 설정되어 있는 Docker 컨테이너를 실행해주셔야 합니다.

```bash
docker-compose up -d
```

### 시퀀스 다이어그램
1. 잔액 조회
![Image](https://github.com/user-attachments/assets/753fc787-f7a4-4782-8aad-c8b53b088b83)
2. 잔액 충전
![Image](https://github.com/user-attachments/assets/3b8ede32-07b3-4e75-8ed2-595b7662b2bc)
3. 상품 조회
![Image](https://github.com/user-attachments/assets/897b1e55-cfaf-4d69-ab3e-41d906c929f8)
4. 쿠폰 발행
![Image](https://github.com/user-attachments/assets/9615a37a-a7a3-46fa-b117-df8a7e4b4ba9)
5. 보유 쿠폰 리스트 조회
![Image](https://github.com/user-attachments/assets/3d21d119-3148-4ce6-9c01-e9bd4a1be175)
6. 주문 생성
![Image](https://github.com/user-attachments/assets/f4a9c545-b1ba-4e3b-9fa1-1cf7229a9dda)
7. 결제 생성
![Image](https://github.com/user-attachments/assets/b8a10926-ed59-4c69-a248-c0570891a547)

### ERD
1. 유저-잔액
![Image](https://github.com/user-attachments/assets/ee9f9f68-60d4-48c8-bd45-af431cd9ff77)
2. 상품-옵션
![Image](https://github.com/user-attachments/assets/d697022d-81b1-4350-b854-da68782db570)
3. 유저-쿠폰
![Image](https://github.com/user-attachments/assets/c1d02915-a283-41b8-ba72-c2c9e2823ded)
4. 주문
![Image](https://github.com/user-attachments/assets/29357d89-a61a-45c4-b3f4-2d3e9f50a36b)
5. 결제
![Image](https://github.com/user-attachments/assets/74e4ad36-c4dd-4180-9969-5158319e1a4f)