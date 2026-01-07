# 📊 04 - Indikator Teknikal

## Apa itu Indikator Teknikal?

**Indikator Teknikal** adalah perhitungan matematis berdasarkan harga, volume, atau open interest yang membantu trader menganalisis trend, momentum, volatility, dan volume.

### Fungsi Indikator:
1. **Konfirmasi** trend atau pattern
2. **Prediksi** pergerakan harga
3. **Signal** entry/exit
4. **Identifikasi** overbought/oversold

### ⚠️ PENTING:
> **Indikator BUKAN crystal ball!** Indikator hanya alat bantu, bukan jaminan profit. Selalu kombinasikan dengan price action, S/R, dan risk management.

---

## Kategori Indikator

### 1. Trend Indicators (Indikator Trend)
- **Fungsi**: Identifikasi arah trend
- **Contoh**: Moving Average, MACD, ADX
- **Best for**: Trending market

### 2. Momentum Indicators (Indikator Momentum)
- **Fungsi**: Ukur kekuatan pergerakan
- **Contoh**: RSI, Stochastic, CCI
- **Best for**: Overbought/oversold

### 3. Volatility Indicators (Indikator Volatilitas)
- **Fungsi**: Ukur volatilitas harga
- **Contoh**: Bollinger Bands, ATR
- **Best for**: Breakout trading

### 4. Volume Indicators (Indikator Volume)
- **Fungsi**: Analisa volume trading
- **Contoh**: Volume, VWAP, OBV
- **Best for**: Konfirmasi

---

## 1️⃣ MOVING AVERAGE (MA)

### Apa itu MA?

**Moving Average** = Rata-rata harga dalam periode tertentu

**Fungsi:**
- Identifikasi trend direction
- Dynamic support/resistance
- Entry/exit signal

### Jenis MA:

#### Simple Moving Average (SMA)
```
SMA = (P1 + P2 + P3 + ... + Pn) / n

Contoh SMA 5:
Day 1: 100
Day 2: 102
Day 3: 104
Day 4: 103
Day 5: 106

SMA 5 = (100+102+104+103+106) / 5 = 103
```

**Karakteristik:**
- Smooth (halus)
- Lambat respond
- Good untuk long-term trend

#### Exponential Moving Average (EMA)
```
EMA = (Price × K) + (Previous EMA × (1-K))
K = 2 / (n+1)

Contoh: EMA 5
K = 2/(5+1) = 0.333
```

**Karakteristik:**
- Lebih sensitif ke harga terbaru
- Cepat respond
- Good untuk short-term trading

### MA Periods (Periode):

| Period | Timeframe | Untuk |
|--------|-----------|-------|
| **MA 9-20** | Short-term | Day trading, scalping |
| **MA 50** | Medium-term | Swing trading |
| **MA 100-200** | Long-term | Position trading, trend |

### Cara Menggunakan MA:

#### 1. Trend Identification
```
Price > MA → Uptrend ✅
Price < MA → Downtrend ✅
Price = MA → Sideways/Transition
```

**Visual:**
```
Price
  ↑
  │    ╱╲   ╱
  │   ╱  ╲ ╱  ← Price di atas MA = Uptrend
  ├──────────── ← MA 50
  │
```

#### 2. Dynamic Support/Resistance
```
Uptrend: MA jadi support
Downtrend: MA jadi resistance
```

**Trading Strategy:**
```
Uptrend:
- Buy saat price pullback ke MA
- SL di bawah MA
- TP di resistance berikutnya
```

#### 3. MA Crossover (Golden/Death Cross)

**Golden Cross (Bullish)** 🟢
```
MA Short (50) cross ABOVE MA Long (200)
= Strong bullish signal
```

**Death Cross (Bearish)** 🔴
```
MA Short (50) cross BELOW MA Long (200)
= Strong bearish signal
```

