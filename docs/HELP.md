# SwelTask Help · دليل SwelTask

**Small steps. Clear mind. · خطوات صغيرة، ذهن أصفى.**

Windows Portable task manager · تطبيق مهام محمول لـWindows

[العربية](#العربية) · [English](#english)

## العربية

### البداية السريعة
1. فك ضغط نسخة التطبيق كاملة داخل مجلد قابل للكتابة، ثم شغّل `SwelTask.exe` أو `run.bat`.
2. من الأيقونات فوق الشجرة أضف فولدرًا ثم صفحة. الإنشاء فوري باسم يحتوي التاريخ والوقت. حدد العنصر واضغط **F2** لتغيير اسمه داخل الشجرة؛ **Enter** للحفظ و**Esc** للإلغاء.
3. افتح الصفحة، واكتب عنوان مهمة في السطر العلوي ثم **Enter**. تقدر تضيف التالية مباشرة. زر **+** يضيف مهمة أيضًا؛ لو السطر فارغ يضاف اسم مؤقت.
4. علامة الإكمال تنهي المهمة. ضغطتان على العنوان تفتحان تفاصيلها داخل الصفحة.

### تنظيم المهام
- الفولدرات تحتوي فولدرات وصفحات، والصفحات تفتح في تبويبات. إغلاق التبويب لا يحذف الصفحة.
- سهم الشجرة يفتح الفروع عند الحاجة. أيقونة الشجرة أعلى النافذة تطوي الشريط الجانبي.
- قائمة **⋯** بجوار الشجرة تعرض إعادة التسمية والنقل والترتيب والحذف. القائمة بجوار سطر الإضافة تعرض إضافة مهمة فرعية وعمليات المهمة المحددة.
- اسحب مهمة فوق أخرى لتصبح فرعية، أو فوق صفحة لنقلها. النقل داخل أحد فروع العنصر مرفوض. السهمان داخل قائمة العمليات يرتبان العناصر في نفس المستوى.
- **Ctrl+F** يظهر البحث في العناوين والملاحظات داخل العرض الحالي. عرض «الكل» يشمل كل الصفحات. اليوم والقادمة والمتأخرة تعتمد على تاريخ الجهاز المحلي.

### التفاصيل والتكرار والتنبيهات
تفاصيل المهمة داخل نفس النافذة. الملاحظات والمواعيد والتكرار أقسام مطوية؛ افتح فقط ما تحتاجه. الحفظ يطبق التعديلات، والإغلاق يسأل قبل تجاهل تغييرات غير محفوظة. يمكن اختيار نافذة الإضافة التقليدية من **الإعدادات ← عام**.

- التاريخ إلزامي للتكرار. الوقت اختياري بصيغة `HH:mm`.
- التكرار يدعم يوميًا وأسبوعيًا وشهريًا وسنويًا، وفاصلًا مخصصًا، وأيام الأسبوع، وتاريخ نهاية أو عدد مرات. الخيارات الإضافية تظهر عند اختيار التكرار ثم فتح سهم الخيارات.
- إكمال المرة يولد المرة التالية، مع الاحتفاظ بسجل الإنجاز. المواعيد الفائتة لا تُتخطى تلقائيًا. يوم 31 ينتقل لآخر يوم بالشهر القصير ثم يعود ليوم 31 عندما يتاح.
- إكمال المهام الفرعية لا يكمل الأم تلقائيًا. إكمال الأم مع فروع غير مكتملة يطلب التأكيد. المهام الفرعية تُنسخ للمرة التالية من الأم بعنوانها وملاحظاتها دون مواعيدها وتنبيهاتها. استخدام تكرار مستقل للفرع مع تكرار الأم قد ينتج مرة مستقلة إضافية؛ راجع القاعدة عند تنظيم المهام المتكررة.
- التنبيهات تُفحص كل 15 ثانية أثناء تشغيل التطبيق أو وجوده في Tray، مع تأجيل 10 دقائق. الخروج النهائي وإطفاء الجهاز يوقفان التنبيهات؛ الفائت يظهر عند التشغيل. راجع الأوقات بعد تغيير المنطقة الزمنية.

### الإعدادات ومحرر INI
من **☰ ← الإعدادات** اختر اللغة والثيم وحجم الواجهة **صغير / وسط / كبير**. حفظ يطبق الاختيارات معًا؛ إغلاق يلغيها. «صغير» هو الوضع الافتراضي، ويمكن تغيير حجم النافذة بحرية.

محرر `settings.ini` في تبويب الملفات. يبدأ النص من أعلى اليسار دائمًا، ويدعم البحث والتحقق وإعادة التحميل. **Save** يعيد القيم إلى الإعدادات، ثم حفظ الإعدادات يطبقها. إعادة التحميل تقرأ الملف المحفوظ بعد تأكيد تجاهل تعديلات المحرر. القيم غير الصالحة أو المفاتيح غير المعروفة تُرفض؛ التعليقات والتنسيق يُعاد تنظيمهما عند الحفظ. رابط التحديث معدّ مسبقًا ولا يظهر كحقل في الإعدادات العادية؛ فحص التحديثات يعمل من الزر مباشرة.

### النسخ الاحتياطي والترقية
**☰ ← البيانات والنسخ الاحتياطي** يجمع النسخ والاستعادة واستيراد وتصدير JSON. الاستيراد والاستعادة يستبدلان مساحة العمل بعد التحقق ونسخة احتياطية، ولا يدمجان البيانات. النسخ داخل `data/backups`، ويفضل الاحتفاظ بنسخة خارج المجلد أيضًا.

المحذوفات تستعيد العناصر وآباءها اللازمين. لا يوجد حذف نهائي في هذه النسخة.

عند الترقية: اخرج نهائيًا، خذ نسخة من مجلدك، وفك الإصدار الجديد في مجلد آخر. انسخ `data` و`settings.ini` من النسخة القديمة إلى الجديدة، ثم افتح الجديدة. لا تستبدل بياناتك ببيانات اختبار ولا تزامن قاعدة SQLite أثناء تشغيلها. ترقية الواجهة القديمة تحفظ نسخة إعدادات قبل ضبط الحجم الافتراضي الجديد.

### تنزيل نسخة التجربة من GitHub Actions
الحصول على نسخة التطوير يحتاج صلاحية المستودع الخاص وتسجيل الدخول إلى GitHub. افتح **Actions** ثم تشغيلًا ناجحًا للنسخة المطلوبة. من **Artifacts** نزّل **SwelTask-v0.2.0-Windows-Portable**. فك الضغط كاملًا وشغّل التطبيق من المجلد المستخرج. ملف **Source code ZIP** أو زر **Code → Download ZIP** لا يحتويان EXE جاهزًا. النسخ التجريبية تنتهي صلاحية تنزيلها بعد مدة الاحتفاظ المحددة في Actions.

### حل المشاكل والخصوصية
- لو ظهر أن التطبيق مفتوح بالفعل، راجع أيقونة Tray واستخدم فتح أو خروج نهائي.
- لو إعدادات البداية غير صالحة، احتفظ بنسخة من `settings.ini` ثم غيّر اسمه لإعادة الإعدادات الافتراضية.
- البيانات محلية، بدون حسابات أو Telemetry أو مزامنة فعلية. ملف الأخطاء محلي؛ راجعه قبل مشاركته.
- فحص التحديثات يتصل بملف التحديث الرسمي عند الضغط على الزر. لا يُثبت أي تحديث تلقائيًا. واجهة فتح/حفظ الملفات التابعة لـWindows تتبع إعدادات النظام.
- عند الإبلاغ عن مشكلة اذكر الإصدار والخطوات والنتيجة المتوقعة والفعلية، وصورة بعد إخفاء البيانات الحساسة.

## English

### Get started
Extract the entire portable build to a writable folder. Run `SwelTask.exe` or `run.bat`. The source-code ZIP is not a runnable build.

Create a folder/page with the icons above the tree. Creation is immediate with a timestamped default name. **F2** renames the selected item inline; **Enter** saves, **Esc** cancels. Open a page, write a task above the list and press **Enter**. The + button also adds a task; a blank input creates a temporary name.

### Organize and focus
Folders contain folders/pages; pages open in tabs. Closing a tab never deletes its page. Arrows expand branches on demand. The top tree icon collapses the sidebar. Each **⋯** menu contains actions for its selected item: rename, move, order, delete/restore, or task details/subtasks. Drag a task onto a task to nest it, onto a page to move it, or onto empty page space to make it a root task. Cycles are rejected.

**Ctrl+F** reveals search for titles/notes within the current view. All searches every page. Today/Upcoming/Overdue use local dates and show incomplete tasks.

### Details, recurrence and reminders
Double-click a task for inline details. Notes, dates/reminders and recurrence are collapsed initially and constructed on first opening. Save applies changes; discarding unsaved edits requires confirmation. Enable **Open details dialog when adding tasks** in Settings → General if preferred.

Recurring tasks need a due date. Select daily/weekly/monthly/yearly and open repeat options for interval, weekdays, completion basis, end date or count. Completing one occurrence creates the next and retains history. Missed dates are not silently skipped. Month-end clamping preserves the original day. Parent completion asks before completing unfinished descendants; completing children never completes the parent automatically. Parent recurrence copies child titles/notes but clears child dates/reminders/recurrence. Independently recurring children can also generate another occurrence in the old parent; use intentionally. Completed recurring occurrences cannot be reopened in this version.

Reminders check every 15 seconds while the process is running/in tray. Snooze is 10 minutes; missed reminders appear on startup. Exit, OS sleep and power-off stop checks until the process resumes. Review times after a time-zone change.

### Settings and INI
Settings groups General, Appearance, Files and Help. Small/Medium/Large changes fonts and spacing together; Small is default. Save applies, Close cancels. The INI editor starts at the top left in every language. Find, Validate, Reload, Save and Close are available. Saving the editor updates the pending settings; save Settings to apply. Reload reads disk after confirmation. Unknown keys/invalid values are rejected; formatting/comments normalize on save. The update URL is preconfigured and not exposed as an ordinary field.

### Data, updates and troubleshooting
Main menu ☰ → Data & backup groups backup/restore/JSON import/export. Import/restore replaces the workspace after validation and a backup; it does not merge. Backups are in `data/backups`; keep external copies too. Recycle bin restores items and required ancestors. No permanent-delete command is provided.

Exit before moving/copying/upgrading. Back up the old folder, extract the new version elsewhere, then copy your `data` folder and `settings.ini` into the new version. Never cloud-sync a running SQLite database. A pre-compact-settings backup is made when migrating old UI settings.

To test from GitHub, sign in with access to the private source repository, open a successful Actions run, and download **SwelTask-v0.2.0-Windows-Portable** from Artifacts. Extract everything; do not run inside the ZIP. Artifacts expire according to the run's retention policy. Public final releases are separate from development artifacts.

Use the tray menu if the app is already running. If settings prevent startup, keep a copy of `settings.ini`, rename it and restart for defaults. Report version, reproduction steps, expected/actual result and a redacted screenshot. Error logs remain local. No accounts, telemetry or actual sync. Update checks fetch the official manifest only when requested and never install automatically. Native Windows file pickers follow the OS appearance.

### Status and support
SwelTask 0.2.0 is an owner-testing build, not a claim of final acceptance or production readiness. Physical DPI, assistive-input behavior and reminder timing across sleep/resume require device testing.

