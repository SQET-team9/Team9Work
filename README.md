# 项目简介
2023年大三第一学期软件质量与评测技术  
第9组任务仓库  
组名：开心超人组  
组长：李 明  
组员：张泽渊、呼延泽、朱鎔彬、马吉龙、李孙鹏  
# 目录
- [项目简介](#项目简介)
- [目录](#目录)
- [一、项目介绍](#一项目介绍)
- [二、测试过程](#二测试过程)
  - [测试内容](#测试内容)
    - [功能度测试](#功能度测试)
      - [模块0 Trie（一个数据结构）](#模块0-trie一个数据结构)
      - [模块1 缓存池管理](#模块1-缓存池管理)
      - [模块2 B+树索引](#模块2-b树索引)
    - [易用性测试](#易用性测试)
      - [评估项：](#评估项)
    - [用户文档检查](#用户文档检查)
  - [测试方法](#测试方法)
    - [静态测试方法](#静态测试方法)
    - [动态测试方法](#动态测试方法)
- [三、任务分工](#三任务分工)
- [四、会议记录](#四会议记录)
  - [时间：2023.11.14](#时间20231114)
    - [会议内容](#会议内容)
    - [会议成果](#会议成果)
- [五、进行评测需要的文档](#五进行评测需要的文档)
  - [项目需求文档](#项目需求文档)
  - [开发者文档](#开发者文档)
- [六、尚未解决的问题](#六尚未解决的问题)
- [七、参考资料](#七参考资料)

# 一、项目介绍
使用cmake进行管理
# 二、测试过程
## 测试内容
### 功能度测试
#### 模块0 Trie（一个数据结构）
插入、取出、并发测试
#### 模块1 缓存池管理
新建缓存页、获取缓存页、取消绑定缓存页、flush缓存页、页的替换功能lru-k算法
#### 模块2 B+树索引
插入索引、删除索引、根据索引键获取到索引值、并发测试
### 易用性测试
#### 评估项：
1. 注释清晰：  
内部代码有注释，无错别字
2. 代码复用性强
3. 命名规范
4. api接口

### 用户文档检查

## 测试方法
### 静态测试方法
用clang检查代码规范
### 动态测试方法
谷歌测试框架gtest  
LLVM Address Sanitizer测试内存泄露  
用gdb调试  



# 三、任务分工
|任务名     |完成者        |DDL        |验收方式    |
|----------|--------------|-----------|-----------|
|需求文档翻译整理（模块0）| xxx|xxx|xxx|
|需求文档翻译整理（模块1）| xxx|xxx|xxx|
|需求文档翻译整理（模块2）| xxx|xxx|xxx|
|xxx| xxx|xxx|xxx|
|xxx| xxx|xxx|xxx|
|xxx| xxx|xxx|xxx|
|xxx| xxx|xxx|xxx|
# 四、会议记录
## 时间：2023.11.14
参与者：李 明、张泽渊、朱鎔彬、马吉龙、李孙鹏  
地点：综B302  
### 会议内容
组长李明大致介绍了项目的情况  
### 会议成果
1. 组员基本明确了对软件测试项目的方向
2. 形成了项目的第一版汇总的README文档，由张泽渊进行编写
# 五、进行评测需要的文档
## 项目需求文档
## 开发者文档
1. API 说明
2. 安装和配置指南
3. 用户案例和示例
4. 数据模型和结构

# 六、尚未解决的问题
1. 有一个小bug不知道要不要写

# 七、参考资料
1. [Markdown 官方教程](https://markdown.com.cn/ "点击跳转")
