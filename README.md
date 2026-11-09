# English Sounds | دەنگە ئینگلیزییەکان

ماڵپەڕی فێربوونی دەنگە ئینگلیزییەکان، وشەکان و ئەکادیمی. دوای یەکەم جار کردنەوە **بێ ئینتەرنێت** کار دەکات (PWA).

## فایلەکان
| فایل | کار |
|---|---|
| `index.html` | هەموو ماڵپەڕەکە (فۆنت، وێنە و وشەکان تێیدان) |
| `sw.js` | Service Worker بۆ کارکردنی ئۆفڵاین |
| `manifest.webmanifest` | بۆ دامەزراندنی وەک ئەپ لەسەر مۆبایل / کۆمپیوتەر |
| `icon-192.png`, `icon-512.png` | ئایکۆنی ئەپ |

## بەرزکردنەوە بۆ GitHub Pages
1. لە GitHub **New repository** دروست بکە (بۆ نموونە `english-sounds`)، **Public**.
2. **Add file → Upload files** و هەموو فایلەکان ڕاکێشە (بێ فۆڵدەر، هەموویان لە ڕیشەی repository).
3. **Commit changes**.
4. **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
5. دوای 1-2 خولەک ماڵپەڕەکە لێرەیە: `https://USERNAME.github.io/english-sounds/`

## ئۆفڵاین
- یەک جار بە ئینتەرنێت بیکەرەوە، پاشان بێ ئینتەرنێت کار دەکات.
- لە Chrome/Edge: ئایکۆنی **Install** لە ناو ناونیشانەکە؛ لە مۆبایل: **Add to Home screen**.

## نوێکردنەوە
هەر کاتێک `index.html` گۆڕیت، لە `sw.js` ژمارەی `VERSION` بگۆڕە (`v1` → `v2`) تاکو بەکارهێنەران ڤێرژنی نوێ وەربگرن.

## تێبینی
- وێنەگرتنی شاشە و تۆمارکردنی ڤیدیۆ تەنها لەسەر **HTTPS** (GitHub Pages) و لە **Chrome/Edge ی کۆمپیوتەر** کار دەکەن؛ دوگمەی «ئەم بەشە» لە مۆبایلیش کار دەکات.
- بۆ تاقیکردنەوەی ناوخۆیی: `python -m http.server` لە فۆڵدەرەکە، پاشان `http://localhost:8000`.
