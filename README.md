# 书名：《java解惑》, "Java Puzzlers"
* 本书官网 http://javapuzzlers.com/ (Joshua Bloch and Neal Gafter)
* 本书包含了95个有关Java及其类库设计的缺陷和陷阱的谜题，其中大多数采用短程序的形式，这些程序的实际行为与其代码字面表达大相径庭。
* 书中每个谜题之后给出了详细的解释，这些解释不是对程序行为的简单解释，而是展示了如何一劳永逸地避免底层的缺陷和陷阱。
* 本书示例代码以JDK 1.5为基础；本工程代码以 JDK 1.8 为基础。
* 本工程在Eclipse + Gradle Plugin的基础上构建的代码。

# 代码权限说明
* 最近重读此书，正好[原作者官网](http://javapuzzlers.com)提供了本身所附的代码的[下载链接](http://javapuzzlers.com/java-puzzlers.zip)。GitHub上正好有热心人提供了[现成的代码仓库](https://github.com/ioanbsu/java-puzzlers)，因此直接fork了一份。
* 感谢原作者的辛苦工作。重要的是请尊重原作者对代码的产权。如需使用请与原作者联系。
* 本工程代码是在原作者代码基础上进行了重构，以符合自己的代码习惯。目的仅在于学习。

# 仓库使用说明
* 原仓库只有master一个分支，为了保持与原仓库同步，保留master仓库，无特别情况下不在此分支修改。
* 派生fork仓库在master 分支基础上新建两个分支：main 和 develop
    main分支 -------> 是自己修改版本的分支，不能直接修改
    develop分支 ----> 仅供开发使用，开发完成后合并到main 分支
* 其他分支仅供特别情况下使用，主要是临时分支，其任务完成后直接删除。
