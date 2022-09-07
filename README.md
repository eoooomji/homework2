## 두번째 강의 TIL
---
### 주요 내용
1. ctrl + (`)빽 키 : 뉴 터미널 생성
2. README.md
    >GitHub에 올린 레퍼지터리에서 먼저 보여주는 문서   
    >이걸 봄으로써 어떠한 형식인지 미리 알 수 있음.
3. md
    >md는 markdown의 줄임말(확장자의 한 종류)
4. .gitignore
    > GitHub에 올리지 않아도 될 환경설정 같은 파일을 만들 때 사용   
    > 레퍼지터리에서 제외 할 파일을 입력하면 올라가지 않음
    - 파일.*(별표) : 같은 파일명의 모든 확장자를 포함할 때
    - *(별표).확장자 : 같은 확장자의 모든 파일을 포함할 때
    - (폴더명)/ : 폴더를 제외시킬 때
5. git restore --staged (file)
    > add한 파일 중 stage에서 제외시킬 때
6. git commit --amend
    > 바로 직전 commit한 상태의 파일을 stage로 돌려 편집이 가능하게 만들어 주는 기능.   
    > 추가로 파일을 더 넣어줄 수 있다.(add한 상태의 파일이 stage에 있다면)
7. GitHub 파일 주고 받기(협업)
    > 생성된 레퍼지터리 > settings > collaborators > add people 이름 입력 > GitHub 연동된 메일 동의 > 코드 복사 > 사용
---

README.md 사용 단축어 및 키
   (공백 3개) : 줄바꿈
# : 제목 (총 6개까지)
--- : 수평선
> : 인용문
1. : 순서가 있는 목록
    - : 순서가 없는 목록   
(tab키 누르면 들여쓰기, shift + tab 다시 원래대로)

```java () ``` : 자바 프로그램   
```html () ``` : html 프로그램•••   
|---|---|---| : 표 만들기   
|:---:| : 가운데 정렬 / |---:| : 오른쪽 정렬 / |:---| : 왼쪽 정렬   
_기울기_ : 이텔릭체, 기울인 글씨체   
**굵기** __굵기__ : 굵은 글씨체   
***굵기+기울기*** : 굵기 +기울기 글씨체   
~~취소선~~ : 가운데 취소선   
**~~굵기+취소~~** : 굵기+취소선   
'<이미지>' : 이미지 표시   
![picture](pic/git-cheat-sheet.png) : 이미지 불러오기   
