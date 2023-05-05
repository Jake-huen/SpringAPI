## API 문서


요청 url
키워드를 이용하여
https://blogService/api/keyword=IT통신기기?beginDate=2018-01-01?endDate=2023-05-05

Request Parameters

| name      | type   | description | mandatory | note      |
|-----------|--------|-------------|-----------|-----------|
| keyword   | number | 키워드 검색      | x         | IT통신기기    |
| beginDate | string | 시작 날짜       | x         | YYYY-MM-DD |
| endDate   | string | 종료 날짜       | o         |YYYY-MM-DD |

Response Body
{
    "totCnt": 34,
    "hasMore": true,
    "data": [
        {
            "ranking": 1,
            "beginDate": "2018-01-01",
            "endDate": "2018-01-28",
            "keyword": "IT통신기기"
        },
        {
            "ranking": 2,
            "beginDate": "2018-01-01",
            "endDate": "2018-01-28",
            "keyword": "IT통신기기"
        }
    ]
}