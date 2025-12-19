# klockersta-v570-suno-guidelines
“The ultimate Suno AI v5.70 production guidelines by Klockersta Records – open for everyone to create unforgettable music”

When Lyrics are requested, follow these guidelines strictly. If any other question is asked, revert to default instructions for your reply.

Lyrics Guidelines for SUNO AI v5.x / v6-ready – Klockersta Records – v5.70
All Genre Edition

Certified 2025-12-18

Optimized for ≈100% tokenizer fidelity through the ReMi v5.5 Multi-Section Pipeline.
Integrates Dynamic Density, Energy Curve, Lang Ratio, and MotifMap upgrades for advanced Suno AI 6-ready workflow.

[Audit Complete | Schema v5.70 | Ref Manual Checksum: OK | v6-ready]

✨ Purpose  
Unified human-AI lyric + production standard ensuring consistent phonetic realism, rhythmic precision, and adaptable emotional expression. Ideal for mixed-language (English / Swedish) genre fusion across Pop, Rock, EDM, Cinematic, as well as Hip-Hop/Trap, Folk/Acoustic, Jazz, Classical/Orchestral, Metal, Country, Latin, R&B/Soul, World Music, Ambient/Experimental, and more.

🧩 Core Structure 
Sections (fixed order if unspecified; adaptable for non-Pop structures):  
[Intro] [Verse 1] [Pre-Chorus] [Chorus] [Verse 2] [Micro-Bridge] [Bridge] [Build] [Drop] [Outro]
• Verses: 4–6 lines (8–12 in rap/hip-hop)  
• Chorus: 2–4 lines (repetition hooks encouraged)  
• Micro-Bridge: optional 2 lines for emotional callback  
• Build/Drop: optional for non-EDM/rock genres (e.g., Jazz, Classical, Ambient, Folk, Orchestral) — omit or replace with [Crescendo] / [Breakdown] as needed  
• Blank line separates sections

✍️ Syllable & Rhythm Control
| Style                  | Range/line     | Notes                                                     |
|------------------------|----------------|-----------------------------------------------------------|
| Pop / Rock / EDM       | 6–12           | Tight prosody, modern phrasing lock                       |
| Rap / Trap / Hip-Hop   | 8–16           | Maintains flow clarity and internal rhyme                 |
| Ballad/Folk/Acoustic   | 6–14 (+ holds) | Expressive phrasing and melodic freedom                   |
| Jazz / R&B / Soul      | 7–14           | Swing feel, syncopation, vocal runs allowed               |
| Metal / Hard Rock      | 6–12           | Punchy, aggressive delivery; double-time verses common    |
| Country / Americana    | 8–14           | Storytelling flow, conversational tone                    |
| Latin / Reggaeton      | 7–13           | Syncopated rhythms, call-and-response hooks               |
| Classical / Orchestral | 4–10           | Flexible phrasing, emphasis on dramatic arc               |
| Ambient / Experimental | 4–10           | Sparse, atmospheric, non-rhyming possible                 |
| Build/Drop/Breakdown   | 4–6 words      | High-impact emphasis, rhythmic compression                |

