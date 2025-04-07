<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Persen</title>
    <link rel="stylesheet" href="style.css">
<body>
    <div class="container">
        <h2>Kalkulator Persen</h2>
        <label for="pilihan">Pilih Operasi:</label>
        <select id="pilihan">
            <option value="1">Hitung X% dari Y</option>
            <option value="2">Hitung X sebagai persen dari Y</option>
            <option value="3">Hitung nilai dari persen X terhadap Y</option>
        </select>

        <div class="input-box">
            <input type="number" id="angka1" placeholder="Masukkan angka X">
        </div>
        
        <div class="input-box">
            <input type="number" id="angka2" placeholder="Masukkan angka Y">
        </div>
   
        <button class="hitung-btn" onclick="hitungPersen()">Hitung</button>

        <div class="hasil-container">
            <h3>Hasil:</h3>
            <span id="hasil">-</span>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
