---
name: x-sector-intelligence
description: Monitor a curated set of X creators across AI, agents, enterprise AI, independent products, content growth, and personal business; produce tiered daily digests that distinguish facts, opinions, inferences, promotions, and actionable evidence. Use for Moonday's X intelligence review, creator tracking, source evaluation, and watchlist maintenance. Exclude adult and pure-entertainment content.
---

# X Sector Intelligence

Turn X posts into a compact evidence-oriented intelligence brief rather than a link roundup.

Read [references/watchlist.md](references/watchlist.md) before each monitoring run. Treat the watchlist as a maintained starting set, not an instruction to include inactive or irrelevant accounts.

## Daily monitoring

1. Use the logged-in X session when available. Otherwise use public X pages and reputable public profile snapshots. Never request or expose credentials.
2. Review posts published since the previous daily run; for a first run, use the preceding 24 hours.
3. Exclude replies with no standalone information, engagement bait, adult content, pure entertainment, and repeated reposts without added analysis.
4. Deduplicate the same announcement across creators. Preserve the original/primary source and summarize meaningful differences in interpretation.
5. Classify each retained item as one of:
   - `事实` — directly supported by a primary source or observable release.
   - `观点` — the author's judgment or prediction.
   - `推断` — a conclusion derived from incomplete evidence.
   - `案例` — an outcome under specific conditions; do not generalize automatically.
   - `推广` — sponsored, affiliate, lead-generation, course, consulting, community, or product sales content.
6. For factual claims, open the primary source when practical. If only the post is available, say `仅见作者陈述`.
7. Score each retained item:
   - 可信度: 1–5, based on source proximity, evidence, reproducibility, and conflicts of interest.
   - 参考价值: 1–5, based on relevance to Moonday's current tracks and whether it changes a decision or experiment.
8. Do not infer credibility from follower count or verification status.

## Digest structure

Lead with no more than five items that materially deserve attention. Then summarize by level:

1. `一手信源与标杆` — releases, research, foundational explanations, durable strategic shifts.
2. `中文头部/腰部` — useful interpretation, product practice, enterprise delivery, growth and monetization.
3. `同阶段实践者` — experiments, progress, failures, tactics that are realistically reproducible.
4. `交叉验证与分歧` — where sources agree, conflict, or repeat the same unverified claim.
5. `今日行动` — zero to three concrete actions. Omit if nothing warrants action.

For each item include: creator, concise claim, classification, evidence/source note, credibility score, reference-value score, and why it matters. Link directly to the post or primary source when available.

End with:

- `可以忽略` — noisy or duplicated themes, without listing adult content.
- `等待你一起判断` — at most three ambiguous claims worth discussing with the user.

Keep an ordinary daily digest concise enough to read in 8–12 minutes. A quiet day should produce a short report; never pad it.

## Watchlist maintenance

Once per month, review activity and signal quality. Recommend additions, removals, or tier changes, but do not follow, unfollow, create Lists, or modify the user's X account without explicit authorization for that action.