**Visual:**
```
Price
  ↑
  │         ╱ ← MA 50
  │        ╱
  │    ╱╲ ╱
  │   ╱  ╳  ← Golden Cross (bullish)
  │  ╱  ╱ ╲
  │ ╱  ╱   ╲ ← MA 200
  │╱  ╱
```

### MA Settings untuk Day Trading:
- **EMA 9** (very short-term)
- **EMA 20** (short-term)
- **EMA 50** (medium-term)

**Strategy:**
```
EMA 9 > EMA 20 > EMA 50 = Strong uptrend
→ Look for buy opportunities

EMA 9 < EMA 20 < EMA 50 = Strong downtrend
→ Look for sell opportunities
```

---

## 2️⃣ RSI (Relative Strength Index)

### Apa itu RSI?

**RSI** = Momentum oscillator yang mengukur kecepatan dan perubahan pergerakan harga.

**Range**: 0 - 100

**Formula:**
```
RSI = 100 - (100 / (1 + RS))
RS = Average Gain / Average Loss
```

### RSI Zones:

```
100 ├─────────────── ← Overbought (>70)
 70 ├───────────────
    │
 50 ├─────────────── ← Neutral
    │
 30 ├───────────────
  0 ├─────────────── ← Oversold (<30)
```

**Interpretasi:**
- **RSI > 70**: Overbought (harga terlalu tinggi, mungkin turun)
- **RSI < 30**: Oversold (harga terlalu rendah, mungkin naik)
- **RSI 50**: Neutral (no clear signal)

### Cara Menggunakan RSI:

#### 1. Overbought/Oversold Signal

**Oversold → Buy Signal** 🟢
```
RSI < 30 → Oversold
Price likely to bounce up
→ Consider BUY
```

**Overbought → Sell Signal** 🔴
```
RSI > 70 → Overbought
Price likely to pull back
→ Consider SELL
```

