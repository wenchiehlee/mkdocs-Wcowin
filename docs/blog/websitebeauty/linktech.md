---
title: 如何給MKdocs新增友鏈
tags:
  - Mkdocs
hide:
  - feedback
---

複製後在需要新增友鏈的.md檔案頁面貼上即可

```html
<div class="post-body">
   <div id="links">
      <style>
/* 用於大螢幕和小螢幕的通用樣式 */
.card {
    width: 45%;
    font-size: 1rem;
    padding: 10px 20px;
    border-radius: 4px;
    transition-duration: 0.15s;
    margin-bottom: 1rem;
    display: flex;
 }
 .card:nth-child(odd) {
    float: left;
 }
 .card:nth-child(even) {
    float: right;
 }
 .card:hover {
    transform: scale(1.1);
    box-shadow: 0 2px 6px 0 rgba(0, 0, 0, 0.12), 0 0 6px 0 rgba(0, 0, 0, 0.04);
 }
 .card a {
    border: none;
 }
 .card .ava {
    width: 3rem!important;
    height: 3rem!important;
    margin: 0!important;
    margin-right: 1em!important;
    border-radius: 4px;
 }
 .card .card-header {
    font-style: italic;
    overflow: hidden;
    width: 100%;
 }
 .card .card-header a {
    font-style: normal;
    color: #608DBD;
    font-weight: bold;
    text-decoration: none;
 }
 .card .card-header a:hover {
    color: #d480aa;
    text-decoration: none;
 }
 .card .card-header .info {
    font-style: normal;
    color: #a3a3a3;
    font-size: 14px;
    min-width: 0;
    overflow: hidden;
    white-space: nowrap;
 }
 /* 媒體查詢：小螢幕 */
 @media (max-width: 768px) {
    .card {
       width: 100%; /* 在小螢幕上顯示為單列 */
       float: none; /* 清除浮動 */
    }
 }
      </style>
      <div class="links-content">
         <div class="link-navigation">
            <div class="card">
               <img class="ava" src="https://cn.mcecy.com/image/20231006/a05f708fb7b0426e7a5786669d5b1386.png" />
               <div class="card-header">
                  <div>
                     <a href="https://wcowin.work/ " target=“_blank”>Wcowin’s blog</a>
                  </div>
                  <div class="info">這是一個分享技術的小站。</div>
               </div>
            </div>
            <div class="card">
               <img class="ava" src="https://i.loli.net/2020/05/14/5VyHPQqR6LWF39a.png" />
               <div class="card-header">
                  <div>
                     <a href="https://twitter.com/" target=“_blank”>Twitter</a>
                  </div>
                  <div class="info">社交分享平臺</div>
               </div>
            </div>
            <div class="card">
               <img class="ava" src="https://cn.mcecy.com/image/20231012/d96b912437fb0bec0d282dfe734b1d9b.jpeg"/>
               <div class="card-header">
                  <div>
                     <a href="https://macapp.org.cn/" target=“_blank”>Macapp</a>
                  </div>
                  <div class="info">一個專注於分享Mac資源的頻道</div>
               </div>
            </div>
         </div>
      </div>
   </div>
</div>
```

## 如何加入友鏈

```html
<div class="card"> 
<img class="ava" src="{avatarurl}" /> 
<div class="card-header"> 
<div> 
<a href="{link}" target="_blank">{name}</a> 
</div> 
<div class="info">{description}</div> 
</div> 
</div>
</div>
```

### 示例

```html
<div class="card"> 
   <img class="ava" src="https://cn.mcecy.com/image/20231006/a05f708fb7b0426e7a5786669d5b1386.png" /> 
   <div class="card-header"> 
   <div> 
   <a href="https://wcowin.work/ " target=“_blank”>Wcowin’s blog</a> 
   </div> 
   <div class="info">
   這是一個分享技術的小站。
   </div> 
</div> 
</div> 
```
## 效果
<div>
  <div class="links-content"> 
   <div class="link-navigation"> 
    <div class="card"> 
     <img class="ava" src="https://s2.loli.net/2024/02/01/gaE47y5fKM6kosV.png" /> 
     <div class="card-header"> 
      <div> 
       <a href="https://wcowin.work/ " target=“_blank”>Wcowin’s blog</a> 
      </div> 
      <div class="info">
       這是一個分享技術的小站。
      </div> 
     </div> 
    </div> 
</div>
