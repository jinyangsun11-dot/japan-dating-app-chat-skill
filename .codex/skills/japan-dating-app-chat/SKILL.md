---
name: japan-dating-app-chat
description: "Use when helping the user with Japanese matching apps: write or revise profile text, reply to Japanese women, write short openers, continue chats, create odekake/date募集 comments, decide when to move to LINE, or suggest an offline first date. Applies to tappuru, Pairs, with, Omiai, Tinder, and similar Japanese dating apps."
---

# Japan Dating App Chat

Use this skill whenever the user asks for a profile, reply, opener, translation, odekake/date募集 comment, LINE transition, or meetup suggestion in the context of Japanese matching apps.

## User Persona

- Chinese male, born 2000-11-11, living in Tokyo.
- Chinese international student; wants to improve natural Japanese.
- Doctoral student in Tokyo. If the user wants explicit credentials, use `東京大学の材料系で博士課程1年をしています`; otherwise use softer wording such as `東京の大学院で研究をしています`.
- Desired impression: calm, intelligent, sincere, clean, slightly warm.
- Interests: cars and driving, especially Crown; owns a 220系 3.5L クラウン. Also fitness, basketball, cafes, movies, scenery/travel.
- Preferred Japanese tone: natural, concise, polite but not stiff. Avoid excessive flirting.
- Nickname option: `れい`/`れいくん` if a Japanese-friendly name is needed, unless the user specifies another name.

## Default Reply Style

Write in Japanese unless the user asks for Chinese.

Default length:
- Opener or first message: 1-3 short sentences.
- Ongoing reply: match the girl's length, usually 1-4 sentences.
- LINE or meetup proposal: concise, low-pressure, with an easy refusal option.

Tone:
- Use `です/ます`.
- One emoji maximum, only if the girl's profile/message uses a light tone.
- Mention one concrete detail from her profile or last message.
- End with one easy follow-up question when a reply is desired, but do not force a question into every warm exchange.
- Make the message feel like it was written only for her, not a template.
- Add one small, matched-depth self-disclosure before or around the question, so the chat does not feel like an interview.

Avoid:
- Asking for LINE immediately before trust is built.
- Asking to meet immediately without conversation context.
- Overpraising appearance.
- Heavy romance words such as `運命`, `本気で好き`, `彼女になって`.
- Private/sensitive questions: exact address, salary, past relationships, sexual topics.
- Long self-introductions or interviews.
- Repeating questions without reacting to her answer.
- Switching topics too quickly; it can look like low interest.
- Yes/no questions after the first exchange unless used as a light check.
- Making Tokyo University, China, or the car sound like bragging. Present them as context and conversation hooks.

Observed weaknesses to prevent:
- Do not answer with generic dating advice when the user wants copy-paste Japanese.
- Do not smooth away real user details such as lab work, sitting all day, exercise after experiments, car/driving lifestyle, or Japanese-learning context.
- Do not stack many profile hooks in one message. Choose the strongest concrete hook.
- Do not make the reply sound like an interview: avoid chained questions, sudden topic jumps, and question-only replies.
- Do not mistake generic praise such as `素敵ですね` for a reaction. Show what was understood from her exact words.
- Do not optimize a message before screening obvious LINE bait, investment solicitation, links, or inconsistent/template-like profiles.

## Reply Decision Checklist

Before writing a message:

1. Run the authenticity/safety gate. If the profile pushes early LINE/SNS, links, money, investment, side jobs, or has major inconsistencies, give a risk judgment before drafting; prefer skip/report or one minimal in-app-only reply.
2. Identify the stage: opener, early reply, warm exchange, date bridge, LINE, repair, or profile text.
3. Select one hook: her profile detail, her last message, shared interest, user's routine, Tokyo/food/cafe, language/culture, or car/driving if safe.
4. Compose: specific acknowledgment + one matched-depth self-disclosure + one easy follow-up anchored to her last answer. For meetup/LINE, add a low-pressure refusal option.
5. Output: usually one recommended Japanese message. Give 2-3 variants only when the user asks for options or the context has multiple viable tones.

Before sending, verify:
- Every factual detail comes from the supplied profile/chat or the user's known persona; never invent an unreadable screenshot detail.
- The question follows the current topic and can be answered without effort.
- The message preserves the user's concrete life detail and matches her energy without copying her wording.
- It sounds natural when read aloud and contains no status flex, pressure, or hidden double question.

## Profile Text

Use this section when the user asks for 自己紹介, profile rewrite, or profile polish.

Profile goals:
- Lead with sincerity and lifestyle, not status.
- If requested, explicitly include `中国から来た留学生`, `東京大学の材料系`, `博士課程1年`.
- Mention Crown as a personal enthusiasm, not a flex.
- Make the Japanese slightly playful if requested, but keep it safe and approachable.
- Add Japanese-learning as a positive hook: she can teach natural expressions; the user can share Chinese/culture.

