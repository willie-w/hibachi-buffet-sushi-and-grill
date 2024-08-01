---
layout: "ssg-theme-astro/layouts/main.astro"
tag: "GTM-"
title: "Hibachi Buffet- Sushi & Grill - Best Food Today"
favicon: "favicon.ico"
logo: "logo.webp"
primaryColor: "#EA5A1B" # logo color
secondaryColor: "#000000"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "dark"
dataGlfCuid: ""
dataGlfRuid: ""
orderOnlineLink: "#"
tableReservationLink: ""
tel: "916-961-1508"

banner:
  text: 
    - boldText: "🔥 無限暢享海鮮、壽司和鐵板燒。限時優惠。試營運特別折扣，憑此廣告全單享有15折優惠。"
    # - smText: ""
    # - text: ""
  # add more text...
  textColor: "#ffffff"
  bgColor: "#EA5A1B"
  bgOpacity: "1" # 0~1

# header
header:
  logoSize: 50
  textAfterLogo: 
    text: ""
    size: 16
    color: ""
  bgColor: "#000000"
  bgOpacity: "0.9" # 0~1
  menuTextColor: "#ffffff"
  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#" }
    - { text: "關於我們", link: "/zh-cn#about-us" }
    - { text: "聯繫我們", link: "/zh-cn#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#ffffff"
  addOtherBtn: true
  otherBtnInsteadText: "導航去餐廳"
  otherBtnHref: "https://maps.app.goo.gl/baq4QQgK9q8gsvuT6"

sections:
# hero
  - type: "hero" 
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "video" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1gueft0keol4QZp7RqibZLYsR1co1c"
    bgImg: "background_image.webp"
    bgImgAlt: "菜品展示"
    bgColor: "#000"
    bgOpacity: "0.3" # 0~1
    title: 
      - "菜品展示"
    titleColor: "#ffffff"
    description: 
      - "豐富多樣，新鮮美味：自助餐的美食盛宴等待您的品嚐！"
    descriptionColor: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""
    showOtherBtn: false
    btn1Text: "See MENU & Order" # default: order online
    btn1Href: "#" # default: order online
    btn2Text: "" # default: table reservation
    btn2Href: "" # default: table reservation

    bannerImg: "Hibachi Buffet- Sushi & Grill - Best Food Today.webp"
    imgAlt: "Hibachi Buffet- Sushi & Grill - Best Food Today"
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 16
    imgRounded: "lg" # sm | md | lg | xl | 2xl | 3xl | full
   
    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"


# Gallery  
  - type: "gallery"
    id: "gallery"
    mode: 1 # 1 - 3
    bgImg: ""
    bgImgAlt: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title: 
      - " A Buffet Lover's Paradise!"
    titleColor: "#000000"
    description: 
      - "Start Your Journey into Asian Cuisine at Hibachi Buffet- Sushi & Grill!"
    descriptionColor: "#333333"
    folderPath: "gallery,gallery2"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full



# map  
  - type: "map"
    noMarginTop: false
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/baq4QQgK9q8gsvuT6"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3115.1563766683626!2d-121.27547174783979!3d38.66827407348092!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x809adf84c7c0d6d3%3A0x8ad478e11209fd52!2sHibachi%20Buffet%2C%20Sushi%20%26%20Grill!5e0!3m2!1sen!2sus!4v1722498429048!5m2!1sen!2sus"
    addTelBtn: true
    getDirectionBtnInsteadText: "導航去餐廳"
    telInsteadText: "tel: (916) 961-1508"
 
 # The modal will only appear once within 30 minutes."
  - type: "modal" 
    bgColor: "#333"
    bgOpacity: "0.1" # 0~1
    title: 
      - "🔥 無限暢享海鮮、壽司和鐵板燒。"
    titleColor: "##EA5A1B"
    titleSize: 18
    description: ""
    descriptionColor: ""
    descriptionSize: 16
    imgName: "offer_chinese.webp"
    imgAlt: "🔥 限時優惠。試營運特別折扣，憑此廣告全單享有85折優惠。"
    buttonText: "導航去餐廳"
    btnHref: "https://maps.app.goo.gl/baq4QQgK9q8gsvuT6" # default orderOnlineLink

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "gallery2/Hibachi_Buffet_Sushi_Grill_Best_Food_Today_dish34.webp"
  bgImgAlt: "Hibachi Buffet Sushi Grill - Best Food Today"
  bgColor: "#000000"
  bgOpacity: "0.8" # 0~1
  openingHours: 
    - "週一 ～ 週日: 11:00 AM - 9:00 PM"
  
  isLogo: true
  logoSize: 80

  menu:
    - { text: "首頁", link: "/zh-cn" }
    - { text: "菜品展示", link: "#" }
    - { text: "關於我們", link: "/zh-cn#about-us" }
    - { text: "聯繫我們", link: "/zh-cn#contact-us" }
    - { text: "English", link: "/" }
  FB: false
  FBLink: "#"
  IG: false
  IGLink: "#"
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: true
  yelpLink: "https://www.yelp.com/biz/hibachi-buffet-sushi-and-grill-citrus-heights"

  paymentMethod: "" #alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  # optional
#   seo:
#     metaDescription: "Discover Hibachi Buffet Sushi & Grill, a local favorite at 5623 Sunrise Blvd, Citrus Heights, CA. Enjoy fresh seafood, sushi, and Asian cuisine."
#     keywords: "Best Hibachi Buffet in Citrus Heights, All-you-can-eat Sushi in Citrus Heights, Family-friendly Asian Restaurant in Citrus Heights, Affordable Buffet in Citrus Heights, Hibachi Buffet with Fresh Seafood in Citrus Heights"
#     img: "Hibachi Buffet- Sushi & Grill - Best Food Today.webp"
#     thisPageUrl: ""
#     locale: "zh_CN" # zh_TW | zh_CN
---
<!-- hello world -->