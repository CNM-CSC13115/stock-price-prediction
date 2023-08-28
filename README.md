# Stock Prediction

# Machine Learning Project

## ℹ️ Thông tin nhóm

- 19127552 - Nguyễn Thanh Thảo
- 20127098 - Đỗ Thuỵ Phương Vy

## 📃 Yêu cầu

- Python > 3.10

## 📦 Hướng dẫn cài đặt

### Install các thư viện

#### 🐳 Cài đặt thư viện

```sh
  pip install keras tensorflow xgboost alpha_vantage dash pandas matplotlib scikit-learn
```

### Run locally

- Mở terminal tại thư mục gốc và gõ lệnh bên dưới:

```sh
  cd APP
  python stock_app.py
```

## Demo

🎬 Youtube: https://youtu.be/lMYBRlqPUoM

## Các tính năng đã làm được

- Người dùng chọn một trong các phương pháp dự đoán
  - XGBoost
  - RNN
  - LSTM
- Người dùng chọn một hay nhiều đặc trưng để dự đoán
  - Close, Price of Change
  - RSI, Bolling Bands, Moving Average
- Hiển thị giá dự đoán của timeframe kế tiếp
- Lấy dữ liệu từ Alpha Vantage
  - Lấy dữ liệu của 1000 nến lịch sử
  - Dự đoán timeframe kế tiếp
  - Lấy dữ liệu real-time append vô dữ liệu hiện tại