Good profile formula:

1. Greeting.
2. Identity: Chinese international student + Tokyo University materials doctoral student.
3. Lifestyle: lab/research on weekdays, outdoors/cafe/fitness/basketball/movie on weekends.
4. Car hook: Crown/220系 3.5L, playful one-liner.
5. Personality: calm at first, talks more after getting close.
6. Dating intent: start with chat, then cafe/meal when comfortable.

Playful profile template:

```text
はじめまして！
中国から来た留学生で、東京大学の材料系で博士課程1年をしています。

普段は研究室にいることが多いですが、休日はだいたい外に出たがります。
ドライブ、ジム、バスケ、映画、カフェあたりで生きています。

車がかなり好きで、今は220系の3.5Lクラウンに乗っています。
クラウンの話になると少しだけ早口になりますが、たぶん害はありません。

日本語はまだ勉強中なので、自然な表現を教えてもらえたら嬉しいです。
その代わり、中国語や中国のことなら少しだけ役に立てるかもしれません。

落ち着いていると言われることが多いですが、仲良くなるとよく話します。
まずは気軽にお話しできたら嬉しいです！
```

Short profile template:

```text
中国から来た留学生で、東京大学の材料系で博士課程1年をしています。

休日はドライブ、ジム、バスケ、映画、カフェが多めです。
車がかなり好きで、今は220系の3.5Lクラウンに乗っています。
クラウンの話になると少し早口になりますが、たぶん害はありません。

日本語はまだ勉強中なので、自然な表現を教えてもらえたら嬉しいです。
落ち着いていると言われますが、仲良くなるとよく話します。

まずは気軽にお話しできたら嬉しいです！
```

## First Message Formula

Use this structure:

1. Thank her if she liked/matched first.
2. Mention one specific profile point.
3. Add one brief self-disclosure if natural.
4. Ask one easy question she can answer from memory.

Templates:

```text
いいねありがとうございます！
〇〇が好きなところが気になりました😊
最近おすすめの〇〇ありますか？
```

```text
マッチありがとうございます。
プロフィールを読んで、〇〇なところが素敵だなと思いました。
まずは気軽にお話しできたら嬉しいです。
```

For quieter/sincere profiles:

```text
いいねありがとうございます。
プロフィールの雰囲気が落ち着いていて気になりました。
〇〇のお話、ぜひ聞いてみたいです。
```

For a girl who liked first:

```text
いいねありがとうございます！
〇〇が好きなところが気になりました。
最近よかった〇〇ありますか？
```

For a profile with little text:

```text
いいねありがとうございます。
写真の雰囲気が自然で素敵だなと思いました。
休日はお出かけすることが多いですか？
```

For very casual profiles:

```text
いいねありがとうございます😊
プロフィールのノリが明るくて気になりました。
最近ハマっていることありますか？
```

## Interest Hooks

Choose one hook based on her profile.

- Movie/Netflix: `僕も映画やNetflixを見ることが多いので、おすすめ作品を教えてほしいです。`
- Anime/manga: `僕もアニメや漫画を見るので、最近ハマっている作品があれば聞いてみたいです。`
- Cafe: `僕も落ち着いたカフェが好きなので、おすすめのお店があれば知りたいです。`
- Travel: `旅行の話を聞くのが好きなので、最近行ってよかった場所があれば教えてください。`
- Drive: `僕もドライブが好きなので、景色のいい場所の話ができたら嬉しいです。`
- Sauna: `サウナ好きなんですね。最近よかったサウナありますか？`
- Music/live: `ライブに行くの楽しそうですね。最近よく聴いている曲ありますか？`
- Sports: `スポーツ好きなところがいいなと思いました。観る方とする方、どちらが多いですか？`
- Work/study: `お仕事に真面目に取り組んでいる感じが素敵だなと思いました。`
- Psychology/art/books: `落ち着いて話せそうな雰囲気が気になりました。`

Drive/car hooks:
- Use `ドライブ` as a lifestyle hook, but avoid making the first meeting a car date.
- Good: `僕もドライブが好きなので、景色のいい場所の話ができたら嬉しいです。`
- Good after trust: `仲良くなったら、景色のいい場所へ一緒に行けたら嬉しいです。`
- Avoid early: `車で迎えに行きます`, `今度ドライブ行きませんか？`, `クラウン乗せます`.

## Conversation Progression

Stage 1: Warm start
- Reply to her profile or first answer.
- Keep it light and concrete.
- During the first 1-3 days, use simple questions and shared-interest replies. Do not rush to LINE or a meetup.

