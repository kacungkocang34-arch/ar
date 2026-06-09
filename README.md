<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/png" href="https://bigo4d.sayurkol.net/apple-touch-icon.png">
    <title>Generator Data WD Auto Flop</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f3ec; /* Background hangat khas Flop */
            color: #0f172a;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            background: #ffffff;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 30px rgba(0,0,0,0.03);
            position: relative;
        }
        h2 {
            color: #005a36; /* Hijau tua utama Flop */
            margin-top: 0;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 12px;
            font-size: 24px;
            font-weight: 700;
        }
        
        /* Block info utama */
        .highlight-box {
            background-color: #005a36; 
            color: #ffffff;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 25px;
            font-size: 14px;
            line-height: 1.6;
            box-shadow: 0 4px 15px rgba(0, 90, 54, 0.15);
        }
        .highlight-box strong {
            color: #00ff01; /* Hijau terang tegas untuk highlight teks */
        }
        
        label {
            font-weight: 600;
            display: block;
            margin-bottom: 8px;
            color: #005a36;
        }
        textarea {
            width: 100%;
            height: 180px;
            padding: 14px;
            border: 1px solid #cbd5e1;
            border-radius: 10px;
            font-family: monospace;
            font-size: 13px;
            resize: vertical;
            box-sizing: border-box;
            background-color: #fafafa;
            transition: all 0.2s;
        }
        textarea:focus {
            outline: none;
            border-color: #005a36;
            background-color: #fff;
            box-shadow: 0 0 0 3px rgba(0, 90, 54, 0.1);
        }
        
        /* Tombol aksi gaya kapsul Flop */
        .btn-group {
            margin-top: 20px;
            margin-bottom: 25px;
            display: flex;
            align-items: center;
            gap: 12px;
            flex-wrap: wrap;
        }
        button {
            background-color: #005a36;
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 14px;
            font-weight: 600;
            border-radius: 30px;
            cursor: pointer;
            transition: all 0.2s ease;
            box-shadow: 0 2px 8px rgba(0, 90, 54, 0.1);
        }
        button:hover {
            background-color: #004428;
            transform: translateY(-1px);
        }
        button.btn-success {
            background-color: #005a36;
            border: 1px solid #005a36;
        }
        button.btn-success:hover {
            background-color: #004428;
        }
        button.btn-danger {
            background-color: #ffffff;
            color: #dc2626;
            border: 1px solid #fca5a5;
        }
        button.btn-danger:hover {
            background-color: #fef2f2;
            border-color: #dc2626;
        }
        
        /* Pop-up Toast Kanan Bawah */
        .elegant-toast {
            position: fixed;
            bottom: 25px;
            right: 25px;
            background-color: #005a36;
            color: #ffffff;
            padding: 14px 24px;
            border-radius: 8px;
            font-size: 13px;
            font-weight: 600;
            letter-spacing: 0.3px;
            box-shadow: 0 10px 25px rgba(0, 90, 54, 0.2);
            z-index: 9999;
            opacity: 0;
            transform: translateY(10px);
            transition: opacity 0.3s ease, transform 0.3s ease;
            pointer-events: none;
            border-left: 4px solid #00ff01;
        }
        .elegant-toast.show {
            opacity: 1;
            transform: translateY(0);
        }

        /* Desain Kolom Tabel - SOLID CONTRAST (TANPA JAM) */
        .table-container {
            overflow-x: auto;
            margin-top: 15px;
            border: 1px solid #4b4b4b;
            border-radius: 6px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 13px;
            background-color: #ffffff;
        }
        th {
            font-weight: 800;
            padding: 12px 8px;
            border: 1px solid #6c6c6c; /* Garis hitam tegas presisi Excel */
            color: #000000;
            text-align: center;
            font-size: 12px;
            letter-spacing: 0.5px;
        }
        
        /* Pewarnaan Solid & Jelas */
        th.cyan-solid { background-color: #00E5FF; } 
        th.green-solid { background-color: #00E676; }
        
        td {
            padding: 12px 10px;
            border: 1px solid #616161; /* Batasan kolom tegas */
            white-space: nowrap;
            text-align: center;
            color: #000000;
            font-size: 13px;
        }
        .fw-bold-data {
            font-weight: 700;
        }
    </style>
</head>
<body>

<div id="popupNotification" class="elegant-toast"></div>

<div class="container">
    <h2>BIGO4D - Tool Generator WITHDRAW Flop!</h2>
    
    <div class="highlight-box">
        <strong>✓ BIGO4D:</strong> Diatas Standard Operating Procedure (SOP) ada kemanusiaan
    </div>

    <label for="rawInput">Masukkan Data Admin di Sini:</label>
    <textarea id="rawInput" placeholder="Tempelkan data transaksi di sini..."></textarea>

    <div class="btn-group">
        <button onclick="processData()">🔄 Proses Data</button>
        <button class="btn-success" onclick="copyToClipboard()">✅ Salin Hasil</button>
        <button class="btn-danger" onclick="resetData()">⛔ Bersihkan Data</button>
    </div>

    <label>HASIL UNTUK PASTE DI DOC:</label>
    <div class="table-container">
        <table>
            <thead>
                <tr>
                    <th class="cyan-solid" style="width: 25%;">USER ID</th>
                    <th class="cyan-solid" style="width: 45%;">NAMA REKENING</th>
                    <th class="green-solid" style="width: 15%;">CREDIT</th>
                    <th class="green-solid" style="width: 15%;">DEBIT</th>
                </tr>
            </thead>
            <tbody id="tableBody">
            </tbody>
        </table>
    </div>
</div>

<script>
let records = [];

function showPopup(message, indicatorColor = '#00ff01') {
    const popup = document.getElementById('popupNotification');
    popup.innerText = message;
    popup.style.borderLeftColor = indicatorColor;
    popup.classList.add('show');
    
    setTimeout(() => {
        popup.classList.remove('show');
    }, 2500);
}

function processData() {
    const input = document.getElementById('rawInput').value;
    const tbody = document.getElementById('tableBody');
    tbody.innerHTML = '';
    records = [];
    
    if (!input.trim()) {
        showPopup('Input data kosong.', '#dc2626');
        return;
    }

    const lines = input.split('\n').map(line => line.trim()).filter(line => line.length > 0);
    let tempRecords = [];
    let currentBlock = null;

    for (let i = 0; i < lines.length; i++) {
        let line = lines[i];
        let lowerLine = line.toLowerCase();

        if (/^g[1-5]$/i.test(line)) {
            continue;
        }

        // =========================================================================
        // BARU & PASTI FIX: LOGIKA LOG SYSTEM BARIS TUNGGAL OTOMATIS
        // Mendukung multi-tahun (2026/12026) dan kebal eror pembacaan simbol bank
        // =========================================================================
        if (lowerLine.includes('withdraw') && lowerLine.includes('accept')) {
            // Tangkap User ID (teks setelah Jam s/d sebelum kata Withdraw)
            let userMatch = line.match(/\d{2}:\d{2}:\d{2}\s*([a-zA-Z0-9_.-]+)\s*Withdraw/i);
            // Tangkap Nama Rekening (teks setelah Withdraw s/d koma pertama)
            let namaMatch = line.match(/Withdraw\s*([^,]+)/i);
            // Tangkap Nominal (angka berformat ribuan tepat sebelum kata ACCEPT)
            let nominalMatch = line.match(/([\d,]+)\s*ACCEPT/i);

            if (userMatch && namaMatch && nominalMatch) {
                if (currentBlock) { tempRecords.push(currentBlock); currentBlock = null; }
                tempRecords.push({
                    userId: userMatch[1].trim(),
                    namaRekening: namaMatch[1].trim().toUpperCase(),
                    nominal: nominalMatch[1].trim()
                });
                continue; // Lanjut baris berikutnya, aman 100%
            }
        }

        // =========================================================================
        // DETEKSI FORMAT HASIL JADI YANG IKUT TER-PASTE
        // =========================================================================
        let resultFormatMatch = line.match(/^([a-zA-Z0-9_.-]+)\s+(.+?)\s+(\d{1,3}(,\d{3})+)$/);
        if (resultFormatMatch && !lowerLine.includes('withdraw') && !line.includes(',')) {
            if (currentBlock) { tempRecords.push(currentBlock); currentBlock = null; }
            tempRecords.push({
                userId: resultFormatMatch[1].trim(),
                namaRekening: resultFormatMatch[2].trim().toUpperCase(),
                nominal: resultFormatMatch[3].trim()
            });
            continue;
        }

        // =========================================================================
        // LOGIKA MULTILINE / FORMAT LAMA BAWAAN AWAL (Tetap Dijaga Utuh)
        // =========================================================================
        if (lowerLine.includes('withdraw')) {
            let nominal = "-";
            let matchUang = line.match(/\d{1,3}(,\d{3})+/);
            if (matchUang) {
                nominal = matchUang[0];
            } else {
                let timeMatch = line.match(/\d{1,2}:\d{2}:\d{2}/);
                if (timeMatch) {
                    let setelahJam = line.split(timeMatch[0])[1];
                    if (setelahJam) {
                        let angkaAwal = setelahJam.match(/\d+/);
                        if (angkaAwal) nominal = angkaAwal[0];
                    }
                }
            }
            if (currentBlock) currentBlock.nominal = nominal;
        } 
        else if (line.includes(',') || lowerLine.startsWith('bca') || lowerLine.startsWith('bri') || lowerLine.startsWith('seabank') || lowerLine.startsWith('dana') || lowerLine.startsWith('ovo')) {
            let parts = line.split(',');
            let namaMentah = parts.length >= 3 ? parts[2].trim() : (parts.length === 2 ? parts[1].trim() : line);

            namaMentah = namaMentah.replace(/^[\d\s\-\.]+/g, '').trim();
            let namaClean = namaMentah;
            let extractedUserId = "";

            let nempelMatch = namaMentah.match(/(.+?)\s*(\d+)([a-zA-Z].*)$/);
            if (nempelMatch) {
                namaClean = nempelMatch[1].trim();
                extractedUserId = nempelMatch[3].trim();
            }

            if (currentBlock) {
                currentBlock.namaRekening = namaClean.toUpperCase();
                if (extractedUserId) {
                    tempRecords.push(currentBlock);
                    currentBlock = { userId: extractedUserId, namaRekening: '', nominal: '' };
                }
            }
        } 
        else {
            if (currentBlock) tempRecords.push(currentBlock);
            let cleanUser = line.replace(/^[0-9]+/, '').trim();
            currentBlock = { userId: cleanUser, namaRekening: '', nominal: '' };
        }
    }

    if (currentBlock) tempRecords.push(currentBlock);

    // Cetak ke HTML tabel doc
    let validCount = 0;
    tempRecords.forEach(rec => {
        if (rec.userId) {
            let row = document.createElement('tr');
            row.innerHTML = `
                <td class="fw-bold-data">${rec.userId}</td>
                <td class="fw-bold-data">${rec.namaRekening || "-"}</td>
                <td></td>
                <td class="fw-bold-data" style="color: #007b33;">${rec.nominal || "-"}</td>
            `;
            tbody.appendChild(row);
            validCount++;
        }
    });

    if (validCount === 0) {
        showPopup('Format data tidak dikenali.', '#dc2626');
    } else {
        showPopup(`Berhasil memproses ${validCount} data.`, '#00ff01');
    }
}

function copyToClipboard() {
    const tbody = document.getElementById('tableBody');
    if (tbody.rows.length === 0) {
        showPopup('Tidak ada data untuk disalin.', '#dc2626');
        return;
    }
    
    let textToCopy = "";
    for (let row of tbody.rows) {
        let uId = row.cells[0].innerText;
        let nRek = row.cells[1].innerText;
        let nom = row.cells[3].innerText; 
        textToCopy += `${uId}\t${nRek}\t\t${nom}\n`;
    }
    
    navigator.clipboard.writeText(textToCopy).then(() => {
        showPopup('Data berhasil disalin!', '#00ff01');
    }).catch(() => {
        showPopup('Gagal menyalin otomatis.', '#dc2626');
    });
}

function resetData() {
    document.getElementById('rawInput').value = '';
    document.getElementById('tableBody').innerHTML = '';
    records = [];
    showPopup('Data berhasil dibersihkan.', '#ffffff');
}
</script>

</body>
</html>
