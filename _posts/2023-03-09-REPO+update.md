---
title: "[Linux Server] '/etc/yum.repos.d' 파일 수정 "
date: '2023-03-09'
categories: linuxserver
toc: true
toc_sticky: true
sidebar:
  nav: docs
---

## /etc/yum.repos.d 內 파일 수정

`/etc/yum.repos.d` 하위에 있는 `.repo` 파일 수정 후에는

 `yum clean all`


 `yum update`

반드시 이 명령을 쳐야 제대로 `.repo`파일 수정한 것이 적용되고 `yum`이 제대로 돌아간다!

### `yum clean all`
 - 캐시되어 있는 yum의 헤더, 다운로드한 패키지 목록, 메타데이터를 지워버린다!!
 - 결론적으로 기존 저장소 목록 제거시켜버린다!
### `yum update`
 - `yum clean all`뒤에 `yum update`실행하면 수정한 `.repo` 파일 기반으로 새로 패키지 목록 다운을 받는다
 - `yum update 패키지명`인데 여기서 패키지명 지정하지 않으면 업데이트 가능한 모든 패키지를 업데이트한다!






