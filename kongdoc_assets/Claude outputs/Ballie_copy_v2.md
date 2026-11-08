# Samsung Ballie — page copy (v2, from Figma)

> 표시: **[수정]** = 제가 고친 부분, **[확인]** = 결정이 필요한 부분

---

## Hero

**Label:** AI HOME ROBOT · 2025
> [확인] Figma에는 "AI SCREEN EXPERIENCE · 2021"로 되어 있어요. Vision AI 페이지 라벨이 복사된 것 같아서 Ballie에 맞게 바꿨어요.

**Title:** Samsung AI Companion Robot Ballie

**Confidential note:** Some details of this project are confidential. This case study shares publicly available information and what I learned along the way. If you'd like to chat about my experience, feel free to email me! 😊

| MY ROLE | THE TEAM | RECOGNITION |
|---|---|---|
| UX and Interaction Design | Software and hardware engineers, AI engineers, UX designers | iF Design Award — Gold 2025 |

---

## PRODUCT FEATURES

Ballie is an autonomous mobile AI companion designed for the domestic environment. Moving seamlessly through living spaces, it choreographs smart home connectivity, conversational intelligence, and dynamic spatial projection to deliver proactive, hands-free assistance.

*(YouTube video: "Get ready for Ballie | Samsung")*

---

## OPPORTUNITIES

While traditional smart assistants rely on static screens and reactive voice commands, an autonomous mobile robot requires an entirely new interaction paradigm. I focused on designing multimodal interactions and spatial projection systems that seamlessly adapt to the rhythm of domestic life.

| # | Title | Description |
|---|---|---|
| 01 | Ambient Presence & Contextual Greetings | Establishing non-intrusive awareness models that recognize user presence and routines without demanding immediate attention. |
| 02 | Proactive Learning & Personalization | Designing proactive feedback loops where the assistant anticipates routines and serves information without manual prompts. |
| 03 | Adaptive Spatial Projection System | Transforming domestic surfaces into flexible, form-free display canvases tailored to varying distances, angles, and activities. |
| 04 | Hands-Free Physicality: Foot-Press Interface | Extending interaction beyond conventional touchscreens by introducing floor-projected controls for hands-busy domestic scenarios. |

> [수정] 01 "Contextual Greeting" → "Greetings" (Main Feature 1 제목과 통일)
> [확인] 02 Figma 카드는 "Context-Aware Proactive Intelligence"인데, 아래 Main Feature 2 제목은 "Proactive Learning and Personalization"이에요. 카드와 섹션 제목을 하나로 맞추는 게 좋아서 일단 섹션 제목 쪽으로 통일했어요.

---

## MAIN FEATURE 1 — Ambient Presence & Contextual Greetings

A mobile robot that greets users every time it sees them quickly turns from helpful companion into ambient noise. The goal was to build connection through precise timing and restraint rather than relentless engagement.

- **Proximity & Gaze-Aware Triggers** — Leveraged mobile proximity signals and low-power computer vision to distinguish between passive room transitions and intentional engagement, initiating greetings only when the user is receptive.
- **Context-Sensitive Cue Calibration** — Engineered dynamic response rules where greetings adapt to external context — delivering brief, subtle auditory chimes during busy morning rushes, while offering richer multimodal summaries (weather, schedules) when users pause nearby.
- **Non-Intrusive Idle States** — Defined calm resting postures and peripheral staging positions so Ballie maintains an approachable presence in the room without obstructing domestic traffic or demanding focal attention.

---

## MAIN FEATURE 2 — Proactive Learning & Personalization

Unlike conventional smart assistants that wait passively for explicit voice commands, Ballie anticipates user needs by observing behavioral rhythms and contextual patterns within the home. The design challenge was defining the threshold between helpful proactivity and intrusive interruption.

- **Routine-Based Anticipation** — Designed adaptive logic that learns repeating daily habits — such as recognizing a 7 a.m. wake-up routine to proactively surface morning news briefings or adjust environmental lighting without explicit prompting.
- **State-Responsive Behavior Modeling** — Established interaction states tailored to specific user activities (working, exercising, or unwinding), ensuring the assistant offers timely support that matches the user's current cognitive load.
- **Zero-Prompt Information Delivery** — Reduced input friction by initiating relevant content — like transitioning directly into guided workout timers or relaxing ambient media when a specific domestic routine is detected.

