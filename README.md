# chatgpt for gpt
- 尝试利用gpt 进一步优化原始仓库，并按照个人需求进行调整；
- 




**原始仓库来源于：https://github.com/dirk1983/chatgpt ，以下内容简介溶氧来源原始仓库

ChatGPT的横空出世真的改变了世界，用过的人都知道ChatGPT完全可以作为生产力工具应用在很多领域。可以说ChatGPT是最近几年又一个的巨大风口，目前大量投资机构和政府部门都在鼓励和支持相关行业的发展。如果您也有使用ChatGPT赚钱或创业的想法，欢迎免费进群讨论，二维码在本文最后。群里有很多志同道合的朋友一起分享资讯，分享知识，对接资源。另外请点下右上角的小星星，方便您随时找到本项目。

**本项目完全开源，是PHP版调用OpenAI的API接口进行问答的Demo，有以下特性和功能：**

1. 对PHP版本无要求，不需要数据库。核心代码只有几个文件，没用任何框架，修改调试很方便，只需要修改stream.php中的API_KEY即可使用。
2. 采用stream流模式通信，一边生成一边输出，响应速度全网最快。
3. 支持GPT-3.5-Turbo和GPT-4等各种模型（后者需要修改下默认model名称）。
4. 支持Markdown格式文本显示，如表格、代码块。对代码进行了着色，提供了代码复制按钮，支持公式显示。
5. 支持多行输入，文本框高度自动调节，手机和PC端显示都已做适配。
6. 支持一些预设话术，支持上下文连续对话，AI回答途中可以随时打断。
7. 支持错误处理，OpenAI接口返回错误时可以看到具体原因。
8. 可以实现区分内外网IP，内网直接访问，外网通过BASIC认证后可访问。
9. 可以实现输入API_KEY使用，方便分享给网友或朋友使用。
10. 服务器自动记录所有访问者的对话日志和IP地址，方便管理员查询。

**本项目定位是个人或朋友之间分享使用，轻量设计，不计划引入数据库等复杂功能。有需要的用户可以自行拿去修改，版权没有，改动不究。对于项目UI或其他功能有改进想法的朋友欢迎提交PR，或者在Issues或Discussions进行讨论。**

-----

附OpenAI官网的模型和接口调用介绍：

https://platform.openai.com/docs/models/moderation

https://platform.openai.com/docs/api-reference/chat/create

https://platform.openai.com/docs/guides/chat/introduction

https://platform.openai.com/docs/api-reference/models/list

------

