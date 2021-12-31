# TIL

>  Today I Learned

##  CIL

Mac 은 터미널(bash)을 열면 된다

처음 시작시 폴더 경로 설정 체크 중요!

경로 이동 (change directory) : cd 폴더이름 +엔터

파일 모두 보기 : ls -a 

파일 생성 : touch 파일이름.확장자

폴더 생성 : mkdir 폴더이름

삭제 : rm (-rf) 삭제할파일(폴더)명  `사용시 주의 ⚠️ 경로 확인`

화면 정리 : clear

VS code 실행 : code `안될때 참고 사이트 https://smilehugo.tistory.com/entry/code-command-is-not-working-on-mac-how-to-solve `



###  MARKDOWN 연습

`git 허브에 문서 올릴때 쓰는 양식 markdown`

> 인용문은 '>' 꺽쇠를 쓰면 된다. 
>
> 하하하
>
> 그렇구나 !



- 이거는 '-' 하이픈 쓰고 (스페이스바) 누르면 되는데 가끔 안될때가 있어 왜그럴까?
  - 나도 모르겟넴
- 몇 번 째 하위까지 갈까?
  - 왜 안될때도 있는거임.
  - 아 그냥 그대로 글쓰고 엔터 누르니까 되넹
    - 이거는 무슨모양
    - 네모군
      - 그 다음은?!
      - 네모군
        - 쳇
        - 재미없어

``` for i in range(n)
 ``` 박스는 백슬래시 세개! 신택스하이라이트 코드 적어넣을때 씀
```

`아하`

` hi light!이거는 백슬래시로 감싸! `

`` ` ``

이미지는 경로 복사해서 붙여넣기!

 <img src="Untitled.assets/스크린샷 2021-12-30 오후 3.15.26.png" alt="스크린샷 2021-12-30 오후 3.15.26" style="zoom:50%;" />



표는 파이프 세개 '| | |'

|      |      |
| ---- | ---- |
|      |      |

*이탤릭체* (*로 감싸기)

**볼드체** (**로 감싸기)

***이건뭐지***(***로 감싸기)

***기울임이었음***

# ## `MARKDOWN.md` 🤔복습해 볼까요

> 확장자는 .md

- github아이디 후보
  - sollaC
  - hiPPap
  - soloolol

|      |      |
| ---- | ---- |
|      |      |
|      |      |
|      |      |

` 백릿? `

```
박스~~오홍
```



##  Vs code

터미널 : control + `

새폴더 열기 : command + o



## Git 

git init > 시작 경로 주의!

git add : commit 하기 전 대기상태

git commit -m'message' : 업데이트 내용을 알수있는 'message'를 달아서 git에 올림

git config --global user.name 'git아이디 혹은 원하는'

git config --global user.email 'email 주소'

git status : 로컬에서의 git 진행상태 

git log : log 보기

git log --oneline : log 한줄로 보기

git remote add <이름> <주소> :

git push 'user' 'master' : commit 한 파일이 github 'user' 저장소 'master'라는 branch로 업데이트

