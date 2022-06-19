---
title: Projects - Ayush Pathak
display: Projects
# subtitle: My projects
description: My projects
projects:
  Personal:
    - name: "Melodify"
      link: "https://github.com/AyushPathak3011/Melodify"
      desc: "Mood based melody generator"
      icon: "i-mdi-clock-fast"

  Minimaly:
    - name: "Gratitude Organice Products"
      link: "http://gratitudeorganicproducts.com"
      desc: "Designed an e-commerce website for a local organic hair product company"
      icon: "i-carbon-favorite"
---

<ListProjects :projects="frontmatter.projects"/>

<StarsRanking/>
<ClientOnly>
  <Plum/>
</ClientOnly>
