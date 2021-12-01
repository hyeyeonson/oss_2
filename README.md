# oss_2 project
### VimGolf 
---

**[설명]**
- 특정 문제를 최소한의 타수로 편집하는 사이트
- 타이핑하는 Keystroke를 최소한으로 맞춰라!
- <http://vimgolf.com>


**[설치방법]**
- apt update
- apt install python
- apt install python3-pip
- pip intsall vimgolf


**[문제 리스트 표시]**
- vimgolf list
- 하지만, 사이트들어가면 더 많은 문제 리스트 볼 수 있다.


**[특정 문제 참가방법]**
- vimgolf put [problem hashID]

---

  
### *Q1*
- Problme : Add quotes to ansible playbook
  - vimgolf put 5f0f5fbe280fbf000c233304
  - 최고점 : 8
- Solution
  - G W i " <End> " <Esc> ZZ
    - G : 파일의 마지막 행으로 가기
    - W : 오른쪽 한 단어의 끝 부분으로 커서 이동
    - i : insert mode
    - " : " 입력
    - <end> : 맨 마지막으로 이동
    - " : " 입력
    - <ESC> : 종료
    - ZZ : 변경사항 보관 후 vi 종료
- 풀이 영상
  
![ezgif com-gif-maker](https://user-images.githubusercontent.com/76990397/144246623-cc92f83c-cf47-42dc-9769-1657991420a8.gif)

---
  
### *Q2*
- Problem : simple replacements
  - vimgolf put 603ba26a01b4d00009c10a49
  - 최고점 : 19
- Solution
  - <F12> :%s/sublime\|emacs/vim/g <CR>ZZ
    - <f12> : 녹화 시작
    - :%s/sublime\|emacs/vim/g : sublime과 emacs를 vim으로 바꾼다
    - ZZ : 변경사항 보관 후 vi 종료
- 풀이 영상
  
  ![ezgif com-gif-maker](https://user-images.githubusercontent.com/76990397/144246731-7c53f699-6f03-444b-941b-99aa80ac4741.gif)

---
### *Q3*
- Problem : Satisfy the go linter
  - vimgolf put 5f1063aa8361810006e73210
  - 최고점 : 20
- Solution
  - 4G yw O // <Esc> p a TODO <Esc> 6G yw O // <Esc> p a TODO <Esc> ZZ
    - 4G : 4번째 줄로 이동
    - yw : 커서가 위치한 word 복사
    - O : 커서 위에 행 삽입
    - p : yank 되거나 삭제된 행 현재 행 위로 삽입
    - a : 커서 오른쪽에 문자 삽입
  
 - 풀이 영상
  
  ![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/76990397/144251480-329aad3c-e248-4f43-bddd-d01f06ac3cf9.gif)

