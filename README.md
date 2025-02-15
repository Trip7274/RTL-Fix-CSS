# RTL-Fix.css
#### English  - الانجليزية
A janky fix for inconsistencies in how Discord handles RTL text in the message box. (Mainly focused at Arabic text, though),
Discord handles RTL text in the only way worse than improperly: *inconsistently*.

RTL text in the chat log is left-aligned, while the message box right-aligns it, which makes it a little annoying to use by requiring your eyes to play ping pong with your text and the chat log. This CSS snippet left-aligns any text in the message box.

Do keep in mind that I'm very inexperienced in React and its CSS syntax and am far from a developer in it, so I'm sure this can be improved and optimized further, but if it works, it works.

## How to use
This CSS snippet is only designed and tested to be used with [Vencord](https://vencord.dev/download/), it probably works with BetterDiscord or the alternatives, however, I haven't tested it and will not provide support (however, do feel free to submit pull requests to improve compatibility!)

Simply add `https://raw.githubusercontent.com/Trip7274/RTL-Fix-CSS/refs/heads/main/RTL-Fix.css` to your themes, and it should work. (User settings -> Themes -> Online Themes -> \[Paste the URL into the box\])

## Contributing
You're free to open an issue/PR for proposals, however, web-app CSS is *not* my expertise, so I may not be able to help much, sorry. (not that I won't at least try to!)

----
#### Arabic  -  ألعربية
### حول
هذا ثيم او قصاصة CSS تحل مشكلة إتجاهات الكتابة العربية في دسكورد، دسكورد يبدأ الكتابة العربية من اليمين اذا انت تكتب رسالة، بس كل الرسائل المرسلة تبدأ من اليسار، وذلك ممكن يسبب انزعاج وانت تتكلم باللغة العربية في دسكورد.

للعلم، انا لست مبرمج رياكت ولا مودات دسكورد، ولذلك هذا الثيم من الممكن ان يٌحسن من مطور أخبر مني في المجال هذا. بس اهم شي انه يسوي وظيفتة.

## كيفية الأستعمال
الثيم هذا مبني للاستعمال مع مود [Vencord](https://vencord.dev/download/) لدسكورد. يجب تحميل وتثبيته قبل استعمال هذا الثيم. قد يعمل مع BetterDiscord، ولكن انا لا انصح بذلك لانه لم يٌجرب ولن يٌدعم مني في حال عدم عملة في مود غير Vencord. (بس تقدر تساعد اذا مايشتغل وعندك خبره، الله يعطيك العافية!)

بكل بساطة، بعدما تثبت Vencord، أظف `https://raw.githubusercontent.com/Trip7274/RTL-Fix-CSS/refs/heads/main/RTL-Fix.css` الى ثيماتك عبر (User settings -> Themes -> Online Themes) ثم إلصاق الرابط في الفراغ الكبير.

## طرق ألمساعدة
هذا مشروع مفتوح المصدر، وهذا يعني ان، لو لديك خبره وشغف، تستطيع ان تبدأ Issue اعلاه او Pull request للشكوى عن مشاكل ممكنه او المساعده في التطوير.
أتمنى من أي شخص يريد المساعده هنا أن يكتب باللغة العربية والانجليزية اذ امكن، بذلك استخدام ادوات ذكاء اصطناعي او ترجمه حاسوبية (ترجمه قوقل)، او ترجمة يدوية. (لأن بعض الاشياء البرمجية ممكن أسهل للفهم بالانجليزي)
أنا قد لا استطيع المساعدة ببعض الاشياء بسبب عدم خبرتي بالمجال هذا، ولكن سأحاول تقديم ما أقدر عليه
