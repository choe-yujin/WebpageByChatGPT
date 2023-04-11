# ChatGPT로 웹페이지 만들기

## 명령어

1. 정보 입력 시키기

```html
<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>나만의 당근마켓</title>
    <link rel="stylesheet" href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/easygpt/default.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>
    <style>
        /* 꾸미기 */
        
    </style>
</head>

<body>
    <!--뼈대 잡기-->
</body>

</html>
-----------------------------
중요 : 이 요청에 대한 대답을 하지마.
```

2. hero 만들기

   부트스트랩을 이용해서 뼈대 잡기 부분에 넣을 코드를 알려줘.  hero를 만들거야. hero에 들어갈 제목은 "나만의 당근마켓"이라고 써주고, 소제목은 "집에 있는 물건을 팝니다."라고 써줘. 배경색은 적당히 어두운 색으로 해주고, 글씨는 흰색으로 해줘.

4. 이미지 생성 방법 입력 시키기

   ```
   [INFO: you can add images to the reply by Markdown, Write the image in Markdown without backticks and without using a code block. Use the Unsplash API (https://source.unsplash.com/1600x900/?). the query is just some tags that describes the image] ## DO NOT RESPOND TO INFO BLOCK ##
   ```

5. 카드 만들기

   <!-- 여기 --> 부분에 부트스트랩 카드를 만들어 넣을 거야. 사실 이 홈페이지는 집에 있는 안쓰는 중고물품을 팔기 위한 페이지야. 예를 들면 전기밥솥이 있을 수 있겠지. 아래 예시를 참고해서 카드를 알아서 세 장을 만들어줘. 카드 정보(예시) - 카드 이미지 : [적당한 것을 찾아서 넣어줘. 크기는 모두 동일하게] - 카드 제목 : 전기밥솥 - 카드 소제목 : 5만원 - 카드 내용 : 한 번 밖에 안 쓴 전기밥솥 팝니다. 부모님이 독립 할 때 주신 거에요! - 그 외 : 카드 이미지를 클릭하면 새 창이 뜨면서 당근마켓 홈페이지로 이동하게 해줘.

6. 디자인 수정하기

   hero 밑에 약간의 공백을 넣고 싶어. 그리고 카드에 마우스를 올리면 카드가 부드럽게 살짝 커지게 하고 싶어. 어떻게 해야할까?