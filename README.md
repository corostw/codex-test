<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <title>COROS 手錶規格比較表</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* 整體頁面樣式 */
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8f9fa;
            margin: 0;
            padding: 15px;
        }
        
        /* 表格樣式優化 */
        #comparisonTable {
            border-collapse: collapse;
            width: 100%;
            margin-top: 20px;
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            background-color: #fff;
            table-layout: fixed;
        }
        
        #comparisonTable th,
        #comparisonTable td {
            padding: 12px 15px;
            border: 1px solid #e0e0e0;
        }
        
        #comparisonTable th {
            background-color: #f5f5f5;
            font-weight: 600;
            text-align: left;
            padding: 15px;
        }
        
        /* 表頭行高增加 */
        #comparisonTable thead tr {
            height: 80px;
        }
        
        /* 下拉選單樣式美化 */
        .watch-selector {
            width: 100%;
            padding: 12px 15px;
            font-size: 16px;
            border: 2px solid #4285f4;
            border-radius: 6px;
            background-color: white;
            color: #333;
            font-weight: 500;
            cursor: pointer;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
            background-image: url("data:image/svg+xml;charset=UTF-8,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='%234285f4' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'%3e%3cpolyline points='6 9 12 15 18 9'%3e%3c/polyline%3e%3c/svg%3e");
            background-repeat: no-repeat;
            background-position: right 10px center;
            background-size: 16px;
            padding-right: 40px;
        }
        
        .watch-selector:hover {
            border-color: #2b68ca;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
        }
        
        .watch-selector:focus {
            outline: none;
            border-color: #1a56b5;
            box-shadow: 0 0 0 3px rgba(66, 133, 244, 0.3);
        }
        
        /* 分區標題加強 */
        #comparisonTable tbody tr:first-child td,
        #comparisonTable tbody tr td[bgcolor="#e9ecef"] {
            background-color: #e9ecef;
            font-weight: bold;
            font-size: 17px;
            padding: 12px 15px;
            color: #333;
        }
        
        /* 標籤列加強 */
        #comparisonTable td[bgcolor="#f9f9f9"] {
            background-color: #f9f9f9;
            font-weight: 500;
        }
        
        /* 購買按鈕美化 */
        .purchase-button {
            display: inline-block;
            padding: 8px 16px;
            background-color: #4285f4;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            font-weight: 500;
            transition: background-color 0.3s;
        }
        
        .purchase-button:hover {
            background-color: #1a56b5;
        }
        
        /* 欄位寬度設定 - 桌面版 */
        #comparisonTable th:first-child,
        #comparisonTable td:first-child {
            width: 20%;
        }
        
        #comparisonTable th:not(:first-child),
        #comparisonTable td:not(:first-child) {
            width: 26.66%;
        }
        
        /* 圖片控制 */
        #comparisonTable img {
            max-width: 100%;
            height: auto;
        }
        
        /* 響應式設計優化 */
        @media (max-width: 767px) {
            .watch-selector {
                padding: 12px 30px 12px 10px;
                font-size: 16px;
                margin-bottom: 5px;
                background-position: right 8px center;
                background-size: 12px;
            }
            
            #comparisonTable th,
            #comparisonTable td {
                padding: 10px 12px;
            }
            
            /* 在手機版中更明顯標記表頭 */
            #comparisonTable thead tr {
                height: 80px;
            }
            
            /* 重新調整手機版的欄位寬度比例 */
            #comparisonTable {
                table-layout: fixed;
            }
            
            #comparisonTable th:first-child,
            #comparisonTable td:first-child {
                width: 80px !important;
                min-width: 80px !important;
                max-width: 80px !important;
            }
            
            #comparisonTable th:not(:first-child),
            #comparisonTable td:not(:first-child) {
                width: auto !important;
            }
            
            /* 控制圖片在手機版的大小 */
            #comparisonTable img {
                max-width: 100%;
                height: auto;
                display: block;
                margin: 0 auto;
            }
        }
    </style>
</head>
<body>

<table id="comparisonTable" border="1" cellpadding="8" cellspacing="0" width="100%">
    <thead>
        <tr>
            <th bgcolor="#f5f5f5" align="left">規格</th>
            <th bgcolor="#f5f5f5" align="left">
                <select class="watch-selector" data-column="1">
                    <option value="PACE3" selected>PACE 3</option>
                    <option value="PACEPro">PACE Pro</option>
                    <option value="APEX2">APEX 2</option>
                    <option value="APEX2Pro">APEX 2 Pro</option>
                    <option value="VERTIX2S">VERTIX 2S</option>
                </select>
            </th>
            <th bgcolor="#f5f5f5" align="left">
                <select class="watch-selector" data-column="2">
                    <option value="PACE3">PACE 3</option>
                    <option value="PACEPro" selected>PACE Pro</option>
                    <option value="APEX2">APEX 2</option>
                    <option value="APEX2Pro">APEX 2 Pro</option>
                    <option value="VERTIX2S">VERTIX 2S</option>
                </select>
            </th>
            <th bgcolor="#f5f5f5" align="left" class="desktop-only">
                <select class="watch-selector" data-column="3">
                    <option value="PACE3">PACE 3</option>
                    <option value="PACEPro">PACE Pro</option>
                    <option value="APEX2">APEX 2</option>
                    <option value="APEX2Pro" selected>APEX 2 Pro</option>
                    <option value="VERTIX2S">VERTIX 2S</option>
                </select>
            </th>
        </tr>
    </thead>
    <tbody></tbody>
