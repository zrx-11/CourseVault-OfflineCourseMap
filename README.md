# 资源核验说明（重要，请先读）

本离线包是「名校公开课学习路径地图」的纯本地版。**必须说明的事实**：上一轮对话中给出的部分 GitHub 笔记链接未经核实，经逐一探测，**16 个链接中有 15 个在 GitHub 上不存在（返回 404）**，仅 1 个真实存在。本包已用「官方课程资料 / 可核实真实仓库」替换全部无效链接，替换结果如下。

## 一、链接核验结果

| 课程 | 原 GitHub 链接 | 状态 | 本包替代资源 |
|---|---|---|---|
| EE 364A 凸优化 | solversworld/convex-optimization-notes、ryancoleman/ee364a-notes | 404 不存在 | Stanford 官网 EE364a 讲义全集 23 份 + 真实仓库 PKUFlyingPig/Standford_CVX101 |
| MIT 18.100 实分析 | rmwu/18100a-notes | 404 不存在（但笔记真实存在于作者个人网站） | MIT 学生 rmwu 课堂笔记 PDF + MIT OCW 18.100A 完整课程包 |
| MIT 18.701 代数 | yuntaowu2000/notes | 404 不存在 | 暂无本地资料（官方教材为 Artin，可自行补充） |
| MIT 18.175 随机过程 | andrewliao11/mit-18.175-notes | 404 不存在 | MIT 18.615 随机过程课堂笔记 PDF + MIT OCW 18.445 课程包 |
| MIT 18.650 统计 | terrencemiao/mit-18.650-notes | 404 不存在 | 暂无本地资料 |
| EE 276 信息论 | yzhao062/ee276-notes | 404 不存在 | Stanford EE376A 课堂笔记全集 PDF（EE276 前身课程） |
| MIT 14.12 微观 | robinlyu/grad-micro-notes | 404 不存在 | MIT OCW 14.124 课程包（MWG 配套，同源） |
| Econ 202 博弈论 | llohse/game-theory-notes | 404 不存在 | 暂无本地资料 |
| Econ 210 计量 | justinmsimon/econ210-notes | 404 不存在 | 暂无本地资料 |
| MIT 15.450 金融 | hschung/mit-15.450-notes | 404 不存在 | 暂无本地资料 |
| MIT 24.500 语言哲学 | tquadrivium/An-Introduction-to-the-Philosophy-of-Language | ✅ 真实存在 | 已克隆到本地 notes/ 目录 |
| PHIL 242 知识论 | andrewwhitehead/epistemology-notes | 404 不存在 | 暂无本地资料 |
| PHIL 270 科学哲学 | ntan/phil-sci-notes | 404 不存在 | 暂无本地资料 |
| MIT 8.333 统计力学 | ccyeeh/mit-8.333-notes | 404 不存在 | MIT OCW 8.333 完整课程包 |
| AA 203 强化学习 | udion/aa203-notes | 404 不存在 | 暂无本地资料 |

## 二、本包实际收录的本地资料（均核实可下载）

| 目录 | 内容 | 来源 |
|---|---|---|
| notes/EE364A-Stanford-lectures/ | 凸优化官方讲义 23 份 PDF（含 lectures.pdf 全集） | Stanford 官网公开 |
| notes/PKUFlyingPig__Standford_CVX101/ | CVX101 作业实现 + 资源汇总仓库 | GitHub 真实仓库 |
| notes/MIT18.100A-rmwu/ | 18.100A 实分析课堂笔记 PDF | MIT 学生个人网站 |
| notes/MIT18.100A-OCW/ | 18.100A 完整课程包（讲义+作业） | MIT OCW |
| notes/MIT18.615-rmwu/ | 18.615 随机过程课堂笔记 PDF | MIT 学生个人网站 |
| notes/MIT18.445-OCW/ | 18.445 随机过程课程包（讲义+作业） | MIT OCW |
| notes/EE376A-InformationTheory-scribes/ | 信息论课堂笔记全集 PDF | Stanford 官网公开 |
| notes/MIT14.124-OCW/ | 14.124 高级微观课程包 | MIT OCW |
| notes/MIT24.900-OCW/ | 24.900 理论语言学课程包 | MIT OCW |
| notes/MIT8.06-OCW/ | 8.06 量子力学 III 课程包 | MIT OCW |
| notes/MIT8.333-OCW/ | 8.333 统计力学课程包 | MIT OCW |
| notes/MIT18.905-OCW/ | 18.905 代数拓扑课程包 | MIT OCW |
| notes/tquadrivium__An-Introduction-to-the-Philosophy-of-Language/ | 语言哲学研读仓库 | GitHub 真实仓库 |

## 三、离线使用说明

1. 解压整个 zip，保持目录结构不变。
2. 双击打开 `名校公开课学习路径地图_离线版.html`（或放入同一目录起本地服务 `python -m http.server 8000` 后访问）。
3. 页面中「本地资料」链接指向 `notes/` 下对应文件夹，双击即可打开 PDF / 课程包。
4. `katex/` 是本地公式渲染库，页面内 `$...$` / `$$...$$` 公式离线即可渲染。
5. 未收录本地资料的课程，可在包内自行放入文件后把链接指过去，或参考各校官网。

## 四、来源说明

- MIT OCW：https://ocw.mit.edu（官方开放课程，可自由下载非商业使用）
- Stanford 课程讲义：https://web.stanford.edu/class/ee364a/lectures/、https://web.stanford.edu/class/ee376a/
- MIT 学生笔记：https://people.csail.mit.edu/rmwu/
- GitHub 仓库：PKUFlyingPig/Standford_CVX101、tquadrivium/An-Introduction-to-the-Philosophy-of-Language

> 生成日期：2026-10-14
