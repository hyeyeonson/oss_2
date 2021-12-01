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
- Add quotes to ansible playbook
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
  
  https://user-images.githubusercontent.com/76990397/144243987-ba54d416-2c3f-48db-a63d-654bcefe074c.mp4


  
