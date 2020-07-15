# <p align="center"> المساعد واتسون</p>
### <div dir="rtl"> ، تقدم تقدم شركة (اي بي ام) أداة بناءروبوت دردشة يمكنك محاولته مجانا. يطلق عليه آي بي إم واتسون المساعد ويتيح لأي شخص الاستفادة من أحد أنظمة الذكاء الاصطناعي الأهم في الوجود.</div>


## <div dir="rtl">قبل إنشاء روبوت دردشة</div> 
#### <div dir="rtl"> أولا يجب عليك التوجه إلى صفحة واتسون المساعد والاشتراك. استخدم الحزمة المجانيةوالتي تتيح لك إنشاء شات بوت مجانا ومدنها 30يوم </div>
#### <p align="center"> [صفحة واتسون المساعد](https://www.ibm.com/cloud/watson-assistant/)</p>
=====================================================================================
# <div dir="rtl">إنشاء روبوت دردشة</div> 

### <div dir="rtl">انقر على "create a new assistant"الإنشاء مساعدك الخاص و املأ الفراغات بمايناسبك</div>
![much-a image](https://cloud.ibm.com/docs-content/v1/content/59ba62f924e3ea418436f195eaf966e3abf487e3/assistant/images/gs-create-assistant-done.png) 
## <div dir="rtl">ولان وقد أصبح لديك مساعد يجب أن تزوده بمهارات</div>

# <div dir="rtl">مهارات</div>

## <div dir="rtl"> هي بيانات مكونه من (نوايا, كيان وحوار) حتى يتسنى للربوت المشي في سير الحديث</div>
##### <div dir="rtl"> كل ماعليك فعله لصنع مهارة جديدة هو النقر على خانة *المهارات* ثم [*add dialoge skill*]</div>
![much-a image](https://help.brightpattern.com/images/3/35/Skills-View-API-53.PNG)




# <div dir="rtl">النوايا</div>

## <div dir="rtl">الغرض الأساسي من روبوت الدرشة هو تفسير ما يقوله المستخدم ثم معرفة ما يجب عمله حيال ذلك. فييوجد شيء يسمى نيةوهو الإجراء الذي يريد المستخدم تحقيقه بشكل أساسي</div>
![much-a image](https://cloud.ibm.com/docs-content/v1/content/59ba62f924e3ea418436f195eaf966e3abf487e3/assistant/images/gs-intents-page.png)
##### <div dir="rtl">  لتصنع اول نية  لروبوت الدردشة الخاص بك أنقر على  [*create intent*]</div>
<div dir="rtl"> أطلق عليه اسمًا ، وقدم له وصفًا وأضف العديد من الطرق التي يمكنك التفكير بها في أن المستخدم سيشير إلى هذه النية</div>


## <div dir="rtl">لا يحتاج أن تبدأ من الصفر فقد وفرت شركة "اي بي ام واتسون" نوايا مشتركة حتى لا تظطر لكتابة عناصر المحادثة الاساسية العامة مثل:الترحيب</div>
#### <div dir="rtl">انقر على [*كاتلوج المحتوى*] وأضف المهارات التي تريدها</div>
![much-a image](https://cloud.ibm.com/docs-content/v1/content/5c1b97d453d5af69d9a584a7d688a76333a13c1c/assistant/images/catalog-overview.png)




# <div dir="rtl">الكيان</div>

## <div dir="rtl">يتم تنفيذ النوايا على الكيانات، والتي تحتوي على المعلومات ذات الصلة التي سيستخدمها روبوت الدردشة للرد.</div>
![much-a image](https://cloud.ibm.com/docs-content/v1/content/5c1b97d453d5af69d9a584a7d688a76333a13c1c/assistant/images/entities-synonyms-added.png)
<div dir="rtl"> فكر بمفرده، وقدم له وصفًا وأضف العديد من الطرق التي يمكنك التفكير بها في أن المستخدم سيشير إلى تلك المفردة.ربما بعض الأخطاء الشائعة أو مرادفات لها</div>



# <div dir="rtl">الحوار</div>

## <div dir="rtl"> عند النقر على خانة  *إضافة حوار* يتم إنشاء عقدتي حوار تلقائيا ويمكنك النقر بالاعلى لإنشاء عقد اخرى تخدم الغرض  من روبوتك الدردشي</div>
![much-a image](https://cloud.ibm.com/docs-content/v1/content/5c1b97d453d5af69d9a584a7d688a76333a13c1c/assistant/images/gs-new-dialog.png)
### <div dir="rtl"> لتكون شجرة حوار أنقر على [*إضافة عقدة*] ثم ضع لها اسم يفيد من غرضها و اضف النية التي تخدم ذاك الغرض ولان تستطيع إضافة الرد بالاسفل مع اختيار نوعية الرد (نص,خيارات,صورةالخ..) و تستطيع ايضا وضع مجموعة ردور و ترتيب طريقة عرضها(عشوائيا,تدرجيا الخ...)</div>
![much-a image](https://cloud.ibm.com/docs-content/v1/content/5c1b97d453d5af69d9a584a7d688a76333a13c1c/assistant/images/gs-edit-welcome-node.png)


# <div dir="rtl">يمكن أن تتعامل العقدة الواحدة ذات شرط الاستجابة والرد مع طلبات الستخدم البسيطة, ولكن في أغلب الأحيا ن يكون لدى المستخدمين أسئلة أكثر تعقيد لهذا وجب في بعض الأحيان أن تضيف [*عقد تابعة*]  </div>
==============================================================
# <div dir="rtl">تجربة روبوت الدردشة</div>
### <div dir="rtl">هناك طريقتين لتجربة الروبوت الدردشة</div>
## <div dir="rtl">طريقة1</div>
### <div dir="rtl"> تستطيع النقر على![much-a image](https://cloud.ibm.com/docs-content/v1/content/5c1b97d453d5af69d9a584a7d688a76333a13c1c/assistant/images/try-it.png)في اعلى الصفحة والميوة في هذه الطريقة انك تستطيع تدريب الروبوت و تصحيح اغلاطه ليحسن أداءه</div>

## <div dir="rtl">طريقة2</div>
### <div dir="rtl"> اختر مساعدك اللذي تريد تجريبه ثم انقر على [*إضافة دمج*]و ستجد [*رابط معاينة*]</div>
![much-m image](https://cloud.ibm.com/docs-content/v1/content/5c1b97d453d5af69d9a584a7d688a76333a13c1c/assistant/images/gs-test-from-preview-link.png)

========================================================================
# <div dir="rtl">تصدير ودمج</div>
