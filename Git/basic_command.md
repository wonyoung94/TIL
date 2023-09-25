# basic command
> Git 기본 명령어 정리

## 초기 설정
- Git을 설치 후 한번만 실행
```bash
git config --global user.email <이메일>
git config --global user.name <이름>
```

## Git 저장소 만들기 

- `git init`
    - `.git directory`를 생성해주는 명령어
    - 관리하고 싶은 최상위 위치에서 실행

## Git 상태 체크

- `status`
    - 현재 git 으로 관리되고 있는 파일/폴더의 상태를 출력

## 코드 수정하고 저장소에 저장하기

- `add`