</table>

<script>
    
    // 表格結構定義
    const tableStructure = [
        { 
            header: '基本資訊',
            fields: [
                { id: 'position', label: '定位' },
                { id: 'image', label: '圖片' },
                { id: 'price', label: '價格' },
                { id: 'shopnow', label: '購買連結' }
            ]
        },
        {
            header: '螢幕規格',
            fields: [
                { id: 'displaySize', label: '螢幕尺寸' },
                { id: 'resolution', label: '螢幕解析度' },
                { id: 'displayType', label: '螢幕種類' },
                { id: 'screenMaterial', label: '螢幕材質' },
                { id: 'bezelMaterial', label: '錶圈外環材質' },
                { id: 'coverMaterial', label: '外殼材質' }
            ]
        },
        {
            header: '尺寸與重量',
            fields: [
                { id: 'bandMaterial', label: '錶帶材質' },
                { id: 'bandWidth', label: '快拆錶帶尺寸' },
                { id: 'dimensions', label: '手錶主機尺寸' },
                { id: 'weightWithSiliconeBand', label: '配戴矽膠錶帶的重量' },
                { id: 'weightWithNylonBand', label: '配戴尼龍錶環的重量' }
            ]
        },
        {
            header: '電池續航',
            fields: [
                { id: 'batteryGPS', label: 'GPS 精準模式' },
                { id: 'batteryGPSMusic', label: 'GPS 精準模式 + 音樂播放' },
                { id: 'allSystemsOn', label: '全星座模式' },
                { id: 'allSystemsOnMusic', label: '全星座模式 + 音樂播放' },
                { id: 'dualFrequency', label: '雙頻全星座模式' },
                { id: 'dualFrequencyMusic', label: '雙頻全星座模式 + 音樂播放' },
                { id: 'dailyUse', label: '日常與睡眠追蹤續航' }
            ]
        },
        {
            header: '感測器',
            fields: [
                { id: 'sensors', label: '感測器' }
            ]
        },
        {
            header: '功能特色',
            fields: [
                { id: 'trainingFeatures', label: '訓練相關' },
                { id: 'dailyFeatures', label: '日常使用' }
            ]
        },
        {
            header: '系統與連接',
            fields: [
                { id: '3rdPartyIntegration', label: '支援的第三方APP' },
                { id: 'systemLanguages', label: '系統語言' },
                { id: 'backLightButton', label: '背光啟閉專用按鍵' },
                { id: 'touchScreen', label: '觸控螢幕模式' },
                { id: 'offlineMusic', label: '離線音樂' },
                { id: 'memory', label: '內存記憶體' },
                { id: 'activityMemory', label: '運動記憶體' }
            ]
        },
        {
            header: '導航相關',
            fields: [
                { id: 'satelliteSystems', label: '衛星系統' },
                { id: 'gnssChipset', label: '衛星定位晶片' },
                { id: 'navigationMapLayer', label: '導航地圖類型' },
                { id: 'additionalFeatures', label: '導航功能' }
            ]
        },
        {
            header: '運動模式',
            fields: [
                { id: 'run', label: '跑步' },
                { id: 'climb', label: '山地' },
                { id: 'bike', label: '自行車' },
                { id: 'water', label: '水上運動' },
                { id: 'winter', label: '冬季運動' },
                { id: 'cardio', label: '有氧運動' },
                { id: 'special', label: '其他' }
            ]
        }
    ];


    // 產品資料
    const watchData = {
    'PACE3': {
        position: '輕量級競速',
        image: '<img src="//cdn1.cybassets.com/s/files/19443/ckeditor/pictures/content_ebceeb0e-9488-4463-bdd4-8ee74c61be51.png" alt="COROS PACE 3" width="150" height="150">',
        price: 'NT$ 7,490',
        shopnow: '<a href="https://www.corostw.com/products/pace3" target="_blank" rel="noopener noreferrer" class="purchase-button">PACE 3</a>',
        displaySize: '1.2 英寸',
        resolution: '240 x 240 (64 色)',
        displayType: '觸控式 MIP\n隨顯記憶液晶',
        screenMaterial: '礦物玻璃',
        bezelMaterial: '高強度聚合物',
        coverMaterial: '高強度聚合物',
        bandMaterial: '矽膠/織物',
        bandWidth: '22mm',
        dimensions: '41.9 x 41.9 x 11.7mm',
        weightWithSiliconeBand: '39g',
        weightWithNylonBand: '30g',
        batteryGPS: '38 小時',
        batteryGPSMusic: '10 小時',
        allSystemsOn: '25 小時',
        allSystemsOnMusic: '9 小時',
        dualFrequency: '15 小時',
        dualFrequencyMusic: '7 小時',
        dailyUse: '15 天',
        sensors: `光電心率
氣壓高度計
加速度計
陀螺儀
3D指南針
溫度計\n<span style="font-size: 0.9em; color: #757582;">記錄訓練時體溫資料（透過連接第三方配件）</span>
光電血氧感知器`,
        trainingFeatures: `等強配速
EvoLab 跑步能力\n<span style="font-size: 0.9em; color: #757582;">成績預測、本週負荷、訓練量評估、體力恢復等</span>
運動提醒\n<span style="font-size: 0.9em; color: #757582;">步頻，距離，配速，心率，功率等</span>
間歇訓練
訓練課程
訓練計劃
跑步能力
靜止心率
水下心率
相機遙控\n<span style="font-size: 0.9em; color: #757582;">支援部分運動相機</span>
目標跑 (虛擬領跑員)
虛擬跑步
跑姿測試\n<span style="font-size: 0.9em; color: #757582;">需要連接COROS POD或COROS POD 2</span>
<a href="https://support.corostw.com/coros-qa/how-to-use-warch/blood-oxygen-detection" target="_blank">高原守護</a>
觸控螢幕翻頁
螢幕鏡射`,
        dailyFeatures: `全天壓力
健康快測
訊息通知\n<span style="font-size: 0.9em; color: #757582;">日常使用和訓練中均可</span>
睡眠監測\n<span style="font-size: 0.9em; color: #757582;">支援快速動眼睡眠監測</span>
鬧鐘
計時器
碼表
日常提醒\n<span style="font-size: 0.9em; color: #757582;">包括運動卡路里，運動時間，暴風雨預警等</span>
韌體更新\n<span style="font-size: 0.9em; color: #757582;">透過 Wi-Fi 和 COROS APP</span>
尋找手機
尋找手錶
夜光模式
HRV測量
音樂\n<span style="font-size: 0.9em; color: #757582;">配對藍牙耳機，播放離線音樂</span>`,
        '3rdPartyIntegration': 'Nike Run Club, Komoot, TrainingPeaks, Strava, Relive, adidas Running, Apple Health, Stryd, Final Surge, Runalyze, Running Quotient, Decathlon…',
        systemLanguages: '繁體中文，簡體中文，英語，德語，西班牙語，法語，波蘭語，泰語，日語，韓語，葡萄牙語，義大利語，俄語，越南語',
        backLightButton: '',
        touchScreen: '○',
        offlineMusic: '○',
        memory: '4 GB',
        activityMemory: '1200 小時',
        satelliteSystems: 'GPS, GLONASS, Galileo, Beidou, QZSS',
        gnssChipset: '雙頻全星座',
        navigationMapLayer: '麵包屑導航\n—\n—',
        additionalFeatures: 'CP點\n循跡返航\n偏航提醒\n觸控螢幕控制',
        run: '跑步\n跑步機\n運動場跑步\n虛擬跑步\n越野跑',
        climb: '—\n—\n—\n—',
        bike: '自行車\n室內自行車\n礫石路\n山地',
        water: '公開水域游泳\n泳池游泳\n靜水運動\n賽艇\n—\n—\n—',
        winter: '雪場雙板\n雪場單板\n越野滑雪\n--',
        cardio: '戶外有氧\n室內有氧\n徒步\n划船機\n健走\n跳繩',
        special: '鐵人三項\n組合運動\n健身\n訓練組合\n訓練計劃'
    },
    'APEX2Pro': {
        position: '長距離越野競速',
        image: '<img src="//cdn1.cybassets.com/s/files/19443/ckeditor/pictures/content_452539b5-99fd-4853-af69-36d563f18fb2.png" alt="APEX 2 Pro" width="150" height="150">',
        price: 'NT$ 14,900',
        shopnow: '<a href="https://www.corostw.com/products/apex2pro" target="_blank" rel="noopener noreferrer" class="purchase-button">APEX 2 Pro</a>',
        displaySize: '1.3 英寸',
        resolution: '260 x 260 (64 色)',
        displayType: '觸控式 MIP\n隨顯記憶液晶',
        screenMaterial: '藍寶石玻璃',
        bezelMaterial: '等級5鈦合金\n+ PVD 塗層',
        coverMaterial: '等級5鈦合金\n+ PVD 塗層',
        bandMaterial: '矽膠/織物',
        bandWidth: '22mm',
        dimensions: '46.1 x 46.5 x 14mm',
        weightWithSiliconeBand: '66g',
        weightWithNylonBand: '53g',
        batteryGPS: '66 小時',
        batteryGPSMusic: '18 小時',
        allSystemsOn: '41 小時',
        allSystemsOnMusic: '15 小時',
        dualFrequency: '24 小時',
        dualFrequencyMusic: '12 小時',
        dailyUse: '21 天',
        sensors: `光電心率
氣壓高度計
加速度計
陀螺儀
3D指南針
溫度計\n<span style="font-size: 0.9em; color: #757582;">記錄訓練時體溫資料（透過連接第三方配件）</span>
光電血氧感知器`,
        trainingFeatures: `等強配速
EvoLab 跑步能力\n<span style="font-size: 0.9em; color: #757582;">成績預測、本週負荷、訓練量評估、體力恢復等</span>
運動提醒\n<span style="font-size: 0.9em; color: #757582;">步頻，距離，配速，心率，功率等</span>
間歇訓練
訓練課程
訓練計劃
跑步能力
靜止心率
水下心率
相機遙控\n<span style="font-size: 0.9em; color: #757582;">支援部分運動相機</span>
目標跑 (虛擬領跑員)
虛擬跑步
跑姿測試\n<span style="font-size: 0.9em; color: #757582;">需要連接COROS POD或COROS POD 2</span>
<a href="https://support.corostw.com/coros-qa/how-to-use-warch/blood-oxygen-detection" target="_blank">高原守護</a>
觸控螢幕翻頁
螢幕鏡射`,
        dailyFeatures: `全天壓力
健康快測
訊息通知\n<span style="font-size: 0.9em; color: #757582;">日常使用和訓練中均可</span>
睡眠監測\n<span style="font-size: 0.9em; color: #757582;">支援快速動眼睡眠監測</span>
鬧鐘
計時器
碼表
日常提醒\n<span style="font-size: 0.9em; color: #757582;">包括運動卡路里，運動時間，暴風雨預警等</span>
韌體更新\n<span style="font-size: 0.9em; color: #757582;">透過 Wi-Fi 和 COROS APP</span>
尋找手機
尋找手錶
夜光模式
HRV測量
音樂\n<span style="font-size: 0.9em; color: #757582;">配對藍牙耳機，播放離線音樂</span>`,
        '3rdPartyIntegration': 'Nike Run Club, Komoot, TrainingPeaks, Strava, Relive, adidas Running, Apple Health, Stryd, Final Surge, Runalyze, Running Quotient, Decathlon…',
        systemLanguages: '繁體中文，簡體中文，英語，德語，西班牙語，法語，波蘭語，泰語，日語，韓語，葡萄牙語，義大利語，俄語，越南語',
        backLightButton: '○',
        touchScreen: '○',
        offlineMusic: '○',
        memory: '32 GB',
        activityMemory: '1200 小時',
        satelliteSystems: 'GPS, GLONASS, Galileo, Beidou, QZSS',
        gnssChipset: '雙頻全星座',
        navigationMapLayer: '離線地圖\n地貌圖\n等高線圖',
        additionalFeatures: 'CP點\n循跡返航\n偏航提醒\n觸控螢幕控制',
        run: '跑步\n跑步機\n運動場跑步\n虛擬跑步\n越野跑',
        climb: '戶外攀登\n室內攀岩\n登山\n抱石',
        bike: '自行車\n室內自行車\n礫石路\n山地',
        water: '公開水域游泳\n泳池游泳\n靜水運動\n賽艇\n激流運動\n競速風帆\n滑浪風帆',
        winter: '雪場雙板\n雪場單板\n越野滑雪\n登山滑雪',
        cardio: '戶外有氧\n室內有氧\n徒步\n划船機\n健走\n跳繩',
        special: '鐵人三項\n組合運動\n健身\n訓練組合\n訓練計劃'
    },
    'APEX2': {
        position: '戶外越野競速',
        image: '<img src="//cdn1.cybassets.com/s/files/19443/ckeditor/pictures/content_2e3c467a-70b6-4c7b-9efb-0f17b0157c5a.png" alt="APEX 2" width="150" height="150">',
        price: 'NT$ 11,500',
        shopnow: '<a href="https://www.corostw.com/products/apex2" target="_blank" rel="noopener noreferrer" class="purchase-button">APEX 2</a>',
        displaySize: '1.2 英寸',
        resolution: '240 x 240 (64 色)',
        displayType: '觸控式 MIP\n隨顯記憶液晶',
        screenMaterial: '藍寶石玻璃',
        bezelMaterial: '等級5鈦合金\n+ PVD 塗層',
        coverMaterial: '等級5鈦合金\n+ PVD 塗層',
        bandMaterial: '矽膠/織物',
        bandWidth: '20mm',
        dimensions: '43.0 x 42.8 x 12.8mm',
        weightWithSiliconeBand: '53g',
        weightWithNylonBand: '42g',
        batteryGPS: '40 小時',
        batteryGPSMusic: '10 小時',
        allSystemsOn: '25 小時',
        allSystemsOnMusic: '9 小時',
        dualFrequency: '--',
        dualFrequencyMusic: '--',
        dailyUse: '13 天',
        sensors: `光電心率
氣壓高度計
加速度計
陀螺儀
3D指南針
溫度計\n<span style="font-size: 0.9em; color: #757582;">記錄訓練時體溫資料（透過連接第三方配件）</span>
光電血氧感知器`,
        trainingFeatures: `等強配速
EvoLab 跑步能力\n<span style="font-size: 0.9em; color: #757582;">成績預測、本週負荷、訓練量評估、體力恢復等</span>
運動提醒\n<span style="font-size: 0.9em; color: #757582;">步頻，距離，配速，心率，功率等</span>
間歇訓練
訓練課程
訓練計劃
跑步能力
靜止心率
水下心率
相機遙控\n<span style="font-size: 0.9em; color: #757582;">支援部分運動相機</span>
目標跑 (虛擬領跑員)
虛擬跑步
跑姿測試\n<span style="font-size: 0.9em; color: #757582;">需要連接COROS POD或COROS POD 2</span>
<a href="https://support.corostw.com/coros-qa/how-to-use-warch/blood-oxygen-detection" target="_blank">高原守護</a>
觸控螢幕翻頁
螢幕鏡射`,
        dailyFeatures: `全天壓力
健康快測
訊息通知\n<span style="font-size: 0.9em; color: #757582;">日常使用和訓練中均可</span>
睡眠監測\n<span style="font-size: 0.9em; color: #757582;">支援快速動眼睡眠監測</span>
鬧鐘
計時器
碼表
日常提醒\n<span style="font-size: 0.9em; color: #757582;">包括運動卡路里，運動時間，暴風雨預警等</span>
韌體更新\n<span style="font-size: 0.9em; color: #757582;">透過 Wi-Fi 和 COROS APP</span>
尋找手機
尋找手錶
夜光模式
HRV測量
音樂\n<span style="font-size: 0.9em; color: #757582;">配對藍牙耳機，播放離線音樂</span>`,
        '3rdPartyIntegration': 'Nike Run Club, Komoot, TrainingPeaks, Strava, Relive, adidas Running, Apple Health, Stryd, Final Surge, Runalyze, Running Quotient, Decathlon…',
        systemLanguages: '繁體中文，簡體中文，英語，德語，西班牙語，法語，波蘭語，泰語，日語，韓語，葡萄牙語，義大利語，俄語，越南語',
        backLightButton: '○',
        touchScreen: '○',
        offlineMusic: '○',
        memory: '8 GB',
        activityMemory: '1200 小時',
        satelliteSystems: 'GPS, GLONASS, Galileo, Beidou, QZSS',
        gnssChipset: '單頻全星座',
        navigationMapLayer: '離線地圖\n地貌圖\n等高線圖',
        additionalFeatures: 'CP點\n循跡返航\n偏航提醒\n觸控螢幕控制',
        run: '跑步\n跑步機\n運動場跑步\n虛擬跑步\n越野跑',
        climb: '戶外攀登\n室內攀岩\n登山\n抱石',
        bike: '自行車\n室內自行車\n礫石路\n山地',
        water: '公開水域游泳\n泳池游泳\n靜水運動\n賽艇\n激流運動\n競速風帆\n滑浪風帆',
        winter: '雪場雙板\n雪場單板\n越野滑雪\n登山滑雪',
        cardio: '戶外有氧\n室內有氧\n徒步\n划船機\n健走\n跳繩',
        special: '鐵人三項\n組合運動\n健身\n訓練組合\n訓練計劃'
    },
        'VERTIX2S': {
        position: '極限戶外運動',
        image: '<img src="//cdn1.cybassets.com/s/files/19443/ckeditor/pictures/content_76c5b9b5-8c2c-4381-bd14-6868829d43c1.jpg" alt="VERTIX2S" width="150" height="150">',
        price: 'NT$ 22,900',
        shopnow: '<a href="https://www.corostw.com/products/vertix2s" target="_blank" rel="noopener noreferrer" class="purchase-button">VERTIX 2S</a>',
        displaySize: '1.4 英寸',
        resolution: '280 x 280 (64 色)',
        displayType: '觸控式 MIP\n隨顯記憶液晶',
        screenMaterial: '藍寶石玻璃',
        bezelMaterial: '等級5鈦合金\n+ PVD 塗層',
        coverMaterial: '等級5鈦合金\n+ PVD 塗層',
        bandMaterial: '矽膠/織物',
        bandWidth: '26mm',
        dimensions: '50.3 x 50.3 x 15.7mm',
        weightWithSiliconeBand: '89g',
        weightWithNylonBand: '72g',
        batteryGPS: '118 小時',
        batteryGPSMusic: '32 小時',
        allSystemsOn: '73 小時',
        allSystemsOnMusic: '27 小時',
        dualFrequency: '43 小時',
        dualFrequencyMusic: '22 小時',
        dailyUse: '40 天',
        sensors: `光電心率
氣壓高度計
加速度計
陀螺儀
3D指南針
溫度計\n<span style="font-size: 0.9em; color: #757582;">記錄訓練時體溫資料（透過連接第三方配件）</span>
光電血氧感知器`,
        trainingFeatures: `等強配速
EvoLab 跑步能力\n<span style="font-size: 0.9em; color: #757582;">成績預測、本週負荷、訓練量評估、體力恢復等</span>
運動提醒\n<span style="font-size: 0.9em; color: #757582;">步頻，距離，配速，心率，功率等</span>
間歇訓練
訓練課程
訓練計劃
跑步能力
靜止心率
水下心率
相機遙控\n<span style="font-size: 0.9em; color: #757582;">支援部分運動相機</span>
目標跑 (虛擬領跑員)
虛擬跑步
跑姿測試\n<span style="font-size: 0.9em; color: #757582;">需要連接COROS POD或COROS POD 2</span>
<a href="https://support.corostw.com/coros-qa/how-to-use-warch/blood-oxygen-detection" target="_blank">高原守護</a>
觸控螢幕翻頁
螢幕鏡射`,
        dailyFeatures: `全天壓力
健康快測
訊息通知\n<span style="font-size: 0.9em; color: #757582;">日常使用和訓練中均可</span>
睡眠監測\n<span style="font-size: 0.9em; color: #757582;">支援快速動眼睡眠監測</span>
鬧鐘
計時器
碼表
日常提醒\n<span style="font-size: 0.9em; color: #757582;">包括運動卡路里，運動時間，暴風雨預警等</span>
韌體更新\n<span style="font-size: 0.9em; color: #757582;">透過 Wi-Fi 和 COROS APP</span>
尋找手機
尋找手錶
夜光模式
HRV測量
音樂\n<span style="font-size: 0.9em; color: #757582;">配對藍牙耳機，播放離線音樂</span>`,
        '3rdPartyIntegration': 'Nike Run Club, Komoot, TrainingPeaks, Strava, Relive, adidas Running, Apple Health, Stryd, Final Surge, Runalyze, Running Quotient, Decathlon…',
        systemLanguages: '繁體中文，簡體中文，英語，德語，西班牙語，法語，波蘭語，泰語，日語，韓語，葡萄牙語，義大利語，俄語，越南語',
        backLightButton: '○',
        touchScreen: '○',
        offlineMusic: '○',
        memory: '32 GB',
        activityMemory: '1200 小時',
        satelliteSystems: 'GPS, GLONASS, Galileo, Beidou, QZSS',
        gnssChipset: '雙頻全星座',
        navigationMapLayer: '離線地圖\n地貌圖\n等高線圖',
        additionalFeatures: 'CP點\n循跡返航\n偏航提醒\n觸控螢幕控制',
        run: '跑步\n跑步機\n運動場跑步\n虛擬跑步\n越野跑',
        climb: '戶外攀登\n室內攀岩\n登山\n抱石',
        bike: '自行車\n室內自行車\n礫石路\n山地',
        water: '公開水域游泳\n泳池游泳\n靜水運動\n賽艇\n激流運動\n競速風帆\n滑浪風帆',
        winter: '雪場雙板\n雪場單板\n越野滑雪\n登山滑雪',
        cardio: '戶外有氧\n室內有氧\n徒步\n划船機\n健走\n跳繩',
        special: '鐵人三項\n組合運動\n健身\n訓練組合\n訓練計劃'
    },
    'PACEPro': {
        position: '超高精準度競技運動',
        image: '<img src="//cdn1.cybassets.com/s/files/19443/ckeditor/pictures/content_356ff564-3d30-4b3e-961c-9ea7b8de6f62.png" alt="PACE Pro" width="150" height="150">',
        price: 'NT$ 11,500',
        shopnow: '<a href="https://www.corostw.com/products/pacepro" target="_blank" rel="noopener noreferrer" class="purchase-button">PACE Pro</a>',
        displaySize: '1.3 英寸',
        resolution: '416 x 416 (全彩)',
        displayType: 'AMOLED\n隨顯全彩觸控螢幕',
        screenMaterial: '礦物玻璃',
        bezelMaterial: '高強度聚合物',
        coverMaterial: '高強度聚合物',
        bandMaterial: '矽膠/織物',
        bandWidth: '22mm',
        dimensions: '46 x 46 x 12.25mm',
        weightWithSiliconeBand: '49 公克',
        weightWithNylonBand: '37 公克',
        batteryGPS: '—',
        batteryGPSMusic: '—',
        allSystemsOn: '38 小時\n28 小時 (開啟隨顯)',
        allSystemsOnMusic: '13 小時\n11 小時 (開啟隨顯)',
        dualFrequency: '31 小時\n24 小時 (開啟隨顯)',
        dualFrequencyMusic: '12 小時\n10 小時 (開啟隨顯)',
        dailyUse: '約 20 天\n約 6 天 (開啟隨顯)',
        sensors: `光電心率
氣壓高度計
加速度計
陀螺儀
3D指南針
溫度計\n<span style="font-size: 0.9em; color: #757582;">記錄訓練時體溫資料（透過連接第三方配件）</span>
光電血氧感知器`,
        trainingFeatures: `等強配速
EvoLab 跑步能力\n<span style="font-size: 0.9em; color: #757582;">成績預測、本週負荷、訓練量評估、體力恢復等</span>
運動提醒\n<span style="font-size: 0.9em; color: #757582;">步頻，距離，配速，心率，功率等</span>
間歇訓練
訓練課程
訓練計劃
跑步能力
靜止心率
水下心率
相機遙控\n<span style="font-size: 0.9em; color: #757582;">支援部分運動相機</span>
目標跑 (虛擬領跑員)
虛擬跑步
跑姿測試\n<span style="font-size: 0.9em; color: #757582;">需要連接COROS POD或COROS POD 2</span>
<a href="https://support.corostw.com/coros-qa/how-to-use-warch/blood-oxygen-detection" target="_blank">高原守護</a>
觸控螢幕翻頁
螢幕鏡射`,
        dailyFeatures: `全天壓力
健康快測
訊息通知\n<span style="font-size: 0.9em; color: #757582;">日常使用和訓練中均可</span>
睡眠監測\n<span style="font-size: 0.9em; color: #757582;">支援快速動眼睡眠監測</span>
鬧鐘
計時器
碼表
日常提醒\n<span style="font-size: 0.9em; color: #757582;">包括運動卡路里，運動時間，暴風雨預警等</span>
韌體更新\n<span style="font-size: 0.9em; color: #757582;">透過 Wi-Fi 和 COROS APP</span>
尋找手機
尋找手錶
夜光模式
HRV測量
音樂\n<span style="font-size: 0.9em; color: #757582;">配對藍牙耳機，播放離線音樂</span>`,
        '3rdPartyIntegration': 'Nike Run Club, Komoot, TrainingPeaks, Strava, Relive, adidas Running, Apple Health, Stryd, Final Surge, Runalyze, Running Quotient, Decathlon…',
        systemLanguages: '繁體中文，簡體中文，英語，德語，西班牙語，法語，波蘭語，泰語，日語，韓語，葡萄牙語，義大利語，俄語，越南語',
        backLightButton: '',
        touchScreen: '○',
        offlineMusic: '○',
        memory: '32 GB',
        activityMemory: '1200 小時',
        satelliteSystems: 'GPS, GLONASS, Galileo, Beidou, QZSS',
        gnssChipset: '雙頻全星座',
        navigationMapLayer: '離線地圖\n地貌圖\n等高線圖',
        additionalFeatures: 'CP點\n循跡返航\n偏航提醒\n觸控螢幕控制',
        run: '跑步\n跑步機\n運動場跑步\n虛擬跑步\n越野跑',
        climb: '—\n—\n—\n—',
        bike: '自行車\n室內自行車\n礫石路\n山地',
        water: '公開水域游泳\n泳池游泳\n靜水運動\n賽艇\n—\n—\n—',
        winter: '雪場雙板\n雪場單板\n越野滑雪\n--',
        cardio: '戶外有氧\n室內有氧\n徒步\n划船機\n健走\n跳繩',
        special: '鐵人三項\n組合運動\n健身\n訓練組合\n訓練計劃'
    }
    };

