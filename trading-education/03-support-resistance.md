# 📈 03 - Support & Resistance

## Apa itu Support & Resistance?

**Support** dan **Resistance** adalah level harga di mana tekanan beli atau jual cenderung muncul, menyebabkan harga berhenti atau berbalik arah.

### Support (Dukungan) 📊
- **Level harga di bawah** harga saat ini
- **Buyers** cenderung masuk di level ini
- Harga cenderung **bounce (memantul) naik**
- Seperti "lantai" yang menahan harga turun

```
Price
  ↑
  │     ╱╲
  │    ╱  ╲    ╱╲
  │   ╱    ╲  ╱  ╲
  │  ╱      ╲╱    ╲
  ├─────────────────── ← Support (harga bounce di sini)
  │
  └──────────────────→ Time
```

### Resistance (Perlawanan) 📊
- **Level harga di atas** harga saat ini
- **Sellers** cenderung masuk di level ini
- Harga cenderung **reject (ditolak) turun**
- Seperti "atap" yang menahan harga naik

```
Price
  ↑
  ├─────────────────── ← Resistance (harga ditolak di sini)
  │      ╱╲      ╱╲
  │     ╱  ╲    ╱  ╲
  │    ╱    ╲  ╱    ╲
  │   ╱      ╲╱      ╲
  │
  └──────────────────→ Time
```

---

## Kenapa Support & Resistance Penting?

### 1. Entry Point
- **Buy di support** (harga murah)
- **Sell di resistance** (harga mahal)

### 2. Exit Point
- **Take profit** di resistance (jika buy)
- **Take profit** di support (jika sell)

### 3. Stop Loss
- **SL di bawah support** (jika buy)
- **SL di atas resistance** (jika sell)

### 4. Risk/Reward Calculation
- Jarak entry ke SL = Risk
- Jarak entry ke target = Reward

---

## Cara Menentukan Support & Resistance

### 1. Historical Price (Harga Historis)
**Lihat di mana harga pernah bounce atau reject sebelumnya**

```
Price
  ↑
  │         ╱╲
  │        ╱  ╲
  ├───────────────── ← Resistance (reject 3x)
  │    ╱╲  ╱    ╲
  │   ╱  ╲╱      ╲
  ├─────────────────── ← Support (bounce 3x)
  │
  └──────────────────→ Time
```

**Semakin sering tested, semakin kuat level tersebut!**

### 2. Round Numbers (Angka Bulat)
**Harga psikologis yang sering jadi S/R**

**Contoh:**
- BBRI: 4,000 / 4,500 / 5,000
- GOTO: 50 / 60 / 70 / 80
- TLKM: 3,000 / 3,500 / 4,000

**Kenapa?**
- Trader suka set order di angka bulat
- Psikologis: "Beli di 4,000" lebih mudah diingat

### 3. Previous High/Low
**High/Low sebelumnya sering jadi S/R**

```
Price
  ↑
  │           ╱╲
  │          ╱  ╲ ← Previous High = Resistance
  │         ╱    ╲
  │    ╱╲  ╱      ╲
  │   ╱  ╲╱        ╲
  │  ╱              ╲
  │ ╱                ╲ ← Previous Low = Support
  └──────────────────→ Time
```

### 4. Moving Average (MA)
**MA sering jadi dynamic S/R**

**Contoh:**
- **MA 20** (short-term S/R)
- **MA 50** (medium-term S/R)
- **MA 200** (long-term S/R)

```
Price
  ↑
  │    ╱╲   ╱╲
  │   ╱  ╲ ╱  ╲
  ├──────────────── ← MA 50 (dynamic resistance)
  │  ╱    ╲╱    ╲
  │ ╱            ╲
  └──────────────────→ Time
```

### 5. Fibonacci Retracement
**Level fibonacci sering jadi S/R**

**Level penting:**
- 23.6%
- 38.2%
- 50%
- 61.8% (golden ratio)
- 78.6%

---

## Support & Resistance Zone

**Konsep**: S/R bukan garis tepat, tapi **ZONE (area)**

