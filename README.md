<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة أوزغور لتعلم التركية 🇹🇷</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        :root { --tr-red: #e30a17; --tr-dark: #212529; }
        body { background-color: #f4f7f6; font-family: 'Cairo', sans-serif; }
        .hero { background: var(--tr-dark); color: white; padding: 60px 0; border-bottom: 5px solid var(--tr-red); }
        .search-box { max-width: 600px; margin: -30px auto 30px; }
        .category-card { background: white; border-radius: 15px; padding: 20px; margin-bottom: 30px; shadow: 0 4px 6px rgba(0,0,0,0.1); }
        .word-item { border-bottom: 1px solid #eee; padding: 10px 0; display: flex; justify-content: space-between; align-items: center; }
        .word-item:last-child { border: none; }
        .tr-text { font-weight: bold; color: var(--tr-red); font-size: 1.2rem; }
        .ar-text { color: #555; }
        .badge-cat { background: var(--tr-red); color: white; margin-bottom: 15px; }
        footer { background: #111; color: white; padding: 30px 0; margin-top: 50px; }
    </style>
</head>
<body>

<div class="hero text-center">
    <h1 class="display-4 font-weight-bold">🇹🇷 أكاديمية أوزغور للغة التركية</h1>
    <p class="lead">أكبر مرجع لتعلم الكلمات والجمل التركية مجاناً</p>
</div>

<div class="container mt-5">
    <div class="search-box">
        <input type="text" id="searchInput" class="form-control form-control-lg shadow" placeholder="ابحث عن كلمة بالعربي أو التركي...">
    </div>

    <div class="row" id="wordsContainer">
        <div class="col-md-6 category-section">
            <div class="category-card shadow-sm">
                <span class="badge badge-cat">🔢 الأرقام (Sayarlar)</span>
                <div class="word-list">
                    <div class="word-item"><span class="tr-text">Sıfır</span> <span class="ar-text">صفر</span></div>
                    <div class="word-item"><span class="tr-text">Bir</span> <span class="ar-text">واحد</span></div>
                    <div class="word-item"><span class="tr-text">İki</span> <span class="ar-text">اثنان</span></div>
                    <div class="word-item"><span class="tr-text">Üç</span> <span class="ar-text">ثلاثة</span></div>
                    <div class="word-item"><span class="tr-text">Dört</span> <span class="ar-text">أربعة</span></div>
                    <div class="word-item"><span class="tr-text">Beş</span> <span class="ar-text">خمسة</span></div>
                    <div class="word-item"><span class="tr-text">On</span> <span class="ar-text">عشرة</span></div>
                    <div class="word-item"><span class="tr-text">Yüz</span> <span class="ar-text">مئة</span></div>
                </div>
            </div>
        </div>

        <div class="col-md-6 category-section">
            <div class="category-card shadow-sm">
                <span class="badge badge-cat">📅 الوقت (Zaman)</span>
                <div class="word-list">
                    <div class="word-item"><span class="tr-text">Bugün</span> <span class="ar-text">اليوم</span></div>
                    <div class="word-item"><span class="tr-text">Yarın</span> <span class="ar-text">غداً</span></div>
                    <div class="word-item"><span class="tr-text">Dün</span> <span class="ar-text">أمس</span></div>
                    <div class="word-item"><span class="tr-text">Sabah</span> <span class="ar-text">صباح</span></div>
                    <div class="word-item"><span class="tr-text">Akşam</span> <span class="ar-text">مساء</span></div>
                    <div class="word-item"><span class="tr-text">Gece</span> <span class="ar-text">ليل</span></div>
                    <div class="word-item"><span class="tr-text">Hafta</span> <span class="ar-text">أسبوع</span></div>
                </div>
            </div>
        </div>

        <div class="col-md-6 category-section">
            <div class="category-card shadow-sm">
                <span class="badge badge-cat">🍽️ في المطعم (Restoran)</span>
                <div class="word-list">
                    <div class="word-item"><span class="tr-text">Su</span> <span class="ar-text">ماء</span></div>
                    <div class="word-item"><span class="tr-text">Ekmek</span> <span class="ar-text">خبز</span></div>
                    <div class="word-item"><span class="tr-text">Tuz</span> <span class="ar-text">ملح</span></div>
                    <div class="word-item"><span class="tr-text">Hesap lüften</span> <span class="ar-text">الحساب لو سمحت</span></div>
                    <div class="word-item"><span class="tr-text">Acı</span> <span class="ar-text">حار</span></div>
                    <div class="word-item"><span class="tr-text">Tatlı</span> <span class="ar-text">حلو</span></div>
                </div>
            </div>
        </div>

        <div class="col-md-6 category-section">
            <div class="category-card shadow-sm">
                <span class="badge badge-cat">🏥 الطوارئ (Acil)</span>
                <div class="word-list">
                    <div class="word-item"><span class="tr-text">Yardım et!</span> <span class="ar-text">ساعدني!</span></div>
                    <div class="word-item"><span class="tr-text">Hastane</span> <span class="ar-text">مستشفى</span></div>
                    <div class="word-item"><span class="tr-text">Eczane</span> <span class="ar-text">صيدلية</span></div>
                    <div class="word-item"><span class="tr-text">Doktor</span> <span class="ar-text">طبيب</span></div>
                    <div class="word-item"><span class="tr-text">Ağrı</span> <span class="ar-text">ألم</span></div>
                </div>
            </div>
        </div>
    </div>
</div>

<footer>
    <div class="container text-center">
        <h4>تطوير وتصميم: اوزغور السموقي</h4>
        <p>تم البرمجة باستخدام Python & HTML في نظام Kali Linux</p>
        <div class="mt-3">
            <a href="#" class="btn btn-outline-light btn-sm">تليجرام</a>
            <a href="#" class="btn btn-outline-light btn-sm">واتساب</a>
        </div>
    </div>
</footer>

<script>
    // نظام البحث الذكي
    document.getElementById('searchInput').addEventListener('keyup', function() {
        let filter = this.value.toLowerCase();
        let items = document.querySelectorAll('.word-item');
        
        items.forEach(function(item) {
            let text = item.textContent.toLowerCase();
            if (text.includes(filter)) {
                item.style.display = "";
            } else {
                item.style.display = "none";
            }
        });
    });
</script>

</body>
</html>
