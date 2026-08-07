<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>日本語タイピングマスター (Japanese Typing Master)</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
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
            background: rgba(255, 255, 255, 0.92);
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

        /* くす玉アニメーション */
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
        .kusudama-left { left: 10px; }
        .kusudama-right {
            right: 10px;
            border-radius: 0 70px 70px 0;
            background: linear-gradient(225deg, #f59e0b, #ef4444);
        }
        .kusudama-open .kusudama-left { transform: rotate(-48deg) translate(-20px, -8px); }
        .kusudama-open .kusudama-right { transform: rotate(48deg) translate(20px, -8px); }
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
            height: 42px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: #ffffff;
            border: 1px solid #cbd5e1;
            border-bottom-width: 3px;
            border-radius: 8px;
            color: #334155;
            font-weight: 700;
            transition: all 0.1s ease;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between overflow-x-hidden relative">

    <canvas id="bg-canvas" class="fixed top-0 left-0 w-full h-full -z-10 pointer-events-none"></canvas>

    <header class="w-full p-4 flex justify-between items-center glass-panel z-20">
        <div class="flex items-center space-x-3">
            <i class="fa-solid fa-keyboard text-3xl text-sky-600"></i>
            <h1 class="text-xl md:text-2xl font-black tracking-wider text-transparent bg-clip-text bg-gradient-to-r from-sky-600 to-indigo-600">
                タイピング MASTER
            </h1>
            <span id="course-count-badge" class="bg-indigo-100 text-indigo-700 text-xs px-2.5 py-1 rounded-full font-extrabold border border-indigo-200 flex items-center gap-1 shadow-sm">
                <i class="fa-solid fa-layer-group text-indigo-500"></i>全 <span id="total-course-count">0</span> コース
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
        
        <div id="start-screen" class="w-full max-w-4xl glass-panel rounded-3xl p-6 md:p-8 shadow-xl text-center space-y-6 my-4">
            <div>
                <h2 class="text-3xl md:text-4xl font-extrabold text-slate-800">タイピング練習ゲーム</h2>
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

            <!-- コース選択グループ (カテゴリ別) -->
            <div class="space-y-5 text-left max-h-[55vh] overflow-y-auto pr-2">
                <div>
                    <!-- 1. 小学校のきょうか・学校 -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-graduation-cap text-indigo-600 mr-1"></i> 1. 小学校のきょうか・学校</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="japanese" class="course-btn p-2.5 rounded-xl border border-sky-500 bg-sky-50 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-book mr-1"></i>国語</div></button>
                        <button data-course="math" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-calculator mr-1"></i>算数</div></button>
                        <button data-course="science" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-flask mr-1"></i>理科</div></button>
                        <button data-course="social" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-earth-americas mr-1"></i>社会</div></button>
                        <button data-course="history_people" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-user-ninja mr-1"></i>歴史の人物</div></button>
                        <button data-course="music" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-600"><i class="fa-solid fa-music mr-1"></i>音楽</div></button>
                        <button data-course="art" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-500"><i class="fa-solid fa-palette mr-1"></i>図工</div></button>
                        <button data-course="pe" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-person-running mr-1"></i>体育</div></button>
                        <button data-course="school_items" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-700"><i class="fa-solid fa-school mr-1"></i>学校にある物</div></button>
                        <button data-course="school_lunch" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700"><i class="fa-solid fa-utensils mr-1"></i>学校給食</div></button>
                    </div>

                    <!-- 2. 地理・観光・世界 -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-globe text-sky-600 mr-1"></i> 2. 地理・観光・世界</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2 mb-4">
                        <button data-course="prefectures" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-600"><i class="fa-solid fa-map-pin mr-1"></i>都道府県</div></button>
                        <button data-course="prefectural_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-building-flag mr-1"></i>県庁所在地</div></button>
                        <button data-course="mountains" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-mountain mr-1"></i>日本の山</div></button>
                        <button data-course="rivers" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-600"><i class="fa-solid fa-water mr-1"></i>日本の川</div></button>
                        <button data-course="lakes" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-water-ladder mr-1"></i>日本の湖</div></button>
                        <button data-course="hot_springs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-hot-tub-person mr-1"></i>日本の温泉</div></button>
                        <button data-course="japan_sightseeing" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-600"><i class="fa-solid fa-torii-gate mr-1"></i>日本の観光地</div></button>
                        <button data-course="world_heritage" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-700"><i class="fa-solid fa-landmark mr-1"></i>世界遺産</div></button>
                        <button data-course="world_sightseeing" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-700"><i class="fa-solid fa-monument mr-1"></i>世界の観光地</div></button>
                        <button data-course="us_states" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-700"><i class="fa-solid fa-flag-usa mr-1"></i>アメリカの州</div></button>
                        <button data-course="asia_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-earth-asia mr-1"></i>アジアの国</div></button>
                        <button data-course="europe_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-earth-europe mr-1"></i>ヨーロッパの国</div></button>
                        <button data-course="americas_oceania_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-earth-americas mr-1"></i>北米・南米・オセアニア</div></button>
                        <button data-course="africa_countries" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-600"><i class="fa-solid fa-earth-africa mr-1"></i>アフリカの国</div></button>
                        <button data-course="asia_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-building-columns mr-1"></i>アジアの首都</div></button>
                        <button data-course="europe_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-landmark mr-1"></i>ヨーロッパの首都</div></button>
                        <button data-course="americas_oceania_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-monument mr-1"></i>米州・オセアニア首都</div></button>
                        <button data-course="africa_capitals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-600"><i class="fa-solid fa-archway mr-1"></i>アフリカの首都</div></button>
                    </div>

                    <!-- 3. 歴史・人物・伝統 -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-scroll text-amber-800 mr-1"></i> 3. 歴史・人物・伝統</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="sengoku" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-700"><i class="fa-solid fa-user-ninja mr-1"></i>戦国武将</div></button>
                        <button data-course="sangokushi" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-800"><i class="fa-solid fa-dragon mr-1"></i>三国志の武将</div></button>
                        <button data-course="pm_japan" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-800"><i class="fa-solid fa-building-user mr-1"></i>歴代の総理大臣</div></button>
                        <button data-course="us_presidents" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-flag-usa mr-1"></i>アメリカ大統領</div></button>
                        <button data-course="world_history_people" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-globe mr-1"></i>世界史の有名人</div></button>
                        <button data-course="famous_battles" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-burst mr-1"></i>歴史上の戦い</div></button>
                        <button data-course="mythology_figures" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-bolt-lightning mr-1"></i>神話の人物</div></button>
                        <button data-course="haiku" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-feather mr-1"></i>俳句</div></button>
                        <button data-course="hyakunin" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-700"><i class="fa-solid fa-scroll mr-1"></i>百人一首</div></button>
                        <button data-course="sumo" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-900"><i class="fa-solid fa-hand-rock mr-1"></i>相撲の決まり手</div></button>
                    </div>

                    <!-- 4. たべもの・お茶・スイーツ -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-utensils text-rose-500 mr-1"></i> 4. たべもの・お茶・スイーツ</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="sushi" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-500"><i class="fa-solid fa-fish mr-1"></i>おすしのメニュー</div></button>
                        <button data-course="japanese_food" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-bowl-rice mr-1"></i>日本料理</div></button>
                        <button data-course="chinese_food" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-bowl-food mr-1"></i>中華料理</div></button>
                        <button data-course="world_food" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-earth-americas mr-1"></i>世界の料理</div></button>
                        <button data-course="ramen_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-bowl-rice mr-1"></i>ラーメンの種類</div></button>
                        <button data-course="sweets" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-500"><i class="fa-solid fa-ice-cream mr-1"></i>スイーツ</div></button>
                        <button data-course="vegetables" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-carrot mr-1"></i>やさい</div></button>
                        <button data-course="fruits" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-500"><i class="fa-solid fa-apple-whole mr-1"></i>くだもの</div></button>
                        <button data-course="tea_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-mug-hot mr-1"></i>世界のお茶</div></button>
                        <button data-course="cheese_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-yellow-600"><i class="fa-solid fa-cheese mr-1"></i>チーズの種類</div></button>
                    </div>

                    <!-- 5. 生きもの・植物・自然 -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-hippo text-emerald-600 mr-1"></i> 5. 生きもの・植物・自然</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2 mb-4">
                        <button data-course="animals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-hippo mr-1"></i>動物</div></button>
                        <button data-course="dog_breeds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700"><i class="fa-solid fa-dog mr-1"></i>犬の種類</div></button>
                        <button data-course="cat_breeds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-600"><i class="fa-solid fa-cat mr-1"></i>ネコの種類</div></button>
                        <button data-course="birds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-600"><i class="fa-solid fa-crow mr-1"></i>鳥</div></button>
                        <button data-course="insects" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-lime-700"><i class="fa-solid fa-bug mr-1"></i>昆虫</div></button>
                        <button data-course="ocean_fish" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-fish-fins mr-1"></i>海の魚</div></button>
                        <button data-course="river_fish" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-water mr-1"></i>川の魚</div></button>
                        <button data-course="dinosaurs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-dragon mr-1"></i>恐竜</div></button>
                        <button data-course="flowers" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-500"><i class="fa-solid fa-seedling mr-1"></i>花の名前</div></button>
                        <button data-course="trees" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-700"><i class="fa-solid fa-tree mr-1"></i>木の名前</div></button>
                        <button data-course="cloud_types" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-sky-600"><i class="fa-solid fa-cloud mr-1"></i>雲の種類</div></button>
                    </div>

                    <!-- 6. 体・健康・科学 -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-heart-pulse text-pink-600 mr-1"></i> 6. 体・健康・科学</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 mb-4">
                        <button data-course="body_parts" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-700"><i class="fa-solid fa-child mr-1"></i>体の部分の名前</div></button>
                        <button data-course="body_organs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-heart mr-1"></i>体の中にあるもの</div></button>
                        <button data-course="human_bones" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-slate-700"><i class="fa-solid fa-bone mr-1"></i>人間の骨の名前</div></button>
                        <button data-course="diseases" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-600"><i class="fa-solid fa-notes-medical mr-1"></i>病気の名前</div></button>
                        <button data-course="elements" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-700"><i class="fa-solid fa-atom mr-1"></i>元素記号の名前</div></button>
                    </div>

                    <!-- 7. 乗り物・スポーツ・趣味 -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-car-side text-blue-600 mr-1"></i> 7. 乗り物・スポーツ・趣味</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2 mb-4">
                        <button data-course="kanto_trains" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-700"><i class="fa-solid fa-train mr-1"></i>関東の電車路線</div></button>
                        <button data-course="car_models" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-slate-800"><i class="fa-solid fa-car mr-1"></i>車種の名前</div></button>
                        <button data-course="sports_names" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-person-running mr-1"></i>スポーツの名前</div></button>
                        <button data-course="sports_equipment" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-baseball mr-1"></i>スポーツの道具</div></button>
                        <button data-course="musicians" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600"><i class="fa-solid fa-music mr-1"></i>音楽家</div></button>
                        <button data-course="shogi_terms" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-800"><i class="fa-solid fa-chess-board mr-1"></i>将棋のことば・駒</div></button>
                        <button data-course="toys" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-orange-500"><i class="fa-solid fa-gamepad mr-1"></i>おもちゃ</div></button>
                        <button data-course="professions" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600"><i class="fa-solid fa-user-tie mr-1"></i>職業の名前</div></button>
                        <button data-course="pc_terms" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-desktop mr-1"></i>パソコンのことば</div></button>
                        <button data-course="it" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-600"><i class="fa-solid fa-laptop-code mr-1"></i>IT用語・カタカナ</div></button>
                        <button data-course="household_items" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-house mr-1"></i>家にあるもの</div></button>
                    </div>

                    <!-- 8. ことば・テーマ・季節 -->
                    <label class="block text-xs font-bold text-slate-500 uppercase tracking-wider mb-2"><i class="fa-solid fa-book-open text-purple-600 mr-1"></i> 8. ことば・テーマ・季節</label>
                    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2" id="course-selector">
                        <button data-course="words" class="course-btn p-2.5 rounded-xl border border-sky-500 bg-sky-50 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600">単語</div></button>
                        <button data-course="greetings" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600">あいさつ</div></button>
                        <button data-course="medium" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-sky-600">日常会話・短文</div></button>
                        <button data-course="proverbs" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600">ことわざ</div></button>
                        <button data-course="yojijukugo" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600">四字熟語</div></button>
                        <button data-course="praise" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-yellow-600"><i class="fa-solid fa-thumbs-up mr-1"></i>ほめことば</div></button>
                        <button data-course="onomatopoeia" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600"><i class="fa-solid fa-wand-magic-sparkles mr-1"></i>オノマトペ</div></button>
                        <button data-course="animal_sounds" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-teal-600"><i class="fa-solid fa-paw mr-1"></i>動物のなきごえ</div></button>
                        <button data-course="radicals" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-red-600"><i class="fa-solid fa-font mr-1"></i>部首の名前</div></button>
                        <button data-course="nandoku_kanji" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-700"><i class="fa-solid fa-font mr-1"></i>難読漢字</div></button>
                        <button data-course="keigo" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700"><i class="fa-solid fa-comments mr-1"></i>敬語</div></button>
                        <button data-course="traditional_colors" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-purple-600"><i class="fa-solid fa-paint-brush mr-1"></i>日本の伝統色</div></button>
                        <button data-course="japanese_holidays" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-rose-600"><i class="fa-solid fa-calendar-day mr-1"></i>日本の祝日</div></button>
                        <button data-course="constellations" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-indigo-600"><i class="fa-solid fa-star mr-1"></i>星座の名前</div></button>
                        <button data-course="world_currencies" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-emerald-600"><i class="fa-solid fa-money-bill-wave mr-1"></i>世界のお金の単位</div></button>
                        <button data-course="spring" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-pink-600">春のもの</div></button>
                        <button data-course="summer" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-blue-600">夏のもの</div></button>
                        <button data-course="autumn" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-amber-700">秋のもの</div></button>
                        <button data-course="winter" class="course-btn p-2.5 rounded-xl border border-slate-300 bg-white hover:border-sky-500 transition-all text-center shadow-sm"><div class="font-bold text-xs sm:text-sm text-cyan-600">冬のもの</div></button>
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

        <div id="play-screen" class="hidden w-full max-w-3xl glass-panel rounded-3xl p-6 md:p-8 shadow-xl space-y-6">
            
            <!-- Dashboard Info Header with Return & Retry Buttons -->
            <div class="flex justify-between items-center bg-white/80 px-4 md:px-6 py-3 rounded-2xl border border-slate-200 shadow-sm gap-2 flex-wrap sm:flex-nowrap">
                <div class="flex items-center space-x-2">
                    <button id="ingame-back-btn" title="トップへ戻る" class="px-3 py-1.5 rounded-xl bg-slate-100 hover:bg-slate-200 border border-slate-300 text-xs font-bold text-slate-700 flex items-center space-x-1.5 transition-all shadow-sm">
                        <i class="fa-solid fa-house text-sky-600"></i>
                        <span>もどる</span>
                    </button>
                    <button id="ingame-retry-btn" title="最初からやり直す" class="px-3 py-1.5 rounded-xl bg-slate-100 hover:bg-slate-200 border border-slate-300 text-xs font-bold text-amber-700 flex items-center space-x-1.5 transition-all shadow-sm">
                        <i class="fa-solid fa-rotate-left text-amber-500"></i>
                        <span>もう１回</span>
                    </button>
                </div>

                <div class="text-center">
                    <span class="text-xs text-slate-500 font-bold block">残り時間</span>
                    <span id="timer-display" class="text-2xl md:text-3xl font-black text-amber-600 font-mono-custom">60</span><span class="text-xs text-slate-500">s</span>
                </div>
                <div class="text-center">
                    <span class="text-xs text-slate-500 font-bold block">スコア</span>
                    <span id="score-display" class="text-2xl md:text-3xl font-black text-sky-600 font-mono-custom">0</span>
                </div>
                <div class="text-center">
                    <span class="text-xs text-slate-500 font-bold block">正確率</span>
                    <span id="accuracy-display" class="text-2xl md:text-3xl font-black text-emerald-600 font-mono-custom">100</span><span class="text-xs text-slate-500">%</span>
                </div>
                
                <button id="ingame-ruby-btn" title="ふりがな切替" class="px-3 py-1.5 rounded-xl bg-slate-100 hover:bg-slate-200 border border-slate-300 text-xs font-bold text-sky-700 flex items-center space-x-1.5 transition-all">
                    <i class="fa-solid fa-eye"></i>
                    <span id="ingame-ruby-text">ルビ: ON</span>
                </button>
            </div>

            <div id="word-card" class="bg-white border-2 border-slate-200 rounded-3xl p-8 text-center space-y-4 shadow-sm relative overflow-hidden min-h-[180px] flex flex-col justify-center">
                <div id="word-display" class="text-3xl md:text-5xl font-black text-slate-800 tracking-wide leading-relaxed">
                </div>
                <div id="kana-display" class="text-base md:text-xl font-bold text-slate-500 tracking-wider">
                </div>
                <div id="romaji-container" class="font-mono-custom text-xl md:text-3xl tracking-wider pt-2 border-t border-slate-200">
                    <span id="romaji-typed" class="text-sky-600 font-bold"></span><span id="romaji-current" class="text-amber-600 font-black underline bg-amber-100 px-1 rounded"></span><span id="romaji-untyped" class="text-slate-400"></span>
                </div>
            </div>

            <div class="space-y-1.5 bg-white/70 p-3 md:p-4 rounded-2xl border border-slate-200 text-xs font-mono-custom shadow-sm">
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

        // 配列をシャッフルするヘルパー関数 (Fisher-Yates)
        function shuffleArray(array) {
            if (!array || !Array.isArray(array)) return [];
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
        }
        const sound = new SoundEngine();

        const WORD_DATA = {
            japanese: [
                { rubyTokens: [{text: '漢字', ruby: 'かんじ'}], kana: 'かんじ' },
                { rubyTokens: [{text: '仮名', ruby: 'かな'}], kana: 'かな' },
                { rubyTokens: [{text: '音読', ruby: 'おんどく'}], kana: 'おんどく' },
                { rubyTokens: [{text: '朗読', ruby: 'ろうどく'}], kana: 'ろうどく' },
                { rubyTokens: [{text: '段落', ruby: 'だんらく'}], kana: 'だんらく' },
                { rubyTokens: [{text: '主語', ruby: 'しゅご'}], kana: 'しゅご' },
                { rubyTokens: [{text: '述語', ruby: 'じゅつご'}], kana: 'じゅつご' },
                { rubyTokens: [{text: '修飾語', ruby: 'しゅうしょくご'}], kana: 'しゅうしょくご' },
                { rubyTokens: [{text: '接続詞', ruby: 'せつぞくし'}], kana: 'せつぞくし' },
                { rubyTokens: [{text: '感動詞', ruby: 'かんどうし'}], kana: 'かんどうし' }
            ],
            math: [
                { rubyTokens: [{text: 'たし算', ruby: 'たしざん'}], kana: 'たしざん' },
                { rubyTokens: [{text: 'ひき算', ruby: 'ひきざん'}], kana: 'ひきざん' },
                { rubyTokens: [{text: 'かけ算', ruby: 'かけざん'}], kana: 'かけざん' },
                { rubyTokens: [{text: 'わり算', ruby: 'わりざん'}], kana: 'わりざん' },
                { rubyTokens: [{text: '九九', ruby: 'くく'}], kana: 'くく' },
                { rubyTokens: [{text: '三角形', ruby: 'さんかくけい'}], kana: 'さんかくけい' },
                { rubyTokens: [{text: '四角形', ruby: 'しかくけい'}], kana: 'しかくけい' },
                { rubyTokens: [{text: '円周率', ruby: 'えんしゅうりつ'}], kana: 'えんしゅうりつ' }
            ],
            science: [
                { rubyTokens: [{text: '光合成', ruby: 'こうごうせい'}], kana: 'こうごうせい' },
                { rubyTokens: [{text: '水溶液', ruby: 'すいようえき'}], kana: 'すいようえき' },
                { rubyTokens: [{text: '酸性', ruby: 'さんせい'}], kana: 'さんせい' },
                { rubyTokens: [{text: 'アルカリ性', ruby: 'あるかりせい'}], kana: 'あるかりせい' },
                { rubyTokens: [{text: '顕微鏡', ruby: 'けんびきょう'}], kana: 'けんびきょう' }
            ],
            social: [
                { rubyTokens: [{text: '日本列島', ruby: 'にほんれっとう'}], kana: 'にほんれっとう' },
                { rubyTokens: [{text: '都道府県', ruby: 'とどうふけん'}], kana: 'とどうふけん' },
                { rubyTokens: [{text: '県庁所在地', ruby: 'けんちょうしょざいち'}], kana: 'けんちょうしょざいち' },
                { rubyTokens: [{text: '縄文時代', ruby: 'じょうもんじだい'}], kana: 'じょうもんじだい' }
            ],
            history_people: [
                { rubyTokens: [{text: '卑弥呼', ruby: 'ひみこ'}], kana: 'ひみこ' },
                { rubyTokens: [{text: '聖徳太子', ruby: 'しょうとくたいし'}], kana: 'しょうとくたいし' },
                { rubyTokens: [{text: '織田信長', ruby: 'おだのぶなが'}], kana: 'おだのぶなが' },
                { rubyTokens: [{text: '豊臣秀吉', ruby: 'とよとみひでよし'}], kana: 'とよとみひでよし' },
                { rubyTokens: [{text: '徳川家康', ruby: 'とくがわいえやす'}], kana: 'とくがわいえやす' }
            ],
            music: [
                { rubyTokens: [{text: 'リコーダー'}], kana: 'りこーだー' },
                { rubyTokens: [{text: '鍵盤ハーモニカ', ruby: 'けんばんはーもにか'}], kana: 'けんばんはーもにか' },
                { rubyTokens: [{text: '木琴', ruby: 'もっきん'}], kana: 'もっきん' },
                { rubyTokens: [{text: '鉄琴', ruby: 'てっきん'}], kana: 'てっきん' }
            ],
            art: [
                { rubyTokens: [{text: '水彩絵の具', ruby: 'すいさいえのぐ'}], kana: 'すいさいえのぐ' },
                { rubyTokens: [{text: '彫刻刀', ruby: 'ちょうこくとう'}], kana: 'ちょうこくとう' },
                { rubyTokens: [{text: '版画', ruby: 'はんが'}], kana: 'はんが' }
            ],
            pe: [
                { rubyTokens: [{text: '準備運動', ruby: 'じゅんびうんどう'}], kana: 'じゅんびうんどう' },
                { rubyTokens: [{text: '50メートル走', ruby: 'ごじゅうめーとるそう'}], kana: 'ごじゅうめーとるそう' },
                { rubyTokens: [{text: '跳び箱', ruby: 'とびばこ'}], kana: 'とびばこ' }
            ],
            school_items: [
                { rubyTokens: [{text: '黒板', ruby: 'こくばん'}], kana: 'こくばん' },
                { rubyTokens: [{text: 'チョーク'}], kana: 'ちょーく' },
                { rubyTokens: [{text: 'ランドセル'}], kana: 'らんどせる' }
            ],
            school_lunch: [
                { rubyTokens: [{text: '揚げパン', ruby: 'あげぱん'}], kana: 'あげぱん' },
                { rubyTokens: [{text: 'カレーライス'}], kana: 'かれーらいす' },
                { rubyTokens: [{text: 'ソフト麺', ruby: 'そふとめん'}], kana: 'そふとめん' }
            ],
            prefectures: [
                { rubyTokens: [{text: '北海道', ruby: 'ほっかいどう'}], kana: 'ほっかいどう' },
                { rubyTokens: [{text: '東京都', ruby: 'とうきょうと'}], kana: 'とうきょうと' },
                { rubyTokens: [{text: '大阪府', ruby: 'おおさかふ'}], kana: 'おおさかふ' }
            ],
            prefectural_capitals: [
                { rubyTokens: [{text: '札幌市', ruby: 'さっぽろし'}], kana: 'さっぽろし' },
                { rubyTokens: [{text: '横浜市', ruby: 'よこはまし'}], kana: 'よこはまし' },
                { rubyTokens: [{text: '名古屋市', ruby: 'なごやし'}], kana: 'なごやし' }
            ],
            mountains: [
                { rubyTokens: [{text: '富士山', ruby: 'ふじさん'}], kana: 'ふじさん' },
                { rubyTokens: [{text: '北岳', ruby: 'きただけ'}], kana: 'きただけ' }
            ],
            rivers: [
                { rubyTokens: [{text: '信濃川', ruby: 'しなのがわ'}], kana: 'しなのがわ' },
                { rubyTokens: [{text: '利根川', ruby: 'とねがわ'}], kana: 'とねがわ' }
            ],
            lakes: [
                { rubyTokens: [{text: '琵琶湖', ruby: 'びわこ'}], kana: 'びわこ' },
                { rubyTokens: [{text: '霞ヶ浦', ruby: 'かすみがうら'}], kana: 'かすみがうら' }
            ],
            hot_springs: [
                { rubyTokens: [{text: '草津温泉', ruby: 'くさつおんせん'}], kana: 'くさつおんせん' },
                { rubyTokens: [{text: '箱根温泉', ruby: 'はこねおんせん'}], kana: 'はこねおんせん' }
            ],
            japan_sightseeing: [
                { rubyTokens: [{text: '東京スカイツリー', ruby: 'とうきょうすかいつりー'}], kana: 'とうきょうすかいつりー' },
                { rubyTokens: [{text: '金閣寺', ruby: 'きんかくじ'}], kana: 'きんかくじ' }
            ],
            world_heritage: [
                { rubyTokens: [{text: '姫路城', ruby: 'ひめじじょう'}], kana: 'ひめじじょう' },
                { rubyTokens: [{text: '屋久島', ruby: 'やくしま'}], kana: 'やくしま' }
            ],
            world_sightseeing: [
                { rubyTokens: [{text: 'エッフェル塔', ruby: 'えっふぇるとう'}], kana: 'えっふぇるとう' },
                { rubyTokens: [{text: 'ピラミッド'}], kana: 'ぴらみっど' }
            ],
            us_states: [
                { rubyTokens: [{text: 'カリフォルニア州', ruby: 'かりふぉるにあしゅう'}], kana: 'かりふぉるにあしゅう' },
                { rubyTokens: [{text: 'ニューヨーク州', ruby: 'にゅーよーくしゅう'}], kana: 'にゅーよーくしゅう' }
            ],
            asia_countries: [
                { rubyTokens: [{text: '日本', ruby: 'にほん'}], kana: 'にほん' },
                { rubyTokens: [{text: '韓国', ruby: 'かんこく'}], kana: 'かんこく' }
            ],
            europe_countries: [
                { rubyTokens: [{text: 'イギリス'}], kana: 'いぎりす' },
                { rubyTokens: [{text: 'フランス'}], kana: 'ふらんす' }
            ],
            americas_oceania_countries: [
                { rubyTokens: [{text: 'アメリカ'}], kana: 'あめりか' },
                { rubyTokens: [{text: 'カナダ'}], kana: 'かなだ' }
            ],
            africa_countries: [
                { rubyTokens: [{text: 'エジプト'}], kana: 'えじぷと' },
                { rubyTokens: [{text: 'ケニア'}], kana: 'けにあ' }
            ],
            asia_capitals: [
                { rubyTokens: [{text: '東京', ruby: 'とうきょう'}], kana: 'とうきょう' },
                { rubyTokens: [{text: 'ソウル'}], kana: 'そうる' }
            ],
            europe_capitals: [
                { rubyTokens: [{text: 'ロンドン'}], kana: 'ろんどん' },
                { rubyTokens: [{text: 'パリ'}], kana: 'ぱり' }
            ],
            americas_oceania_capitals: [
                { rubyTokens: [{text: 'ワシントン'}], kana: 'わしんとん' },
                { rubyTokens: [{text: 'オタワ'}], kana: 'おたわ' }
            ],
            africa_capitals: [
                { rubyTokens: [{text: 'カイロ'}], kana: 'かいろ' },
                { rubyTokens: [{text: 'ナイロビ'}], kana: 'ないろび' }
            ],
            sengoku: [
                { rubyTokens: [{text: '武田信玄', ruby: 'たけだしんげん'}], kana: 'たけだしんげん' },
                { rubyTokens: [{text: '上杉謙信', ruby: 'うえすぎけんしん'}], kana: 'うえすぎけんしん' }
            ],
            sangokushi: [
                { rubyTokens: [{text: '劉備', ruby: 'りゅうび'}], kana: 'りゅうび' },
                { rubyTokens: [{text: '関羽', ruby: 'かんう'}], kana: 'かんう' }
            ],
            pm_japan: [
                { rubyTokens: [{text: '伊藤博文', ruby: 'いとうひろぶみ'}], kana: 'いとうひろぶみ' },
                { rubyTokens: [{text: '吉田茂', ruby: 'よしだしげる'}], kana: 'よしだしげる' }
            ],
            us_presidents: [
                { rubyTokens: [{text: 'ワシントン'}], kana: 'わしんとん' },
                { rubyTokens: [{text: 'リンカーン'}], kana: 'りんかーん' }
            ],
            world_history_people: [
                { rubyTokens: [{text: 'ナポレオン'}], kana: 'なぽれおん' },
                { rubyTokens: [{text: 'アインシュタイン'}], kana: 'あいんしゅたいん' }
            ],
            famous_battles: [
                { rubyTokens: [{text: '関ヶ原の戦い', ruby: 'せきがはらのたたかい'}], kana: 'せきがはらのたたかい' }
            ],
            mythology_figures: [
                { rubyTokens: [{text: 'ゼウス'}], kana: 'ぜうす' },
                { rubyTokens: [{text: 'ポセイドン'}], kana: 'ぽせいどん' }
            ],
            haiku: [
                { rubyTokens: [{text: '古池や', ruby: 'ふるいけや'}, {text: '蛙飛びこむ', ruby: 'かわずとびこむ'}, {text: '水の音', ruby: 'みずのおと'}], kana: 'ふるいけやかわずとびこむみずのおと' }
            ],
            hyakunin: [
                { rubyTokens: [{text: '秋の田の', ruby: 'あきのたの'}, {text: 'かりほの庵の', ruby: 'かりほのいおの'}, {text: '苫をあらみ', ruby: 'とまをおらみ'}], kana: 'あきのたのかりほのいおのとまをおらみ' }
            ],
            sumo: [
                { rubyTokens: [{text: '寄り切り', ruby: 'よりきり'}], kana: 'よりきり' },
                { rubyTokens: [{text: '押し出し', ruby: 'おしだし'}], kana: 'おしだし' }
            ],
            sushi: [
                { rubyTokens: [{text: '赤身', ruby: 'あかみ'}], kana: 'あかみ' },
                { rubyTokens: [{text: 'サーモン'}], kana: 'さーもん' },
                { rubyTokens: [{text: 'イクラ'}], kana: 'いくら' }
            ],
            japanese_food: [
                { rubyTokens: [{text: '寿司', ruby: 'すし'}], kana: 'すし' },
                { rubyTokens: [{text: '天ぷら', ruby: 'てんぷら'}], kana: 'てんぷら' }
            ],
            chinese_food: [
                { rubyTokens: [{text: '餃子', ruby: 'ぎょうざ'}], kana: 'ぎょうざ' },
                { rubyTokens: [{text: '炒飯', ruby: 'ちゃーはん'}], kana: 'ちゃーはん' }
            ],
            world_food: [
                { rubyTokens: [{text: 'パスタ'}], kana: 'ぱすた' },
                { rubyTokens: [{text: 'ピザ'}], kana: 'ぴざ' }
            ],
            ramen_types: [
                { rubyTokens: [{text: '醤油ラーメン', ruby: 'しょうゆらーめん'}], kana: 'しょうゆらーめん' },
                { rubyTokens: [{text: '味噌ラーメン', ruby: 'みそらーめん'}], kana: 'みそらーめん' }
            ],
            sweets: [
                { rubyTokens: [{text: 'ショートケーキ'}], kana: 'しょーとけーき' },
                { rubyTokens: [{text: 'プリン'}], kana: 'ぷりん' }
            ],
            vegetables: [
                { rubyTokens: [{text: 'トマト'}], kana: 'とまと' },
                { rubyTokens: [{text: '大根', ruby: 'だいこん'}], kana: 'だいこん' }
            ],
            fruits: [
                { rubyTokens: [{text: '林檎', ruby: 'りんご'}], kana: 'りんご' },
                { rubyTokens: [{text: '苺', ruby: 'いちご'}], kana: 'いちご' }
            ],
            tea_types: [
                { rubyTokens: [{text: '煎茶', ruby: 'せんちゃ'}], kana: 'せんちゃ' },
                { rubyTokens: [{text: '抹茶', ruby: 'まっちゃ'}], kana: 'まっちゃ' },
                { rubyTokens: [{text: '黄茶', ruby: 'きちゃ'}], kana: 'きちゃ' }
            ],
            cheese_types: [
                { rubyTokens: [{text: 'チェダー'}], kana: 'ちぇだー' },
                { rubyTokens: [{text: 'モッツァレラ'}], kana: 'もっつぁれら' }
            ],
            animals: [
                { rubyTokens: [{text: 'ライオン'}], kana: 'らいおん' },
                { rubyTokens: [{text: 'パンダ'}], kana: 'ぱんだ' }
            ],
            dog_breeds: [
                { rubyTokens: [{text: '柴犬', ruby: 'しばいぬ'}], kana: 'しばいぬ' },
                { rubyTokens: [{text: 'トイプードル'}], kana: 'といぷーどる' }
            ],
            cat_breeds: [
                { rubyTokens: [{text: 'マンチカン'}], kana: 'まんちかん' },
                { rubyTokens: [{text: 'ラグドール'}], kana: 'らぐどーる' }
            ],
            birds: [
                { rubyTokens: [{text: '雀', ruby: 'すずめ'}], kana: 'すずめ' },
                { rubyTokens: [{text: 'ペンギン'}], kana: 'ぺんぎん' }
            ],
            insects: [
                { rubyTokens: [{text: 'カブトムシ'}], kana: 'かぶとむし' },
                { rubyTokens: [{text: 'トンボ'}], kana: 'とんぼ' }
            ],
            ocean_fish: [
                { rubyTokens: [{text: 'マグロ'}], kana: 'まぐろ' },
                { rubyTokens: [{text: 'サケ'}], kana: 'さけ' }
            ],
            river_fish: [
                { rubyTokens: [{text: 'アユ'}], kana: 'あゆ' },
                { rubyTokens: [{text: 'ヤマメ'}], kana: 'やまめ' }
            ],
            dinosaurs: [
                { rubyTokens: [{text: 'ティラノサウルス'}], kana: 'てぃらのさうるす' },
                { rubyTokens: [{text: 'トリケラトプス'}], kana: 'とりけらとぷす' }
            ],
            flowers: [
                { rubyTokens: [{text: '桜', ruby: 'さくら'}], kana: 'さくら' },
                { rubyTokens: [{text: '向日葵', ruby: 'ひまわり'}], kana: 'ひまわり' }
            ],
            trees: [
                { rubyTokens: [{text: '杉', ruby: 'すぎ'}], kana: 'すぎ' },
                { rubyTokens: [{text: '松', ruby: 'まつ'}], kana: 'まつ' }
            ],
            cloud_types: [
                { rubyTokens: [{text: '積乱雲', ruby: 'せきらんうん'}], kana: 'せきらんうん' },
                { rubyTokens: [{text: 'うろこ雲', ruby: 'うろこぐも'}], kana: 'うろこぐも' }
            ],
            body_parts: [
                { rubyTokens: [{text: '頭', ruby: 'あたま'}], kana: 'あたま' },
                { rubyTokens: [{text: '目', ruby: 'め'}], kana: 'め' }
            ],
            body_organs: [
                { rubyTokens: [{text: '心臓', ruby: 'しんぞう'}], kana: 'しんぞう' },
                { rubyTokens: [{text: '肺', ruby: 'はい'}], kana: 'はい' }
            ],
            human_bones: [
                { rubyTokens: [{text: '鎖骨', ruby: 'さこつ'}], kana: 'さこつ' },
                { rubyTokens: [{text: '大腿骨', ruby: 'だいたいこつ'}], kana: 'だいたいこつ' }
            ],
            diseases: [
                { rubyTokens: [{text: '風邪', ruby: 'かぜ'}], kana: 'かぜ' },
                { rubyTokens: [{text: 'インフルエンザ'}], kana: 'いんふるえんざ' }
            ],
            elements: [
                { rubyTokens: [{text: '水素', ruby: 'すいそ'}], kana: 'すいそ' },
                { rubyTokens: [{text: '酸素', ruby: 'さんそ'}], kana: 'さんそ' }
            ],
            kanto_trains: [
                { rubyTokens: [{text: '山手線', ruby: 'やまのてせん'}], kana: 'やまのてせん' },
                { rubyTokens: [{text: '小田急線', ruby: 'おだきゅうせん'}], kana: 'おだきゅうせん' }
            ],
            car_models: [
                { rubyTokens: [{text: 'プリウス'}], kana: 'ぷりうす' },
                { rubyTokens: [{text: 'アクア'}], kana: 'あくあ' }
            ],
            sports_names: [
                { rubyTokens: [{text: 'サッカー'}], kana: 'さっかー' },
                { rubyTokens: [{text: '野球', ruby: 'やきゅう'}], kana: 'やきゅう' }
            ],
            sports_equipment: [
                { rubyTokens: [{text: 'テニスラケット'}], kana: 'てにすらけっと' }
            ],
            musicians: [
                { rubyTokens: [{text: 'ベートーヴェン'}], kana: 'べーとーべん' },
                { rubyTokens: [{text: 'モーツァルト'}], kana: 'もーつぁると' }
            ],
            shogi_terms: [
                { rubyTokens: [{text: '王手', ruby: 'おうて'}], kana: 'おうて' },
                { rubyTokens: [{text: '詰み', ruby: 'つみ'}], kana: 'つみ' }
            ],
            toys: [
                { rubyTokens: [{text: '積み木', ruby: 'つみき'}], kana: 'つみき' },
                { rubyTokens: [{text: '折り紙', ruby: 'おりがみ'}], kana: 'おりがみ' }
            ],
            professions: [
                { rubyTokens: [{text: '医師', ruby: 'いしゃ'}], kana: 'いしゃ' },
                { rubyTokens: [{text: 'パイロット'}], kana: 'ぱいろっと' }
            ],
            pc_terms: [
                { rubyTokens: [{text: 'キーボード'}], kana: 'きーぼーど' },
                { rubyTokens: [{text: 'マウス'}], kana: 'まうす' }
            ],
            it: [
                { rubyTokens: [{text: 'プログラミング'}], kana: 'ぷろぐらみんぐ' }
            ],
            household_items: [
                { rubyTokens: [{text: '冷蔵庫', ruby: 'れいぞうこ'}], kana: 'れいぞうこ' }
            ],
            words: [
                { rubyTokens: [{text: '桜', ruby: 'さくら'}], kana: 'さくら' },
                { rubyTokens: [{text: '空', ruby: 'そら'}], kana: 'そら' }
            ],
            greetings: [
                { rubyTokens: [{text: 'こんにちは'}], kana: 'こんにちは' },
                { rubyTokens: [{text: 'ありがとう'}], kana: 'ありがとう' }
            ],
            medium: [
                { rubyTokens: [{text: '日本語入力', ruby: 'にほんごにゅうりょく'}], kana: 'にほんごにゅうりょく' }
            ],
            proverbs: [
                { rubyTokens: [{text: '猿も木から落ちる', ruby: 'さるもきからおちる'}], kana: 'さるもきからおちる' }
            ],
            yojijukugo: [
                { rubyTokens: [{text: '一期一会', ruby: 'いちごいちえ'}], kana: 'いちごいちえ' }
            ],
            praise: [
                { rubyTokens: [{text: '素晴らしい', ruby: 'すばらしい'}], kana: 'すばらしい' }
            ],
            onomatopoeia: [
                { rubyTokens: [{text: 'わくわく'}], kana: 'わくわく' }
            ],
            animal_sounds: [
                { rubyTokens: [{text: 'ワンワン'}], kana: 'わんわん' }
            ],
            radicals: [
                { rubyTokens: [{text: '木偏', ruby: 'きへん'}], kana: 'きへん' },
                { rubyTokens: [{text: 'さんずい'}], kana: 'さんずい' }
            ],
            nandoku_kanji: [
                { rubyTokens: [{text: '海老', ruby: 'えび'}], kana: 'えび' }
            ],
            keigo: [
                { rubyTokens: [{text: '承知いたしました', ruby: 'しょうちいたしました'}], kana: 'しょうちいたしました' }
            ],
            traditional_colors: [
                { rubyTokens: [{text: '桜色', ruby: 'さくらいろ'}], kana: 'さくらいろ' }
            ],
            japanese_holidays: [
                { rubyTokens: [{text: '元日', ruby: 'がんじつ'}], kana: 'がんじつ' }
            ],
            constellations: [
                { rubyTokens: [{text: 'オリオン座', ruby: 'おりおんざ'}], kana: 'おりおんざ' }
            ],
            world_currencies: [
                { rubyTokens: [{text: '円', ruby: 'えん'}], kana: 'えん' },
                { rubyTokens: [{text: 'ドル'}], kana: 'どる' }
            ],
            spring: [{ rubyTokens: [{text: '桜', ruby: 'さくら'}], kana: 'さくら' }],
            summer: [{ rubyTokens: [{text: '蝉', ruby: 'せみ'}], kana: 'せみ' }],
            autumn: [{ rubyTokens: [{text: '紅葉', ruby: 'もみじ'}], kana: 'もみじ' }],
            winter: [{ rubyTokens: [{text: '雪達磨', ruby: 'ゆきだるま'}], kana: 'ゆきだるま' }]
        };

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
            course: 'japanese',
            timeLimit: 60,
            timeLeft: 60,
            showRuby: true,
            soundEnabled: true,
            isPlaying: false,
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

        window.addEventListener('DOMContentLoaded', () => {
            const totalCourseCountEl = document.getElementById('total-course-count');
            if (totalCourseCountEl) {
                totalCourseCountEl.textContent = Object.keys(WORD_DATA).length;
            }

            initBackgroundParticles();
            setupSettingsUI();
            setupKeyboardListeners();
            updateHighscoreDisplays();
        });

        function updateHighscoreDisplays() {
            document.getElementById('start-totalscore').textContent = gameState.totalScore.toLocaleString();
            document.getElementById('start-highscore').textContent = gameState.highScore.toLocaleString();
            document.getElementById('start-highwpm').textContent = gameState.highWpm;
        }

        function setRubyState(enable) {
            gameState.showRuby = enable;
            
            const settingRubyBtn = document.getElementById('setting-ruby-btn');
            const settingRubyStatus = document.getElementById('setting-ruby-status');
            const headerRubyText = document.getElementById('header-ruby-text');
            const ingameRubyText = document.getElementById('ingame-ruby-text');

            if (settingRubyStatus) settingRubyStatus.textContent = enable ? 'ON' : 'OFF';
            if (settingRubyBtn) {
                if (enable) {
                    settingRubyBtn.classList.remove('border-slate-300', 'bg-white', 'text-slate-600');
                    settingRubyBtn.classList.add('border-sky-500', 'bg-sky-50', 'text-sky-700');
                } else {
                    settingRubyBtn.classList.remove('border-sky-500', 'bg-sky-50', 'text-sky-700');
                    settingRubyBtn.classList.add('border-slate-300', 'bg-white', 'text-slate-600');
                }
            }

            if (headerRubyText) headerRubyText.textContent = `ふりがな: ${enable ? 'ON' : 'OFF'}`;
            if (ingameRubyText) ingameRubyText.textContent = `ルビ: ${enable ? 'ON' : 'OFF'}`;

            const card = document.getElementById('word-card');
            if (card) {
                if (enable) {
                    card.classList.remove('ruby-hidden');
                } else {
                    card.classList.add('ruby-hidden');
                }
            }
        }

        function setupSettingsUI() {
            document.querySelectorAll('.course-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    document.querySelectorAll('.course-btn').forEach(b => {
                        b.classList.remove('border-sky-500', 'bg-sky-50');
                        b.classList.add('border-slate-300', 'bg-white');
                    });
                    btn.classList.remove('border-slate-300', 'bg-white');
                    btn.classList.add('border-sky-500', 'bg-sky-50');
                    gameState.course = btn.dataset.course;
                });
            });

            document.querySelectorAll('.time-btn').forEach(btn => {
                btn.addEventListener('click', () => {
                    document.querySelectorAll('.time-btn').forEach(b => {
                        b.classList.remove('border-sky-500', 'bg-sky-50', 'text-sky-600');
                        b.classList.add('border-slate-300', 'bg-white', 'text-slate-700');
                    });
                    btn.classList.remove('border-slate-300', 'bg-white', 'text-slate-700');
                    btn.classList.add('border-sky-500', 'bg-sky-50', 'text-sky-600');
                    gameState.timeLimit = parseInt(btn.dataset.time);
                });
            });

            const toggleFurigana = () => setRubyState(!gameState.showRuby);
            const settingRubyBtn = document.getElementById('setting-ruby-btn');
            const headerRubyToggle = document.getElementById('header-ruby-toggle');
            const ingameRubyBtn = document.getElementById('ingame-ruby-btn');
            const ingameBackBtn = document.getElementById('ingame-back-btn');
            const ingameRetryBtn = document.getElementById('ingame-retry-btn');
            const soundToggleBtn = document.getElementById('sound-toggle-btn');
            const soundIcon = document.getElementById('sound-icon');

            if (settingRubyBtn) settingRubyBtn.addEventListener('click', toggleFurigana);
            if (headerRubyToggle) headerRubyToggle.addEventListener('click', toggleFurigana);
            if (ingameRubyBtn) ingameRubyBtn.addEventListener('click', toggleFurigana);

            if (ingameBackBtn) {
                ingameBackBtn.addEventListener('click', () => {
                    if (gameState.isPlaying) {
                        gameState.isPlaying = false;
                        if (gameState.timerId) clearInterval(gameState.timerId);
                        showStartScreen();
                    }
                });
            }

            if (ingameRetryBtn) {
                ingameRetryBtn.addEventListener('click', () => {
                    if (gameState.isPlaying) {
                        startGame();
                    }
                });
            }

            if (soundToggleBtn) {
                soundToggleBtn.addEventListener('click', () => {
                    gameState.soundEnabled = !gameState.soundEnabled;
                    if (soundIcon) soundIcon.className = gameState.soundEnabled ? 'fa-solid fa-volume-high' : 'fa-solid fa-volume-xmark text-slate-500';
                });
            }

            document.getElementById('start-game-btn').addEventListener('click', startGame);
            document.getElementById('restart-btn').addEventListener('click', startGame);
            document.getElementById('back-home-btn').addEventListener('click', showStartScreen);
        }

        function startGame() {
            gameState.isPlaying = true;
            gameState.score = 0;
            gameState.totalTyped = 0;
            gameState.correctTyped = 0;
            gameState.correctKanaTyped = 0;
            gameState.missTyped = 0;
            gameState.timeLeft = gameState.timeLimit;
            
            const selectedCourseData = WORD_DATA[gameState.course] || WORD_DATA.japanese;
            gameState.remainingWords = shuffleArray(selectedCourseData);

            document.getElementById('start-screen').classList.add('hidden');
            document.getElementById('result-screen').classList.add('hidden');
            document.getElementById('play-screen').classList.remove('hidden');

            setRubyState(gameState.showRuby);

            document.getElementById('timer-display').textContent = gameState.timeLeft;
            document.getElementById('score-display').textContent = '0';
            document.getElementById('accuracy-display').textContent = '100';

            if (gameState.timerId) clearInterval(gameState.timerId);
            gameState.timerId = setInterval(() => {
                gameState.timeLeft--;
                document.getElementById('timer-display').textContent = gameState.timeLeft;
                if (gameState.timeLeft <= 0) {
                    endGame();
                }
            }, 1000);

            nextWord();
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
                const selectedCourseData = WORD_DATA[gameState.course] || WORD_DATA.japanese;
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
                if (e.code === 'Space' && !gameState.isPlaying && !document.getElementById('start-screen').classList.contains('hidden')) {
                    e.preventDefault();
                    startGame();
                    return;
                }

                if (!gameState.isPlaying) return;

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
