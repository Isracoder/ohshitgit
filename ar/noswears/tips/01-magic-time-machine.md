---
tags: tip
title: <div class="rtl"> يا للهراء , لقد اخطأت كثيراً , ارجوك اخبرني انه يوجد في git طريقة سحرية للانتقال عبر الزمن !؟ </div>
id: آلة-زمن-سحرية
order: 1
---

<div class="rtl">

```git
git reflog
# سوف ترى قائمة تحوي كل التغيرات
#  branches على نطاق جميع ال, git في
# لكل منها يوجد index HEAD@{index}
# لذا اختر المناسبة التي تم حفظها
# قبل ان دمرت كل شيء,ثم
git reset HEAD@{index}
# الة تغيير الزمن السحرية !
```

تستطيع ان تستخدم هذا لاسترجاع ما حذفته خطأً, أو لمجرد ازالة بعض الامور التي جربتها و افسدت ال repo
أو للتعافي بعد merge خاطئ
أو حتى الرجوع إلى نقطة في الزمن كان كل شيء يعمل .
أنا استخدم "reflog" كثيراً
فلذا ارفع قبعتي مرات عدة احتراماً لكل من اقترح اضافته!

</div>