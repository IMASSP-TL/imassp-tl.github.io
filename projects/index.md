---
title: 项目进度
nav:
  order: 2
  tooltip: 当前汉化进度
header: images/header-background.jpg
footer: images/header-background.jpg
header-dark: false
footer-dark: false
---

# {% include icon.html icon="fa-solid fa-wrench" %}汉化进度

偶像大师SP汉化项目各部分进度如下(处理文件数量 / 总文件数量)：

```mermaid!
%%{init:{
  "gantt" :{
    "barGap":12,
    "barHeight": 36,
    "fontSize":20,
    "sectionFontSize":25,
    "leftPadding":150
  }
}}%%
gantt
    title 　
    dateFormat  X
    axisFormat %s%%

    section 主线剧情
    完美之日 409/409 : ps,0,100
    惊奇之星 404/404 : ws,0,100
    思念之月 404/404 : mm,0,100
    section Fan's Mail
    天海春香 20/20 : done,har,0,100
    如月千早 20/20 : done,chi,0,100
    萩原雪步 20/20 : done,yuk,0,100
    水濑伊织 20/20 : done,ior,0,100
    高槻弥生 20/20 : done,yay,0,100
    三浦梓 20/20 : done,azu,0,100
    菊地真 20/20 : done,mak,0,100
    双海亚美&真美 20/20 : mam,0,100
    秋月律子 20/20 : rit,0,100
    section 公用内容
    对话 29/29 : done,com,0,100
    图片UI 100/100 : iu,0,100
    系统UI 1858/1875: su,0,98
    staff's mail 28/28 : done,sm,0,100
    section DLC Items
    歌曲服饰 157/162 : di,0,96
    广播剧 11/11 : drama,0,100
    section DLC Mail
    天海春香 137/137 : done,har,0,100
    如月千早 137/137 : done,chi,0,100
    萩原雪步 137/137 : done,yuk,0,100
    水濑伊织 137/137 : done,ior,0,100
    高槻弥生 137/137 : done,yay,0,100
    三浦梓 5/137 : azu,0,1
    菊地真 137/137 : mak,0,100
    双海亚美&真美 60/137 : mam,0,44
    秋月律子 137/137 : rit,0,100
    section 总体进度
    天海春香 100% : done,har,0,100
    如月千早 100% : done,chi,0,100
    萩原雪步 100% : yuk,0,100
    水濑伊织 100% : ior,0,100
    高槻弥生 100% : yay,0,100
    三浦梓 78% : azu,0,78
    菊地真 100% : mak,0,100
    双海亚美&真美 82% : mam,0,82
    秋月律子 100% : rit,0,100
    星井美希 100% : mik,0,100
    四条贵音 100% : tak,0,100
    我那霸响 100% : hib,0,100
```

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## 效果预览

{% include list.html component="card" data="projects" filters="group: featured" %}

{% include section.html %}

## 相关下载

{% include list.html data="posts" component="post-excerpt" %}

{% include section.html %}