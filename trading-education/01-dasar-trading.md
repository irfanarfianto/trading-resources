# 📖 01 - Dasar-Dasar Trading

## Apa itu Trading?

**Trading** adalah aktivitas membeli dan menjual aset (saham, forex, crypto, dll) dalam jangka waktu tertentu dengan tujuan mendapatkan profit dari pergerakan harga.

### Trading vs Investasi

| Aspek | Trading | Investasi |
|-------|---------|-----------|
| **Tujuan** | Profit dari fluktuasi harga | Profit dari pertumbuhan jangka panjang |
| **Holding Period** | Menit - Hari | Bulan - Tahun |
| **Analisis** | Technical (chart, pattern) | Fundamental (laporan keuangan) |
| **Frekuensi** | Sering (daily) | Jarang (buy & hold) |
| **Risk** | Higher | Lower |
| **Time Commitment** | Full-time | Part-time |
| **Stress Level** | High | Low |

**Contoh:**
- **Trading**: Beli BBRI @ 4,500 pagi, jual @ 4,600 sore (+2.2%)
- **Investasi**: Beli BBRI @ 4,000, hold 1 tahun, jual @ 5,000 (+25%)

---

## Jenis-Jenis Trading

### 1. Scalping ⚡
- **Holding Period**: 30 detik - 30 menit
- **Target Profit**: 0.3-1% per trade
- **Trades/Day**: 10-20+ trades
- **Difficulty**: ⭐⭐⭐⭐⭐ (Expert)
- **Time Commitment**: Very High (constant monitoring)

**Contoh:**
```
09:15 - Buy BBRI @ 4,500
09:20 - Sell BBRI @ 4,515 (+0.33% = Rp 15/share)
10 trades × 0.5% = 5% daily profit
```

### 2. Day Trading 📊
- **Holding Period**: 1-4 jam
- **Target Profit**: 2-5% per trade
- **Trades/Day**: 3-5 trades
- **Difficulty**: ⭐⭐⭐⭐ (Advanced)
- **Time Commitment**: High (market hours)

**Contoh:**
```
09:30 - Buy GOTO @ 70
12:00 - Sell GOTO @ 73 (+4.3%)
Close all positions before 14:45
```

### 3. Swing Trading 📈
- **Holding Period**: 2-7 hari
- **Target Profit**: 5-15% per trade
- **Trades/Week**: 2-5 trades
- **Difficulty**: ⭐⭐⭐ (Intermediate)
- **Time Commitment**: Medium (check 2-3x/day)

**Contoh:**
```
Senin - Buy BBCA @ 9,000
Jumat - Sell BBCA @ 9,500 (+5.6%)
Hold overnight (multi-day)
```

### 4. Position Trading 📉
- **Holding Period**: Minggu - Bulan
- **Target Profit**: 15-50% per trade
- **Trades/Month**: 1-3 trades
- **Difficulty**: ⭐⭐ (Beginner-friendly)
- **Time Commitment**: Low (check weekly)

**Contoh:**
```
Januari - Buy TLKM @ 3,000
Maret - Sell TLKM @ 3,600 (+20%)
Hold 2 bulan
```

---

## Cara Kerja Pasar Saham Indonesia (IHSG)

### Bursa Efek Indonesia (BEI/IDX)
- **Trading Hours**: 09:00 - 15:00 (Senin-Jumat)
- **Pre-Market**: 08:45 - 09:00 (order masuk, belum execute)
- **Session 1**: 09:00 - 12:00 (morning session)
- **Lunch Break**: 12:00 - 13:30 (low volume)
- **Session 2**: 13:30 - 15:00 (afternoon session)
- **Post-Market**: 15:00 - 15:15 (closing auction)

### Lot System
- **1 lot** = 100 shares
- Minimum order: 1 lot
- Contoh: Buy 5 lot BBRI @ 4,500 = 500 shares × Rp 4,500 = Rp 2,250,000

### Tick Size (Auto Rejection)
Pergerakan harga harus sesuai tick size:

