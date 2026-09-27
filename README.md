# Culpachain
## 许可说明 · License Notice

> **本仓库使用自定义许可，不是 MIT / Apache-2.0**。平台显示为 `Other`（NOASSERTION），
> 属识别算法的正常结果，**不代表本仓库处于无许可状态**。

- **权利状态**：全部内容保留所有权利（All Rights Reserved）。未经书面许可，
  不得复制、改编、再分发、公开传播或用于衍生作品。
- **可否引用**：可以。允许在**注明出处**的前提下引用与学术、公共讨论；
  引用时请同时标注仓库名、原文链接 `https://github.com/zhaoxinghua09-cell/culpachain`
  与权利人「赵兴华 / Steven Zhao·China」。
- **完整条款**：见仓库根目录 [LICENSE](LICENSE)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **免责**：本仓库内容不构成法规意见或注册代理服务；关键数据以监管机构最新发布为准。

---


**多智能体问责治理 · Multi-Agent Accountability**

> A coined theoretic term in the **LGD (凡自治之物 · 全程治理论)** theory stack.
> Theory-layer zero-collision: the descriptive English name is settled by others; the coined term is ours.

---

## Definition

**Culpachain** — the accountability chain across a **chain of autonomous agents**: when several agents act in sequence or in concert, which one answers?

Single-agent governance has a simple answer — the agent's owner is liable. Multi-agent systems break this. Agent A plans, agent B executes, agent C retries after failure, and the outcome is an emergent product of the chain. The harm is real; the culprit is **distributed across the chain**.

Culpachain holds that accountability must be **chain-resolved**, not agent-resolved:

- **Registry (LGD-I)** — every link in the chain is registered with its role, authority scope, and handoff boundary.
- **Evidence (LGD-II)** — every handoff leaves a trace: input, decision, output, and the *delegation act* itself.
- **Gate (LGD-III)** — responsibility is gated at handoff: a link may not accept a task whose authority it cannot discharge, and may not pass on a task whose outcome it cannot account for.

## Why the term was coined

*Multi-Agent Accountability* is already claimed in the literature — *accountability boundaries theory* and the *Accountable AI Framework (AAF)* occupy the descriptive phrase. The theory layer is closed to newcomers using that name.

**Culpachain** names the *structural object* — the chain along which culpability is distributed and must be re-resolved — rather than competing for the phrase. The descriptive subtitle carries search; the coined term carries the claim.

## Position in the stack

| | |
|---|---|
| **Angle ID** | TH-ANG-003 |
| **Domain code** | ANG (cross-domain governance angles) |
| **Parent** | TH-ANG-000 跨域治理角度矩阵 (Cross-Domain Governance Angle Matrix) |
| **Related** | LGD-II 有证 (six evidence artifact classes) · audit-trail-keeper |
| **Collision verdict** | Theory layer 🔴🔴 (accountability boundaries theory + AAF) → Coined term 🟢 |

## Real-world referents (mapped, not invented)

| Domain | Referent | Mapping |
|---|---|---|
| Agent protocols | ADCS specification | delegation and identity in agent chains |
| Agent messaging | IETF drafts (3) on agent interoperation | handoff trace format |
| Frontier labs | DeepMind multi-agent safety work | emergent-behaviour accountability |
| Runtime monitoring | SentinelAgent | chain-level observation |
| Product liability | joint-and-several liability doctrines | the legal analogue for distributed fault |

## Citation

If you use or cite this term, please reference:

> Zhao, S. (2026). *Culpachain: Multi-Agent Accountability — LGD Angle Matrix #3*. SynomosAI.
> https://github.com/zhaoxinghua09-cell/culpachain

## Theory stack

- **LGD — 凡自治之物 · 全程治理论 (Lifecycle Governance Doctrine)** — the parent framework: *有籍 · 有证 · 有门禁* (registered · evidenced · gated) across the full life of an autonomous thing.
- **Cross-domain angle matrix** — 5 angles × 13+ domains; this repo is angle #3.
- Companion angles: Terminance · Mnemoship · Runtigil · Assurability.

## Author

**赵兴华 / Steven Zhao·China**
ORCID [0009-0001-0512-1237](https://orcid.org/0009-0001-0512-1237) · https://medxpert.cn

Proposed and named 2026-09-10. Co-created with Lao Paidang (老拍档), AI research partner.
Human authorship, judgment, and final responsibility rest with the author.

## License

Theory names and definitions — all rights reserved by the author. Any citation, use, or extension shall trace back to this source.
