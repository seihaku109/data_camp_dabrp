
# RStudio에 사용하기 좋은 기능 소개 {#rstudio}

첫 수업은 RStudio를, 정확하게는 IDE에서 받을 수 있는 기능적 혜택들을 소개하려고 합니다.

## RStudio 소개 {#introduce-rstudio}

### IDE 란 {#ide}

IDE란 _통합 개발 환경_의 영어 줄임말로 텍스트 편집이외에도 디버깅, 컴파일, 배포등 개발의 위한 기능을 통합적으로 제공하는 프로그램을 지칭합니다. R 또한 개발언어의 일종으로 여러 IDE에서 사용할 수 있게 지원하고 있습니다.

### Rstudio {#rstudio}

![RStudio 홈페이지](https://raw.githubusercontent.com/mrchypark/data_camp_dabrp/master/images/rstudio-home.PNG)
[RStudio][5]는 R을 처음 배우는 사람이 꼭 사용하는 IDE입니다. 다른 IDE에 비해 R 언어에 특화된 UI와 기능을 가지고 있으며 ggplot2, shiny, dplyr, httr 등 다양항 패키지를 왕성하게 만들고 있는 RStudio 팀이 직접 관리를 하기 때문에 문서도 많고, 우리나라 사용자층도 큰 편입니다. 특히 초보자부터 고급 사용자까지 필요한 많은 기능들을 GUI로 제공해 줘서 배울 수록 편리함이 늘어납니다.

### 다른 IDE 소개 {#ide-others}

IDE는 메모장 처럼 가벼운 [Sublime Text][201]부터 본격적인 [Visual Studio][202]까지 다양합니다. 개발자들이 많이 사용하는 IDE를 몇개 소개하겠습니다.

![Sublime Text](https://www.drupal.org/files/sublime.png)
[Sublime Text][201]는 꽤 오랫동안 사랑받은 텍스트 에디터 형 IDE입니다. 몇 가지 설정을 진행하면 R 코드도 실행하게 만들 수 있어 기존 개발자 분들 중 R을 공부하실 때 사용하는 경우가 종종 있습니다.

![Atom](https://joshuajangblog.files.wordpress.com/2016/09/atom_editor.png?w=840)
[Atom][204]은 웹기술을 활용해서 어느 컴퓨터에서든 사용할 수 있는 범용성을 가진 IDE입니다. 가장 큰 강점은 plugin 제작이 쉬워서 사용자층이 폭발적으로 늘어나서 최근 많은 개발자들이 사용하고 있습니다. 대부분 웹 개발에 사용되며 오픈소스여서 비용이 발생하지 않는 장점이 있습니다.

![Vs Code](https://msdnshared.blob.core.windows.net/media/2016/03/vsc1.jpg)
[Vs Code][205]는 Atom의 소스를 사용해서 마이크로소프트에서 수정한 IDE입니다. 여전히 오픈소스이며 큰 기업이 지원하는 만큼 기능 정리를 통한 최적화가 강점입니다. github 연동, 자동 업데이트 등 사용자 편의에 조금 더 중점을 두었습니다.

![Nuclide](https://nuclide.io/static/images/docs/promo-debugger.png)
[Nuclide][206]도 역시 Atom의 소스를 사용해서 페이스북이 만든 IDE입니다. 역시 오픈소스이며 remote Development를 기본 제공하는 것이 큰 특징입니다. 페이스북 내에서 사용하기 위해 만들어졌다보니 웹개발에 조금더 최적화되어 있습니다.

![RTVS](http://microsoft.github.io/RTVS-docs/media/RTVS-Installation-data-scientist-layout-result.png)
마이크로 소프트가 레볼루션 R을 인수하면서 R 생태계 흡수를 위해 여러 기능들을 지원하는데요. [RTVS][203]이 대표적입니다. [Visual Studio][202]는 꽤 오랫동안 개발자들이 사용한 IDE입니다. IDE라는 말이 어울리게 수GB의 용량을 차지하고 매우 많은 기능들을 제공합니다. [RTVS][203]는 이런 [Visual Studio][202]에서 R을 사용할 수 있게 만든 기능으로 무료로 공개한 Visual Studio 2015 커뮤니티 버전에 설치하여 R의 사용환경을 구성할 수 있습니다.

## 구조와 기능들 {#structures}

RStudio는 처음부터 R을 지원하기 때문에 설치 이외의 작업을 할 필요 없고, 사용자층이 많아 사용법을 배우기도 좋고 검색도 쉽게 됩니다. 그래서 IDE를 RStudio로 선정하고 기능에 대해 설명하겠습니다. 여기 설명하는 기능은 RStudio만의 기능이 아니며 다른 IDE도 구성에 따라 같은 기능 혹은 더 나은 기능을 사용할 수 있습니다.
![실행화면](https://raw.githubusercontent.com/mrchypark/data_camp_dabrp/master/images/rstudio-run.png)
처음 실행하면 전부 4개면(pane)으로 구성되어 있으며 각부의 이름 은 위 그림과 같습니다.


### source 창 {#source-pane}

### console 창 {#console-pane}

### environment 창 {#env-pane}

### help 창 {#help-pane}


## 프로젝트와 버전관리 {#project-git}

### 폴더와 프로젝트 {#use-project}

### 버전관리도구 git {#introduce-git}

### 오픈소스와 github {#introduce-github}


## 도움말 {#help-page}

### 도움말 설명 {#introduce-help}

### 도움말 사용법 {#help-usage}

### 함수의 옵션 설명 {#help-param}

### 함수의 상세 설명 {#help-detail}

### 예시 코드 {#help-example}

[201]: https://www.sublimetext.com/
[202]: https://www.visualstudio.com/
[203]: http://microsoft.github.io/RTVS-docs/installation.html
[204]: https://atom.io/
[205]: https://code.visualstudio.com/
[206]: https://nuclide.io/