<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>タイピング★ラッシュ100</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=M+PLUS+Rounded+1c:wght@400;700;900&family=JetBrains+Mono:wght@500;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'M PLUS Rounded 1c', sans-serif;
            background-color: #e0f2fe;
            color: #0f172a;
            user-select: none;
            touch-action: manipulation;
        }
        .font-mono-custom {
            font-family: 'JetBrains Mono', monospace;
        }
        ruby {
            ruby-position: over;
        }
        rt {
            font-size: 0.55em;
            color: #0284c7;
            font-weight: 700;
            letter-spacing: 0.05em;
            user-select: none;
            transition: opacity 0.2s ease, visibility 0.2s ease;
        }
        .ruby-hidden rt {
            opacity: 0;
            visibility: hidden;
        }
        .key-active {
            transform: translateY(2px);
            box-shadow: 0 0 12px rgba(14, 165, 233, 0.6) !important;
            background-color: #0284c7 !important;
            color: #ffffff !important;
        }
        .key-next {
            border-color: #d97706 !important;
            box-shadow: 0 0 10px rgba(217, 119, 6, 0.4);
            animation: pulse-border 1.2s infinite alternate;
        }
        @keyframes pulse-border {
            0% { border-color: rgba(217, 119, 6, 0.4); }
            100% { border-color: rgba(217, 119, 6, 1); }
        }
        .glass-panel {
            background: rgba(255, 255, 255, 0.88);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(226, 232, 240, 0.9);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.05);
        }
        .shake {
            animation: shake 0.25s cubic-bezier(.36,.07,.19,.97) both;
        }
        @keyframes shake {
            10%, 90% { transform: translate3d(-1px, 0, 0); }
            20%, 80% { transform: translate3d(2px, 0, 0); }
            30%, 50%, 70% { transform: translate3d(-4px, 0, 0); }
            40%, 60% { transform: translate3d(4px, 0, 0); }
        }

        .kusudama-container {
            position: relative;
            width: 160px;
            height: 160px;
            margin: 0 auto;
        }
        .kusudama-glow {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 220px;
            height: 220px;
            margin-top: -110px;
            margin-left: -110px;
            background: radial-gradient(circle, rgba(251, 191, 36, 0.6) 0%, rgba(245, 158, 11, 0.2) 50%, rgba(255, 255, 255, 0) 70%);
            border-radius: 50%;
            opacity: 0;
            transform: scale(0.2) rotate(0deg);
            transition: opacity 0.5s ease, transform 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.27);
            pointer-events: none;
            z-index: 1;
        }
        .kusudama-open .kusudama-glow {
            opacity: 1;
            transform: scale(1.2) rotate(180deg);
            animation: rotate-glow 12s linear infinite;
        }
        @keyframes rotate-glow {
            0% { transform: scale(1.2) rotate(0deg); }
            100% { transform: scale(1.2) rotate(360deg); }
        }
        .kusudama-string {
            position: absolute;
            top: -25px;
            left: 50%;
            transform: translateX(-50%);
            width: 4px;
            height: 35px;
            background: linear-gradient(180deg, #ca8a04, #eab308);
            border-radius: 2px;
            z-index: 2;
        }
        .kusudama-anim-drop {
            animation: kusudama-drop-shake 0.7s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
        }
        @keyframes kusudama-drop-shake {
            0% { transform: translateY(-60px) scale(0.3); opacity: 0; }
            50% { transform: translateY(10px) scale(1.1); opacity: 1; }
            70% { transform: translateY(-5px) rotate(-8deg); }
            85% { transform: translateY(2px) rotate(8deg); }
            100% { transform: translateY(0) rotate(0deg); }
        }
        .kusudama-anim-shake {
            animation: kusudama-pre-shake 0.4s ease-in-out infinite alternate;
        }
        @keyframes kusudama-pre-shake {
            0% { transform: rotate(-10deg) scale(1.05); }
            100% { transform: rotate(10deg) scale(1.05); }
        }
        .kusudama-left, .kusudama-right {
            position: absolute;
            top: 10px;
            width: 70px;
            height: 140px;
            background: linear-gradient(135deg, #f59e0b, #ef4444);
            border-radius: 70px 0 0 70px;
            border: 4px solid #fef08a;
            box-shadow: 0 6px 15px rgba(0,0,0,0.2);
            transition: transform 0.7s cubic-bezier(0.175, 0.885, 0.32, 1.27);
            transform-origin: top center;
            z-index: 10;
        }
        .kusudama-left {
            left: 10px;
        }
        .kusudama-right {
            right: 10px;
            border-radius: 0 70px 70px 0;
            background: linear-gradient(225deg, #f59e0b, #ef4444);
        }
        .kusudama-open .kusudama-left {
            transform: rotate(-48deg) translate(-20px, -8px);
        }
        .kusudama-open .kusudama-right {
            transform: rotate(48deg) translate(20px, -8px);
        }
        .kusudama-banner {
            position: absolute;
            top: 55px;
            left: 50%;
            transform: translateX(-50%) scaleY(0);
            transform-origin: top center;
            width: 140px;
            background: linear-gradient(180deg, #ffffff, #fff5f5);
            border: 3.5px solid #ef4444;
            border-radius: 14px;
            padding: 10px 6px;
            box-shadow: 0 12px 25px rgba(239, 68, 68, 0.3);
            transition: transform 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.35) 0.15s;
            z-index: 20;
        }
        .kusudama-open .kusudama-banner {
            transform: translateX(-50%) scaleY(1);
            animation: banner-sway 3s ease-in-out infinite alternate 0.8s;
        }
        @keyframes banner-sway {
            0% { transform: translateX(-50%) scaleY(1) rotate(-3deg); }
            100% { transform: translateX(-50%) scaleY(1) rotate(3deg); }
        }
        .kbd-key {
            width: 8.5%;
            height: 36px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: #ffffff;
            border: 1px solid #cbd5e1;
            border-bottom-width: 3px;
            border-radius: 8px;
            color: #334155;
            font-weight: 700;
            font-size: 0.85rem;
            transition: all 0.1s ease;
        }
        @media (max-height: 720px) {
            .kbd-key {
                height: 30px;
                font-size: 0.75rem;
                border-radius: 6px;
            }
        }

        @keyframes countdown-pop {
            0% { transform: scale(0.2); opacity: 0; }
            40% { transform: scale(1.15); opacity: 1; }
            75% { transform: scale(1.0); opacity: 1; }
            100% { transform: scale(0.85); opacity: 0; }
        }
        .animate-countdown {
            animation: countdown-pop 0.85s cubic-bezier(0.175, 0.885, 0.32, 1.27) forwards;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between overflow-x-hidden relative">

    <canvas id="bg-canvas" class="fixed top-0 left-0 w-full h-full -z-10 pointer-events-none"></canvas>

    <header class="w-full p-4 flex justify-between items-center glass-panel z-20">
        <div class="flex items-center space-x-3">
            <i class="fa-solid fa-keyboard text-3xl text-sky-600"></i>
            <h1 class="text-xl md:text-2xl font-black tracking-wider text-transparent bg-clip-text bg-gradient-to-r from-sky-600 to-indigo-600">
                タイピング★ラッシュ100
            </h1>
            <span id="course-count-badge" class="bg-indigo-100 text-indigo-700 text-xs px-2.5 py-1 rounded-full font-extrabold border border-indigo-200 flex items-center gap-1 shadow-sm">
                <i class="fa-solid fa-layer-group text-indigo-500"></i>全 <span id="total-course-count">100</span> コース
            </span>
        </div>
        
        <div class="flex items-center space-x-3">
            <button id="header-ruby-toggle" class="px-3 py-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 border border-slate-300 text-xs md:text-sm text-slate-700 flex items-center space-x-2 transition-all">
                <i class="fa-solid fa-language text-sky-600"></i>
                <span id="header-ruby-text">ふりがな: ON</span>
            </button>
            <button id="sound-toggle-btn" class="p-2 rounded-lg bg-slate-100 hover:bg-slate-200 border border-slate-300 text-sky-600 transition-all">
                <i id="sound-icon" class="fa-solid fa-volume-high"></i>
            </button>
        </div>
    </header>

    <main class="flex-grow flex items-center justify-center p-4 relative z-10">
        
        <div id="countdown-overlay" class="hidden fixed inset-0 bg-slate-900/60 backdrop-blur-md z-50 flex flex-col items-center justify-center pointer-events-auto">
            <div id="countdown-text" class="text-6xl sm:text-7xl md:text-9xl font-black text-amber-400 drop-shadow-[0_10px_20px_rgba(0,0,0,0.5)]">
                3
            </div>
        </div>

        <div id="start-screen" class="w-full max-w-4xl glass-panel rounded-3xl p-6 md:p-8 shadow-xl text-center space-y-6 my-4">
            <div>
                <h2 class="text-3xl md:text-4xl font-extrabold text-slate-800">タイピング★ラッシュ100</h2>
                <div id="daily-message-box" class="mt-3 inline-flex items-center justify-center gap-2 px-4 py-2 bg-gradient-to-r from-amber-50 to-orange-50 border border-amber-200 text-amber-900 rounded-full text-xs md:text-sm font-bold shadow-sm transition-all duration-300">
                    <i class="fa-solid fa-comment-dots text-amber-500 text-base"></i>
                    <span id="daily-message-text">今日も楽しくタイピングしよう！</span>
                </div>
            </div>

            <div class="bg-slate-50 border border-slate-200 p-4 rounded-2xl space-y-2 text-xs md:text-sm font-bold text-slate-600">
                <div class="text-center pb-2.5 border-b border-slate-200">
                    <i class="fa-solid fa-coins text-amber-500 mr-1.5 text-base"></i> 累計スコア: <span id="start-totalscore" class="text-emerald-600 font-mono-custom text-xl font-black">0</span>
                </div>
                <div class="flex justify-around pt-1">
                    <div><i class="fa-solid fa-trophy text-amber-500 mr-1"></i> 最高スコア: <span id="start-highscore" class="text-sky-600 font-mono-custom text-base">0</span></div>
                    <div><i class="fa-solid fa-bolt text-indigo-500 mr-1"></i> 最高速度: <span id="start-highwpm" class="text-indigo-600 font-mono-custom text-base">0</span><span class="text-[10px] text-slate-500 font-normal"> 文字/分</span></div>
                </div>
            </div>

            <div class="space-y-5 text-left max-h-[60vh] overflow-y-auto pr-2">
                <div>
                    <!-- Practice Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-seedling text-emerald-600 mr-1"></i> れんしゅう</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2 mb-4">
                        <button data-course="aiueo" class="course-btn p-2.5 rounded-xl border border-sky-500 bg-sky-50 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-hand-peace mr-1"></i>あいうえお</div></button>
                        <button data-course="kakikukeko" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-hand-peace mr-1"></i>かきくけこ</div></button>
                        <button data-course="a_to_so" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-sky-600"><i class="fa-solid fa-hand-peace mr-1"></i>あ～そ</div></button>
                        <button data-course="a_to_n" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-hand-peace mr-1"></i>あ～ん</div></button>
                        <button data-course="dakuon_handakuon" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600"><i class="fa-solid fa-hand-peace mr-1"></i>がざだばぱ</div></button>
                        <button data-course="sokuon_youon" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-600"><i class="fa-solid fa-hand-peace mr-1"></i>っゃゅょ</div></button>
                    </div>

                    <!-- Food Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-utensils text-rose-500 mr-1"></i> たべもの・お<ruby>茶<rt>ちゃ</rt></ruby>・スイーツ</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="sushi" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-500"><i class="fa-solid fa-fish mr-1"></i>おすしのメニュー</div></button>
                        <button data-course="japanese_food" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-bowl-rice mr-1"></i><ruby>日本<rt>にほん</rt>料理<rt>りょうり</rt></ruby></div></button>
                        <button data-course="chinese_food" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-bowl-food mr-1"></i><ruby>中華<rt>ちゅうか</rt>料理<rt>りょうり</rt></ruby></div></button>
                        <button data-course="world_food" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-earth-americas mr-1"></i><ruby>世界<rt>せかい</rt></ruby>の<ruby>料理<rt>りょうり</rt></ruby></div></button>
                        <button data-course="ramen_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-bowl-rice mr-1"></i>ラーメン</div></button>
                        <button data-course="sweets" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-500"><i class="fa-solid fa-ice-cream mr-1"></i>スイーツ</div></button>
                        <button data-course="vegetables" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-carrot mr-1"></i>やさい</div></button>
                        <button data-course="fruits" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-500"><i class="fa-solid fa-apple-whole mr-1"></i>くだもの</div></button>
                        <button data-course="tea_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-mug-hot mr-1"></i><ruby>世界<rt>せかい</rt></ruby>のお<ruby>茶<rt>ちゃ</rt></ruby></div></button>
                        <button data-course="cheese_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-yellow-600"><i class="fa-solid fa-cheese mr-1"></i>チーズ</div></button>
                    </div>

                    <!-- School Subjects Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-graduation-cap text-indigo-600 mr-1"></i> <ruby>小学校<rt>しょうがっこう</rt></ruby>のきょうか・<ruby>学校<rt>がっこう</rt></ruby></label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="japanese" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-book mr-1"></i><ruby>国語<rt>こくご</rt></ruby></div></button>
                        <button data-course="math" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-calculator mr-1"></i><ruby>算数<rt>さんすう</rt></ruby></div></button>
                        <button data-course="science" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-flask mr-1"></i><ruby>理科<rt>りか</rt></ruby></div></button>
                        <button data-course="social" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-earth-americas mr-1"></i><ruby>社会<rt>しゃかい</rt></ruby></div></button>
                        <button data-course="history_people" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-user-ninja mr-1"></i><ruby>歴史<rt>れきし</rt></ruby>の<ruby>人物<rt>じんぶつ</rt></ruby></div></button>
                        <button data-course="music" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-600"><i class="fa-solid fa-music mr-1"></i><ruby>音楽<rt>おんがく</rt></ruby></div></button>
                        <button data-course="art" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-500"><i class="fa-solid fa-palette mr-1"></i><ruby>図工<rt>ずこう</rt></ruby></div></button>
                        <button data-course="pe" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-person-running mr-1"></i><ruby>体育<rt>たいいく</rt></ruby></div></button>
                        <button data-course="school_items" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-700"><i class="fa-solid fa-school mr-1"></i><ruby>学校<rt>がっこう</rt></ruby>にある<ruby>物<rt>もの</rt></ruby></div></button>
                        <button data-course="school_lunch" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700"><i class="fa-solid fa-utensils mr-1"></i><ruby>学校<rt>がっこう</rt>給食<rt>きゅうしょく</rt></ruby></div></button>
                    </div>

                    <!-- Geography Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-globe text-sky-600 mr-1"></i> <ruby>地理<rt>ちり</rt></ruby>・<ruby>観光<rt>かんこう</rt></ruby>・<ruby>世界<rt>せかい</rt></ruby></label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2 mb-4">
                        <button data-course="prefectures" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-600"><i class="fa-solid fa-map-pin mr-1"></i><ruby>都道府県<rt>とどうふけん</rt></ruby></div></button>
                        <button data-course="prefectural_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-building-flag mr-1"></i><ruby>県庁<rt>けんちょう</rt>所在地<rt>しょざいち</rt></ruby></div></button>
                        <button data-course="mountains" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-mountain mr-1"></i><ruby>日本<rt>にほん</rt></ruby>の<ruby>山<rt>やま</rt></ruby></div></button>
                        <button data-course="rivers" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-600"><i class="fa-solid fa-water mr-1"></i><ruby>日本<rt>にほん</rt></ruby>の<ruby>川<rt>かわ</rt></ruby></div></button>
                        <!-- 31~36: lakes, hot_springs, japan_sightseeing, world_heritage, world_sightseeing, us_states -->
                        <button data-course="lakes" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-water-ladder mr-1"></i><ruby>日本<rt>にほん</rt></ruby>の<ruby>湖<rt>みずうみ</rt></ruby></div></button>
                        <button data-course="hot_springs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-hot-tub-person mr-1"></i><ruby>日本<rt>にほん</rt></ruby>の<ruby>温泉<rt>おんせん</rt></ruby></div></button>
                        <button data-course="japan_sightseeing" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-600"><i class="fa-solid fa-torii-gate mr-1"></i><ruby>日本<rt>にほん</rt></ruby>の<ruby>観光地<rt>かんこうち</rt></ruby></div></button>
                        <button data-course="world_heritage" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-700"><i class="fa-solid fa-landmark mr-1"></i><ruby>世界<rt>せかい</rt>遺産<rt>いさん</rt></ruby></div></button>
                        <button data-course="world_sightseeing" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-700"><i class="fa-solid fa-monument mr-1"></i><ruby>世界<rt>せかい</rt></ruby>の<ruby>観光地<rt>かんこうち</rt></ruby></div></button>
                        <button data-course="us_states" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-700"><i class="fa-solid fa-flag-usa mr-1"></i>アメリカの<ruby>州<rt>しゅう</rt></ruby></div></button>
                        <button data-course="asia_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-earth-asia mr-1"></i>アジアの<ruby>国<rt>くに</rt></ruby></div></button>
                        <button data-course="europe_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-earth-europe mr-1"></i>ヨーロッパの<ruby>国<rt>くに</rt></ruby></div></button>
                        <button data-course="americas_oceania_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-earth-americas mr-1"></i><ruby>北米<rt>ほくべい</rt></ruby>・<ruby>南米<rt>なんべい</rt></ruby>・オセアニア</div></button>
                        <button data-course="africa_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-600"><i class="fa-solid fa-earth-africa mr-1"></i>アフリカの<ruby>国<rt>くに</rt></ruby></div></button>
                        <button data-course="asia_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-building-columns mr-1"></i>アジアの<ruby>首都<rt>しゅと</rt></ruby></div></button>
                        <button data-course="europe_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-landmark mr-1"></i>ヨーロッパの<ruby>首都<rt>しゅと</rt></ruby></div></button>
                        <button data-course="americas_oceania_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-monument mr-1"></i><ruby>米州<rt>べいしゅう</rt></ruby>・オセアニア<ruby>首都<rt>しゅと</rt></ruby></div></button>
                        <button data-course="africa_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-600"><i class="fa-solid fa-archway mr-1"></i>アフリカの<ruby>首都<rt>しゅと</rt></ruby></div></button>
                    </div>

                    <!-- History & Culture Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-scroll text-amber-800 mr-1"></i> <ruby>歴史<rt>れきし</rt></ruby>・<ruby>人物<rt>じんぶつ</rt></ruby>・<ruby>伝統<rt>でんとう</rt></ruby></label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="sengoku" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-700"><i class="fa-solid fa-user-ninja mr-1"></i><ruby>戦国<rt>せんごく</rt>武将<rt>ぶしょう</rt></ruby></div></button>
                        <button data-course="sangokushi" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-800"><i class="fa-solid fa-dragon mr-1"></i><ruby>三国志<rt>さんごくし</rt></ruby>の<ruby>武将<rt>ぶしょう</rt></ruby></div></button>
                        <button data-course="pm_japan" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-800"><i class="fa-solid fa-building-user mr-1"></i><ruby>総理<rt>そうり</rt></ruby><ruby>大臣<rt>だいじん</rt></ruby></div></button>
                        <button data-course="us_presidents" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-flag-usa mr-1"></i>アメリカ<ruby>大統領<rt>だいとうりょう</rt></ruby></div></button>
                        <button data-course="world_history_people" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-globe mr-1"></i><ruby>世界史<rt>せかいし</rt></ruby>の<ruby>有名人<rt>ゆうめいじん</rt></ruby></div></button>
                        <button data-course="famous_battles" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-burst mr-1"></i><ruby>歴史上<rt>れきしじょう</rt></ruby>の<ruby>戦<rt>たたか</rt></ruby>い</div></button>
                        <button data-course="mythology_figures" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-bolt-lightning mr-1"></i><ruby>神話<rt>しんわ</rt></ruby>の<ruby>人物<rt>じんぶつ</rt></ruby></div></button>
                        <button data-course="haiku" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-feather mr-1"></i><ruby>俳句<rt>はいく</rt></ruby></div></button>
                        <button data-course="hyakunin" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-scroll mr-1"></i><ruby>百人一首<rt>ひゃくにんいっしゅ</rt></ruby></div></button>
                        <button data-course="sumo" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-900"><i class="fa-solid fa-hand-rock mr-1"></i><ruby>相撲<rt>すもう</rt></ruby>の<ruby>決<rt>き</rt></ruby>まり<ruby>手<rt>て</rt></ruby></div></button>
                    </div>

                    <!-- Animals & Nature Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-hippo text-emerald-600 mr-1"></i> 生きもの・<ruby>植物<rt>しょくぶつ</rt></ruby>・<ruby>自然<rt>しぜん</rt></ruby></label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2 mb-4">
                        <button data-course="animals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-hippo mr-1"></i><ruby>動物<rt>どうぶつ</rt></ruby></div></button>
                        <button data-course="dog_breeds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700"><i class="fa-solid fa-dog mr-1"></i><ruby>犬<rt>いぬ</rt></ruby></div></button>
                        <button data-course="cat_breeds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-600"><i class="fa-solid fa-cat mr-1"></i>ネコ</div></button>
                        <button data-course="birds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-600"><i class="fa-solid fa-crow mr-1"></i><ruby>鳥<rt>とり</rt></ruby></div></button>
                        <button data-course="insects" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-lime-700"><i class="fa-solid fa-bug mr-1"></i><ruby>昆虫<rt>こんちゅう</rt></ruby></div></button>
                        <button data-course="ocean_fish" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-fish-fins mr-1"></i><ruby>海<rt>うみ</rt></ruby>の<ruby>魚<rt>さかな</rt></ruby></div></button>
                        <button data-course="river_fish" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-water mr-1"></i><ruby>川<rt>かわ</rt></ruby>の<ruby>魚<rt>さかな</rt></ruby></div></button>
                        <button data-course="dinosaurs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-dragon mr-1"></i><ruby>恐竜<rt>きょうりゅう</rt></ruby></div></button>
                        <button data-course="flowers" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-500"><i class="fa-solid fa-seedling mr-1"></i><ruby>花<rt>はな</rt></ruby></div></button>
                        <button data-course="trees" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-tree mr-1"></i><ruby>木<rt>き</rt></ruby></div></button>
                        <button data-course="cloud_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-sky-600"><i class="fa-solid fa-cloud mr-1"></i><ruby>雲<rt>くも</rt></ruby></div></button>
                    </div>

                    <!-- Health & Science Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-heart-pulse text-pink-600 mr-1"></i> <ruby>体<rt>からだ</rt></ruby>・<ruby>健康<rt>けんこう</rt></ruby>・<ruby>科学<rt>かがく</rt></ruby></label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="body_parts" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-700"><i class="fa-solid fa-child mr-1"></i><ruby>体<rt>からだ</rt></ruby>の<ruby>部分<rt>ぶぶん</rt></ruby></div></button>
                        <button data-course="body_organs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-heart mr-1"></i><ruby>体<rt>からだ</rt></ruby>の<ruby>中<rt>なか</rt></ruby>にあるもの</div></button>
                        <button data-course="human_bones" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-slate-700"><i class="fa-solid fa-bone mr-1"></i><ruby>人間<rt>にんげん</rt></ruby>の<ruby>骨<rt>ほね</rt></ruby></div></button>
                        <button data-course="diseases" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-600"><i class="fa-solid fa-notes-medical mr-1"></i><ruby>病気<rt>びょうき</rt></ruby></div></button>
                        <button data-course="elements" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-700"><i class="fa-solid fa-atom mr-1"></i><ruby>元素<rt>げんそ</rt>記号<rt>きごう</rt></ruby></div></button>
                    </div>

                    <!-- Sports & Hobbies Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-car-side text-blue-600 mr-1"></i> <ruby>乗<rt>の</rt></ruby>り<ruby>物<rt>もの</rt></ruby>・スポーツ・<ruby>趣味<rt>しゅみ</rt></ruby></label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2 mb-4">
                        <button data-course="kanto_trains" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-700"><i class="fa-solid fa-train mr-1"></i><ruby>関東<rt>かんとう</rt></ruby>の<ruby>電車<rt>でんしゃ</rt></ruby></div></button>
                        <button data-course="car_models" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-slate-800"><i class="fa-solid fa-car mr-1"></i><ruby>車<rt>くるま</rt></ruby></div></button>
                        <button data-course="sports_names" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-person-running mr-1"></i>スポーツ</div></button>
                        <button data-course="sports_equipment" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-baseball mr-1"></i>スポーツの<ruby>道具<rt>どうぐ</rt></ruby></div></button>
                        <button data-course="musicians" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600"><i class="fa-solid fa-music mr-1"></i><ruby>音楽家<rt>おんがくか</rt></ruby></div></button>
                        <button data-course="shogi_terms" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-chess-board mr-1"></i><ruby>将棋<rt>しょうぎ</rt></ruby></div></button>
                        <button data-course="toys" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-500"><i class="fa-solid fa-gamepad mr-1"></i>おもちゃ</div></button>
                        <button data-course="professions" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-user-tie mr-1"></i><ruby>職業<rt>しょくぎょう</rt></ruby></div></button>
                        <button data-course="pc_terms" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-desktop mr-1"></i>パソコンのことば</div></button>
                        <button data-course="it" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-laptop-code mr-1"></i>IT<ruby>用語<rt>ようご</rt></ruby>・カタカナ</div></button>
                        <button data-course="household_items" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-house mr-1"></i><ruby>家<rt>いえ</rt></ruby>にあるもの</div></button>
                    </div>

                    <!-- Language & Seasonal Courses -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-book-open text-purple-600 mr-1"></i> ことば・テーマ・<ruby>季節<rt>きせつ</rt></ruby></label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2" id="course-selector">
                        <button data-course="idioms" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><ruby>慣用句<rt>かんようく</rt></ruby></div></button>
                        <button data-course="greetings" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600">あいさつ</div></button>
                        <button data-course="medium" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-sky-600"><ruby>日常<rt>にちじょう</rt></ruby><ruby>会話<rt>かいわ</rt></ruby></div></button>
                        <button data-course="proverbs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600">ことわざ</div></button>
                        <button data-course="yojijukugo" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><ruby>四字熟語<rt>よじじゅくご</rt></ruby></div></button>
                        <button data-course="praise" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-yellow-600"><i class="fa-solid fa-thumbs-up mr-1"></i>ほめことば</div></button>
                        <button data-course="onomatopoeia" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600"><i class="fa-solid fa-wand-magic-sparkles mr-1"></i>オノマトペ</div></button>
                        <button data-course="animal_sounds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-paw mr-1"></i><ruby>動物<rt>どうぶつ</rt></ruby>のなきごえ</div></button>
                        <button data-course="radicals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-font mr-1"></i><ruby>部首<rt>ぶしゅ</rt></ruby></div></button>
                        <button data-course="nandoku_kanji" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-font mr-1"></i><ruby>難読<rt>なんどく</rt>漢字<rt>かんじ</rt></ruby></div></button>
                        <button data-course="keigo" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700"><i class="fa-solid fa-comments mr-1"></i><ruby>敬語<rt>けいご</rt></ruby></div></button>
                        <button data-course="traditional_colors" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600"><i class="fa-solid fa-paint-brush mr-1"></i><ruby>色<rt>いろ</rt></ruby></div></button>
                        <button data-course="japanese_holidays" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-600"><i class="fa-solid fa-calendar-day mr-1"></i><ruby>日本<rt>にほん</rt></ruby>の<ruby>祝日<rt>しゅくじつ</rt></ruby></div></button>
                        <button data-course="constellations" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-star mr-1"></i><ruby>星座<rt>せいざ</rt></ruby></div></button>
                        <button data-course="world_currencies" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-money-bill-wave mr-1"></i><ruby>世界<rt>せかい</rt></ruby>のお<ruby>金<rt>かね</rt></ruby></div></button>
                        <button data-course="spring" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-600"><ruby>春<rt>はる</rt></ruby>のもの</div></button>
                        <button data-course="summer" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><ruby>夏<rt>なつ</rt></ruby>のもの</div></button>
                        <button data-course="autumn" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700"><ruby>秋<rt>あき</rt></ruby>のもの</div></button>
                        <button data-course="winter" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-600"><ruby>冬<rt>ふゆ</rt></ruby>のもの</div></button>
                    </div>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 pt-2">
                    <div>
                        <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-clock mr-1"></i> 制限時間</label>
                        <div class="flex space-x-2" id="time-selector">
                            <button data-time="30" class="time-btn flex-1 py-2 rounded-xl border border-slate-300 bg-white text-sm font-bold hover:border-sky-500 text-slate-700 shadow-sm">30秒</button>
                            <button data-time="60" class="time-btn flex-1 py-2 rounded-xl border border-sky-500 bg-sky-50 text-sm font-bold text-sky-600 shadow-sm">60秒</button>
                            <button data-time="90" class="time-btn flex-1 py-2 rounded-xl border border-slate-300 bg-white text-sm font-bold hover:border-sky-500 text-slate-700 shadow-sm">90秒</button>
                        </div>
                    </div>

                    <div>
                        <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-eye mr-1"></i> ふりがな（ルビ）表示</label>
                        <button id="setting-ruby-btn" class="w-full py-2 px-4 rounded-xl border border-sky-500 bg-sky-50 hover:bg-sky-100 text-sky-700 font-bold text-sm flex items-center justify-between transition-all shadow-sm">
                            <span><i class="fa-solid fa-language mr-2"></i> ふりがなを表示する</span>
                            <span id="setting-ruby-status" class="bg-sky-600 text-white text-xs px-2 py-0.5 rounded font-black">ON</span>
                        </button>
                    </div>
                </div>
            </div>

            <button id="start-game-btn" class="w-full py-4 rounded-2xl bg-gradient-to-r from-sky-500 to-indigo-600 hover:from-sky-400 hover:to-indigo-500 text-white font-black text-xl shadow-lg shadow-sky-500/25 transform active:scale-98 transition-all">
                ゲームスタート (スペースキー)
            </button>
        </div>

        <div id="play-screen" class="hidden w-full max-w-3xl glass-panel rounded-3xl p-3 sm:p-5 shadow-xl space-y-3">
            
            <div class="flex justify-between items-center bg-slate-100/90 px-3 py-1.5 rounded-2xl border border-slate-200">
                <div class="flex space-x-2">
                    <button id="ingame-back-btn" class="px-3 py-1 rounded-xl bg-white hover:bg-slate-200 border border-slate-300 text-xs font-bold text-slate-700 flex items-center space-x-1.5 transition-all shadow-sm">
                        <i class="fa-solid fa-arrow-left text-sky-600"></i>
                        <span>もどる</span>
                    </button>
                    <button id="ingame-retry-btn" class="px-3 py-1 rounded-xl bg-amber-50 hover:bg-amber-100 border border-amber-300 text-xs font-bold text-amber-700 flex items-center space-x-1.5 transition-all shadow-sm">
                        <i class="fa-solid fa-rotate-right text-amber-600"></i>
                        <span>もう１回</span>
                    </button>
                </div>
                
                <button id="ingame-ruby-btn" title="ふりがな切替" class="px-3 py-1 rounded-xl bg-white hover:bg-slate-200 border border-slate-300 text-xs font-bold text-sky-700 flex items-center space-x-1.5 transition-all shadow-sm">
                    <i class="fa-solid fa-eye"></i>
                    <span id="ingame-ruby-text">ルビ: ON</span>
                </button>
            </div>

            <div class="flex justify-around items-center bg-white/80 px-4 py-1.5 rounded-2xl border border-slate-200 shadow-sm">
                <div class="text-center">
                    <span class="text-[11px] text-slate-500 font-bold block leading-none">残り時間</span>
                    <span id="timer-display" class="text-xl md:text-2xl font-black text-amber-600 font-mono-custom">60</span><span class="text-xs text-slate-500">s</span>
                </div>
                <div class="text-center">
                    <span class="text-[11px] text-slate-500 font-bold block leading-none">スコア</span>
                    <span id="score-display" class="text-xl md:text-2xl font-black text-sky-600 font-mono-custom">0</span>
                </div>
                <div class="text-center">
                    <span class="text-[11px] text-slate-500 font-bold block leading-none">正確率</span>
                    <span id="accuracy-display" class="text-xl md:text-2xl font-black text-emerald-600 font-mono-custom">100</span><span class="text-xs text-slate-500">%</span>
                </div>
            </div>

            <div id="word-card" class="bg-white border-2 border-slate-200 rounded-2xl p-4 text-center space-y-2 shadow-sm relative overflow-hidden min-h-[130px] md:min-h-[150px] flex flex-col justify-center">
                <div id="word-display" class="text-2xl md:text-4xl font-black text-slate-800 tracking-wide leading-tight">
                </div>
                <div id="kana-display" class="text-xs md:text-sm font-bold text-slate-500 tracking-wider">
                </div>
                <div id="romaji-container" class="font-mono-custom text-lg md:text-2xl tracking-wider pt-1 border-t border-slate-200">
                    <span id="romaji-typed" class="text-sky-600 font-bold"></span><span id="romaji-current" class="text-amber-600 font-black underline bg-amber-100 px-1 rounded"></span><span id="romaji-untyped" class="text-slate-400"></span>
                </div>
            </div>

            <div class="space-y-1 bg-white/70 p-2 md:p-3 rounded-2xl border border-slate-200 text-xs font-mono-custom shadow-sm">
                <div class="flex justify-center space-x-1" id="kbd-row-1">
                    <div data-key="q" class="kbd-key">Q</div><div data-key="w" class="kbd-key">W</div><div data-key="e" class="kbd-key">E</div><div data-key="r" class="kbd-key">R</div><div data-key="t" class="kbd-key">T</div><div data-key="y" class="kbd-key">Y</div><div data-key="u" class="kbd-key">U</div><div data-key="i" class="kbd-key">I</div><div data-key="o" class="kbd-key">O</div><div data-key="p" class="kbd-key">P</div>
                </div>
                <div class="flex justify-center space-x-1" id="kbd-row-2">
                    <div data-key="a" class="kbd-key">A</div><div data-key="s" class="kbd-key">S</div><div data-key="d" class="kbd-key">D</div><div data-key="f" class="kbd-key">F</div><div data-key="g" class="kbd-key">G</div><div data-key="h" class="kbd-key">H</div><div data-key="j" class="kbd-key">J</div><div data-key="k" class="kbd-key">K</div><div data-key="l" class="kbd-key">L</div><div data-key="-" class="kbd-key">-</div>
                </div>
                <div class="flex justify-center space-x-1" id="kbd-row-3">
                    <div data-key="z" class="kbd-key">Z</div><div data-key="x" class="kbd-key">X</div><div data-key="c" class="kbd-key">C</div><div data-key="v" class="kbd-key">V</div><div data-key="b" class="kbd-key">B</div><div data-key="n" class="kbd-key">N</div><div data-key="m" class="kbd-key">M</div><div data-key="," class="kbd-key">,</div><div data-key="." class="kbd-key">.</div>
                </div>
            </div>
        </div>

        <div id="result-screen" class="hidden w-full max-w-xl glass-panel rounded-3xl p-6 md:p-8 shadow-xl text-center space-y-6">

            <div id="kusudama-wrapper" class="hidden relative py-2">
                <div id="kusudama-element" class="kusudama-container">
                    <div class="kusudama-glow"></div>
                    <div class="kusudama-string"></div>
                    <div class="kusudama-left"></div>
                    <div class="kusudama-right"></div>
                    <div class="kusudama-banner">
                        <div class="text-red-600 font-black text-xl leading-tight tracking-wider">祝！新記録</div>
                        <div class="text-amber-600 font-bold text-xs mt-1">ボーナス +500pt</div>
                    </div>
                </div>
                <div id="kusudama-msg" class="text-emerald-600 font-black text-xl mt-3 opacity-0 transition-opacity duration-500">
                    🎉🎉🎉 新記録達成！ボーナス500pt獲得！ 🎉🎉🎉
                </div>
            </div>

            <div class="grid grid-cols-2 gap-4">
                <div class="bg-white/80 p-4 rounded-2xl border border-slate-200 shadow-sm">
                    <span class="text-xs text-slate-500 font-bold block">獲得ポイント</span>
                    <span id="final-score" class="text-3xl md:text-4xl font-black text-sky-600 font-mono-custom">0</span>
                </div>
                <div class="bg-white/80 p-4 rounded-2xl border border-slate-200 shadow-sm flex flex-col justify-center items-center">
                    <span class="text-xs text-slate-500 font-bold block">タイピング速度 (文字/分)</span>
                    <span id="final-wpm" class="text-3xl md:text-4xl font-black text-indigo-600 font-mono-custom">0</span>
                    <span id="wpm-comment" class="text-[11px] font-bold text-sky-700 bg-sky-50 px-2 py-0.5 rounded-full mt-1 border border-sky-200"></span>
                </div>
                <div class="bg-white/80 p-4 rounded-2xl border border-slate-200 shadow-sm">
                    <span class="text-xs text-slate-500 font-bold block">入力キー数</span>
                    <span id="final-keys" class="text-2xl font-bold text-slate-800 font-mono-custom">0</span>
                </div>
                <div class="bg-white/80 p-4 rounded-2xl border border-slate-200 shadow-sm">
                    <span class="text-xs text-slate-500 font-bold block">正確率</span>
                    <span id="final-accuracy" class="text-2xl font-bold text-emerald-600 font-mono-custom">100%</span>
                </div>
            </div>

            <div class="bg-sky-50/80 border border-sky-200 p-3.5 rounded-2xl text-xs space-y-2 text-left text-slate-700">
                <div class="font-bold text-sky-700 text-center text-xs">
                    <i class="fa-solid fa-gauge-high mr-1 text-sky-600"></i> タイピング速度のめやす（1分あたりのひらがな文字数）
                </div>
                <div class="grid grid-cols-2 gap-2 text-center">
                    <div class="bg-white p-2.5 rounded-xl border border-sky-100 shadow-sm flex flex-col justify-between">
                        <span class="font-black text-amber-600 block text-xs md:text-sm">50〜80 文字/分</span>
                        <span class="text-slate-600 font-bold text-[11px] mt-1">はじめてレベル 🌱<br><span class="text-[10px] text-slate-400 font-normal">ゆっくりでOK！</span></span>
                    </div>
                    <div class="bg-white p-2.5 rounded-xl border border-sky-100 shadow-sm flex flex-col justify-between">
                        <span class="font-black text-emerald-600 block text-xs md:text-sm">120 文字/分</span>
                        <span class="text-slate-600 font-bold text-[11px] mt-1">大人の仕事レベル 💼<br><span class="text-[10px] text-slate-400 font-normal">パソコンのお仕事ができる</span></span>
                    </div>
                </div>
            </div>

            <div id="rank-badge" class="py-3 px-6 rounded-2xl bg-gradient-to-r from-amber-100 to-yellow-100 border border-amber-300 text-amber-800 font-black text-lg shadow-sm">
                評価: B 級 (グッドタイパー)
            </div>

            <div class="flex space-x-3">
                <button id="restart-btn" class="flex-1 py-3.5 rounded-xl bg-sky-500 hover:bg-sky-400 text-white font-black text-lg transition-all shadow-lg shadow-sky-500/20">
                    もう一度挑戦
                </button>
                <button id="back-home-btn" class="px-5 py-3.5 rounded-xl bg-white hover:bg-slate-100 border border-slate-300 text-slate-700 font-bold transition-all shadow-sm">
                    設定へ戻る
                </button>
            </div>
        </div>

    </main>

    <footer class="w-full p-3 text-center text-xs text-slate-400 relative z-10">
        HTML5 / JavaScript Web Typing Game &copy; 2026
    </footer>

    <script>
        let confettiParticles = [];

        function shuffleArray(array) {
            const arr = [...array];
            for (let i = arr.length - 1; i > 0; i--) {
                const j = Math.floor(Math.random() * (i + 1));
                [arr[i], arr[j]] = [arr[j], arr[i]];
            }
            return arr;
        }

        class SoundEngine {
            constructor() {
                this.ctx = null;
            }
            init() {
                if (!this.ctx) {
                    this.ctx = new (window.AudioContext || window.webkitAudioContext)();
                }
            }
            playType() {
                if (!gameState.soundEnabled) return;
                this.init();
                const now = this.ctx.currentTime;
                
                const masterGain = this.ctx.createGain();
                masterGain.gain.setValueAtTime(1.0, now);
                masterGain.connect(this.ctx.destination);

                const bassOsc = this.ctx.createOscillator();
                const bassGain = this.ctx.createGain();
                bassOsc.type = 'sine';
                bassOsc.frequency.setValueAtTime(260, now);
                bassOsc.frequency.exponentialRampToValueAtTime(35, now + 0.12);
                bassGain.gain.setValueAtTime(0.85, now);
                bassGain.gain.exponentialRampToValueAtTime(0.001, now + 0.12);
                bassOsc.connect(bassGain);
                bassGain.connect(masterGain);
                bassOsc.start(now);
                bassOsc.stop(now + 0.12);

                const popOsc = this.ctx.createOscillator();
                const popGain = this.ctx.createGain();
                popOsc.type = 'triangle';
                popOsc.frequency.setValueAtTime(900, now);
                popOsc.frequency.exponentialRampToValueAtTime(1800, now + 0.08);
                popGain.gain.setValueAtTime(0.75, now);
                popGain.gain.exponentialRampToValueAtTime(0.001, now + 0.08);
                popOsc.connect(popGain);
                popGain.connect(masterGain);
                popOsc.start(now);
                popOsc.stop(now + 0.08);

                const bufferSize = Math.floor(this.ctx.sampleRate * 0.06);
                const buffer = this.ctx.createBuffer(1, bufferSize, this.ctx.sampleRate);
                const data = buffer.getChannelData(0);
                for (let i = 0; i < bufferSize; i++) {
                    data[i] = Math.random() * 2 - 1;
                }
                const noise = this.ctx.createBufferSource();
                noise.buffer = buffer;

                const filter = this.ctx.createBiquadFilter();
                filter.type = 'bandpass';
                filter.frequency.setValueAtTime(4500, now);
                filter.Q.setValueAtTime(1.2, now);

                const noiseGain = this.ctx.createGain();
                noiseGain.gain.setValueAtTime(0.8, now);
                noiseGain.gain.exponentialRampToValueAtTime(0.001, now + 0.06);

                noise.connect(filter);
                filter.connect(noiseGain);
                noiseGain.connect(masterGain);
                noise.start(now);
            }
            playMiss() {
                if (!gameState.soundEnabled) return;
                this.init();
                const osc = this.ctx.createOscillator();
                const gain = this.ctx.createGain();
                osc.type = 'sawtooth';
                osc.frequency.setValueAtTime(140, this.ctx.currentTime);
                osc.frequency.linearRampToValueAtTime(90, this.ctx.currentTime + 0.1);
                gain.gain.setValueAtTime(0.2, this.ctx.currentTime);
                gain.gain.exponentialRampToValueAtTime(0.01, this.ctx.currentTime + 0.1);
                osc.connect(gain);
                gain.connect(this.ctx.destination);
                osc.start();
                osc.stop(this.ctx.currentTime + 0.1);
            }
            playSuccess() {
                if (!gameState.soundEnabled) return;
                this.init();
                const now = this.ctx.currentTime;
                const notes = [523.25, 659.25, 783.99, 1046.50];
                notes.forEach((freq, index) => {
                    const osc = this.ctx.createOscillator();
                    const gain = this.ctx.createGain();
                    osc.type = 'triangle';
                    osc.frequency.setValueAtTime(freq, now + index * 0.04);
                    gain.gain.setValueAtTime(0.4, now + index * 0.04);
                    gain.gain.exponentialRampToValueAtTime(0.001, now + index * 0.04 + 0.25);
                    osc.connect(gain);
                    gain.connect(this.ctx.destination);
                    osc.start(now + index * 0.04);
                    osc.stop(now + index * 0.04 + 0.25);
                });
            }
            playFanfare() {
                if (!gameState.soundEnabled) return;
                this.init();
                const notes = [523.25, 659.25, 783.99, 1046.50];
                notes.forEach((freq, i) => {
                    const osc = this.ctx.createOscillator();
                    const gain = this.ctx.createGain();
                    osc.type = 'triangle';
                    osc.frequency.setValueAtTime(freq, this.ctx.currentTime + i * 0.1);
                    gain.gain.setValueAtTime(0.25, this.ctx.currentTime + i * 0.1);
                    gain.gain.exponentialRampToValueAtTime(0.01, this.ctx.currentTime + i * 0.1 + 0.3);
                    osc.connect(gain);
                    gain.connect(this.ctx.destination);
                    osc.start(this.ctx.currentTime + i * 0.1);
                    osc.stop(this.ctx.currentTime + i * 0.1 + 0.3);
                });
            }
            playCountdown(isStart = false) {
                if (!gameState.soundEnabled) return;
                this.init();
                const now = this.ctx.currentTime;
                const osc = this.ctx.createOscillator();
                const gain = this.ctx.createGain();
                osc.type = 'sine';
                if (isStart) {
                    osc.frequency.setValueAtTime(880, now);
                    osc.frequency.exponentialRampToValueAtTime(1760, now + 0.15);
                    gain.gain.setValueAtTime(0.3, now);
                    gain.gain.exponentialRampToValueAtTime(0.001, now + 0.35);
                    osc.connect(gain);
                    gain.connect(this.ctx.destination);
                    osc.start(now);
                    osc.stop(now + 0.35);
                } else {
                    osc.frequency.setValueAtTime(440, now);
                    gain.gain.setValueAtTime(0.25, now);
                    gain.gain.exponentialRampToValueAtTime(0.001, now + 0.2);
                    osc.connect(gain);
                    gain.connect(this.ctx.destination);
                    osc.start(now);
                    osc.stop(now + 0.2);
                }
            }
        }
        const sound = new SoundEngine();

        const RAW_WORD_DATA = {
            // Category 0 Practice Courses
            aiueo: [["愛","あい"],["青","あお"],["上","うえ"],["家","いえ"],["会う","あう"],["言う","いう"],["追う","おう"],["甥","おい"],["葵","あおい"],["魚","うお"],["絵","え"],["胃","い"],["良い","いい"],["相愛","あいあい"],["多い","おおい"],["意","い"],["威","い"],["逢う","あう"],["覆う","おおう"],["青い","あおい"]],
            kakikukeko: [["柿","かき"],["菊","きく"],["苔","こけ"],["過去","かこ"],["茎","くき"],["欠く","かく"],["描く","かく"],["聴く","きく"],["牡蠣","かき"],["書く","かく"],["効く","きく"],["掻く","かく"]],
            a_to_so: [["朝","あさ"],["傘","かさ"],["鹿","しか"],["咲く","さく"],["坂","さか"],["底","そこ"],["景色","けしき"],["組織","そしき"],["草","くさ"],["席","せき"],["刺す","さす"],["貸す","かす"],["塩","しお"],["汗","あせ"],["声","こえ"],["菓子","かし"],["酒","さけ"],["息","いき"],["嘘","うそ"],["椅子","いす"],["石","いし"],["牛","うし"],["医師","いし"],["式","しき"],["越す","こす"],["赤","あか"],["青","あお"],["寿司","すし"],["家","いえ"],["上","うえ"]],
            a_to_n: [["桜","さくら"],["机","つくえ"],["日本","にほん"],["花","はな"],["祭り","まつり"],["道","みち"],["山","やま"],["雪","ゆき"],["空","そら"],["栗","くり"],["鳥","とり"],["雲","くも"],["海","うみ"],["棚","たな"],["星","ほし"],["虫","むし"],["月","つき"],["船","ふね"],["角","つの"],["肩","かた"],["光","ひかり"],["森","もり"],["川","かわ"],["秋","あき"],["冬","ふゆ"],["夏","なつ"],["春","はる"],["琴","こと"],["糸","いと"],["庭","にわ"]],
            dakuon_handakuon: [["象","ぞう"],["豚","ぶた"],["ゴリラ","ごりら"],["パンダ","ぱんだ"],["カバ","かば"],["雀","すずめ"],["ダンゴムシ","だんごむし"],["トカゲ","とかげ"],["兎","うさぎ"],["メダカ","めだか"],["クラゲ","くらげ"],["薔薇","ばら"],["紫陽花","あじさい"],["蒲公英","たんぽぽ"],["葡萄","ぶどう"],["苺","いちご"],["バナナ","ばなな"],["ピザ","ぴざ"],["ボタン","ぼたん"],["眼鏡","めがね"],["ベンチ","べんち"],["ベッド","べっど"],["電車","でんしゃ"],["風","かぜ"],["水","みず"],["影","かげ"],["銀河","ぎんが"],["団子","だんご"],["鍵","かぎ"],["地図","ちず"]],
            sokuon_youon: [["学校","がっこう"],["切手","きって"],["雑誌","ざっし"],["楽器","がっき"],["石鹸","せっけん"],["お茶","おちゃ"],["牛乳","ぎゅうにゅう"],["写真","しゃしん"],["金魚","きんぎょ"],["恐竜","きょうりゅう"],["忍者","にんじゃ"],["医者","いしゃ"],["列車","れっしゃ"],["自転車","じてんしゃ"],["自動車","じどうしゃ"],["野球","やきゅう"],["地球","ちきゅう"],["会社","かいしゃ"],["神社","じんじゃ"],["図書館","としょかん"],["勉強","べんきょう"],["宿題","しゅくだい"],["発表","はっぴょう"],["サッカー","さっかー"],["ラケット","らけっと"],["トラック","とらっく"],["ロケット","ろけっと"],["百円","ひゃくえん"],["一緒","いっしょ"],["今日","きょう"]],

            japanese: [["漢字","かんじ"],["仮名","かな"],["音読","おんどく"],["朗読","ろうどく"],["段落","だんらく"],["主語","しゅご"],["述語","じゅつご"],["修飾語","しゅうしょくご"],["接続詞","せつぞくし"],["感動詞","かんどうし"],["擬音語","ぎおんご"],["擬態語","ぎたいご"],["比喩","ひゆ"],["対句","ついく"],["故事成語","こじせいご"],["対義語","たいぎご"],["類義語","るいぎご"],["同音異義語","どうおんいぎご"],["熟語","じゅくご"],["部首","ぶしゅ"],["画数","かくすう"],["送り仮名","おくりがな"],["読解","どっかい"],["要約","ようやく"],["原稿用紙","げんこうようし"],["拝啓","はいけい"],["敬具","けいぐ"],["敬語","けいご"],["謙譲語","けんじょうご"],["尊敬語","そんけいご"]],
            math: [["たし算","たしざん"],["ひき算","ひきざん"],["かけ算","かけざん"],["わり算","わりざん"],["九九","くく"],["整数","せいすう"],["小数","しょうすう"],["分数","ぶんすう"],["通分","つうぶん"],["約分","やくぶん"],["三角形","さんかくけい"],["四角形","しかくけい"],["円周率","えんしゅうりつ"],["直線","ちょくせん"],["平行","へいこう"],["垂直","すいちょく"],["角度","かくど"],["面積","めんせき"],["体積","たいせき"],["割合","わりあい"],["百分率","ひゃくぶんりつ"],["比例","ひれい"],["反比例","はんひれい"],["偶数","ぐうすう"],["奇数","きすう"],["倍数","ばいすう"],["約数","やくすう"],["平均","へいきん"],["展開図","てんかいず"],["グラフ","ぐらふ"]],
            science: [["光合成","こうごうせい"],["蒸散","じょうさん"],["水溶液","すいようえき"],["酸性","さんせい"],["アルカリ性","あるかりせい"],["顕微鏡","けんびきょう"],["昆虫","こんちゅう"],["メダカ","めだか"],["状態変化","じょうたいへんか"],["蒸発","じょうはつ"],["凝縮","ぎょうしゅく"],["てこ","てこ"],["支点","してん"],["作用点","さようてん"],["力点","りきてん"],["電流","でんりゅう"],["導線","どうせん"],["電磁石","でんじしゃく"],["太陽","たいよう"],["月の満ち欠け","つきのみちかけ"],["天体","てんたい"],["地層","ちそう"],["化石","かせき"],["地震","じしん"],["火山","かざん"],["呼吸","こきゅう"],["消化","しょうか"],["血液循環","けつえきじゅんかん"],["環境","かんきょう"],["生態系","せいたいけい"]],
            social: [["日本列島","にほんれっとう"],["都道府県","とどうふけん"],["県庁所在地","けんちょうしょざいち"],["縄文時代","じょうもんじだい"],["弥生時代","やよいじだい"],["古墳時代","こふんじだい"],["平安京","へいあんきょう"],["鎌倉幕府","かまくらばくふ"],["室町時代","むろまちじだい"],["江戸幕府","えどばくふ"],["明治維新","めいじいしん"],["太平洋戦争","たいへいようせんそう"],["日本国憲法","にほんこくけんぽう"],["三権分立","さんけんぶんりつ"],["国会","こっかい"],["内閣","ないかく"],["裁判所","さいばんしょ"],["地方自治","ちほうじち"],["貿易","ぼうえき"],["農業","のうぎょう"],["水産業","すいさんぎょう"],["工業地帯","こうぎょうちたい"],["地球温暖化","ちきゅうおんだんか"],["情報化社会","じょうほうかしゃかい"],["資源","しげん"],["交通網","こうつうもう"],["市役所","しやくしょ"],["伝統工芸","でんとうこうげい"],["国際連合","こくさいれんごう"],["少子高齢化","しょうしこうれいか"]],
            history_people: [["卑弥呼","ひみこ"],["聖徳太子","しょうとくたいし"],["聖武天皇","しょうむてんのう"],["紫式部","むらさきしきぶ"],["源頼朝","みなもとのよりとも"],["源義経","みなもとのよしつね"],["足利尊氏","あしかがたかうじ"],["織田信長","おだのぶなが"],["豊臣秀吉","とよとみひでよし"],["徳川家康","とくがわいえやす"],["徳川家光","とくがわいえみつ"],["坂本龍馬","さかもとりょうま"],["西郷隆盛","さいごうたかもり"],["勝海舟","かつかいしゅう"],["板垣退助","いたがきたいすけ"],["伊藤博文","いとうひろぶみ"],["福沢諭吉","ふくざわゆきち"],["野口英世","のぐちひでよ"],["樋口一葉","ひぐちいちよう"],["夏目漱石","なつめそうせき"],["宮沢賢治","みやざわけんじ"],["与謝野晶子","よさのあきこ"],["平塚らいてう","ひらつからいてう"],["杉原千畝","すぎはらちうね"],["湯川秀樹","ゆかわひでき"],["葛飾北斎","かつしかほくさい"],["歌川広重","うたがわひろしげ"],["雪舟","せっしゅう"],["千利休","せんのりきゅう"],["松尾芭蕉","まつおばしょう"]],
            music: [["リコーダー","りこーだー"],["鍵盤ハーモニカ","けんばんはーもにか"],["木琴","もっきん"],["鉄琴","てっきん"],["大太鼓","おおだいこ"],["小太鼓","こだいこ"],["シンバル","しんばる"],["トライアングル","とらいあんぐる"],["カスタネット","かすたねっと"],["タンバリン","たんばりん"],["ト音記号","とおんきごう"],["ヘ音記号","へおんきごう"],["五線譜","ごせんふ"],["ハ長調","はちょうちょう"],["音符","おんぷ"],["休符","きゅうふ"],["拍子","ひょうし"],["テンポ","てんぽ"],["合唱","がっしょう"],["合奏","がっそう"],["指揮者","しきしゃ"],["発声練習","はっせいれんしゅう"],["校歌","こうか"],["旋律","せんりつ"],["和音","わおん"],["輪唱","りんしょう"],["アカペラ","あかぺら"],["伴奏","ばんそう"],["歌声","うたごえ"],["ドレミファソラシド","どれみふぁそらしど"]],
            art: [["水彩絵の具","すいさいえのぐ"],["彫刻刀","ちょうこくとう"],["版画","はんが"],["粘土","ねんど"],["画用紙","がようし"],["筆","ふで"],["パレット","ぱれっと"],["デザイン","でざいん"],["工作","こうさく"],["スケッチ","すけっち"],["デッサン","でっさん"],["風景画","ふうけいが"],["肖像画","しょうぞうが"],["混色","こんしょく"],["明暗","めいあん"],["グラデーション","ぐらでーしょん"],["立体作品","りったいさくひん"],["針金","はりがね"],["折り紙","おりがみ"],["千代紙","ちよがみ"],["鑑賞","かんしょう"],["色彩","しきさい"],["一筆描き","いっぷでがき"],["木工","もっこう"],["ニス","にす"],["接着剤","せっちゃくざい"],["影","かげ"],["構図","こうず"],["展示","てんじ"],["芸術","げいじゅつ"]],
            pe: [["準備運動","じゅんびうんどう"],["整理運動","せいりうんどう"],["陸上競技","りくじょうきょうぎ"],["50メートル走","ごじゅうめーとるそう"],["リレー","りれー"],["バトンパス","ばとんぱす"],["跳び箱","とびばこ"],["マット運動","まっとうんどう"],["鉄棒","てつぼう"],["前回り","まえまわり"],["逆上がり","さかあがり"],["平均台","へいきんだい"],["水泳","すいえい"],["クロール","くろーる"],["平泳ぎ","ひらおよぎ"],["背泳ぎ","せおよぎ"],["ラジオ体操","らじおたいそう"],["サッカー","さっかー"],["バスケットボール","ばすけっとぼーる"],["ポートボール","ぽーとぼーる"],["ドッジボール","どっじぼーる"],["大縄跳び","おおなわとび"],["一輪車","いちりんしゃ"],["竹馬","たけうま"],["体力測定","たいりょくそくてい"],["徒競走","ときょうそう"],["応援合戦","おうえんがっせん"],["組体操","くみたいそう"],["ダンス","だんす"],["体育館","たいいくかん"]],
            school_items: [["黒板","こくばん"],["チョーク","ちょーく"],["黒板消し","こくばんけし"],["机","つくえ"],["椅子","いす"],["ランドセル","らんどせる"],["筆箱","ふでばこ"],["鉛筆","えんぴつ"],["消しゴム","けしごむ"],["定規","じょうぎ"],["コンパス","こんぱす"],["分度器","ぶんどき"],["ノート","のーと"],["教科書","きょうかしょ"],["ドリル","どりる"],["体育館","たいいくかん"],["運動場","うんどうじょう"],["プール","ぷーる"],["理科室","りかしつ"],["音楽室","おんがくしつ"],["図工室","ずこうしつ"],["保健室","ほけんしつ"],["図書館","としょかん"],["跳び箱","とびばこ"],["鍵盤ハーモニカ","けんばんはーもにか"],["リコーダー","りこーだー"],["水彩絵の具","すいさいえのぐ"],["名札","なふだ"],["連絡帳","れんらくちょう"],["上履き","うわばき"]],
            school_lunch: [["コッペパン","こっぺぱん"],["揚げパン","あげぱん"],["カレーライス","かれーらいす"],["ソフト麺","そふとめん"],["揚げ餃子","あげぎょうざ"],["竜田揚げ","たつたあげ"],["冷凍みかん","れいとうみかん"],["わかめご飯","わかめごはん"],["ポークカレー","ぽーくかれー"],["ミートソース","みーとそーす"],["ポテトサラダ","ぽてとさらだ"],["マカロニグラタン","まかろにぐらたん"],["コーンスープ","こーんすーぷ"],["ABCスープ","えーびーしーすーぷ"],["ワンタンスープ","わんたんすーぷ"],["フルーツポンチ","ふるーつポンち"],["瓶牛乳","びんぎゅうにゅう"],["ミルメーク","みるめーく"],["ビビンバ","びびんば"],["チキン南蛮","ちきんなんばん"],["春巻き","はるまき"],["クリームシチュー","くりーむしちゅー"],["ドライカレー","どらいかれー"],["鯖の味噌煮","さばのみそに"],["五目ご飯","ごもくごはん"],["豚汁","とんじる"],["バンサンスー","ばんさんすー"],["大学芋","だいがくいも"],["フルーツサンド","ふるーつさんど"],["ナポリタン","なぽりたん"]],
            
            prefectures: [["北海道","ほっかいどう"],["青森県","あおもりけん"],["岩手県","いわてけん"],["宮城県","みやぎけん"],["秋田県","あきたけん"],["山形県","やまがたけん"],["福島県","ふくしまけん"],["茨城県","いばらきけん"],["栃木県","とちぎけん"],["群馬県","ぐんまけん"],["埼玉県","さいたまけん"],["千葉県","ちばけん"],["東京都","とうきょうと"],["神奈川県","かながわけん"],["新潟県","にいがたけん"],["富山県","とやまけん"],["石川県","いしかわけん"],["福井県","ふくいけん"],["山梨県","やまなしけん"],["長野県","ながのけん"],["岐阜県","ぎふけん"],["静岡県","しずおかけん"],["愛知県","あいちけん"],["三重県","みえけん"],["滋賀県","しがけん"],["京都府","きょうとふ"],["大阪府","おおさかふ"],["兵庫県","ひょうごけん"],["奈良県","ならけん"],["和歌山県","わかやまけん"],["鳥取県","とっとりけん"],["島根県","しまねけん"],["岡山県","おかやまけん"],["広島県","ひろしまけん"],["山口県","やまぐちけん"],["徳島県","とくしまけん"],["香川県","かがわけん"],["愛媛県","えひめけん"],["高知県","こうちけん"],["福岡県","ふくおかけん"],["佐賀県","さがけん"],["長崎県","ながさかけん"],["熊本県","くまもとけん"],["大分県","おおいたけん"],["宮崎県","みやざきけん"],["鹿児島県","かごしまけん"],["沖縄県","おきなわけん"]],
            prefectural_capitals: [["札幌市","さっぽろし"],["青森市","あおもりし"],["盛岡市","もりおかし"],["仙台市","せんだいし"],["秋田市","あきたし"],["山形市","やまがたし"],["福島市","ふくしまし"],["水戸市","みとし"],["宇都宮市","うつのみやし"],["前橋市","まえばしし"],["さいたま市","さいたまし"],["千葉市","ちばし"],["新宿区","しんじゅくく"],["横浜市","よこはまし"],["新潟市","にいがたし"],["富山市","とやまし"],["金沢市","かなざわし"],["福井市","ふくいし"],["甲府市","こうふし"],["長野市","ながのし"],["岐阜市","ぎふし"],["静岡市","しずおかし"],["名古屋市","なごやし"],["津市","つし"],["大津市","おおつし"],["京都市","きょうとし"],["大阪市","おおさかし"],["神戸市","こうべし"],["奈良市","ならし"],["和歌山市","わかやまし"],["鳥取市","とっとりし"],["松江市","まつえし"],["岡山市","おかやまし"],["広島市","ひろしまし"],["山口市","やまぐちし"],["徳島市","とくしまし"],["高松市","たかまつし"],["松山市","まつやまし"],["高知市","こうちし"],["福岡市","ふくおかし"],["佐賀市","さがし"],["長崎市","ながさきし"],["熊本市","くまもとし"],["大分市","おおいたし"],["宮崎市","みやざきし"],["鹿児島市","かごしまし"],["那覇市","なはし"]],
            mountains: [["富士山","ふじさん"],["北岳","きただけ"],["奥穂高岳","おくほたかだけ"],["間ノ岳","あいのだけ"],["槍ヶ岳","やりがたけ"],["悪沢岳","わるさわだけ"],["赤石岳","あかいしだけ"],["涸沢岳","からさわだけ"],["北穂高岳","きたほたかだけ"],["大喰岳","おおばみだけ"],["前穂高岳","まえほたかだけ"],["中岳","なかだけ"],["荒川中岳","あらかわなかだけ"],["御嶽山","おんたけさん"],["塩見岳","しおみだけ"],["仙丈ヶ岳","せんじょうがたけ"],["立山","たてやま"],["聖岳","ひじりだけ"],["剱岳","つるぎだけ"],["薬師岳","やくしだけ"],["乗鞍岳","のりくらだけ"],["黒部五郎岳","くろべごろうだけ"],["白山","はくさん"],["八ヶ岳","やつがたけ"],["阿蘇山","あそさん"],["大山","だいせん"],["筑波山","つくばさん"],["石鎚山","いしづちさん"],["開聞岳","かいもんだけ"],["岩手山","いわてさん"]],
            rivers: [["信濃川","しなのがわ"],["利根川","とねがわ"],["石狩川","いしかりがわ"],["勅使川","てしおがわ"],["北上川","きたかがみがわ"],["阿賀野川","あがのがわ"],["モガミ川","もがみがわ"],["天竜川","てんりゅうがわ"],["吉野川","よしのがわ"],["四万十川","しまんとがわ"],["木曽川","きそがわ"],["多摩川","たまがわ"],["荒川","あらかわ"],["淀川","よどがわ"],["筑後川","ちくごがわ"],["熊野川","くまのがわ"],["長良川","ながらがわ"],["揖斐川","いびがわ"],["富士川","ふじかわ"],["球磨川","くみがわ"],["大井川","おおいがわ"],["高津川","たかつがわ"],["神通川","じんづうがわ"],["黒部川","くろべがわ"],["庄川","しょうがわ"],["斐伊川","ひいかわ"],["相模川","さがみがわ"],["渡良瀬川","わたらせがわ"],["鬼怒川","きぬがわ"],["江戸川","えどがわ"]],
            lakes: [["琵琶湖","びわこ"],["霞ヶ浦","かすみがうら"],["サロマ湖","さろまこ"],["猪苗代湖","いなわしろこ"],["中禅寺湖","ちゅうぜんじこ"],["浜名湖","はまなこ"],["十和田湖","とわだこ"],["屈斜路湖","くっしゃろこ"],["支笏湖","しこつこ"],["洞爺湖","とうやこ"],["田沢湖","たざわこ"],["諏訪湖","すわこ"],["宍道湖","しんじこ"],["芦ノ湖","あしのこ"],["山中湖","やまなかこ"],["河口湖","かわぐちこ"],["本栖湖","もとすこ"],["精進湖","しょうじこ"],["西湖","さいこ"],["摩周湖","ましゅうこ"],["阿寒湖","あかんこ"],["小川原湖","おがわらこ"],["八郎潟","はちろうがた"],["能取湖","のとりこ"],["風蓮湖","ふうれんこ"],["十三湖","じゅうさんこ"],["然別湖","しかりべつこ"],["余呉湖","よごこ"],["神西湖","じんざいこ"],["池田湖","いけだこ"]],
            hot_springs: [["草津温泉","くさつおんせん"],["箱根温泉","はこねおんせん"],["有馬温泉","ありまおんせん"],["別府温泉","べっぷおんせん"],["登別温泉","のぼりべつおんせん"],["道後温泉","どうごおんせん"],["由布院温泉","ゆふいんおんせん"],["城崎温泉","きのさきおんせん"],["熱海温泉","あたみおんせん"],["伊香保温泉","いかほおんせん"],["下呂温泉","げろおんせん"],["銀山温泉","ぎんざんおんせん"],["鬼怒川温泉","きぬがわおんせん"],["黒川温泉","くろかわおんせん"],["乳頭温泉","にゅうとうおんせん"],["蔵王温泉","ざおうおんせん"],["和倉温泉","わくらおんせん"],["指宿温泉","いぶすきおんせん"],["修善寺温泉","しゅぜんじおんせん"],["万座温泉","まんざおんせん"],["白骨温泉","しらほねおんせん"],["野沢温泉","のざわおんせん"],["玉川温泉","たまがわおんせん"],["湯田中温泉","ゆだなかおんせん"],["定山渓温泉","じょうざんけいおんせん"],["阿蘇温泉","あそおんせん"],["皆生温泉","かいけおんせん"],["三朝温泉","みささおんせん"],["湯布院","ゆふいん"],["湯の峰温泉","ゆのみねおんせん"]],
            japan_sightseeing: [["金閣寺","きんかくじ"],["清水寺","きよみずでら"],["伏見稲荷大社","ふしみいなりたいしゃ"],["巌島神社","いつくしまじんじゃ"],["日光東照宮","にっこうとうしょうぐう"],["姫路城","ひめじじょう"],["富士山","ふじさん"],["東京タワー","とうきょうたわー"],["東京スカイツリー","とうきょうすかいつりー"],["浅草寺","せんそうじ"],["兼六園","けんろくえん"],["伊勢神宮","いせじんぐう"],["出雲大社","いずもたいしゃ"],["松島","まつしま"],["天橋立","あまのはしだて"],["宮島","みやじま"],["首里城","しゅりじょう"],["熊本城","くまもとじょう"],["松本城","まつもとじょう"],["美ら海水族館","ちゅらうみすいぞくかん"],["道頓堀","どうとんぼり"],["嵐山","あらしやま"],["屋久島","やくしま"],["白川郷","しらかわごう"],["阿蘇山","あそさん"],["高野山","こうやさん"],["箱根","はこね"],["小樽運河","おたるうんが"],["富良野","ふらの"],["厳島","いつくしま"]],
            world_heritage: [["マチュピチュ","まちゅぴちゅ"],["サグラダファミリア","さぐらだふぁみりあ"],["万里の長城","ばんりのちょうじょう"],["ピラミッド","ぴらみっど"],["タージマハル","たーじまはる"],["自由の女神","じゆうのめがみ"],["グランドキャニオン","ぐらんどきゃにおん"],["モンサンミッシェル","もんさんみっしぇる"],["コロッセオ","ころっせお"],["アンコールワット","あんこーるわっと"],["ペトラ遺跡","ぺとらいせき"],["イグアスの滝","いぐあすのたき"],["ガルパン島","ガルパンとう"],["イースター島","いーすたーとう"],["グレートバリアリーフ","ぐれーとばりありーふ"],["白川郷","しらかわごう"],["屋久島","やくしま"],["日光の社寺","にっこうのしゃじ"],["古都京都の文化財","こときょうとのぶんかざい"],["知床","しれとこ"],["平泉","ひらいずみ"],["小笠原諸島","おがさわらしょとう"],["富士山","ふじさん"],["富岡製糸場","とみおかせいしじょう"],["明治日本の産業革命遺産","めいじにほんのさんぎょうかくめいいさん"],["国立西洋美術館","こくりつせいようびじゅつかん"],["百舌鳥古市古墳群","もずふるいちこふんぐん"],["奄美大島","あまみおおしま"],["徳之島","とくのしま"],["西表島","いりおもてじま"]],
            world_sightseeing: [["エッフェル塔","えっふぇるとう"],["ルーブル美術館","るーぶるびじゅつかん"],["タイムズスクエア","たいむずすくえあ"],["オペラハウス","おぺらはうす"],["ビッグベン","びっぐべん"],["ウユニ塩湖","うゆにしおこ"],["カッパドキア","かっぱどきあ"],["サントリーニ島","さんとりーにとう"],["ベネチア","べねちあ"],["ナイアガラの滝","ないあがらのたき"],["ピサの斜塔","ぴさのしゃとう"],["マーライオン","まーらいおん"],["ブルジュハリファ","ぶるじゅはりふぁ"],["ノイシュバンシュタイン城","のいしゅばんしゅたいんじょう"],["ストーンヘンジ","すとーんへんじ"],["シェーンブルン宮殿","しぇーんぶるんきゅうでん"],["プラハ城","ぷらはじょう"],["モスクワの赤の広場","もすくわのあかのひろば"],["ドゥブロヴニク","どぅぶろぶにく"],["ゴールデンゲートブリッジ","ごーるでんげーとぶりっじ"],["ディズニードリーム","でぃずにーどりーむ"],["せんとらるぱーく","せんとらるぱーく"],["バチカン市国","ばちかんしこく"],["アルハンブラ宮殿","あるはんぶらきゅうでん"],["フィレンツェ大聖堂","ふぃれんつぇだいせいどう"],["モンサンミッシェル","もんさんみっしぇる"],["アクロポリス","あくろぽりす"],["ギザのピラミッド","ぎざのぴらみっど"],["アンコールワット","あんこーるわっと"],["タージマハル","たーじまはる"]],
            us_states: [["カリフォルニア","かりふぉるにあ"],["テキサス","てきさす"],["フロリダ","ふろりだ"],["ニューヨーク","にゅーよーく"],["ペンシルベニア","ぺんしるべにあ"],["イリノイ","いりのい"],["オハイオ","おはいお"],["ジョージア","じょーじあ"],["ノースカロライナ","のーすかろらいな"],["ミシガン","みしがん"],["ニュージャージー","にゅーじゃーじー"],["バージニア","ばーじにあ"],["ワシントン","わしんとん"],["アリゾナ","ありぞな"],["マサチューセッツ","まさちゅーせっつ"],["テネシー","てねしー"],["インディアナ","いんでぃあな"],["ミズーリ","みずーり"],["メリーランド","めりーらんど"],["ウィスコンシン","うぃすこんしん"],["コロラド","ころらど"],["ミネソタ","みねそた"],["サウスカロライナ","さうすかろらいな"],["アラバマ","あらばま"],["ルイジアナ","るいじあな"],["ケンタッキー","けんたっきー"],["オレゴン","おれごん"],["オクラホマ","おくらほま"],["コネチカット","こねちかっと"],["ユタ","ゆた"]],
            
            asia_countries: [["日本","にほん"],["韓国","かんこく"],["中国","ちゅうごく"],["台湾","たいわん"],["インド","いんど"],["タイ","たい"],["ベトナム","べとなむ"],["フィリピン","ふぃりぴん"],["インドネシア","いんどねしあ"],["マレーシア","まれーしあ"],["シンガポール","しんがぽーる"],["ミャンマー","みゃんまー"],["カンボジア","かんぼじあ"],["ラオス","らおす"],["ネパール","ねぱーる"],["スリランカ","すりらんか"],["パキスタン","ぱきすたん"],["バングラデシュ","ばんぐらでしゅ"],["モンゴル","もんごる"],["モルディブ","もるでぃぶ"],["サウジアラビア","さうじあらびあ"],["アラブ首長国連邦","あらぶしゅちょうこくれんぽう"],["トルコ","とるこ"],["イラン","いらん"],["イラク","いらく"],["カザフスタン","かざふすたん"],["ウズベキスタン","うずべきすたん"],["ヨルダン","よるだん"],["カタール","かたーる"],["オマーン","おまーん"]],
            europe_countries: [["イギリス","いぎりす"],["フランス","ふらんす"],["ドイツ","どいつ"],["イタリア","いたりあ"],["スペイン","すぺいん"],["ポルトガル","ぽるとがる"],["オランダ","おらんだ"],["ベルギー","べるぎー"],["スイス","すいす"],["オーストリア","おーすとりあ"],["ギリシャ","ぎりしゃ"],["スウェーデン","すうぇーでん"],["ノルウェー","のるうぇー"],["フィンランド","ふぃんらんど"],["デンマーク","でんまーく"],["アイルランド","あいるらんど"],["ポーランド","ぽーらんど"],["チェコ","ちぇこ"],["ハンガリー","はんがりー"],["ルーマニア","るーまにあ"],["ブルガリア","ぶるがりあ"],["クロアチア","くろあちあ"],["セルビア","せるびあ"],["ウクライナ","うくらいな"],["スロバキア","すろばきあ"],["スロベニア","すろべにあ"],["エストニア","えすとにあ"],["ラトビア","らとびあ"],["リトアニア","りとあにあ"],["モナコ","もなこ"]],
            americas_oceania_countries: [["アメリカ","あめりか"],["カナダ","かなだ"],["メキシコ","めきしこ"],["ブラジル","ぶらじる"],["アルゼンチン","あるぜんちん"],["チリ","ちり"],["コロンビア","ころんびあ"],["ペルー","ぺるー"],["ベネズエラ","べねずえら"],["ウルグアイ","うるぐあい"],["パラグアイ","ぱらぐあい"],["ボリビア","ぼりびあ"],["キューバ","きゅーば"],["ジャマイカ","じゃまいか"],["コスタリカ","こすたりか"],["パナマ","ぱなま"],["エクアドル","えくあどる"],["オーストラリア","おーすとらりあ"],["ニュージーランド","にゅーじーらんど"],["フィジー","ふぃじー"],["パプアニューギニア","ぱぷあにゅーぎにあ"],["サモア","さもあ"],["トンガ","とんが"],["パラオ","ぱらお"],["マーシャル諸島","まーしゃるしょとう"],["ソロモン諸島","そろもんしょとう"],["バヌアツ","ばぬあつ"],["ミクロネシア","みくろねしあ"],["グアテマラ","ぐあてまら"],["ハイチ","はいち"]],
            africa_countries: [["エジプト","えじぷと"],["ケニア","けにあ"],["ナイジェリア","ないじぇりあ"],["ガーナ","がーな"],["南アフリカ","みなみあふりか"],["モロッコ","もろっこ"],["チュニジア","ちゅにじあ"],["アルジェリア","あるじぇりあ"],["エチオピア","えちおぴあ"],["タンザニア","たんざにあ"],["ウガンダ","うがんだ"],["せねガル","せねがる"],["カメルーン","かめるーん"],["マダガスカル","まだがすかる"],["ジンバブエ","じんばぶえ"],["ザンビア","ざんびあ"],["アンゴラ","あんごら"],["モザンビーク","もざんびーく"],["コートジボワール","こーとじぼわーる"],["マリ","まり"],["ニジェール","にじぇーる"],["スーダン","すーだん"],["ルワンダ","るわんだ"],["コンゴ民主共和国","こんごみんしゅきょうわこく"],["ギニア","ぎニア"],["ガボン","がぼん"],["ボツワナ","ぼつわな"],["ナミビア","なみびあ"],["リビア","りびあ"],["ソマリア","そまりあ"]],
            asia_capitals: [["東京","とうきょう"],["ソウル","そうる"],["北京","ぺきん"],["台北","たいぺい"],["ニューデリー","にゅーでりー"],["バンコク","ばんこく"],["ハノイ","はのい"],["マニラ","まにら"],["ジャカルタ","じゃかるた"],["クアラルンプール","くあらるんぷーる"],["シンガポール","しんがぽーる"],["ネピドー","ねぴどー"],["プノンペン","ぷのんぺん"],["ビエンチャン","びえんちゃん"],["カトマンズ","かとまんず"],["コロンボ","ころんぼ"],["イスラマバード","いすらまばーど"],["だっか","だっか"],["ウランバートル","うらんばーとる"],["マレ","まれ"],["リヤド","りやど"],["アブダビ","あぶだび"],["アンカラ","あんから"],["テヘラン","てへらん"],["バグダッド","ばぐだっど"],["アスタナ","あすたな"],["タシケント","たしけんと"],["アンマン","あんまん"],["ドーハ","どーは"],["マスカット","ますかっと"]],
            europe_capitals: [["ロンドン","ろんどん"],["パリ","ぱり"],["ベルリン","べるりん"],["ローマ","ろーま"],["マドリード","まどりーど"],["リスボン","りすぼん"],["アムステルダム","あむすてるだむ"],["ブリュッセル","ぶりゅっせる"],["ベルン","べるん"],["ウィーン","うぃーん"],["アテネ","あてね"],["ストックホルム","すとっくほるむ"],["オスロ","おすろ"],["ヘルシンキ","へるしんき"],["コペンハーゲン","こぺんはーげん"],["ダブリン","だぶりん"],["ワルシャワ","わるしゃわ"],["プラハ","ぷらは"],["ブダペスト","ぶだぺすと"],["ブクレシュティ","ぶくれしゅてぃ"],["ソフィア","そふぃあ"],["ザグレブ","ざぐれぶ"],["ベオグラード","べおぐらーど"],["キエフ","きえふ"],["ブラチスラヴァ","ぶらちすらゔぁ"],["リュブリャナ","りゅぶりゃな"],["たりん","たりん"],["リガ","りが"],["ヴィルニュス","びるにゅす"],["モナコ","もなこ"]],
            americas_oceania_capitals: [["ワシントン","わしんとん"],["オタワ","おたわ"],["メキシコシティ","めきしこしてぃ"],["ブラジリア","ぶらじりあ"],["ブエノスアイレス","ぶえのすあいれす"],["サンティアゴ","さんてぃあご"],["ボゴタ","ぼごた"],["リマ","りま"],["カラカス","からかす"],["モンテビデオ","もんてびでお"],["アスンシオン","あすんしおん"],["ラパス","らぱす"],["ハバナ","はばな"],["キングストン","きんぐすとん"],["サンホセ","さんほせ"],["パナマシティ","ぱなましてぃ"],["キト","きと"],["キャンベラ","きゃんべら"],["ウェリントン","うぇりんとん"],["スバ","すば"],["ポートモレスビー","ぽーともれすびー"],["アピア","あぴあ"],["ヌクアロファ","ぬくあろふぁ"],["マルキョク","まるきょく"],["マジュロ","まじゅろ"],["ホニアラ","ほにあら"],["ポートビラ","ぽーとびら"],["パリキール","ぱりきーる"],["ぐあてまらしてぃ","ぐあてまらしてぃ"],["ぽるとーぷらんす","ぽるとーぷらんす"]],
            africa_capitals: [["カイロ","かいろ"],["ナイロビ","ないろび"],["アブジャ","あぶじゃ"],["アクラ","あくら"],["プレトリア","ぷれとりあ"],["ラバト","らばと"],["チュニス","ちゅにす"],["アルジェ","あるじぇ"],["アディスアベバ","あでぃすあべば"],["ドドマ","どどま"],["カンパラ","かんぱら"],["ダカール","だかーる"],["ヤウンデ","やうんで"],["アンタナナリボ","あんたななりぼ"],["ハラレ","はられ"],["ルサカ","るさか"],["ルアンダ","るあんだ"],["マプト","まぷと"],["ヤムスクロ","やむすくろ"],["バマコ","ばまこ"],["ニアメ","にあめ"],["ハルツーム","はるつーむ"],["キガリ","きがり"],["キンシャサ","きんしゃさ"],["こなくり","こなくり"],["リーブルビル","りーぶるびる"],["ハボローネ","はぼろーね"],["ウィントフック","うぃんとふっく"],["トリポリ","とりぽり"],["モガディシュ","もがでぃしゅ"]],

            sengoku: [["織田信長","おだのぶなが"],["豊臣秀吉","とよとみひでよし"],["徳川家康","とくがわいえやす"],["武田信玄","たけだしんげん"],["上杉謙信","うえすぎけんしん"],["伊達政宗","だてまさむね"],["真田幸村","さなだゆきむら"],["明智光秀","あけちみつひで"],["石田三成","いしだみつなり"],["毛利元就","もうりもとなり"],["長宗我部元親","ちょうそかべもとちか"],["島津義弘","しまづよしひろ"],["本多忠勝","ほんだただかつ"],["前田利家","まえだとしいえ"],["服部半蔵","はっとりはんぞう"],["直江兼続","なおえかねつぐ"],["加藤清正","かとうきよまさ"],["福島正則","ふくしままさのり"],["竹中半兵衛","たけなかはんべえ"],["黒田官兵衛","くろだかんべえ"],["井伊直政","いいなおまさ"],["榊原康政","さかきばらやすまさ"],["酒井忠次","さかいただつぐ"],["柴田勝家","しばたかついえ"],["丹羽長秀","にわながひで"],["今川義元","いまがわよしもと"],["斎藤道三","さいとうどうさん"],["浅井長政","あざいながまさ"],["朝倉義景","あさくらよしかげ"],["北条氏康","ほうじょううじやす"]],
            sangokushi: [["劉備","りゅうび"],["関羽","かんう"],["張飛","ちょうひ"],["諸葛亮","しょかつりょう"],["趙雲","ちょううん"],["馬超","ばちょう"],["黄忠","こうちゅう"],["魏延","ぎえん"],["姜維","きょうい"],["曹操","そうそう"],["夏侯惇","かこうとん"],["夏侯淵","かこうえん"],["曹仁","そうじん"],["張遼","ちょうりょう"],["徐晃","じょこう"],["張郃","ちょうこう"],["司馬懿","しばい"],["孫権","そんけん"],["周瑜","しゅうゆ"],["陸遜","りくそん"],["呂蒙","りょもう"],["甘寧","かんねい"],["太史慈","たいしじ"],["黄蓋","こうがい"],["孫策","そんさく"],["孫堅","そんけん"],["呂布","りょふ"],["董卓","とうたく"],["袁紹","えんしょう"],["袁術","えんじゅつ"]],
            pm_japan: [["伊藤博文","いとうひろぶみ"],["黒田清隆","くろだきよたか"],["山県有朋","やまがたありとも"],["松方正義","まつかたまさよし"],["大隈重信","おおくましげのぶ"],["桂太郎","かつらたろう"],["西園寺公望","さいおんじきんもち"],["山本権兵衛","やまもとごんべえ"],["寺内正毅","てらうちまさたけ"],["原敬","はらたかし"],["高橋是清","たかはしこれきよ"],["加藤友三郎","かとうともさぶろう"],["清浦奎吾","きようらけいご"],["加藤高明","かとうたかあき"],["若槻礼次郎","わかつきれいじろう"],["田中義一","たなかぎいち"],["浜口雄幸","はまぐちおさち"],["犬養毅","いぬかいつよし"],["斎藤実","さいとうまこと"],["岡田啓介","おかだけいすけ"],["広田弘毅","ひろたこうき"],["林銑十郎","はやしせんじゅうろう"],["近衛文麿","このえふみまろ"],["平沼騏一郎","ひらぬまきいちろう"],["阿部信行","あべのぶゆき"],["米内光政","よないみつまさ"],["東条英機","とうじょうひでき"],["小磯国昭","こいそくにあき"],["鈴木貫太郎","すずきかんたろう"],["吉田茂","よしだしげる"]],
            us_presidents: [["ワシントン","わしんとん"],["アダムズ","あだむず"],["ジェファーソン","じぇふぁーそん"],["マディソン","までぃそん"],["モンロー","もんろー"],["ジャクソン","じゃくそん"],["ヴァンビューレン","ばんびゅーれん"],["ハリソン","はりそん"],["タイラー","たいらー"],["ポーク","ぽーく"],["テイラー","ていらー"],["フィルモア","ふぃるもあ"],["ピアース","ぴあーす"],["ブキャナン","ぶきゃなん"],["リンカーン","りんかーん"],["ジョンソン","じょんそん"],["ぐらんと","ぐらんと"],["ヘイズ","へいず"],["ガーフィールド","がーふぃーるど"],["アーサー","あーさー"],["クリーブランド","くりーぶらんど"],["マッキンリー","まっきんりー"],["セオドアルーズベルト","せおどあるーずべると"],["ウィルソン","うぃるそん"],["フーバー","ふーばー"],["フランクリンルーズベルト","ふらんくりんるーずべると"],["トルーマン","とるーまん"],["ケネディ","けねでぃ"],["にくそん","にくそん"],["レーガン","れーがん"]],
            world_history_people: [["アレクサンダー","あれくさんだー"],["カエサル","かえさる"],["クレオパトラ","くれおぱとら"],["チンギスハン","ちんぎすはん"],["コロンブス","ころんぶす"],["レオナルドダヴィンチ","れおなるどだびんち"],["ミケランジェロ","みけらんじぇろ"],["るたー","るたー"],["ガリレオ","がりれお"],["ニュートン","にゅーとん"],["ルイ14世","るいじゅうよんせい"],["ナポレオン","なぽれおん"],["ビスマルク","びすまるく"],["ダーウィン","だーうぃん"],["ベートーヴェン","べーとーべん"],["モーツァルト","もーつぁると"],["あいんしゅたいん","あいんしゅたいん"],["ガンディー","がんでぃー"],["チャールズ1世","ちゃーるずいっせい"],["マリーアントワネット","まりーあんとわねっと"],["シャルルマーニュ","しゃるるまーにゅ"],["ジャンヌダルク","じゃんぬだるく"],["マゼラン","まぜらん"],["コペルニクス","こぺんにくす"],["エジソン","えじそん"],["ナイチンゲール","ないちんげーる"],["ノーベル","のーべる"],["ピカソ","ぴかそ"],["チャーチル","ちゃーちる"],["キュリー夫人","きゅりーふじん"]],
            famous_battles: [["関ヶ原の戦い","せきがはらのたたかい"],["川中島の戦い","かわなかじまのたたかい"],["桶狭間の戦い","おけはざまのたたかい"],["長篠の戦い","ながしののたたかい"],["壇ノ浦の戦い","だんのうらのたたかい"],["湊川の戦い","みなとがわのたたかい"],["一ノ谷の戦い","いちのたにのたたかい"],["屋島の戦い","やしまのたたかい"],["姉川の戦い","あねがわのたたかい"],["三方ヶ原の戦い","みかたがはらのたたかい"],["山崎の戦い","やまざきのたたかい"],["賤ヶ岳の戦い","しずがたけのたたかい"],["小牧長久手の戦い","こまきながくてのたたかい"],["大坂の陣","おおさかのじん"],["鳥羽伏見の戦い","とばふしみのにたたかい"],["戊辰戦争","ぼしんせんそう"],["西南戦争","せいなんせんそう"],["マラトンの戦い","まらとんのたたかい"],["カンナエの戦い","かんなえのたたかい"],["赤壁の戦い","せきへきのたたかい"],["ヘイスティングズの戦い","へいすてぃんぐすのたたかい"],["レパントの海戦","れぱんとのかいせん"],["アルマダの海戦","あるまだのかいせん"],["ワーテルローの戦い","わーてるろーのたたかい"],["トラファルガーの海戦","とらふぁるがーのかいせん"],["ゲティスバーグの戦い","げてぃすばーぐのたたかい"],["スターリングラードの戦い","すたーりんぐらーどのたたかい"],["ノルマンディー上陸作戦","のるまんでぃーじょうりくさくせん"],["ミッドウェー海戦","みっどうぇーかいせん"],["日露戦争","にちろせんそう"]],
            mythology_figures: [["ゼウス","ぜうす"],["ポセイドン","ぽせいどん"],["ハデス","はです"],["アポロン","あぽろん"],["アテナ","あてな"],["アフロディーテ","あふろでぃーて"],["へるめす","へるめす"],["アレス","あれす"],["ヘラクレス","へらくれす"],["オーディン","おーでぃん"],["トール","とーる"],["ロキ","ろき"],["ラー","らー"],["オシリス","おしりす"],["イシス","いしす"],["アヌビス","あぬびす"],["アマテラス","あまてらす"],["スサノオ","すさのお"],["ツクヨミ","つくよみ"],["イザナギ","いざなぎ"],["イザナミ","いざなみ"],["ギルガメッシュ","ぎるがめっしゅ"],["ラーマ","らーま"],["シヴァ","しば"],["ヴィシュヌ","びしゅぬ"],["ブラフマー","ぶらふまー"],["プロメテウス","ぷろめてうす"],["ペルセウス","ぺるせうす"],["アキレウス","あきれうす"],["オルフェウス","おるふぇうす"]],
            haiku: [["古池や蛙飛びこむ水の音","ふるいけやかわずとびこむみずのおと"],["閑さや岩にしみ入る蝉の声","しずけさやいわにしみいるせみのこえ"],["夏草や兵どもが夢の跡","なつくさやつわものどもがゆめのあと"],["柿くへば鐘が鳴るなり法隆寺","かきくえばかねがなるなりほうりゅうじ"],["荒海や佐渡によこたふ天の川","あらうみやさどによこたうあまのがわ"],["目には青葉山ホトトギス初鰹","めにはあおばやまほととぎすはつがつお"],["五月雨をあつめて早し最上川","さみだれをあつめてはやしもがみがわ"],["菜の花や月は東に日は西に","なのはなやつきはひがしにひはにしに"],["やせ蛙負けるな一茶これにあり","やせがえるまけるないっさこれにあり"],["朝顔に釣瓶とられてもらい水","あさ顔につるべとられてもらいみず"],["東風吹かばにほひおこせよ梅の花","こちふかばにおいおこせようめのはな"],["春の海ひねもすのたりのたりかな","はるのうみひねもすのたりのたりかな"],["名月をとられてしまふ泣子かな","めいげつをとられてしまうなきこかな"],["閑さや心にしみ入る秋の風","しずけさやこころにしみいるあきのかぜ"],["旅に病んで夢は枯野をかけ廻る","たびにやんでゆめはかれのをかけめぐる"],["梅一輪一輪ほどのあたたかさ","うめいちりんいちりんほどのあたたかさ"],["万緑の中や吾子の歯生えそむる","ばんりょくのなかやあこのははえそむる"],["桐一葉日落ちて天下の秋を知る","きりひとはひおちててんかのあきをしる"],["雀の子そこのけそこのけお馬が通る","すずめのこそこのけそこのけおうまがとおる"],["赤とんぼ筑バに雲もなかりけり","あかとんぼつくばにくももなかりけり"],["痩せ蛙負けるな一茶ここにあり","やせがえるまけるないっさここにあり"],["朝顔や一輪咲きて秋の風","あさ顔やいちりんさきてあきのかぜ"],["月天心貧しき町を通りけり","つきてんしんまずしきまちをとおりけり"],["涼しさや鐘を離るるかねの音","すずしさやかねをはなるるかねのおと"],["降る雪や明治は遠くなりにけり","ふるゆきやめいじはとおくなりにけり"],["春風や堤長うして家遠し","はるかぜやつつみながうしていえとおし"],["いくたびも雪の深さを尋ねけり","いくたびもゆきのふかさをたずねけり"],["牡丹散りて打ちかさなりぬ二三片","ぼたんちりてうちかさなりぬにさんぺん"],["渡り鳥空に描くは夢の道","わたりどりそらにえがくはゆめのみち"],["白菊の目に立てて見る塵もなし","しらぎくのめにたててみるちりもなし"]],
            hyakunin: [["秋の田のかりほの庵の苫をあらみ","あきのたのかりほのいおのとまをあらみ"],["春過ぎて夏来にけらし白妙の","はるすぎてなつきにけらししろたえの"],["足びきの山鳥の尾のしだり尾の","あしびきのやまどりののおのしだりおの"],["田子の浦に打出でてみれば白妙の","たごのうらにうちいでてみればしろたえの"],["奥山にモミジ踏み分け鳴く鹿の","おくやまにもみじふみ分けしかのこえの"],["かささぎの渡せる橋におく霜の","かささぎのわたせるはしにおくしもの"],["天の原ふりさけ見れば春日なる","あまのはらふりさけ見ればかすがなる"],["わが庵は都のたつみしかぞすむ","わがいおはみやこのたつみしかぞすむ"],["花の色はうつりにけりないたづらに","はなのいろはうつりにけりないたづらに"],["これやこの行くも帰るも分れては","これやこのゆくもかえるもわかれては"],["わたの原八十島かけて漕ぎ出でぬと","わたのはらやそしまかけてこぎいでぬと"],["天つ風雲の通ひ路吹き閉じよ","あまつかぜくものかよいじふきとじよ"],["筑波嶺の峰より落つるみなの川","つくばねのみねよりおつるみなのがわ"],["陸奥のしのぶもぢずり誰ゆゑに","みちのくのしのぶもぢずりたれゆえに"],["君がため春の野に出でて若菜つむ","きみがためはるののにいでてわかなつむ"],["立ち別れいなばの山の峰に生ふる","たちわかれいなばのやまのみねにおうる"],["ちはやぶる神代も聞かず竜田川","ちはやぶるかみよもきかずたつたがわ"],["すみの江の岸による波寄るしくも","すみのえのきしによるなみよるしくも"],["難波潟短きアシのふしのまも","なにわがたみじかきあしのふしのまも"],["わびぬれば今はた同じ難波なる","わびぬればいまはたおなじなにわなる"],["今来むといひしばかりに長月の","いまこむといひしばかりにながつきの"],["吹くからに秋の草木のしをるれば","ふくからにあきのくさきのしおるれば"],["月見ればちぢにものこそ悲しけれ","つきみればちぢにものこそかなしけれ"],["このたびは幣も取りあへず手向山","このたびはぬさもとりあえずたむけやま"],["名にし負はば逢坂山のさねかづら","なにしおわばおうさかやまのさねかづら"],["小倉山峰のモミジ葉心あらば","おぐらやまみねのもみじばこころあらば"],["みかの原わきて流れる泉川","みかのはらわきてながれるいずみがわ"],["山里は冬ぞさびしさまさりける","やまざとはふゆぞさびしさまさりける"],["心あてに折らばや折らむ初霜の","こころあてにおらばやおらむはつしもの"],["有明のつれなく見えし別れより","ありあけのつれなくみえし別れより"]],
            sumo: [["寄り切り","よりきり"],["押し出し","おしだし"],["突出し","つきだし"],["上手投げ","うわなげ"],["下手投げ","したなげ"],["小手投げ","こてなげ"],["掬い投げ","すくいなげ"],["首投げ","くびなげ"],["叩き込み","たたきこみ"],["引き落とし","ひきおとし"],["突き落とし","つきおとし"],["送り出し","おくりだし"],["寄り倒し","よりたおし"],["押し倒し","おしたおし"],["浴せ倒し","あびせたおし"],["内掛け","うちがけ"],["外掛け","そとがけ"],["切返し","きりかえし"],["ちょん掛け","ちょんがけ"],["渡し込み","わたしこみ"],["二本挿し","にほんざし"],["けたぐり","けたぐり"],["足取り","あしどり"],["上手ひねり","うわてひねり"],["下手ひねり","したてひねり"],["腕ひねり","かいなひねり"],["合掌ひねり","がっしょうひねり"],["裾払い","すそはらい"],["裾取り","すそどり"],["うっちゃり","うっちゃり"]],
            sushi: [["赤身","あかみ"],["中トロ","ちゅうとろ"],["大トロ","おおとろ"],["サーモン","さーもん"],["イクラ","いくら"],["ウニ","うに"],["アジ","あじ"],["サバ","さば"],["イワシ","いわし"],["エビ","えび"],["甘エビ","あまえび"],["イカ","いか"],["タコ","たこ"],["穴子","あなご"],["鰻","うなぎ"],["玉子","たまご"],["カッパ巻","かっぱまき"],["鉄火巻","てっかまき"],["ネギトロ","ねぎとろ"],["勘八","かんぱち"],["鯛","たい"],["平目","ひらめ"],["帆立","ほたて"],["赤貝","あかがい"],["つぶ貝","つぶがい"],["数の子","かずのこ"],["芽ねぎ","めねぎ"],["納豆巻","なっとうまき"],["かんぴょう巻","かんぴょうまき"],["太巻","ふとまき"]],
            japanese_food: [["寿司","すし"],["天ぷら","てんぷら"],["刺身","さしみ"],["蕎麦","そば"],["うどん","うどん"],["すき焼き","すきやき"],["しゃぶしゃぶ","しゃぶしゃぶ"],["焼き鳥","やきとり"],["鰻の蒲焼","うなぎのかばやき"],["納豆","なっとう"],["味噌汁","みそしる"],["豚汁","とんじる"],["お好み焼き","おこのみやき"],["たこ焼き","たこやき"],["茶碗蒸し","ちゃわんむし"],["煮物","にもの"],["卵焼き","たまごやき"],["筑前煮","ちくぜんに"],["肉じゃが","にくじゃが"],["焼き魚","やきざかな"],["竜田揚げ","たつたあげ"],["とんかつ","とんかつ"],["炊き込みご飯","たきこみごはん"],["おにぎり","おにぎり"],["湯豆腐","ゆどうふ"],["懐石料理","かいせきりょうり"],["おでん","おでん"],["関東煮","かんとうだき"],["親子丼","おやこどん"],["カツ丼","かつどん"]],
            chinese_food: [["餃子","ぎょうざ"],["炒飯","ちゃーはん"],["麻婆豆腐","まーぼーどうふ"],["小籠包","しょうろんぽう"],["焼売","しゅうまい"],["春巻き","はるまき"],["酢豚","すぶた"],["エビチリ","えびちり"],["青椒肉絲","ちんじゃおろーす"],["回鍋肉","ほいこーろー"],["担々麺","たんたんめん"],["杏仁豆腐","あんにんどうふ"],["ごま団子","ごまだんご"],["天津飯","てんしんはん"],["八宝菜","はっぽうさい"],["中華丼","ちゅうかどん"],["角煮","かくに"],["油淋鶏","ゆーりんちー"],["ワンタン","わんたん"],["北京ダック","ぺきんだっく"],["水餃子","すいぎょうざ"],["上海焼きそば","しゃんはいやきそば"],["酸辣湯","さんらーたん"],["棒棒鶏","ばんばんじー"],["ザーサイ","ざーさい"],["ピータン","ぴーたん"],["エビマヨ","えびまよ"],["蟹玉","かにたま"],["中華まん","ちゅうかまん"],["飲茶","やむちゃ"]],
            world_food: [["パスタ","ぱすた"],["ピザ","ぴざ"],["パエリア","ぱえりあ"],["タコス","たこす"],["カレー","かれー"],["トムヤムクン","とむやむくん"],["フォー","ふぉー"],["ステーキ","すてーき"],["ハンバーガー","はんばーがー"],["ボルシチ","ぼるしち"],["ガパオライス","がぱおらいす"],["ブイヤベース","ぶいやべーす"],["シュニッツェル","しゅにっつぇる"],["フィッシュアンドチップス","ふぃっしゅあんどちっぷす"],["ナシゴレン","なしごれん"],["サムギョプサル","さむぎょぷさる"],["参鶏湯","さむげたん"],["グラタン","ぐらたん"],["ラザニア","らざにあ"],["リゾット","りぞっと"],["ポトフ","ぽとふ"],["アヒージョ","あひーじょ"],["ケバブ","けばぶ"],["フェジョアーダ","ふぇじょあーだ"],["ロコモコ","ろこもこ"],["クラムチャウダー","くらむちゃうだー"],["むさか","むさか"],["クスクス","くすくす"],["シュラスコ","しゅらすこ"],["ビーフストロガノフ","びーふすとろがのふ"]],
            ramen_types: [["醤油ラーメン","しょうゆらーめん"],["味噌ラーメン","みそらーめん"],["塩ラーメン","しおらーめん"],["豚骨ラーメン","とんこつらーめん"],["豚骨醤油ラーメン","とんこつしょうゆらーめん"],["鶏白湯ラーメン","とりぱいたんらーめん"],["つけ麺","つけめん"],["油そば","あぶらそば"],["汁なし担々麺","しるなしたんたんめん"],["家系ラーメン","いえけいらーめん"],["二郎系ラーメン","じろうけいらーめん"],["札幌ラーメン","さっぽろらーめん"],["旭川ラーメン","あさひかわらーめん"],["函館ラーメン","はこだてらーめん"],["津軽ラーメン","つがるらーめん"],["酒田ラーメン","さかたらーめん"],["米沢ラーメン","よねざわらーめん"],["喜多方ラーメン","きたかたらーめん"],["佐野ラーメン","さのらーめん"],["八王子ラーメン","はちおうじらーめん"],["横浜家系","よこはまいえけい"],["富山ブラック","とやまぶらっく"],["敦賀ラーメン","つるがらーめん"],["高山ラーメン","たかやまらーめん"],["台湾ラーメン","たいわんらーめん"],["京都ラーメン","きょうとらーめん"],["和歌山ラーメン","わかやまらーめん"],["尾道ラーメン","おのみちらーめん"],["徳島ラーメン","とくしまらーめん"],["博多ラーメン","はかたらーめん"],["久留米ラーメン","くるめらーめん"],["熊本ラーメン","くまもとらーめん"]],
            sweets: [["ショートケーキ","しょーとけーき"],["プリン","ぷりん"],["シュークリーム","しゅーくりーむ"],["チーズケーキ","ちーずけーき"],["チョコレートケーキ","ちょこれーとけーき"],["タルト","たると"],["モンブラン","もんぶらん"],["ガトーショコラ","がとーしょこら"],["マカロン","まかろん"],["パフェ","ぱふぇ"],["アイスクリーム","あいすくりーむ"],["クレープ","くれーぷ"],["ドーナツ","どーなつ"],["パンケーキ","ぱんけーき"],["ワッフル","わっふる"],["ティラミス","てぃらみす"],["パンナコッタ","ぱんなこった"],["ナタデココ","なたでここ"],["カヌレ","かぬれ"],["フィナンシェ","ふぃなんしぇ"],["マドレーヌ","まどれーぬ"],["エクレア","えくれあ"],["シャルロット","しゃるろっと"],["羊羹","ようかん"],["どら焼き","どらやき"],["大福","だいふく"],["みたらし団子","みたらしだんご"],["鯛焼き","たいやき"],["カステラ","かすてら"],["かき氷","かきごおり"]],
            vegetables: [["トマト","とまと"],["大根","だいこん"],["キャベツ","きゃべつ"],["人参","にんじん"],["玉ねぎ","たまねぎ"],["茄子","なす"],["胡瓜","きゅうり"],["白菜","はくさい"],["ほうれん草","ほうれんそう"],["ブロッコリー","ぶろっこりー"],["レタス","れたす"],["ピーマン","ぴーまん"],["じゃがいも","じゃがいも"],["さつまいも","さつまいも"],["里芋","さといも"],["ごぼう","ごぼう"],["れんこん","れんこん"],["ねぎ","ねぎ"],["ニラ","にら"],["もやし","もやし"],["カリフラワー","かりふらわー"],["アスパラガス","あすぱらがす"],["オクラ","おくら"],["かぼちゃ","かぼちゃ"],["小松菜","こまつな"],["チンゲン菜","ちんげんさい"],["セロリ","せろり"],["パプリカ","ぱぷりか"],["ズッキーニ","ずっきーに"],["枝豆","えだまめ"]],
            fruits: [["林檎","りんご"],["苺","いちご"],["蜜柑","みかん"],["葡萄","ぶどう"],["桃","もも"],["西瓜","すいか"],["梨","なし"],["柿","かき"],["バナナ","ばなな"],["パイナップル","ぱいなっぷる"],["メロン","めろん"],["キウイ","きうい"],["レモン","れもん"],["桜桃","さくらんぼ"],["柚子","ゆず"],["栗","くり"],["無花果","いちじく"],["枇杷","びわ"],["マンゴー","まんごー"],["パパイヤ","ぱぱいや"],["アボカド","あぼかど"],["ブルーベリー","ぶるーべりー"],["ラズベリー","らずべりー"],["マスカット","ますかっと"],["ライチ","らいち"],["ドラゴンフルーツ","どらごんふるーつ"],["パッションフルーツ","ぱっしょんふるーつ"],["ザクロ","ざくろ"],["すもも","すもも"],["金柑","きんかん"]],
            tea_types: [["煎茶","せんちゃ"],["玉露","ぎょくろ"],["抹茶","まっちゃ"],["ほうじ茶","ほうじちゃ"],["玄米茶","げんまいちゃ"],["番茶","ばんちゃ"],["茎茶","くきちゃ"],["芽茶","めちゃ"],["粉茶","こなちゃ"],["烏龍茶","うーろんちゃ"],["ジャスミン茶","じゃすみんちゃ"],["ダージリン","だーじりん"],["アッサム","あっさむ"],["セイロン","せいろん"],["アールグレイ","あーるぐれい"],["ルイボスティー","るいぼすてぃー"],["カモミールティー","かもみーるてぃー"],["ペパーミントティー","ぺぱーみんとてぃー"],["ローズヒップティー","ろーずひっぷてぃー"],["ハイビスカスティー","はいびすかすてぃー"],["黒豆茶","くろまめちゃ"],["麦茶","むぎちゃ"],["普洱茶","ぷーあるちゃ"],["鉄観音","てっかんのん"],["白茶","はくちゃ"],["黄茶","きちゃ"],["杜仲茶","とちゅうちゃ"],["ごぼう茶","ごぼうちゃ"],["なたまめ茶","なたまめちゃ"],["よもぎ茶","よもぎちゃ"],["さんぴん茶","さんぴんちゃ"],["甜茶","てんちゃ"]],
            cheese_types: [["チェダー","ちぇだー"],["モッツァレラ","もっつぁれら"],["カマンベール","かまんべーる"],["ゴーダ","ごーだ"],["パルミジャーノ","ぱるみじゃーの"],["ゴルゴンゾーラ","ごるごんぞーら"],["ロックフォール","ろっくふぉーる"],["スティルトン","すてぃるとん"],["ブリー","ぶりー"],["エメンタール","えめんたーる"],["グリュイエール","ぐりゅいえーる"],["マスカルポーネ","ますかるぽーね"],["リコッタ","りこった"],["クリームチーズ","くりーむちーず"],["プロヴォローネ","ぷろぼろーね"],["フェタ","ふぇた"],["カチョカヴァッロ","かちょかばっろ"],["ラクレット","らくれっと"],["コンテ","こんて"],["ミモレット","みもれっと"],["スモークチーズ","すもーくちーず"],["ペコリーノ","ぺこりーの"],["マンチェゴ","まんちぇご"],["ハルーミ","はるーみ"],["ベルパエーゼ","べるぱえーぜ"],["アジアーゴ","あじあーご"],["タルレッジョ","たるれっじょ"],["ハヴァティ","はばてぃ"],["サンタンドレ","さんたんどれ"],["ヴァランセ","ばらんせ"],["シュヴル","しゅぶる"],["プロセスチーズ","ぷろせすちーず"]],
            
            animals: [["ライオン","らいおん"],["パンダ","ぱんだ"],["象","ぞう"],["麒麟","きりん"],["縞馬","しまうま"],["河馬","かば"],["犀","さい"],["虎","とら"],["豹","ひょう"],["熊","くま"],["狐","きつね"],["狸","たぬき"],["狼","おおかみ"],["鹿","しか"],["猿","さる"],["ゴリラ","ごりら"],["チンパンジー","ちんぱんじー"],["カンガルー","かんがるー"],["コアラ","こあら"],["ラクダ","らくだ"],["栗鼠","りす"],["獺","かわうそ"],["ビーバー","びーばー"],["カピバラ","かぴばら"],["アザラシ","あざらし"],["アシカ","あしか"],["セイウチ","せいうち"],["クジラ","くじら"],["イルカ","いるか"],["シャチ","しゃち"]],
            dog_breeds: [["柴犬","しばいぬ"],["トイプードル","といぷーどる"],["チワワ","ちわわ"],["ミニチュアダックスフンド","みにちゅあだっくすふんど"],["ポメラニアン","ぽめらにあん"],["フレンチブルドッグ","ふれんちぶるどっぐ"],["ヨークシャーテリア","よーくしゃーてりあ"],["シーズー","しーずー"],["マルチーズ","まるちーず"],["パグ","ぱぐ"],["ゴールデンレトリバー","ごーるでんれとりばー"],["ラブラドールレトリバー","らぶらどーるれとりばー"],["秋田犬","あきたいぬ"],["紀州犬","きしゅういぬ"],["甲斐犬","かいけん"],["ボーダーコリー","ぼーだーこりー"],["コーギー","こーぎー"],["ビーグル","びーぐる"],["ドーベルマン","どーべるまん"],["シェパード","しぇぱーど"],["シベリアンハスキー","しべりあんはすきー"],["ボルゾイ","ぼるぞい"],["セントバーナード","せんとばーなーど"],["ダルメシアン","だるめしあん"],["チャウチャウ","ちゃうちゃう"],["パピヨン","ぱぴよん"],["キャバリア","きゃばりあ"],["ボストンテリア","ぼすとんてりあ"],["シュナウザー","しゅなうざー"],["ブルドッグ","ぶるどっぐ"]],
            cat_breeds: [["アメリカンショートヘア","あめりかんしょーとへあ"],["マンチカン","まんちかん"],["スコティッシュフォールド","すこてぃっしゅふぉーるど"],["ラグドール","らぐどーる"],["ペルシャ","ぺるしゃ"],["メインクーン","めいんくーん"],["ロシアンブルー","ろしあんぶるー"],["ベンガル","べんがる"],["ソマリ","そまり"],["アビシニアン","あびしにあん"],["ノルウェージャンフォレストキャット","のるうぇーじゃんふぉれすときゃっと"],["サイベリアン","さいべりあん"],["エキゾチックショートヘア","えきぞちっくしょーとへあ"],["ブリティッシュショートヘア","ぶりてぃっしゅしょーとへあ"],["シャム","しゃむ"],["シンガプーラ","しんがぽーる"],["トンキニーズ","とんきにーず"],["ヒマラヤン","ひまらやん"],["エジプシャンマウ","えじぷしゃんまう"],["オシキャット","おしかっと"],["オリエンタル","おりえんたる"],["セルカークレックス","せるかーくれっくす"],["ターキッシュアンゴラ","たーきっしゅあんごら"],["ターキッシュバン","たーきっしゅばん"],["デボンレックス","でぼんれっくす"],["バーマン","ばーまん"],["バーミーズ","ばーみーず"],["ハバナブラウン","はばなぶらうん"],["ピクシーボブ","ぴくしーぼぶ"],["スフィンクス","すふぃんくす"]],
            birds: [["雀","すずめ"],["烏","からす"],["鳩","はと"],["燕","つばめ"],["鴬","うぐいす"],["雉","きじ"],["鴨","かも"],["鷺","さぎ"],["鷲","わし"],["鷹","たか"],["梟","ふくろう"],["鴎","かもめ"],["鵜","う"],["白鳥","はくちょう"],["鶴","つる"],["孔雀","くじゃく"],["鸚鵡","おうむ"],["文鳥","ぶんちょう"],["十姉妹","じゅうしまつ"],["啄木鳥","きつつき"],["翡翠","かわせみ"],["鶺鴒","せきれい"],["百舌","もず"],["鶫","つぐみ"],["椋鳥","むくどり"],["家鴨","あひる"],["軍鶏","しゃも"],["鶉","うずら"],["鸛","こうのとり"],["ペンギン","ぺんぎん"]],
            insects: [["カブトムシ","かぶとむし"],["クワガタムシ","くわがたむし"],["テントウムシ","てんとうむし"],["バッタ","ばった"],["カマキリ","かまきり"],["セミ","せみ"],["トンボ","とんぼ"],["チョウ","ちょう"],["ガ","が"],["ハチ","はち"],["アリ","あり"],["ホタル","ほたる"],["コオロギ","こおろぎ"],["スズムシ","すずむし"],["マツムシ","まつむし"],["キリギリス","きりぎりす"],["タガメ","たがめ"],["ミズカマキリ","みずかまきり"],["ゲンゴロウ","げんごろう"],["アメンボ","あめんぼ"],["カゲロウ","かげろう"],["ゾウムシ","ぞうむし"],["ハンミョウ","はんみょう"],["ナナフシ","ななふし"],["カメムシ","かめむし"],["ハサミムシ","はさみむし"],["ギフチョウ","ぎふちょう"],["アゲハチョウ","あげはちょう"],["モンシロチョウ","もんしろちょう"],["オニヤンマ","おにやんま"]],
            ocean_fish: [["マグロ","まぐろ"],["サケ","さけ"],["ブリ","ぶり"],["サバ","さば"],["アジ","あじ"],["イワシ","いわし"],["サンマ","さんま"],["タイ","たい"],["ヒラメ","ひらめ"],["カレイ","かれい"],["カツオ","かつお"],["フグ","ふぐ"],["スズキ","すずき"],["タラ","たら"],["ニシン","にしん"],["トビウオ","とびうお"],["タチウオ","たちうお"],["カジキ","かじき"],["アンコウ","あんこう"],["クエ","くえ"],["ハマチ","はまち"],["サワラ","さわら"],["アイナメ","あいなめ"],["カワハギ","かわはぎ"],["メバル","めばる"],["カサゴ","かさご"],["ボラ","ぼら"],["イサキ","いさき"],["キス","きす"],["シイラ","しいら"]],
            river_fish: [["アユ","あゆ"],["ヤマメ","やまめ"],["イワナ","いわな"],["ニジマス","にじます"],["アマゴ","あまご"],["ウナギ","うなぎ"],["コイ","こい"],["フナ","ふな"],["メダカ","めだか"],["ドジョウ","どじょう"],["ナマズ","なまず"],["ライギョ","らいぎょ"],["おいかわ","おいかわ"],["ウグイ","うぐい"],["かわむつ","かわむつ"],["タナゴ","たなご"],["ハゼ","はぜ"],["カジカ","かじか"],["イトウ","いとう"],["サツキマス","さつきます"],["いとよ","いとよ"],["ハス","はす"],["もつご","もつご"],["ワカサギ","わかさぎ"],["かわあなご","かわあなご"],["ぎぎ","ぎぎ"],["どんこ","どんこ"],["あかざ","あかざ"],["あゆかけ","あゆかけ"],["ビワマス","びわます"]],
            dinosaurs: [["ティラノサウルス","てぃらのさうるす"],["トリケラトプス","とりけらとぷす"],["ステゴサウルス","すてごさうるす"],["ブラキオサウルス","ぶらきおさうるす"],["ヴェロキラプトル","べろきらぷとる"],["プテラノドン","ぷてらのどん"],["アンキロサウルス","あんきろさうるす"],["スピノサウルス","すぴのさうるす"],["アロサウルス","あろさうるす"],["パキケファロサウルス","ぱきけふぁろさうるす"],["イグアノドン","いぐあのどん"],["ディプロドクス","でぃぷろどくす"],["パラサウロロフス","ぱらさうろろふす"],["プレシオサウルス","ぷれしおさうるす"],["モササウルス","もささうるす"],["アルゼンチノサウルス","あるぜんちのさうるす"],["カルノタウルス","かるのたうるす"],["ぎがのたうるす","ぎがのたうるす"],["デイノニクス","でいのにくす"],["コンプソグナトゥス","こんぷそぐなとぅす"],["オビラプトル","おびらぷとる"],["マイアサウラ","まいあさうら"],["スティラコサウルス","すてぃらこさうるす"],["プロトケラトプス","ぷろとけらとぷす"],["テリジノサウルス","てりじのさうるす"],["どりおさうるす","どりおさうるす"],["ガリミムス","がりみむす"],["トロオドン","とろおどん"],["エラスモサウルス","えらすもさうるす"],["あんはんぐえら","あんはんぐえら"]],
            flowers: [["桜","さくら"],["向日葵","ひまわり"],["朝顔","あさ顔"],["紫陽花","あじさい"],["蒲公英","たんぽぽ"],["鬱金香","ちゅーりっぷ"],["薔薇","ばら"],["百合","ゆり"],["菊","きく"],["椿","つばき"],["梅","うめ"],["牡丹","ぼたん"],["芍薬","しゃくやく"],["竜胆","りんどう"],["桔梗","ききょう"],["撫子","なでしこ"],["蓮","はす"],["菖蒲","あやめ"],["菫","すみれ"],["桜草","さくらそう"],["雛菊","ひなぎく"],["秋桜","こすもす"],["彼岸花","ひがんばな"],["鈴蘭","すずらん"],["水仙","すいせん"],["茉莉花","じゃすみん"],["カーネーション","かーねーしょん"],["アネモネ","あねもね"],["フリージア","ふりーじあ"],["ガーベラ","がーべら"]],
            trees: [["杉","すぎ"],["松","まつ"],["檜","ひのき"],["欅","けやき"],["桜","さくら"],["楓","かえで"],["銀杏","いちょう"],["楠","くすのき"],["樫","かし"],["楢","なら"],["椈","ぶな"],["柳","やなぎ"],["桐","きり"],["桑","くわ"],["椿","つばき"],["柿","かき"],["栗","くり"],["桃","もも"],["梅","うめ"],["蜜柑","みかん"],["白樺","しらかば"],["槐","えんじゅ"],["桂","かつら"],["槇","まき"],["樅","もみ"],["栂","つが"],["椹","さわら"],["蘇鉄","そてつ"],["蘇芳","すおう"],["竹","たけ"]],
            cloud_types: [["巻雲","けんうん"],["巻積雲","けんせきうん"],["巻層雲","けんそううん"],["高積雲","こうせきうん"],["高層雲","こうそううん"],["乱層雲","らんそううん"],["層積雲","そうせきうん"],["層雲","そううん"],["積雲","せきうん"],["積乱雲","せきらんうん"],["すじ雲","すじぐも"],["うろこ雲","うろこぐも"],["いわし雲","いわしぐも"],["ひつじ雲","ひつじぐも"],["おぼろ雲","おぼろぐも"],["雨雲","あまぐも"],["わた雲","わたぐも"],["入道雲","にゅうどうぐも"],["笠雲","かさぐも"],["つるし雲","つるしぐも"],["飛行機雲","ひこうきぐも"],["彩雲","さいうん"],["蜂の巣状雲","はちのすじょううん"],["レンズ雲","れんずぐも"],["かなとこ雲","かなとこぐも"],["漏斗雲","ろうとぐも"],["尾流雲","びりゅううん"],["肋骨状雲","ろっこつじょううん"],["乳房雲","ちぶさぐも"],["霧雲","きりぐも"],["茜雲","あかねぐも"],["雲海","うんかい"]],
            body_parts: [["頭","あたま"],["目","め"],["耳","みみ"],["鼻","はな"],["口","くち"],["歯","は"],["舌","した"],["首","くび"],["肩","かた"],["胸","むね"],["背中","せなか"],["腹","はら"],["腰","こし"],["腕","うで"],["肘","ひじ"],["手首","てくび"],["手","て"],["指","ゆび"],["爪","つめ"],["太もも","ふともも"],["膝","ひざ"],["脛","すね"],["ふくらはぎ","ふくらはぎ"],["足首","あしくび"],["足","あし"],["踵","かかと"],["足の指","あしのゆび"],["額","ひたい"],["頬","ほほ"],["顎","あご"]],
            body_organs: [["心臓","しんぞう"],["肺","はい"],["胃","い"],["小腸","しょうちょう"],["大腸","だいちょう"],["肝臓","かんぞう"],["腎臓","じんぞう"],["膵臓","すいぞう"],["胆嚢","たんのう"],["脾臓","ひぞう"],["脳","のう"],["大脳","だいのう"],["小脳","しょうのう"],["脳幹","のうかん"],["食道","しょくどう"],["気管","きかん"],["膀胱","ぼうこう"],["血管","けっかん"],["動脈","どうみゃく"],["静脈","じょうみゃく"],["毛細血管","もうさいけっかん"],["筋肉","きんにく"],["骨","ほね"],["関節","かんせつ"],["靭帯","じんたい"],["神経","しんけい"],["骨髄","こつずい"],["甲状腺","こうじょうせん"],["リンパ節","りんぱせつ"],["網膜","もうまく"]],
            human_bones: [["頭蓋骨","ずがいこつ"],["鎖骨","さこつ"],["肩甲骨","けんこうこつ"],["胸骨","きょうこつ"],["肋骨","ろっこつ"],["脊椎","せきつい"],["頸椎","けいつい"],["胸椎","きょうつい"],["腰椎","ようつい"],["仙骨","せんこつ"],["尾骨","びこつ"],["骨盤","こつばん"],["腸骨","ちょうこつ"],["恥骨","ちこつ"],["坐骨","ざこつ"],["上腕骨","じょうわんこつ"],["橈骨","とうこつ"],["尺骨","しゃっこつ"],["手根骨","しゅこんこつ"],["中手骨","ちゅうしゅこつ"],["指骨","しこつ"],["大腿骨","だいたいこつ"],["膝蓋骨","しつがいこつ"],["脛骨","けいこつ"],["腓骨","ひこつ"],["足根骨","そくこんこつ"],["踵骨","しょうこつ"],["距骨","きょこつ"],["中足骨","ちゅうそくこつ"],["趾骨","しこつ"]],
            diseases: [["風邪","かぜ"],["インフルエンザ","いんふるえんざ"],["肺炎","はいえん"],["喘息","ぜんそく"],["貧血","ひんけつ"],["糖尿病","とうにょうびょう"],["高血圧","こうけつあつ"],["胃炎","いえん"],["腸炎","ちょうえん"],["肝炎","かんえん"],["胆石症","たんせきしょう"],["痛風","つうふう"],["骨折","こっせつ"],["捻挫","ねんざ"],["脱臼","だっきゅう"],["虫垂炎","ちゅうすいえん"],["白内障","はくないしょう"],["緑内障","りょくないしょう"],["中耳炎","ちゅうじえん"],["鼻炎","びえん"],["花粉症","かふんしょう"],["蕁麻疹","じんましん"],["アトピー","あとぴー"],["偏頭痛","へんずつう"],["脳梗塞","のうこうそく"],["心筋梗塞","しんきんこうそく"],["不整脈","ふせいみゃく"],["腎臓病","じんぞうびょう"],["熱中症","ねっちゅうしょう"],["脱水症状","だっすいしょうじょう"]],
            elements: [["水素","すいそ"],["ヘリウム","へりうむ"],["リチウム","りちうむ"],["ベリリウム","べりりうむ"],["ホウ素","ほうそ"],["炭素","たんそ"],["窒素","ちっそ"],["酸素","さんそ"],["フッ素","ふっそ"],["ネオン","ねおん"],["ナトリウム","なとりうむ"],["マグネシウム","まぐねしうむ"],["アルミニウム","あるみにうむ"],["ケイ素","けいそ"],["リン","りん"],["硫黄","いおう"],["塩素","えんそ"],["アルゴン","あるごん"],["カリウム","かりうむ"],["カルシウム","かるしうむ"],["鉄","てつ"],["銅","どう"],["亜鉛","あえん"],["銀","ぎん"],["金","きん"],["鉛","なまり"],["水銀","すいぎん"],["ウラン","うらん"],["チタン","ちたん"],["ニッケル","にっける"]],
            kanto_trains: [["山手線","やまのてせん"],["京浜東北線","けいひんとうほくせん"],["中央線","ちゅうおうせん"],["総武線","そうぶせん"],["常磐線","じょうばんせん"],["東海道線","とうかいどうせん"],["横須賀線","よこすかせん"],["高崎線","たかさきせん"],["宇都宮線","うつのみやせん"],["武蔵野線","むさしのせん"],["南武線","なんぶせん"],["横浜線","よこはません"],["京葉線","けいようせん"],["埼京線","さいきょうせん"],["湘南新宿ライン","しょうなんしんじゅくらいん"],["上野東京ライン","うえのとうきょうらいん"],["銀座線","ぎんざせん"],["丸ノ内線","まるのうちせん"],["日比谷線","ひびやせん"],["東西線","とうざいせん"],["千代田線","ちよだせん"],["有楽町線","ゆうらくちょうせん"],["半蔵門線","はんぞうもんせん"],["南北線","なんぼくせん"],["副都心線","ふくとしんせん"],["都営浅草線","とえいあさくさせん"],["都営三田線","とえいみたせん"],["都営新宿線","とえいしんじゅくせん"],["都営大江戸線","とえいおおえどせん"],["つくばエクスプレス","つくばえくすぷれす"]],
            car_models: [["プリウス","ぷりうす"],["アクア","あくあ"],["ヤリス","やりす"],["シエンタ","しえんた"],["カローラ","かろーら"],["クラウン","くらうん"],["アルファード","あるふぁーど"],["ヴェルファイア","べるふぁいあ"],["ヴォクシー","ぼくしー"],["ノア","のあ"],["ハリアー","はりあー"],["ランドクルーザー","らんどくるーざー"],["ハイエース","はいえーす"],["フィット","ふぃっと"],["ヴェゼル","べぜる"],["フリード","ふりーど"],["ステップワゴン","すてっぷわごん"],["シビック","しびっく"],["ノート","のーと"],["せれな","せれな"],["エクストレイル","えくすとれいる"],["デリカ","でりか"],["アウトランダー","あうとらんだー"],["ロードスター","ろーどすたー"],["インプレッサ","いんぷれっさ"],["フォレスター","ふぉれすたー"],["ジムニー","じむにー"],["スイフト","すいふと"],["タント","たんと"],["キャンバス","きゃんばす"]],
            sports_names: [["サッカー","さっかー"],["野球","やきゅう"],["バスケットボール","ばすけっとぼーる"],["テニス","てにす"],["バレーボール","ばれーぼーる"],["卓球","たっきゅう"],["バドミントン","ばどみんとん"],["水泳","すいえい"],["陸上競技","りくじょうきょうぎ"],["体操","たいそう"],["柔道","じゅうどう"],["剣道","けんどう"],["空手","からて"],["弓道","きゅうどう"],["相撲","すもう"],["ゴルフ","ごるふ"],["ラグビー","らぐびー"],["アメリカンフットボール","あめりかんふっとぼーる"],["アイスホッケー","あいすほっけー"],["スケート","すけーと"],["スキー","すきー"],["スノーボード","すのーぼーど"],["ボクシング","ぼくしんぐ"],["レスリング","れすりんぐ"],["フェンシング","ふぇんしんぐ"],["アーチェリー","あーちぇりー"],["サーフィン","さーふぃん"],["スケートボード","すけーとぼーど"],["クライミング","くらいみんぐ"],["トライアスロン","とらいあすろん"]],
            sports_equipment: [["サッカーボール","さっかーぼーる"],["野球ボール","やきゅうぼーる"],["バット","ばっと"],["グローブ","ぐろーぶ"],["プロテクター","ぷろてくたー"],["テニスラケット","てにすらけっと"],["卓球ラケット","たっきゅうらけっと"],["バドミントンラケット","ばどみんとんらけっと"],["シャトル","しゃとる"],["バスケットボール","ばすけっとぼーる"],["バレーボール","ばれーぼーる"],["ネット","ねっと"],["ゴールネット","ごーるねっと"],["ゼッケン","ぜっけん"],["スパイク","すぱいく"],["陸上シューズ","りくじょうしゅーず"],["水着","みずぎ"],["ゴーグル","ごーぐる"],["水泳帽","すいえいぼう"],["竹刀","しない"],["防具","ぼうぐ"],["柔道着","じゅうどうぎ"],["ゴルフクラブ","ごるふくらぶ"],["ゴルフボール","ごるふぼーる"],["ラグビーボール","らぐびーぼーる"],["ヘルメット","へるめっと"],["スキー板","すきーいた"],["ストック","すとっく"],["スノーボード","すのーぼーど"],["ホッケースティック","ほっけーすてぃっく"]],
            musicians: [["ベートーヴェン","べーとーべん"],["モーツァルト","もーつぁると"],["バッハ","ばっは"],["シューベルト","しゅーべると"],["ショパン","しょぱん"],["チャイコフスキー","ちゃいこふすきー"],["ワーグナー","わーぐなー"],["ヴェルディ","ゔぇるでぃ"],["ブラームス","ぶらーむす"],["リスト","りすと"],["ハイドン","はいどん"],["ヘンデル","へんでる"],["ヴィヴァルディ","ゔぃゔぁるでぃ"],["ドビュッシー","どびゅっしー"],["ラヴェル","らゔぇる"],["メンデルスゾーン","めんでるすぞーん"],["サンサーンス","さんさーんす"],["ドヴォルザーク","どゔぉるざーく"],["マーラー","まーらー"],["ストラヴィンスキー","すとらゔぃんすきー"],["プロコフィエフ","ぷろこふぃえふ"],["ショスタコーヴィチ","しょすたこーゔぃち"],["ガーシュウィン","がーしゅうぃん"],["滝廉太郎","たきれんたろう"],["山田耕筰","やまだこうさく"],["中田喜直","なかだよしなお"],["武満徹","たけみつとおる"],["久石譲","ひさいしじょう"],["坂本龍一","さかもとりゅういち"],["葉加瀬太郎","はかせたろう"]],
            shogi_terms: [["王将","おうしょう"],["玉将","ぎょくしょう"],["飛車","ひしゃ"],["角行","かくぎょう"],["金将","きんしょう"],["銀将","ぎんしょう"],["桂馬","けいま"],["香車","きょうしゃ"],["歩兵","ふひょう"],["龍王","りゅうおう"],["龍馬","りゅうま"],["成銀","なりぎん"],["成桂","なりけい"],["成香","なりきょう"],["と金","ときん"],["王手","おうて"],["詰み","つみ"],["成り","なり"],["千日手","せんにちて"],["入玉","にゅうぎょく"],["詰将棋","つみしょうぎ"],["矢倉囲い","やぐらがこい"],["美濃囲い","みのがこい"],["穴熊囲い","あなぐまがこい"],["居飛車","いびしゃ"],["振り飛車","ふりびしゃ"],["四間飛車","しけんびしゃ"],["投了","とうりょう"],["封じ手","ふうじて"],["合駒","あいごま"]],
            toys: [["積み木","つみき"],["ぬいぐるみ","ぬいぐるみ"],["ミニカー","みにかー"],["おままごと","おままごと"],["粘土","ねんど"],["折り紙","おりがみ"],["けん玉","けんだま"],["おはじき","おはじき"],["竹トンボ","たけとんぼ"],["コマ","こま"],["ヨーヨー","よーよー"],["フラフープ","ふらふーぷ"],["水鉄砲","みずでっぽう"],["シャボン玉","しゃぼんだま"],["凧","たこ"],["トランプ","とらんぷ"],["カルタ","かるた"],["パズル","ぱずる"],["ルービックキューブ","るーびっくきゅーぶ"],["ボードゲーム","ぼーどげーむ"],["プラモデル","ぷらもでる"],["フィギュア","ふぃぎゅあ"],["ラジコン","らじこん"],["スライム","すらいむ"],["ビー玉","びーだま"],["万華鏡","まんげきょう"],["風船","ふうせん"],["だるま落とし","だるまおとし"],["輪投げ","わなげ"],["ガチャガチャ","がちゃがちゃ"]],
            professions: [["医師","いしゃ"],["看護師","かんごし"],["薬剤師","やくざいし"],["警察官","けいさつかん"],["消防士","しょうぼうし"],["パイロット","ぱいろっと"],["客室乗務員","きゃくしつじょうむいん"],["電車運転士","でんしゃうんてんし"],["保育士","ほいくし"],["教師","きょうし"],["料理人","りょうりにん"],["パティシエ","ぱてぃしえ"],["美容師","びようし"],["理容師","りようし"],["花屋","はなや"],["宇宙飛行士","うちゅうひこうし"],["弁護士","べんごし"],["裁判官","さいばんかん"],["政治家","せいじか"],["漫画家","まんがか"],["声優","せいゆう"],["歌手","かしゅ"],["俳優","はいゆう"],["プロゲーマー","ぷろげーまー"],["建築士","けんちくし"],["大工","だいく"],["農家","のうか"],["漁師","りょうし"],["翻訳家","ほんやくか"],["銀行員","ぎんこういん"]],
            pc_terms: [["キーボード","きーぼーど"],["マウス","まうす"],["モニター","もにたー"],["ディスプレイ","でぃすぷれい"],["プリンター","ぷりんたー"],["スキャナー","すきゃなー"],["ハードディスク","はーどでぃすく"],["メモリ","めもり"],["プロセッサー","ぷろせっさー"],["マザーボード","まざーぼーど"],["電源ユニット","でんげんゆにっと"],["ノートパソコン","のーとぱそこん"],["デスクトップ","ですくとっぷ"],["タッチパッド","たっちぱっど"],["画面","がめん"],["フォルダ","ふぉるだ"],["ファイル","ふぁいる"],["カーソル","かーそる"],["クリック","くりっく"],["ダブルクリック","だぶるくりっく"],["ドラッグ","どらっぐ"],["ドロップ","どろっぷ"],["コピー","こぴー"],["ペースト","ぺーすと"],["カット","かっと"],["保存","ほぞん"],["削除","さくじょ"],["検索","けんさく"],["ブラウザ","ぶらうざ"],["ショートカット","しょーとかっと"]],
            it: [["インターネット","いんたーねっと"],["プログラミング","ぷろぐらみんぐ"],["ソフトウェア","そふとうぇあ"],["ハードウェア","はーどうぇあ"],["アルゴリズム","あるごりずむ"],["データベース","でーたべーす"],["ネットワーク","ねっとわーく"],["クラウド","くらうど"],["アプリケーション","あぷりけーしょん"],["セキュリティ","せきゅりてぃ"],["パスワード","ぱすわーど"],["アカウント","あかうんと"],["サーバー","さーばー"],["クライアント","くらいあんと"],["ダウンロード","だうんろーど"],["アップロード","あっぷろーど"],["インストール","いんすとーる"],["アンインストール","あんいんすとーる"],["アップデート","あっぷでーと"],["バックアップ","ばっくあっぷ"],["システム","しすてむ"],["エンジニア","えんじにあ"],["コーディング","こーでぃんぐ"],["バグ","ばぐ"],["デバッグ","でばっぐ"],["AI","えーあい"],["ロボット","ろぼっと"],["デジタル","でじたる"],["アナログ","あなろぐ"],["ドメイン","どめいん"]],
            household_items: [["冷蔵庫","れいぞうこ"],["洗濯機","せんたくき"],["掃除機","そうじき"],["電子レンジ","でんしれんじ"],["炊飯器","すいはんき"],["テレビ","てれび"],["エアコン","えあこん"],["扇風機","せんぷうき"],["空気清浄機","くうきせいじょうき"],["ドライヤー","どらいやー"],["食卓","しょくたく"],["テーブル","てーぶる"],["ソファー","そふぁー"],["ベッド","べっど"],["布団","ふとん"],["枕","まくら"],["鏡","かがみ"],["時計","とけい"],["カーテン","かーてん"],["じゅうたん","じゅうたん"],["歯ブラシ","はぶらし"],["タオル","たおる"],["石鹸","せっけん"],["シャンプー","しゃんぷー"],["箸","はし"],["スプーン","すぷーん"],["フォーク","ふぉーく"],["お椀","おわん"],["コップ","こっぷ"],["鍋","なべ"]],
            
            idioms: [["猫の手も借りたい","ねこのてもかりたい"],["喉から手が出る","のどからてがでる"],["頭が下がる","あたまがさがる"],["足を引っ張る","あしをひっぱる"],["腹が立つ","はらがたつ"],["目がない","めがない"],["耳を疑う","みみをうたがう"],["口が硬い","くちがかたい"],["口が軽い","くちがかるい"],["手を焼く","てをやく"],["鼻が高い","はながたかい"],["釘を刺す","くぎをさす"],["胸を張る","むねをはる"],["肩を落とす","かたをおとす"],["眉をひそめる","まゆをひそめる"],["顔が広い","かおがひろい"],["腹を割る","はらをわる"],["身を粉にする","みをこなにする"],["手に汗を握る","てニアせをにぎる"],["骨を折る","ほねをおる"],["舌を巻く","したをまく"],["腹を括る","はらをくくる"],["腰を抜かす","こしをぬかす"],["尻を叩く","しりをたたく"],["匙を投げる","さじをなげる"],["油を売る","あぶらをうる"],["胡麻をする","ごまする"],["水に流す","みずにながす"],["太鼓判を押す","たいこばんをおす"],["一目を置く","いちもくをおく"]],
            greetings: [
                ["おはようございます","おはようございます"],["こんにちは","こんにちは"],["こんばんは","こんばんは"],["おやすみなさい","おやすみなさい"],
                ["ありがとうございます","ありがとうございます"],["どういたしまして","どういたしまして"],["すみません","すみません"],["ごめんなさい","ごめんなさい"],
                ["いただきます","いただきます"],["ごちそうさまでした","ごちそうさまでした"],["いってきます","いってきます"],["いってらっしゃい","いってらっしゃい"],
                ["ただいま","ただいま"],["おかえりなさい","おかえりなさい"],["はじめまして","はじめまして"],["よろしくお願いします","よろしくおねがいします"],
                ["お元気ですか","おげんきですか"],["さようなら","さようなら"],["またね","またね"],["お疲れ様です","おつかれさまです"],
                ["おめでとうございます","おめでとうございます"],["いらっしゃいませ","いらっしゃいませ"],["乾杯","かんぱい"],["お邪魔します","おじゃまします"],
                ["お大事に","おだいじに"],["久しぶり","ひさしぶり"],["気をつけて","きをつけて"],["良いお年を","よいおとしを"],
                ["明けましておめでとう","あけましておめでとう"],["どうぞ","どうぞ"]
            ],
            medium: [["天気が良いですね","てんきがよいですね"],["一緒に行きましょう","いっしょにいきましょう"],["明日は楽しみです","あしたはたのしみです"],["美味しいご飯を食べる","おいしいごはんをたべる"],["早起きは三文の徳","はやおきはさんもんのとく"],["散歩に出かけよう","さんぽにでかけよう"],["宿題が終わりました","しゅくだいがおわりました"],["準備はできましたか","じゅんびはできましたか"],["応援しています","おうえんしています"],["風邪を引かないでね","かぜをひかないでね"],["今日も頑張ろう","きょうもがんばろう"],["本を読むのが好き","ほんをよむのがすき"],["音楽を聴いてリラックス","おんがくをきいてりらっくす"],["映画を見に行こう","えいがをみにいこう"],["手を洗ってうがいをする","てをあらってうがいをする"],["笑顔で過ごそう","えがおですごそう"],["友達と遊ぶ約束","ともだちとあそぶやくそく"],["夢に向かって走る","ゆめにむかってはしる"],["季節の変わり目","きせつのかわりめ"],["星が綺麗に見える","ほしがきれいにみえる"],["時間を大切にしよう","じかんをたいせつにしよう"],["力を合わせて頑張る","ちからをあわせてがんばる"],["感謝の気持ちを伝える","かんしゃのきもちをつたえる"],["新しい挑戦をする","あたらしいちょうせんをする"],["旅に出たい気分","たびにでたいきぶん"],["綺麗な花が咲いた","きれいなはながさいた"],["心を込めて届ける","こころをこめてとどける"],["安全第一で行動","あんぜんだいいちでこうどう"],["明日は晴れるかな","あしたははれるかな"],["素晴らしい一日","すばらしいいちにち"]],
            proverbs: [["犬も歩けば棒に当たる","いぬもあるけばぼうにあたる"],["猿も木から落ちる","さるもきからおちる"],["石の上にも三年","いしのうえにもさんねん"],["三日坊主","みっかぼうず"],["塵も積もれば山となる","ちりもつもればやまとなる"],["笑う門には福来る","わらうかどにはふくきたる"],["早起きは三文の徳","はやおきはさんもんのとく"],["井の中の蛙大海を知らず","いのなかのかわずたいかいをしらず"],["急がば回れ","いそがばまわれ"],["渡りに船","わたりにふね"],["一石二鳥","いっせきにちょう"],["千里の道も一歩から","せんりのみちもいっぽから"],["能ある鷹は爪を隠す","のうあるたかはつめを隠す"],["壁に耳あり障子に目あり","かべにみみありしょうじにめあり"],["聞くは一時の恥聞かぬは一生の恥","きくはいちじのはじきかぬはいっしょうのはじ"],["好きこそ物の上手なれ","すきこそもののじょうずなれ"],["どんぐりの背比べ","どんぐりのせいくらべ"],["猫に小判","ねこにこばん"],["馬の耳に念仏","うまのみみにねんぶつ"],["花より団子","はなよりだんご"],["百聞は一見に如かず","ひゃくぶんはいっけんにしかず"],["豚に真珠","ぶたにしんじゅ"],["立つ鳥跡を濁さず","たつとりあとをにごさず"],["七転び八起き","ななころびやおき"],["案ずるより産むが易し","あんずるよりうむがやすし"],["頭隠して尻隠さず","あたまかくしてしりかくさず"],["郷に入っては郷に従え","ごうにいってはごうにしたがえ"],["触らぬ神に祟りなし","さわらぬかみにたたりなし"],["継続は力なり","けいぞくはちからなり"],["朱に交われば赤くなる","しゅにまじわればあかくなる"]],
            yojijukugo: [["一期一会","いちごいちえ"],["一石二鳥","いっせきにちょう"],["十人十色","じゅうにんといろ"],["自画自賛","じがじさん"],["以心伝心","いしんでんしん"],["弱肉強食","じゃくにくきょうしょく"],["日進月歩","にっしんげっぽ"],["試行錯誤","しこうさくご"],["温故知新","おんこちしん"],["起死回生","きしかいせい"],["大器晩成","たいきばんせい"],["電光石火","でんこうせっか"],["臨機応変","りんきおうへん"],["一朝一夕","いっちょういっせき"],["誠心誠意","せいしんせいい"],["無我夢中","むがむちゅう"],["自由自在","じゆうじざい"],["切磋琢磨","せっさたくま"],["前途洋々","ぜんとようよう"],["喜怒哀楽","きどあいらく"],["百花繚乱","ひゃっかりょうらん"],["悪戦苦闘","あくせんくとう"],["一刀両断","いっとうりょうだん"],["臥薪嘗胆","がしんしょうたん"],["花鳥風月","かちょうふうげつ"],["質実剛健","しつじつごうけん"],["単刀直入","たんとうちょくにゅう"],["天真爛漫","てんしんらんまん"],["不撓不屈","ふとうふくつ"],["容姿端麗","ようしたんれい"]],
            praise: [["素晴らしい","すばらしい"],["最高","さいこう"],["天才","てんさい"],["流石","さすが"],["完璧","かんぺき"],["素敵","すてき"],["優秀","ゆうしゅう"],["頼もしい","たのもしい"],["手際が良い","てぎわがよい"],["素晴らしい成果","すばらしいせいか"],["努力家","どりょくか"],["才能がある","さいのうがある"],["気が利く","きがきく"],["尊敬します","そんけいします"],["流石の腕前","さすがのうでまえ"],["魅力満点","みりょくまんてん"],["センスが良い","せんすがよい"],["笑顔が素敵","えがおがすてき"],["一目置いています","いちもくおいています"],["頼りにしています","たよりにしています"],["頭が良い","あたまがよい"],["優しい","やさしい"],["素晴らしい手腕","すばらしいしゅわん"],["期待以上","きたいいじょう"],["完璧な仕事","かんぺきなしごと"],["誇りに思います","ほこりにおもいます"],["感動しました","かんどうしました"],["素晴らしい発想","すばらしいはっそう"],["頼りになる存在","たよりになるそんざい"],["百点満点","ひゃくてんまんてん"]],
            onomatopoeia: [["わくわく","わくわく"],["どきどき","どきどき"],["にこにこ","にこにこ"],["ギラギラ","ぎらぎら"],["キラキラ","きらきら"],["ふわふわ","ふわふわ"],["もちもち","もちもち"],["すらすら","すらすら"],["ぐるぐる","ぐるぐる"],["ぺらぺら","ぺらぺら"],["どんどん","どんどん"],["どんどん進む","どんどんすすむ"],["ばっちり","ばっちり"],["しっかり","しっかり"],["ぐっすり","ぐっすり"],["うとうと","うとうと"],["はきはき","はきはき"],["のびのび","のびのび"],["ぴかぴか","ぴかぴか"],["つるつる","つるつる"],["さらさら","さらさら"],["ざあざあ","ざあざあ"],["しんしん","しんしん"],["ぐんぐん","ぐんぐん"],["ぱくぱく","ぱくぱく"],["ごくごく","ごくごく"],["もぐもぐ","もぐもぐ"],["てきぱき","てきぱき"],["ぬくぬく","ぬくぬく"],["ぽかぽか","ぽかぽか"]],
            animal_sounds: [["ワンワン","わんわん"],["ニャーニャー","にゃーにゃー"],["モーモー","もーもー"],["メーメー","めーめー"],["コケコッコー","こけこっこー"],["ブーブー","ぶーぶー"],["ヒーヒーン","ひーひーん"],["ガーガー","がーがー"],["クワクワ","くわくわ"],["チュンチュン","ちゅんちゅん"],["カーカー","かーかー"],["クークー","くーくー"],["パオーン","ぱおん"],["ガオー","がおー"],["ウキッキー","うきっきー"],["ケロケロ","けろけろ"],["ミーンミーン","みーんみーん"],["カンカン","かんかん"],["ホーホー","ほーほー"],["チッチッ","ちっちっ"],["ブーンブーン","ぶーんぶーん"],["ヒヒーン","ひひーん"],["ケーンケーン","けーんけーん"],["ピヨピヨ","ぴよぴよ"],["ゲコゲコ","げこげこ"],["コロコロ","ころころ"],["クックッ","くっくっ"],["ポッポ","ぽっぽ"],["ギコギコ","ぎこぎこ"],["チュウチュウ","ちゅうちゅう"]],
            radicals: [["木偏","きへん"],["人偏","にんべん"],["三水","さんずい"],["草冠","くさかんむり"],["手偏","てへん"],["言偏","ごんべん"],["うかんむり","うかんむり"],["まだれ","まだれ"],["竹冠","たけかんむり"],["糸偏","いとへん"],["門構え","もんがまえ"],["国構え","くにがまえ"],["心","こころ"],["のぎへん","のぎへん"],["金偏","かねへん"],["女偏","おんなへん"],["子偏","こへん"],["やまいだれ","やまいだれ"],["しんにょう","しんにょう"],["りっしんべん","りっしんべん"],["けものへん","けものへん"],["にくづき","にくづき"],["貝偏","かいへん"],["車偏","くるまへん"],["魚偏","さかなへん"],["鳥偏","とりへん"],["日偏","ひへん"],["月偏","つきへん"],["目偏","めへん"],["弓偏","ゆみへん"]],
            nandoku_kanji: [["海老","えび"],["玉葱","たまねぎ"],["紫陽花","あじさい"],["向日葵","ひまわり"],["仙人掌","さぼてん"],["蒲公英","たんぽぽ"],["土竜","もぐら"],["海月","くらげ"],["心太","ところてん"],["烏賊","いか"],["蛸","たこ"],["鮟鱇","あんこう"],["栄螺","さざえ"],["蜻蛉","とんぼ"],["蟷螂","かまきり"],["鸚鵡","おうむ"],["啄木鳥","きつつき"],["翡翠","かわせみ"],["満天星","どうだんつつじ"],["百合","ゆり"],["薔薇","ばら"],["鬱金香","ちゅーりっぷ"],["乙女心","おとめごころ"],["零余子","むかご"],["八月朔日","ほずみ"],["小豆","あずき"],["大豆","だいず"],["団栗","どんぐり"],["胡桃","くるみ"],["翻車魚","まんぼう"]],
            keigo: [["承知いたしました","しょうちいたしました"],["かしこまりました","かしこまりました"],["ありがとうございます","ありがとうございます"],["申し訳ございません","もうしわけございません"],["お世話になっております","おせわになっております"],["よろしくお願い申し上げます","よろしくおねがいもうしあげます"],["おっしゃる","おっしゃる"],["ご覧になる","ごらんになる"],["召し上がる","めしあがる"],["いらっしゃる","いらっしゃる"],["拝見する","はいけんする"],["伺う","うかがう"],["申し上げる","もうしあげる"],["いたします","いたします"],["存じ上げております","ぞんじあげております"],["恐れ入ります","おそれいります"],["お手数をおかけします","おてすうをおかけします"],["ご容赦ください","ごようしゃください"],["ご確認くだされば","ごかくにんくだされば"],["ご連絡いたします","ごれんらくいたします"],["お待ちしております","おまちしております"],["ご指導ご鞭撻","ごしどうごべんたつ"],["ご足労","ごそくろう"],["お疲れ様です","おつかれさまです"],["ご自愛ください","ごじあいください"],["おっしゃる通り","おっしゃるとおり"],["差し支えなければ","さしつかえなければ"],["お力になれず","おちからになれず"],["幸いに存じます","さいわいにぞんじます"],["お忙しいところ","おいそがしいところ"]],
            traditional_colors: [["桜色","さくらいろ"],["山吹色","やまぶきいろ"],["茜色","あかねいろ"],["藍色","あいいろ"],["浅葱色","あさぎいろ"],["群青色","ぐんじょういろ"],["萌黄色","もぎいろ"],["鶯色","うぐいしいろ"],["琥珀色","こはくいろ"],["桔梗色","ききょういろ"],["藤色","ふじいろ"],["牡丹色","ぼたんいろ"],["朱色","しゅいろ"],["柿色","かきいろ"],["栗色","くりいろ"],["狐色","きつねいろ"],["抹茶色","まっちゃいろ"],["常盤色","ときわいろ"],["空色","そらいろ"],["瑠璃色","るりいろ"],["紺青","こんじょう"],["墨色","すみいろ"],["胡粉色","ごふんいろ"],["生成色","きなりいろ"],["葡萄色","えびいろ"],["唐紅","からくれない"],["竜胆色","りんどういろ"],["若竹色","わかたけいろ"],["黄金色","こがねいろ"],["漆黒","しっこく"]],
            japanese_holidays: [["元日","がんじつ"],["成人の日","せいじんのひ"],["建国記念の日","けんこくきねんのひ"],["天皇誕生日","てんのうたんじょうび"],["春分の日","しゅんぶんのひ"],["昭和の日","しょうわのひ"],["憲法記念日","けんぽうきねんび"],["みどりの日","みどりのひ"],["こどもの日","こどものひ"],["海の日","うみのひ"],["山の日","やまのひ"],["敬老の日","けいろうのひ"],["秋分の日","しゅうぶんのひ"],["スポーツの日","すぽーつのひ"],["文化の日","ぶんかのひ"],["勤労感謝の日","きんろうかんしゃのひ"],["振替休日","ふりかえきゅうじつ"],["国民の休日","こくみんのきゅうじつ"],["ハッピーマンデー","はっぴーまんでー"],["ゴールデンウィーク","ごーるでんうぃーく"],["シルバーウィーク","しるばーうぃーく"],["正月","しょうがつ"],["節分","せつぶん"],["ひな祭り","ひなまつり"],["端午の節句","たんごのせっく"],["七夕","たなばた"],["お盆","おぼん"],["十五夜","じゅうごや"],["大晦日","おおみそか"],["七五三","しちごさん"]],
            constellations: [["おひつじ座","おひつじざ"],["おうし座","おうしざ"],["ふたご座","ふたござ"],["かに座","かにざ"],["しし座","ししざ"],["おとめ座","おとめざ"],["てんびん座","てんびんざ"],["さそり座","さそりざ"],["いて座","いてざ"],["やぎ座","やぎざ"],["みずがめ座","みずがめざ"],["うお座","うおざ"],["オリオン座","おりおんざ"],["カシオペヤ座","かしおぺやざ"],["北斗七星","ほくとしちせい"],["はくちょう座","はくちょうざ"],["わし座","わしざ"],["こと座","ことざ"],["アンドロメダ座","あんどろめだざ"],["ペガスス座","ぺがすすざ"],["おおぐま座","おおぐまざ"],["こぐま座","こぐまざ"],["ヘルクレス座","へるくれすざ"],["ペルセウス座","ぺるせうすざ"],["みなみじゅうじ座","みなみじゅうじざ"],["ケンタウルス座","けんたうるすざ"],["りゅう座","りゅうざ"],["いっかくじゅう座","いっかくじゅうざ"],["へびつかい座","へびつかいざ"],["うみへび座","うみへびざ"]],
            world_currencies: [["円","えん"],["ドル","どる"],["ユーロ","ゆーろ"],["ポンド","ぽんど"],["元","げん"],["ウォン","うぉん"],["ルピー","るぴー"],["バーツ","ばーつ"],["ドン","どん"],["ルピア","るぴあ"],["リンギット","りんぎっと"],["ペソ","ぺそ"],["リアル","りある"],["ルーブル","るーぶる"],["フラン","ふらん"],["クローネ","くろーね"],["リラ","りら"],["ディナール","でぃなーる"],["ディルハム","でぃるはむ"],["シェケル","しぇける"],["ランド","らんど"],["スム","すむ"],["テンゲ","てんげ"],["タカ","たか"],["ニュージーランドドル","にゅーじーらんどどる"],["カナダドル","かなだどる"],["オーストラリアドル","おーすとらりあどる"],["シンガポールドル","しんがぽーるどる"],["レアル","れある"],["ズロチ","ずろち"]],
            spring: [["桜","さくら"],["菜の花","なのはな"],["蒲公英","たんぽぽ"],["チューリップ","ちゅーりっぷ"],["鶯","うぐいす"],["燕","つばめ"],["新学期","しんがっき"],["卒業式","そつぎょうしき"],["入学式","にゅうがくしき"],["花見","はなみ"],["筍","たけのこ"],["草餅","くさもち"],["柏餅","かしわもち"],["ひな人形","ひなにおう"],["つくし","つくし"],["春風","はるかぜ"],["春一番","はるいちばん"],["ポカポカ","ぽかぽか"],["苺","いちご"],["芽吹き","めぶき"],["鯉のぼり","こいのぼり"],["蜜蜂","みつばち"],["蝶々","ちょうちょう"],["潮干狩り","しおひがり"],["桜餅","さくらもち"],["春雨","はるさめ"],["新緑","しんりょく"],["啓蟄","けいちつ"],["春分","しゅんぶん"],["朧月","おぼろづき"]],
            summer: [["向日葵","ひまわり"],["朝顔","あさ顔"],["蝉","せみ"],["カブトムシ","かぶとむし"],["西瓜","すいか"],["かき氷","かきごおり"],["風鈴","ふうりん"],["麦わら帽子","むぎわらぼうし"],["花火","はなび"],["夏祭り","なつまつり"],["入道雲","にゅうどうぐも"],["蚊取り線香","かとりせんこう"],["冷やし中華","ひやしちゅうか"],["夏休み","なつやすみ"],["海水浴","かいすいよく"],["プール","ぷーる"],["扇風機","せんぷうき"],["エアコン","えあこん"],["うちわ","うちわ"],["扇子","せんす"],["浴衣","ゆかた"],["金魚すくい","きんぎょすくい"],["蚊","か"],["蛍","ほたる"],["日日草","にちにちそう"],["猛暑","もうしょ"],["夕立","ゆうだち"],["暑中見舞い","しょちゅうみまい"],["ラジオ体操","らじおたいそう"],["氷水","こおりみず"]],
            autumn: [["紅葉","もみじ"],["銀杏","いちょう"],["栗","くり"],["柿","かき"],["葡萄","ぶどう"],["秋刀魚","さんま"],["松茸","まつたけ"],["十五夜","じゅうごや"],["お月見","おつきみ"],["虫の音","むしのね"],["鈴虫","すずむし"],["赤とんぼ","あかとんぼ"],["読書の秋","どくしょのあき"],["食欲の秋","しょくよくのあき"],["運動会","うんどうかい"],["文化祭","ぶんかさい"],["ハロウィン","はろうぃん"],["彼岸花","ひがんばな"],["コスモス","こすもす"],["落ち葉","おちば"],["焼き芋","やきいも"],["豊作","ほうさく"],["新米","しんまい"],["秋晴れ","あきばれ"],["秋風","あきかぜ"],["初霜","はつしも"],["寒露","かんろ"],["木枯らし","こがらし"],["団栗","どんぐり"],["松っくり","まつぼっくり"]],
            winter: [["雪","ゆき"],["氷","こおり"],["霜","しも"],["雪だるま","ゆきだるま"],["コタツ","こたつ"],["蜜柑","みかん"],["鍋料理","なべりょうり"],["おでん","おでん"],["クリスマス","くりすます"],["サンタクロース","さんたくろーす"],["大晦日","おおみそか"],["除夜の鐘","じょやのかね"],["年越しそば","としこしそば"],["お正月","おしょうがつ"],["初詣","はつもうで"],["お年玉","おとしだま"],["おせち料理","おせちりょうり"],["雑煮","ぞうに"],["凧揚げ","たこあげ"],["羽子板","はごいた"],["成人式","せいじんしき"],["スキー","すきー"],["スノーボード","すのーぼーど"],["スケート","すけーと"],["寒波","かんぱ"],["つらら","つらら"],["息が白い","いきがしろい"],["湯たんぽ","ゆたんぽ"],["カイロ","かいろ"],["マフラー","まふらー"]]
        };

        const WORD_DATA = {};
        for (const [courseKey, list] of Object.entries(RAW_WORD_DATA)) {
            WORD_DATA[courseKey] = list.map(item => {
                if (typeof item === 'string') {
                    return { rubyTokens: [{ text: item, ruby: item }], kana: item };
                }
                const [text, kana, ruby] = item;
                const actualKana = kana || text;
                const actualRuby = ruby || actualKana;
                return {
                    rubyTokens: [{ text: text, ruby: actualRuby }],
                    kana: actualKana
                };
            });
        }

        const ROMAJI_MAP = {
            'あ':['a'], 'い':['i'], 'う':['u','wu'], 'え':['e'], 'お':['o'],
            'か':['ka'], 'き':['ki'], 'く':['ku'], 'け':['ke'], 'こ':['ko'],
            'さ':['sa'], 'し':['si','shi'], 'す':['su'], 'せ':['se'], 'そ':['so'],
            'た':['ta'], 'ち':['ti','chi'], 'つ':['tsu','tu'], 'て':['te'], 'と':['to'],
            'な':['na'], 'に':['ni'], 'ぬ':['nu'], 'ね':['ne'], 'の':['no'],
            'は':['ha'], 'ひ':['hi'], 'ふ':['fu','hu'], 'へ':['he'], 'ほ':['ho'],
            'ま':['ma'], 'み':['mi'], 'む':['mu'], 'め':['me'], 'も':['mo'],
            'や':['ya'], 'ゆ':['yu'], 'よ':['yo'],
            'ら':['ra'], 'り':['ri'], 'る':['ru'], 'れ':['re'], 'ろ':['ro'],
            'わ':['wa'], 'を':['wo'], 'ん':['nn','n',"n'"],
            'が':['ga'], 'ぎ':['gi'], 'ぐ':['gu'], 'げ':['ge'], 'ご':['go'],
            'ざ':['za'], 'じ':['ji','zi'], 'ず':['zu'], 'ぜ':['ze'], 'ぞ':['zo'],
            'だ':['da'], 'ぢ':['di'], 'づ':['du'], 'で':['de'], 'ど':['do'],
            'ば':['ba'], 'び':['bi'], 'ぶ':['bu'], 'べ':['be'], 'ぼ':['bo'],
            'ぱ':['pa'], 'ぴ':['pi'], 'ぷ':['pu'], 'ぺ':['pe'], 'ぽ':['po'],
            
            'きゃ':['kya'], 'きゅ':['kyu'], 'きょ':['kyo'],
            'しゃ':['sya','sha'], 'しゅ':['syu','shu'], 'しょ':['syo','sho'],
            'ちゃ':['tya','cha'], 'ちゅ':['tyu','chu'], 'ちょ':['tyo','cho'],
            'にゃ':['nya'], 'にゅ':['nyu'], 'にょ':['nyo'],
            'ひゃ':['hya'], 'ひゅ':['hyu'], 'ひょ':['hyo'],
            'みゃ':['mya'], 'みゅ':['myu'], 'みょ':['myo'],
            'りゃ':['rya'], 'りゅ':['ryu'], 'りょ':['ryo'],
            'ぎゃ':['gya'], 'ぎゅ':['gyu'], 'ぎょ':['gyo'],
            'じゃ':['ja','zya','jya'], 'じゅ':['ju','zyu','jyu'], 'じょ':['jo','zyo','jyo'],
            'びゃ':['bya'], 'びゅ':['byu'], 'びょ':['byo'],
            'ぴゃ':['pya'], 'ぴゅ':['pyu'], 'ぴょ':['pyo'],

            'じぇ':['je','zye','jye'], 'しぇ':['she','sye'], 'ちぇ':['che','tye'],
            'じぃ':['jyi','zyi'],
            'てぃ':['ti','thi'], 'でぃ':['di','dhi'],
            'てゅ':['tyu','thu'], 'でゅ':['dyu','dhu'],
            'とぅ':['twu'], 'どぅ':['dwu'],
            'ふぁ':['fa'], 'ふぃ':['fi','fyi'], 'ふぇ':['fe','fye'], 'ふぉ':['fo'], 'ふゅ':['fyu'],
            'つぁ':['tsa'], 'つぃ':['tsi'], 'つぇ':['tse'], 'つぉ':['tso'],
            'うぃ':['wi','whi'], 'うぇ':['we','whe'], 'うぉ':['who'],
            'いぇ':['ye'],
            'きぇ':['kye'], 'ぎぇ':['gye'], 'にぇ':['nye'], 'ひぇ':['hye'], 'みぇ':['mye'], 'りぇ':['rye'], 'ぴぇ':['pye'], 'びぇ':['bye'],
            'くぁ':['kwa','qa'], 'くぃ':['qi','qwi'], 'くぇ':['qe','qwe'], 'くぉ':['qo','qwo'], 'ぐぁ':['gwa'],
            'ゔぁ':['va'], 'ゔぃ':['vi'], 'ゔ':['vu'], 'ゔぇ':['ve'], 'ゔぉ':['vo'], 'ゔゅ':['vyu'],

            'ぁ':['xa','la'], 'ぃ':['xi','li','yi'], 'ぅ':['xu','lu','whu'], 'ぇ':['xe','le','ye'], 'ぉ':['xo','lo'],
            'ゃ':['xya','lya'], 'ゅ':['xyu','lyu'], 'ょ':['xyo','lyo'], 'っ':['xtu','ltu','xtsu','ltsu'], 'ゎ':['xwa','lwa'],

            'ー':['-']
        };

        let gameState = {
            course: 'aiueo',
            timeLimit: 60,
            timeLeft: 60,
            showRuby: true,
            soundEnabled: true,
            isPlaying: false,
            isCountingDown: false,
            countdownTimeouts: [],
            score: 0,
            totalTyped: 0,
            correctTyped: 0,
            correctKanaTyped: 0,
            missTyped: 0,
            timerId: null,
            totalScore: parseInt(localStorage.getItem('typing_master_totalscore') || '0'),
            highScore: parseInt(localStorage.getItem('typing_master_highscore') || '0'),
            highWpm: parseInt(localStorage.getItem('typing_master_highwpm') || '0'),
            
            currentWord: null,
            kanaTokens: [],
            tokenIndex: 0,
            typedInToken: '',
            targetRomajiList: [],
            remainingWords: []
        };

        function cancelCountdown() {
            if (gameState.countdownTimeouts) {
                gameState.countdownTimeouts.forEach(t => clearTimeout(t));
            }
            gameState.countdownTimeouts = [];
            gameState.isCountingDown = false;
            const overlay = document.getElementById('countdown-overlay');
            if (overlay) overlay.classList.add('hidden');
        }

        function startGame() {
            cancelCountdown();
            clearInterval(gameState.timerId);

            gameState.isPlaying = false;
            gameState.isCountingDown = true;

            gameState.score = 0;
            gameState.totalTyped = 0;
            gameState.correctTyped = 0;
            gameState.correctKanaTyped = 0;
            gameState.missTyped = 0;
            gameState.timeLeft = gameState.timeLimit;

            const currentCourseData = WORD_DATA[gameState.course] || WORD_DATA.aiueo;
            gameState.remainingWords = shuffleArray(currentCourseData);

            document.getElementById('timer-display').textContent = gameState.timeLeft;
            document.getElementById('score-display').textContent = 0;
            document.getElementById('accuracy-display').textContent = 100;

            document.getElementById('start-screen').classList.add('hidden');
            document.getElementById('result-screen').classList.add('hidden');
            document.getElementById('play-screen').classList.remove('hidden');

            nextWord();

            const overlay = document.getElementById('countdown-overlay');
            const countdownText = document.getElementById('countdown-text');
            overlay.classList.remove('hidden');

            const steps = [
                { text: '3', color: 'text-amber-400', isStart: false },
                { text: '2', color: 'text-amber-400', isStart: false },
                { text: '1', color: 'text-amber-400', isStart: false },
                { text: 'スタート！', color: 'text-emerald-400', isStart: true }
            ];

            function showStep(index) {
                if (index < steps.length) {
                    const step = steps[index];
                    countdownText.textContent = step.text;
                    countdownText.className = `text-6xl sm:text-7xl md:text-9xl font-black ${step.color} drop-shadow-[0_10px_20px_rgba(0,0,0,0.5)] animate-countdown`;
                    
                    countdownText.classList.remove('animate-countdown');
                    void countdownText.offsetWidth;
                    countdownText.classList.add('animate-countdown');

                    sound.playCountdown(step.isStart);

                    const timeoutId = setTimeout(() => {
                        showStep(index + 1);
                    }, step.isStart ? 750 : 900);
                    gameState.countdownTimeouts.push(timeoutId);
                } else {
                    overlay.classList.add('hidden');
                    gameState.isCountingDown = false;
                    gameState.isPlaying = true;

                    clearInterval(gameState.timerId);
                    gameState.timerId = setInterval(() => {
                        gameState.timeLeft--;
                        document.getElementById('timer-display').textContent = gameState.timeLeft;
                        if (gameState.timeLeft <= 0) {
                            endGame();
                        }
                    }, 1000);
                }
            }

            showStep(0);
        }

        window.addEventListener('DOMContentLoaded', () => {
            initBackgroundParticles();
            setupSettingsUI();
            setupKeyboardListeners();
            updateHighscoreDisplays();
            updateDailyMessage();
        });

        function setupSettingsUI() {
            // Course buttons
            document.querySelectorAll('.course-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    document.querySelectorAll('.course-btn').forEach(b => {
                        b.classList.remove('border-sky-500', 'bg-sky-50');
                        b.classList.add('border-slate-300', 'bg-white');
                    });
                    btn.classList.remove('border-slate-300', 'bg-white');
                    btn.classList.add('border-sky-500', 'bg-sky-50');
                    if (btn.dataset.course) {
                        gameState.course = btn.dataset.course;
                    }
                });
            });

            // Time selector buttons
            document.querySelectorAll('.time-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    document.querySelectorAll('.time-btn').forEach(b => {
                        b.classList.remove('border-sky-500', 'bg-sky-50', 'text-sky-600');
                        b.classList.add('border-slate-300', 'bg-white', 'text-slate-700');
                    });
                    btn.classList.remove('border-slate-300', 'bg-white', 'text-slate-700');
                    btn.classList.add('border-sky-500', 'bg-sky-50', 'text-sky-600');
                    if (btn.dataset.time) {
                        gameState.timeLimit = parseInt(btn.dataset.time, 10);
                        gameState.timeLeft = gameState.timeLimit;
                    }
                });
            });

            // Ruby toggle handler
            const updateRubyDisplay = () => {
                const headerRubyText = document.getElementById('header-ruby-text');
                const ingameRubyText = document.getElementById('ingame-ruby-text');
                const settingRubyStatus = document.getElementById('setting-ruby-status');
                const settingRubyBtn = document.getElementById('setting-ruby-btn');

                if (gameState.showRuby) {
                    document.body.classList.remove('ruby-hidden');
                    if (headerRubyText) headerRubyText.textContent = 'ふりがな: ON';
                    if (ingameRubyText) ingameRubyText.textContent = 'ルビ: ON';
                    if (settingRubyStatus) settingRubyStatus.textContent = 'ON';
                    if (settingRubyBtn) {
                        settingRubyBtn.classList.remove('bg-slate-100', 'text-slate-600');
                        settingRubyBtn.classList.add('bg-sky-50', 'text-sky-700');
                    }
                } else {
                    document.body.classList.add('ruby-hidden');
                    if (headerRubyText) headerRubyText.textContent = 'ふりがな: OFF';
                    if (ingameRubyText) ingameRubyText.textContent = 'ルビ: OFF';
                    if (settingRubyStatus) settingRubyStatus.textContent = 'OFF';
                    if (settingRubyBtn) {
                        settingRubyBtn.classList.add('bg-slate-100', 'text-slate-600');
                        settingRubyBtn.classList.remove('bg-sky-50', 'text-sky-700');
                    }
                }
            };

            const toggleRuby = () => {
                gameState.showRuby = !gameState.showRuby;
                updateRubyDisplay();
            };

            const headerRubyToggle = document.getElementById('header-ruby-toggle');
            const settingRubyBtn = document.getElementById('setting-ruby-btn');
            const ingameRubyBtn = document.getElementById('ingame-ruby-btn');

            if (headerRubyToggle) headerRubyToggle.addEventListener('click', toggleRuby);
            if (settingRubyBtn) settingRubyBtn.addEventListener('click', toggleRuby);
            if (ingameRubyBtn) ingameRubyBtn.addEventListener('click', toggleRuby);

            // Sound toggle
            const soundToggleBtn = document.getElementById('sound-toggle-btn');
            const soundIcon = document.getElementById('sound-icon');
            if (soundToggleBtn && soundIcon) {
                soundToggleBtn.addEventListener('click', () => {
                    gameState.soundEnabled = !gameState.soundEnabled;
                    if (gameState.soundEnabled) {
                        soundIcon.className = 'fa-solid fa-volume-high';
                        soundToggleBtn.classList.remove('text-slate-400');
                        soundToggleBtn.classList.add('text-sky-600');
                    } else {
                        soundIcon.className = 'fa-solid fa-volume-xmark';
                        soundToggleBtn.classList.add('text-slate-400');
                        soundToggleBtn.classList.remove('text-sky-600');
                    }
                });
            }

            // Start game buttons
            const startGameBtn = document.getElementById('start-game-btn');
            if (startGameBtn) startGameBtn.addEventListener('click', () => startGame());

            // In-game buttons
            const ingameBackBtn = document.getElementById('ingame-back-btn');
            if (ingameBackBtn) {
                ingameBackBtn.addEventListener('click', () => {
                    cancelCountdown();
                    gameState.isPlaying = false;
                    clearInterval(gameState.timerId);
                    showStartScreen();
                });
            }

            const ingameRetryBtn = document.getElementById('ingame-retry-btn');
            if (ingameRetryBtn) ingameRetryBtn.addEventListener('click', () => startGame());

            // Result buttons
            const restartBtn = document.getElementById('restart-btn');
            if (restartBtn) restartBtn.addEventListener('click', () => startGame());

            const backHomeBtn = document.getElementById('back-home-btn');
            if (backHomeBtn) backHomeBtn.addEventListener('click', () => showStartScreen());
        }

        function updateHighscoreDisplays() {
            document.getElementById('start-totalscore').textContent = gameState.totalScore.toLocaleString();
            document.getElementById('start-highscore').textContent = gameState.highScore.toLocaleString();
            document.getElementById('start-highwpm').textContent = gameState.highWpm;
        }

        function updateDailyMessage() {
            const msgEl = document.getElementById('daily-message-text');
            if (!msgEl) return;

            const today = new Date().toISOString().split('T')[0];
            const lastVisit = localStorage.getItem('typing_master_last_visit');
            let streak = parseInt(localStorage.getItem('typing_master_streak') || '0');

            if (!lastVisit) {
                streak = 1;
            } else if (lastVisit === today) {
                if (streak === 0) streak = 1;
            } else {
                const lastDate = new Date(lastVisit);
                const currentDate = new Date(today);
                const diffDays = Math.round((currentDate - lastDate) / (1000 * 60 * 60 * 24));
                if (diffDays === 1) {
                    streak += 1;
                } else {
                    streak = 1;
                }
            }

            localStorage.setItem('typing_master_last_visit', today);
            localStorage.setItem('typing_master_streak', streak.toString());

            const tips = [
                "タイピングができると、学校の発表や宿題がサクサク進むよ！",
                "タイピングができると、将来パソコンのお仕事も得意になるよ！",
                "キーボードを見ずに画面を見て打つ（タッチタイピング）を目指してみよう！",
                "ホームポジション（FとJに人差し指）を意識すると、もっと速く打てるよ！",
                "指をたくさん動かすと、脳が活性化して集中力もアップするよ！",
                "毎日少しずつ練習することが、タイピング上達の一番の近道だよ！"
            ];

            const candidates = [];

            if (streak > 1) {
                candidates.push(`🔥 ${streak}日連続でアクセス中！すごい継続力だね！`);
                candidates.push(`✨ すごーい！${streak}日連続で練習に来てくれたね！`);
            } else {
                candidates.push(`✨ アクセスありがとう！今日も楽しくタイピングしよう！`);
            }

            if (gameState.totalScore > 0) {
                candidates.push(`🎉 累計スコアが ${gameState.totalScore.toLocaleString()}pt になったね。すごい！`);
            }

            const randomTip = tips[Math.floor(Math.random() * tips.length)];
            candidates.push(`💡 ${randomTip}`);

            const chosen = candidates[Math.floor(Math.random() * candidates.length)];
            msgEl.textContent = chosen;
        }

        function triggerConfetti() {
            const colors = ['#f59e0b', '#ef4444', '#10b981', '#06b6d4', '#8b5cf6', '#ec4899', '#facc15', '#3b82f6'];
            const kusudamaX = window.innerWidth / 2;
            const kusudamaY = window.innerHeight / 2 - 80;

            confettiParticles = Array.from({ length: 140 }, () => {
                const isStreamer = Math.random() < 0.3;
                const angle = Math.random() * Math.PI * 2;
                const speed = Math.random() * 12 + 4;
                return {
                    x: kusudamaX + (Math.random() - 0.5) * 40,
                    y: kusudamaY + (Math.random() - 0.5) * 20,
                    vx: Math.cos(angle) * speed,
                    vy: Math.sin(angle) * speed - 4,
                    width: isStreamer ? Math.random() * 4 + 3 : Math.random() * 8 + 5,
                    height: isStreamer ? Math.random() * 25 + 15 : Math.random() * 8 + 5,
                    color: colors[Math.floor(Math.random() * colors.length)],
                    rotation: Math.random() * 360,
                    vRot: (Math.random() - 0.5) * 12,
                    drag: 0.96,
                    gravity: Math.random() * 0.15 + 0.1,
                    isStreamer: isStreamer
                };
            });
        }

        function endGame() {
            gameState.isPlaying = false;
            clearInterval(gameState.timerId);

            const accuracy = gameState.totalTyped > 0 
                ? Math.round((gameState.correctTyped / gameState.totalTyped) * 100) 
                : 100;
            
            const kanaSpeed = Math.round((gameState.correctKanaTyped / gameState.timeLimit) * 60);

            let isNewRecord = false;
            const NEW_RECORD_BONUS = 500;

            if (gameState.score > gameState.highScore && gameState.score > 0) {
                isNewRecord = true;
                gameState.score += NEW_RECORD_BONUS;
                gameState.highScore = gameState.score;
                localStorage.setItem('typing_master_highscore', gameState.score.toString());
            }

            if (kanaSpeed > gameState.highWpm) {
                gameState.highWpm = kanaSpeed;
                localStorage.setItem('typing_master_highwpm', kanaSpeed.toString());
            }

            gameState.totalScore += gameState.score;
            localStorage.setItem('typing_master_totalscore', gameState.totalScore.toString());

            updateHighscoreDisplays();

            let rank = 'C';
            let rankTitle = 'ビギナータイパー';
            if (gameState.score >= 1200 && accuracy >= 95) {
                rank = 'S'; rankTitle = 'タイピング神';
            } else if (gameState.score >= 800 && accuracy >= 90) {
                rank = 'A'; rankTitle = 'マスタータイパー';
            } else if (gameState.score >= 400) {
                rank = 'B'; rankTitle = 'エキスパートタイパー';
            }

            document.getElementById('final-score').textContent = gameState.score;
            document.getElementById('final-wpm').textContent = kanaSpeed;
            document.getElementById('final-keys').textContent = gameState.correctTyped;
            document.getElementById('final-accuracy').textContent = `${accuracy}%`;
            document.getElementById('rank-badge').textContent = `ランク [ ${rank} ] : ${rankTitle}`;

            let wpmComment = '';
            if (kanaSpeed >= 120) wpmComment = '💼 大人の仕事レベル！';
            else if (kanaSpeed >= 70) wpmComment = '👍 スムーズに入力！';
            else wpmComment = '🌱 はじめてレベル';
            const wpmCommentEl = document.getElementById('wpm-comment');
            if (wpmCommentEl) wpmCommentEl.textContent = wpmComment;

            const kusudamaWrapper = document.getElementById('kusudama-wrapper');
            const kusudamaElement = document.getElementById('kusudama-element');
            const kusudamaMsg = document.getElementById('kusudama-msg');

            if (isNewRecord) {
                kusudamaWrapper.classList.remove('hidden');
                kusudamaElement.classList.remove('kusudama-open', 'kusudama-anim-drop', 'kusudama-anim-shake');
                kusudamaMsg.classList.add('opacity-0');
                
                void kusudamaElement.offsetWidth;
                kusudamaElement.classList.add('kusudama-anim-drop');

                setTimeout(() => {
                    kusudamaElement.classList.remove('kusudama-anim-drop');
                    kusudamaElement.classList.add('kusudama-anim-shake');
                }, 600);

                setTimeout(() => {
                    kusudamaElement.classList.remove('kusudama-anim-shake');
                    kusudamaElement.classList.add('kusudama-open');
                    kusudamaMsg.classList.remove('opacity-0');
                    kusudamaMsg.classList.add('animate-bounce');
                    
                    sound.playFanfare();
                    triggerConfetti();
                }, 950);

            } else {
                kusudamaWrapper.classList.add('hidden');
            }

            document.getElementById('play-screen').classList.add('hidden');
            document.getElementById('result-screen').classList.remove('hidden');
        }

        function showStartScreen() {
            document.getElementById('play-screen').classList.add('hidden');
            document.getElementById('result-screen').classList.add('hidden');
            document.getElementById('start-screen').classList.remove('hidden');
            updateHighscoreDisplays();
            updateDailyMessage();
        }

        function parseKanaToTokens(kanaStr) {
            kanaStr = kanaStr.replace(/[\u30a1-\u30f6]/g, match => String.fromCharCode(match.charCodeAt(0) - 0x60));

            let tokens = [];
            let i = 0;
            while (i < kanaStr.length) {
                if (i + 1 < kanaStr.length) {
                    let pair = kanaStr.substring(i, i + 2);
                    if (ROMAJI_MAP[pair]) {
                        tokens.push(pair);
                        i += 2;
                        continue;
                    }
                }
                if (kanaStr[i] === 'っ' && i + 1 < kanaStr.length) {
                    tokens.push('っ');
                    i++;
                    continue;
                }
                tokens.push(kanaStr[i]);
                i++;
            }
            return tokens;
        }

        function nextWord() {
            if (!gameState.remainingWords || gameState.remainingWords.length === 0) {
                const selectedCourseData = WORD_DATA[gameState.course] || WORD_DATA.aiueo;
                gameState.remainingWords = shuffleArray(selectedCourseData);
            }
            const word = gameState.remainingWords.pop();
            gameState.currentWord = word;
            
            let wordHtml = '';
            word.rubyTokens.forEach(token => {
                const rubyText = token.ruby || token.text;
                wordHtml += `<ruby>${token.text}<rt>${rubyText}</rt></ruby>`;
            });
            document.getElementById('word-display').innerHTML = wordHtml;
            document.getElementById('kana-display').textContent = word.kana;

            gameState.kanaTokens = parseKanaToTokens(word.kana);
            gameState.tokenIndex = 0;
            gameState.typedInToken = '';
            
            updateRomajiDisplay();
        }

        function updateRomajiDisplay() {
            if (gameState.tokenIndex >= gameState.kanaTokens.length) {
                sound.playSuccess();
                nextWord();
                return;
            }

            const currentKana = gameState.kanaTokens[gameState.tokenIndex];
            
            let candidates = [];
            if (currentKana === 'っ') {
                const nextKana = gameState.kanaTokens[gameState.tokenIndex + 1];
                if (nextKana && ROMAJI_MAP[nextKana]) {
                    const nextFirstChar = ROMAJI_MAP[nextKana][0][0];
                    candidates = [nextFirstChar, 'xtu', 'ltu'];
                } else {
                    candidates = ['xtu', 'ltu'];
                }
            } else if (currentKana === 'ん') {
                const nextKana = gameState.kanaTokens[gameState.tokenIndex + 1];
                let isFollowedByVowelOrYorN = false;
                if (nextKana && ROMAJI_MAP[nextKana]) {
                    const firstChars = ROMAJI_MAP[nextKana].map(r => r[0].toLowerCase());
                    isFollowedByVowelOrYorN = firstChars.some(c => ['a', 'i', 'u', 'e', 'o', 'y', 'n'].includes(c));
                }
                if (isFollowedByVowelOrYorN) {
                    candidates = ['nn', "n'"];
                } else {
                    candidates = ['n', 'nn', "n'"];
                }
            } else if (ROMAJI_MAP[currentKana]) {
                candidates = ROMAJI_MAP[currentKana];
            } else {
                candidates = [currentKana];
            }

            gameState.targetRomajiList = candidates;

            let typedStr = '';
            for (let i = 0; i < gameState.tokenIndex; i++) {
                const k = gameState.kanaTokens[i];
                if (k === 'っ') {
                    const nk = gameState.kanaTokens[i + 1];
                    typedStr += (nk && ROMAJI_MAP[nk]) ? ROMAJI_MAP[nk][0][0] : 't';
                } else if (k === 'ん') {
                    const nk = gameState.kanaTokens[i + 1];
                    let isFollowedByVowelOrYorN = false;
                    if (nk && ROMAJI_MAP[nk]) {
                        const firstChars = ROMAJI_MAP[nk].map(r => r[0].toLowerCase());
                        isFollowedByVowelOrYorN = firstChars.some(c => ['a', 'i', 'u', 'e', 'o', 'y', 'n'].includes(c));
                    }
                    typedStr += isFollowedByVowelOrYorN ? 'nn' : 'n';
                } else {
                    typedStr += ROMAJI_MAP[k] ? ROMAJI_MAP[k][0] : k;
                }
            }
            typedStr += gameState.typedInToken;

            const defaultCurrentCandidate = candidates[0];
            const remainingInToken = defaultCurrentCandidate.substring(gameState.typedInToken.length);
            const currentExpectedKey = remainingInToken[0] || '';

            let untypedStr = remainingInToken.substring(1);
            for (let i = gameState.tokenIndex + 1; i < gameState.kanaTokens.length; i++) {
                const k = gameState.kanaTokens[i];
                if (k === 'っ') {
                    const nk = gameState.kanaTokens[i + 1];
                    untypedStr += (nk && ROMAJI_MAP[nk]) ? ROMAJI_MAP[nk][0][0] : 't';
                } else if (k === 'ん') {
                    const nk = gameState.kanaTokens[i + 1];
                    let isFollowedByVowelOrYorN = false;
                    if (nk && ROMAJI_MAP[nk]) {
                        const firstChars = ROMAJI_MAP[nk].map(r => r[0].toLowerCase());
                        isFollowedByVowelOrYorN = firstChars.some(c => ['a', 'i', 'u', 'e', 'o', 'y', 'n'].includes(c));
                    }
                    untypedStr += isFollowedByVowelOrYorN ? 'nn' : 'n';
                } else {
                    untypedStr += ROMAJI_MAP[k] ? ROMAJI_MAP[k][0] : k;
                }
            }

            document.getElementById('romaji-typed').textContent = typedStr;
            document.getElementById('romaji-current').textContent = currentExpectedKey;
            document.getElementById('romaji-untyped').textContent = untypedStr;

            highlightVirtualKey(currentExpectedKey);
        }

        function highlightVirtualKey(keyChar) {
            document.querySelectorAll('.kbd-key').forEach(el => {
                el.classList.remove('key-next');
            });
            if (!keyChar) return;
            const targetEl = document.querySelector(`.kbd-key[data-key="${keyChar.toLowerCase()}"]`);
            if (targetEl) {
                targetEl.classList.add('key-next');
            }
        }

        function setupKeyboardListeners() {
            window.addEventListener('keydown', (e) => {
                if (e.code === 'Space' && !gameState.isPlaying && !gameState.isCountingDown && !document.getElementById('start-screen').classList.contains('hidden')) {
                    e.preventDefault();
                    startGame();
                    return;
                }

                if (!gameState.isPlaying || gameState.isCountingDown) return;

                const pressedKey = e.key.toLowerCase();

                const keyEl = document.querySelector(`.kbd-key[data-key="${pressedKey}"]`);
                if (keyEl) {
                    keyEl.classList.add('key-active');
                    setTimeout(() => keyEl.classList.remove('key-active'), 120);
                }

                if (pressedKey.length !== 1 || e.ctrlKey || e.altKey || e.metaKey) return;

                gameState.totalTyped++;

                const nextTyped = gameState.typedInToken + pressedKey;
                const matchedCandidate = gameState.targetRomajiList.find(cand => cand.startsWith(nextTyped));

                if (matchedCandidate) {
                    sound.playType();
                    gameState.correctTyped++;
                    
                    gameState.score += 1;
                    document.getElementById('score-display').textContent = gameState.score;

                    gameState.typedInToken = nextTyped;

                    if (gameState.typedInToken === matchedCandidate) {
                        const completedKana = gameState.kanaTokens[gameState.tokenIndex];
                        gameState.correctKanaTyped += completedKana.length;

                        gameState.tokenIndex++;
                        gameState.typedInToken = '';
                    }

                    updateRomajiDisplay();
                } else {
                    sound.playMiss();
                    gameState.missTyped++;
                    
                    const card = document.getElementById('word-card');
                    card.classList.add('shake');
                    setTimeout(() => card.classList.remove('shake'), 250);
                }

                const acc = Math.round((gameState.correctTyped / gameState.totalTyped) * 100);
                document.getElementById('accuracy-display').textContent = acc;
            });
        }

        function initBackgroundParticles() {
            const canvas = document.getElementById('bg-canvas');
            const ctx = canvas.getContext('2d');
            let width = (canvas.width = window.innerWidth);
            let height = (canvas.height = window.innerHeight);

            window.addEventListener('resize', () => {
                width = canvas.width = window.innerWidth;
                height = canvas.height = window.innerHeight;
            });

            const particles = Array.from({ length: 45 }, () => ({
                x: Math.random() * width,
                y: Math.random() * height,
                radius: Math.random() * 2 + 1,
                vx: (Math.random() - 0.5) * 0.4,
                vy: (Math.random() - 0.5) * 0.4,
                alpha: Math.random() * 0.4 + 0.1
            }));

            function animate() {
                ctx.clearRect(0, 0, width, height);

                particles.forEach(p => {
                    p.x += p.vx;
                    p.y += p.vy;

                    if (p.x < 0) p.x = width;
                    if (p.x > width) p.x = 0;
                    if (p.y < 0) p.y = height;
                    if (p.y > height) p.y = 0;

                    ctx.beginPath();
                    ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
                    ctx.fillStyle = `rgba(14, 165, 233, ${p.alpha})`;
                    ctx.fill();
                });

                for (let i = confettiParticles.length - 1; i >= 0; i--) {
                    const c = confettiParticles[i];
                    c.vx *= c.drag;
                    c.vy *= c.drag;
                    c.vy += c.gravity;
                    c.x += c.vx;
                    c.y += c.vy;
                    c.rotation += c.vRot;

                    ctx.save();
                    ctx.translate(c.x, c.y);
                    ctx.rotate((c.rotation * Math.PI) / 180);
                    ctx.fillStyle = c.color;
                    ctx.fillRect(-c.width / 2, -c.height / 2, c.width, c.height);
                    ctx.restore();

                    if (c.y > height + 50) {
                        confettiParticles.splice(i, 1);
                    }
                }

                requestAnimationFrame(animate);
            }
            animate();
        }
    </script>
</body>
</html>