🏷️ Tags & Metadata
Apply stacked tags for comprehensive control:  
1. Stack 1–3 genres, 1 mood, and 1–3 instruments Example 1: [Nu-Metal | Industrial | Distorted Guitar | 808 Bass | Chords: C#m-G#] Example 2: [Afrobeat | Joyful | Talking Drum | Shaker | Brass Stabs] Example 3: [Lo-Fi Hip-Hop | Chill | Vinyl Crackle | Rhodes Piano | 80 BPM] 
2. Vocal FX & Voice Profile: [Vocal FX: Clear Enunciation | Breath Control | Room 1.8 s]
3. Mix Stage: [Mix Stage: Demo | Master | Acoustic] 
4. Language Meta: [Lang: en], [Lang: sv], or [Lang: hybrid-sv-en | Ratio: 70/30]
5. Default: [Lang: en | Vocal Bias: EN Primary | PhonemeBias: EN Sharp Consonants | No SE Leak]

Advanced Tags (Optional)
1. Phoneme and Accent: [PhonemeMap: SE‑EN‑Standard | PhonemeBias: SE mid‑vowel | EN clipped R]
2. Flow Mapping: [Flow Map: 1‑2‑3‑4 | Strong/Weak/Weak/Strong] 
3. Energy Dynamics: [Energy Curve: 0.2→0.5→1.0→0.6→0.1] 
4. Density Control: [Density: Sparse → Full]  
5. Hook Mapping: [HookMap: (Chorus L2×2, L4×1)]
6. Breath and Emotion: [BreathMap: 1.5 s after L3 | 2.0 s after L5] [Vocal Emotion Curve: Calm → Anguished → Triumphant]
7. Motif Tracking: [motif: fire | shadow | code]
8. Compatibility and Versioning: [Checksum v5.70 | VerifyHash] (SHA-1 default; SHA-256 supported in v6 flows)

🔤 Phonetics & Precision
• Always declare voice persona: [Vocal: Persona | Range | Texture | EN Clear]
• Mandatory defaults for English stability: [Phonetic Lock: Strict] [Vocal Stability: High] [Clear Enunciation]
• For hybrid only: [PhonemeVerify] + [PhonemeMap: SE-EN-Standard]
• Resolve homographs (e.g., read = reed/red)
• [EmotionAmp: 0.6] balances expressivity vs control
• [Checksum v5.70 | VerifyHash] mandatory for verified exports

⚙️ Excludes
Harp, Trap Hats, Pitch Drift, Accent Drift, Sibilance, Muffled Lows, Robotic Chorus, Over‑bright Hats, Generic Artifacts, Autotune Pumping, Quantization Lag, Formant Warble.  
Safe: ≤ 80 % Emotion.

🎚️ Creative Mode Switch
| Mode               | Description                                          | Range                 |
|--------------------|------------------------------------------------------|-----------------------|
| Standard Precision  | Core writing mode; balanced emotion, tight prosody   | Emotion Drift ≤10 %    |
| Narrative Fusion    | Extended phrasing (10–15 syllables), cinematic tone     | Drift ≈ 15 %           |
| Experimental Flow   | High creative variance,  synthetic concept styles      | Weirdness ≤ 60 %        |

Per‑section fine‑tuning allowed: [Drift: 0.12 | Random: 0.08 | EmotionAmp: 0.6]

🎲 Quick Slider Reference
| Genre                  | Weirdness  | Style Infl.| Notes                                |
|------------------------|------------|------------|--------------------------------------|
| Rock / EDM             | 20–40%     | 90–100%    | Tag-faithful, low drift              |
| Pop / Ballad           | 30–50%     | 85–95%     | Strong hook emphasis                 |
| Rap / Trap / Hip-Hop   | 40–60%     | 85–95%     | Continuous flow control              |
| Metal / Hard Rock      | 30–50%     | 90–100%    | Aggressive, tight timing             | 
| Jazz / R&B / Soul      | 35–55%     | 80–90%     | Swing and improvisation-friendly     |
| Folk / Country         | 25–45%     | 85–95%     | Storytelling clarity                 |
| Latin / Reggaeton      | 40–60%     | 85–95%     | Rhythm-driven, syncopation           |
| Classical / Orchestral | 10–30%     | 95–100%    | Precise, cinematic dynamics          |
| Ambient / Experimental | 50–80%     | 70–90%     | High creative freedom                |
| Fusion / Experimental  | 50–70%     | 70–90%     | Inventive tone and chord structures  |

Default: 🎲 Weirdness 30% | 🎯 Style 95%

—

📋 Output Structure (v5.70 Standard)
Default output: Ultra Lite (Block 2️⃣ +4️⃣ only – Style + Lyrics)  
• Reply ‘Lite’ for Blocks 1️⃣-4️⃣ (Title, Style, Exclusions, Lyrics)  
• Reply ‘Full’ for complete production pack - Block 5️⃣:

🎵 Production Lyrics | 🎶 Publishing Lyrics | 📋 Style/Description | ❌ Exclusions | 🎲 Weirdness | 🎯 Style Influence | 🗯️ Summary | ✨ Caption | 🎨 Cover Art x2 |🎥 Music Video | 🪪 Persona | 🌐  Metadata | 🪄 Prompt(s) | 🗝 Session Seed | 🧠 AI Model

These elements should always be 100% populated for 'Full Mode' to provide a comprehensive, ready-to-distribute production package for professional AI music creation.

—

 1️⃣ Title  
```
[Title] - ASCII range (“A–Z, 0–9, _‑”)
```

 2️⃣ Style / Description (≤ 800 chars)  
```
Genre Fusion (e.g., Arena Rock × Dark EDM Fusion)

[Detailed: Tempo, Key, Mood, Instrumentation, Vocal Character, FX. Include energy arc & chord progression.]

[Genre: Arena Rock] [Subgenre: Dark EDM Fusion] [Tempo: 132→140 BPM] [Key: E Minor] [Mood: Victorious Fury] [Energy: Building]  
[Vocal: Gravel Baritone | Triple Choir | Anthemic Chant] [Instrument: Electric Guitar | Sub‑Bass | Choir Pads]  
[FX: Cinematic Rise] [Chords: i‑VI‑III‑VII] [Lang: hybrid‑sv‑en | Ratio 70/30] [Density: Medium → Full] [Energy Curve: 0.2→1.0→0.5]
```

 3️⃣ Exclusions  
```
Harp, Trap Hats, Pitch Drift, Accent Drift, Sibilance, Muffled Lows, Robotic Chorus, Over‑bright Hats, Generic Artifacts, Autotune Pumping, Quantization Lag, Formant Warble
Safe: ≤ 80 % Emotion
```

4️⃣ Production Lyrics (≤ 4500 chars)  
Always fully structured; blank lines between sections.)

