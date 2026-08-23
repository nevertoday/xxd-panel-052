<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 052 project banner" width="1200"></p>

<div align="center" dir="rtl">

# 🦁 XXD Panel 052

### جعل عالم مصغّر يدوي يطفو على خط منظر واحد

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-EF805E?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-4AA1AE?style=flat-square)](#)

<a href="README.md">简体中文</a> مجسّم ورقي · شريط أفقي عائم · مادة يدوية أصيلة · أزرق بارد هوائي · فراغ واسع

يُعاد بناء أكثر موضوعات المصدر تميّزاً والعناصر البيئية القليلة المدعومة كمجسّمات من الورق والبطاقات والطين اللين والخشب الرقيق فوق شريط منظر أفقي طويل عائم. وتصنع تفاصيل اليد وضوء الماكرو والفراغ الفاتح الواسع حضور تركيب فني راقٍ.

## لماذا توجد هذه المهارة؟

يعتمد الأسلوب على المصدر وليس قالباً زخرفياً يمكن تبديل محتواه. ويتبع سلسلة التحويل الآتية:

```text
lock identity, silhouette, pose, direction, and relation → preserve three cues → select one primary subject and limited supported elements → rebuild paper, cardstock, soft-clay, and thin-wood miniatures → place them on one long horizontal floating strip → establish scale depth, overlap, and calm balance → reveal authentic craft through macro light → retain airy cool blue and generous space → add one signature-like short title
```

إذا أمكن استبدال المصدر بصورة لا صلة لها من دون تغيير جوهري في التعرّف وبناء المجسّم والعناصر المساندة ومحيط الشريط والمادة والتوازن واللون والفراغ والنص، فالنتيجة لا تنتمي إلى هذا Panel.

## العقد البصري

- تُحفظ ثلاث علامات خاصة بالمصدر على الأقل من المحيط والنسبة والوضع والاتجاه والفعل والبنية واللون والمادة والعلاقة.
- يُبنى موضوع رئيس واحد مع عدد محدود من المجسّمات المساندة فوق شريط منظر أفقي واحد طويل وضيق وخفيف.
- يُصنع العمق بتفاوت الحجم والتراكب وهدوء المقدمة والخلفية، مع تمركز عام من دون تناظر آلي أو بؤرة ثانية.
- تظهر ألياف الورق والطيات وآثار القطع وسماكة الطبقات والحواف الخشنة والعيوب اليدوية الصغيرة، ويُرفض CGI البلاستيكي الأملس.
- تُنظم درجات الأزرق البارد الهوائي والعاجي والبيج الفاتح والأخضر المكتوم ولمسات وردية ضئيلة بضوء ماكرو ناعم وفراغ فاتح واسع.

توجد القيود الجمالية وقواعد الرفض الكاملة في المهارة وتوجيهات الإنتاج. وهي تحفظ دافع النص الأصلي من دون تحويل لوحة 3:4 التاريخية إلى قيمة افتراضية خفية. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-052-prompt.en.md)

## النماذج

لم تُقدّم نماذج بعد. يوثَّق موضعها المحجوز في [assets/examples](assets/examples/README.md). وستعرض النماذج المستقبلية الدافع الجمالي فقط، ولن تصبح مراجع للتوليد أو موضوعات أو تراكيب أو ألواناً أو نصوصاً أو مقاسات افتراضية ثابتة.

## أربعة مخرجات قابلة للجمع

اختر نمطاً واحداً أو عدة أنماط بـ `1` أو `1+3` أو `1,2,4` أو `الكل`. ينتج «الكل» سبعة ملفات PNG لكل مصدر: ثلاثة مخرجات عادية وأربع خلفيات.

| النمط | المقاس عند غياب التحديد | الناتج |
| --- | --- | --- |
| `top-bottom` | متكيف مع المصدر `W×2H` | الأصل كاملاً في الأعلى والتصميم المتحوّل في الأسفل، بنسبة 50/50 دقيقة |
| `left-right` | متكيف مع المصدر `2W×H` | الأصل كاملاً في اليسار والتصميم المتحوّل في اليمين، بنسبة 50/50 دقيقة |
| `design-only` | متكيف مع المصدر `W×H` | التصميم المتحوّل وحده من دون ظهور الأصل |
| `wallpaper-pack` | مقاسات مسمّاة لكل جهاز | ملفات PNG منفصلة للهاتف وiPad والحاسوب وساعة الأطفال |

