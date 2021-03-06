## code review

### code review的目的
1. 提高代码质量
2. 提前发现bug
3. 统一团队代码规范
4. 营造工程师交流的氛围

### 什么情况下需要code review?
哪些团队需要？
1. 技术驱动型团队: 底层逻辑多，功能路径难以被测试覆盖
2. 公共服务型团队：质量问题影响范围较大
3. 测试缺失型团队：没有测试环境，只得加强开发自检工作
4. 新人密集型团队：新人代码可读性较差，需要组织及时纠正
   
哪些团队不需要？
1. 不认同型团队：领导和骨干均不任何code review的价值
2. 疲于应付型团队：大量需求实现、变更和优化工作，没有时间进行code review
3. 创新型团队：工作重点是快速原型推向市场验证项目价值，需要足够敏捷

### code review有哪些优点和缺点？

### 基于git工作流下如何进行code review?
> 具体的规则可能每个部门各不相同，比如有的部门给每个组件规定几个owner，改到那块代码必须找至少一个owner做review。有的部门还规定每次code review至少要有一个senior级别以上的码农参与，等等