# 창업넷 API 테스트 - [링크](https://www.data.go.kr/data/15001174/openapi.do)

창업 진흥원 사업공고 목록 조회를 위한 API 테스트  

## 요청 서비스 URL
[http://openapi.kised.or.kr/openapi/service/rest/ContentsService/getAnnouncementList](http://openapi.kised.or.kr/openapi/service/rest/ContentsService/getAnnouncementList)

## 인증키
serviceKey는 Encoding과 Decoding 방식이 있는데 두가지 방식 중에서 호출되는 방식을 선택하여 진행한다.

- ENCODING
  - vEPsfUSBEBqVe2urfoNPkd0X3OYf9Ok%2BCUlKFmXKRta9VFTlaShY0uN0buD8MrmCWSrjJDQXWXniDu63VksEaA%3D%3D
- DECODING
  - vEPsfUSBEBqVe2urfoNPkd0X3OYf9Ok+CUlKFmXKRta9VFTlaShY0uN0buD8MrmCWSrjJDQXWXniDu63VksEaA==


## 확인된 것

curl로 서비스키 `xGMSjzWMa5MtIyn%2FRgVvPV1MV9%2BNVznfh3uBp%2FBB1iEUqT7ewoagM3mbTVzxXl0RPNrnfAGkDdjrJYc39VqhpA%3D%3D`에 대한 응답데이터 확인
```bash
curl -i -G -d serviceKey=xGMSjzWMa5MtIyn%2FRgVvPV1MV9%2BNVznfh3uBp%2FBB1iEUqT7ewoagM3mbTVzxXl0RPNrnfAGkDdjrJYc39VqhpA%3D%3D http://openapi.kised.or.kr/openapi/service/rest/ContentsService/getAnnouncementList
```



