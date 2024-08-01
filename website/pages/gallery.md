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
    - boldText: "🔥 All you can eat seafood, sushi and hibachi grill."
    - text: "Limited time offer. soft opening special . take 15% off entire bill with this ad."
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
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-cn" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#ffffff"
  addOtherBtn: true
  otherBtnInsteadText: "Get Direction"
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
    bgImgAlt: "Hibachi Buffet- Sushi & Grill - Best Food Today"
    bgColor: "#000"
    bgOpacity: "0.3" # 0~1
    title: 
      - "Gallery"
    titleColor: "#ffffff"
    description: 
      - "Experience Variety and Freshness: A Buffet Delight Awaits!"
    descriptionColor: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: "See MENU & Order"
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
      - "Gallery"
    titleColor: "#000000"
    description: 
      - "Bringing You Culinary Delights with Our Commitment to Quality and Service!"
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
    getDirectionBtnInsteadText: ""
    telInsteadText: ""
 
 # The modal will only appear once within 30 minutes."
  - type: "modal" 
    bgColor: "#333"
    bgOpacity: "0.1" # 0~1
    title: 
      - "🔥  All you can eat seafood, sushi and hibachi grill."
    titleColor: "##EA5A1B"
    titleSize: 18
    description: ""
    descriptionColor: ""
    descriptionSize: 16
    imgName: "offer.webp"
    imgAlt: "🔥 Limited time offer. soft opening special . take 15% off entire bill with this ad."
    buttonText: "Get Direction"
    btnHref: "https://maps.app.goo.gl/baq4QQgK9q8gsvuT6" # default orderOnlineLink

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: "gallery2/Hibachi_Buffet_Sushi_Grill_Best_Food_Today_dish34.webp"
  bgImgAlt: "Hibachi Buffet Sushi Grill - Best Food Today"
  bgColor: "#000000"
  bgOpacity: "0.8" # 0~1
  openingHours: 
    - "Monday to Sunday: 11:00 AM - 9:00 PM"
  
  isLogo: true
  logoSize: 80

  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh-cn" }

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
  seo:
    metaDescription: "Gallery of Hibachi Buffet Sushi & Grill. Perfect for family dinners and special events. Join us today for an unforgettable local dining experience!"
    keywords: "food at Hibachi Buffet Sushi & Grill, Best Hibachi Buffet in Citrus Heights, All-you-can-eat Sushi in Citrus Heights, Family-friendly Asian Restaurant in Citrus Heights, Affordable Buffet in Citrus Heights, Hibachi Buffet with Fresh Seafood in Citrus Heights"
    img: "Hibachi Buffet- Sushi & Grill - Best Food Today.webp"
    thisPageUrl: ""
    locale: "en_US" # zh_TW | zh_CN
---
<!-- hello world -->