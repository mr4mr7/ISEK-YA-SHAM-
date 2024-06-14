# ISEK-YA-SHAM-
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مطعمي الاحترافي</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">مطعمي</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#home">الرئيسية</a></li>
                <li class="nav-item"><a class="nav-link" href="#menu">القائمة</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">الاتصال</a></li>
                <li class="nav-item"><a class="nav-link" href="#reservation">الحجوزات</a></li>
            </ul>
        </div>
    </nav>

    <header id="home" class="jumbotron jumbotron-fluid text-center">
        <div class="container">
            <h1 class="display-4">مرحبا بكم في مطعمنا</h1>
            <p class="lead">استمتعوا بأشهى الأطباق وأفضل الخدمات.</p>
        </div>
    </header>

    <section id="menu" class="py-5">
        <div class="container">
            <h2 class="text-center">القائمة</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="dish1.jpg" class="card-img-top" alt="الطبق الأول">
                        <div class="card-body">
                            <h5 class="card-title">الطبق الأول</h5>
                            <p class="card-text">وصف للطبق الأول.</p>
                            <p class="card-text"><strong>$10</strong></p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="dish2.jpg" class="card-img-top" alt="الطبق الثاني">
                        <div class="card-body">
                            <h5 class="card-title">الطبق الثاني</h5>
                            <p class="card-text">وصف للطبق الثاني.</p>
                            <p class="card-text"><strong>$12</strong></p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card mb-4">
                        <img src="dish3.jpg" class="card-img-top" alt="الطبق الثالث">
                        <div class="card-body">
                            <h5 class="card-title">الطبق الثالث</h5>
                            <p class="card-text">وصف للطبق الثالث.</p>
                            <p class="card-text"><strong>$15</strong></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center">الاتصال</h2>
            <div class="row">
                <div class="col-md-6">
                    <h5>العنوان:</h5>
                    <p>شارع المطاعم، المدينة</p>
                    <h5>الهاتف:</h5>
                    <p>123456789</p>
                    <h5>البريد الإلكتروني:</h5>
                    <p>info@myrestaurant.com</p>
                </div>
                <div class="col-md-6">
                    <h5>خريطة الموقع:</h5>
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.8354345093776!2d-122.4194160846817!3d37.77492927975813!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085809c5b59c7f3%3A0xdda4c58a5f9d093!2sCity%20Hall%2C%20San%20Francisco%2C%20CA%2094102%2C%20USA!5e0!3m2!1sen!2sin!4v1605455189543!5m2!1sen!2sin" width="100%" height="300" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
                </div>
            </div>
        </div>
    </section>

    <section id="reservation" class="py-5">
        <div class="container">
            <h2 class="text-center">الحجوزات</h2>
            <form id="reservation-form" class="needs-validation" novalidate>
                <div class="form-row">
                    <div class="col-md-6 mb-3">
                        <label for="name">الاسم:</label>
                        <input type="text" class="form-control" id="name" name="name" required>
                        <div class="invalid-feedback">يرجى إدخال الاسم.</div>
                    </div>
                    <div class="col-md-6 mb-3">
                        <label for="email">البريد الإلكتروني:</label>
                        <input type="email" class="form-control" id="email" name="email" required>
                        <div class="invalid-feedback">يرجى إدخال بريد إلكتروني صحيح.</div>
                    </div>
                </div>
                <div class="form-row">
                    <div class="col-md-6 mb-3">
                        <label for="date">التاريخ:</label>
                        <input type="date" class="form-control" id="date" name="date" required>
                        <div class="invalid-feedback">يرجى إدخال التاريخ.</div>
                    </div>
                    <div class="col-md-6 mb-3">
                        <label for="time">الوقت:</label>
                        <input type="time" class="form-control" id="time" name="time" required>
                        <div class="invalid-feedback">يرجى إدخال الوقت.</div>
                    </div>
                </div>
                <div class="form-row">
                    <div class="col-md-6 mb-3">
                        <label for="guests">عدد الضيوف:</label>
                        <input type="number" class="form-control" id="guests" name="guests" required>
                        <div class="invalid-feedback">يرجى إدخال عدد الضيوف.</div>
                    </div>
                </div>
                <button class="btn btn-primary" type="submit">حجز</button>
            </form>
        </div>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p>&copy; 2024 مطعمي. جميع الحقوق محفوظة.</p>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
