---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/lang/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Links"
    info: "저의 블로그와 프로그램에 대한 다양한 정보 링크를 공유하는 장소입니다~ 많은 도음이 되었으면 합니다!"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Study"
      type: id_study
      color: "#F4A273"
    - title: "관련정보"
      type: id_related_info
      color: "#62b462"
    - title: "전공-반도체"
      type: id_semiconductor
      color: "gray"
    - title: "전공-컴퓨터"
      type: id_computer
      color: "blue"

  list:
    # Study
    - type: id_study
      title: "github 블로그 만들기"
      url: "https://velog.io/@shg4821/%EA%B9%83%ED%97%88%EB%B8%8C-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0-1"
      info: "나만의 홈페이지를 만들기 위해 github.io를 활용, 디자인 플랫폼 많이 있어서 활용하기 편함"

    # 관련정보
    - type: id_related_info
      title: "한양대학교 ASDL연구실"
      url: "https://yh2424.github.io/"
      info: "Advanced Semiconductor Devices Laboratory (ASDL), Hanyang University (Jun.2021 ~Jan.2022) - [김영현교수님]"


    # 반도체
    - type: id_semiconductor
      title: "한양대(학부) TFT의 전반적인 연구"
      url: "https://junsusong98.github.io/ko/tabs/projects.html#id_Lab"
      info: "한양대 학부생 연구실 생활을 하면서 이뤄낸 성과와 연구입니다."

    # Computer
    - type: id_computer
      title: "Stanford CS231 수업 수강"
      url: "https://youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk"
      info: "AI원리를 기초적으로 알려준다."
    
---