### Garis (Salah) ❌
```
Price
  ↑
  ├─────────────── ← Resistance (garis tipis)
  │
```
**Masalah**: Harga jarang tepat di garis

### Zone (Benar) ✅
```
Price
  ↑
  ├═════════════════ ← Resistance Zone (area)
  ├═════════════════
  │
```
**Lebih realistis**: Harga di sekitar area ini

**Contoh:**
```
BBRI Resistance Zone: 4,580 - 4,620
Bukan: 4,600 (tepat)

Artinya: Harga 4,580 - 4,620 = resistance area
```

---

## Breakout & Breakdown

### Breakout (Tembus Resistance) 🚀
**Harga tembus resistance → jadi support baru**

```
Price
  ↑
  │              ╱
  │             ╱ ← Breakout!
  ├────────────╱──── ← Ex-resistance jadi support
  │        ╱╲ ╱
  │       ╱  ╲╱
  │      ╱
  └──────────────────→ Time
```

**Signal**: Bullish (harga bisa lanjut naik)

### Breakdown (Tembus Support) 📉
**Harga tembus support → jadi resistance baru**

```
Price
  ↑
  │      ╲
  │       ╲  ╱╲
  │        ╲╱  ╲
  ├─────────╲────── ← Ex-support jadi resistance
  │          ╲ ← Breakdown!
  │           ╲
  └──────────────────→ Time
```

**Signal**: Bearish (harga bisa lanjut turun)

### Konfirmasi Breakout/Breakdown

**Valid breakout/breakdown harus punya:**

1. **Volume tinggi** ✅
```
Price: Breakout
Volume: █████████ ← High volume
```

2. **Candle close di luar S/R** ✅
```
Resistance: ─────
Price:         ╱ ← Close di atas resistance
              ╱
```

3. **Retest** (optional tapi bagus)
```
Price
  ↑
  │         ╱
  │        ╱ ← Breakout
  ├───────╱─╲─── ← Retest (test ex-resistance)
  │      ╱   ╲╱
  │     ╱
```

**Jika tidak ada konfirmasi → bisa jadi FALSE BREAKOUT!**

---

## False Breakout (Fake Breakout)

**Harga tembus S/R tapi langsung balik lagi**

### False Breakout di Resistance
```
Price
  ↑
  │        ╱╲ ← Fake breakout (langsung turun)
  ├───────╱──╲──── ← Resistance
  │      ╱    ╲
  │     ╱      ╲
```

**Ciri-ciri:**
- ❌ Volume rendah
- ❌ Candle close masih di dalam S/R
- ❌ Langsung balik

**Cara avoid:**
- ✅ Tunggu volume confirmation
- ✅ Tunggu candle close
- ✅ Tunggu retest

---

## Trading Strategy dengan S/R

### Strategy 1: Buy at Support (Range Trading)
```
Price
  ↑
  ├─────────────── ← Resistance (SELL/TP)
  │    ╱╲    ╱╲
  │   ╱  ╲  ╱  ╲
  │  ╱    ╲╱    ╲
  ├─────────────── ← Support (BUY)
  │
```

**Setup:**
- Market: Sideways (range-bound)
- Entry: Buy di support
- Target: Resistance
- SL: Di bawah support

**Example:**
```
BBRI sideways 4,500 - 4,600
Buy: 4,510 (support zone)
TP: 4,590 (resistance zone)
SL: 4,480 (below support)
R/R: 80 / 30 = 2.67:1 ✅
```

### Strategy 2: Breakout Trading
```
Price
  ↑
  │              ╱
  │             ╱ ← BUY (breakout)
  ├────────────╱──── ← Resistance
  │        ╱╲ ╱
  │       ╱  ╲╱
```

**Setup:**
- Market: Consolidation → breakout
- Entry: Buy saat breakout resistance
- Target: Next resistance
- SL: Di ex-resistance (jadi support)

**Example:**
```
GOTO consolidation 68-72
Breakout: 73 (BUY)
TP: 78 (next resistance)
SL: 71 (ex-resistance)
R/R: 5 / 2 = 2.5:1 ✅
```

