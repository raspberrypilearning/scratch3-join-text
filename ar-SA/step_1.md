يمكنك استخدام `اربط`{:class="block3operators"} من كتلة `العمليات`{:class="block3operators"}لضم النص والمتغيرات لإنشاء نصوص أطول.

اسحب `اربط`{:class="block3operators"} إلى الكتلة حيث تريد استخدامها:

```blocks3
say (join [apple ] [banana]) for [2] seconds
```

استبدل النص بالنص الذي تريد استخدامه ، أو اسحب متغيرًا:

```blocks3
set [الاسم v] to [Scratch]
say (join [أهلا أنا ] (الاسم)) for [2] seconds
```

**نصيحة: كتلة** `اربط`{:class="block3operators"} لا تضيف مسافات لذلك سوف تحتاج إلى كتابتها.

يمكنك سحب كتلة `اربط`{:class="block3operators"} داخل كتلة `اربط`{:class="block3operators"}ثانية لإنشاء سلاسل نصية أطول:

```blocks3
say (join [أهلا أنا ] (join (الاسم) [ القط])) for [2] seconds
```

لاحظ "الفراغ" في نهاية `مرحبًا ، أنا` وبداية `القط`.

