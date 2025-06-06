**产品介绍文档（PID）草稿：实用型语音生活助手机器人**

---

### 一、产品名称（暂定）

Kubi：你的桌面语音生活助理机器人

---

### 二、产品核心目标与价值主张

Kubi 致力于成为一款 "真正能协助你过生活" 的桌面语音机器人。它不是单纯的情感陪伴型玩具，而是专为提升生活效率所打造的 **实用型智能终端**。Kubi 能够以语音完成提醒、日程整合、IoT 控制、天气播报、知识问答等任务，减少使用者依赖手机 app，提高生活便利性。

核心价值：

* 减轻使用者的记忆负担
* 取代被动的语音音箱，用 "主动协助 + 知识反馈" 改变生活方式
* 聚焦 "语音就能完成" 的零摩擦用户体验

---

### 三、目标市场与用户画像

本产品适用于以下三类主要用户群体：

1. **独居上班族**：需要语音助手协助日程管理、闹钟、天气提醒与家庭 IoT 控制。
2. **有小孩的家庭**：家长可透过机器人协助孩子生活习惯建立、定时提醒、简单问答辅助学习。
3. **居家办公工作者**：支持专注工作场景下的提醒推送、语音查询日程、控制环境灯光/空调等。

用户共通特征：对隐私不是特别敏感，偏好云端智能、效率优先、乐于使用语音交互者。

---

### 四、市场机会与竞争分析

现今陪伴型桌面机器人市场（如 EMO、Loona）偏重于情感互动、萌态与感官娱乐，但用户常批评 "功能薄弱、没有用"。

而主流智能音箱（如 Google Nest, Alexa）虽具语音能力，但缺乏实体存在感、主动性弱、任务记忆差，难以承担生活协助角色。

Kubi 的差异化在于：

* **以桌面型实体机器人形式存在**，增强陪伴感与“随侍在侧”的体验。
* **专注实用性与主动服务**，不走表演型娱乐路线。
* **全语音操作 + 云端 AI 能力**，真正做到 "能做事" 而非 "能卖萌"。

---

### 五、核心功能（高层说明）

| 功能分类   | 描述                                          |
| ------ | ------------------------------------------- |
| 语音唤醒   | 支持语音热词启动，如“嘿 Kubi”                          |
| 日程提醒   | 可设定、播报提醒事项，例如“下午三点提醒我开会”                    |
| 天气播报   | 主动或查询式播报天气、空气质量等                            |
| IoT 控制 | 语音控制家中智能设备（透过 Home Assistant、Matter、MQTT 等） |
| 知识问答   | 用户可随时提问任何知识性问题（由 GPT-4o 等 AI 模型生成回答）        |
| 日程整合   | 透过授权访问 Google / Apple 日历，播报今日行程             |
| 语音记事   | 即时语音记录代办、备忘（自动转为提醒或日志）                      |
| OTA 更新 | 云端推送更新功能与模型                                 |

---

### 六、技术架构简述（非详规）

* **硬件形态**：固定式桌面设备，无需轮子或移动装置。
* **收音系统**：MEMS 麦克风阵列（支持 2～4 颗），远场识别能力（3～5 公尺）
* **主控建议**：Raspberry Pi CM4 / ESP32-S3（如仅部分边缘运算）/ RK3308
* **网络通信**：Wi-Fi、BLE，支持家庭 IoT 整合
* **语音系统**：

  * 识别：Whisper、Google STT
  * 回答：GPT-4 API（云端）
  * 合成：Google TTS / ElevenLabs

---

### 七、产品策略定位

| 对象                      | 差异点                       |
| ----------------------- | ------------------------- |
| EMO / Loona             | Kubi 不强调情绪、表情、社交互动，功能实用为本 |
| Alexa / Google Nest     | Kubi 有实体形象、主动服务设计、跨平台能力更强 |
| Home Assistant Voice PE | Kubi 为消费型量产设备，不需用户深度 DIY  |
