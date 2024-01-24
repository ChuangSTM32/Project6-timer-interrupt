# STM32 Project - 計時器中斷

這是一個用於 STM32F4 系列微控制器的示例項目，旨在設計一個向上計時器。

## 硬件要求

- STM32F429ZIT6 微控制器
- OLED 0.96 I2C

## 軟件依賴

- STM32CubeIDE

## 學習目標

- 使用 timer interrupt，更新計時器數字

## 電路圖

![STM32 Board](images/circuit.png)

## 構建和編譯

1. 在 STM32CubeIDE 中打開 .cproject
2. 編譯並燒寫至您的微控制器

## 使用方法

將編譯好的程序燒寫到 STM32 微控制器後，OLED 上的數字，每秒加一
