# 大氣層個人整合包生成腳本

## 功能如下：

- 下載最新：
  - 大氣層三件套
    - [x] `Atmosphere + Fusee` [From Here](https://github.com/Atmosphere-NX/Atmosphere/releases/latest)
    - [x] `Hekate + Nyx 繁體中文` [From Here](https://github.com/easyworld/hekate/releases/latest)
    - [x] `Sigpatches` [From Here](https://hackintendo.com/download/sigpatches/)
  - Payload插件
    - [x] 主機系統的密鑰提取工具 `Lockpick_RCM` [From Here](https://github.com/zdm65477730/Lockpick_RCMDecScots/releases/latest)
    - [x] Hekate下的文件管理工具 `TegraExplorer` [From Here](https://github.com/zdm65477730/TegraExplorer/releases/latest)
    - [x] Hekate下刪除主題和關閉插件自動啟動 `CommonProblemResolver` [From Here](https://github.com/zdm65477730/CommonProblemResolver/releases/latest)
  - Nro插件
    - [x] 聯網檢測是否屏蔽任天堂服務器 `Switch_90DNS_tester` [From Here](https://github.com/meganukebmp/Switch_90DNS_tester/releases/latest)
    - [x] 遊戲安裝，存檔管理和文件傳輸工具 `DBI` [From Here](https://github.com/rashevskyv/dbi/releases/latest)
    - [x] 遊戲安裝和文件傳輸工具 `Awoo Installer` [From Here](https://github.com/dragonflylee/Awoo-Installer/releases/latest)
    - [x] 深海工具箱 `Hekate-toolbox` [From Here](https://github.com/WerWolv/Hekate-Toolbox/releases/latest)
    - [x] 遊戲遊玩時間記錄工具 `NX-Activity-Log` [From Here](https://github.com/zdm65477730/NX-Activity-Log/releases/latest)
    - [x] 主題安裝工具 `NXThemesInstaller` [From Here](https://github.com/exelix11/SwitchThemeInjector/releases/latest)
    - [x] 遊戲存檔管理工具 `JKSV` [From Here](https://github.com/J-D-K/JKSV/releases/latest)
    - [ ] ~~系統切換工具 `tencent-switcher-gui` [From Here](https://github.com/CaiMiao/Tencent-switcher-GUI/releases/latest)~~
    - [x] 多工具合一任天堂Switch更新器 `aio-switch-updater` [From Here](https://github.com/HamletDuFromage/aio-switch-updater/releases/latest)
    - [x] 第三方B站客戶端 `wiliwili` [From Here](https://github.com/xfangfang/wiliwili/releases/latest)
    - [x] Mod下載器 `SimpleModDownloader` [From Here](https://github.com/PoloNX/SimpleModDownloader/releases/latest)
    - [x] Jellyfin客戶端 `Switchfin` [From Here](https://github.com/dragonflylee/switchfin/releases/latest)
    - [x] 串流工具 `Moonlight` [From Here](https://github.com/XITRIX/Moonlight-Switch/releases/latest)
    - [x] 文件管理 `NX-Shell` [From Here](https://github.com/zdm65477730/NX-Shell/releases/latest)
    - [x] 黑商店 `hb-appstore`  [From Here](https://github.com/fortheusers/hb-appstore/releases/latest)
    - [x] 系統升級工具 `daybreak`  [From Here](https://www.tekqart.com/thread-258184-1-1.html)

  - 補丁
    - [x] 主題破解 `theme-patches` [From Here](https://github.com/exelix11/theme-patches)
  - Ultrahand
    - [x] 加載器 `nx-ovlloader` [From Here](https://github.com/zdm65477730/nx-ovlloader/releases/latest)
    - [x] 菜單 `Ultrahand-Overlay` [From Here](https://github.com/zdm65477730/Ultrahand-Overlay/releases/latest)
  - Ovl插件
    - [x] 金手指工具 `EdiZon` [From Here](https://github.com/zdm65477730/EdiZon-Overlay/releases/latest)
    - [x] 系統模塊 `ovl-sysmodules` [From Here](https://github.com/zdm65477730/ovl-sysmodules/releases/latest)
    - [x] 系統監視 `StatusMonitor` [From Here](https://github.com/zdm65477730/Status-Monitor-Overlay/releases/latest)
    - [x] 掌機底座模式切換 `ReverseNX-RT` [From Here](https://github.com/zdm65477730/ReverseNX-RT/releases/latest)
    - [x] 局域網聯機 `ldn_mitm` [From Here](https://github.com/zdm65477730/ldn_mitm/releases/latest)
    - [x] 虛擬Amiibo `emuiibo` [From Here](https://github.com/zdm65477730/emuiibo/releases/latest)
    - [x] 時間同步 `QuickNTP` [From Here](https://github.com/zdm65477730/QuickNTP/releases/latest)
    - [x] 色彩調整 `Fizeau` [From Here](https://github.com/zdm65477730/Fizeau/releases/latest)
    - [x] 金手指工具 `Zing` [From Here](https://www.tekqart.com/thread-222735-1-1.html)
    - [x] 後台音樂 `sys-tune` [From Here](https://github.com/HookedBehemoth/sys-tune/releases/latest)
    - [x] 系統補丁 `sys-patch` [From Here](https://github.com/zdm65477730/sys-patch/releases/latest)
    - [x] 超頻插件 `sys-clk` [From Here](https://github.com/zdm65477730/sys-clk/releases/latest)
    - [x] 調頻插件 `OC Toolkit` [From Here](https://github.com/halop/OC_Toolkit_SC_EOS/releases/latest)

  - 其他
    - [x] 藍牙手柄插件 `MissionControl` [From Here](https://github.com/ndeadly/MissionControl/releases/latest)

- 文件操作：
    - [x] 移動 `fusee.bin` 至 `bootloader/payloads` 文件夾
    - [x] 將 `hekate_ctcaer_*.bin` 重命名為 `payload.bin`
    - [x] 在 `bootloader` 文件夾中創建 `hekate_ipl.ini`
    - [x] 在根目錄中創建 `exosphere.ini`
    - [x] 在 `atmosphere/hosts` 文件夾中創建 `emummc.txt` 和 `sysmmc.txt`
    - [x] 在根目錄中創建 `boot.ini`
    - [x] 在 `atmosphere/config` 文件夾中創建 `override_config.ini`
    - [x] 在 `atmosphere/config` 文件夾中創建 `system_settings.ini`
    - [x] 刪除 `switch` 文件夾中 `haze.nro`
    - [x] 刪除 `switch` 文件夾中 `daybreak.nro`
    - [x] 刪除 `switch` 文件夾中 `reboot_to_payload.nro`

## 使用說明（僅適用於 `Linux` ，科學上網環境）:
  - 安裝 `jq` 工具
  - 運行腳本（switchScript.sh）

## 更新日志
- 2025-10-06 更新 `system_settings.ini`
- 2025-05-27 精簡代碼，修正由於 `API` 限制而造成的運行錯誤
- 2025-05-23 批量更新插件地址
- 2025-05-12 更新 `Lockpick_RCM` 倉庫地址
- 2025-05-11 更新 `hekate_ipl.ini`
- 2024-12-11 更新 `Lockpick_RCM` 倉庫地址，降級 `DBI` 至版本658
- 2024-10-29 更新腳本，修正 `sys-patch` 文件更新造成的運行錯誤
- 2024-10-11 更新腳本，修正 `Lockpick_RCM` 倉庫失效造成的運行錯誤
- 2024-08-26 更新腳本，修正 `OC Toolkit` 更新造成的運行錯誤
- 2024-07-21 添加 `sys-clk`、`OC Toolkit`
- 2024-07-16 更新腳本，替換 `Tesla-Menu` 為 `Ultrahand-Overlay`，去除 `sys-clk`
- 2024-07-06 更新 `daybreak` 為漢化版
- 2024-06-29 添加 `hb-appstore`
- 2024-06-22 添加 `SigPatches`、`MissionControl`
- 2024-06-20 更新 `hekate_ipl.ini` 修正啟動時 `nosigchk` 報錯；集成 `NX-Shell`
- 2024-06-16 更新 `Hekate + Nyx`、`sys-patch` 倉庫鏈接，去除 `SigPatches`
- 2024-05-25 更新 `sys-patch`，集成`Moonlight`
- 2024-05-15 更新 `SigPatches`，修正部分遊戲運行錯誤的情況
- 2024-04-12 更新腳本，修正插件源更新造成的運行錯誤，增強腳本的穩定性
- 2024-01-30 添加 `Switchfin` 插件
- 2024-01-27 添加 `Hekate` 漢化，刪除4個 `Nro` 插件
- 2024-01-25 更新 `Tesla` 倉庫鏈接
- 2024-01-24 添加 `sys-tune` 插件
- 2024-01-19 添加 `aio-switch-updater`、`wiliwili`、`SimpleModDownloader` 插件
- 2024-01-09 更新 `Tesla` 倉庫鏈接
- 2023-12-15 更新 `Lockpick_RCM` 倉庫鏈接
- 2023-12-04 刪除 `Safe_Reboot_Shutdown.nro` 插件，添加3個 `Ovl` 插件
- 2023-12-03 添加 `Atmosphere-OC-Suite` 插件
- 2023-11-25 添加 `SwitchTime` 插件
- 2023-11-09 更新 `Lockpick_RCM` 倉庫鏈接
- 2023-10-13 更新腳本，修正 `SigPatches` 鏈接更新造成的運行錯誤；新增2個 `Nro` 插件
- 2023-05-11 更新腳本，修正 `Lockpick_RCM` 倉庫失效造成的運行錯誤；每天16點定時生成整合包
- 2023-05-04 更新腳本
- 2023-04-28 更新腳本，自動生成 Release 內容
- 2023-04-27 添加 Github Action 自動打包代碼

## 截圖
![](https://raw.githubusercontent.com/huangqian8/SwitchPlugins/main/screenshot/screenshot.png)
