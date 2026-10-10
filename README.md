# 🎯 AI SmartMark — Sistem Penilaian Jawapan Pelajar Berasaskan AI

**Versi:** 1.0 MVP  
**Platform:** Web Application (HTML5 + Vanilla JS)  
**Bahasa Interface:** Bahasa Melayu (dengan sokongan jawapan Bahasa Inggeris)  
**Target:** Pensyarah Politeknik, Universiti & Kolej Malaysia  

---

## ✅ Ciri-Ciri MVP Yang Diimplementasi

| Ciri | Status |
|------|--------|
| Log Masuk & Daftar Akaun | ✅ |
| Papan Pemuka | ✅ |
| Buat Peperiksaan | ✅ |
| Muat Naik & Ekstrak Skim Markah PDF | ✅ |
| Editor Rubrik (semak & edit soalan) | ✅ |
| Muat Naik Skrip Pelajar (berbilang PDF) | ✅ |
| Ekstrak Teks PDF (PDF.js) | ✅ |
| Penandaan AI (OpenAI GPT-4o / GPT-4o-mini) | ✅ |
| Mod Demo (tanpa API key) | ✅ |
| Ruang Kerja Penandaan (semak, edit markah) | ✅ |
| Semak & Moderasi | ✅ |
| Keputusan & Analitik | ✅ |
| Eksport Excel (XLSX) & CSV | ✅ |
| Log Audit | ✅ |
| Tetapan & Konfigurasi AI | ✅ |
| Anonymous Marking | ✅ |

---

## 🚀 Cara Guna

### 1. Buka Aplikasi
Buka fail `index.html` terus dalam browser (Chrome / Edge disyorkan).

**Atau akses online:**  
👉 `https://normala7175-art.github.io/SmartMarkingMaster/`

### 2. Log Masuk
Gunakan sebarang emel dan kata laluan (akaun disimpan secara tempatan).

### 3. Aliran Kerja Lengkap
```
Buat Peperiksaan → Muat Naik Skim Markah PDF → Sahkan Rubrik
→ Muat Naik Skrip Pelajar → AI Menanda → Semak & Edit Markah
→ Lulus Skrip → Eksport Keputusan (XLSX/CSV)
```

---

## 🤖 Konfigurasi AI

### Mod Demo (Default)
Tanpa API key, sistem menggunakan **Mod Demo** dengan data contoh yang jelas dilabel sebagai demo.

### Mod AI Sebenar (OpenAI)
1. Pergi ke **Tetapan & Konfigurasi**
2. Pilih pembekal AI: `OpenAI (GPT-4o)` atau `OpenAI (GPT-4o-mini)`
3. Masukkan OpenAI API Key anda (`sk-...`)
4. Klik **Simpan Tetapan AI**

> ⚠️ API key disimpan dalam `localStorage` penyemak imbas anda sahaja dan tidak dihantar ke mana-mana pelayan pihak ketiga.

---

## 🗄️ Storan Data
Semua data disimpan dalam **localStorage** penyemak imbas. Gunakan fungsi **Eksport Semua Data** (Tetapan) untuk membuat sandaran.

---

## 📁 Struktur Fail
```
smartmark/
├── index.html      ← Aplikasi lengkap (single-file)
└── README.md       ← Dokumentasi ini
```

---

## ⚠️ Had Diketahui (Known Limitations)
- Handwriting OCR tidak disokong (perlu PDF janaan digital)
- Storan data bergantung pada localStorage browser
- Multi-institusi belum disokong (Priority 3)
- Fail PDF besar (>20MB) mungkin lambat diproses

---

*Dibina dengan AI SmartMark MVP — TVET Politeknik Malaysia*
