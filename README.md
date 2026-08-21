# 프롬프트 관리 프로그램 - 미션 완료 리포트

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

## 4. 개발 환경 설정
### 4-1. python 
  
<img width="1523" height="779" alt="스크린샷 2026-08-16 155258" src="https://github.com/user-attachments/assets/375136d8-64bc-4ef1-a5ac-38e25a3f5f6e" />

### 4-2. VSCODE
   
<img width="1418" height="621" alt="image" src="https://github.com/user-attachments/assets/a3328ef9-4d60-44fd-be1d-9c231eddfc95" />

  
<img width="1713" height="939" alt="image" src="https://github.com/user-attachments/assets/435c715d-119b-490c-96ac-99bbd80572a4" />
<img width="833" height="599" alt="image" src="https://github.com/user-attachments/assets/3f65269c-e15a-41ec-9de1-deb26f8829cc" />

 
### 4-3. Git

<img width="800" height="612" alt="image" src="https://github.com/user-attachments/assets/c7a0c168-e2a9-422c-8d15-43646a303c78" />

  
  - 
## 5. 프로그램 개발

<img width="477" height="361" alt="image" src="https://github.com/user-attachments/assets/8cee7897-7807-4798-80cb-50bcc31c082c" />

 
# 📌 프롬프트 관리 프로그램 기능설명서

### 프로그램 개요
프롬프트를 추가·조회·검색·수정·삭제하고, 즐겨찾기로 관리할 수 있는 콘솔 기반 프로그램입니다.
모든 데이터는 파일에 저장되어 프로그램을 종료해도 유지됩니다.

### 📌 프롬프트 관리 프로그램 기능설명서


### 📋 메뉴별 기능 요약

| 기능 | 내용 |
|------|------|
| **1. 프롬프트 추가** | 제목, 내용, 카테고리를 입력받아 새 프롬프트를 등록하고 파일에 저장 |
| **2. 프롬프트 목록 보기** | 저장된 전체 프롬프트를 번호순으로 출력 |
| **3. 카테고리별 보기** | 특정 카테고리에 속한 프롬프트만 골라서 출력 |
| **4. 프롬프트 검색** | 제목이나 내용에 검색어가 포함된 프롬프트를 찾아서 출력 |
| **5. 프롬프트 상세보기** | 특정 프롬프트의 제목·내용·카테고리 등 전체 정보를 자세히 표시 |
| **6. 프롬프트 삭제** | 선택한 프롬프트를 목록에서 제거하고 파일에 반영 |
| **7. 즐겨찾기 추가/해제** | 선택한 프롬프트의 즐겨찾기 상태를 켜거나 끔 (토글) |
| **8. 즐겨찾기 목록** | 즐겨찾기(★)로 지정된 프롬프트만 모아서 출력 |
| **0. 종료** | 프로그램을 안전하게 종료 |

---

### 🔧 내부 보조 기능 (사용자 메뉴에는 없지만 동작을 지원)

| 기능 | 내용 |
|------|------|
| **load_prompts()** | 저장된 파일에서 프롬프트 데이터를 불러옴 (프로그램 시작 시 실행) |
| **save_prompts()** | 프롬프트 데이터를 파일에 저장 (추가·삭제·수정 시 자동 호출) |
| **ensure_favorite_field()** | 모든 프롬프트에 `favorite` 필드가 없으면 기본값(False)으로 채워 데이터 안정성 보장 |
| **main()** | 메뉴를 반복 출력하고 사용자 입력에 따라 각 기능을 연결하는 메인 루프 |

---

### 💾 데이터 저장 방식
- 각 프롬프트는 다음 정보를 가집니다.

| 항목 | 설명 |
|------|------|
| **id** | 프롬프트 고유 번호 |
| **title** | 프롬프트 제목 |
| **content** | 프롬프트 내용 |
| **category** | 분류 카테고리 |
| **favorite** | 즐겨찾기 여부 (True / False) |
| **created_at** | 생성 날짜·시간 |

### 📋프로그램 실행화면

<img width="730" height="378" alt="image" src="https://github.com/user-attachments/assets/2ae54bc8-29ba-4f70-b3b0-d57392d91cf6" />

<img width="829" height="347" alt="image" src="https://github.com/user-attachments/assets/a7fe9b1b-7f90-4bf7-b494-81a43a5e5cf6" />

<img width="798" height="497" alt="image" src="https://github.com/user-attachments/assets/c57f0a2c-9389-4448-95b0-499e67d752ff" />




<img width="743" height="124" alt="image" src="https://github.com/user-attachments/assets/5f3d1b30-6828-49ac-86a5-c332923fdffe" />

✅ 이전 미션 프롬프트 최소 3개 기본 데이터 등록



## 6. 브랜치 
### 6.1 브랜치 만들기

<img width="1141" height="762" alt="image" src="https://github.com/user-attachments/assets/d2ffd17a-61b3-4608-b5dd-452bd8efafee" />

### 6.2브랜치에서 기능추가

 ✅  브랜치에서 새로운 기능 추가   
 
#### 즐겨찾기 추가/해제 및 즐겨찾기 목록

### 6.3 브랜치 병합 

#### GitHub Pull Request 방식의 merge 선택

*  GitHub에 이런 기록이 남기기 위해서
   - Pull Request 제목
   - 어떤 브랜치에서 왔는지
   - 어떤 커밋이 포함됐는지
   - 언제 병합했는지
   - 병합한 사람

## 7 Git 커밋 내역 

- 총 커밋 수:
✅ 커밋 최소 10개 이상
   (기능 단위로 나누기)

  #### git log --oneline --graph

- git --no-pager log --oneline --graph --decorate --all

<img width="889" height="194" alt="image" src="https://github.com/user-attachments/assets/2ced05db-1228-40d0-bb4d-2e308fc9e7f2" />
 


✅ 아래 명령어 각 1회 이상 사용:
   - git init
   - git add
   - git commit
   - git push
   - git pull
   - git checkout
   - git clone
   - git merge


## 8. 어려웠던 점 & 해결 방법

- 문제: 학습네이토에서 claude sonnet 을 사용해서 미션을 기억시키고 미션의 순서대로 네이토의 도움말을 보며 도움에 따라 진행 하다 200턴이 넘게 되면부터는 미션을 거의 기억을 못하게 되어 엉뚱한 방향으로 진행이되어 미션을 아무리 다시 보여주어도 5턴을 넘기지 못하고 미션을 망각하는 현상이 벌어여 그 이후부터 다른 스레드로 프로프트를 일일이 작성해서 진행하게 되어 진행이 늦어지게 되었음 

- 해결: 해결을 하지 못하였으나 앞으로는 퍼실리테이터님의 힌트에 따라 처음부터 미션을 파악하게 하고 그것에 대한 분할하여 질문할 수 있는 프롬프트를 준비하게 해서 다른 쓰레드와 공둥운영을 통해 기억소멸을 피하려고  합니다. 

## 9. 배운 점

  즐겨찾기 기능은 feature/favorite 브랜치에서 개발한 뒤,
  GitHub Pull Request를 통해 main 브랜치에 병합하였다.
  이를 통해 브랜치 작업과 병합 과정을 연습하였다.
 
  git checkout -b feature/new-function
  git add .
  git commit -m "새 기능 추가"
  git push origin feature/new-function
  
