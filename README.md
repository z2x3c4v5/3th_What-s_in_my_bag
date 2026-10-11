# What's in my bag?

초등학교 3학년 영어 수업용 웹 앱 초안입니다. `index.html` 하나로 동작하며, 브라우저에서 바로 열면 됩니다.

## 표현
- Do you have a(n) ____?
- Yes, I do. I have a(n) ____.
- No, I don't. I don't have a(n) ____.

## 탭 1. 단어 배우기
- 학용품 단어 카드 18개 (교과서 단어 pen, glue stick, ruler, eraser, notebook, crayon 포함)
- 카드를 누르면 영어 발음을 들려주고, 위의 문장 패턴에 단어가 들어갑니다. a / an 표시
- 듣고 고르기: 소리를 듣고 맞는 카드를 고르는 미니 퀴즈

## 탭 2. 가방 싸기
- 물건을 누르거나 끌어서 백팩에 넣기. 넣으면 "I have a pen." 을 말해 줍니다
- 가방 안의 물건을 누르면 꺼내기 ("I don't have a pen.")
- 친구가 물어봐요: "Do you have a(n) ___?" 질문에 가방을 보고 Yes, I do. / No, I don't. 로 대답하는 퀴즈

음성은 브라우저 내장 TTS(Web Speech API)를 사용합니다. Chrome, Edge, Safari에서 동작합니다.