| Harga Saham | Tick Size |
|-------------|-----------|
| < Rp 200 | Rp 1 |
| Rp 200 - 500 | Rp 2 |
| Rp 500 - 2,000 | Rp 5 |
| Rp 2,000 - 5,000 | Rp 10 |
| > Rp 5,000 | Rp 25 |

**Contoh:**
- BBRI @ 4,500 → tick Rp 10 → bisa 4,510, 4,520, 4,530 ✅
- BBRI @ 4,505 ❌ (tidak valid, tick harus Rp 10)

### Auto Rejection (ARB)
Batas pergerakan harga per hari:
- **ARB**: ±35% dari harga penutupan kemarin
- **ARB**: ±7% (first trigger), ±15% (second trigger)

**Contoh:**
- BBRI close kemarin: Rp 4,000
- ARB atas: Rp 5,400 (+35%)
- ARB bawah: Rp 2,600 (-35%)

---

## Istilah-Istilah Penting

### Order Types

**1. Market Order**
- Buy/sell segera di harga pasar saat ini
- Eksekusi cepat, tapi harga tidak pasti
- **Gunakan**: Saat butuh eksekusi cepat

**2. Limit Order**
- Buy/sell di harga spesifik yang Anda tentukan
- Eksekusi lambat (tunggu harga), tapi harga pasti
- **Gunakan**: Saat mau entry di level tertentu

**Contoh:**
```
Market Order:
- BBRI bid 4,500 / ask 4,510
- Market buy → dapat 4,510 (langsung)

Limit Order:
- BBRI bid 4,500 / ask 4,510
- Limit buy @ 4,500 → tunggu sampai ada seller di 4,500
```

### Bid & Ask

**Bid**: Harga tertinggi yang buyer mau bayar
**Ask**: Harga terendah yang seller mau terima
**Spread**: Selisih ask - bid

**Contoh:**
```
BBRI:
Bid: 4,500 (100 lot) ← Buyer mau beli di 4,500
Ask: 4,510 (50 lot)  ← Seller mau jual di 4,510
Spread: 10 poin
```

**Spread kecil** = Liquid (mudah buy/sell)
**Spread besar** = Illiquid (susah buy/sell)

### Volume

**Volume**: Jumlah saham yang diperdagangkan
- **High volume**: Banyak transaksi (liquid, valid)
- **Low volume**: Sedikit transaksi (illiquid, risky)

**Contoh:**
```
BBRI volume: 200M shares/day → Very liquid ✅
ABCD volume: 5M shares/day → Illiquid ❌
```

### Market Cap

**Market Cap** = Harga saham × Total shares outstanding

**Kategori:**
- **Large Cap**: > Rp 10 Triliun (BBRI, BBCA, TLKM)
- **Mid Cap**: Rp 1-10 Triliun
- **Small Cap**: < Rp 1 Triliun

**Large cap** = Stable, liquid, lower risk
**Small cap** = Volatile, illiquid, higher risk

---

## Profit & Loss (P&L)

### Cara Hitung P&L

**Formula:**
```
Profit/Loss = (Sell Price - Buy Price) × Shares - Fees

Profit % = ((Sell Price - Buy Price) / Buy Price) × 100%
```

**Contoh:**
```
Buy: 10 lot BBRI @ 4,500 (1,000 shares)
Sell: 10 lot BBRI @ 4,600

Profit = (4,600 - 4,500) × 1,000 = Rp 100,000
Profit % = (100 / 4,500) × 100% = 2.22%

Fees (0.3%):
- Buy fee: 4,500 × 1,000 × 0.15% = Rp 6,750
- Sell fee: 4,600 × 1,000 × 0.25% = Rp 11,500
- Total fee: Rp 18,250

Net Profit = Rp 100,000 - Rp 18,250 = Rp 81,750
```

### Trading Fees (Biaya)

**Biaya di Indonesia:**
1. **Broker fee**: 0.15-0.20% (buy + sell)
2. **VAT**: 11% dari broker fee
3. **Transaction fee**: 0.04% (sell only)
4. **Total**: ~0.3-0.4% (roundtrip)

