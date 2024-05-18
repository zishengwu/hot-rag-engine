# 前言
本项目搜集了一些开源的基于LLM的RAG（Retrieval-Augmented Generation）框架，旨在吸纳业界最新的RAG应用方法与思路。如有错误或者意见可以提出，同时也欢迎大家把自己常用而这里未列出的框架贡献出来，感谢~

# RAG应用框架
 1.  RAGFlow
 - 项目地址：https://github.com/infiniflow/ragflow
 - 简介：RAGFlow 是一款基于深度文档理解构建的开源 RAG（Retrieval-Augmented Generation）引擎。RAGFlow 可以为各种规模的企业及个人提供一套精简的 RAG 工作流程，结合大语言模型（LLM）针对用户各类不同的复杂格式数据提供可靠的问答以及有理有据的引用。
 - 特性：OCR、**内置多种文档切分模板**、文档切分可视化并且可修改、兼容多种文档数据类型
 - 架构：
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/c34b905634e04be0adfd2450be41e4cb.png#pic_center)

 - 硬件要求：CPU >= 4 核、RAM >= 16 GB、Disk >= 50 GB、Docker >= 24.0.0 & Docker Compose >= v2.26.1

 
2. QAnything 
- 项目地址： https://github.com/netease-youdao/QAnything
 - 简介：QAnything ( Q uestion based on Anything ) 是贡献支持任何格式文件或数据库的本地知识库问答系统，可断网安装使用。您的任何格式的本地文件都可以往里扔，即可获得准确、快速、靠谱的问答体验。
 - 特性：支持离线安装使用、**跨语种问答**、**粗排和精排的二阶段召回**  
 - 架构：
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/d34724e9c483434dbf88896885b839d8.png#pic_center)

 - 硬件要求：最低CPU即可；使用GPU环境需要NVIDIA GPU Memory	>= 4GB (use OpenAI API) & Docker Desktop >= 4.26.1（131620）
 
3. open-webui
- 项目地址：https://github.com/open-webui/open-webui

 - 简介：Open WebUI 是一个可扩展、功能丰富且用户友好的自托管 WebUI，旨在完全离线操作。它支持各种 LLM 运行程序，包括 Ollama 和 OpenAI 兼容的 API。
 - 特性：**原生支持Ollama**、**支持安装和卸载模型**、**支持多模态模型**、**支持切换模型**、**多用户管理**
 - 架构：
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/413e61ac41fb4c1d981194df467de82f.gif#pic_center)

 - 硬件要求：最低CPU即可，使用GPU环境需要NVIDIA GPU Memory	>= 4GB (取决于使用Ollama的模型大小)
 
 4. FastGPT

- 项目地址：https://github.com/labring/FastGPT
 
 - 简介：FastGPT 是一个基于 LLM 大语言模型的知识库问答系统，提供开箱即用的数据处理、模型调用等能力。同时可以通过 Flow 可视化进行工作流编排，从而实现复杂的问答场景！
 - 特性：**支持应用编排**、**免登录分享**、**支持接入飞书、企业微信等应用**
 - 架构：
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/4a0319a9d1834a3aae3b219557bb9128.webp#pic_center)

 - 硬件要求：CPU >= 2 核、RAM >= 4 GB用于安装数据库，GPU取决于使用的模型
 
 5. Langchain-Chatchat
 - 项目地址：https://github.com/chatchat-space/Langchain-Chatchat
 
 - 简介：基于 ChatGLM 等大语言模型与 Langchain 等应用框架实现，开源、可离线部署的检索增强生成(RAG)大模型知识库项目。
 - 特性：算是比较早期的RAG框架了，使用的基本全是python的框架。该项目是一个可以实现**完全本地化**推理的知识库增强方案, 重点解决数据安全保护，私域化部署的企业痛点。支持市面上主流的本地大语言模型和Embedding模型，支持开源的本地向量数据库。 本开源方案采用Apache License，可以**免费商用，无需付费**。
 - 架构：
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/d891ea4ac20e4827bea7845a34de0990.png#pic_center)
- 硬件要求：对GPU要求较高


 6. MaxKB
 - 项目地址：https://github.com/1Panel-dev/MaxKB

 - 简介：MaxKB 是一款基于 LLM 大语言模型的知识库问答系统。MaxKB = Max Knowledge Base，旨在成为企业的最强大脑。

 - 特性：开箱即用，支持直接上传文档、自动爬取在线文档；支持零编码快速嵌入到第三方业务系统；支持对接主流的大模型，包括 Ollama 本地私有大模型以及API调用

 - 架构：
  前端：Vue.js
  后端：Python / Django
  LangChain：LangChain
  向量数据库：PostgreSQL / pgvector
  大模型：Azure OpenAI、OpenAI、百度千帆大模型、Ollama、通义千问、Kimi、智谱 AI、讯飞星火
 
 - 硬件要求：

  操作系统：Ubuntu 22.04 / CentOS 7 64 位系统
  CPU/内存： 推荐 2C/4GB 以上
  磁盘空间：100GB


                            



