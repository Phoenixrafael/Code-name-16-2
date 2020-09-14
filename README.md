16진수와 2진수를 이용한 암호다. 다음은 작동 원리이다.

1. 5X5 크기의 표를 준비한다.
_ _ _ _ _
_ _ _ _ _
_ _ _ _ _
_ _ _ _ _
_ _ _ _ _

2. 원하는 그림을 그린다
# _ _ _ #
_ # _ # _
_ _ # _ _
_ # _ # _
# _ _ _ #

3. 일자로 펴준다.
# _ _ _ # _ # _ # _ _ _ # _ _ _ # _ # _ # _ _ _ #

4. 빈칸은 0, 채운 칸은 1로 대체한다.
1 0 0 0 1 0 1 0 1 0 0 0 1 0 0 0 1 0 1 0 1 0 0 0 1

5. 맨 앞에 1을 붙인다.
1 1 0 0 0 1 0 1 0 1 0 0 0 1 0 0 0 1 0 1 0 1 0 0 0 1

6. 2진수를 16진수로 바꾼다.
11000101010001000101010001 = 3151151

7. 완성
3151151 <- 이게 한 문자다.

다음과 같이 단어나 문장도 만들 수 있다.
_ # # # #   _ # # # _   # # # # #
# _ _ _ _   # _ _ _ #   _ _ # _ _
# _ _ _ _   # # # # #   _ _ # _ _ = 2F8420F 2E8FE31 3F21084
# _ _ _ _   # _ _ _ #   _ _ # _ _
_ # # # #   # _ _ _ #   _ _ # _ _

이 암호를 해독하는 프로그램이 '암호해독기'다. 글자 사이에는 띄어쓰기를 해주길 바란다. 예)2F8420F(띄고)2E8FE31(띄고)3F21084
하지만 이 암호를 일일이 만들기엔 너무 오래 걸려서 만든 프로그램이 '암호만들기'다. 문자마다 암호 하나하나를 지정해 놓고 입력한 문자열과 일일이 바꿔준다.
