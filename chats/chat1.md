# FOF Youth Sports Branding

_Started 2026-05-09 22:30 UTC_

---

## User



## Assistant

_[tool: questions_v2]_

Before I dive in and build this whole system out, I need to nail down a few brand fundamentals — there are no assets attached, and "our own unique local brand" leaves the most important decisions open. A short round of questions now will save us a lot of churn later.

## User

Questions answered:
- brand_name: FOF Youth Sports 
- location: Charlotte NC 
- sports: Soccer, Flag football, Basketball, Baseball / T-ball, Volleyball, Cheer
- age_range: 5–12 (elementary)
- personality: Balanced — playful for kids, polished for parents (the i9 zone)
- color_direction: 0
- logo_style: 0
- typography_vibe: Friendly humanist (rounded, approachable — think Nunito/DM Sans)
- products: Marketing website (homepage, about, sports pages), Registration / sign-up flow, Parent dashboard (schedule, team, payments), Mobile app (game-day companion), Coach dashboard
- imagery_style: Real photos of kids playing — warm, candid, sunny
- anything_else: Color Preence Gold and blue

## Assistant

_[tool: update_todos]_

_[tool: set_project_title]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

I'll move fast and write things in parallel batches. Let me start with the core foundation files.

_[tool: snip]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

Now the README, the photo placeholder pattern, sport iconography setup, and preview cards. I'll keep working in parallel batches.

_[tool: snip]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: show_to_user]_

_[tool: write_file]_

_[tool: snip]_

_[tool: show_to_user]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: snip]_

_[tool: write_file]_

_[tool: show_to_user]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: snip]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: show_to_user]_

_[tool: snip]_

_[tool: write_file]_

_[tool: show_to_user]_

_[tool: register_assets]_

_[tool: snip]_

_[tool: write_file]_

_[tool: snip]_

_[tool: show_to_user]_

_[tool: str_replace_edit]_

_[tool: write_file]_

_[tool: snip]_

_[tool: write_file]_

_[tool: show_to_user]_

_[tool: snip]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: write_file]_

_[tool: register_assets]_

_[tool: read_file]_

_[tool: read_file]_

_[tool: read_file]_

_[tool: snip]_

_[tool: write_file]_

_[tool: str_replace_edit]_

_[tool: str_replace_edit]_

_[tool: update_todos]_

_[tool: show_to_user]_

_[tool: snip]_

Updated:

- **Logo Mark Cream** — bigger pop: gold-glow background, gold halo ring, and outlined gold stars instead of flat navy ones.
- **Type — Headings** — H2 specimen now reads "Saturdays at Corvian Community School."
- **Type — Body** — body specimen now leads with "Five weeks of games on turf."

All three should refresh in the review pane.

## User

I really would like to add “a high-energy homepage hero video featuring children participating in multiple youth sports (soccer, football, basketball, baseball), emphasizing fun, inclusion, teamwork, and community. The video should autoplay muted, loop seamlessly, and feel modern, family-friendly, and inspirational.”

## Assistant

_[tool: snip]_

_[tool: read_file]_

_[tool: str_replace_edit]_

_[tool: show_to_user]_

Hero video slot is in. Here's what I did and what I need from you:

**What's in the page now**
- A real `<video autoplay muted loop playsinline>` element sized as the hero panel (4:5, rounded, gold glow + bottom gradient).
- Sound-toggle button (muted by default; tap to unmute).
- A "Live · Spring '26" pulsing badge and the floating Lions 3 · Hawks 2 score card.
- An animated **fallback** behind the video — four crossfading branded scenes (Soccer → Flag football → Basketball → T-ball) with the FOF confetti pattern overlay — so the hero looks alive even before a real file lands.

**To go live, drop the real video here**
- `assets/hero-loop.mp4` (required) — H.264, 1080p+, 8–15 s seamless loop, **no audio track or silent**, 4:5 vertical-friendly framing
- `assets/hero-loop.webm` (optional, smaller) — VP9/AV1
- `assets/hero-poster.jpg` (optional) — first-frame still for slow connections

The current code already references all three paths — once they exist the browser will pick them up automatically and hide the fallback.

