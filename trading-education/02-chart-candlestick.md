# 📊 02 - Chart & Candlestick

## Apa itu Chart?

**Chart** adalah representasi visual dari pergerakan harga saham dalam periode waktu tertentu. Chart membantu trader melihat trend, pattern, dan momentum.

---

## Jenis-Jenis Chart

### 1. Line Chart (Garis)
- Paling sederhana
- Hanya menunjukkan closing price
- Kurang detail

```
Kelebihan: Simple, mudah lihat trend
Kekurangan: Tidak ada info open, high, low
```

### 2. Bar Chart (Batang)
- Menunjukkan OHLC (Open, High, Low, Close)
- Lebih detail dari line chart

```
|  ← High
├─ ← Open (kiri)
├─ ← Close (kanan)
|  ← Low
```

### 3. Candlestick Chart (Lilin) ⭐ PALING POPULER
- Menunjukkan OHLC dengan visual yang jelas
- Mudah baca sentiment (bullish/bearish)
- Paling banyak digunakan trader

---

## Anatomy Candlestick

```
        |  ← Upper Shadow (Sumbu Atas)
        |
    ┌───┐
    │   │  ← Body (Badan)
    │   │
    └───┘
        |
        |  ← Lower Shadow (Sumbu Bawah)
```

### Komponen Candlestick:

1. **Body (Badan)**
   - Jarak antara Open dan Close
   - Hijau/Putih = Bullish (Close > Open)
   - Merah/Hitam = Bearish (Close < Open)

2. **Upper Shadow (Sumbu Atas)**
   - Dari top of body ke High
   - Menunjukkan rejection di atas

3. **Lower Shadow (Sumbu Bawah)**
   - Dari bottom of body ke Low
   - Menunjukkan rejection di bawah

### Bullish Candle (Hijau) 🟢
```
Close → ┌───┐  ← High
        │   │
        │   │
Open  → └───┘
            ↓
           Low
```
- **Open < Close** (harga naik)
- **Sentiment**: Buyers menang
- **Warna**: Hijau/Putih

### Bearish Candle (Merah) 🔴
```
Open  → ┌───┐  ← High
        │   │
        │   │
Close → └───┘
            ↓
           Low
```
- **Open > Close** (harga turun)
- **Sentiment**: Sellers menang
- **Warna**: Merah/Hitam

---

## Timeframe

**Timeframe** = Periode waktu yang direpresentasikan oleh 1 candlestick

### Jenis Timeframe:

| Timeframe | 1 Candle = | Untuk Trading |
|-----------|------------|---------------|
| **1 Minute (1M)** | 1 menit | Scalping |
| **5 Minute (5M)** | 5 menit | Scalping, Day Trading |
| **15 Minute (15M)** | 15 menit | Day Trading |
| **1 Hour (1H)** | 1 jam | Day Trading, Swing |
| **4 Hour (4H)** | 4 jam | Swing Trading |
| **Daily (1D)** | 1 hari | Swing, Position |
| **Weekly (1W)** | 1 minggu | Position Trading |

### Multiple Timeframe Analysis

**Konsep**: Lihat chart di beberapa timeframe untuk konfirmasi

**Contoh:**
```
Daily Chart: Uptrend (big picture)
1H Chart: Pullback (koreksi sementara)
15M Chart: Entry signal (buy di support)

Action: BUY (trend besar naik, entry di pullback)
```

**Rule of Thumb:**
- **Higher timeframe** = Trend direction
- **Lower timeframe** = Entry timing

---

## Pola Candlestick Dasar

### Single Candlestick Patterns

#### 1. Doji
```
    |
    |
  ─┼─  ← Body sangat kecil
    |
    |
```
- **Arti**: Indecision (buyers vs sellers seimbang)
- **Signal**: Possible reversal
- **Konfirmasi**: Tunggu candle berikutnya

