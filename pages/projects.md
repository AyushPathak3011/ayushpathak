---
title: Projects - Ayush Pathak
display: Projects
# subtitle: My projects
description: My projects
projects:
  Python:
    - name: "Melodify"
      link: "https://github.com/AyushPathak3011/Melodify"
      desc: "Mood based melody generator"
      icon: "i-mdi-clock-fast"

  Minimaly:
    - name: "Gratitude Organic Products"
      link: "http://gratitudeorganicproducts.com"
      desc: "Designed an e-commerce website for a local organic hair product company"
      icon: "i-carbon-favorite"

  Blockchain:
    - name: "brokeDAO"
      link: "https://github.com/AyushPathak3011/brokeDAO"
      desc: "Winner BlockET Hackathon by IET-VIT Revise Track. <br>A DAO for students and contributors with NFT minting, governance and voting features."
      icon: "i-carbon-favorite"
---

<ListProjects :projects="frontmatter.projects"/>

<StarsRanking/>
<ClientOnly>
  <Plum/>
</ClientOnly>
