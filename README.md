<!DOCTYPE html>
<html lang="he" dir="rtl">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ז' באדר - לזכר חללי ישראל</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" defer></script>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8f9fa;
            color: #333;
        }

        header {
            background-color: #343a40;
            color: white;
            padding: 20px;
            text-align: center;
        }

        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

        .card {
            margin-bottom: 20px;
        }

        .placeholder {
            color: gray;
            text-align: center;
            padding: 50px 0;
            background-color: #f1f1f1;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <header>
        <h1>ז' באדר</h1>
        <p>פרויקט לזכר חללי ישראל שמקום קבורתם לא נודע</p>
    </header>

    <main class="container my-4">
        <section>
            <h2>על הפרויקט</h2>
            <p>פרויקט ז' באדר מוקדש לזכרם של חללי ישראל שמקום קבורתם לא נודע. מטרת האתר היא להנציח את שמם וסיפור חייהם
                באמצעות מידע שיאסף ויוצג כאן. האתר מאפשר גישה נוחה ומכובדת לכל אדם לקרוא ולהכיר את הגיבורים שנפלו
                עבור המדינה.</p>
        </section>

        <section class="mt-5">
            <h2>רשימת חללים</h2>
            <p class="placeholder">עדיין לא הוזן מידע. ניתן להוסיף פרטים על חללים בהמשך.</p>
            <div class="row" id="soldiersList">
                <!-- כאן יופיעו כרטיסי חללים בעתיד -->
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 פרויקט ז' באדר</p>
    </footer>
</body>

</html>