**My ask**
Can you give me a brief or shot list for the video? Specifically:
1. Will you film original footage or license stock? (I'd lean original — i9-style stock looks generic.)
2. Sports to feature in the loop (all 6, or focus on 3–4)?
3. Any moments that *must* be in there (a high-five, a goal celebration, a parent on the sideline)?
4. Tone — pure montage with music vibes, or one continuous slow-mo "hero kid" shot?

Once you decide, I can write a 30-second shot list/storyboard for whoever shoots it.

## User

1. free license stock. 2. basketball, volleyball, flag football, soccer. 3. Basketball made. must be diverse mix of youth kids one continuous

## Assistant

_[tool: snip]_

Got it. Here's the brief — written so you can hand it straight to a stock-licensing person or paste the queries into Pexels / Pixabay / Mixkit (all CC0, commercial-free).

## FOF hero — 30s continuous montage

**Sports order (rhythm builds → release):**
1. **Soccer** — open with motion (running, kicking) → 0:00–0:07
2. **Volleyball** — bump/set energy, indoor light → 0:07–0:14
3. **Flag football** — flag pull or TD celebration → 0:14–0:21
4. **Basketball — MADE SHOT** → 0:21–0:30 *(this is the hero beat — bigger, slower, end on celebration high-five or arms-up)*

**Cast requirements (every clip):**
- Ages 5–12 (elementary)
- **Diverse mix** — at least 3 racial/ethnic groups visible across the loop, mixed gender per sport
- Real teamwork moments: high-fives, huddles, parents/coaches in soft background
- No close-up faces of any single kid for >2 sec (keeps it "every kid" not "this kid")

**Look:**
- Warm, sunlit, candid — golden hour > studio
- Slight shallow depth of field is fine
- No slow-mo gimmicks until the basketball made-shot, where a half-speed beat lands well
- Cuts on motion (a ball leaves frame in clip A → enters frame in clip B)

**Technical — drop into `assets/`:**
- `hero-loop.mp4` — H.264, 1920×2400 (4:5) or 1080×1350 cropped, **silent track**, ~8–12 MB max for fast load, last frame matches first frame for seamless loop
- `hero-loop.webm` — VP9, same content, ~30% smaller
- `hero-poster.jpg` — first frame of the basketball celebration (the emotional payoff)

## Free-stock search queries to run

Run these on **Pexels.com**, **Pixabay.com/videos**, and **Mixkit.co** (all free for commercial use, no attribution required):

| Sport | Query |
|---|---|
| Soccer | `kids soccer practice`, `youth soccer goal`, `children soccer field` |
| Volleyball | `kids volleyball`, `youth volleyball indoor`, `children volleyball serve` |
| Flag football | `flag football kids`, `youth flag football`, `children touchdown` |
| Basketball | **`kids basketball shot`, `youth basketball score`, `child basketball celebration`** ← this is the hero — pick the best one first |
| Cutaways | `kids high five sports`, `youth team huddle`, `children sports celebration` |

**Tip:** Pexels has the cleanest youth-sports library; start there. Filter by orientation = **portrait** since the hero panel is 4:5.

Once you have 4–6 candidate clips, send them my way and I'll cut the loop together (or describe the order to your editor — the timing above is what makes it feel continuous instead of montage-y).

## User

I will let you design this one

## Assistant

_[tool: snip]_

_[tool: read_file]_

_[tool: write_file]_

_[tool: snip]_

_[tool: str_replace_edit]_

_[tool: snip]_

_[tool: done]_

_[tool: fork_verifier_agent]_

The hero now plays a 24-second continuous SVG-driven montage built around your brief:

1. **Soccer** — kicker striking the ball, ball arcs out frame
2. **Volleyball** — bumper-to-spiker rally across the net
3. **Flag football** — runner breaks away with yard lines panning past, gold flag streaming
4. **Basketball — MADE SHOT** (climax) — shooter rises, ball arcs to the rim, net swishes, gold confetti pops, **+2** flashes, "MADE IT." headline lands

Diversity is wired in via a six-tone `--skin-*` palette assigned across the four figures. A real `<video>` slot stays in place — drop `assets/hero-loop.mp4` whenever footage is ready and it'll auto-replace the animation.

**Caveats**
- Stylized illustration, not photography — clearly a design placeholder. Once you license real Pexels/Pixabay clips it should swap in.
- The "MADE IT." copy on scene 4 is mine — change it if you want something different ("Game on", "Hooped it", etc).

## User

can you publish website

## Assistant

## User

Save this design as a PDF: the current design

## Assistant

