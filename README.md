# Studying: Interactive Practice Quizzes

Practice quizzes that run in the browser, on phone or desktop. Each one is a single HTML file with no framework and no backend, hosted on GitHub Pages.

اختبارات تدريبية تفاعلية تشتغل من المتصفح، على الجوال أو الكمبيوتر. كل اختبار ملف HTML واحد، بدون framework ولا backend، ومستضافة على GitHub Pages.

## Quizzes / الاختبارات

| Quiz / الاختبار | Questions / الأسئلة | Link / الرابط |
|---|---|---|
| Media Translation / الترجمة الإعلامية | 81 | [Open](https://selflearninghelper.github.io/studying/media-translation-quiz/) |
| ME 4441 Engineering Management / الإدارة الهندسية | 70 | [Open](https://selflearninghelper.github.io/studying/me4441-quiz/) |
| ME 4245 Renewable Energy, True or False / الطاقة المتجددة، صح وخطأ | 290 | [Open](https://selflearninghelper.github.io/studying/me4245-TrueOrFalse/) |
| IDP Competency Certification | 822 | [Open](https://selflearninghelper.github.io/studying/idp-certification-quiz/) |

**Every question is checked against its source.** All 1,263 answers were matched to the original lecture slides or question-bank files, including slides that are images only.

**كل سؤال متطابق مع مصدره.** الـ 1,263 إجابة كلها تمت مطابقتها مع السلايدات أو ملفات بنك الأسئلة الأصلية، حتى السلايدات اللي نصها صور.

## Features / المميزات

| Feature / الميزة | Media Translation | ME 4441 | ME 4245 | IDP |
|---|:-:|:-:|:-:|:-:|
| Learn mode with instant feedback, and timed Exam mode<br>وضع تعلم بتصحيح فوري، ووضع اختبار بوقت | ✓ | ✓ | ✓ | ✓ |
| Flashcards: recall the answer, then flip to check<br>بطاقات: تتذكر الجواب وتقلب البطاقة تتأكد | ✓ | ✓ | | ✓ |
| Arabic / English questions<br>الأسئلة بالعربي أو الإنجليزي | ✓ | ✓ | ✓ | |
| Arabic translation under English slide quotes<br>ترجمة عربية تحت الشروحات المنقولة من السلايدات | ✓ | ✓ | ✓ | |
| Pick lectures or topics<br>اختيار المحاضرات أو المواضيع | ✓ | | ✓ | ✓ |
| Question count fits the selection (under 10 = all of them)<br>عدد الأسئلة يناسب اختيارك (أقل من 10 = كلها) | ✓ | ✓ | ✓ | ✓ |
| Open the full topic behind a question (summary, or IDP's reference library)<br>تفتح الموضوع كامل اللي جاي منه السؤال (من الملخص، أو المكتبة المرجعية في IDP) | ✓ | ✓ | ✓ | ✓ |
| Search the summaries or reference library<br>البحث في الملخصات أو المكتبة المرجعية | ✓ | ✓ | ✓ | ✓ |
| Review screen with mistakes-only filter<br>مراجعة بعد الاختبار، مع عرض الأخطاء فقط | ✓ | ✓ | ✓ | ✓ |
| Correct-answer streak and score celebration<br>سلسلة الإجابات الصح واحتفال بالنتيجة | ✓ | ✓ | ✓ | ✓ |
| Keyboard shortcuts<br>اختصارات الكيبورد | ✓ | ✓ | ✓ | ✓ |
| Dark / light theme that follows the device<br>وضع داكن وفاتح يتبع الجهاز | ✓ | ✓ | ✓ | ✓ |
| One-minute warning and leave warning in exams<br>تنبيه آخر دقيقة وتنبيه قبل الخروج من الاختبار | ✓ | ✓ | | |

The IDP question bank is by Hussain Shehab and used with his permission.

بنك أسئلة IDP من إعداد Hussain Shehab، ومستخدم بإذنه.

## Why I built this

I started with this for myself. Some of my courses were hard and rereading didn't help. What worked was studying through questions: answer, see right away why it's right or wrong, and check the summary in the same place. Studying from something that doesn't look like the usual slides also made studying feel lighter.

It made a big difference for me, so now I build it for other students too.

## ليش سويتها

بديت بهذي الطريقة لنفسي. كانت عندي مواد صعبة، وكثرة القراءة ما كانت تنفع. اللي نفع إني أذاكر بالأسئلة: أجاوب، وأعرف فورًا ليش صح أو ليش غلط، وأرجع للملخص في نفس المكان. ولاحظت إن المذاكرة من شي شكله مختلف عن السلايدات اللي تعودنا عليها تخلي المذاكرة أخف على النفس.

فرقت معي كثير، فصرت أسويها لغيري.

## Tech / التقنية

Plain HTML, CSS and JavaScript, one file per quiz. The only external resource is the IBM Plex Sans Arabic font from Google Fonts. Language and theme choices are saved in `localStorage`.

HTML و CSS و JavaScript عادي، وكل اختبار في ملف واحد. الشي الخارجي الوحيد هو خط IBM Plex Sans Arabic من Google Fonts. اختيار اللغة والثيم ينحفظ في `localStorage`.
