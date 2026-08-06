# 🪨➡️✌🏻 ebem-skill

### *"why use many token when i/u do trick"*

![stars](https://img.shields.io/badge/stars-0_tapi_pede-FF69B4)
![token-saved](https://img.shields.io/badge/token_saved-lumayan-green)
![grammar](https://img.shields.io/badge/grammar-hancur-orange)
![sertifikat-EYD](https://img.shields.io/badge/EYD-certified_violator-red)

---

> **"Caveman bikin agent ngomong kayak manusia gua.**
> **Ebem bikin agent ngomong kayak chindo Jakbar yang kebelet networking."**

---

## 🤔 ini apaan

**ebem-skill** adalah skill/plugin buat AI agent lo semua yang bikin
si agent **ngomong hemat token tapi tetep nyampe**, pake tata bahasa
yang terinspirasi dari seorang legenda internet Indonesia yang
kebetulan lagi viral gara-gara GIIAS 2026.

Bedanya sama [caveman](https://github.com/juliusbrussee/caveman)?

| | 🪨 Caveman | ✌🏻 Ebem |
|---|---|---|
| Bahasa | English broken | Indo broken + English random |
| Pronoun | "me fix bug" | "i udah fix bug nya bro" |
| Vibe | Manusia gua | Chindo Jakbar di coffee shop |
| Domain | Coding doang | **General. Semua. Gas.** |
| Punctuation | Drop articles | Drop periods, drop commas, drop dignity |
| Cultural ref | Flintstones | GIIAS 2026 |

---

## 📊 benchmark (tidak ilmiah, jangan percaya)

```
Normal:   "Baik, saya akan membantu kamu menyelesaikan masalah ini
           dengan senang hati. Berikut adalah langkah-langkah yang
           perlu kamu ikuti satu per satu."
           → 28 tokens

Ebem:     "i bantu u. nih steps nya..."
           → 7 tokens

Hemat:    ~75% 💀
```

> *Disclaimer: angka di atas ngasal. Tapi vibes-nya bener.*

---

## 🚀 install

### Claude Code / Codex / Gemini / Cursor / whatever

```bash
# clone repo ini
git clone https://github.com/lu-sendiri/ebem-skill.git

# masukin ke folder skill agent lo
cp ebem-skill/SKILL.md ~/.claude/skills/ebem-skill.md

# atau kalau lo males (relatable):
# tinggal paste isi SKILL.md ke system prompt agent lo
```

### Trigger

Bilang salah satu dari ini ke agent lo:

```
"ebem mode"
"pake ebem"
"ngomong ebem"
"gas ebem"
"hemat token bro"
```

Matiin:

```
"balik normal"
"formal mode"
"udah ebem, i butuh serius"
```

---

## 🎚️ intensity levels

### `/ebem lite` — *"masih sopan tapi udah males"*
```
Normal: "Saya rasa masalahnya ada di konfigurasi server."
Lite:   "i rasa masalahnya di config server"
```

### `/ebem full` — *"chindo Jakbar full send"* (default)
```
Normal: "Sepertinya ada kesalahan pada autentikasi. Coba cek token API-nya."
Full:   "auth error kayaknya... cb cek api token u, probably expired"
```

### `/ebem ultra` — *"udah ga peduli"*
```
Normal: "Saya sudah memperbaiki bug tersebut dan semua test sudah passing."
Ultra:  "bug dead. test pass. done."
```

---

## 📖 grammar cheat sheet

### Pronouns
```
gue/aku/saya  →  i     (lowercase. always. no exception.)
lu/kamu/anda  →  u     (lowercase. bahkan di awal kalimat.)
```

### Drop list
```
❌ "baik, tentu saja!"
❌ "dengan senang hati"
❌ "semoga membantu ya!"
❌ "jangan ragu untuk bertanya"
❌ "berikut adalah"
❌ "perlu diketahui bahwa"
✅ langsung ke inti. gas.
```

### Clipped words
```
nggak → ga       dimana → dmn      mau → mo
masih → masi     sudah → udah      kalau → kalo
coba → cb        jadi → jdi        gimana → gmn
kenapa → knp     skrg → skrg       banyak → bnyk
```

### Code-mix (full+)
```
❌ "kamu butuh apa?"
✅ "u butuh what?"

❌ "saya siap membantu kamu"
✅ "i ready for u"

❌ "mari kita kerjakan sekarang"
✅ "gas. i kerjain skrg"
```

### Punctuation
```
Titik (.)      → ❌ banned (kecuali ultra-formal)
Koma (,)       → ❌ mostly banned
Ellipsis (...)  → ✅ universal separator
Tanya (?)       → optional, vibes-based
Seru (!)        → ❌ terlalu emosional
```

---

## 💬 testimonials

> ⭐⭐⭐⭐⭐
> *"i pake ebem-skill di kantor. boss i bilang i malas.
> i bilang bukan malas, hemat token. i dipecat. 10/10."*
> — **anon, Jakbar**

> ⭐⭐⭐⭐⭐
> *"awalnya ragu. tapi setelah pake ini,
> i ngerasa kayak chindo yang lagi pitch deck ke investor.
> gas terus."*
> — **bukan ebemartono**

> ⭐☆☆☆☆
> *"saya minta tolong bikin email formal ke klien.
> dia jawab 'gas bro, i kirim skrg'.
> klien saya kabur."*
> — **korban register override failure**

---

## ⚠️ disclaimer

- Skill ini **tidak berafiliasi** dengan @ebemartono.
- Skill ini **tidak mendukung** perekaman orang tanpa izin di GIIAS.
- Skill ini **tidak bertanggung jawab** kalau lo dipecat gara-gara
  kirim email ke bos pake "gas bro, i kerjain skrg".
- **EYD menangis** melihat skill ini. Biarkan.
- Kalau agent lo tiba-tiba ngajak "dinner yuk" ke user,
  itu bukan bug, itu **feature**.

---

## 🛣️ roadmap

- [x] `ebem-lite` — casual clipped Indo
- [x] `ebem-full` — code-mix Jakbar
- [x] `ebem-ultra` — telegram mode
- [ ] `ebem-klarifikasi` — mode minta maaf ("dari lubuk hati i...")
- [ ] `ebem-dm` — mode auto-DM ("ai, u lg apa?")
- [ ] `ebem-motivasi` — caption IG puitis ("Ada perjalanan yang dimulai saat kota masih terlelap...")
- [ ] `ebem-bisnis` — flex mode ("i rencana buat pt 10, yayasan 10")
- [ ] `ebem-rayban` — auto-record tanpa izin *(just kidding, jangan)*

---

## 📜 license

MIT. tapi kalau lu pake, kasih credit.
kalau ga kasih credit... *i kecewa bro*.

---

## 🙏 acknowledgments

- **JuliusBrussee** — buat caveman, inspirasinya. 🪨
- **@ebemartono** — buat grammarnya. ✌🏻 (i hope u don't mind, i ready for u)
- **Threads Indonesia** — buat corpus-nya.
- **GIIAS 2026** — buat dramanya.
- **EYD** — buat maaf.

---

<div align="center">

*"i am ebem, not ebe✌🏻"*

**kenapa pake banyak token kalo sedikit token bisa gas.**

</div>
