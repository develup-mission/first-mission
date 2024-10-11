# 미션 - 온보딩(깃허브 익히기)

## 🤔 이런 분이 풀면 좋아요

`1` 나는 깃허브를 사용해본 경험이 많이 없다.

`2` [미션 진행 가이드 문서](https://github.com/develup-mission/docs/blob/main/mission-guide.md)를 봐도 무슨 소린지 모르겠다.

## 💻 기능 요구 사항

아래 튜토리얼을 잘 따라해봅시다. 🍀

### 깃허브에서 자신의 레파지트리로 이 미션을 `Fork`하기

`1` `Fork` 버튼을 클릭한다.

   ![image](https://github.com/user-attachments/assets/76058f86-a8b5-45e1-bd00-12c93c342634)

`2` 버튼을 누르면 나오는 창에서 `Create fork` 버튼을 누르면 자신의 레파지토리 목록에 동일한 레파지토리가 생성된다.

   ![image](https://github.com/user-attachments/assets/071c9a4d-6b0c-427f-9aad-120773086093)

### 로컬에 레파지토리 `clone`하기

`1` **자신**의 `first-mission` 레파지토리에서 `clone` 버튼을 클릭한다.

   ![image](https://github.com/user-attachments/assets/bc0dec2a-4ede-4232-9b1d-377de3dab122)

`2` web URL 주소를 복사한다.

   ![image](https://github.com/user-attachments/assets/a37267db-c70f-4c60-ab4b-707750c835cd)

`3` 터미널 창에 아래 명령어를 입력하면 로컬에 `first-mission` 폴더가 생성된다.

```bash
git clone {방금 복사한 web URL 주소}
```

![image](https://github.com/user-attachments/assets/8f56a3c9-943a-447d-80e1-534299d97084)

### 미션 풀기 👍

`1` 원하는 IDE에서 `first-mission` 폴더를 연다.
`2` `mission.md` 파일을 생성한다.
`3` `안녕하세요.`를 입력하고 저장한다.

### 깃허브에 `push` 하기

`1` 터미널에 다음과 같은 명령어를 입력해 작업한 파일을 git 스테이지 영역에 추가한다.

   > 현재 디렉토리 위치가 `first-mission`이어야 한다.

```bash
git add .
```

![image](https://github.com/user-attachments/assets/7d463cd8-9e9b-4444-979a-476ba9721bda)

`2` 이제 아래 명령어를 통해 변경 내역을 `commit`한다.

```bash
git commit -m "{커밋 메시지}"
```

![image](https://github.com/user-attachments/assets/ec16bfe1-3679-4818-92a7-5d101773b0f9)

`3` 깃허브 레파지토리에 `push`한다.

```bash
git push
```

### PR 날리기

`1` 깃허브 나의 `first-mission` 레파지토리에서 `Pull requests` 버튼을 클릭한다.

   ![image](https://github.com/user-attachments/assets/b228ec0e-bed0-4843-b382-722af6e2877a)

`2` `New pull request` 버튼을 클릭한다.

   ![image](https://github.com/user-attachments/assets/df9c97f0-e34b-49f1-a44a-961a63cb26e3)

`3` 간단하게 제목을 입력한뒤 `Create pull request` 버튼을 클릭한다.

   ![image](https://github.com/user-attachments/assets/fecd921e-58c1-4ac4-bfba-0fb92501b1ad)
