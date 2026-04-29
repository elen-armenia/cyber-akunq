<!DOCTYPE html>
<html lang="hy">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cyber Dictionary | Elite Edition</title>
    <style>
        :root {
            --gold: #FFD700;
            --blue: #007BFF;
            --orange: #FF8C00;
            --bg: #121212;
            --card-bg: #1e1e1e;
            --text: #e0e0e0;
        }
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0; padding: 20px;
        }
        .container { max-width: 800px; margin: auto; }
        header { text-align: center; margin-bottom: 30px; }
        h1 { color: var(--gold); text-transform: uppercase; letter-spacing: 2px; }
        #search {
            width: 100%; padding: 15px; border: 2px solid var(--gold);
            background: #000; color: #fff; border-radius: 8px;
            font-size: 16px; box-sizing: border-box; margin-bottom: 30px;
        }
        .section-title {
            color: var(--orange); border-bottom: 2px solid var(--gold);
            padding-bottom: 10px; margin-top: 40px;
        }
        .card {
            background: var(--card-bg); padding: 15px; border-radius: 8px;
            margin-bottom: 10px; border-left: 4px solid var(--blue);
            transition: 0.3s;
        }
        .card:hover { border-left-color: var(--gold); }
        .card b { color: var(--gold); display: block; font-size: 1.1em; }
        .card span { color: #aaa; font-size: 0.95em; }
        .hidden { display: none; }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>Cyber Dictionary</h1>
    </header>
    
    <input type="text" id="search" placeholder="Որոնել (Search)..." onkeyup="search()">

    <div id="dictionary">
        <h2 class="section-title">Օգտահաշիվներ և հասանելիություն</h2>
        <div class="card"><b>Account</b> <span>հաշիվ</span></div>
        <div class="card"><b>Username</b> <span>օգտանուն</span></div>
        <div class="card"><b>Password</b> <span>գաղտնաբառ</span></div>
        <div class="card"><b>Password Manager</b> <span>գաղտնաբառերի կառավարիչ</span></div>
        <div class="card"><b>Login Credentials</b> <span>մուտքային տվյալներ</span></div>
        <div class="card"><b>Authentication</b> <span>նույնականացում</span></div>
        <div class="card"><b>Authorization</b> <span>արտոնությունների տրամադրում</span></div>
        <div class="card"><b>Multi-Factor Authentication (MFA)</b> <span>բազմագործոն նույնականացում</span></div>
        <div class="card"><b>2-Factor Authentication (2FA)</b> <span>երկգործոն նույնականացում</span></div>

        <h2 class="section-title">Կիբեռանվտանգության հիմունքներ</h2>
        <div class="card"><b>Cybersecurity</b> <span>կիբեռանվտանգություն</span></div>
        <div class="card"><b>Security</b> <span>անվտանգություն</span></div>
        <div class="card"><b>Cyber Hygiene</b> <span>կիբեռ հիգիենա</span></div>
        <div class="card"><b>Privacy</b> <span>գաղտնիություն</span></div>
        <div class="card"><b>Artificial Intelligence (AI)</b> <span>Արհեստական բանականություն</span></div>
        <div class="card"><b>Protocol</b> <span>հաղորդակարգ</span></div>

        <h2 class="section-title">Սպառնալիքներ և հարձակումներ</h2>
        <div class="card"><b>Phishing</b> <span>ֆիշինգ</span></div>
        <div class="card"><b>Scam</b> <span>խաբեություն</span></div>
        <div class="card"><b>Spam</b> <span>սպամ</span></div>
        <div class="card"><b>Malware</b> <span>վնասակար ծրագիր</span></div>
        <div class="card"><b>Ransomware</b> <span>դրամաշորթ վնասակար ծրագիր</span></div>
        <div class="card"><b>Spyware</b> <span>լրտես ծրագիր</span></div>
        <div class="card"><b>Worm</b> <span>ինքնավերարտադրվող վնասակար ծրագիր</span></div>
        <div class="card"><b>Stealer</b> <span>հափշտակիչ ծրագիր</span></div>
        <div class="card"><b>Malicious Link</b> <span>վնասակար հղում</span></div>
        <div class="card"><b>Social Engineering</b> <span>սոցիալական ինժեներիա</span></div>
        <div class="card"><b>Cyber Attack</b> <span>կիբեռ հարձակում</span></div>
        <div class="card"><b>Threat</b> <span>սպառնալիք</span></div>
        <div class="card"><b>Vulnerability</b> <span>խոցելիություն</span></div>
        <div class="card"><b>Data Breach</b> <span>տվյալների արտահոսք</span></div>

        <h2 class="section-title">Անվտանգության գործիքներ</h2>
        <div class="card"><b>Firewall</b> <span>հրեպատ</span></div>
        <div class="card"><b>Antivirus</b> <span>հակավիրուսային ծրագիր</span></div>
        <div class="card"><b>Encryption</b> <span>գաղտնագրում</span></div>
        <div class="card"><b>Decryption</b> <span>վերծանում</span></div>
        <div class="card"><b>Virtual Private Network (VPN)</b> <span>վիրտուալ անձնական ցանց</span></div>
        <div class="card"><b>Secure Website (HTTPS)</b> <span>անվտանգ կայք</span></div>

        <h2 class="section-title">Համակարգեր և ծրագրային ապահովում</h2>
        <div class="card"><b>Operating System</b> <span>օպերացիոն համակարգ</span></div>
        <div class="card"><b>Software</b> <span>ծրագրային ապահովում</span></div>
        <div class="card"><b>Update</b> <span>թարմացում</span></div>
        <div class="card"><b>Patch</b> <span>շտկում</span></div>
        <div class="card"><b>Browser</b> <span>դիտարկիչ</span></div>

        <h2 class="section-title">Ցանց և կապ</h2>
        <div class="card"><b>Public Wi-Fi</b> <span>հանրային Wi-Fi</span></div>

        <h2 class="section-title">Միջադեպեր և հաղորդումներ</h2>
        <div class="card"><b>Incident</b> <span>միջադեպ</span></div>
        <div class="card"><b>Incident Report</b> <span>միջադեպի հաղորդում</span></div>
    </div>
</div>

<script>
    function search() {
        let input = document.getElementById('search').value.toLowerCase();
        let cards = document.getElementsByClassName('card');
        for (let c of cards) {
            c.classList.toggle('hidden', !c.innerText.toLowerCase().includes(input));
        }
    }
</script>

</body>
</html>
