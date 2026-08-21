---
permalink: /
title: ""
author_profile: true
header:
  overlay_image: "https://yibochen23333.vercel.app/images/banner.png"
  overlay_filter: 0.1
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 解决问题3：拉高背景横幅，居中显示，让“哈基米”字画和小猫完美露出 */
  .page__hero--overlay {
    min-height: 580px !important; 
    background-position: center center !important;
  }

  /* 解决问题1和2：给左侧信息栏加一个半透明白底板，并强行把它往下推，不准遮挡顶栏 */
  .sidebar {
    background-color: rgba(255, 255, 255, 0.95) !important;
    padding: 20px 20px 10px 20px !important;
    border-radius: 12px !important;
    box-shadow: 0 4px 15px rgba(0,0,0,0.15) !important;
    margin-top: 30px !important; 
    z-index: 10;
  }

  /* 强制左侧文字变黑，去除默认的白色发光特效，确保绝对清晰 */
  .author__name, .author__bio, .author__urls-wrapper {
    text-shadow: none !important;
    color: #222 !important;
  }
  .author__urls a {
    color: #494e52 !important;
  }
</style>

# Welcome!

I am a PhD student in Mathematics at the University of Jyväskylä and the University of Padua (Double degree based on a "Cotutelle" agreement). 

I am working in the [Geometric measure theory and harmonic analysis](https://www.jyu.fi/en/research-groups/geometric-measure-theory-and-harmonic-analysis) research group.

My supervisors are Prof. [Katrin Fässler](https://kfaessler.wixsite.com/math) and Prof. [Roberto Monti](https://www.math.unipd.it/~monti/).

You can find my email on my JYU's official website: [https://www.jyu.fi/en/people/yibo-chen](https://www.jyu.fi/en/people/yibo-chen).

### Research Interests
I am interested in **Geometric Analysis**, including:
* Uniform/Quantitative rectifiability in Heisenberg groups.
* Minimal surfaces/Plateau problems in Heisenberg groups.
* Currents in Heisenberg groups.
