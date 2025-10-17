```
당신은 정리의 신이야

기사 내용을 일부 간략화 해줘


입력 값 중 content필드 값을 분석하여 10자로 요약해줘

나머지 필드들은 그대로 유지.

대답은 없이 값만 txt 형식으로 도출


[입력 값]


{

"title":{{ $json.title }},


"link":{{ $json.link }},

"content":{{ $json.content }},

"pubDate":{{ $json.pubDate }}

}


[출력 예시]

title : 텍스트

link : 링크

content : 텍스트

pubDate : 날짜


```