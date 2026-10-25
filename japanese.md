# 🇯🇵 Japanese Learning Plan: Pranav-sama

*Created: 2026-10-25*

## 👤 Learning Profile

| | |
|---|---|
| **Name** | Pranav-sama |
| **Learning** | Japanese |
| **Native language** | English (+ Hindi) |
| **Level** | A1 (total beginner) → B1 / **JLPT N3** |
| **Target date** | April 2027 (6 months) |
| **Exam sitting** | JLPT N3, July 2027 |
| **Daily time** | 60 min |
| **Learning style** | Balanced |
| **Script** | Learning kana from scratch; romaji fades out after kana |
| **Gamification** | On 🎮 |

## 📋 Estimate

- **About 250 study hours** (A1 → A2: ~100h, A2 → B1: ~150h)
- At 60 min/day, that's roughly **7.5 months** (10% less than usual because you know Hindi)
- Japanese takes English speakers longer than most languages because of kana and kanji, so 6 months is ambitious. Consistency matters most.

### 📅 About exam dates

The JLPT is only held in **July and December**. December 2026 is too soon, so **July 2027** is the realistic sitting, about 8.5 months from the start date. That leaves time to spare beyond the estimate. The goal is still N3-level skills by April 2027, and the remaining months become the exam-prep phase.

### 🇮🇳 Your Hindi head start

Japanese and Hindi are both subject–object–verb languages, and both put small words *after* nouns instead of before them:

- 東京**に** (Tōkyō **ni**) works like दिल्ली **में** (Dillī **mẽ**), meaning "in Tokyo / in Delhi"
- 私**は**本**を**読みます (watashi **wa** hon **o** yomimasu) has the same word order as मैं किताब पढ़ता हूँ (I book read)

Most English speakers don't have this advantage.

## ⏱️ Daily Routine (60 min)

| Time | Command | What |
|---|---|---|
| 10 min | `/fluent-review` | Spaced-repetition reviews |
| 20 min | `/fluent-vocab` | Kana now, vocabulary and kanji later |
| 30 min | One of these (see below) | Skill practice |

**30-minute skill rotation:**

| Day | Command |
|---|---|
| Mon / Wed / Fri | 📝 `/fluent-writing` |
| Tue / Thu / Sat | 🗣️ `/fluent-speaking` |
| Sun | 📖 `/fluent-reading` |

**Weekly:** 📊 `/fluent-progress` to check stats (5 min)

**Anytime:** `/fluent-learn` for an adaptive mixed session

## 🏁 Milestones

| When | Target |
|---|---|
| **Weeks 1–3** | Hiragana ✅ then katakana ✅; start fading out romaji |
| **Month 1** | ~150 words, polite です/ます sentences, the basic particles は・が・を・に・で |
| **Month 3** | **N5 level**: ~800 words, ~100 kanji, past tense and て-form |
| **Month 5** | **N4 level**: ~1,500 words, ~300 kanji, plain form, giving/receiving verbs |
| **Month 6–7** | **B1 / N3 level**: ~3,000+ words, ~650 kanji, reading short articles |
| **July 2027** | 🎯 Sit JLPT N3! |

## ✅ Next Steps

1. Start with `/fluent-learn`; the first lesson covers the あ row and か row of hiragana plus a few greetings
2. Do `/fluent-review` every day; even a short session keeps your streak going 🔥
3. Check your stats weekly with `/fluent-progress`
4. Stay consistent: 10 minutes every day beats 2 hours once a week

## 📁 Where your data lives

Your progress is stored in `data/` (git ignores it, so it stays private):

- `learner-profile.json`: profile, streak, preferences
- `progress-db.json`: overall stats and trends
- `mistakes-db.json`: error patterns
- `mastery-db.json`: skill mastery (0–5 ⭐)
- `spaced-repetition.json`: SM-2 review queue
- `session-log.json`: session history

To change goals or preferences, run `/fluent-setup` again and choose **Update profile**.

がんばって！(Ganbatte! Good luck!) 🚀
