[[English](https://github.com/junsusong98/junsusong98.github.io/blob/main/README.md#readme)] [[việtnam](https://github.com/junsusong98/junsusong98.github.io/blob/main/README-vi.md#readme)] [한글]

## Mr. Green Jekyll 테마

<!-- readme -->

[<img src="https://img.shields.io/github/issues/MrGreensWorkshop/MrGreen-JekyllTheme" alt="GitHub issues" data-no-image-viewer>](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/issues)
[<img src="https://img.shields.io/github/forks/MrGreensWorkshop/MrGreen-JekyllTheme" alt="GitHub forks" data-no-image-viewer>](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/README.md#readme)
[<img src="https://img.shields.io/github/stars/MrGreensWorkshop/MrGreen-JekyllTheme" alt="GitHub stars" data-no-image-viewer>](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/README.md#readme)
[<img src="https://img.shields.io/github/license/MrGreensWorkshop/MrGreen-JekyllTheme" alt="GitHub license" data-no-image-viewer>](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/LICENSE)
[<img src="https://shields.io/badge/Patreon-Tip%20me-blue?logo=Patreon" alt="Tip Me via Patreon" data-no-image-viewer>](https://patreon.com/MrGreensWorkshop "Tip Me via Patreon")
[<img src="https://shields.io/badge/Ko--fi-Tip%20me-blue?logo=kofi" alt="Tip Me via Ko-fi" data-no-image-viewer>](https://www.ko-fi.com/MrGreensWorkshop "Tip Me via Ko-fi")

---

<div align="center">
  <img src="https://mrgreen-jekylltheme.mrgreensworkshop.com/assets/img/posts/mock1.jpg" height="500" alt="screen_mock">
  <br><br>
  <a href="https://MrGreen-JekyllTheme.MrGreensWorkshop.com" style="font-weight: bold;" >Click here for live demo</a>
</div>


### 소개

<!-- outline-start -->

미스터 그린은 지킬과 함께 만들어진 다국어 테마이며 깃허브 페이지와 완벽하게 호환된다.

저는 제 웹사이트를 만들려 했고, 만약 제가 그것을 템플릿으로 한다면, 오픈 소스 커뮤니티와 공유할 수 있을 것이라고 생각했습니다. 그래서 테마로 만들기로 했어요. 저는 이 일을 가능하게 하기 위해 열심히 노력해왔기 때문에 여러분이 저를 지지해 주신다면 기쁘겠습니다. 고마워요.

### 특징

- 다국어 웹 사이트
  - English (default), koran(한글), vietnam(việt nam)
- 권장 언어 제공 기능
- 자동 탐색 버튼 추가
- `Home`, `About`, `Archives`, `Post-list`, `Links`, `Projects` and more 와 같은 layout
- 색상표 전환 옵션 (Dark light)
- 자동 연락처 옵션 추가
- 자동 이미지 참조기 (이미지의 전체 경로를 추가할 필요 없음. 단지 앞에  `:` 을 추가하면 된다.)
- image lazy loader, 이미지 뷰어
- Cool Footer with creative commons licensing
- 게시물로 부터 이동 가능한 contents 모델 상자의 표
- 공유 옵션 게시
- 범주 또는 태그 별 사후 목록
- 게시물에 대한 댓글
  - [Disqus](https://disqus.com)
- 선택 가능한 번호 매기기 또는 로드 유형으로 스크롤
- 사이트 맵 기능
- 검색 엔진 최적화 (SEO)
  - [Schema Markup](https://schema.org)
  - [Open Graph](https://ogp.me/)
  - [Twitter](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/summary)
- 분석 (Google Analytics)
- Cookie 동의 기능
- 사이트 검색 기능
- 작은 공간을 위함 코드 압푹 (`HTML` `JS` `SCSS`)
- 모바일 앱 지원
- 모바일 기기 친화적 (Tested on Android and IOS)
- 개발자를 위한 잘 구성된 폴더 구조 (Tested on Chrome, Safari, FireFox)

### 설치

#### Github pages

1. the repo에서 fork 생성.
1. 편집 \_config.yml 그리고 아래의 `url` 같이 편지 후 push!

   ```yaml
   url: "https://your_github_user_name.github.io"
   ```

1. the repo의 이름을 다시 정하기 `your_github_user_name.github.io`
1. Repo에서 Deploy status 'Actions' 탭을 선택합니다
1. green으로 바뀔때, 너의 사이트를 실행한다. `https://your_github_user_name.github.io`

#### Local build

1. [Install Jekyll](https://jekyllrb.com/docs/installation/) os에 설치
1. Clone or [download](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/releases/latest) the repo, 명령 프롬프트에서 폴더 run `bundle install` 명령으로 이동한다.
1. Build using `bundle exec jekyll serve --watch --host 0.0.0.0 --safe` command
    - with `--host 0.0.0.0` 매개 변수를 사용하면 동일한 lan에서 웹 서버에 액세스할 수 있습니다.
    - with `--safe` 매개 변수를 사용하면 타사 플러그인이 추가되지 않았는지 확인할 수 있습니다. (Github 페이지 개발용)
1.  `0.0.0.0:4000/` 주소에서 페이지가 실행되고 실행됩니다 

### Documentation

나도 알아, 나도 알아. 문서를 쓰는 것보다 코드를 쓰는 게 낫기 때문에 문서로는 결코 충분하지 않아. 하지만 나는 문서와 튜토리얼을 위한 시간을 내려고 노력할 것이다. YouTube에서 미스터 그린 테마 튜토리얼 플레이리스트를 확인하세요.
Check out [Mr. Green theme tutorials playlist](https://www.youtube.com/watch?v=Tz5iWWX0WD4&list=PLAymxPbYHgl-fFy5can7uZBMJtFWVcphD) on YouTube

### Credits

저는 제 웹사이트를 만들 수 있는 기회를 준 이 프로젝트들에 감사드리고 싶습니다.

- [Jekyll](https://jekyllrb.com/) is a static site generator. 즐겨찾기 표시 언어로 작성된 텍스트를 사용하고 레이아웃을 사용하여 정적 웹 사이트를 만듭니다. 사이트의 모양과 느낌, URL, 페이지에 표시되는 데이터 등을 조정할 수 있습니다. 그것은 자원봉사자들에 의해 유지되는 멋진 프로젝트이다

- [GitHub Pages](https://pages.github.com/) Hosted directly from your GitHub repository. 변경 사항을 누르기만 하면 사이트가 자동으로 생성됩니다.

제가 이 프로젝트를 진행하면서 유용하다고 생각하는 사이트들 중 몇 가지가 있습니다. [links page](https://MrGreen-JekyllTheme.MrGreensWorkshop.com/tabs/links.html)

### [You Can Support My Work](https://github.com/MrGreensWorkshop#sponsorship)

처음부터 프로젝트를 만드는 데는 많은 시간이 걸립니다. 제가 이런 프로젝트를 계속하고 모두를 위한 새로운 콘텐츠를 만들 수 있도록 지원해주시면 감사하겠습니다.

### Contribute

꺼내기 요청을 환영합니다. 문제 및 풀 요청 템플릿의 지침을 확인하십시오.

### License

As it says in the [MIT license](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/LICENSE), 라이센스 및 저작권 고지를 포함하기만 하면 어디에서나 이 테마를 사용할 수 있습니다.

`Copyright (c) 2022 Mr. Green's Workshop https://www.MrGreensWorkshop.com`

내 페이지에 링크를 추가하거나 바닥글에 "Pwrd by Mr. Green" 링크를 남겨주시면 내 작업에 대한 점수를 얻을 수 있습니다.

Thank you!

### Other Licenses

Mr. Green Jekil Theme은 아래에 쓰여진 libraries 을 통합합니다. 이 libraries 없이는, 저는 이 프로젝트를 가능하게 할 수 없었습니다.

| Library                              | file |
| :----------------------------------- | ---- |
| [jQuery v3.6.0](https://github.com/jquery/jquery/tree/3.6.0), Copyright [OpenJS Foundation](https://openjsf.org) and other contributors. jQuery is distributed under the terms of the MIT License. | [jquery-3.6.0.min.js](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/js/jquery-3.6.0.min.js) |
| [Bootstrap v3.3.7](https://github.com/twbs/bootstrap/tree/v3.3.7), Copyright (c) 2011-2016 Twitter, Inc. Bootstrap is distributed under the terms of the MIT License. | [bootstrap.min.js](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/js/bootstrap.min.js), [bootstrap.min.css](assets/css/bootstrap.min.css) |
| [Bootstrap Table of Contents v0.4.1](https://github.com/afeld/bootstrap-toc/tree/v0.4.1), Copyright (c) 2015 Aidan Feldman Aidan Feldman. Bootstrap Table of Contents is distributed under the terms of the MIT License. | [bootstrap-toc.min.js](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/js/bootstrap-toc.min.js), [bootstrap-toc.min.css](assets/css/bootstrap-toc.min.css) |
| [Font Awesome v4.7.0](https://github.com/FortAwesome/Font-Awesome/tree/v4.7.0), Copyright (c) 2017 Dave Gandy. The Font Awesome font is distributed under the terms of the [SIL OFL 1.1](http://scripts.sil.org/OFL). Font Awesome CSS, LESS, and Sass files are distributed under the terms of the [MIT License](https://opensource.org/licenses/mit-license.html). | [font-awesome.min.css](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/css/font-awesome.min.css), [FontAwesome](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/fonts/) |
| [Lozad.js v1.16.0](https://github.com/ApoorvSaxena/lozad.js/tree/v1.16.0), Copyright (c) 2017 Apoorv Saxena. Lozad.js is distributed under the terms of the MIT License. | [lozad.min.js](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/js/lozad.min.js) |
| [Magnific Popup v1.1.0](https://github.com/dimsemenov/Magnific-Popup/tree/1.1.0), Copyright (c) 2014-2016 Dmitry Semenov, http://dimsemenov.com. Magnific Popup is distributed under the terms of the MIT License. | [jquery.magnific-popup.min.js](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/js/jquery.magnific-popup.min.js), [magnific-popup.css](assets/css/magnific-popup.css) |
| [Simple-Jekyll-Search v1.9.2](https://github.com/christian-fei/Simple-Jekyll-Search/tree/v1.9.2), Copyright (c) 2015 Christian Fei. Simple-Jekyll-Search is distributed under the terms of the MIT License. | [simple-jekyll-search-1.9.2.min.js](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/assets/js/simple-jekyll-search-1.9.2.min.js) |
| [Compress HTML in Jekyll v3.1.0](https://github.com/penibelst/jekyll-compress-html/tree/v3.1.0), Copyright (c) 2014 Anatol Broder. Compress HTML in Jekyll is distributed under the terms of the MIT License. | [compress.liquid](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme/blob/main/_layouts/util/compress.liquid) |

[Mr. Green Jekyll Theme](https://github.com/MrGreensWorkshop/MrGreen-JekyllTheme)