### Strategy 3: Pullback Trading
```
Price
  ↑
  │         ╱
  │        ╱ ← Breakout
  ├───────╱─╲─── ← Retest (BUY)
  │      ╱   ╲╱
  │     ╱
```

**Setup:**
- Market: Uptrend
- Entry: Buy saat pullback ke support (ex-resistance)
- Target: Next resistance
- SL: Di bawah support

**Example:**
```
BRMS breakout 1,300
Pullback ke 1,290 (retest)
BUY: 1,295
TP: 1,350
SL: 1,280
R/R: 55 / 15 = 3.67:1 ✅
```

---

## Multiple Support & Resistance

**Semakin banyak S/R di satu area, semakin kuat!**

### Confluence (Pertemuan)
```
Price
  ↑
  ├═════════════════ ← Resistance Zone
  ├─────────────────  ← MA 50
  ├─────────────────  ← Fibonacci 61.8%
  ├─────────────────  ← Round number (5,000)
  │
```

**3 S/R di area yang sama = VERY STRONG RESISTANCE!**

**Contoh:**
```
BBRI 4,600:
- Previous high (4,600)
- MA 50 (4,590)
- Fibonacci 61.8% (4,610)
- Round number (4,600)

= VERY STRONG RESISTANCE!
```

---

## Tips Menggambar S/R

### ✅ Do's:
1. **Gunakan line tool** di TradingView
2. **Gambar horizontal** di level yang sering tested
3. **Gunakan zone** (bukan garis tipis)
4. **Lihat multiple timeframes** (Daily, 4H, 1H)
5. **Update regularly** (S/R bisa berubah)

### ❌ Don'ts:
1. **Jangan terlalu banyak garis** (max 3-5 per chart)
2. **Jangan gambar di setiap high/low** (pilih yang signifikan)
3. **Jangan ignore volume** (S/R dengan volume tinggi lebih valid)
4. **Jangan trade tanpa konfirmasi** (tunggu signal)

---

## Practice Exercise

### Daily Practice (15 menit):
1. Buka TradingView
2. Pilih 1 saham (BBRI, GOTO, atau TLKM)
3. Timeframe: Daily chart
4. Gambar 2-3 support levels
5. Gambar 2-3 resistance levels
6. Screenshot dan save

### Weekly Review:
- Apakah harga respect S/R yang digambar?
- Apakah ada breakout/breakdown?
- Apakah ada false breakout?
- Update S/R jika perlu

---

## Checklist S/R Trading

Before entry:

- [ ] Support/resistance identified
- [ ] Level tested multiple times (min 2x)
- [ ] Volume confirmation
- [ ] Candlestick pattern (hammer, engulfing, dll)
- [ ] Risk/reward > 1:2
- [ ] Stop loss clear (below S / above R)
- [ ] Target clear (next R / next S)

**Semua ✅ → Consider entry**
**Ada yang ❌ → Skip atau wait**

---

## Common Mistakes

### ❌ Mistake 1: Too Many Lines
- **Wrong**: Gambar S/R di setiap high/low
- **Right**: Pilih 3-5 level paling signifikan

### ❌ Mistake 2: Exact Price
- **Wrong**: Resistance tepat di 4,600
- **Right**: Resistance zone 4,580-4,620

### ❌ Mistake 3: Ignore Timeframe
- **Wrong**: Lihat S/R di 5M untuk swing trading
- **Right**: Lihat S/R di Daily/4H untuk swing

### ❌ Mistake 4: No Confirmation
- **Wrong**: Harga di support → langsung buy
- **Right**: Support + volume + candle pattern → buy

---

## Next Steps

1. **Lanjut ke**: [Indikator Teknikal](./04-indikator-teknikal.md)
2. **Practice**: Gambar S/R di 5 saham berbeda
3. **Backtest**: Lihat historical chart, apakah S/R valid?
4. **Journal**: Screenshot dan catat

---

**Remember: "Support & Resistance are the foundation of technical analysis. Master them!"** 📊📈
