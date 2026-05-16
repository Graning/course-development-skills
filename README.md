# Course Development Skills

这个仓库用于管理课程开发流程相关的 Codex skills。当前上传范围只包含课程开发与学习评估所需的 skill。

## Skills

1. `topic-analysis` - 课题分析：判断课题是否适合做成课程，明确业务目标、学员对象、痛点、场景和内容边界。
2. `course-objectives` - 目标设定：把课题分析结果转化为可观察、可衡量、可评估的课程目标。
3. `course-structure` - 结构搭建：根据课题分析和课程目标搭建模块、层级、重难点和课程逻辑。
4. `content-organization` - 内容组织：筛选、归类、裁剪和排序课程内容，让内容服务学员工作应用。
5. `process-design` - 教学过程设计：把课程模块转化为可授课的流程、活动、时间分配和评估方式。
6. `expert-interview-outline` - 专家访谈提纲设计：围绕课题分析、课程目标和课程结构，设计专家访谈问题和 STAR 追问话术。
7. `quiz-generation` - 试题生成：根据课程目标、核心内容、重难点和试卷要求生成课后考试题、随堂测试题、答案与解析。

## Recommended Workflow

课程设计建议按下面顺序使用：

1. 课题分析
2. 目标设定
3. 结构搭建
4. 内容组织
5. 教学过程设计

如需从专家经验中萃取课程内容，可在完成课程结构后使用 `expert-interview-outline`，再把访谈结果回填到内容组织和教学过程设计中。

如需检验学习效果，可在课程目标、内容组织和教学过程稳定后使用 `quiz-generation` 生成课后考试题或随堂测试题。

## Update

修改 skill 后，使用：

```bash
git status
git add .agents/skills README.md .gitignore
git commit -m "Update course development skills"
git push
```
