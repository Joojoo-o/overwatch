# 프로젝트 폴더 생성

> 폴더 명 : overwatch
> 폴더 생성 : 깃허브 - git clone

첫 프로젝트는 overwatch 캐릭터를 고르는 페이지를 제작하는 것이다.
따라서 프로젝트 명은 overwatch로 지었다.

#### 1. 깃허브에서 프로젝트 폴더를 생성해 준 후 컴퓨터에 폴더를 git clone 해준다.

#### 2. 필요한 이미지들을 다운받아 이미지 폴더를 생성 후 프로젝트 폴더 안에 넣어준다.

(폴더: overwatch-images)

# vscode 기본 설정

> 만들어진 폴더의 vscode 열고 필요한 기본 파일 생성

overwatch 폴더를 열고 기본 파일을 생성해준다.

#### 1. index.html

#### 2. main.css

#### 3. images (파일을 미리 옮겨놨으면 생략가능)

> index.html 기본 설정

#### 1. !를 입력하여 기본 설정을 해준다.

#### 2. lang(언어)를 ko(한글)로 바꿔준다.

```
<html lang="ko" />
```

#### 3. 프로젝트 명대로 페이지의 이름을 설정해준다.

title을 overwatch로 설정

```
<title>overwatch</title>
```

#### 4. 브라우저 기본스타일을 초기화 시켜준다.

구글에 ***reset.css cdn***을 검색하여
reset-css CDN by jsDelivr - A CDN for npm and GitHub 페이지에 들어간다.
HTML을 카피하여 복붙한다. (copy HTML)
title 아래에 그대로 ctrl+V하여 붙여넣기 하기

#### 5. css파일 연결해주기

4번(브라우저 초기화) 밑에 css파일을 link해준다.

```
<link rel="stylesheet" href="./main.css" />
```

link 자동완성 탭 누른 후 ./main.css를 link해주면 된다.
**link는 연결해주는 코드
./는 상대경로로 생략가능하다. (작성하는 파일 기준으로 주변 파일의 경로를 찾아준다.)
./는 주변 파일이며 ../는 상위폴더의 경로를 찾는다.
그외 절대경로는 http(https)와 /(//)가 있다.**
