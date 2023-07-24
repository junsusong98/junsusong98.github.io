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
# image_lazy_loader_on: true
# exclude from on site search
# on_site_search_exclude: true
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
    info: "It is a place where I share links to my blog and programs or various information links~ I hope it helps you a lot"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Study"
      type: id_study
      color: "#F4A273"
    - title: "Related_info"
      type: id_related_info
      color: "#62b462"
    - title: "Major_semiconductor"
      type: id_semiconductor
      color: "gray"
    - title: "Major_computer"
      type: id_computer
      color: "blue"

  list:
    # Study
    - type: id_study
      title: "Create github Blog"
      url: "https://velog.io/@shg4821/%EA%B9%83%ED%97%88%EB%B8%8C-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0-1"
      info: "Use `github.io` to create your own homepage. Easy to use because there are many design platforms"

    # Related_info
    - type: id_related_info
      title: "Hanyang University ASDL Lab"
      url: "https://yh2424.github.io/"
      info: "Advanced Semiconductor Devices Laboratory (ASDL), Hanyang University (Jun.2021 ~Jan.2022) - [Younghyun Kim, Ph.D.]"


     # 반도체
    - type: id_semiconductor
      title: "A Overall Study on the TFT of Hanyang University (Undergraduate)"
      url: "https://junsusong98.github.io/ko/tabs/projects.html#id_Lab"
      info: "It is the achievement and research that I have achieved while living in the laboratory of undergraduate students at Hanyang University."

    # Computer
    - type: id_computer
      title: "Taking Stanford CS231 lectures"
      url: "https://youtube.com/playlist?list=PLC1qU-LWwrF64f4QKQT-Vg5Wr4qEE1Zxk"
      info: "It basically informs the principles of AI."
---

