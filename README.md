# **오픈소스SW개발론**

### Introduction

-------------
### Week1-1 강의 개요 (강의계획서)
* 교과목명: 오픈소스소프트웨어
* 담당교수: 최광훈
* 인공지능학부 2학년 전공 교과목으로, 아래와 같은 내용을 이해하고 이에 대한 능력을 함양할 수 있도록 함을 해당 수업의 목표로 한다.
  1. 오픈소스 소프트웨어 개발을 위한 기본 개념과 도구, 특히 소스 코드 버전 컨트롤과 패키지 관리, 프로그램 빌드
  2. 애자일 기반 소프트웨어 개발 방법인 짝프로그래밍, 테스트 주도 개발, 행위 주도 개발, 클라우드 기반 데브옵스
  3. 새로운/낯선 소프트웨어 개발 환경 및 도구를 스스로 배우는 태도
* 수업방식: 플립러닝 방식
* 수업의 주요 내용
  * 오픈소스소프트웨어 개요
  * _Git_
  * _Github_, _fork_, _pull request_
  * _Markdown_
  * _Haskell_

-------------
### Week1-2 오픈소스소프트웨어 개요
* Open Source Software(OSS)의 최신 트렌드와 분석을 [GitHub Octoverse'](https://github.blog/news-insights/research/the-state-of-open-source-and-ai/)에서 살펴본다.
![github Octoverse](https://github.blog/wp-content/uploads/2023/11/github-octoverse-hero-image-2023.png?w=1600)
* **Open Source Software**: 소프트웨어 저작권 소유자가 모든 사람에게 소스코드를 게시 사용 복사 수정 및 배포할 권리를 부여한 소프트웨어
* **OSS License**: 오픈소스 소프트웨어애 대한 권한의 범위를 지정
* OSS는 상용화 관점에서 **Commercial SW**와 **Open Source SW**로 나눌 수 있다.
* OSS는 철학적 관점에서 **Free Software**와 **Open Source Software**로 나눌 수 있다. 
* 수많은 Open Source Software License 중 몇 가지에 대해서 알아봤다.
   * _GPL2.0_
   * _LGPL_
   * _MIT_
   * _BSD_
   * _Apache 2.0_
   * _MPL1.0/1.1_

-------------
### Week2-1 버전 관리 개요
* 버전관리의 필요성
  * Make a single copy
  * Add a version number or date
  * Use a shared folder so other people can see and edit files together
* Version Control System(VCS): Track your files over time so you can easily get back to a previous working version
  * VCS software의 종류
    * CVS(Concurrent Version System)
    * SVN(Subversion)
    * Mercurial
    * Darcs
    * Git
  * Repository or Repo(저장소)
  * General Actions in VCS
    * Checkin
    * Checkout and editing
    * Diffs
    * Branching
    * Merging
    * Conflicts
    * Tagging
  * VCS는 주로 Centralized VCS와 Decentralized(Distributed) VCS
    * Git은 Decentralized(Distributed) VCS에 해당한다.

-------------
### Week2-2 Git
* Linus Torvalds: For collaboration of development of Linux kernel
* A distributed version control system
  * Workspace
  * Index
  * Local repository
  * Remote repository
 
* Workflow(git에서 사용하는 명령어)
![workflow of Git](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNDA2MDhfMjYg%2FMDAxNzE3ODQzNzAwNDIy.V6hIcccYpr5ZuY0MwdAAZKU4boF6IRM1sNgc6mnWwmEg.2i90U6w8FTrrvrmcdA3ag1LlKUK6KfyPFys9U26Ld6Yg.PNG%2Fimage.png&type=sc960_832)

-------------
### Week2-3 Github, fork, pull request  
Github 명령어 연습  
#### Basic  
> 실습 전 설정
> Stage 1: 초기화 및 첫 commit 하기  
> Stage 2: diff 사용과 추가 commit 하기  
> Stage 3: commit 에 본인서명 포함하기    
> Stage 4: 지금까지의 commit을 push하자  
> Stage 5: 커밋 수정하기  
> Stage 6: add 한거 취소하기  
> Stage 7: commit 한거 없애기  
> Github에서 fork하기

#### Advanced  
> Stage 8: pull-request 하기  
> Stage 9: merge로 2개 브랜치 합치기  
> Stage 10: rebase 하기  
> Stage 11: 중간에 낀 commit 수정하기  
> Bonus Stage: blame으로 추적하기

#### [Come to My Github Blog](https://github.com/kkanuseobin)

-------------
### Week3     Markdown
* _Italics and Bold_
* _Headers_
* _Links_
* _Images_
* _Blockquotes_
* _Lists_
* _Paragraphs_
