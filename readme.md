# YouVersion Bible 阅读优化脚本  
# YouVersion Bible Reading Optimizer (UserScript)

---

## 中文说明

### 功能
- 自动解除 YouVersion 网页版章节宽度限制，文本区域扩展至 90% 视口宽度并居中显示  
- 隐藏原版翻页按钮，改为屏幕左右边缘 5vw 透明热区，点击即可上下章跳转  
- 保留所有现有功能（朗读、对比、笔记等）  

### 安装
1. 安装 [Tampermonkey][1]（或同类用户脚本管理器）  
2. 点击「Raw」→ 安装  
3. 打开 [https://www.bible.com/bible][2] 即可生效  

### 使用
- 鼠标移至左右边缘出现淡色箭头，单击跳转  
- 热区宽度 5vw，不影响正文选择复制  

### 兼容性
Chrome ≥ 105、Edge ≥ 105、Firefox ≥ 113、Safari ≥ 16  
（需支持 `:has()` 选择器）

---

## English README

### Features
- Removes YouVersion web chapter width limit; content expands to 90% viewport width and centers automatically  
- Replaces default nav-arrows with 5vw transparent hot-zones on both screen edges  
- All original features (audio, parallel, highlights) remain intact  

### Install
1. Install [Tampermonkey][1] (or any userscript manager)  
2. Click「Raw」→ Install  
3. Visit [https://www.bible.com/bible][2] and enjoy  

### Usage
- Move cursor to left/right edge → faint arrow appears → click to change chapter  
- Hot-zone width = 5vw; will not interfere with text selection  

### Compatibility
Chrome ≥ 105, Edge ≥ 105, Firefox ≥ 113, Safari ≥ 16  
(requires `:has()` selector support)

---

[1]: https://www.tampermonkey.net  
[2]: https://www.bible.com/bible
