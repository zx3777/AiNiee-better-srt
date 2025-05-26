<div align="center">
  <a href="https://github.com/NEKOparapa/AiNiee-chatgpt">
    <img src="https://github.com/NEKOparapa/AiNiee-chatgpt/blob/main/Example%20image/logo.png" width=60% height=60%>
  </a>
</div>


<div align="center">
  <a href="README_EN.md">English</a> | 简体中文
</div>

---


## 软件介绍🧾 

  
<div align="center">
<strong>AiNiee</strong> 是一款专注于 AI 翻译的工具，<br>一键自动翻译游戏、书籍、字幕、文档等复杂长文本内容。
</div>


* **格式全能，覆盖广泛**
    * 🎮 **游戏翻译**：深度支持 Mtool, Renpy, Translator++, ParaTranzr, VNText, SExtractor 等游戏文本导出工具。
    * 📚 **多样支持**：轻松处理 I18Next 数据、Epub/TXT 电子书、Srt/Vtt/Lrc 字幕、Word/PDF/MD 文档等。

* **智能高效，省时省心**
    * 🚀 **一键操作**：一拖一点，自动识别文件与语言，无需设置。
    * ⏱️ **极速翻译**：喝杯奶茶的工夫，就能拿到译文。

* **长文优化，质量出众**
    * 🎯 **突破局限**：采用轻盈翻译格式、思维链翻译、AI 术语表、上下文关联等技术，确保长文本翻译的连贯性与准确性。
    * 💎 **质量追求**：支持基础提示、角色介绍、背景设定、翻译风格等提示词调整，拥有[双子星翻译](https://github.com/NEKOparapa/AiNiee/wiki/%E5%8F%8C%E5%AD%90%E6%98%9F%E7%BF%BB%E8%AF%91%E4%BB%8B%E7%BB%8D)功能，满足对翻译质量有更高要求的用户。

---

## AiNiee三步走 📢

* **第一步：配置接口**
  > <img src="https://raw.githubusercontent.com/NEKOparapa/AiNiee/main/Example%20image/三步走/第一步.png">

  - 在线接口：需付费但性价比很高，无显卡要求，全语言支持，[接口设置说明 - DeepSeek](https://github.com/NEKOparapa/AiNiee/wiki/QuickStartDeepSeek)
  - 在线接口：同上，如果Deepseek官网无法正常使用，可换该接口，[接口设置说明 - 火山引擎](https://github.com/NEKOparapa/AiNiee/wiki/QuickStartHuo)

* **第二步：项目设置**
  > <img src="https://raw.githubusercontent.com/NEKOparapa/AiNiee/main/Example%20image/三步走/第二步.png">
  
  - API接口平台：选择你第一步设置的接口名字<br>
  - 输入文件夹：将原文文件单独放置新的文件夹，并将该文件夹拖入框内。小说、字幕、文档可直接进行翻译，游戏需要文本提取工具进行配合。<br>

* **第三步：开始翻译**

  > <img src="https://raw.githubusercontent.com/NEKOparapa/AiNiee/main/Example%20image/三步走/第三步.png">

  - 点击开始按钮，剩下等待任务的完成。

  - [AiNiee下载地址](https://github.com/NEKOparapa/AiNiee/releases)

---


<details>
<summary>
  
## 游戏翻译[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#游戏翻译)
</summary>


<details>
<summary> 

### 工具准备
</summary>

 * **`📖游戏文本提取工具`**

      |工具名|介绍|项目类型|
      |:----:|:-----:|:-----:|
      |[Mtool](https://afdian.com/p/d42dd1e234aa11eba42452540025c377)|上手简单，推荐新人使用|Mtool导出文件|
      |[ParaTranzr](https://paratranz.cn/projects)|上手中等，功能强大，推荐大佬使用|ParaTranzr导出文件|
      |[RenPy SDK](https://www.renpy.org/latest.html)|上手中等，功能强大，推荐大佬使用|renpy导出文件|
      |[Translator++](https://dreamsavior.net/download/)|上手中等，功能强大，推荐大佬使用|T++导出文件或Trans工程文件|
      |[SExtractor](https://github.com/satan53x/SExtractor)|上手复杂，功能强大，推荐大佬使用|Mtool或者VNText导出文件|


 * **`🚡术语表预提取工具`**

      |工具名|说明|
      |:----:|:-----:|
      |[小说工具箱](https://books.fishhawk.top/workspace/toolbox)|术语表辅助制作工具|
      |[KeywordGacha](https://github.com/neavo/KeywordGacha) |使用 AI 技术来自动生成实体词语表的翻译辅助工具|


 * **`🧰本地模型运行工具`**

      |工具名|说明|
      |:----:|:-----:|
      |[Sakura_Launcher_GUI](https://github.com/PiDanShouRouZhouXD/Sakura_Launcher_GUI)|Sakura模型的专属GUI启动器|
      |[OneClickLLAMA](https://github.com/neavo/OneClickLLAMA) |一键运行 Qwen2.5 SakuraLLM 等本地 LLM 模型|
      |[LM Studio](https://lmstudio.ai/download) |一个本地部署大语言模型（LLM）平台，致力于简化LLM的使用和管理。|
      |[ollama](https://ollama.com/) |开源跨平台大模型工具 |


</details>



<details>
<summary>
  
### 翻译教程
</summary>

 * **`📺游戏翻译视频教程`**

      |视频链接|说明|
      |:----:|:-----:|
      |[Mtool教程](https://www.bilibili.com/video/BV1h6421c7MA) |初次使用推荐观看|
      |[Translator++教程](https://www.bilibili.com/video/BV1LgfoYzEaX/?share_source=copy_web&vd_source=b0eede35fc5eaa5c382509c6040d6501)|初次使用推荐观看|
      |[Wolf游戏教程](https://www.bilibili.com/video/BV1SnXbYiEjQ/?share_source=copy_web&vd_source=b0eede35fc5eaa5c382509c6040d6501)|初次使用推荐观看|
      |[人名读取教程](https://www.bilibili.com/video/BV1j1VyzqERD/?share_source=copy_web&vd_source=b0eede35fc5eaa5c382509c6040d6501)|进阶翻译推荐观看|

 * **`🎫游戏翻译图文教程`**

      |视频链接|说明|
      |:----:|:-----:|
      |[Mtool教程](https://github.com/NEKOparapa/AiNiee/wiki/%E6%B8%B8%E6%88%8F%E7%BF%BB%E8%AF%91%E2%80%90Mtool) |适合新人，懒人翻译RPG,RenPY,Krkr等游戏，进行外挂式翻译|
      |[Translator++教程](https://github.com/NEKOparapa/AiNiee/wiki/%E6%B8%B8%E6%88%8F%E7%BF%BB%E8%AF%91%E2%80%90Translator--%EF%BC%88%E5%B7%A5%E7%A8%8B%E6%96%87%E4%BB%B6%E7%89%88%EF%BC%89)|适合翻译RPG,RenPY,Krkr等等游戏，进行内嵌式翻译|
      |[Paratranz教程](https://github.com/NEKOparapa/AiNiee/wiki/%E6%B8%B8%E6%88%8F%E7%BF%BB%E8%AF%91%E2%80%90Paratranz)|适合翻译各类大型游戏的MOD|
      |[StevExtraction教程](https://github.com/NEKOparapa/AiNiee/wiki/%E6%B8%B8%E6%88%8F%E7%BF%BB%E8%AF%91%E2%80%90StevExtraction)|适合翻译RPGmakerMZ/MZ游戏|
      |[Unity翻译教程](https://zhuanlan.zhihu.com/p/1894065679927313655)|适合翻译unity游戏|
      |[综合游戏翻译超详细教程](https://www.notion.so/AI-1d43d31f89b280f6bd61e12580652ce5?pvs=4)|适合翻译各类游戏，制作高质量的内嵌补丁|

</details>


</details>

---

<details>
<summary>
  
## 功能说明[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#功能说明)  
</summary>



<details>
<summary>
  
### 设置说明
</summary>

- [功能 ‐ 接口管理](https://github.com/NEKOparapa/AiNiee/wiki/%E5%8A%9F%E8%83%BD%E2%80%90%E6%8E%A5%E5%8F%A3%E7%AE%A1%E7%90%86)
- [功能 ‐ 双子星翻译](https://github.com/NEKOparapa/AiNiee/wiki/%E5%8F%8C%E5%AD%90%E6%98%9F%E7%BF%BB%E8%AF%91%E4%BB%8B%E7%BB%8D)

</details>

  

<details>
<summary> 

### 表格说明
</summary>

- [表格 - AI术语表](https://github.com/NEKOparapa/AiNiee/wiki/%E8%A1%A8%E6%A0%BC%E2%80%90AI%E6%9C%AF%E8%AF%AD%E8%A1%A8%E4%BB%8B%E7%BB%8D)
- [表格 - AI禁翻表](https://github.com/NEKOparapa/AiNiee/wiki/%E8%A1%A8%E6%A0%BC%E2%80%90AI%E7%A6%81%E7%BF%BB%E8%A1%A8%E4%BB%8B%E7%BB%8D)
- [表格 - 文本替换](https://github.com/NEKOparapa/AiNiee/wiki/%E8%A1%A8%E6%A0%BC%E2%80%90%E6%96%87%E6%9C%AC%E6%9B%BF%E6%8D%A2%E4%BB%8B%E7%BB%8D)
    
</details>



<details>
<summary>
  
### 插件说明
</summary>

- [插件 - 语言过滤器](https://github.com/NEKOparapa/AiNiee/wiki/%E6%8F%92%E4%BB%B6%E2%80%90LanguageFilter)
- [插件 - 文本规范器](https://github.com/NEKOparapa/AiNiee/wiki/%E6%8F%92%E4%BB%B6%E2%80%90TextNormalizer)

</details>



<details>
<summary> 

### 其他说明
</summary>

* ` 多key轮询`
  >如果想使用多个key来分担消耗压力，根据key数量进行加速翻译，请使用同类型账号的key，而且输入时在每个key中间加上英文逗号，不要换行。例如：key1,key2,key3

* ` 批量文件翻译`
  >把所有需要翻译的文件放在输入文件夹即可，也支持多文件夹结构

* ` 配置迁移`
  >配置信息都会存储在resource的config.json中，下载新版本可以把它复制到新版本的resource中。

</details>


</details>



---

<details>
<summary>

## 贡献指南[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#贡献指南)  
</summary>


* **`开发增强插件`**: 请根据[插件编写指南](https://github.com/NEKOparapa/AiNiee/blob/main/PluginScripts/README.md)进行开发更强功能插件

* **`改进或增加支持文件`**: 需要有一定的代码编程能力，拉取源码进行改进。文件具体读取代码在ModuleFolders\FileReader与FileOutputer文件夹中。[读写器系统编写指南](https://github.com/NEKOparapa/AiNiee/blob/main/ModuleFolders/FileAccessor/README.md)。UI支持在UserInterface\Setting的ProjectSettingsPage。

* **`完善正则库`**: 正则库的完备将极大帮助游戏内嵌工作的进行，并利好下一次游戏翻译工作和造福其他翻译用户，正则库在[Resource\Regex](https://github.com/NEKOparapa/AiNiee/blob/main/Resource/Regex/regex.json)文件夹中

* **`改进界面翻译`**: 多语言界面的UI文本可能翻译不够准确合适，可以提交你的修改意见，或者直接进行修改。本地化文本在[Resource\Localization](https://github.com/NEKOparapa/AiNiee/tree/main/Resource/Localization)文件夹中

</details>


---

## 特别声明[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#特别声明)   
AiNiee能够不断发展迭代至今，其关键功能框架均源于项目创立以来的持续个人研发、用户反馈建议以及大佬们PR的共同努力与创造。
这是两年以来一个不断摸索、持续改进、共同构筑的过程，才形成了AiNiee如今相对成熟和完整的AI翻译体系。
请大家在使用和学习之余，尊重开源精神，署名来源项目，并不忘了给项目点个star。

该款AI翻译工具仅供个人合法用途,任何使用该工具进行直接或者间接非法盈利活动的行为,均不属于授权范围,也不受到任何支持和认可。
