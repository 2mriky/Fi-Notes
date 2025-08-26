<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README موجز - تطبيق Finote</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #0056b3;
            border-bottom: 1px solid #eee;
            padding-bottom: 8px;
            margin-top: 15px;
        }
        h1 {
            font-size: 2em;
            text-align: center;
            border-bottom: none;
            color: #333;
        }
        h2 {
            font-size: 1.5em;
        }
        p {
            margin-bottom: 8px;
        }
        ul {
            list-style: disc;
            margin-left: 18px;
            margin-bottom: 8px;
        }
        code {
            background-color: #eee;
            padding: 1px 3px;
            border-radius: 3px;
            font-family: 'Courier New', Courier, monospace;
            font-size: 0.9em;
        }
        pre {
            background-color: #eee;
            padding: 8px;
            border-radius: 4px;
            overflow-x: auto;
            font-size: 0.9em;
        }
        strong {
            color: #0056b3;
        }
        hr {
            border: 0;
            height: 1px;
            background: #eee;
            margin: 20px 0;
        }
        .icon {
            margin-left: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>تطبيق <i class="fas fa-money-bill-wave icon"></i> Finote – مصاريف + نوتس <i class="fas fa-clipboard icon"></i></h1>
        <p>Finote هو تطبيق ويب بسيط وفعال لإدارة الأموال الشخصية والملاحظات. يتيح لك تتبع الدخل والمصروفات، إدارة المدخرات، وتنظيم الملاحظات، بالإضافة إلى مدير كلمات مرور مدمج.</p>

        <hr>

        <h2><i class="fas fa-star icon"></i> الميزات</h2>
        <ul>
            <li><strong>المعاملات:</strong> تسجيل وتتبع الدخل والمصروفات، تصفية وفرز، تعديل وحذف.</li>
            <li><strong>المدخرات:</strong> تتبع المدخرات، إضافة أهداف ادخارية، سجل المعاملات.</li>
            <li><strong>كلمات المرور:</strong> حفظ وعرض وتعديل كلمات المرور محليًا، بحث وفلاتر.</li>
            <li><strong>النوتس:</strong> إنشاء وتعديل وتثبيت الملاحظات مع دعم المرفقات (صور).</li>
            <li><strong>تقسيم الفواتير:</strong> أداة لتقسيم الفواتير وحفظ حصتك كمصروف.</li>
            <li><strong>رسوم بيانية:</strong> تمثيل مرئي لتدفقات الأموال.</li>
            <li><strong>تعدد اللغات:</strong> دعم العربية والإنجليزية.</li>
            <li><strong>الوضع الليلي/النهاري:</strong> تبديل المظهر.</li>
            <li><strong>تصدير البيانات:</strong> تصدير إلى JSON أو CSV للنسخ الاحتياطي.</li>
        </ul>

        <hr>

        <h2><i class="fas fa-rocket icon"></i> البدء السريع</h2>
        <p>Finote هو تطبيق ويب يعمل بالكامل من جانب العميل. للاستخدام:</p>
        <ol>
            <li><strong>استنساخ المستودع:</strong>
                <pre><code>git clone https://github.com/YourUsername/Finote.git</code></pre>
            </li>
            <li><strong>فتح <code>index.html</code>:</strong> افتح الملف في أي متصفح ويب.</li>
            <li>ابدأ الاستخدام مباشرة!</li>
        </ol>

        <hr>

        <h2><i class="fas fa-info-circle icon"></i> ملاحظات فنية وأمان</h2>
        <ul>
            <li>مبني بـ <strong>HTML, CSS, JavaScript</strong>.</li>
            <li>يستخدم <strong>localStorage</strong> للتخزين المحلي، مما يعني أن بياناتك خاصة بجهازك.</li>
            <li>**كلمات المرور تُخزن محليًا بدون تشفير إضافي:** تأكد من أمان جهازك.</li>
        </ul>

        <hr>

        <h2><i class="fas fa-handshake icon"></i> المساهمة</h2>
        <p>نرحب بالمساهمات! قم بعمل <code>fork</code>، أنشئ فرعًا، قم بالتغييرات، ثم أرسل طلب سحب.</p>

        <p style="text-align: center; margin-top: 25px;">نتمنى لك تجربة ممتعة مع Finote!</p>
    </div>
</body>
</html>
