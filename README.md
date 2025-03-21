<h2>📫 MCG - Massive CRUD Generator</h2>


 
 💞️💞️💞️<span class="font-weight-bold">Documentation MCG link</span>💞️💞️💞️
<br>
<br><span class="font-weight-bold">English: </span>
<i>	
<a href="https://yudhi-irawan.github.io/mcg-documentation/index.html">https://yudhi-irawan.github.io/mcg-documentation/index.html</a>
<br>🌱🌱🌱<br>
<span class="font-weight-bold">Indonesia: </span>
<a href="https://yudhi-irawan.github.io/mcg-documentation/index-id.html">https://yudhi-irawan.github.io/mcg-documentation/index-id.html</a>
</i>
<br><br>

💞️💞️💞️ <span class="font-weight-bold">Download</span> MCG Application link at:
<i>	
<a href="https://yudhi-irawan.github.io/mcg-documentation/download.html">https://yudhi-irawan.github.io/mcg-documentation/download.html</a>
</i>💞️💞️💞️
<br><br>
 
 
 Thanks you for using this tool. 


    <h1>CoolGuard</h1>
    <div id="data-container"></div>

    <script>
        const data = {
            "master-EC:FA:BC:5A:47:D7": {
                "00-tanggal": "Thu Mar 20 09:17:36 2025\n",
                "01-OVERHEAD": 1,
                "02-ACC": 1,
                "03-alatberat": "Excavator",
                "03-type": "Excavator",
                "04-nama": "BOLDUZER",
                "05-operator": "Jhoni",
                "08-reading": 1,
                "32-mcu": "ESP8266",
                "33-Flash": 4,
                "33-idmcu": 5916631,
                "37-lokasi": "gps",
                "40-suhumesin": 77,
                "img": "https://raw.githubusercontent.com/ninofelino12/react-router-project/refs/heads/master/img/5916631.jpg",
                "link": "data-EC:FA:BC:5A:47:D7",
                "photo": "https://raw.githubusercontent.com/ninofelino12/react-router-project/refs/heads/master/img/P5916631.jpg",
                "timestamp": 1742462256,
                "z50-PIND5": 1,
                "z50-PIND6": 1,
                "z50-PIND7": 1,
                "z50-PIND8_BUZZER": 1,
                "z51 Count": 39
            }
        };

        const dataContainer = document.getElementById('data-container');
        const innerObject = Object.values(data)[0];

        let html = '<table>';
        html += '<thead><tr><th>Key</th><th>Value</th></tr></thead>';
        html += '<tbody>';

        html += <tr><td>00-tanggal</td><td>${innerObject['00-tanggal']}</td></tr>;
        html += <tr><td>01-OVERHEAD</td><td>${innerObject['01-OVERHEAD']}</td></tr>;
        html += <tr><td>02-ACC</td><td>${innerObject['02-ACC']}</td></tr>;
        html += <tr><td>03-alatberat</td><td>${innerObject['03-alatberat']}</td></tr>;
        html += <tr><td>03-type</td><td>${innerObject['03-type']}</td></tr>;
        html += <tr><td>04-nama</td><td>${innerObject['04-nama']}</td></tr>;
        html += <tr><td>05-operator</td><td>${innerObject['05-operator']}</td></tr>;
        html += <tr><td>08-reading</td><td>${innerObject['08-reading']}</td></tr>;
        html += <tr><td>32-mcu</td><td>${innerObject['32-mcu']}</td></tr>;
        html += <tr><td>33-Flash</td><td>${innerObject['33-Flash']}</td></tr>;
        html += <tr><td>33-idmcu</td><td>${innerObject['33-idmcu']}</td></tr>;
        html += <tr><td>37-lokasi</td><td>${innerObject['37-lokasi']}</td></tr>;
        html += <tr><td>40-suhumesin</td><td>${innerObject['40-suhumesin']}</td></tr>;
        html += <tr><td>img</td><td>${innerObject['img']}</td></tr>;
        html += <tr><td>link</td><td>${innerObject['link']}</td></tr>;
        html += <tr><td>photo</td><td>${innerObject['photo']}</td></tr>;
        html += <tr><td>timestamp</td><td>${innerObject['timestamp']}</td></tr>;
        html += <tr><td>z50-PIND5</td><td>${innerObject['z50-PIND5']}</td></tr>;
        html += <tr><td>z50-PIND6</td><td>${innerObject['z50-PIND6']}</td></tr>;
        html += <tr><td>z50-PIND7</td><td>${innerObject['z50-PIND7']}</td></tr>;
        html += <tr><td>z50-PIND8_BUZZER</td><td>${innerObject['z50-PIND8_BUZZER']}</td></tr>;
        html += <tr><td>z51 Count</td><td>${innerObject['z51 Count']}</td></tr>;

        html += '</tbody></table>';
        dataContainer.innerHTML = html;
    </script> 

 👋 👀 🌱 💞️ 📫 