#### 2. Hammer (Bullish) 🔨
```
    ┌─┐
    └─┘
     |
     |
     |  ← Long lower shadow
```
- **Arti**: Rejection di bawah (buyers push up)
- **Signal**: Bullish reversal
- **Kondisi**: Muncul di downtrend/support

#### 3. Shooting Star (Bearish) ⭐
```
     |
     |
     |  ← Long upper shadow
    ┌─┐
    └─┘
```
- **Arti**: Rejection di atas (sellers push down)
- **Signal**: Bearish reversal
- **Kondisi**: Muncul di uptrend/resistance

#### 4. Marubozu (Strong Trend)
```
Bullish:        Bearish:
┌───┐           ┌───┐
│   │           │   │
│   │           │   │
│   │           │   │
└───┘           └───┘
No shadow       No shadow
```
- **Arti**: Strong momentum (no rejection)
- **Signal**: Continuation
- **Bullish**: Buyers sangat kuat
- **Bearish**: Sellers sangat kuat

---

### Double Candlestick Patterns

#### 1. Bullish Engulfing (Bullish) 🟢
```
  ┌─┐ ┌───┐
  │ │ │   │  ← Green candle "menelan"
  └─┘ │   │     red candle sebelumnya
      └───┘
```
- **Arti**: Buyers mengambil alih
- **Signal**: Strong bullish reversal
- **Kondisi**: Di downtrend/support

#### 2. Bearish Engulfing (Bearish) 🔴
```
  ┌───┐ ┌─┐
  │   │ │ │  ← Red candle "menelan"
  │   │ └─┘     green candle sebelumnya
  └───┘
```
- **Arti**: Sellers mengambil alih
- **Signal**: Strong bearish reversal
- **Kondisi**: Di uptrend/resistance

#### 3. Tweezer Top/Bottom
```
Tweezer Top (Bearish):
  |   |
┌─┐ ┌─┐  ← Same high
└─┘ │ │
    └─┘

Tweezer Bottom (Bullish):
┌─┐ ┌─┐
│ │ └─┘
└─┘   |  ← Same low
      |
```
- **Arti**: Double rejection
- **Signal**: Reversal
- **Konfirmasi**: Breakout candle berikutnya

---

### Triple Candlestick Patterns

#### 1. Morning Star (Bullish) 🌅
```
┌─┐     ┌───┐
│ │  ─  │   │  ← 3 candles
└─┘     │   │
        └───┘
```
1. Red candle (downtrend)
2. Small candle (indecision)
3. Green candle (reversal)

**Signal**: Strong bullish reversal

#### 2. Evening Star (Bearish) 🌆
```
┌───┐     ┌─┐
│   │  ─  │ │  ← 3 candles
│   │     └─┘
└───┘
```
1. Green candle (uptrend)
2. Small candle (indecision)
3. Red candle (reversal)

**Signal**: Strong bearish reversal

#### 3. Three White Soldiers (Bullish) 🟢🟢🟢
```
        ┌───┐
    ┌───┐   │
┌───┐   │   │  ← 3 green candles
│   │   │   │
└───┘   └───┘
```
- **Arti**: Strong buying pressure
- **Signal**: Strong uptrend continuation
- **Kondisi**: Setelah consolidation/downtrend

#### 4. Three Black Crows (Bearish) 🔴🔴🔴
```
┌───┐
│   │   ┌───┐
│   │   │   │   ┌───┐  ← 3 red candles
└───┘   │   │   │   │
        └───┘   └───┘
```
- **Arti**: Strong selling pressure
- **Signal**: Strong downtrend continuation
- **Kondisi**: Setelah consolidation/uptrend

---

## Cara Membaca Candlestick

### 1. Body Size (Ukuran Badan)

**Large Body** = Strong momentum
```
┌───┐
│   │
│   │  ← Big body = strong move
│   │
└───┘
```

**Small Body** = Weak momentum / Indecision
```
  ┌─┐
  └─┘  ← Small body = weak move
```

### 2. Shadow Length (Panjang Sumbu)