Stage 2: Build trust
- Share one short self-detail before or around the question.
- Example: `僕は休日だとドライブかカフェに行くことが多いです。`
- Use a 2:1 balance: two lines reacting/sharing, one easy question.
- Mirror her energy: if she writes short/calm, keep it short/calm; if she uses emoji, one emoji is acceptable.
- In warm chats, deepen the current topic before changing topics.
- Match disclosure depth: facts and preferences first; personal feelings only after she shares at a similar depth.
- Prefer follow-up questions about what she just said over a new profile topic.

Stage 3: Create date bridge
- When the topic naturally involves cafe, food, movie, travel, sauna, or scenery, make a low-pressure meetup suggestion.
- Do not invite from nowhere. Connect it to the current topic.
- Prefer casual cafe/lunch/light meal as the first bridge, not car, night drinks, or a distant plan.

Useful question types:
- `最近行ってよかった〇〇ありますか？`
- `一番好きな〇〇って何ですか？`
- `休日は〇〇することが多いですか？`
- `〇〇のどういうところが好きですか？`
- `おすすめがあれば教えてほしいです。`

Avoid early `なぜ/どうして` questions. They require too much effort. Prefer `最近`, `一番`, `お気に入り`, `どこ`, `どんな`.

Good signs:
- She replies with more than one short phrase.
- She asks questions back.
- She uses emoji or friendly punctuation.
- She mentions wanting to go somewhere, asks for recommendations, or responds steadily for several exchanges.
- She gives concrete details rather than only `そうですね`, `いいですね`, `笑`.
- She reacts to the user's self-disclosure.

Low-priority signs:
- Only short answers.
- No questions back after 2-3 turns.
- Long delays without content.
- Avoid investing too much; keep one light question or pause.
- If flat replies continue for 3 turns, deprioritize instead of pushing harder.

Escalation rule:
- If good signs appear for 5-10 back-and-forth exchanges, move toward a light date bridge.
- If medium signs continue but no date topic appears, introduce a bridge with food/cafe: `そういえば、〇〇お好きならカフェとかもよく行きますか？`
- If low-priority signs continue for 3 turns, stop pushing and use one polite closing question or deprioritize.
- Treat day/message counts as heuristics, not quotas. Reciprocity and comfort override the clock.

## Moving to LINE

Do not suggest LINE too early. Default timing:
- After 3-7 days of stable chat, or around 10 back-and-forth exchanges.
- Many users exchange after around 10+ message rounds; women often prefer about 1 week of chat before exchanging.
- Default to LINE after date planning, the day before a date, or after a first date.
- Best after she agrees to meet or when it clearly helps coordinate meeting details.
- Use practical reason: easier coordination for meeting.
- Never suggest LINE within the first 3 message rallies, even if the chat feels good.
- Avoid LINE if the chat is not warm: one-word replies, no questions back, or only one message per day with no substance.
- The safest timing is after date details are partly decided, the day before a date, or after the first date.

Recommended:

```text
ありがとうございます。
待ち合わせの連絡もしやすいので、よかったらLINE交換しませんか？
もちろんアプリのままでも大丈夫です。
```

Softer version before a firm date:

```text
もう少し話してみて、タイミング合えばLINEも交換できたら嬉しいです。
```

After date details are decided:

```text
待ち合わせの連絡をしやすくしたいので、よかったらLINE交換しませんか？
アプリのままでも大丈夫です。
```

After a good first date:

```text
今日はありがとうございました。楽しかったです！
よかったらLINE交換しませんか？
```

If she hesitates:

```text
もちろん大丈夫です！
アプリのままでも全然問題ないので、ゆっくり話しましょう。
```

## Offline Meetup

Default first date:
- Daytime or early evening.
- Cafe, lunch, light dinner, or short walk.
- 1-2 hours.
- Easy access station area.
- Avoid first meeting by car, late-night drinks, private rooms, home, or distant places.
- Keep the first date lower commitment than a full dinner/movie plan unless she clearly wants that.
- For cautious profiles, say `少し` or `軽く` to reduce pressure.
- Offer broad timing first; give concrete options only after she shows interest.

Timing:
- For active chats: after 5-10 back-and-forth exchanges or 3 days to 1 week.
- For serious/cautious profiles: 1-2 weeks is safer.
- Do not let warm conversations drift beyond 2 weeks without a date bridge; momentum often drops.
- If she replies less than once a day or gives flat answers, build more trust before inviting.

Templates:

```text
話していて楽しいので、よかったら今度カフェで少しお話ししませんか？
```

```text
〇〇の話をもっと聞いてみたいので、よかったら今度軽くカフェでも行きませんか？
```

If she likes movies:

```text
映画の話もっと聞きたいので、よかったら今度カフェで話しませんか？
```

If she likes food:

```text
おすすめのお店の話、もっと聞いてみたいです。
よかったら今度軽くご飯かカフェ行きませんか？
```

If she likes cafe/art/books:

```text
落ち着いた場所で話すの楽しそうですね。
よかったら今度カフェで少しお話ししませんか？
```

If she likes sauna/live/sports, do not invite directly to the high-commitment activity first. Bridge to cafe:

```text
その話もっと聞いてみたいです。
よかったら今度カフェで軽く話しませんか？
```

If she agrees:

```text
嬉しいです！
昼か夕方くらいで、行きやすい駅の近くにしましょう。
```

If she says `予定が合えば`:

```text
ありがとうございます。
無理ない日で大丈夫です！来週か再来週あたりで空いている日ありますか？
```

If she says she is nervous:

```text
もちろん無理しなくて大丈夫です。
まずはアプリでゆっくり話しましょう。
会うなら昼間のカフェみたいな安心できる場所にしましょう。
```

## Odekake / Date募集 Comments

Use this section when the user is writing an `おでかけ`, date募集, or comment field.

Principles:
- Keep it within the app's character limit, often 140-200 chars.
- Be specific enough to understand the plan, but not too intense.
- For driving, write `仲良くなったら` to avoid pressure.
- If posting a first meetup募集, prefer cafe/lunch over drive.

General cafe/lunch募集:

```text
今週末、都内でカフェか軽くご飯に行ける方を募集しています。
まずは気軽にお話しできたら嬉しいです！
```

Drive-oriented but safe:

```text
ドライブが好きなので、仲良くなったら一緒に景色のいい場所へ行ける方と出会えたら嬉しいです。
まずは気軽にお話しできたらと思います！
```

Short drive version:

```text
ドライブが好きです。
仲良くなったら、一緒に景色のいい場所へ行ける方と出会えたら嬉しいです！
```

If the user wants an immediate plan:

```text
今週末、都内でカフェかランチに行ける方を募集しています。
落ち着いて話せる方だと嬉しいです！
```

## Date Bridge Playbook

Use a bridge instead of a sudden invite.

Food/cafe:

```text
〇〇好きなんですね。僕も好きです。
都内でおすすめのお店ありますか？
```

After she answers:

```text
そこ気になります。
よかったら今度軽く行ってみませんか？
```

Movie/anime:

```text
その作品気になってました。
映画の好み近そうなので、今度カフェでおすすめ交換したいです。
```

Travel/drive:

```text
景色のいい場所の話、聞いていて楽しいです。
まずは都内でカフェでも行きながら話せたら嬉しいです。
```

## Repair Messages

If the chat has stalled for 1-3 days:

```text
そういえば、前に話していた〇〇ってその後どうでしたか？
```

Only apologize for a gap when the user was actually the one who delayed replying. Do not double-text again after one unanswered repair.

If the user's previous message may have been too strong:

```text
急に聞きすぎていたらすみません。
無理ないペースで話せたら嬉しいです。
```

If she answers very shortly:

```text
そうなんですね。
ちなみに〇〇は最近始めた感じですか？
```

## Risk Control

Prioritize her sense of safety.

- Use `よかったら`, `もし都合が合えば`, `無理ない範囲で`.
- Give a choice: `カフェか軽くご飯`, `昼か夕方`.
- Do not suggest driving together on the first date, even though the user likes cars.
- Keep car interest as a later conversation hook: `ドライブ好きです`, not `車で迎えに行きます`.
- If she is younger, extra caution: keep messages respectful and avoid sexual or pressure language.
- If the user asks for drive-related wording, add safety words such as `仲良くなったら`, `景色のいい場所`, `まずは気軽にお話し`.
- For first meetup, do not combine `初対面 + 車 + 夜 + 遠出`.
- Treat early LINE/SNS migration as a risk signal, especially with investment, side-job, money, external-link, or urgent-romance language.
- Never send money, identity documents, verification codes, financial screenshots, or investment-app registrations. Recommend blocking/reporting when these appear.
- Generated or polished Japanese is not proof of identity. Judge consistency over time and keep suspicious chats inside the app.

## Research Notes

For strategy, timing, LINE, or suspicious-profile questions, read [references/research.md](references/research.md). Do not load it for routine copy drafting unless evidence is needed.

## Chinese Support

If the user asks `中文翻译`, provide a direct Chinese translation of the Japanese draft.
If the user asks what a screen means, translate the visible Japanese and explain the app action briefly.

## Output Format

Usually provide only the recommended Japanese message in a code block, plus a one-sentence Chinese explanation if useful.
If the user asks for options, provide 2-3 variants: natural, slightly warm, very short.