**⚠️ WARNING:**
- **Strong uptrend**: RSI bisa stay >70 lama (don't sell!)
- **Strong downtrend**: RSI bisa stay <30 lama (don't buy!)

#### 2. RSI Divergence (Powerful!)

**Bullish Divergence** 🟢
```
Price: Lower low
RSI: Higher low
→ Momentum weakening, possible reversal UP
```

**Visual:**
```
Price:  ╲    ╲
         ╲    ╲  ← Lower low
          ╲    ╲

RSI:     ╲   ╱
          ╲ ╱   ← Higher low (divergence!)
           ╲
```

**Bearish Divergence** 🔴
```
Price: Higher high
RSI: Lower high
→ Momentum weakening, possible reversal DOWN
```

#### 3. RSI Centerline (50)

```
RSI cross above 50 → Bullish momentum
RSI cross below 50 → Bearish momentum
```

### RSI Settings:
- **Default**: 14 periods (recommended)
- **Day Trading**: 9-14 periods
- **Scalping**: 5-9 periods

### RSI Strategy:

**Strategy 1: Overbought/Oversold**
```
1. Wait RSI < 30 (oversold)
2. Wait price bounce (bullish candle)
3. BUY
4. TP when RSI > 70
5. SL below support
```

**Strategy 2: RSI + Trend**
```
Uptrend + RSI pullback to 40-50
→ BUY (pullback dalam uptrend)

Downtrend + RSI bounce to 50-60
→ SELL (bounce dalam downtrend)
```

---

## 3️⃣ MACD (Moving Average Convergence Divergence)

### Apa itu MACD?

**MACD** = Trend-following momentum indicator yang menunjukkan hubungan antara 2 moving averages.

**Komponen:**
1. **MACD Line** (biru): EMA 12 - EMA 26
2. **Signal Line** (merah): EMA 9 dari MACD Line
3. **Histogram**: MACD Line - Signal Line

**Visual:**
```
Price Chart
─────────────

MACD Chart:
    │     ╱╲
    │    ╱  ╲  ← MACD Line (biru)
    ├───╱────╲─── ← Signal Line (merah)
    │  ╱      ╲
    │ ╱        ╲
    │╱          ╲
────┼────────────── ← Zero Line
    │
    ║║║║║║║║  ← Histogram
```

### Cara Menggunakan MACD:

#### 1. MACD Crossover

**Bullish Crossover** 🟢
```
MACD Line cross ABOVE Signal Line
→ Buy signal
```

**Bearish Crossover** 🔴
```
MACD Line cross BELOW Signal Line
→ Sell signal
```

#### 2. Zero Line Cross

**Bullish** 🟢
```
MACD cross above zero line
→ Uptrend confirmed
```

**Bearish** 🔴
```
MACD cross below zero line
→ Downtrend confirmed
```

#### 3. Histogram

**Histogram Growing** = Momentum strengthening
**Histogram Shrinking** = Momentum weakening

```
Histogram:
    ║
    ║║
    ║║║  ← Growing = Strong momentum
    ║║
    ║
```

#### 4. MACD Divergence

**Bullish Divergence** 🟢
```
Price: Lower low
MACD: Higher low
→ Possible reversal UP
```

**Bearish Divergence** 🔴
```
Price: Higher high
MACD: Lower high
→ Possible reversal DOWN
```

### MACD Settings:
- **Default**: 12, 26, 9 (recommended)
- **Fast**: 5, 13, 5 (untuk scalping)
- **Slow**: 19, 39, 9 (untuk swing)

### MACD Strategy:

**Strategy: MACD + Trend**
```
1. Identify trend (price > MA 50 = uptrend)
2. Wait MACD pullback (cross below signal)
3. Wait MACD cross back above signal
4. BUY
5. TP when MACD cross below signal again
6. SL below support
```

---

## 4️⃣ BOLLINGER BANDS

### Apa itu Bollinger Bands?

**Bollinger Bands** = Volatility indicator yang terdiri dari 3 garis:
1. **Middle Band**: SMA 20
2. **Upper Band**: SMA 20 + (2 × Standard Deviation)
3. **Lower Band**: SMA 20 - (2 × Standard Deviation)

**Visual:**
```
Price
  ↑
  ├─────────────── ← Upper Band
  │    ╱╲   ╱╲
  │   ╱  ╲ ╱  ╲
  ├──────────────── ← Middle Band (SMA 20)
  │  ╱    ╲╱    ╲
  │ ╱            ╲
  ├─────────────── ← Lower Band
```

### Interpretasi:

#### 1. Volatility
```
Bands Wide (lebar) = High volatility
Bands Narrow (sempit) = Low volatility
```

**Squeeze (Bands sempit):**
```
  ├───── ← Bands sempit
  ├─────
  ├───── ← Possible breakout soon!
```

#### 2. Overbought/Oversold
```
Price touch Upper Band = Overbought (consider sell)
Price touch Lower Band = Oversold (consider buy)
```

#### 3. Trend
```
Price consistently near Upper Band = Strong uptrend
Price consistently near Lower Band = Strong downtrend
```

### Bollinger Bands Strategy:

**Strategy 1: Bounce Trading (Sideways)**
```
1. Market sideways (range-bound)
2. Price touch Lower Band
3. Wait bullish candle
4. BUY
5. TP at Middle Band or Upper Band
6. SL below Lower Band
```

**Strategy 2: Breakout Trading**
```
1. Bands squeeze (sempit)
2. Wait breakout (price keluar dari bands)
3. Confirm with volume
4. BUY/SELL (follow breakout direction)
5. TP at next S/R
6. SL at opposite band
```

**Strategy 3: Bollinger Squeeze**
```
Bands sempit → Volatility rendah
→ Big move coming soon!
→ Wait for breakout, then trade
```

### Bollinger Settings:
- **Default**: 20, 2 (20 periods, 2 std dev)
- **Sensitive**: 20, 1.5
- **Conservative**: 20, 2.5

---

## 5️⃣ VWAP (Volume Weighted Average Price)

### Apa itu VWAP?

**VWAP** = Average price weighted by volume (harga rata-rata tertimbang volume)

**Fungsi:**
- Benchmark harga (fair value)
- Dynamic support/resistance
- Institutional traders reference

**Formula:**
```
VWAP = Σ(Price × Volume) / Σ(Volume)
```

### Cara Menggunakan VWAP:

#### 1. Trend Identification
```
Price > VWAP = Bullish (buyers in control)
Price < VWAP = Bearish (sellers in control)
```

#### 2. Support/Resistance
```
Uptrend: VWAP jadi support
Downtrend: VWAP jadi resistance
```

#### 3. Entry Signal

**Buy Setup:**
```
1. Price above VWAP (uptrend)
2. Price pullback to VWAP
3. Bounce from VWAP
4. BUY
5. SL below VWAP
```

**Sell Setup:**
```
1. Price below VWAP (downtrend)
2. Price bounce to VWAP
3. Reject at VWAP
4. SELL
5. SL above VWAP
```

### VWAP Strategy (Day Trading):

**Morning Strategy:**
```
09:00-10:00:
- Observe where price vs VWAP
- Price > VWAP → Look for buy
- Price < VWAP → Look for sell
```

**Intraday Strategy:**
```
1. Price cross above VWAP (bullish)
2. Wait pullback to VWAP
3. BUY when bounce
4. TP at resistance
5. SL below VWAP
```

**⚠️ Note:**
- VWAP reset setiap hari (intraday indicator)
- Best untuk day trading & scalping
- Institutional traders use VWAP

---

## 6️⃣ VOLUME

### Apa itu Volume?

**Volume** = Jumlah saham yang diperdagangkan dalam periode tertentu

**Fungsi:**
- Konfirmasi trend
- Konfirmasi breakout
- Identifikasi reversal

### Volume Analysis:

#### 1. Volume + Price

**High Volume + Price Up** = Strong buying ✅
```
Price:  ╱
       ╱
Volume: ████████ ← High volume
```

**High Volume + Price Down** = Strong selling ✅
```
Price:  ╲
         ╲
Volume: ████████ ← High volume
```

**Low Volume + Any Move** = Weak signal ❌
```
Price:  ╱ or ╲
Volume: ██ ← Low volume (not valid)
```

#### 2. Volume Spike

**Volume Spike** = Unusual high volume

**Interpretasi:**
- **Spike + Breakout** = Valid breakout ✅
- **Spike + Reversal** = Possible trend change ✅
- **Spike + No clear move** = Indecision ⚠️

#### 3. Volume Trend

**Increasing Volume in Uptrend** = Healthy ✅
```
Price:    ╱
         ╱
Volume: ██ ███ ████ ← Increasing
```

**Decreasing Volume in Uptrend** = Weakening ⚠️
```
Price:    ╱
         ╱
Volume: ████ ███ ██ ← Decreasing (warning!)
```

### Volume Strategy:

**Breakout Confirmation:**
```
1. Price at resistance
2. Wait breakout
3. Check volume:
   - High volume → Valid ✅ (trade)
   - Low volume → False ❌ (skip)
```

**Reversal Confirmation:**
```
1. Downtrend
2. Price at support
3. Bullish candle + High volume
4. → Possible reversal (consider buy)
```

---

## 🎯 Kombinasi Indikator (Powerful!)

### Combo 1: MA + RSI (Trend + Momentum)
```
Setup:
1. Price > MA 50 (uptrend)
2. RSI pullback to 40-50
3. RSI bounce up
4. BUY
5. TP when RSI > 70
6. SL below MA 50
```

### Combo 2: MACD + Bollinger Bands
```
Setup:
1. Bollinger squeeze (bands sempit)
2. MACD cross above signal
3. Price breakout upper band
4. BUY
5. TP at next resistance
6. SL at middle band
```

### Combo 3: MA + VWAP + Volume (Triple Confirmation)
```
Setup:
1. Price > MA 20 AND Price > VWAP (uptrend)
2. Price pullback to VWAP
3. Bounce with high volume
4. BUY
5. TP at resistance
6. SL below VWAP
```

### Combo 4: RSI + MACD (Divergence)
```
Setup:
1. Price: Lower low
2. RSI: Higher low (divergence)
3. MACD: Higher low (divergence)
4. Double divergence = Strong signal!
5. BUY
6. TP at resistance
7. SL below support
```

---

## ⚠️ Common Mistakes

### ❌ Mistake 1: Too Many Indicators
```
Wrong: MA + RSI + MACD + BB + Stochastic + ...
Right: 2-3 indikator max (simple is better!)
```

### ❌ Mistake 2: Indikator Tanpa Price Action
```
Wrong: RSI oversold → langsung buy
Right: RSI oversold + support + bullish candle → buy
```

### ❌ Mistake 3: Ignore Volume
```
Wrong: Breakout tanpa volume
Right: Breakout + high volume = valid
```

### ❌ Mistake 4: Wrong Timeframe
```
Wrong: Lihat RSI di 1M untuk swing trading
Right: Match indikator dengan trading style
```

### ❌ Mistake 5: Indikator Lag
```
Remember: Indikator based on past data!
→ Always confirm with current price action
```

---

## 📊 Indikator untuk Trading Style

### Scalping (1M, 5M):
- **EMA 9, 20** (fast MA)
- **RSI 5-9** (sensitive)
- **VWAP** (intraday reference)
- **Volume** (confirmation)

### Day Trading (15M, 1H):
- **EMA 20, 50** (trend)
- **RSI 14** (momentum)
- **MACD** (12,26,9)
- **Bollinger Bands** (volatility)
- **VWAP** (support/resistance)

### Swing Trading (4H, Daily):
- **SMA 50, 200** (trend)
- **RSI 14** (overbought/oversold)
- **MACD** (trend confirmation)
- **Bollinger Bands** (breakout)

---

## ✅ Checklist Menggunakan Indikator

Before entry:

- [ ] Max 2-3 indikator (don't overload!)
- [ ] Indikator align (semua bullish/bearish)
- [ ] Confirm dengan price action
- [ ] Confirm dengan S/R
- [ ] Confirm dengan volume
- [ ] Timeframe sesuai trading style
- [ ] Understand what indikator tells you

**Semua ✅ → Consider entry**
**Ada yang ❌ → Skip atau wait**

---

## 🎓 Practice Exercise

### Daily Practice (30 menit):
1. Buka TradingView
2. Pilih 1 saham (BBRI, GOTO, TLKM)
3. Add indikator:
   - MA 20, 50
   - RSI 14
   - MACD
4. Analyze:
   - Trend (MA)
   - Momentum (RSI)
   - Signal (MACD)
5. Screenshot & journal

### Weekly Review:
- Apakah signal valid?
- Apakah indikator align?
- Apakah ada false signal?
- What can be improved?

---

## 💡 Pro Tips

### 1. Less is More
- 2-3 indikator cukup
- Lebih banyak ≠ lebih baik
- Focus on mastering few indicators

### 2. Indikator = Confirmation Tool
- Bukan crystal ball
- Konfirmasi price action
- Konfirmasi S/R

### 3. Backtest
- Test indikator di historical data
- Lihat win rate
- Adjust settings jika perlu

### 4. Combine with Price Action
- Indikator + candlestick pattern
- Indikator + S/R
- Indikator + volume

---

## Next Steps

1. **Lanjut ke**: [Chart Patterns](./05-chart-patterns.md)
2. **Practice**: Add indikator di TradingView
3. **Backtest**: Test 1 strategy dengan indikator
4. **Journal**: Catat hasil & learning

---

**Remember: "Indicators are tools, not magic. Master the basics, then add indicators for confirmation!"** 📊🎯
