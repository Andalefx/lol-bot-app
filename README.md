<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[BOT ADI] - Ana Sayfa</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; color: #333; }
        /* Navbar Stilleri */
        .navbar {
            background-color: #333;
            color: white;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 0 15px;
            font-size: 1.1em;
        }
        .navbar a:hover {
            color: #5865F2; /* Discord Mavisi */
        }

        /* Ana İçerik ve Sidebar Düzeni */
        .container {
            display: flex;
            max-width: 1200px;
            margin: 20px auto;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .sidebar {
            width: 250px;
            padding: 20px;
            background-color: #e9e9e9;
            border-right: 1px solid #ccc;
        }
        .sidebar h3 {
            border-bottom: 2px solid #aaa;
            padding-bottom: 10px;
            margin-top: 0;
        }
        .sidebar ul {
            list-style: none;
            padding: 0;
        }
        .sidebar ul li a {
            display: block;
            padding: 10px 0;
            text-decoration: none;
            color: #333;
            border-bottom: 1px dotted #ccc;
        }
        .sidebar ul li a:hover {
            color: #5865F2;
        }
        .content {
            flex-grow: 1;
            padding: 40px;
        }
        .btn-discord {
            display: inline-block;
            background-color: #5865F2; /* Discord Mavisi */
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 20px;
        }
        .btn-discord:hover {
            background-color: #404EED;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <div class="logo">
            <a href="./index.html">🤖 [BOT ADI]</a>
        </div>
        <div class="nav-links">
            <a href="./index.html">Ana Sayfa</a>
            <a href="./terms.html">Hizmet Şartları</a>
            <a href="./privacy.html">Gizlilik Politikası</a>
        </div>
    </div>
    <div class="container">
        <div class="sidebar">
            <h3>Yasal Belgeler</h3>
            <ul>
                <li><a href="./terms.html">Hizmet Şartları</a></li>
                <li><a href="./privacy.html">Gizlilik Politikası</a></li>
            </ul>
            
            <h3>Bot Linkleri</h3>
            <ul>
                <li><a href="[DESTEK SUNUCUSU DAVET LİNKİ]" target="_blank">Destek Sunucusu</a></li>
                <li><a href="mailto:[E-POSTA ADRESİNİZ]">İletişim</a></li>
            </ul>
        </div>
        <div class="content">
            <h1>Discord Sunucunuz İçin League of Legends İstatistik Botu</h1>
            <p><strong>[BOT ADI]</strong>, Discord sunucunuz için tasarlanmış, anlık ve detaylı League of Legends dereceli verilerini Riot Games API'sini kullanarak sunan en gelişmiş bottur.</p>

            <h2>🚀 Hemen Botu Ekleyin!</h2>
            <p>Aşağıdaki butona tıklayarak Bot'u Discord sunucunuza kolayca ekleyebilirsiniz:</p>
            
            <a href="[BOTUNUZUN GERÇEK DAVET LİNKİ]" target="_blank" class="btn-discord">
                Botu Sunucuya Ekle
            </a>
            
            <hr>

            <h2>✅ Özellikler</h2>
            <ul>
                <li>**Anlık Veri:** Oyuncuların mevcut Lig/Küme, LP ve kazanma oranını saniyeler içinde gösterir.</li>
                <li>**Maç Geçmişi:** Son oynanan maçların skorları ve KDA detaylarını analiz eder.</li>
                <li>**Kullanıcı Kaydı:** Kullanıcıların Riot ID'lerini kaydederek hızlı komut çekme imkanı sunar.</li>
            </ul>
            
            <hr>
            
            <p style="font-size: 0.8em; color: #666;">
                **Önemli Not:** Bu uygulama Riot Games tarafından yapılmamıştır ve Riot Games'in görüşlerini veya fikirlerini yansıtmaz. Riot Games veya League of Legends ile resmi olarak bağlantılı değildir.
            </p>
        </div>
        </div>

</body>
</html>
