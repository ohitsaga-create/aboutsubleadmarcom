# aboutsubleadmarcom
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kết Quả Tuyển Dụng | LEAD(A)GAIN</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #f8fafc; }
        .card-reveal { opacity: 0; transform: translateY(20px); transition: all 0.6s ease-out; }
        .card-reveal.active { opacity: 1; transform: translateY(0); }
    </style>
</head>
<body class="text-slate-900">

    <header class="py-16 px-4 text-center">
        <h1 class="text-4xl md:text-5xl font-bold tracking-tight text-slate-900 mb-4">
            TO LIVE A LIFE WELL-LIVED
        </h1>
        <p class="text-lg text-slate-600 max-w-2xl mx-auto">
            Chúc mừng những cá nhân xuất sắc đã chính thức gia nhập đội ngũ. 
            Cùng nhau, chúng ta sẽ viết nên những câu chuyện truyền cảm hứng.
        </p>
    </header>

    <main class="max-w-6xl mx-auto px-4 pb-20">
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            
            <div class="card-reveal bg-white p-8 rounded-2xl shadow-sm border border-slate-100 flex flex-col items-center text-center">
                <div class="w-16 h-16 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mb-6 font-bold text-xl">01</div>
                <h3 class="text-sm uppercase tracking-widest text-slate-400 font-semibold mb-2">Content Creator</h3>
                <p class="text-xl font-bold text-slate-800 italic">Nguyễn Hoàng Nam</p>
            </div>

            <div class="card-reveal bg-white p-8 rounded-2xl shadow-sm border border-slate-100 flex flex-col items-center text-center">
                <div class="w-16 h-16 bg-purple-100 text-purple-600 rounded-full flex items-center justify-center mb-6 font-bold text-xl">02</div>
                <h3 class="text-sm uppercase tracking-widest text-slate-400 font-semibold mb-2">Graphic Designer</h3>
                <p class="text-xl font-bold text-slate-800 italic">Lê Phan Anh Thư</p>
            </div>

            <div class="card-reveal bg-white p-8 rounded-2xl shadow-sm border border-slate-100 flex flex-col items-center text-center">
                <div class="w-16 h-16 bg-emerald-100 text-emerald-600 rounded-full flex items-center justify-center mb-6 font-bold text-xl">03</div>
                <h3 class="text-sm uppercase tracking-widest text-slate-400 font-semibold mb-2">Project Manager</h3>
                <p class="text-xl font-bold text-slate-800 italic">Trần Minh Quang</p>
            </div>

            <div class="card-reveal bg-white p-8 rounded-2xl shadow-sm border border-slate-100 flex flex-col items-center text-center">
                <div class="w-16 h-16 bg-amber-100 text-amber-600 rounded-full flex items-center justify-center mb-6 font-bold text-xl">04</div>
                <h3 class="text-sm uppercase tracking-widest text-slate-400 font-semibold mb-2">Communication Lead</h3>
                <p class="text-xl font-bold text-slate-800 italic">Phạm Hoàng Yến</p>
            </div>

        </div>

        <div class="mt-16 text-center">
            <button class="bg-slate-900 text-white px-8 py-3 rounded-full font-medium hover:bg-slate-800 transition-colors">
                Xem chi tiết nhiệm vụ
            </button>
        </div>
    </main>

    <footer class="border-t border-slate-200 py-8 text-center text-sm text-slate-500">
        © 2026 LEAD(A)GAIN Campaign. All rights reserved.
    </footer>

    <script>
        // Hiệu ứng xuất hiện lần lượt
        document.addEventListener('DOMContentLoaded', () => {
            const cards = document.querySelectorAll('.card-reveal');
            cards.forEach((card, index) => {
                setTimeout(() => {
                    card.classList.add('active');
                }, index * 200);
            });
        });
    </script>
</body>
</html>
