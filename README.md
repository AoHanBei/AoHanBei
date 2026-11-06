<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner.svg">
  <img src="assets/banner.svg" alt="吴昊强 · AoHanBei — 大模型应用开发：模型网关、Agent 运行时与用户记忆" width="100%">
</picture>

<p align="center">
  <a href="https://aohanbei.github.io/"><img alt="作品集 aohanbei.github.io" src="https://img.shields.io/badge/Portfolio-aohanbei.github.io-B8432B?style=flat-square&amp;logo=githubpages&amp;logoColor=white"></a>
  <a href="https://aohanbei.github.io/#open-source"><img alt="13 个已合并的上游 PR，核对于 2026-11-06" src="https://img.shields.io/badge/Open_source-13_merged_PRs-1F1B17?style=flat-square&amp;logo=github&amp;logoColor=white"></a>
  <a href="mailto:2292110346@qq.com"><img alt="邮箱 2292110346@qq.com" src="https://img.shields.io/badge/Email-2292110346%40qq.com-6B6158?style=flat-square&amp;logo=maildotru&amp;logoColor=white"></a>
</p>

## 你好，我是吴昊强

做模型网关、Agent 运行时与用户记忆的大模型应用开发，2027 届，正在找大模型应用开发岗位。

[精选项目](#精选项目) · [开源贡献](#开源贡献) · [技术方向](#技术方向) · [作品集](https://aohanbei.github.io/)

## 精选项目

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AoHanBei/ModelPort">ModelPort</a></h3>
      <p>源于实习的大模型网关，为 Claude Code、OpenAI SDK 与内部 Agent 提供统一调用入口：协议适配、确定性路由、并发幂等与预算结算。</p>
      <p>
        <img alt="Rust" src="https://img.shields.io/badge/Rust-1F1B17?style=flat-square&amp;logo=rust&amp;logoColor=white">
        <a href="https://aohanbei.github.io/projects/modelport.html"><img alt="ModelPort 案例页" src="https://img.shields.io/badge/案例页-B8432B?style=flat-square"></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AoHanBei/Memory">可演化用户记忆</a></h3>
      <p>面向长期 AI 助手的用户记忆服务，记忆可溯源、可回看、可受控更新：双时态查询、混合检索归因、反馈隔离与策略发布门禁。</p>
      <p>
        <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white">
        <a href="https://aohanbei.github.io/projects/evolvable-user-memory.html"><img alt="可演化用户记忆案例页" src="https://img.shields.io/badge/案例页-B8432B?style=flat-square"></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://aohanbei.github.io/projects/quantpilot.html">量化研究智能体</a></h3>
      <p>学习笔记（原项目 QuantPilot）：把自然语言金融研究变成可交付任务的 Data Agent，关注领域包、Worker 治理与独立质量门禁。</p>
      <p>
        <img alt="学习中" src="https://img.shields.io/badge/状态-学习中-6B6158?style=flat-square">
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/AoHanBei/aohanbei.github.io">个人作品集</a></h3>
      <p>Vite + React + TypeScript 多页面站点，项目文案逐条对应事实来源并在 CI 中校验，GitHub Actions 自动部署。</p>
      <p>
        <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white">
        <a href="https://aohanbei.github.io/"><img alt="访问作品集" src="https://img.shields.io/badge/访问-B8432B?style=flat-square"></a>
      </p>
    </td>
  </tr>
</table>

## 开源贡献

围绕 Agent 运行时与模型调用链路的可靠性提交修复与增强，每条都附带回归测试。

| 上游项目 | Stars | 已合并 PR | 代表性改动 |
| --- | --- | --- | --- |
| [DeerFlow](https://github.com/bytedance/deer-flow) | 85k+ | 5 | [#4933](https://github.com/bytedance/deer-flow/pull/4933) MCP 远程任务取消补偿，保留原始取消语义<br>[#5127](https://github.com/bytedance/deer-flow/pull/5127) 持久化循环检测事件，补齐子 Agent 审计转发 |
| [DeepTutor](https://github.com/HKUDS/DeepTutor) | 55k+ | 8 | [#1499](https://github.com/HKUDS/DeepTutor/pull/1499) 重试预算随密钥池伸缩，限流后剩余密钥都会被尝试<br>[#1492](https://github.com/HKUDS/DeepTutor/pull/1492) 定价改为精确匹配优先，修复 gpt-4o-mini 成本高估 |

完整清单按主题分组见 [作品集 · 开源贡献](https://aohanbei.github.io/#open-source)。数字核对于 2026-11-06，只统计本人提交并合并到上游的 PR。

## 技术方向

- **模型接入与 Agent 工程**：模型协议适配、工具调用、SSE 流式处理及 Agent 运行时故障排查。
- **记忆与检索**：长期记忆建模、双时态查询、混合召回、结果归因及固定评测门禁。
- **后端可靠性**：PostgreSQL 事务、请求幂等、租约协调、异步任务取消与生命周期管理，结合回归测试分析并发与一致性问题。
