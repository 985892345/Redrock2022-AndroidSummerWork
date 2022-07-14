# REDROCK 移动部门 Android 2022年暑假考核

## 📝写在前面

紧张的课件终于结束了，迎来了我们的开发考核！👏👏👏

不知不觉中，你已经在网校学习了一年了。从最开始的“Hello World”，到现在能够在指尖跳跃的 APP，从软件的使用者，到软件的开发者。一年里你上过的每一节课，做过每一次作业，~~掉过的每一根头发~~，熬过的每一个夜，换来的不仅仅是别人嘴中的一句“大佬”，还有自己肉眼可见的进步。

## 考核形式

在一周时间内完成一个较完整的 APP，后面给出一些参考接口，**允许写自己想写的应用（但必须要多个网络请求，且不允许写已经写过或正在写的项目，违反即作为作弊处理）**

- 7号休息一天
- 8号 - 14 号（7天）:发布选题，根据选题写课件
- 15号 - 26号（12天）：发布个人考核文档，请在这 12 天内写完功能
- 26号网校会举行开工仪式，所有留校的都得到场，预计会耽搁半天时间（**请注意该点**）
- 26号 **18 点前** 公开你的仓库并**发布一个 release**，要求包含正式版 apk，晚上叶师傅会讲最后一节 `Android` 课
- 27号 - 30号（4天）：讲课，在这 4 天内允许修 bug，但**禁止添加新功能**，谈心时会进行比对
- 31号谈心
- 1号 - 开学：维护掌邮、开发掌邮新功能

（留给后人：21级考核是先把讲课选题发布了，后面14号中午才发的这个文档）

### 注意事项

- 除了最开始的7天准备课件以外，在讲课前仍可以完善课件，但请合理分配课件与考核的时间
- 讲课前（26号前）个人考核截止，之后的4天讲课时间**禁止添加新功能**

## APP 要求

### 基本要求

- API 兼容到 Android5.0（API 21）
- 只能使用 `kotlin`，允许存在小部分 `java` 代码
- 代码中**重要函数和变量**需要有注释，不要求全部都写
- **`Github` 的 commit 记录最长间隔两天**
- 完整的 README，必须包含：
  - APP 简要介绍（背景、功能、使用步骤等）附 Gif 图片
  - 使用到的比较重要的技术及知识点
  - 心得体会
- 考核期间如果遇到**运行时 bug**，原则上**不能向学长求助**，如果是无法编译问题，百度后仍无法解决则可以在大群里面提问
- 请使用自己擅长的技术，**不熟练就谨慎使用**，比如多模块
- 因为有 12 天开发 + 4 天改 bug，所以要求谈心时的最终版本无明显闪退 bug（**记得做好断网时的网络请求出错处理**）

### 依赖要求

- **禁止**使用除以下库外的其他库，可使用的库如下：
  - 所有 `google` 库
  - 所有 `android` 以及 `androidx` 库
  - 所有 `jetbrains` 库（协程包含在这里面）
  - 部分第三方库
    - [`ARouter`](https://github.com/alibaba/ARouter)（如果不熟练多模块开发，就不要尝试）
    - [`Glide`](https://github.com/bumptech/glide)
    - [`Lottie`](https://lottiefiles.com/blog/working-with-lottie/getting-started-with-lottie-animations-in-android-app)
    - [`Retrofit`](https://github.com/square/retrofit)
    - [`Okhttp`](https://github.com/square/okhttp)
    - [`Gson`](https://github.com/google/gson)
    - [`Rxjava`](https://github.com/ReactiveX/RxJava)
    - [`RxPermissions`](https://github.com/tbruyelle/RxPermissions)：一个权限申请库
    - [`PhotoView`](https://github.com/Baseflow/PhotoView)：一个专门查看图片的库
    - 如果你做的项目需要使用到视频播放的功能，允许使用播放视频的第三方库（因为官方库有坑）
    - 如果对依赖有特殊要求，请在大群里提问
    - 如果使用自己的依赖库，有如下要求
      - 不能是 fork 来的
      - 绝大部分代码是自己所写
- 由于本次考核需要衡量你们接手掌邮的能力，所以**强烈不推荐**使用 `compose`，掌邮目前明确禁止使用 `compose`
- `Banner`（轮播图）请自己实现

### 设计要求

- MVVM 架构，允许在简单网络请求时不设计仓库层
- 不建议全部使用 `Flow`，`Rxjava` 仍然很重要（该点不强制要求）
- 需包含网络请求
- 好看的 UI

### 特殊要求

- 需要公开你的仓库，**从考核第一天开始**
- 如果不想公开，可以在私有仓库的情况下把我们设置成贡献者
  - 点击 Settings - Collaborators - Add people
  - 输入以下学长的 github 名字
    - 郭：985892345
    - 廖：SnowOwlet
- 别忘了前面要求的 **`Github` 的 commit 记录最长间隔两天**



## 可选接口

请查看 [接口收集文档](./接口收集文档.md)



## 考后须知

按正常流程，考核完后每人都会有一场与多位学长面对面的谈心工作，请轻松对待

本次考核通过的同学将参加接下来为期一个月的暑假工作



## 暑假工作

时间：1号至开学

内容：

- 分配 ~~(甩锅)~~ 掌邮的开发及维护工作，部分人进行掌邮新需求开发，部分人修掌邮 bug
- 准备下一届学弟的课件（学妹的任务光荣交给你们了，Android 部门单身三年了）



## 其他问题

**考核完后可以回家吗？**

原则上不能回家

**学校让暑假做社会实践怎么办？**

社会实践在暑假留校后就可以在网校开证明，考核没有通过的也能开



## 其他

为方便后来人快速找到其他考核，故整理了一下

22 年暑假考核：https://github.com/985892345/Redrock2022-AndroidSummerWork

22 年期中考核：https://github.com/OkAndGreat/Mid-Term-Exam-2022

22 年寒假考核：https://github.com/SnowOwlet/Redrock2022-AndroidWinterWork

21 年暑假考核：因为军训时间不够，所以考核为两人一组共 5 组写掌邮积分商城

21 年期中考核：[Android-2021-中期考核](./其他届的考核/Android-2021-中期考核.pdf)

21 年寒假考核：https://github.com/SpreadWater/RedRockWinnterWork

20 年暑假考核：两周时间内个人考核+准备课件，考核内容自由发挥

20 年期中考核：https://github.com/Override0330/Mid-Term-Exam-2020

20 年寒假考核：https://github.com/Override0330/WinterExam-Android-2020

19 年暑假考核：未知，猜测也是跟 20 年一样

19 年期中考核：https://github.com/Hosigus/Mid-Term-Exam-2019

19 年寒假考核：https://github.com/Hosigus/WinterExam-Android-2019

18 年期中考核：https://github.com/SmallTashi/MRedrock-Exam-2018 （这应该是 fork 来的，源仓库已经被删除）

后面基本上找不到了



**重要的事情说三遍：**

### 不要熬夜！

## 不要熬夜！

# 不要熬夜！

### 严禁通宵！

## 严禁通宵！

# 严禁通宵！