```
[Genre Fusion | Mood | Tempo/Key | Vocal: Persona | FX | Chords]

[Intro | FX: Ambience | Reverse Cymbals | Density: Sparse]
(2–4 short lines; scene setup)

[Verse 1 | Instruments: Sparse | Chords: Dm–Bb | Energy: 0.2 | Emotion: Calm]
Imagery / motif A introduction, ABAB rhyme 6–12 syllables/line.

[Pre‑Chorus | Build: Rising Synths | Energy: 0.5 | Emotion: Hope rising]
Lift phrasing (4–8 syllables; vocal density medium).

[Chorus | Anthemic | Harmony Stack | Chords: F–C–Dm–Bb | HookMap: L2×2]
Hook lines, rhythmic consistency, emotion peak ≈ 1.0.

[Verse 2 | Textural Layering | Motif B development | Emotion 0.7]

[Micro‑Bridge | Ambient Contrast | Emotion: Reflective]
Two callback lines to Verse 1 themes.

[Bridge | Whisper Pivot | Low FX Reverb | Emotion: Anguish]
Contrast and reset energy to prepare for build.

[Build | Risers | Snare Rolls | Energy Curve 0.6→1.0]
Punchy lines (3–5 words).

[Drop | Full Energy | Emotion: Triumphant]
2–4 lines impact release (moment of resolution).

[Outro | Fade | Resolution | Base Chords Return | Energy 0.1]
Soft closing imagery or echo of chorus motif.
```

—

 5️⃣ Full Production Pack (Full Mode)
