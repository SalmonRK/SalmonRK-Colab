<a href="https://www.buymeacoffee.com/salmonrk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

แจ้งบัค พูดคุย แลกเปลี่ยนความรู้กันได้ในกลุ่ม
AI Image Channel
https://discord.gg/aith 

:: Runtime SalmonRK Colab (ใช้พื้นที่ของ Colab ติดตั้งใหม่ทุกครั้งก่อนใช้งาน)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SalmonRK/A1111-Colab/blob/main/SalmonRK_SD_Webui_Colab.ipynb)


:: Google Drive SalmonRK Colab (ติดตั้งครั้งเดียว พื้นที่ G Drive > 80 GB)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SalmonRK/A1111-Colab/blob/main/SalmonRK_SD_Webui_Colab_GDrive_V9.ipynb) 

# :: Updated 11 SEP 2023
- Update SalmonRK_SD_Webui_Colab
  - Base Directory : SD-A1111
- Fixed Bug on Google drive colab file
      
# :: Updated 9 SEP 2023
Update Support Google drive
Centralized SD Model Folder

Model_SD15
      - Model
      - Lora
      - CTN
      - model
      - annotator


# :: Updated 18 Aug 2023
- เพิ่ม Google Drive Colab ติดตั้ง A1111 ครั้งเดียว ควรมีพื้นที่บน Google Drive อย่างน้อย 80 GB
      Colab ใหม่ จะมี การทำงาน 2 ข้อ 1 Option
กล่องที่ 1. สำหรับติดตั้งโปรแกรม SD A1111 v1.5.1, Controlnet และ Extension ที่จำเป็น บน Google drive (ติดตั้งครั้งเดียว โปรแกรมไม่หาย ควรมีพื้นที่ อย่างน้อย 80GB)
- เมื่อติดตั้งเสร็จ กล่องนี้จะหยุดทำงานเอง
กล่องที่2 สำหรับเปิด WebUI เมื่อเสร็จจะมี link สำหรับเข้าใช้งาน SD
- ข้อนี้ต้องทำทุกครั้งเมื่อจะใช้งาน SD WebUI
Option 1 สำหรับ Download Model (checkpoint), Lora หรือ Lycoris เข้าระบบ (ทำข้อนี้แล้วต้อง รีสตาร์ท กล่องที่ 2 )
- หาลิ้ง download ใน civitai โดย คลิ๊กขวาที่ปุ่ม Download -> เลือก Copy Link address แล้วเอามาวางในช่วง model_url หรือ lora_url
อย่าลืมตั้งชื่อ แล้วใส่นามสกุลให้ถูกต้อง .safetensors หรือ .ckpt


![](/image/copy_link.jpg)


# :: SalmonRK Colab V8.1 :: Updated 13 Aug 2023
- A1111 Version 1.5.1
- Controlnet lastest version - Support DW Pose ก้างปลาที่แก้ปัญหามือได้ดีกว่าเดิม
https://github.com/Mikubill/sd-webui-controlnet/discussions/1863


# :: SalmonRK Colab V07.1 :: Updated 5 July 2023
- A1111 V.1.3.2 แก้ปัญหา Gradio ไม่ทำงาน
- เพิ่ม Controlnet Model : QR CODE
- เพิ่มตัวเลือก VAE, Clip stop  
- เซฟภาพที่เจนเข้า output ใน google drive
- เพิ่ม VAE 6 ตัว

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

