<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>マイ・スペシャル・クロップ | ひとつの作物を愛でる栽培紹介サイト</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Noto+Sans+JP:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Inter', 'Noto Sans JP', sans-serif;
        }
        .hero-bg {
            transition: background-image 0.5s ease-in-out;
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #f5f5f4;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #d6d3d1;
            border-radius: 3px;
        }
    </style>
</head>
<body class="bg-stone-50 text-stone-800 min-h-screen flex flex-col selection:bg-emerald-100 selection:text-emerald-900">

    <!-- ヘッダー -->
    <header class="bg-white/80 backdrop-blur-md border-b border-stone-200/80 sticky top-0 z-40">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 py-4 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="bg-gradient-to-br from-emerald-500 to-teal-600 text-white p-2 rounded-xl shadow-md shadow-emerald-200">
                    <i class="fa-solid fa-seedling text-lg animate-pulse"></i>
                </div>
                <div>
                    <h1 class="text-base sm:text-lg font-black tracking-wider text-stone-900">
                        My Star Crop
                    </h1>
                    <p class="text-[10px] text-stone-500 font-medium tracking-tight">
                        たったひとつの、自慢の作物紹介・栽培日記
                    </p>
                </div>
            </div>
            
            <button onclick="openEditModal()" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold text-xs sm:text-sm px-4 py-2 rounded-xl transition duration-300 transform hover:-translate-y-0.5 shadow-md shadow-emerald-100 flex items-center space-x-1.5">
                <i class="fa-solid fa-pen-to-square"></i>
                <span>紹介情報を編集する</span>
            </button>
        </div>
    </header>

    <!-- メインビジュアル / ヒーローセクション -->
    <section class="relative bg-stone-900 text-white overflow-hidden sm:rounded-b-[2.5rem] shadow-xl">
        <div class="absolute inset-0 z-0">
            <!-- 作物メイン写真（動的に差し替え） -->
            <img id="cropHeroImg" src="" alt="作物の写真" class="w-full h-full object-cover opacity-60 blur-xs transition-all duration-700 scale-105">
            <div class="absolute inset-0 bg-gradient-to-t from-stone-950 via-stone-950/40 to-stone-900/40"></div>
        </div>
        
        <div class="relative z-10 max-w-4xl mx-auto px-4 sm:px-6 py-12 sm:py-20 flex flex-col md:flex-row md:items-end justify-between gap-6">
            <!-- 左側：基本情報 -->
            <div class="space-y-4">
                <div class="flex flex-wrap items-center gap-2">
                    <span id="cropCategoryBadge" class="px-3 py-1 rounded-full text-xs font-black tracking-wide shadow-sm">
                        <!-- カテゴリが挿入されます -->
                    </span>
                    <span id="cropStatusBadge" class="px-3 py-1 rounded-full text-xs font-bold shadow-sm">
                        <!-- ステータスが挿入されます -->
                    </span>
                </div>
                
                <h2 id="cropDisplayName" class="text-3xl sm:text-5xl font-black tracking-tight drop-shadow-md">
                    <!-- 作物名が挿入されます -->
                </h2>
                
                <div class="flex flex-wrap items-center gap-y-2 gap-x-4 text-xs sm:text-sm text-stone-300">
                    <span class="flex items-center gap-1.5 bg-stone-900/60 backdrop-blur-md px-3 py-1.5 rounded-lg border border-stone-700/50">
                        <i class="fa-regular fa-calendar-days text-emerald-400"></i>
                        栽培開始日: <strong id="cropDisplayDate" class="text-white"></strong>
                    </span>
                    <span class="flex items-center gap-1.5 bg-stone-900/60 backdrop-blur-md px-3 py-1.5 rounded-lg border border-stone-700/50">
                        <i class="fa-solid fa-hourglass-half text-amber-400"></i>
                        経過日数: <strong id="cropDisplayDaysCount" class="text-white">-- 日目</strong>
                    </span>
                </div>
            </div>

            <!-- 右側：簡易ステータスカード -->
            <div class="bg-white/10 backdrop-blur-md rounded-2xl p-4 border border-white/20 text-xs space-y-3 min-w-[220px] self-start md:self-end">
                <h4 class="font-bold text-emerald-300 uppercase tracking-wider flex items-center gap-1">
                    <i class="fa-solid fa-gauge-high"></i> 栽培環境 & ケア
                </h4>
                <div class="space-y-2">
                    <div class="flex justify-between items-center text-stone-200">
                        <span>☀️ 日当たり:</span>
                        <span id="displaySunlight" class="font-bold text-white">日向を好む</span>
                    </div>
                    <div class="flex justify-between items-center text-stone-200">
                        <span>💧 水やり:</span>
                        <span id="displayWatering" class="font-bold text-white">乾いたらたっぷり</span>
                    </div>
                    <div class="flex justify-between items-center text-stone-200">
                        <span>❤️ 今の元気度:</span>
                        <div class="flex items-center gap-1">
                            <span id="displayHealth" class="font-bold text-yellow-400">最高！</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- メインコンテンツ -->
    <main class="flex-grow max-w-5xl mx-auto px-4 sm:px-6 py-8 w-full grid grid-cols-1 md:grid-cols-3 gap-8">
        
        <!-- 左カラム：詳細説明とプロフィール -->
        <div class="md:col-span-1 space-y-6">
            <!-- 作物の写真展示 -->
            <div class="bg-white rounded-2xl p-4 shadow-sm border border-stone-200/80">
                <h3 class="text-xs font-black text-stone-400 uppercase tracking-wider mb-3 flex items-center gap-1">
                    <i class="fa-solid fa-camera"></i>
                    作物のベストショット
                </h3>
                <div class="aspect-square rounded-xl overflow-hidden bg-stone-100 shadow-inner group relative">
                    <img id="cropMainImg" src="" alt="作物の写真" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="mt-3 text-[11px] text-center text-stone-500 italic">
                    愛情を込めて日々育てているお気に入りの一枚です
                </div>
            </div>

            <!-- 詳細説明メモ -->
            <div class="bg-white rounded-2xl p-5 shadow-sm border border-stone-200/80 space-y-3">
                <h3 class="text-xs font-black text-stone-400 uppercase tracking-wider flex items-center gap-1">
                    <i class="fa-solid fa-circle-info"></i>
                    この作物の紹介・栽培のこだわり
                </h3>
                <div class="border-t border-stone-100 pt-3">
                    <p id="cropDisplayDesc" class="text-stone-700 text-sm leading-relaxed whitespace-pre-wrap">
                        <!-- ここに説明文が入ります -->
                    </p>
                </div>
            </div>

            <!-- 目標や一言アピール -->
            <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-5 border border-emerald-100 space-y-2">
                <h3 class="text-xs font-black text-emerald-800 uppercase tracking-wider flex items-center gap-1">
                    <i class="fa-solid fa-bullseye"></i>
                    栽培の目標・意気込み
                </h3>
                <p id="cropDisplayGoal" class="text-emerald-950 font-bold text-sm leading-relaxed">
                    <!-- 目標が入ります -->
                </p>
            </div>

            <!-- 栽培方法・育て方のステップ -->
            <div class="bg-white rounded-2xl p-5 shadow-sm border border-stone-200/80 space-y-3">
                <h3 class="text-xs font-black text-stone-400 uppercase tracking-wider flex items-center gap-1">
                    <i class="fa-solid fa-graduation-cap text-emerald-600"></i>
                    栽培方法・育て方の手順
                </h3>
                <div id="cropDisplayMethodContainer" class="space-y-2.5 border-t border-stone-100 pt-3">
                    <!-- 動的に栽培ステップが挿入されます -->
                </div>
            </div>
        </div>

        <!-- 右カラム：栽培日記・成長タイムライン -->
        <div class="md:col-span-2 space-y-6">
            <div class="bg-white rounded-2xl p-6 shadow-sm border border-stone-200/80">
                <!-- タイトル -->
                <div class="flex items-center justify-between mb-6 pb-4 border-b border-stone-100">
                    <div class="flex items-center space-x-2">
                        <span class="bg-emerald-50 text-emerald-600 p-2 rounded-lg text-lg">
                            <i class="fa-solid fa-book"></i>
                        </span>
                        <div>
                            <h3 class="font-black text-stone-800 text-base">成長のあゆみ（栽培日記）</h3>
                            <p class="text-xs text-stone-400">日々の成長や、お世話した作業のログを残そう</p>
                        </div>
                    </div>
                    <span id="logCounterBadge" class="bg-stone-100 text-stone-600 text-xs font-bold px-3 py-1 rounded-full">
                        0件の記録
                    </span>
                </div>

                <!-- ログ追加フォーム -->
                <div class="bg-stone-50 rounded-2xl p-4 border border-stone-200/60 mb-8">
                    <h4 class="text-xs font-black text-stone-500 uppercase tracking-wider mb-2.5 flex items-center gap-1">
                        <i class="fa-solid fa-pen-nib text-emerald-600"></i>
                        新しい日記を記録する
                    </h4>
                    
                    <div class="space-y-3">
                        <textarea id="newLogText" rows="2" placeholder="例: 可愛い芽が3つ出てきました！毎日少しずつ大きくなっています。水やりをしました。🌿" class="w-full text-sm px-4 py-2.5 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 bg-white resize-none"></textarea>
                        
                        <div class="flex flex-col sm:flex-row gap-2 justify-between items-stretch sm:items-center">
                            <!-- 日付選択と状態選択 -->
                            <div class="flex flex-wrap items-center gap-2">
                                <input type="date" id="newLogDate" class="text-xs px-3 py-1.5 border border-stone-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-emerald-500 bg-white">
                                <select id="newLogIcon" class="text-xs px-2.5 py-1.5 border border-stone-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-emerald-500 bg-white">
                                    <option value="🌱">🌱 発芽・植え付け</option>
                                    <option value="💦" selected>💦 水やり・お世話</option>
                                    <option value="✨">✨ 追肥・土寄せ</option>
                                    <option value="🌸">🌸 開花</option>
                                    <option value="🍅">🍅 結実・実り</option>
                                    <option value="✂️">✂️ 剪定・わき芽摘み</option>
                                    <option value="🎉">🎉 収穫・大成功</option>
                                    <option value="⚠️">⚠️ 注意・トラブル</option>
                                </select>
                            </div>
                            
                            <!-- 保存ボタン -->
                            <button onclick="addNewLog()" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold px-5 py-2 rounded-xl text-xs sm:text-sm transition duration-200 flex items-center justify-center gap-1">
                                <i class="fa-solid fa-check"></i>
                                <span>日記を残す</span>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- タイムライン表示エリア -->
                <div id="logTimeline" class="relative before:absolute before:inset-y-0 before:left-4 before:w-0.5 before:bg-stone-200 space-y-6">
                    <!-- 動的にJSで挿入されます -->
                </div>
            </div>
        </div>

    </main>

    <!-- 作物プロフィール編集用モーダル -->
    <div id="editModal" class="fixed inset-0 bg-stone-900/60 backdrop-blur-xs z-50 flex items-center justify-center p-4 transition-opacity duration-300 opacity-0 pointer-events-none">
        <div class="bg-white rounded-3xl max-w-lg w-full max-h-[90vh] overflow-y-auto shadow-2xl transform scale-95 transition-transform duration-300 flex flex-col">
            <!-- モーダルヘッダー -->
            <div class="p-6 border-b border-stone-100 flex items-center justify-between sticky top-0 bg-white z-10">
                <h3 class="text-lg font-black text-stone-800 flex items-center gap-2">
                    <i class="fa-solid fa-sliders text-emerald-600"></i>
                    <span>主役の作物を設定する</span>
                </h3>
                <button onclick="closeEditModal()" class="text-stone-400 hover:text-stone-700 p-2 text-xl rounded-full hover:bg-stone-100 transition">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>

            <!-- フォーム -->
            <form id="editForm" onsubmit="handleFormSubmit(event)" class="p-6 space-y-5 flex-grow">
                
                <!-- 作物名 -->
                <div>
                    <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5" for="formCropName">作物の名前 <span class="text-red-500">*</span></label>
                    <input type="text" id="formCropName" required placeholder="例: 激甘ミニトマト、もこもこバジル" class="w-full px-4 py-2.5 bg-stone-50 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 text-sm">
                </div>

                <!-- カテゴリ ＆ 栽培ステータス -->
                <div class="grid grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5" for="formCategory">カテゴリ <span class="text-red-500">*</span></label>
                        <select id="formCategory" required class="w-full px-3 py-2.5 bg-stone-50 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 text-sm">
                            <option value="vegetable">野菜 🥬</option>
                            <option value="fruit">果物 🍓</option>
                            <option value="herb">ハーブ 🌿</option>
                            <option value="flower">お花・観葉 🌸</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5" for="formStatus">栽培ステータス <span class="text-red-500">*</span></label>
                        <select id="formStatus" required class="w-full px-3 py-2.5 bg-stone-50 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 text-sm">
                            <option value="planting">種まき・植え付け</option>
                            <option value="growing">すくすく成長中</option>
                            <option value="harvesting">ウキウキ収穫期</option>
                            <option value="completed">栽培完了</option>
                        </select>
                    </div>
                </div>

                <!-- 栽培開始日 -->
                <div>
                    <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5" for="formStartDate">栽培を開始した日</label>
                    <input type="date" id="formStartDate" class="w-full px-4 py-2.5 bg-stone-50 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 text-sm">
                </div>

                <!-- 育成環境のこだわり -->
                <div class="grid grid-cols-3 gap-2">
                    <div>
                        <label class="block text-[10px] font-black text-stone-500 uppercase tracking-wider mb-1" for="formSunlight">☀️ 日当たり</label>
                        <input type="text" id="formSunlight" placeholder="例: 日向を好む" class="w-full px-2 py-2 bg-stone-50 border border-stone-200 rounded-lg text-xs">
                    </div>
                    <div>
                        <label class="block text-[10px] font-black text-stone-500 uppercase tracking-wider mb-1" for="formWatering">💧 水やり頻度</label>
                        <input type="text" id="formWatering" placeholder="例: 土が乾いたら" class="w-full px-2 py-2 bg-stone-50 border border-stone-200 rounded-lg text-xs">
                    </div>
                    <div>
                        <label class="block text-[10px] font-black text-stone-500 uppercase tracking-wider mb-1" for="formHealth">❤️ 元気度</label>
                        <select id="formHealth" class="w-full px-2 py-2 bg-stone-50 border border-stone-200 rounded-lg text-xs">
                            <option value="満点！💮">満点！💮</option>
                            <option value="絶好調✨">絶好調✨</option>
                            <option value="ボチボチ順調🌱">ボチボチ順調🌱</option>
                            <option value="ちょっと元気ないかも💦">ちょっと元気ないかも💦</option>
                        </select>
                    </div>
                </div>

                <!-- 画像アップロード / プリセット選択 -->
                <div>
                    <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5">作物の写真</label>
                    
                    <!-- プレビュー -->
                    <div class="relative w-full h-40 bg-stone-100 rounded-2xl border-2 border-dashed border-stone-200 mb-3 overflow-hidden flex items-center justify-center">
                        <img id="formImgPreview" src="" alt="プレビュー" class="hidden w-full h-full object-cover">
                        <div id="formImgPlaceholder" class="text-center p-4">
                            <i class="fa-solid fa-camera text-stone-300 text-3xl mb-1"></i>
                            <p class="text-xs text-stone-400">端末の写真から選択するか、おまかせ画像をセットできます</p>
                        </div>
                    </div>

                    <div class="grid grid-cols-2 gap-2">
                        <label class="cursor-pointer bg-stone-100 hover:bg-stone-200 text-stone-700 font-bold py-2 px-3 rounded-xl text-xs text-center border border-stone-300 transition flex items-center justify-center gap-1">
                            <i class="fa-solid fa-upload"></i>
                            <span>写真を選ぶ</span>
                            <input type="file" id="cropImageFile" accept="image/*" onchange="handleFileSelect(event)" class="hidden">
                        </label>
                        <button type="button" onclick="setPresetPlaceholder()" class="bg-emerald-50 hover:bg-emerald-100 text-emerald-700 font-bold py-2 px-3 rounded-xl text-xs text-center border border-emerald-200 transition flex items-center justify-center gap-1">
                            <i class="fa-solid fa-wand-magic-sparkles"></i>
                            <span>おまかせイラスト</span>
                        </button>
                    </div>
                    <input type="hidden" id="formImageData" value="">
                </div>

                <!-- 詳細説明文 -->
                <div>
                    <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5" for="formDesc">紹介文・育てようと思った理由など</label>
                    <textarea id="formDesc" rows="3" placeholder="ベランダの日当たりの良いプランターで愛情を注いで栽培中。パスタやサラダに大活躍する予定！" class="w-full px-4 py-2 bg-stone-50 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 text-sm resize-none"></textarea>
                </div>

                <!-- 目標 -->
                <div>
                    <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5" for="formGoal">栽培の目標</label>
                    <input type="text" id="formGoal" placeholder="例: 100個以上の実を収穫して、トマトパスタを作る！" class="w-full px-4 py-2 bg-stone-50 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 text-sm">
                </div>

                <!-- 栽培方法・育て方 -->
                <div>
                    <label class="block text-xs font-black text-stone-500 uppercase tracking-wider mb-1.5" for="formMethod">栽培方法・育て方のコツ（改行するとステップに分割されます）</label>
                    <textarea id="formMethod" rows="4" placeholder="【ステップ1：土づくり】水はけの良い用土を準備します。&#10;【ステップ2：水やり】表面が乾いたらたっぷり与えます。" class="w-full px-4 py-2 bg-stone-50 border border-stone-200 rounded-xl focus:outline-none focus:ring-2 focus:ring-emerald-500 text-sm resize-none"></textarea>
                </div>

                <!-- フォームボタン -->
                <div class="pt-4 border-t border-stone-100 flex items-center justify-end space-x-3">
                    <button type="button" onclick="closeEditModal()" class="bg-stone-100 hover:bg-stone-200 text-stone-700 font-bold px-4 py-2 rounded-xl text-xs transition">
                        キャンセル
                    </button>
                    <button type="submit" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold px-5 py-2 rounded-xl text-xs transition shadow">
                        保存する
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- トースト通知システム -->
    <div id="toastContainer" class="fixed bottom-5 right-5 z-50 flex flex-col space-y-2 pointer-events-none"></div>

    <!-- カスタム確認ダイアログ (alert/confirmの代替用) -->
    <div id="confirmModal" class="fixed inset-0 bg-stone-900/60 backdrop-blur-xs z-50 flex items-center justify-center p-4 opacity-0 pointer-events-none transition-opacity duration-300">
        <div class="bg-white rounded-2xl max-w-sm w-full p-6 shadow-xl transform scale-95 transition-transform duration-300">
            <h3 class="text-base font-black text-stone-800 mb-2 flex items-center gap-2">
                <i class="fa-solid fa-circle-question text-amber-500"></i>
                <span>確認</span>
            </h3>
            <p id="confirmMessage" class="text-stone-600 text-sm mb-6 leading-relaxed">本当に実行しますか？</p>
            <div class="flex justify-end gap-3">
                <button id="confirmCancelBtn" class="bg-stone-100 hover:bg-stone-200 text-stone-700 px-4 py-2 rounded-xl text-xs font-bold transition">キャンセル</button>
                <button id="confirmOkBtn" class="bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-xl text-xs font-bold transition">削除する</button>
            </div>
        </div>
    </div>

    <!-- フッター -->
    <footer class="bg-stone-900 text-stone-400 text-center py-8 mt-12 border-t border-stone-800 text-xs">
        <div class="max-w-5xl mx-auto px-4 space-y-2">
            <p class="font-bold text-stone-300">My Star Crop — 愛情たっぷり栽培日記</p>
            <p>© 2026 マイ・クロップ・ガーデン. 太陽と土、そして水を大切に。 🌱🍅</p>
        </div>
    </footer>

    <script>
        // --- データのキー ---
        const LOCAL_STORAGE_KEY = 'single_crop_data';

        // デフォルトの作物データ（ローカルストレージが空の場合の初期紹介アイテム）
        const INITIAL_CROP_DATA = {
            name: '極甘フルーツミニトマト「あまぷる」',
            category: 'vegetable',
            status: 'growing',
            startDate: '2026-05-10',
            image: 'https://images.unsplash.com/photo-1592924357228-91a4daadcfea?w=1000&auto=format&fit=crop&q=80',
            description: '南向きの日当たりが良いベランダで、大きめの不織布プランターを使用して育てています。\n化成肥料と有機たい肥をうまく使い分け、水やりは「土の表面がしっかり乾いてからたっぷりあげる」を徹底。脇芽かきをしっかり行って、第一花房の実つきをよくするために振動授粉を実践しています。甘くて美味しい実がたくさん収穫できるのがとても楽しみです！',
            goal: '今年はプランターから150個以上の甘い実を収穫して、自家製ドライトマトパスタを作る！',
            sunlight: '1日中直射日光があたる特等席',
            watering: '乾いたら底から流れ出るまでたっぷり',
            health: '絶好調✨',
            method: '【土づくり・植え付け】水はけが良く元肥入りの野菜用培養土に植え付け、仮支柱を立てます。\n【わき芽かき】栄養を実へ集中させるため、葉の付け根から出るわき芽は小さいうちに手で摘み取ります。\n【水やり管理】第一花房（最初の実）がつき始めたら、水やりは土がしっかり乾いてからにし、乾燥気味にして甘みを凝縮させます。\n【追肥と収穫】最初の実が膨らみ始めたら2週間に1回程度追肥を行い、赤く熟した順に朝のうちに収穫します。',
            logs: [
                { id: 'log_1', date: '2026-05-10', icon: '🌱', text: '近くのホームセンターで幹が太く健康な接ぎ木苗を購入してプランターに植え付け完了！元肥をたっぷり施しました。' },
                { id: 'log_2', date: '2026-05-24', text: '最初のわき芽摘みと、150cm of 太い支柱を立ててヒモで誘引を行いました。ぐんぐん上を向いて伸びています。', icon: '✂️' },
                { id: 'log_3', date: '2026-06-12', text: '第一花房に黄色い可愛らしい花が開花！実がたくさん着くよう、指で軽くトントンと茎をたたいて振動授粉を行いました。', icon: '🌸' },
                { id: 'log_4', date: '2026-06-22', text: 'ついに花が落ち、小さな緑色の赤ちゃんトマトが実ってきました！鈴なりになる姿が楽しみです。追肥（トマト専用液肥）を施しました。', icon: '🍅' }
            ]
        };

        // アプリの状態
        let activeCrop = {};

        // アプリ起動時にデータを読み込み
        window.onload = function () {
            const stored = localStorage.getItem(LOCAL_STORAGE_KEY);
            if (stored) {
                try {
                    activeCrop = JSON.parse(stored);
                } catch(e) {
                    console.error("データのパースに失敗しました。", e);
                    activeCrop = { ...INITIAL_CROP_DATA };
                }
            } else {
                activeCrop = { ...INITIAL_CROP_DATA };
                saveData();
            }

            // 今日の日付をログの初期値に設定
            document.getElementById('newLogDate').value = new Date().toISOString().substring(0, 10);

            renderPage();
        };

        // データをLocalStorageへ保存
        function saveData() {
            localStorage.setItem(LOCAL_STORAGE_KEY, JSON.stringify(activeCrop));
        }

        // --- 画面レンダリング ---
        function renderPage() {
            // ヘッダー・メイン写真の適用
            const heroImg = document.getElementById('cropHeroImg');
            const mainImg = document.getElementById('cropMainImg');
            
            const displayImgUrl = activeCrop.image || 'https://placehold.co/800x600/10b981/ffffff?text=MyCrop';
            heroImg.src = displayImgUrl;
            mainImg.src = displayImgUrl;

            // テキスト部分の流し込み
            document.getElementById('cropDisplayName').textContent = activeCrop.name;
            document.getElementById('cropDisplayDesc').textContent = activeCrop.description || 'まだ説明がありません。上の「編集する」ボタンから作物の説明を書いてみましょう！';
            document.getElementById('cropDisplayGoal').textContent = activeCrop.goal || '甘い実をたくさん収穫する！';
            
            // 栽培開始日と経過日数計算
            if (activeCrop.startDate) {
                document.getElementById('cropDisplayDate').textContent = formatDate(activeCrop.startDate);
                
                // 経過日数の計算
                const start = new Date(activeCrop.startDate);
                const today = new Date();
                const diffTime = Math.abs(today - start);
                const diffDays = Math.ceil(diffTime / (1000 * 60 * 60 * 24));
                document.getElementById('cropDisplayDaysCount').textContent = `${diffDays} 日目`;
            } else {
                document.getElementById('cropDisplayDate').textContent = '未登録';
                document.getElementById('cropDisplayDaysCount').textContent = '-- 日目';
            }

            // 環境パラメータ
            document.getElementById('displaySunlight').textContent = activeCrop.sunlight || '未設定';
            document.getElementById('displayWatering').textContent = activeCrop.watering || '未設定';
            document.getElementById('displayHealth').textContent = activeCrop.health || '絶好調✨';

            // 栽培方法の表示
            renderMethod();

            // バッジ
            renderBadges();

            // タイムラインのレンダリング
            renderTimeline();
        }

        // 栽培方法のレンダリング処理
        function renderMethod() {
            const container = document.getElementById('cropDisplayMethodContainer');
            container.innerHTML = '';

            const methodText = activeCrop.method || '';
            if (!methodText.trim()) {
                container.innerHTML = `<p class="text-xs text-stone-400 italic">栽培方法が登録されていません。上の「編集する」ボタンから追加してみましょう！</p>`;
                return;
            }

            // 改行で分割して、各行を個別のステップとして表示
            const steps = methodText.split('\n').filter(line => line.trim() !== '');
            steps.forEach((step, idx) => {
                const stepDiv = document.createElement('div');
                stepDiv.className = 'flex items-start gap-2.5 text-xs text-stone-700 leading-relaxed bg-stone-50 hover:bg-stone-100/60 p-3 rounded-xl border border-stone-200/40 transition duration-150 shadow-sm';
                stepDiv.innerHTML = `
                    <span class="bg-emerald-100 text-emerald-800 text-[10px] font-black rounded-full w-5 h-5 flex items-center justify-center shrink-0 mt-0.5">
                        ${idx + 1}
                    </span>
                    <span class="flex-grow whitespace-pre-wrap">${step}</span>
                `;
                container.appendChild(stepDiv);
            });
        }

        // バッジ表示用
        function renderBadges() {
            const catBadge = document.getElementById('cropCategoryBadge');
            const statBadge = document.getElementById('cropStatusBadge');

            // カテゴリのバッジ色分け
            switch(activeCrop.category) {
                case 'vegetable':
                    catBadge.className = 'bg-green-100 text-green-800 border border-green-200 px-3 py-1 rounded-full text-xs font-black shadow-sm';
                    catBadge.innerHTML = '🥬 野菜';
                    break;
                case 'fruit':
                    catBadge.className = 'bg-rose-100 text-rose-800 border border-rose-200 px-3 py-1 rounded-full text-xs font-black shadow-sm';
                    catBadge.innerHTML = '🍓 果物';
                    break;
                case 'herb':
                    catBadge.className = 'bg-teal-100 text-teal-800 border border-teal-200 px-3 py-1 rounded-full text-xs font-black shadow-sm';
                    catBadge.innerHTML = '🌿 ハーブ';
                    break;
                default:
                    catBadge.className = 'bg-amber-100 text-amber-800 border border-amber-200 px-3 py-1 rounded-full text-xs font-black shadow-sm';
                    catBadge.innerHTML = '🌸 お花・観葉';
                    break;
            }

            // ステータスバッジ
            switch(activeCrop.status) {
                case 'planting':
                    statBadge.className = 'bg-blue-600 text-white px-3 py-1 rounded-full text-xs font-bold shadow-sm';
                    statBadge.innerHTML = '<i class="fa-solid fa-seedling mr-1"></i>定植・導入期';
                    break;
                case 'growing':
                    statBadge.className = 'bg-yellow-500 text-stone-900 px-3 py-1 rounded-full text-xs font-bold shadow-sm';
                    statBadge.innerHTML = '<i class="fa-solid fa-circle-arrow-up mr-1 animate-pulse"></i>すくすく成長中';
                    break;
                case 'harvesting':
                    statBadge.className = 'bg-emerald-600 text-white px-3 py-1 rounded-full text-xs font-bold shadow-sm';
                    statBadge.innerHTML = '<i class="fa-solid fa-basket-shopping mr-1"></i>ウキウキ収穫期';
                    break;
                default:
                    statBadge.className = 'bg-stone-500 text-white px-3 py-1 rounded-full text-xs font-bold shadow-sm';
                    statBadge.innerHTML = '<i class="fa-solid fa-check mr-1"></i>栽培完了';
                    break;
            }
        }

        // --- タイムラインレンダリング ---
        function renderTimeline() {
            const list = document.getElementById('logTimeline');
            const badge = document.getElementById('logCounterBadge');
            list.innerHTML = '';

            const logs = activeCrop.logs || [];
            badge.textContent = `${logs.length}件の記録`;

            if (logs.length === 0) {
                list.innerHTML = `
                    <div class="text-center py-8 bg-stone-50 rounded-2xl border border-dashed border-stone-200 text-stone-400 text-xs">
                        <i class="fa-solid fa-book-open text-lg mb-2 block"></i>
                        まだ日記がありません。上のフォームから最初の日記を追加してください！
                    </div>
                `;
                return;
            }

            // 新しい日付が上に来るように降順にソートして描画
            const sortedLogs = [...logs].sort((a, b) => new Date(b.date) - new Date(a.date));

            sortedLogs.forEach((log) => {
                const item = document.createElement('div');
                item.className = 'relative pl-8 pb-6 group';
                
                const emoji = log.icon || '💦';

                item.innerHTML = `
                    <!-- タイムラインの丸・アイコン -->
                    <div class="absolute left-1.5 top-1 w-5 h-5 rounded-full border border-emerald-500 bg-white group-hover:bg-emerald-500 transition-colors z-10 flex items-center justify-center text-[10px]">
                        <span>${emoji}</span>
                    </div>
                    <!-- 日記吹き出し本体 -->
                    <div class="bg-stone-50 hover:bg-stone-100/50 rounded-2xl p-4 border border-stone-200/40 relative transition duration-150">
                        <div class="flex items-center justify-between mb-1.5">
                            <span class="text-xs font-bold text-stone-400">
                                <i class="fa-regular fa-clock mr-1"></i>${formatDate(log.date)}
                            </span>
                            <!-- 削除ボタン -->
                            <button onclick="deleteLog('${log.id}')" class="text-stone-300 hover:text-red-500 text-xs transition p-1 opacity-0 group-hover:opacity-100 absolute top-3 right-3">
                                <i class="fa-solid fa-trash-can"></i>
                            </button>
                        </div>
                        <p class="text-stone-700 text-sm whitespace-pre-wrap pr-4 leading-relaxed">${log.text}</p>
                    </div>
                `;
                list.appendChild(item);
            });
        }

        // --- 新しい日記を追加 ---
        function addNewLog() {
            const input = document.getElementById('newLogText');
            const text = input.value.trim();
            const date = document.getElementById('newLogDate').value;
            const icon = document.getElementById('newLogIcon').value;

            if (!text) {
                showToast('日記の内容を入力してください', 'error');
                return;
            }

            if (!activeCrop.logs) {
                activeCrop.logs = [];
            }

            const newLog = {
                id: 'log_' + Date.now(),
                date,
                icon,
                text
            };

            activeCrop.logs.push(newLog);
            saveData();
            renderTimeline();
            
            // フォームリセット
            input.value = '';
            showToast('栽培日記に新しく記録しました！📝');
        }

        // 日記の削除
        function deleteLog(logId) {
            openConfirm('この日記を完全に削除しますか？', () => {
                activeCrop.logs = activeCrop.logs.filter(l => l.id !== logId);
                saveData();
                renderTimeline();
                showToast('日記を削除しました。');
            });
        }

        // --- 編集モーダルの制御 ---
        function openEditModal() {
            document.getElementById('formCropName').value = activeCrop.name || '';
            document.getElementById('formCategory').value = activeCrop.category || 'vegetable';
            document.getElementById('formStatus').value = activeCrop.status || 'growing';
            document.getElementById('formStartDate').value = activeCrop.startDate || '';
            document.getElementById('formSunlight').value = activeCrop.sunlight || '';
            document.getElementById('formWatering').value = activeCrop.watering || '';
            document.getElementById('formHealth').value = activeCrop.health || '絶好調✨';
            document.getElementById('formDesc').value = activeCrop.description || '';
            document.getElementById('formGoal').value = activeCrop.goal || '';
            document.getElementById('formMethod').value = activeCrop.method || ''; // 栽培方法のセット
            document.getElementById('formImageData').value = activeCrop.image || '';

            if (activeCrop.image) {
                document.getElementById('formImgPreview').src = activeCrop.image;
                document.getElementById('formImgPreview').classList.remove('hidden');
                document.getElementById('formImgPlaceholder').classList.add('hidden');
            } else {
                document.getElementById('formImgPreview').classList.add('hidden');
                document.getElementById('formImgPlaceholder').classList.remove('hidden');
            }

            const modal = document.getElementById('editModal');
            modal.classList.remove('pointer-events-none');
            modal.classList.add('opacity-100');
            modal.querySelector('div').classList.remove('scale-95');
        }

        function closeEditModal() {
            const modal = document.getElementById('editModal');
            modal.classList.add('pointer-events-none');
            modal.classList.remove('opacity-100');
            modal.querySelector('div').classList.add('scale-95');
        }

        // 編集フォームの送信保存
        function handleFormSubmit(e) {
            e.preventDefault();

            activeCrop.name = document.getElementById('formCropName').value.trim();
            activeCrop.category = document.getElementById('formCategory').value;
            activeCrop.status = document.getElementById('formStatus').value;
            activeCrop.startDate = document.getElementById('formStartDate').value;
            activeCrop.sunlight = document.getElementById('formSunlight').value.trim();
            activeCrop.watering = document.getElementById('formWatering').value.trim();
            activeCrop.health = document.getElementById('formHealth').value;
            activeCrop.description = document.getElementById('formDesc').value.trim();
            activeCrop.goal = document.getElementById('formGoal').value.trim();
            activeCrop.method = document.getElementById('formMethod').value.trim(); // 栽培方法の更新
            
            const imageVal = document.getElementById('formImageData').value;
            if (imageVal) {
                activeCrop.image = imageVal;
            }

            saveData();
            renderPage();
            closeEditModal();
            showToast('作物の情報を更新しました！🍅✨');
        }

        // --- 画像処理・おまかせイラスト ---
        function handleFileSelect(e) {
            const file = e.target.files[0];
            if (!file) return;

            const reader = new FileReader();
            reader.onload = function(evt) {
                const base64Url = evt.target.result;
                
                // 画像を縮小圧縮してローカルストレージの容量対策
                const img = new Image();
                img.src = base64Url;
                img.onload = function() {
                    const canvas = document.createElement('canvas');
                    const MAX_WIDTH = 800;
                    const scale = MAX_WIDTH / img.width;
                    
                    if (img.width > MAX_WIDTH) {
                        canvas.width = MAX_WIDTH;
                        canvas.height = img.height * scale;
                    } else {
                        canvas.width = img.width;
                        canvas.height = img.height;
                    }

                    const ctx = canvas.getContext('2d');
                    ctx.drawImage(img, 0, 0, canvas.width, canvas.height);
                    const compressedBase64 = canvas.toDataURL('image/jpeg', 0.7);

                    document.getElementById('formImageData').value = compressedBase64;
                    document.getElementById('formImgPreview').src = compressedBase64;
                    document.getElementById('formImgPreview').classList.remove('hidden');
                    document.getElementById('formImgPlaceholder').classList.add('hidden');
                }
            }
            reader.readAsDataURL(file);
        }

        function setPresetPlaceholder() {
            const name = document.getElementById('formCropName').value.trim() || '野菜';
            const category = document.getElementById('formCategory').value;
            
            const keywords = {
                vegetable: 'vegetable,tomato,garden',
                fruit: 'fruit,strawberry,melon',
                herb: 'mint,basil,herb',
                flower: 'flower,succulent,plant'
            };
            const kw = keywords[category] || 'nature,farm';
            const randomSig = Math.floor(Math.random() * 1000);
            
            // Unsplashより高画質な自然な画像をセット
            const imageUrl = `https://images.unsplash.com/photo-1592417817098-8f3d6eb19675?w=1000&auto=format&fit=crop&q=80&sig=${randomSig}&q=${encodeURIComponent(name)}`;

            document.getElementById('formImageData').value = imageUrl;
            document.getElementById('formImgPreview').src = imageUrl;
            document.getElementById('formImgPreview').classList.remove('hidden');
            document.getElementById('formImgPlaceholder').classList.add('hidden');
            
            showToast('作物のカテゴリに合った、綺麗な仮写真を自動セットしました！');
        }

        // --- ユーティリティ & 自作ダイアログ ---
        function formatDate(dateStr) {
            if (!dateStr) return '';
            const d = new Date(dateStr);
            if (isNaN(d.getTime())) return dateStr;
            return `${d.getFullYear()}年${d.getMonth() + 1}月${d.getDate()}日`;
        }

        // トースト通知
        function showToast(message, type = 'success') {
            const container = document.getElementById('toastContainer');
            const toast = document.createElement('div');
            toast.className = 'flex items-center space-x-2 px-4 py-3 rounded-xl shadow-lg border text-xs font-bold transition-all duration-300 transform translate-y-2 opacity-0 pointer-events-auto bg-white max-w-sm';
            
            let icon = '<i class="fa-solid fa-circle-check text-emerald-500 text-base"></i>';
            if (type === 'error') {
                toast.classList.add('border-red-200', 'text-red-800');
                icon = '<i class="fa-solid fa-circle-exclamation text-red-500 text-base"></i>';
            } else {
                toast.classList.add('border-emerald-200', 'text-emerald-800');
            }

            toast.innerHTML = `${icon}<span>${message}</span>`;
            container.appendChild(toast);

            setTimeout(() => {
                toast.classList.remove('translate-y-2', 'opacity-0');
            }, 50);

            setTimeout(() => {
                toast.classList.add('translate-y-2', 'opacity-0');
                setTimeout(() => toast.remove(), 300);
            }, 3000);
        }

        // おしゃれな自作確認ダイアログ
        function openConfirm(message, onOkCallback) {
            const modal = document.getElementById('confirmModal');
            document.getElementById('confirmMessage').textContent = message;

            const onOk = () => {
                onOkCallback();
                closeConfirm();
                cleanupListeners();
            };
            const onCancel = () => {
                closeConfirm();
                cleanupListeners();
            };

            const cleanupListeners = () => {
                document.getElementById('confirmOkBtn').removeEventListener('click', onOk);
                document.getElementById('confirmCancelBtn').removeEventListener('click', onCancel);
            };

            document.getElementById('confirmOkBtn').addEventListener('click', onOk);
            document.getElementById('confirmCancelBtn').addEventListener('click', onCancel);

            modal.classList.remove('pointer-events-none');
            modal.classList.add('opacity-100');
            modal.querySelector('div').classList.remove('scale-95');
        }

        function closeConfirm() {
            const modal = document.getElementById('confirmModal');
            modal.classList.add('pointer-events-none');
            modal.classList.remove('opacity-100');
            modal.querySelector('div').classList.add('scale-95');
        }
    </script>
</body>
</html>
