# ECOCO 場勘 AR 模型包

本包提供場勘工具使用的機型與外觀版本，每個款式可直接載入對應的 GLB。

## 使用方式

1. 讀取 `latest.json`。
2. 依 `models[].variants[].asset` 載入對應 GLB。
3. 模型座標以公分建立；若 WebXR 場景 1 單位代表 1 公尺，請將模型根節點縮放為 `0.01`。
4. 尺寸顯示以 `size_cm` 為準。
5. 更新時以 `release` 與每個檔案的 `sha256` 判斷是否需要清除快取。

模型顯示尺寸請以 `latest.json` 的 `size_cm` 為準。
