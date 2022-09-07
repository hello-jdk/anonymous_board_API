# 익명 게시판

비밀번호를 사용한 익명게시판 만들기

## 사용자 요구사항

1. 사용자 게시글 올리기

   1. 게시글의 제목은 최대 20자, 본문내용은 최대 200자입니다.
   2. 제목과 본문 모두 이모지가 포함 할 수 있습니다.

2. 패스워드를 통한 게시글 관리

   1. 패스워드를 통한 수정, 삭제 가능
   2. 패스워드는 DB에 암호화되서 저장
   3. 패스워드는 6자 이상, 숫자 1개 이상 반드시 포함

3. 모든 사용자가 한 페이지 내에서 모든 게시글을 확인

   1. 최신 글 순서로 정렬되어있습니다.
   2. 하나의 요청마다 최대 20개의 게시글 목록을 불러옵니다.

## 사용기술

`nodejs` `express.js` `mysql` `sequelize` `swagger`

## ERD

<img width="200" alt="1" src="https://user-images.githubusercontent.com/57665888/188879492-bcfee6f2-eca7-4546-b215-a6773487f59f.png">

## API DOCS

```
localhost:PORT/docs
```