> [수정] "adjusting environmental lighting" → "adjust" (surface와 병렬)
> [수정] "(working, exercising, or unwinding , ensuring …)" 괄호 위치 정리

---

## MAIN FEATURE 3 — Adaptive Spatial Projection System

Domestic environments are visually cluttered and lack standardized screens. Rather than treating projection as a static rectangular frame, I designed an adaptive spatial display system that treats everyday architectural surfaces as flexible, non-intrusive interfaces.

- **Dynamic Surface Calibration** — Leveraged spatial mapping to dynamically calculate surface angles, projection distances, and ambient lighting, ensuring text and UI elements remain legible whether cast onto low floors or vertical walls.
- **Adaptive Visual Scale & Hierarchy** — Created a responsive visual design system that scales interface density based on proximity — rendering glanceable, bold iconography from across the room, and shifting to detailed interactive controls as the user approaches.
- **Peripheral, Non-Intrusive Presence** — Designed placement guidelines to anchor visual information in peripheral sightlines rather than dead center, supporting ambient awareness without demanding focal attention or dominating the living space.

---

## MAIN FEATURE 4 — Hands-Free Physicality: Foot-Press Interface

In domestic environments, users frequently find themselves in hands-busy situations — such as cooking, working out, or carrying items — where reaching for a smartphone or operating physical touchscreens introduces unnecessary cognitive and physical friction. To bridge this gap, I designed the foot-press virtual interface, transforming everyday floors into dynamic touchpoints using Ballie's triple-laser projector and spatial sensors.

- **Floor-Projected Controls** — Instead of requiring users to approach a screen, Ballie casts intuitive control menus and status widgets directly onto the floor within the user's immediate reaching zone.
- **Foot Gestures & Tap Affirmation** — Engineered intuitive physical gestures — including single-taps to trigger smart home appliances or adjust thermostats, and gentle slides to scroll through media playlists or workouts.
- **Contextual Safety & Feedback** — Defined visual feedback and boundary detection rules so users can confidently trigger commands without accidental misfires while moving naturally around the home.

> [확인] Figma 라벨은 "INTERACTIONS 1"이에요. Opportunities 카드 04와 짝이 맞도록 "MAIN FEATURE 4"로 바꿨어요. 원래대로 두길 원하시면 말씀해 주세요.

---

## PERSONAL LEARNINGS & PRINCIPLES

### 01. Context-Adaptive Error Communication & Troubleshooting

Operating an autonomous physical robot in unstructured domestic settings inevitably introduces environmental friction — such as navigating loose cables, transitioning between rug pile heights, or encountering blocked pathways.

- **Graceful Degradation Over Immediate Interruption** — A core principle was limiting active alerts to the absolute minimum. Rather than emitting loud alarms or demanding urgent troubleshooting for every minor obstacle, Ballie first attempts autonomous resolution (e.g., path re-routing or gentle angle adjustments).
- **Multi-Tiered Feedback Channels** — When human intervention is truly necessary, error feedback is graduated based on user proximity: subtle ambient light indicators for peripheral awareness, transitioning to floor-projected status hints or companion mobile push alerts only if the obstacle persists.

> [수정] "A core principle established was" → "A core principle was" (간결하게)

### 02. The Emergence of Companion Attachment Beyond Utility

Moving from initial proof-of-concept prototypes to testing in real living environments revealed a profound shift in how users perceive an embodied AI entity.

- **From Appliance to Autonomous Companion** — While initial user expectations centered on utility (smart home control, projection, home security), prolonged exposure transformed Ballie from an appliance into a pet-like presence. Subtle micro-movements, polite spatial distance, and responsive greetings created tangible emotional resonance.
- **Expanding Beyond General Convenience** — This dynamic was particularly pronounced among solo dwellers and families requiring additional daily care. It validated that for mobile domestic robotics, seamless functional utility is merely the baseline; the true design frontier lies in choreographing respectful physical presence and emotional companionship.

> [수정] "(smart home control, projection, home security , prolonged exposure)" 괄호 위치 정리

---

## Ballie on Media!

*(article thumbnail)*
