---
theme: seriph
background: https://source.unsplash.com/1920x1080/?3d,world,ai
title: Marble World AI
info: |
  ## Marble World AI 介紹
  使用 AI 創建高保真、持久化的 3D 世界
  
  Learn more at [World Labs](https://docs.worldlabs.ai/)
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
duration: 30min
---

# Marble World AI

## 用 AI 創造高保真 3D 世界

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    開始探索 <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="在編輯器中打開" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://docs.worldlabs.ai/" target="_blank" alt="World Labs 文檔" title="World Labs 文檔" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:logo-github />
  </a>
</div>

---
transition: fade-out
---

# 什么是 Marble？

<div class="grid grid-cols-2 gap-8 mt-8">

<div>

**Marble** 是 World Labs 的首個產品

- 🎨 **高保真 3D 世界** - 創建逼真的 3D 環境
- 🔄 **持久化** - 世界可以被保存和分享
- 🤖 **AI 驅動** - 由多模態世界模型提供支持
- 🚀 **簡單易用** - 任何人都可以輕鬆創建

</div>

<div>

**核心能力**

- 從文本、圖像、視頻重建 3D 世界
- 生成完整的 3D 環境
- 模擬和編輯 3D 空間
- 支持多種導出格式

</div>

</div>

---
transition: slide-up
level: 2
---

# Marble 界面導航

<div class="grid grid-cols-3 gap-6 mt-8">

<div v-click>

## 🖼️ Gallery
**[畫廊](https://marble.worldlabs.ai/)**

瀏覽和探索社區創建的世界，發現靈感，訪問自己創建的世界

</div>

<div v-click>

## ✨ Create
**[創建](https://marble.worldlabs.ai/create)**

主要工作區，使用文本、圖像、視頻或 3D 結構生成新的 3D 世界

</div>

<div v-click>

## 🎬 Studio
**[工作室](https://marble.worldlabs.ai/projects)**

高級工具，用於編輯、組合多個世界，並創建電影級的環境錄製

</div>

</div>

---
layout: two-cols
layoutClass: gap-16
---

# 創建世界的方式

Marble 提供多種創建 3D 世界的方法，適應不同的創作工作流：

::left::

<div v-click>

### 🎲 Preset
**預設模板**

瀏覽並選擇精選的預設示例，快速生成基於流行主題和風格的世界

</div>

<div v-click class="mt-4">

### 📝 Text Prompt
**文本提示**

用自然語言描述你的願景，讓 Marble 的 AI 生成完整的 3D 環境

</div>

<div v-click class="mt-4">

### 🖼️ Single Image
**單張圖片**

將任何照片或藝術作品轉換為沉浸式 3D 世界

</div>

::right::

<div v-click>

### 🖼️ Multiple Images

組合多張圖片以指定更多視覺細節，可以指定每張圖片的方向位置

</div>

<div v-click class="mt-4">

### 🌐 Panorama

上傳 360° 全景圖像，獲得對世界佈局的最大控制和最準確的空間表示

</div>

<div v-click class="mt-4">

### 🎥 Video

上傳短視頻（小於 100MB）提供豐富的空間信息

</div>

<div v-click class="mt-4">

### 🔨 3D Structure (Chisel)

使用內置 3D 建模工具構建幾何佈局和建築結構作為詳細世界生成的基礎

</div>

---
transition: slide-up
---

# 創建方式詳解（一）

<div class="grid grid-cols-2 gap-6 mt-8">

<div v-click>

## 📝 [文本提示](https://marble.worldlabs.ai/create)
**最簡單的方式**

```
"A futuristic technology lab, 
featuring holographic projections 
and robotic assistants."
```

- 自然語言描述
- AI 自動生成
- 適合快速原型

</div>

<div v-click>

## 🖼️ 圖像轉 3D
**從 2D 到 3D**

- **單張圖片**：快速轉換
- **多張圖片**：更精確的控制
- **全景圖**：最準確的空間表示

支持方向定位：
- Front（前）
- Back（後）
- Left（左）
- Right（右）
- Auto Layout（自動佈局）

</div>

</div>

---
transition: slide-up
---

# 創建方式詳解（二）

<div class="grid grid-cols-2 gap-6 mt-8">

<div v-click>

## 🎥 [視頻輸入](https://marble.worldlabs.ai/create)
**豐富的空間信息**

- 上傳短視頻（< 100MB）
- 適合 360° 旋轉視圖
- 提供豐富的空間上下文

</div>

<div v-click>

## 🔨 [Chisel 工具](https://docs.worldlabs.ai/guides/chisel/chisel_basics)
**3D 結構建模**

- 內置 3D 建模工具
- 構建幾何佈局
- 創建建築結構
- 作為詳細生成的基礎

</div>

</div>

<!--
# 編輯世界

<div class="grid grid-cols-3 gap-6 mt-8">

<div v-click>

## 🌐 Pano Edit
**全景編輯**

通過全景表示編輯世界

- 選擇特定區域
- 使用自然語言描述更改
- 進行針對性修改
- 保留整體環境

</div>

<div v-click>

## 👆 Click and Expand
**點擊擴展**

超越原始邊界擴展世界

- 點擊未探索區域
- 生成無縫擴展
- 自然連接到現有內容
- 無限擴展可能

</div>

<div v-click>

## 🎨 Variation
**變化生成**

生成世界的替代版本

- 保持核心元素和風格
- 探索不同可能性
- 從同一起點創造變化
- 快速迭代

</div>

</div>
-->

---
layout: two-cols
layoutClass: gap-16
---

# Studio 工具

高級工作室功能，將世界創作提升到新水平

::left::

<div v-click>

## 🎭 Compose
**組合**

連接和排列多個現有世界

- 創建更大的無縫環境
- 適合遊戲地圖
- 建築綜合體
- 廣闊的連接體驗

</div>

::right::

<div v-click>

## 🎬 [Record](https://docs.worldlabs.ai/guides/studio/record)
**錄製**

創建電影級相機動畫

- 平滑的飛行視頻
- 展示環境
- 創建預告片
- 專業演示

</div>

---
transition: slide-up
---

# 導出和分享（一）

<div class="grid grid-cols-2 gap-8 mt-8">

<div v-click>

## 🌐 Web Sharing
**網頁分享**

- 複製可分享鏈接
- 基於瀏覽器的查看和探索
- 無需安裝

</div>

<div v-click>

## 🥽 VR Experience
**VR 體驗**

- 生成 VR 兼容鏈接
- 沉浸式虛擬現實查看
- 完整的 VR 支持

</div>

<div v-click>

## 💻 Development Assets
**開發資源**

- 導出 3D 模型和紋理
- 用於遊戲引擎
- [開發工具集成](https://sparkjs.dev/)

</div>

</div>

---
transition: slide-up
---

# 導出和分享（二）

<div class="grid grid-cols-2 gap-8 mt-8">

<div v-click>

## 🎨 DCC Integration
**數字內容創作集成**

- Blender
- Maya
- 3ds Max
- 專業工作流支持

</div>

<div v-click>

## 🖨️ Mesh Export
**網格導出**

- 導出乾淨的 3D 幾何體
- 3D 打印
- CAD 軟件
- 進一步建模工作

</div>

<div v-click>

## 📦 Gaussian Splat Export
**高斯點雲導出**

- 最新的 3D 表示技術
- 高質量渲染
- 實時性能

</div>

</div>

---
transition: slide-up
---

# 生成時間

<div class="mt-8">

我們不斷努力使 Marble 中的世界生成更快

<div class="grid grid-cols-2 gap-6 mt-6">

<div v-click>

### 快速生成
- **從文本/圖像/3D 結構創建全景**：~30 秒
- **創建草稿**：~20 秒
- **編輯全景**：~20 秒

</div>

<div v-click>

### 完整生成
- **從多圖像/視頻創建全景**：~2 分鐘
- **創建完整世界**：~5 分鐘
- **擴展世界**：~5 分鐘

</div>

<div v-click class="col-span-2">

### 高質量導出
- **生成高質量網格**：~1 小時 (Mesh)

</div>

</div>

</div>

---
layout: center
class: text-center
---

# 核心優勢

<div class="grid grid-cols-3 gap-8 mt-12">

<div v-click>

## 🚀 快速
從想法到 3D 世界只需幾分鐘

</div>

<div v-click>

## 🎨 高質量
高保真、逼真的 3D 環境

</div>

<div v-click>

## 🔄 靈活
多種輸入方式，適應不同需求

</div>

<div v-click>

## 🛠️ 強大
豐富的編輯和導出工具

</div>

<div v-click>

## 🌐 可分享
輕鬆分享和發布你的世界

</div>

<div v-click>

## 🤖 AI 驅動
先進的 AI 技術，簡化創作流程

</div>

</div>

---
layout: center
class: text-center
---

# 應用場景

<div class="grid grid-cols-2 gap-6 mt-8">

<div v-click>

## 🎮 遊戲開發
- 快速原型設計
- 環境創建
- 關卡設計

</div>

<div v-click>

## 🏗️ 建築設計
- 可視化設計
- 空間規劃
- 客戶演示

</div>

<div v-click>

## 🎬 內容創作
- 虛擬場景
- 視頻背景
- 創意項目

</div>

<div v-click>

## 🎓 教育培訓
- 虛擬學習環境
- 歷史場景重建
- 科學可視化

</div>

<div v-click>

## 🏢 商業應用
- 產品展示
- 虛擬展廳
- 營銷材料

</div>

<div v-click>

## 🎨 藝術創作
- 數字藝術
- 概念設計
- 創意探索

</div>

</div>

---
layout: center
class: text-center
---

# 開始使用

<div class="mt-12">

## 訪問 Marble

<div class="text-2xl mt-6">
  [marble.worldlabs.ai](https://marble.worldlabs.ai)
</div>

</div>

<div class="grid grid-cols-3 gap-8 mt-12">

<div v-click>

### 1️⃣ 註冊賬號
創建你的 World Labs 賬號

</div>

<div v-click>

### 2️⃣ 選擇創建方式
從文本、圖像或視頻開始

</div>

<div v-click>

### 3️⃣ 生成和分享
創建你的第一個 3D 世界

</div>

</div>

---
layout: center
class: text-center
---

# 了解更多

<div class="mt-12 text-xl">

[📚 完整文檔](https://docs.worldlabs.ai/) · 
[💬 社區支持](https://docs.worldlabs.ai/) · 
[❓ 常見問題](https://docs.worldlabs.ai/)

</div>

<div class="mt-16 text-4xl">
感謝觀看！
</div>

<div class="mt-8 text-lg opacity-75">
開始創建你的第一個 3D 世界吧 🚀
</div>
