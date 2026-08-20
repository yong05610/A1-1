 프롬프트 관리 프로그램 - 미션 완료 리포트

## 1. 기본 정보
###  프롬프트관리 프로그램 작성

- python 설처
- VSCODE 설치
- GIT 설치
- 프로프트 관리 프로그램 작성

## 2. 개발 환경
- OS: MS WIN 11
- Python 버전: 3.14.7 
- VSCode 버전: 1.133.0
- Git 버전: 2.55.0

## 3. 구현 기능 목록
| 기능 | 구현 여부 | 비고 |
|------|----------|------|
| 메뉴 시스템 | ✅ | |
| 프롬프트 추가 | ✅ | |
| 목록 보기 | ✅ | |
| 카테고리별 조회 | ✅ | |
| 검색 | ✅ | |
| 상세 보기 | ✅ | |
| 즐겨찾기 | ✅ | |
| 종료 | ✅ | |

## 4. 스크린샷
### 4-1. 개발 환경 설정
   - python 
<img width="1523" height="779" alt="스크린샷 2026-08-16 155258" src="https://github.com/user-attachments/assets/375136d8-64bc-4ef1-a5ac-38e25a3f5f6e" />

   - vscode
   
<img width="1418" height="621" alt="image" src="https://github.com/user-attachments/assets/a3328ef9-4d60-44fd-be1d-9c231eddfc95" />

  - vscode
<img width="1713" height="939" alt="image" src="https://github.com/user-attachments/assets/435c715d-119b-490c-96ac-99bbd80572a4" />
<img width="833" height="599" alt="image" src="https://github.com/user-attachments/assets/3f65269c-e15a-41ec-9de1-deb26f8829cc" />

 
  - Git

<img width="800" height="612" alt="image" src="https://github.com/user-attachments/assets/c7a0c168-e2a9-422c-8d15-43646a303c78" />

  
  - 
### 4-2. 프로그램 실행 화면

<img width="730" height="378" alt="image" src="https://github.com/user-attachments/assets/2ae54bc8-29ba-4f70-b3b0-d57392d91cf6" />

<img width="829" height="347" alt="image" src="https://github.com/user-attachments/assets/a7fe9b1b-7f90-4bf7-b494-81a43a5e5cf6" />

<img width="798" height="497" alt="image" src="https://github.com/user-attachments/assets/c57f0a2c-9389-4448-95b0-499e67d752ff" />




<img width="743" height="124" alt="image" src="https://github.com/user-attachments/assets/5f3d1b30-6828-49ac-86a5-c332923fdffe" />


### 4-3. git log --oneline --graph


## 브랜치 
### 브랜치 만들기

<img width="1141" height="762" alt="image" src="https://github.com/user-attachments/assets/d2ffd17a-61b3-4608-b5dd-452bd8efafee" />

### 브랜치에서 기능추가


### 브랜치 병합 


#### GitHub Pull Request 방식의 merge 선택

*  GitHub에 이런 기록이 남기기 위해서
   - Pull Request 제목
   - 어떤 브랜치에서 왔는지
   - 어떤 커밋이 포함됐는지
   - 언제 병합했는지
   - 병합한 사람

git --no-pager log --oneline --graph --decorate --all

<img width="889" height="194" alt="image" src="https://github.com/user-attachments/assets/2ced05db-1228-40d0-bb4d-2e308fc9e7f2" />

 
## 5. Git 커밋 내역
- 총 커밋 수:
✅ 커밋 최소 10개 이상
   (기능 단위로 나누기)

<img width="703" height="106" alt="image" src="https://github.com/user-attachments/assets/ba717de2-9d05-4b4a-ab3f-81b31f38aae1" />

   
✅ 커밋 메시지에 변경 의도 설명
✅ 아래 명령어 각 1회 이상 사용:
   - git init
   - git add
   - git commit
   - git push
   - git pull
   - git checkout
   - git clone
   - git merge
✅ 브랜치 생성 + 병합 로컬에서 수행
✅ 이전 미션 프롬프트 최소 3개 기본 데이터 등록



## 6. 어려웠던 점 & 해결 방법
- 문제: 
- 해결: 

## 7. 배운 점

  즐겨찾기 기능은 feature/favorite 브랜치에서 개발한 뒤,
  GitHub Pull Request를 통해 main 브랜치에 병합하였다.
  이를 통해 브랜치 작업과 병합 과정을 연습하였다.
 
  git checkout -b feature/new-function
  git add .
  git commit -m "새 기능 추가"
  git push origin feature/new-function
  