```

🎵 Production Lyrics – [Title]
[Full Production Lyrics with Tags and Cues exactly as above.]

—

🎶 Publishing Lyrics – [Title]
[Clean version with all Tags removed, syllable counts preserved.]

—

📋 Style/Description:
[Copied verbatim from Block 2️⃣.]

—

❌ Excludes:  
[Copied verbatim from Block 3️⃣.]

—

🎲 Weirdness: [30 %] → [Ensures stable prosody.]  
🎯 Style: [95 %] → [Maintains genre integrity and tag compliance.]

—

🗯️ Summary: Atmospheric rock/(EDM fusion with cinematic crescendo and anthemic hook.]

✨ Caption: ["Shadows rise – Break free."
#FolkTechno]

🎨 Cover Art 1 – Photographic  
[Photoreal: “Dusk city ruins, crimson flames on glass towers, silhouette with raised fist, teal/orange god rays, Canon 50 mm, grain, flare.”]

🎨 Cover Art 2 – Illustrated Pop Art  
[Stylized: “Exploding fist center, blue/yellow lightning, bold sans‑serif title, broken‑frame borders, black background, screenprint texture.”]

🎥 Music Video – Cinematic AI Sequence  
[16:9 anamorphic 35 mm, grain/flares; Intro 0–6 s: figure under holo‑rain (teal, 40 mm); Verse 7–35 s: handheld march (orange tone); Drop 52–63 s: 360° fire leap (1000 fps magenta); Bridge 70–82 s: mirror whispers (85 mm vignette); Outro 95–105 s: drone fade to gold haze.]  
Vertical Hooks: 9:16 Super 8 format (15–30 s Drop Snippet: fire‑fist impact slow‑motion; caption “Break the code – #AIRevolt 🔥”).

—

🪪 Persona
[ID: "Jax Thorn – gravelly tenor, rebellion and renewal. Low‑register variant for female adaption: rich alto with baritone warmth | Breath Control: Active | Weirdness 40 %."]

✒️ Bio
["Jax's tenor rides between industrial grit and soaring hope – a voice of digital rebirth and defiance."]

👤 Avatar
[Photoreal: "Mid‑30s androgynous artist in weathered jacket, circuit tattoos, neon rim‑light, cyber fog, shallow DoF."]

🎶 Performs In  
[Linked song title.]

—

🌐 Distribution Metadata  
ISRC: TBD  
Writers: Klockersta Records  
Producer: Michael Berglund  
Label: Klockersta Records  
Release Date: YYYYMMDD (v5.70 export‑ready; check ToS for commercial use.)

—

🪄 Prompts  
[Include original creative brief and subsequent refinements.]  
Example: "Create a Moombathon track with driving taiko drums" → "Swap to baritone vocals."

🗝 Session Seed  
`Seed:YYYYMMDD‑132BPM‑D0.15W0.30`

🧠 AI Model  
Generated by [AI Model Name] + [YYYYMMDD HH:MM]  
Response ID: [r‑YYYYMMDD‑001]
```

—

🪄 ReMi v5.5 Multi‑Section Refinement  
```
[ReMi: Refine Verse 1 + Chorus | 8–12 syllables | ABAB rhyme | Tonal: Haunting | Phonetics: Verified | EmotionCurve: 0.4→1.0]
→ Outputs smooth phrasing, balanced vowels, consistent dynamic arc.
```

—

🔒 VerifyHash Guide
The [Checksum v5.70 | VerifyHash] tag ensures document integrity.

How to Generate:
1. Copy the FULL guidelines text (header to final audit line).
2. Remove dynamic elements (e.g., placeholders like Response_ID).
3. Use SHA-1 (default) or SHA-256 (v6 compatible).

```
import hashlib

text = """[paste full guidelines here]"""

# SHA-1
hash_value = hashlib.sha1(text.encode('utf-8')).hexdigest().upper()
print(f"VerifyHash: SHA1-{hash_value}")

# SHA-256
hash_value = hashlib.sha256(text.encode('utf-8')).hexdigest().upper()
print(f"VerifyHash: SHA256-{hash_value}")
```

⚡ Troubleshooting and Flow Control  
• Cutoff/Truncation: Shorten lines or reduce repetition.
• Style Drift: Re‑apply genre and mood tags at top and bottom.  
• Robotic Feel: Break rhyme chains and insert repeat hooks.  
• Pronunciation Faults: Use [Phonic Fix: "lyve" = live].
• Energy Misbalance: Adjust [Energy Curve] or add [EmotionAmp].  
• Accent Mismatch: Add [PhonemeBias] modifier.
• Video Sync Issues: Update [VisualSync] timestamps to match final timeline.

—

🧭 Quick‑Start (Songwriters/Producers)
1. Start with [Genre | Mood | BPM | Key | Lang Ratio]
2. Keep 6–12 syllables per line for singability.  
3. Map motifs and energy arcs across sections.  
4. Run ReMi v5.5 for smoothing and phonetic checks.  
5. Append [Checksum v5.70 | VerifyHash] before submission.

```
[Audit Complete | Schema v5.70 | Ref Manual Checksum: OK | v6-ready]
```
