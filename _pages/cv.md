---
layout: cv
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: nchmz_CV.pdf
description: Download my latest CV in PDF format.
toc:
  sidebar: left
---

<style>
  /* 将简历里的列表（Skills 和 Interests）变成横向双列排版 */
  .resume .list-group {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    padding-left: 0;
  }
  
  .resume .list-group-item {
    flex: 0 0 50%; /* 每个词条占据 50% 的宽度，自动形成两列/两行 */
    border: none;
    padding: 0.2rem 0; /* 微调上下间距，让行与行之间更紧凑 */
  }

  /* 针对手机端的小屏幕优化：屏幕太窄时自动恢复单列，防止文字挤在一起 */
  @media (max-width: 576px) {
    .resume .list-group-item {
      flex: 0 0 100%;
    }
  }
</style>