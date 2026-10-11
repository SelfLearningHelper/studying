# Studying — Interactive Practice Quizzes

Browser-based practice quizzes I built to study my university courses. Each quiz is one self-contained HTML file: no framework, no build step, no backend. It runs on GitHub Pages and works on phone and desktop.

اختبارات تدريبية تفاعلية بنيتها عشان أذاكر مواد الجامعة. كل اختبار ملف HTML واحد مستقل، بدون framework ولا build ولا backend. تشتغل على GitHub Pages، من الجوال أو الكمبيوتر.

---

## Quizzes / الاختبارات

| Quiz | Link |
|---|---|
| Media Translation | [Open](https://selflearninghelper.github.io/studying/media-translation-quiz/) |
| ME 4245 — Renewable Energy: True or False (Lectures 1–3) | [Open](https://selflearninghelper.github.io/studying/me4245-TrueOrFalse/) |
| ME 4441 — Engineering Management | [Open](https://selflearninghelper.github.io/studying/me4441-quiz/) |
| IDP Competency Certification | [Open](https://selflearninghelper.github.io/studying/idp-certification-quiz/) |

---

## Features (English)

### Media Translation · ME 4245 · ME 4441
- **Two modes:** *Learn* has no timer and explains the correct answer after each question. *Exam* is timed and graded only at the end.
- **Arabic / English:** switch the question language before starting.
- **Lecture selection:** quiz on one lecture or several (ME 4441 covers a single module).
- **Adjustable question count.**
- **Review screen:** go through every answer after the quiz, or filter to mistakes only.
- **Lecture summaries** built into the quiz for quick revision.
- **Keyboard shortcuts:** `1`–`4` for multiple choice, `1`/`2` or `T`/`F` for true/false.
- **Accessibility (Media Translation):** screen-reader announcements for feedback and the one-minute warning, 44px tap targets, and a warning before leaving an exam in progress.

### IDP Competency Certification
- **Topic selection** from the full IDP review question banks.
- **40 to 200 questions** per quiz.
- **Learn or Exam mode**, with 30 or 60 seconds per question in Exam mode.
- **Reference Library** to browse the material without taking a test.
- **Results:** retry the same setup, start a new quiz, or show only wrong answers.
- **Jump to question** navigation.
- Question bank compiled by Hussain Shehab. For personal study only.

---

## المميزات (عربي)

### الترجمة الإعلامية · ME 4245 · ME 4441
- **وضعين:** *التعلم* بدون وقت، ويشرح لك الإجابة الصحيحة بعد كل سؤال. *الاختبار* بوقت محدد، والتصحيح في النهاية.
- **عربي / إنجليزي:** تختار لغة الأسئلة قبل ما تبدأ.
- **اختيار المحاضرات:** محاضرة وحدة أو أكثر (ME 4441 فيه موديول واحد).
- **عدد أسئلة تختاره أنت.**
- **مراجعة بعد الاختبار:** تشوف كل الإجابات أو أخطاءك بس.
- **ملخصات المحاضرات** داخل الاختبار نفسه.
- **اختصارات الكيبورد:** `1`–`4` للاختيار من متعدد، و `1`/`2` أو `T`/`F` لصح وخطأ.
- **إمكانية الوصول (الترجمة الإعلامية):** قارئ الشاشة ينطق التصحيح وتنبيه آخر دقيقة، وأزرار بحجم 44px، وتنبيه لو حاولت تطلع والاختبار شغال.

### IDP Competency Certification
- **اختيار المواضيع** من بنوك أسئلة مراجعة IDP كاملة.
- **من 40 إلى 200 سؤال** في الاختبار الواحد.
- **وضع تعلم أو اختبار**، والاختبار فيه 30 أو 60 ثانية لكل سؤال.
- **مكتبة مرجعية** تتصفح فيها المادة بدون اختبار.
- **النتائج:** تعيد نفس الإعدادات، أو تبدأ اختبار جديد، أو تعرض أخطاءك بس.
- **انتقال مباشر** لأي سؤال.
- بنك الأسئلة من إعداد Hussain Shehab، وللمذاكرة الشخصية فقط.

---

## Tech / التقنية

Plain HTML, CSS and vanilla JavaScript in a single file per quiz. The only external resource is the IBM Plex Sans Arabic font from Google Fonts. The language choice is saved in `localStorage`.

HTML و CSS و JavaScript عادي، وكل اختبار في ملف واحد. الشي الخارجي الوحيد هو خط IBM Plex Sans Arabic من Google Fonts. اختيار اللغة ينحفظ في `localStorage`.
