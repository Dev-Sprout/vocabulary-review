# Vocabulary Review **UZ** - **EN**

**Vocabulary Review** — bu o‘zbek foydalanuvchilari uchun mo‘ljallangan inglizcha so‘z yodlash ilovasi.

Ilova foydalanuvchiga kerakli so‘zlarni tez va samarali yod olishda yordam beradi:
- Spaced Repetition algoritmi
- Quiz/Flashcard rejimi
- Kategoriya bo‘yicha so‘zlar
- AI yordamchi
- Offline rejim

---

## 🧠 Asosiy Imkoniyatlar

### 1. Yodlash Rejimlari

#### 🔁 Spaced Repetition — Yodlash Algoritmi

- So‘zlar **takrorlanadigan intervallar** asosida qayta ko‘rsatiladi
- Har bir muvaffaqiyatli eslashdan so‘ng, **interval uzoqlashadi**
- Xatolik bo‘lsa, so‘z yana tez-tez chiqadi

**Algoritm mantig‘i:**

| Ketma-ket to‘g‘ri javob | Keyingi ko‘rsatish oraliği |
|-------------------------|-----------------------------|
| 0                       | 1 kun                       |
| 1                       | 3 kun                       |
| 2                       | 7 kun                       |
| 3+                      | 14+ kun                     |

So‘zlar quyidagi qiymatlar bilan saqlanadi:
- `reviewCount`
- `correctInRow`
- `lastReviewedDate`
- `nextReviewDate`

#### 🧾 Flashcard Rejimi
- Old tomonda: inglizcha so‘z
- Orqa tomonda: o‘zbekcha tarjima, misol va grammatik izoh

#### 🧪 Quiz Rejimi
- Variantlardan to‘g‘ri tarjimani tanlash
- Natijalar statistikada aks etadi

---

### 2. 📚 Kategoriya Bo‘yicha So‘zlar

- Tayyor to‘plamlar:
  - `Travel`
  - `Education`
  - `Health`
  - `Technology`
  - va boshqa mavzular

- Har bir kategoriya uchun:
  - 100–300 ta foydali so‘z
  - Misollar va TTS(Text to Speach)

---

### 3. 📊 Progress Kuzatish

- Nechta so‘z yodlangan
- Quizdagi to‘g‘ri/noto‘g‘ri javoblar
- Yodlash progressi (kunlik/haftalik)
(Bu qismi ustinda biroz o'ylanish garak)

---

### 4. 📡 Offline Rejim

- Ilova **internet bo‘lmasa ham** ishlaydi
- TTS audiosi oldindan yuklab olinadi
- Ma’lumotlar **SQLite** orqali saqlanadi

---

### 5. 📘 Grammatik Qoidalar

- Har bir `Part of Speech` (noun, verb, adjective, etc.) bo‘yicha qisqa izohlar
- Misollar:  
  - `Irregular Verbs`  
  - `Phrasal Verbs`  
  - `Verb Tenses`

---

### 6. 🤖 AI Yordamchi

- **Yozilgan gapni to‘g‘rilaydi** (Grammar correction)
- **So‘zlarni kontekstda ishlatadi**
- **Speaking mashqlari:** foydalanuvchi AI bilan muloqot qiladi
- `GPT` + `Whisper` API integratsiyasi orqali ishlaydi

---

## 🧩 Texnologiyalar

| Qism             | Texnologiya        |
|------------------|--------------------|
| Frontend         | Flutter / React Native |
| Backend          | Firebase / Supabase    |
| Ma’lumotlar      | SQLite (offline)   |
| TTS (Ovoz)       | Google TTS / OpenAI TTS |
| AI               | OpenAI GPT / Whisper |
(Bu qism ixtiyoriy, ya'ni o'zimizga mos)

---

**So‘zlar bazasini o‘zimiz tuzamiz va ochiq manbalarni ham qo‘shamiz, shuningdek albatta foydalanuvchi ham so'zlarni kiritadi.

---

## 🔜 Kelajakdagi Rejalar

- Foydalanuvchi o‘zi to‘plam yaratishi
- Ovoz bilan izlash
- Ko‘proq til (ruscha, nemischa) qo‘llab-quvvatlash

---
