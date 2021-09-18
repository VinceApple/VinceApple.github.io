---
title: "Service"
description: "this is meta description"
bg_image: "images/feature-bg.jpg"
layout: "service"
draft: false
menu:
  main:
    parent: "More"
    name: "Service"
    weight: 1
  footer:
    name: "Service"
    weight: 3

########################### about service #############################
about:
  enable : true
  title : "Creative UX/UI Design Agency"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate soluta corporis odit, optio
          cum! Accusantium numquam ab, natus excepturi architecto earum ipsa aliquam, illum, omnis rerum, eveniet
          officia nihil. Eum quod iure nulla, soluta architecto distinctio. Nesciunt odio ullam expedita, neque fugit
          maiores sunt perferendis placeat autem animi, nihil quis suscipit quibusdam ut reiciendis doloribus natus nemo
          id quod illum aut culpa perspiciatis consequuntur tempore? Facilis nam vitae iure quisquam eius harum
          consequatur sapiente assumenda, officia voluptas quas numquam placeat, alias molestias nisi laudantium
          nesciunt perspiciatis suscipit hic voluptate corporis id distinctio earum. Dolor reprehenderit fuga dolore
          officia adipisci neque!"
  image : "images/company/company-group-pic.jpg"


########################## featured service ############################
featured_service:
  enable : true
  service_item:
    # featured service item loop
    - name : "Interface Design"
      icon : "ion-erlenmeyer-flask"
      color : "primary"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

    # featured service item loop
    - name : "Product Branding"
      icon : "ion-leaf"
      color : "primary-dark"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

    # featured service item loop
    - name : "Game Development"
      icon : "ion-lightbulb"
      color : "primary-darker"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."


############################# Service ###############################
service:
  enable : true
  title : "Features"
  description : <p style="font-size:20px">Speedy deployment and flexible customization<br/>Tailor-made to EFL teachers</p>
  service_item:
    # service item loop
    - icon : ion-load-c  #ionicon pack v2 : https://ionicons.com/v2/
      name: Adaptable
      content: <p style="font-size:18px;line-height:30px; color:#7b7b7b">Tailored to the needs of <br/>EFL teachers</p>

    # service item loop
    - icon : ion-clipboard #ionicon pack v2 : https://ionicons.com/v2/
      name: Informative
      content: <p style="font-size:18px;line-height:30px; color:#7b7b7b">Bridging the gap between <br/>technology and EFL</p>

    # service item loop
    - icon : ion-chatbox-working #ionicon pack v2 : https://ionicons.com/v2/
      name: Supportive
      content: <p style="font-size:18px;line-height:30px; color:#7b7b7b">Providing extracurricular technical support</p>

    # service item loop
    - icon : ion-search #ionicon pack v2 : https://ionicons.com/v2/
      name: Exploratory
      content: <p style="font-size:18px;line-height:30px; color:#7b7b7b">Discovering use cases in <br/>EFL contexts</p>

 

############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "_index.md"
---
