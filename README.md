# 沈士隆 (Slaung)

- 生日：2000/04/12
- 學歷：[國立勤益科技大學/資訊工程系碩士班](https://csie.ncut.edu.tw/)
- 信箱：r7753pro25@gmail.com
- 地點：台中市
- 熟悉技能：FPGA, Vivado, Vitis, Verilog, ROS, MAVROS, Mavlink, Ardupilot, PX4, Gazebo, rospy, TensorFlow, Keras, neuralnetwork, deeplearning, darknet, YOLO, python, java, C, C++, C#

## 自傳
- todo...
- todo...

## 專業技能
1. 熟悉 Vivado 開發技能
- **Verilog 演算法設計與優化：** 使用 Verilog 設計演算法並封裝為 IP，透過Pipelining、Parallelism、Loop unrolling 提升電路計算效能。
- **模擬與驗證：** 使用 Simulation 進行邏輯驗證、時序模擬與邊界條件測試，確保設計的功能和其性能。
- **AXI 介面設計：** 設計 AXI 介面，將演算法 IP 整合進 PL 端，實現 PS 與 PL 之間的數據通信。
- **Block Design：** 使用 Block Design 完成數據流和控制信號設計，實現硬體系統的整合。
- **綜合與實現：** 進行 Synthesis 和 Implementation，確保設計滿足時序約束和資源使用要求。
- **生成與配置 Bitstream：** 生成 Bitstream 並配置到 FPGA 開發板，完成硬體功能部署。

2. 熟悉 Vitis 開發技能
- **軟硬體協同開發：** 熟悉 Vitis Unified Software Platform ，在FPGA上進行軟硬協同開發。
- **Bitstream 燒錄：** 使用 Vitis 工具將生成的 Bitstream 燒錄至 FPGA 平台，並進行後續系統調試。
- **C++ 驗證與優化：** 撰寫 C++ 程式，以控制 PL 端的數據輸入輸出，進行系統驗證和性能優化。
- **資源使用與性能優化：** 根據資源使用情況調整硬體設計，優化 DSP、LUT、BRAM 等資源分配，提升計算效率與吞吐量。

3. 熟悉 ROS 機器人開發作業系統
- **ROS 基本框架與架構：** 熟悉 ROS 核心概念，包括Node、Master、Topic、Service、Action、Publish和Subscribe。
- **ROS 環境設置與Package管理：** 使用 ROS 的環境設置、工作空間管理和 catkin 工具進行Package建置與依賴管理。
- **機器人模擬與測試：** 使用 Gazebo、RViz 等工具進行機器人模擬和視覺化，進行感測器數據測試和模擬導航與控制。
- **感測器與硬件整合：** 整合各種感測器 (如 Camera, GPS, IMU等) 和控制器，並使用 ROS 驅動程序進行數據獲取與處理。
- **ROS 訊息與服務通信：** 設計自定義消息格式，熟悉 ROS 的話題通訊機制，能夠設計複雜的機器人訊息與指令傳遞結構。

4. 無人機自動控制與自動駕駛平台開發
- **無人機運動控制與導航：** 透過 rospy 撰寫控制程式，實現無人機的自動化控制與導航，整合 ArduPilot 與 ROS 進行飛行模式切換、導航點規劃及自動起降等功能。
- **PX4 / ArduPilot 自動駕駛系統平台：** 熟悉 PX4 和 ArduPilot 架構，能夠進行飛行控制器的設置與無人機系統整合，支持多種飛行模式與控制協定 (如 MAVLink)。
- **自動化飛行任務規劃：** 基於 ROS 和 PX4 / ArduPilot，實現自動化飛行任務，包含導航、資料收集、追蹤與降落，並進行即時監控和數據記錄。
- **感測器數據整合與優化：** 整合無人機上的多種感測器 (如 Camera, GPS, IMU)，用於環境感測、飛行路徑調整及運動控制優化。
- **熟悉 GCS (Ground Control Station)：** 熟悉地面控制站工具 (如 QGroundControl, Mission Planner)，進行無人機的飛行監控、數據管理和遠程任務控制。
- **自定義應用與開發：** 根據任務需求，定制開發無人機控制應用，編寫自定義飛行任務腳本或控制演算法，提升無人機的自動化與智能化。

5. 邊緣運算器與無人機控制整合
- **Nvidia Orin NX 邊緣運算器與 APM 飛控板整合：** 實現邊緣運算器 (Nvidia Orin NX) 與 APM 飛控板的系統整合，完成無人機自動控制。
- **ROS、MAVROS 與 MAVLink 通訊整合：** 透過 ROS、MAVROS 和 MAVLink 建立邊緣運算器、飛控系統與地面控制站之間的即時通信。
- **即時目標檢測與 GPU 加速：** 在邊緣運算器上實現 YOLO-tiny 算法，使用 GPU 加速技術達到即時目標檢測，確保自動追蹤精確性與效率。
- **ArUco Marker 檢測與導航：** 使用 ArUco marker 檢測技術，進行小型標記物檢測，實現精確的無人機降落定位。
- **自定義無人機控制演算法開發：** 編寫自定義的無人機控制程式，在 Nvidia Orin NX 上運行，以實現自動目標追蹤與自動降落任務。
- **邊緣運算系統優化與應用：** 針對無人機自動控制應用，優化邊緣運算器性能(GPU加速推論、控制算法優化、CUDA優化等)，實現即時處理和低延遲反應，提升無人機任務執行效率。

6. 熟悉 神經網路與深度學習開發
- **使用 TensorFlow 和 Keras 進行神經網路開發：** 熟練使用 TensorFlow 與 Keras 構建神經網路模型，應用於回歸與分類問題。
- **多種網路架構實現：** 開發 NN（神經網路）、CNN（卷積神經網路）、FNN（模糊神經網路）等不同網路架構，解決多樣的任務需求。
- **資料預處理：** 熟悉資料預處理、標準化、正則化、資料增強等技術，提升模型準確性。
- **模型參數設置：** 參數調整（如learning、batch size等），進行超參數優化，提升模型收斂速度與性能。
- **訓練與推論：** 進行數據集上的模型訓練，並使用訓練好的模型進行推理，產出預測結果。
- **評估指標：** 使用交叉熵、均方誤差、準確度、F1 score、AUC﹐MAPE、RMSE 等多種評估指標來評估模型表現。
- **優化模型參數演算法：** 使用不同演算法調整模型超參數(如Bayesian Optimization)，以達到最佳或最合適的超參數解。

7. 熟悉 YOLO目標偵測之開發環境

8. 熟悉 C# 應用開發
- 前後端整合開發：設計並開發使用者介面，實現後端資料處理與傳輸。
- Socket網絡通信：使用 C# 開發 Socket 通信功能，實現多系統之間的信息傳遞。
- 多執行緒程式設計：使用 Threads 技術實現應用程式的並行處理，提升系統性能。
- 資料庫操作：與資料庫進行連線、資料存取與查詢。

9. 工業自動化系統開發
- 開發工業機台狀態檢測程式，整合 DIO 模組與氣壓缸模組進行狀態監控。
- 實作異常檢測與警報功能，設計狀態顯示欄位，協助用戶監控設備運行狀態。

10. 語音識別與語音機器人整合
- Python 語音機器人開發：整合語音識別技術與 C# 系統，實現與用戶的自動對話流程。
- 結巴斷詞技術應用：使用規則和斷詞技術處理語音內容，獲取報案表單的關鍵資訊。

11. 系統架構設計與實現
- 開發基於 C# 的語音報案系統，整合 Server 端、接線員端與消防局端功能，實現信息流的完整閉環。
- 設計系統任務自動派遣與回報機制，確保消防局快速收到報案信息並做出應對。
- 使用多執行緒與同步機制優化資料傳遞與派車動作，提升系統效能與穩定性。

## 證照
- todo..
- todo..
- todo..

## 作品集
1. Convoultion fuzzy neural network for blood predictor implements FPGA
2. UAV tracking and land controller
3. UAV autonomous navigation

## 碩士論文 2024/07
- 論文題目：基於視覺偵測之模糊PID控制系統於無人機自主追蹤與降落任務(Vision-based Fuzzy PID Control Systems for Tracking and Landing of Autonomous UAV)
- 論文連結：[https://hdl.handle.net/11296/2596r4](https://hdl.handle.net/11296/2596r4)
- DM影片連結：[https://youtu.be/zwSrO8xwgmo](https://youtu.be/zwSrO8xwgmo)