**Contoh:**
```
Trade Rp 10,000,000
Total fee: Rp 30,000 - 40,000

Artinya: Profit minimal 0.4% baru break-even!
```

---

## Capital & Risk

### Berapa Modal Minimal?

**Rekomendasi:**
- **Pemula (learning)**: Rp 5-10 juta
- **Intermediate**: Rp 20-50 juta
- **Advanced**: Rp 50-100 juta+

**Kenapa?**
- Risk management: Max 2% per trade
- Diversifikasi: 3-5 posisi
- Fees: Agar tidak terlalu besar %

**Contoh:**
```
Modal: Rp 10 juta
Risk per trade: 2% = Rp 200,000
Max loss per trade: Rp 200,000

Jika SL 5%:
Position size = 200,000 / 5% = Rp 4,000,000 (40% modal)
```

### Risk Management Dasar

**Golden Rules:**
1. **Never risk > 2% per trade**
2. **Always use stop loss**
3. **Position size max 20-30% per trade**
4. **Keep 30-50% cash reserve**

---

## Mindset Trading

### Mindset yang Benar ✅

1. **Trading adalah bisnis**
   - Butuh modal, skill, waktu
   - Ada profit, ada loss
   - Konsistensi > profit besar sekali

2. **Focus on process, not profit**
   - Follow trading plan
   - Risk management first
   - Profit akan datang sendiri

3. **Losses are part of the game**
   - No trader win 100%
   - Cut loss cepat = bagus
   - Learn from mistakes

4. **Patience & discipline**
   - Wait for setup
   - Don't force trades
   - Stick to the plan

### Mindset yang Salah ❌

1. **Get rich quick**
   - Trading bukan judi
   - Butuh waktu & effort
   - Realistic expectations

2. **Revenge trading**
   - Loss → emosi → trade lagi
   - Biasanya loss lebih besar
   - Take a break!

3. **FOMO (Fear of Missing Out)**
   - Lihat orang profit → ikut
   - Entry tanpa analisa
   - Usually loss

4. **Overconfidence**
   - Profit → merasa jago
   - Nambah risk
   - Biasanya loss besar

---

## Langkah Awal Mulai Trading

### Step 1: Edukasi (1-2 bulan)
- ✅ Belajar dasar-dasar (baca semua materi)
- ✅ Pahami technical analysis
- ✅ Study chart patterns
- ✅ Understand risk management

### Step 2: Paper Trading (1-2 bulan)
- ✅ Simulasi trading (TradingView, demo account)
- ✅ Test strategies
- ✅ Build confidence
- ✅ Target win rate >50%

### Step 3: Real Trading - Small Capital (3-6 bulan)
- ✅ Mulai dengan modal kecil (Rp 5-10 juta)
- ✅ Follow trading plan strictly
- ✅ Journal every trade
- ✅ Focus on consistency

### Step 4: Scale Up (6+ bulan)
- ✅ Jika konsisten profitable 6 bulan
- ✅ Naikkan capital gradually
- ✅ Maintain discipline
- ✅ Never stop learning

---

## Checklist Pemula

Sebelum mulai trading, pastikan:

- [ ] Sudah belajar dasar-dasar trading
- [ ] Punya broker account (Mandiri Sekuritas, Mirae, dll)
- [ ] Punya charting tool (TradingView)
- [ ] Punya modal yang siap hilang (risk capital)
- [ ] Punya trading plan
- [ ] Punya trading journal
- [ ] Understand risk management
- [ ] Mental siap (losses are normal)
- [ ] Time commitment (monitor market)
- [ ] Emergency fund (6-12 bulan)

**Jika ada yang belum ✅ → JANGAN trading dulu!**

---

## Next Steps

1. **Lanjut ke**: [Chart & Candlestick](./02-chart-candlestick.md)
2. **Practice**: Buka TradingView, lihat chart BBRI, GOTO, TLKM
3. **Study**: 30 menit setiap hari
4. **Patience**: Jangan rush!

---

**Remember: "Trading is a marathon, not a sprint. Learn the basics well!"** 🎓
