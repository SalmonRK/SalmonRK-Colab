แจ้งบัค พูดคุย แลกเปลี่ยนความรู้กันได้ในกลุ่ม
AI Image Channel
https://discord.gg/aith 

# :: SalmonRK Colab V07.1 :: Updated 5 July 2023
A1111 V.1.3.2 แก้ปัญหา Gradio ไม่ทำงาน
เพิ่ม Controlnet Model : QR CODE
- เพิ่มตัวเลือก VAE, Clip stop  
- เซฟภาพที่เจนเข้า output ใน google drive

แก้ปัญหา แจ้งเตือน เมื่อใช้งาน SD webui
เพิ่ม extension ที่ใช้งานได้
:: Extension ที่ใช้ได้ 
- controlnet 1.1
- openpose-editor
- posex 
- lycoris
- ABG_extension
- sd-dynamic-thresholding
- canvas-zoom 
- sd-dynamic-prompts
- ultimate-upscale-for-automatic1111
- adetailer
เพิ่ม
- tagcomplete
- aspect-ratio-helper 
- wd14-tagger
- Segment Anything

# การใช้งาน
![](/image/001.png)
- เลือกที่ไฟล์ SalmonRK_SD_Webui_Colab.ipynb
- กดที่ Open in Colab


# การทำงานจะมี 4 ส่วน
1. Install A1111 (Setup) กดในช่องสีแดง เพื่อ Run cell เมื่อติดตั้งเรียบร้อย เซลนี้จะดับเอง (อาจจะมีการขอสิทธ์เพื่อเข้าถึง Google drive)
2. อันนี้อธิบายในข้อ1
3. สำหรับ Import Model,Lora,embedding ส่วนตัว จาก Google drive 
    (ถ้าโหลดจาก Civitai หรือ hugginface ทำใน option1 จะไวกว่า)
4. Launch the web ui สำหรับ เปิดโปรแกรม Cell นี้จะทำงานตลอด ไม่ปิดเอง รอระบบทำงานจนปรากฏ Link 
  กดที่ Link เพื่อเข้าใช้งาน 
  
# Option 1 
    สำหรับ Download Model, Lora จาก Civitai หรือ Huggingface
    คลิกขวา ที่ ปุ่มดาวน์โหลดโมเดลหรือ lora คัดลอก แล้วมาวาง ในช่อง URL
    การตั้งชื่อต้องมี นามสกุลด้วยเช่น  .safetensors หรือ .ckpt
# Option 2 
    สำหรับ คัดลอก ผลงานที่เรา Generate ไว้ ใน colab กลับไปเก็บไว้ยัง Google drive

