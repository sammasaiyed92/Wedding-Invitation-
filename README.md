# Wedding-Invitation-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding & Bismillah Invitation - Sufiyan & Misbah</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=Amiri:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #0d1117;
            font-family: 'Playfair Display', serif;
            color: #e6edf3;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background: #161b22;
            border: 1px solid #30363d;
            box-shadow: 0 4px 20px rgba(0,0,0,0.5);
        }
        .section {
            padding: 40px 20px;
            border-bottom: 1px solid #30363d;
        }
        .gold-accent-section {
            background-color: #1f242c;
        }
        .arabic-text {
            font-family: 'Amiri', serif;
            font-size: 26px;
            direction: rtl;
            margin-bottom: 10px;
            color: #f0b741;
        }
        .translation {
            font-size: 15px;
            font-style: italic;
            color: #8b949e;
            margin-bottom: 20px;
        }
        h2, h3 {
            font-weight: 600;
            letter-spacing: 1px;
            color: #f0b741;
        }
        .names {
            font-size: 30px;
            margin: 20px 0;
            color: #f0b741;
            line-height: 1.4;
        }
        .countdown-grid {
            display: flex;
            justify-content: center;
            gap: 12px;
            margin-top: 20px;
        }
        .countdown-box {
            border: 1px solid #f0b741;
            padding: 12px 8px;
            min-width: 55px;
            border-radius: 6px;
            background: rgba(240, 183, 65, 0.05);
        }
        .countdown-box span {
            display: block;
            font-size: 22px;
            font-weight: bold;
            color: #f0b741;
        }
        .countdown-box label {
            font-size: 10px;
            letter-spacing: 1px;
            text-transform: uppercase;
            color: #8b949e;
        }
        .events-box {
            font-size: 15px;
            line-height: 1.8;
            margin: 20px 0;
            text-align: left;
            background: #0d1117;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #30363d;
        }
        .events-box h4 {
            color: #f0b741;
            margin: 0 0 10px 0;
            font-size: 18px;
            border-bottom: 1px dashed #f0b741;
            padding-bottom: 8px;
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Header: Bismillah -->
    <div class="section">
        <div class="arabic-text">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</div>
        <p style="font-size: 12px; letter-spacing: 2px; color: #8b949e;">IN THE NAME OF ALLAH, THE MOST GRACIOUS, THE MOST MERCIFUL</p>
    </div>

    <!-- Couple Names & Opening View -->
    <div class="section gold-accent-section">
        <p style="letter-spacing: 3px; font-size: 12px; color: #8b949e;">THE CELEBRATION OF LOVE</p>
        <div class="names">
            Saiyed Mohammad Sufiyan<br>
            <span style="font-size: 22px; color: #e6edf3; font-style: italic;">&</span><br>
            Pirzada Misbah
        </div>
        <div class="arabic-text" style="font-size: 20px; margin-top: 20px;">بَارَكَ اللَّهُ لَکُمَا وَبَارَكَ عَلَيْکُمْ وَجَمَعَ بَيْنَکُمَا فِي خَيْرٍ</div>
        <p class="translation">“May Allah bless you both, shower His blessings upon you, and unite you in goodness.”</p>
    </div>

    <!-- Bismillah Ceremony Details & Countdown -->
    <div class="section">
        <h3>Bismillah Ceremony</h3>
        <p style="color: #8b949e; font-size: 14px;">Of <strong>Kadri Ali Abbas.T.</strong></p>
        <div class="countdown-grid" id="countdown-bismillah">
            <div class="countdown-box"><span id="b-days">00</span><label>Days</label></div>
            <div class="countdown-box"><span id="b-hours">00</span><label>Hours</label></div>
            <div class="countdown-box"><span id="b-minutes">00</span><label>Mins</label></div>
            <div class="countdown-box"><span id="b-seconds">00</span><label>Secs</label></div>
        </div>
    </div>

    <!-- Nikah Ceremony & Countdown -->
    <div class="section gold-accent-section">
        <h3>Nikah Ceremony</h3>
        <p style="color: #8b949e; font-size: 14px;">Wedding Countdown</p>
        <div class="countdown-grid" id="countdown-nikah">
            <div class="countdown-box"><span id="n-days">00</span><label>Days</label></div>
            <div class="countdown-box"><span id="n-hours">00</span><label>Hours</label></div>
            <div class="countdown-box"><span id="n-minutes">00</span><label>Mins</label></div>
            <div class="countdown-box"><span id="n-seconds">00</span><label>Secs</label></div>
        </div>
    </div>

    <!-- Programme Details -->
    <div class="section">
        <h2 style="margin-bottom: 20px;">Programme Details</h2>
        
        <div class="events-box">
            <h4>📖 Bismillah Ceremony</h4>
            <p><strong>Date:</strong> 03 December 2026<br>
            <strong>Time:</strong> 06:00 PM<br>
            <strong>Venue:</strong> Saiyedwada, Raikhad, Ahmedabad</p>
        </div>

        <div class="events-box">
            <h4>💍 Nikah Ceremony</h4>
            <p><strong>Date:</strong> 05 December 2026<br>
            <strong>Time:</strong> 11:00 AM<br>
            <strong>Venue:</strong> Shah-e-Aalam Dargah, Shah-e-Aalam Darwaja, P & T Colony, Shah-e-Aalam Roja, Ahmedabad</p>
        </div>

        <div class="events-box">
            <h4>✨ Barat</h4>
            <p><strong>Date:</strong> 05 December 2026<br>
            <strong>Time:</strong> 07:00 PM<br>
            <strong>Venue:</strong> Kohinoor Party Plot, Ahmedabad</p>
        </div>

        <div class="events-box">
            <h4>🍽️ Walima</h4>
            <p><strong>Date:</strong> 06 December 2026<br>
            <strong>Time:</strong> 08:00 PM<br>
            <strong>Venue:</strong> Ahad Sport Club, Ahmedabad</p>
        </div>
    </div>

    <!-- Footer Dua -->
    <div class="section gold-accent-section">
        <div class="arabic-text">اللَّهُمَّ بَارِكْ لَهُمَا وَاجْمَعْ بَيْنَهُمَا بِخَيْرٍ</div>
        <p class="translation">"O Allah, bless them both and unite them in goodness."</p>
    </div>
</div>

<script>
    // Bismillah Countdown (3 Dec 2026, 06:00 PM)
    const bismillahDate = new Date("Dec 3, 2026 18:00:00").getTime();
    // Nikah Countdown (5 Dec 2026, 11:00 AM)
    const nikahDate = new Date("Dec 5, 2026 11:00:00").getTime();

    setInterval(function() {
        const now = new Date().getTime();

        // Bismillah Timer
        const distB = bismillahDate - now;
        if (distB > 0) {
            document.getElementById("b-days").innerHTML = Math.floor(distB / (1000 * 60 * 60 * 24));
            document.getElementById("b-hours").innerHTML = Math.floor((distB % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            document.getElementById("b-minutes").innerHTML = Math.floor((distB % (1000 * 60 * 60)) / (1000 * 60));
            document.getElementById("b-seconds").innerHTML = Math.floor((distB % (1000 * 60)) / 1000);
        }

        // Nikah Timer
        const distN = nikahDate - now;
        if (distN > 0) {
            document.getElementById("n-days").innerHTML = Math.floor(distN / (1000 * 60 * 60 * 24));
            document.getElementById("n-hours").innerHTML = Math.floor((distN % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            document.getElementById("n-minutes").innerHTML = Math.floor((distN % (1000 * 60 * 60)) / (1000 * 60));
            document.getElementById("n-seconds").innerHTML = Math.floor((distN % (1000 * 60)) / 1000);
        }
    }, 1000);
</script>

</body>
</html>