**Long Upper Shadow** = Rejection di atas
```
  |
  |
  |  ← Sellers reject high prices
┌─┐
└─┘
```

**Long Lower Shadow** = Rejection di bawah
```
┌─┐
└─┘
  |
  |  ← Buyers reject low prices
  |
```

### 3. Color (Warna)

**Green** = Bullish (buyers win)
**Red** = Bearish (sellers win)

**Consecutive greens** = Uptrend
**Consecutive reds** = Downtrend

---

## Volume & Candlestick

**Volume** = Konfirmasi kekuatan candle

### High Volume + Bullish Candle = Strong Buy Signal ✅
```
┌───┐
│   │  ← Big green candle
│   │
└───┘
█████  ← High volume bar
```

### High Volume + Bearish Candle = Strong Sell Signal ✅
```
┌───┐
│   │  ← Big red candle
│   │
└───┘
█████  ← High volume bar
```

### Low Volume + Any Candle = Weak Signal ❌
```
┌───┐
│   │  ← Any candle
└───┘
██     ← Low volume = tidak valid
```

**Rule**: Always confirm candlestick pattern with volume!

---

## Practice: Cara Baca Chart

### Step 1: Identify Timeframe
- Scalping: 1M, 5M
- Day Trading: 15M, 1H
- Swing: 4H, Daily

### Step 2: Identify Trend
- **Uptrend**: Higher highs + higher lows
- **Downtrend**: Lower highs + lower lows
- **Sideways**: Range-bound

### Step 3: Look for Patterns
- Single candle (doji, hammer, shooting star)
- Double candle (engulfing)
- Triple candle (morning/evening star)

### Step 4: Confirm with Volume
- Pattern + high volume = valid ✅
- Pattern + low volume = skip ❌

### Step 5: Identify Support/Resistance
- Where did price bounce before?
- Where did price reject before?

---

## Common Mistakes

### ❌ Mistake 1: Trading Every Pattern
- **Wrong**: Lihat hammer → langsung buy
- **Right**: Hammer + support + volume → buy

### ❌ Mistake 2: Ignoring Timeframe
- **Wrong**: Lihat bullish di 1M, buy untuk swing
- **Right**: Match timeframe dengan trading style

### ❌ Mistake 3: No Volume Confirmation
- **Wrong**: Pattern bagus tapi volume rendah
- **Right**: Pattern + volume tinggi

### ❌ Mistake 4: Trading Against Trend
- **Wrong**: Downtrend tapi buy karena 1 hammer
- **Right**: Tunggu trend reversal confirmation

---

## Checklist Analisa Candlestick

Before entry, pastikan:

- [ ] Timeframe sesuai trading style
- [ ] Trend identified (up/down/sideways)
- [ ] Pattern recognized (hammer, engulfing, dll)
- [ ] Volume confirmation (high volume)
- [ ] Support/resistance nearby
- [ ] Multiple timeframe aligned
- [ ] Risk/reward > 1:2

**Jika semua ✅ → Consider entry**
**Jika ada yang ❌ → Skip atau wait**

---

## Practice Exercise

### Daily Practice (15-30 menit):
1. Buka TradingView
2. Pilih 3 saham (BBRI, GOTO, TLKM)
3. Lihat chart 15M dan 1H
4. Identify:
   - Trend (up/down/sideways)
   - Candlestick patterns
   - Support/resistance
   - Volume
5. Screenshot dan catat di journal

### Weekly Review:
- Review semua screenshot
- Apakah pattern valid?
- Apakah ada volume?
- Apa yang bisa dipelajari?

---

## Next Steps

1. **Lanjut ke**: [Support & Resistance](./03-support-resistance.md)
2. **Practice**: Buka TradingView, study 10 charts
3. **Identify**: Cari 5 candlestick patterns
4. **Journal**: Screenshot dan catat

---

**Remember: "Candlesticks tell a story. Learn to read it!"** 📊🕯️
