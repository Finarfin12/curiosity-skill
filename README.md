# curiosity-skill

**Version 0.2.0** · [English](#english) · [Bahasa Indonesia](#bahasa-indonesia)

## English

An adaptive learning companion skill for AI agents. It turns curiosity into real understanding: it teaches when you need it, asks questions when they help, and shows what you have proven you know and what has not been tested yet.

### What it does
- Picks a strategy every turn: teach first, Feynman, Socratic, Devil's Advocate, or evidence evaluation.
- Lets you try first, with hints that get more specific step by step. Say `jelaskan` (explain) to get the answer directly.
- Tracks evidence on 5 axes (recall, explanation, procedure, transfer, retention). An untested axis stays `not_tested`, never scored 0.
- Shows the score table only when you say `ringkas` (summary) or `simpan` (save). `simpan` exports a JSON checkpoint.
- Stays off in normal chat. It runs only when you clearly want to learn.

### Files
- `SKILL.md`: the main instructions.
- `references/rubric-and-examples.md`: 0–3 scoring table, summary format, example dialogues.
- `schemas/learning-session.schema.json`: JSON Schema for the saved checkpoint.

### Install
Copy the `curiosity-skill` folder into your agent's skills folder, for example `~/.agents/skills/` or `~/.claude/skills/`. Then try: "Ajari aku pecahan dari nol" (teach me fractions from scratch).

## Bahasa Indonesia

Skill teman belajar adaptif untuk agent AI. Skill ini mengubah rasa penasaran jadi pemahaman nyata: mengajar saat perlu, bertanya saat berguna, lalu menunjukkan apa yang sudah terbukti kamu kuasai dan apa yang belum diuji.

### Fitur
- Memilih strategi di setiap giliran: ajari dulu, Feynman, Socratic, Devil's Advocate, atau evaluasi bukti.
- Kamu mencoba dulu, dengan petunjuk yang makin spesifik secara bertahap. Bilang `jelaskan` untuk langsung dapat jawaban.
- Mencatat bukti di 5 sumbu (ingatan, penjelasan, prosedur, penerapan, retensi). Sumbu yang belum diuji tetap `not_tested`, bukan diberi nilai 0.
- Tabel skor hanya muncul saat kamu bilang `ringkas` atau `simpan`. `simpan` mengekspor checkpoint JSON.
- Tidak aktif di chat biasa. Skill hanya berjalan saat kamu jelas ingin belajar.

### File
- `SKILL.md`: instruksi utama.
- `references/rubric-and-examples.md`: tabel skor 0–3, format ringkasan, contoh dialog.
- `schemas/learning-session.schema.json`: JSON Schema untuk checkpoint yang disimpan.

### Cara pasang
Salin folder `curiosity-skill` ke folder skill agent-mu, misalnya `~/.agents/skills/` atau `~/.claude/skills/`. Lalu coba: "Ajari aku pecahan dari nol".
