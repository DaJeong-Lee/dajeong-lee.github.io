---
layout: post
title: Vim cheet sheet
date: 2018-03-21
description: 유용한 vim 명령어 모음
tags:
---

# Vim cheat sheet

## 유용한 vim 명령어

 행동 | 명령어
 ---- | ----
 실행취소 | u
 커서 위치에서 다음단어시작까지 복사 | yw
 세로선택 후 편집 | ctrl+shitf+v -> shift+i -> 단어입력 -> esc
 찾아바꾸기 | :%s/찾을단어/바꿀단어/g(문서전체)c(확인하면서 바꾸기)
 위로 검색 | #
 위로 찾기 | ?검색어
 대소문자 무시 찾기| /\c검색어
 대소문자 전환 | ~
 줄번호 이동 | :줄번호
 단어저장(레지스터) |  "알파벳(저장할a~z)y  / 붙여넣기 "알파벳(저장할a~z)p
 단어저장(레지스터) 화인 | :reg
