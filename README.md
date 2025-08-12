
This is a MetaTrader 5 (MT5) script written in MQL5 that sends Telegram notifications when an order is opened or closed. It's perfect for traders who want instant updates on their order activities directly to their Telegram app.

### ✅ Features
- Sends order notifications (e.g. order open/close) via Telegram
- Easy setup with bot token and chat ID
- Works with MetaTrader 5

### 📦 Requirements
- MetaTrader 5 platform
- Telegram account and bot token
- Your Telegram chat ID

### ⚙️ How to Use

1. **Create a Telegram Bot**
   - Search for `@BotFather` in Telegram and create a new bot
   - Save your token

2. **Get your Chat ID**
   - Send any message to your bot
   - Open this URL (replace YOUR_BOT_TOKEN):
     ```
     https://api.telegram.org/botYOUR_BOT_TOKEN/getUpdates
     ```
   - Copy your chat ID from the response

3. **Edit the Script**
   - Open `Order notification.mq5` in MetaEditor
   - Modify the following lines:
     ```mql5
     string TOKEN = "YOUR_BOT_TOKEN";
     string CHAT_ID = "YOUR_CHAT_ID";
     ```

4. **Compile & Attach the Script**
   - Compile the `.mq5` file in MetaEditor
   - Attach it to any chart in MetaTrader 5

5. **Done!**
   - You will receive Telegram messages when orders are opened or closed.

---



สคริปต์นี้เป็น MQL5 สำหรับ MetaTrader 5 เพื่อแจ้งเตือนกิจกรรมการเปิดหรือปิดออเดอร์ผ่าน Telegram เหมาะสำหรับเทรดเดอร์ที่ต้องการทราบความเคลื่อนไหวของออเดอร์ทันที

### ✅ จุดเด่น
- แจ้งเตือนเมื่อมีการเปิด/ปิดออเดอร์
- ตั้งค่าได้ง่าย เพียงใส่ token และ chat ID ของ Telegram
- ใช้ได้กับ MetaTrader 5

### 📦 ความต้องการ
- โปรแกรม MetaTrader 5
- บัญชี Telegram และ bot token
- รหัส chat ID ของคุณใน Telegram

### ⚙️ วิธีใช้งาน

1. **สร้าง Telegram Bot**
   - ค้นหา `@BotFather` ใน Telegram แล้วสร้างบอทใหม่
   - คัดลอก token ที่ได้มาเก็บไว้

2. **หาค่า Chat ID**
   - ส่งข้อความใดๆ ไปยังบอทที่สร้าง
   - เปิดลิงก์นี้ (แทนที่ YOUR_BOT_TOKEN):
     ```
     https://api.telegram.org/botYOUR_BOT_TOKEN/getUpdates
     ```
   - ดู chat ID จากผลลัพธ์ที่ได้

3. **แก้ไข Script**
   - เปิด `Order notification.mq5` ด้วย MetaEditor
   - แก้ไขบรรทัดนี้:
     ```mql5
     string TOKEN = "YOUR_BOT_TOKEN";
     string CHAT_ID = "YOUR_CHAT_ID";
     ```

4. **คอมไพล์และเปิดใช้งาน**
   - คอมไพล์ไฟล์ `.mq5`
   - แนบสคริปต์เข้ากับกราฟใดก็ได้ใน MetaTrader 5

5. **เรียบร้อย!**
   - Telegram ของคุณจะได้รับการแจ้งเตือนเมื่อมีการเปิดหรือปิดออเดอร์

---

## 👤 ผู้พัฒนา

- เตเต้
- Telegram: https://t.me/@shibainuu90