قد تكون الخلفيات مترابطة أو مستقلة. تعتمد المجموعة المترابطة عملاً مرجعياً واحداً ثم يرجع كل جهاز إلى الأصل وإلى المرجع نفسه، من دون قص أو سلسلة مشتقات. أما المستقلة فيرجع كل جهاز فيها إلى الأصل فقط.

## النص واللغة

يُحسم قبل التوليد النص التلقائي أو النص الدقيق المخصص أو غياب النص. تتبع اللغة الجمهور المقصود لا لغة الأمر، ويبقى نص المستخدم النهائي حرفياً.

قاعدة النص الخاصة بالمشروع: يُستخلص عنوان قصير واحد من المكان أو هوية الموضوع أو الفكرة أو الشعور، وتوضع الكتابة الأصلية للغة المستهدفة صغيرة وراقية وبلمسة خط يدوي تحت الشريط أو بمحاذاة قاعدته أو داخل فضائه، لتبدو كتوقيع فنان لا كعنوان تجاري.

## الهندسة والصورة النقطية والثقة

تتكيف الأنماط العادية مع المصدر ما لم يرد مقاس صريح، وتنقسم التركيبات الثنائية 50/50 بدقة، وكل النتائج ملفات PNG نقطية. ينشئ كل استدعاء مهمة جديدة تحت `~/Desktop/xxd/` ولا يكشف معلومات مسار التوليد الخاصة.

لا يعيد جسر الصور المضبوط إلا حالة منزوعة التفاصيل، ولا يكشف المزوّد أو نقطة الاتصال أو بيانات الاعتماد أو الرؤوس أو التوجيه أو الاستجابة أو معلومات الحساب. ولا تصلح SVG أو HTML أو Canvas أو الرسوم البرمجية بديلاً للعمل النقطي النهائي.

## البدء

```bash
git clone https://github.com/nevertoday/xxd-panel-052.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-052" ~/.codex/skills/xxd-panel-052
```

يمكن لمستخدمي Claude Code ربط المجلد نفسه بالمسار: `~/.claude/skills/xxd-panel-052`. أعد تشغيل جلسة الوكيل بعد التثبيت.

```text
$xxd-panel-052
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

المواصفات الكاملة: [مسار عمل المهارة](SKILL.md) · [أرشيف الأسلوب الأصلي](references/052-source.md) · [توجيه الإنتاج الإنجليزي](references/xxd-panel-052-prompt.en.md) · [توجيه الإنتاج الصيني](references/xxd-panel-052-prompt.zh-CN.md)

## عن XXD

XXD هو اختصار اسم علامة Xiaoxiaodong. أنشأ المشروع ويديره: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## الدعم والعضوية

### استشارة متعمقة · 299 يواناً/ساعة

استشارة فردية متعمقة في استخدام Skills ومسار العمل. تواصل مع Xiaoxiaodong عبر WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### مجموعة مستخدمي Xiaoxiaodong Skills · 99 يواناً

تتيح دفعة واحدة الانضمام إلى مجموعة مستخدمي Skills لتبادل المسارات والنقاش؛ والاستشارة الفردية بالساعة منفصلة.

### Knowledge Planet＋مكتبة توجيهات الأعضاء · 699 يواناً/سنة

يفتح دفع سنوي واحد قدره 699 يواناً كلاً من Knowledge Planet ومكتبة التوجيهات. بعد الاشتراك في Knowledge Planet، تواصل مع Xiaoxiaodong عبر WeChat للحصول على رمز استرداد مكتبة التوجيهات؛ وبعد التفعيل الذاتي في المكتبة، تواصل عبر WeChat للحصول على دعوة إلى Knowledge Planet.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center" dir="rtl"><strong>يحمل شريط منظر خفيف تفصيل الحياة اليومية الجدير بالتذكر.</strong></div>

---

<div align="center" dir="rtl">

## ☕ دعم المشروع المفتوح المصدر

تستخدم النسخ غير الصينية Buy Me a Coffee. الدعم اختياري ولا يغيّر الوصول إلى المشروع المفتوح المصدر.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
