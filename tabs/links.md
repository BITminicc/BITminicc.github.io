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
# check the meta_common_description in _data/owner/[language].yml
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
    info: "It may have no direct relationship with me, but it is a more useful link."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "RL Study"
      type: id_RL
      color: "gray"
    - title: "Web Design"
      type: id_webdesign
      color: "#F4A273"
    - title: "Programming"
      type: id_programming
      color: "#62b462"

  list:
    -
    # programming
    - type: id_programming
      title: "github"
      url: "https://github.com/"
      info: "Github is the home for all developers — including me."

    # Reinforcement learning
    - type: id_RL
      title: "RLChina"
      url: "https://space.bilibili.com/604515161/channel/series"
      info: "Learn from experts."
    - type: id_RL
      title: "BIT-RL-Class"
      url: "https://github.com/BITminicc/Experiment-Codes"
      info: "Code for class in BIT."
    - type: id_RL
      title: "Class from DeepMind"
      url: "https://www.bilibili.com/video/BV1h54y1B7nH/?from=search&seid=14138284187456381757"
      info: "DeepMind class for MARL in 2020."
    - type: id_RL
      title: "OpenAI-GYM"
      url: "https://github.com/openai/gym"
      info: "Famous RL test/train environment."

    # webdesign
    - type: id_webdesign
      title: element ui
      url: "https://element.eleme.cn/#/zh-CN"
      info: "A set of desktop component library based on Vue 2.0 for developers, designers and product managers."
    - type: id_webdesign
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools offers free online tutorials, references and exercises in all the major languages of the web. Covering popular subjects like HTML, CSS, JavaScript, Python, SQL, Java, and many more."
---