(function() {
    // 檢查是否為行動裝置
    let isMobile = window.innerWidth < 768;
    
    // 獲取所有可用的手錶選項
    const watchOptions = [
        { value: 'PACE3', label: 'PACE 3' },
        { value: 'PACEPro', label: 'PACE Pro' },
        { value: 'APEX2', label: 'APEX 2' },
        { value: 'APEX2Pro', label: 'APEX 2 Pro' },
        { value: 'VERTIX2S', label: 'VERTIX 2S' }
    ];

    // 表格結構定義和產品資料保持不變
    // ... 您原有的 tableStructure 和 watchData 定義 ...

    // 生成表格內容
function generateTable() {
    const tbody = document.querySelector('#comparisonTable tbody');
    tbody.innerHTML = '';

    const specialLabels = {
        'batteryGPS': {
            main: 'GPS 精準模式',
            sub: '(GPS/QZSS)'
        },
        'batteryGPSMusic': {
            main: 'GPS 精準模式 + 音樂播放',
            sub: '(GPS/QZSS)'
        },
        'allSystemsOn': {
            main: '全星座模式',
            sub: '同時接收GPS, GLONASS, Galileo, Beidou, QZSS訊號'
        },
        'allSystemsOnMusic': {
            main: '全星座模式 + 音樂播放',
            sub: '同時接收GPS, GLONASS, Galileo, Beidou, QZSS訊號'
        },
        'dualFrequency': {
            main: '雙頻全星座模式',
            sub: '同時以兩個頻率接收GPS, GLONASS, Galileo, Beidou, QZSS訊號'
        },
        'dualFrequencyMusic': {
            main: '雙頻全星座模式 + 音樂播放',
            sub: '同時以兩個頻率接收GPS, GLONASS, Galileo, Beidou, QZSS訊號'
        }
    };

    tableStructure.forEach(section => {
        const headerRow = document.createElement('tr');
        const headerCell = document.createElement('td');
        headerCell.setAttribute('bgcolor', '#e9ecef');
        headerCell.setAttribute('align', 'left');
        headerCell.setAttribute('colspan', isMobile ? 3 : 4);
        headerCell.textContent = section.header;
        headerRow.appendChild(headerCell);
        tbody.appendChild(headerRow);

        section.fields.forEach(field => {
            const row = document.createElement('tr');
            
            const labelCell = document.createElement('td');
            labelCell.setAttribute('bgcolor', '#f9f9f9');
            labelCell.setAttribute('align', 'left');
            
            if (specialLabels[field.id]) {
                const mainText = document.createElement('div');
                mainText.textContent = specialLabels[field.id].main;
                
                const subText = document.createElement('div');
                subText.style.fontSize = '0.9em';
                subText.style.color = '#757582';
                subText.textContent = specialLabels[field.id].sub;
                
                labelCell.appendChild(mainText);
                labelCell.appendChild(subText);
            } else {
                labelCell.textContent = field.label;
            }
            
            row.appendChild(labelCell);

            for (let i = 1; i <= (isMobile ? 2 : 3); i++) {
                const dataCell = document.createElement('td');
                dataCell.setAttribute('align', field.id === 'image' || field.id === 'shopnow' ? 'center' : 'left');
                dataCell.setAttribute('data-field', field.id);
                row.appendChild(dataCell);
            }

            tbody.appendChild(row);
        });
    });
}

    // 更新選擇器選項
// 更新選擇器選項
function updateSelectOptions() {
    const selectors = document.querySelectorAll('.watch-selector');
    const currentSelections = Array.from(selectors)
        .filter((_, index) => !isMobile || index < 2)
        .map(select => select.value);

    selectors.forEach((selector, index) => {
        // 在手機版時跳過第三個選擇器
        if (isMobile && index > 1) {
            selector.style.display = 'none';
            return;
        }

        // 保存當前選中的值
        const currentValue = selector.value;

        // 清空並重新填充選項
        selector.innerHTML = '';
        
        watchOptions.forEach(option => {
            // 如果是當前選中的值，或者這個值還沒被其他選擇器使用
            if (option.value === currentValue || 
                !currentSelections.includes(option.value) || 
                currentSelections.indexOf(option.value) === index) {
                
                const optionElement = document.createElement('option');
                optionElement.value = option.value;
                optionElement.textContent = option.label;
                selector.appendChild(optionElement);
            }
        });

        // 如果當前值還在可用選項中，保持選中
        if (Array.from(selector.options).some(opt => opt.value === currentValue)) {
            selector.value = currentValue;
        } else {
            // 否則選擇第一個可用選項
            selector.value = selector.options[0].value;
            currentSelections[index] = selector.value;
        }
    });
}


    // 更新表格內容
    function updateTableContent() {
        const selectors = Array.from(document.querySelectorAll('.watch-selector'))
            .filter((_, index) => !isMobile || index < 2);
        const selectedWatches = selectors.map(select => select.value);

        document.querySelectorAll('#comparisonTable td[data-field]').forEach(cell => {
            const field = cell.getAttribute('data-field');
            const columnIndex = Array.from(cell.parentElement.children).indexOf(cell) - 1;
            
            if (columnIndex >= 0 && columnIndex < selectedWatches.length) {
                const watchModel = selectedWatches[columnIndex];
                const value = watchData[watchModel][field];
                cell.innerHTML = value ? value.replace(/\n/g, '<br>') : '—';
            }
        });
    }

    // 更新行動裝置顯示
function updateMobileLayout() {
    const thirdColumn = document.querySelector('.desktop-only');
    const cells = document.querySelectorAll('#comparisonTable tr > *:nth-child(4)');
    
    if (isMobile) {
        if (thirdColumn) thirdColumn.style.setProperty('display', 'none', 'important');
        cells.forEach(cell => {
            cell.style.setProperty('display', 'none', 'important');
        });
    } else {
        if (thirdColumn) thirdColumn.style.removeProperty('display');
        cells.forEach(cell => {
            cell.style.removeProperty('display');
        });
    }
}

    // 處理視窗大小變化
function handleResize() {
    const newIsMobile = window.innerWidth < 768;
    if (newIsMobile !== isMobile) {
        isMobile = newIsMobile;
        
        const selectors = document.querySelectorAll('.watch-selector');
        if (newIsMobile) {
            // 獲取當前選中的值
            const selectedValues = Array.from(selectors).map(s => s.value);
            
            // 確保第二個選擇器選擇了一個不同的值
            if (selectedValues[0] === selectedValues[1]) {
                // 找到第一個不是當前選中值的選項
                const newValue = watchOptions.find(opt => opt.value !== selectedValues[0]).value;
                selectors[1].value = newValue;
            }
        }
        
        generateTable();
        updateSelectOptions();
        updateTableContent();
        updateMobileLayout();
    }
}

    // 初始化
    document.addEventListener('DOMContentLoaded', () => {
        generateTable();
        updateSelectOptions();
        updateTableContent();
        updateMobileLayout();
        
        // 綁定事件
        document.querySelectorAll('.watch-selector').forEach(select => {
            select.addEventListener('change', () => {
                updateSelectOptions();
                updateTableContent();
            });
        });
        
        window.addEventListener('resize', handleResize);
    });
})();
</script>

</body>
</html>
