---
layout: post
title: "Atom에서 GFM 마크다운 스니펫(snippet) 만들기"
date: 2016-12-21 20:07:30
categories: Markdown
tags: Atom GFM Markdown Snippet 단축키
---
### Atom에서 GFM 마크다운 스니펫(snippet) 만들기
먼저 아톰 실행 후 Ctrl+Shift+P를 눌러서 커맨드 창을 띄운 이후 snippet을 입력하고, Application:Open Your Snippets를 선택하여 `snippets.cson`파일을 연다

![capture1](http://i.imgur.com/BFgKb17.png)

구글에서 [atom snippet]((https://github.com/atom/language-gfm/blob/master/snippets/gfm.cson))으로 검색 결과 나온 github의 cson파일의 내용을 로컬 저장소에 있는 snippets.cson 파일 안에 붙여넣는다.

![capture2](http://i.imgur.com/D3xCmA0.png)

`prefix`는 단축키, `body`는 내용이며 \$1은 내용이 들어갔을 때 커서의 위치를 의미한다.
(개인적으로 아직까지는 \$1만을 사용하고 있는 중)

`snippets.cson`파일이 저장된 직후 markdown 파일 편집 시 해당하는 스니펫이 뜨는 것을 확인할 수 있다. 확인 후 엔터를 치면 해당하는 스니펫이 뜨는 것을 확인할 수 있다.

![capture3](blob:http://imgur.com/00fffe88-4add-4897-9169-2c3b1c2bc84c)
