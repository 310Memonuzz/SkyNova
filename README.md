
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SkyNova SatÄ±ÅŸ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #0b0c10;
            color: #fff;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 500px;
            margin: auto;
            background: #1f2833;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 20px #66fcf1;
        }
        h1 {
            text-align: center;
            color: #66fcf1;
        }
        label {
            display: block;
            margin: 15px 0 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        .submit-btn {
            background-color: #45a29e;
            color: white;
            cursor: pointer;
            font-weight: bold;
        }
        .submit-btn:hover {
            background-color: #66fcf1;
            color: #0b0c10;
        }
        .info {
            background: #0b0c10;
            padding: 10px;
            border-left: 5px solid #66fcf1;
            margin-bottom: 20px;
        }
        .support {
            text-align: center;
            margin-top: 20px;
        }
        .support a {
            color: #66fcf1;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>SkyNova SatÄ±ÅŸ Sistemi</h1>
        <div class="info">
            <p><strong>Ã–deme Papara NumarasÄ±:</strong> 1535726249</p>
            <p>âœ… AÃ§Ä±klamaya mutlaka Minecraft adÄ±nÄ±zÄ± yazÄ±nÄ±z.</p>
        </div>
        <form>
            <label for="mcname">Minecraft AdÄ±nÄ±z</label>
            <input type="text" id="mcname" name="mcname" required>

            <label for="sender">Papara AdÄ±nÄ±z (GÃ¶nderici)</label>
            <input type="text" id="sender" name="sender" required>

            <label for="package">Paket SeÃ§in</label>
            <select id="package" name="package" required>
                <option value="">-- SeÃ§in --</option>
                <option value="VIP">VIP - 100 TL</option>
                <option value="VIP+">VIP+ - 200 TL</option>
                <option value="MVIP">MVIP - 300 TL</option>
                <option value="MVIP+">MVIP+ - 400 TL</option>
            </select>

            <label for="notes">Ek AÃ§Ä±klama (isteÄŸe baÄŸlÄ±)</label>
            <textarea id="notes" name="notes" rows="4"></textarea>

            <button type="submit" class="submit-btn">GÃ¶nder</button>
        </form>

        <div class="support">
            <p>Ã–deme yaptÄ±ktan sonra <a href="#">CanlÄ± Destek</a>'e baÅŸvurun.</p>
        </div>
    </div>
</body>
</html>
