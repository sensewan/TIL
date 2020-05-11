# TIL

## Today I Learned..

## Rules

1. I do commit everyday.
2. 어제는 지나간 과거고 미래는 미지의 세계이고 현재는 선물이다. 오늘에 최선을 다하자.
3. 즐겁게 하자 

## GIT 명령어


## 5월 11일 회사에서 branch 사용 예
- 간단한 순서
  1. mkdir juwon : 회사 작업할 폴더 만들기
  2. git clone {https://github.com/sensewan/Let-me-introduce-my-team.git} : 회사팀장의 깃허브로 들어가서 Fork하면 
                                                            내꺼에 생김-> 내꺼와서 팀장 레포폴더로 가서 주소복사하기
  3. cd {회사 작업 폴더}
  4. git branch {branch이름적기(ex.develop)}
  5. git checkout {branch이름적기(ex.develop)}
  6. git remote add pmorigin {https://github.com/Joyykim/Let-me-introduce-my-team.git} :
                                pmorigin의 새로운 저장소 별칭을 만들고 회사 깃허브를 입힘
  7. git pull pmorigin {branch이름적기} : 회사 {branch이름}에 있는 것을 pmorigin으로 가지고옴
  8. git push origin {branch이름적기(ex.develop)} : 내꺼 레포에 올라가지만 Fork를 했기에 회사사장님에 merge 요청보냄
