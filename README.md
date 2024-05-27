# sg_4_ai_project

### [Figma Link](https://www.figma.com/proto/IozltLTK1Skj0A17p89FNC/ai-%EA%B8%88%EC%9C%B5-%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4_%EC%9B%B9%EC%82%AC%EC%9D%B4%ED%8A%B8?node-id=2-2&t=14Dhk2dbmaQ9Pzbg-1&scaling=scale-down-width&page-id=0%3A1)
![image](https://github.com/peggy330/sg_4_ai_project/assets/44740259/8f172e1b-2ed3-46e1-a689-11c2ed27ea9d)

![image](https://github.com/peggy330/sg_4_ai_project/assets/44740259/2f919801-2df7-4ba3-8a93-295847013399)

위 혹은 아래의 링크를 클릭하면 저희가 구축한 사이트 접근할 수 있습니다.

### 파일 설명

폴더 구조
- etf_data
  - AGG_price_data.csv
- macro_economic_indicator
- model1
  - model1.py
  - model_rec_sys.py
  - porfolio_optimization.ipynb
  - porfolio_rec_system.py
- stock info
  - info.json
  - stock_info.xlsx

### 기능 및 구조 간단 설명
- 유저의 투자 유형과 현 시장 상황에 맞는 포트폴리오 추천
  - 투자목적, 투자성향 등의 사전 조사를 통해 성향 분석을 진행하고
  - 이후 시장 상황을 고려한 산업/섹터별 투자 포트폴리오와 기업 추천
- 산업 뉴스, 주가 변동 이벤트에 따른 주가 변동 뉴스로 딥러닝 모델(DL, LSTM 등)을 통한 가격 예측 -> 예측 가격 기반으로 현대 재무 이론들의 포트폴리오 최적화

### 역할 분담
유진(팀장) : 기획, 데이터 수집 (경제지표), 데이터분석, etf 가격 모델링
민석 : 기획, 데이터 수집(etf 가격, 변동성), 데이터분석, etf 가격 모델링
시은 : 기획, 데이터 수집(산업군별 금융상품), UI/UX 구성
예나 : 기획, 데이터 수집(산업군별 금융상품), 데이터 분석
형준 : 기획, 데이터 수집(기업정보, 뉴스 크롤러), 포트폴리오 최적화 모델링
