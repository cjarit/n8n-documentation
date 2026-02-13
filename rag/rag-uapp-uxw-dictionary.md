# UX Writing Dictionary & Lexicon for RAG

This document contains a structured lexicon and dictionary for UX Writing, optimized for Retrieval Augmented Generation (RAG).

## Categories

### tone_phrase
- **polite_request**
  - **Thai Preferred**: กรุณา…
  - **English Label**: polite ask
  - **Description**: คำขอแบบสุภาพ ใช้เมื่อจำเป็น โดยไม่ต้องใส่ทุกประโยค
  - **Example TH**: กรุณาตรวจสอบข้อมูลอีกครั้ง
  - **Avoid**: คุณต้อง… / โปรด… (ทางการกว่า)
  - **Notes**: ใช้พอดีเพื่อไม่ให้ดูแข็งหรือเยอะเกิน

- **try_again**
  - **Thai Preferred**: ลองใหม่
  - **English Label**: retry
  - **Description**: ใช้เมื่อผู้ใช้ทำได้ทันที
  - **Example TH**: ลองใหม่อีกครั้ง
  - **Avoid**: ตกลง (เมื่อควรเป็น action)
  - **CTA Primary**: ลองใหม่
  - **CTA Secondary**: ปิด
  - **Notes**: ถ้าไม่มี retry จริง ใช้ “ปิด” และบอกให้ลองภายหลังในข้อความ

- **try_later**
  - **Thai Preferred**: โปรดลองอีกครั้งภายหลัง
  - **English Label**: try later
  - **Description**: ใช้เมื่อระบบไม่พร้อม/ต้องรอเวลา
  - **Example TH**: โปรดลองอีกครั้งภายหลัง
  - **Avoid**: ไม่สามารถ… (จบไม่มีทางออก)
  - **CTA Primary**: ปิด
  - **Notes**: ควรมีสาเหตุเท่าที่รู้ + next step

- **apology_system**
  - **Thai Preferred**: ขออภัย
  - **English Label**: apology
  - **Description**: ใช้เมื่อเป็นความผิดพลาดจากระบบ/บริการ
  - **Example TH**: ขออภัย ระบบขัดข้องชั่วคราว
  - **Avoid**: ขออภัย (พร่ำเพรื่อในทุกกรณี)
  - **Notes**: หลีกเลี่ยงการขอโทษเมื่อเป็น user mistake

---

### cta
- **view_details**
  - **Thai Preferred**: ดูรายละเอียด
  - **English Label**: view details
  - **Description**: เปิดดูข้อมูลเพิ่มเติม/สรุป
  - **Example TH**: ดูรายละเอียดการชำระเงิน
  - **CTA Primary**: ดูรายละเอียด
  - **CTA Secondary**: ปิด

- **view_more**
  - **Thai Preferred**: ดูเพิ่มเติม
  - **English Label**: view more
  - **Description**: ขยายข้อมูล/รายการ
  - **Example TH**: ดูเพิ่มเติม
  - **CTA Primary**: ดูเพิ่มเติม
  - **CTA Secondary**: ปิด

- **continue**
  - **Thai Preferred**: ไปต่อ
  - **English Label**: continue
  - **Description**: ดำเนินขั้นตอนถัดไป
  - **Example TH**: ไปต่อ
  - **CTA Primary**: ไปต่อ
  - **CTA Secondary**: ย้อนกลับ

- **back**
  - **Thai Preferred**: ย้อนกลับ
  - **English Label**: back
  - **Description**: กลับหน้าก่อนหน้า
  - **Example TH**: ย้อนกลับ
  - **CTA Primary**: ย้อนกลับ

- **close**
  - **Thai Preferred**: ปิด
  - **English Label**: close
  - **Description**: ปิด modal/dialog
  - **Example TH**: ปิด
  - **Avoid**: ตกลง (ถ้าไม่ชัดว่าปิด)
  - **CTA Primary**: ปิด

- **confirm**
  - **Thai Preferred**: ยืนยัน
  - **English Label**: confirm
  - **Description**: ยืนยันการทำรายการ/การเลือก
  - **Example TH**: ยืนยันข้อมูล
  - **Avoid**: ตกลง
  - **CTA Primary**: ยืนยัน
  - **CTA Secondary**: แก้ไข
  - **Notes**: ถ้าเป็นธุรกรรม ให้ใช้คำเฉพาะเจาะจง เช่น “ยืนยันชำระเงิน”

- **cancel**
  - **Thai Preferred**: ยกเลิก
  - **English Label**: cancel
  - **Description**: ยกเลิกการทำรายการ
  - **Example TH**: ยกเลิก
  - **CTA Primary**: ยกเลิก
  - **CTA Secondary**: ทำต่อ

- **edit**
  - **Thai Preferred**: แก้ไข
  - **English Label**: edit
  - **Description**: แก้ไขข้อมูล/รายการ
  - **Example TH**: แก้ไขข้อมูล
  - **CTA Primary**: แก้ไข
  - **CTA Secondary**: ยกเลิก

- **save**
  - **Thai Preferred**: บันทึก
  - **English Label**: save
  - **Description**: บันทึกข้อมูล/การตั้งค่า
  - **Example TH**: บันทึก
  - **CTA Primary**: บันทึก
  - **CTA Secondary**: ยกเลิก

- **delete**
  - **Thai Preferred**: ลบ
  - **English Label**: delete
  - **Description**: ลบข้อมูล/รายการ (ควรมี confirm)
  - **Example TH**: ลบรายการนี้
  - **CTA Primary**: ลบ
  - **CTA Secondary**: ยกเลิก
  - **Notes**: ควรมี warning ก่อนลบ

- **retry**
  - **Thai Preferred**: ลองใหม่
  - **English Label**: retry
  - **Description**: ทำซ้ำ action เดิม
  - **Example TH**: ลองใหม่
  - **CTA Primary**: ลองใหม่
  - **CTA Secondary**: ปิด

- **restart**
  - **Thai Preferred**: เริ่มใหม่
  - **English Label**: restart
  - **Description**: เริ่ม flow ใหม่หลัง timeout/ผิดพลาด
  - **Example TH**: เริ่มใหม่
  - **CTA Primary**: เริ่มใหม่
  - **CTA Secondary**: ปิด

- **go_settings**
  - **Thai Preferred**: ไปที่ตั้งค่า
  - **English Label**: go to settings
  - **Description**: พาไปตั้งค่าระบบ เช่น Location/Notification
  - **Example TH**: ไปที่ตั้งค่า
  - **CTA Primary**: ไปที่ตั้งค่า
  - **CTA Secondary**: ไม่ตอนนี้

- **update_now**
  - **Thai Preferred**: อัปเดตตอนนี้
  - **English Label**: update now
  - **Description**: อัปเดตเวอร์ชันแอป
  - **Example TH**: อัปเดตตอนนี้
  - **CTA Primary**: อัปเดตตอนนี้
  - **CTA Secondary**: ไว้ก่อน

- **later**
  - **Thai Preferred**: ไว้ก่อน
  - **English Label**: later
  - **Description**: เลื่อนการทำ action
  - **Example TH**: ไว้ก่อน
  - **Avoid**: ทำภายหลัง (ใช้ได้เช่นกัน)
  - **CTA Primary**: ไว้ก่อน

- **copy**
  - **Thai Preferred**: คัดลอก
  - **English Label**: copy
  - **Description**: คัดลอกข้อความ/เลขอ้างอิง
  - **Example TH**: คัดลอกเลขอ้างอิง
  - **CTA Primary**: คัดลอก
  - **CTA Secondary**: ปิด

- **share**
  - **Thai Preferred**: แชร์
  - **English Label**: share
  - **Description**: แชร์ข้อมูล/หลักฐาน
  - **Example TH**: แชร์สลิป
  - **CTA Primary**: แชร์
  - **CTA Secondary**: ปิด

---

### error_template
- **structure_3part**
  - **English Label**: what+why+next
  - **Description**: โครงสร้างข้อความผิดพลาดมาตรฐาน
  - **Example TH**: เกิดอะไรขึ้น + (สาเหตุถ้ารู้) + ทำอะไรต่อ
  - **Notes**: อย่าคาดเดาสาเหตุถ้าไม่ชัวร์

- **network**
  - **Thai Preferred**: ไม่มีการเชื่อมต่ออินเทอร์เน็ต กรุณาตรวจสอบแล้วลองใหม่อีกครั้ง
  - **English Label**: network error
  - **Description**: กรณีไม่มีอินเทอร์เน็ต/สัญญาณ
  - **Example TH**: ไม่มีการเชื่อมต่ออินเทอร์เน็ต กรุณาตรวจสอบแล้วลองใหม่อีกครั้ง
  - **Avoid**: ไม่พบสัญญาณอินเทอร์เน็ต (ใช้ได้แต่ควรมี next step)
  - **CTA Primary**: ลองใหม่
  - **CTA Secondary**: ปิด

- **timeout**
  - **Thai Preferred**: หมดเวลาทำรายการ กรุณาเริ่มใหม่อีกครั้ง
  - **English Label**: timeout
  - **Description**: กรณีการทำรายการใช้เวลานานเกินกำหนด
  - **Example TH**: หมดเวลาทำรายการ กรุณาเริ่มใหม่อีกครั้ง
  - **Avoid**: ทำรายการเกินเวลาที่กำหนด (ควรปรับให้เป็นภาษาคน)
  - **CTA Primary**: เริ่มใหม่
  - **CTA Secondary**: ปิด

- **system_generic**
  - **Thai Preferred**: ทำรายการไม่สำเร็จในตอนนี้ กรุณาลองใหม่อีกครั้ง
  - **English Label**: system error
  - **Description**: กรณีระบบไม่สามารถดำเนินการได้ชั่วคราว
  - **Example TH**: ทำรายการไม่สำเร็จในตอนนี้ กรุณาลองใหม่อีกครั้ง
  - **Avoid**: ไม่สามารถทำรายการได้ในขณะนี้ (ใช้ได้ แต่ควรเติม next step)
  - **CTA Primary**: ลองใหม่
  - **CTA Secondary**: ปิด

- **with_reference_code**
  - **Thai Preferred**: รหัสอ้างอิง: [Error code]
  - **English Label**: reference code
  - **Description**: ใช้แสดงรหัสเพื่อการช่วยเหลือ/ติดตาม
  - **Example TH**: รหัสอ้างอิง: 12345
  - **Avoid**: [Error code] (ไม่บอกความหมาย)
  - **Notes**: ใส่ในบรรทัดแยกเพื่ออ่านง่าย

---

### validation_template
- **required_field**
  - **Thai Preferred**: กรุณากรอกข้อมูลให้ครบ
  - **English Label**: required
  - **Description**: เมื่อช่องบังคับว่าง
  - **Example TH**: กรุณากรอกข้อมูลให้ครบ
  - **Avoid**: ข้อมูลไม่ถูกต้อง
  - **Notes**: ถ้าระบุได้ ให้ชี้จุด: “กรุณากรอกอีเมล”

- **invalid_format**
  - **Thai Preferred**: รูปแบบไม่ถูกต้อง กรุณาตรวจสอบอีกครั้ง
  - **English Label**: invalid format
  - **Description**: เมื่อรูปแบบข้อมูลไม่ตรงแพทเทิร์น
  - **Example TH**: รูปแบบไม่ถูกต้อง กรุณาตรวจสอบอีกครั้ง
  - **Avoid**: คุณทำไม่ถูกต้อง
  - **Notes**: ควรมีตัวอย่างเมื่อเหมาะสม

- **need_selection**
  - **Thai Preferred**: กรุณาเลือก___ก่อน
  - **English Label**: selection required
  - **Description**: เมื่อจำเป็นต้องเลือก item ก่อนทำต่อ
  - **Example TH**: กรุณาเลือกตัวเลือกก่อน
  - **Avoid**: กรุณาทำรายการให้ถูกต้อง
  - **Notes**: เติมคำให้ชัด เช่น “กรุณาเลือกภาคเรียนก่อน”

---

### permission
- **location_reason**
  - **Thai Preferred**: เพื่อแสดงบริการใกล้คุณ กรุณาอนุญาตการเข้าถึงตำแหน่ง
  - **English Label**: location permission
  - **Description**: ขอสิทธิ์ Location พร้อมเหตุผล
  - **Example TH**: เพื่อแสดงบริการใกล้คุณ กรุณาอนุญาตการเข้าถึงตำแหน่ง
  - **Avoid**: กรุณาตั้งค่าให้แอปเข้าถึง Location ของคุณได้
  - **CTA Primary**: ไปที่ตั้งค่า
  - **CTA Secondary**: ไม่ตอนนี้

- **notification_reason**
  - **Thai Preferred**: เปิดแจ้งเตือนเพื่อไม่พลาดประกาศสำคัญ
  - **English Label**: notification permission
  - **Description**: ชวนเปิด notification แบบเป็นมิตร
  - **Example TH**: เปิดแจ้งเตือนเพื่อไม่พลาดประกาศสำคัญ
  - **Avoid**: เปิดแจ้งเตือนเดี๋ยวนี้
  - **CTA Primary**: เปิดแจ้งเตือน
  - **CTA Secondary**: ไม่ตอนนี้

---

### status
- **success**
  - **Thai Preferred**: สำเร็จ
  - **English Label**: success
  - **Description**: สถานะสำเร็จ
  - **Example TH**: ชำระเงินสำเร็จ

- **processing**
  - **Thai Preferred**: กำลังดำเนินการ
  - **English Label**: processing
  - **Description**: สถานะกำลังทำงาน
  - **Example TH**: กำลังดำเนินการ…

- **pending**
  - **Thai Preferred**: รอดำเนินการ
  - **English Label**: pending
  - **Description**: สถานะรอผล/รออนุมัติ
  - **Example TH**: รอดำเนินการ

- **failed**
  - **Thai Preferred**: ไม่สำเร็จ
  - **English Label**: failed
  - **Description**: สถานะไม่สำเร็จ (ควรมี next step ในข้อความหลัก)
  - **Example TH**: ทำรายการไม่สำเร็จ
  - **Avoid**: ล้มเหลว

- **cancelled**
  - **Thai Preferred**: ยกเลิกแล้ว
  - **English Label**: cancelled
  - **Description**: สถานะถูกยกเลิก
  - **Example TH**: ยกเลิกแล้ว

- **start_point**
  - **Thai Preferred**: ต้นทาง
  - **English Label**: origin
  - **Description**: แท็ก/label จุดเริ่มต้น
  - **Example TH**: ต้นทาง

- **end_point**
  - **Thai Preferred**: ปลายทาง
  - **English Label**: destination
  - **Description**: แท็ก/label จุดปลาย
  - **Example TH**: ปลายทาง

- **recommended**
  - **Thai Preferred**: แนะนำ
  - **English Label**: recommended
  - **Description**: ป้ายกำกับรายการแนะนำ (ใช้เมื่อมี logic)
  - **Example TH**: แนะนำ
  - **Notes**: ใช้เมื่อมีเหตุผลรองรับจริง

- **new**
  - **Thai Preferred**: ใหม่
  - **English Label**: new
  - **Description**: ป้ายกำกับของใหม่
  - **Example TH**: ใหม่
  - **Notes**: อย่าใช้พร่ำเพรื่อ

---

### avoid_word
- **ล้มเหลว**
  - **Thai Preferred**: ไม่สำเร็จ
  - **English Label**: failed
  - **Description**: หลีกเลี่ยงคำแรง/ให้ความรู้สึกผิด
  - **Example TH**: ทำรายการไม่สำเร็จ
  - **Avoid**: ล้มเหลว

- **ผิดพลาด**
  - **Thai Preferred**: ไม่สำเร็จ / มีปัญหา
  - **English Label**: error wording
  - **Description**: หลีกเลี่ยงคำที่ทำให้รู้สึกแย่
  - **Example TH**: ทำรายการไม่สำเร็จในตอนนี้
  - **Avoid**: เกิดข้อผิดพลาด

- **คุณทำไม่ถูกต้อง**
  - **Thai Preferred**: รูปแบบไม่ถูกต้อง / กรุณาตรวจสอบ
  - **English Label**: no blame
  - **Description**: ห้ามกล่าวโทษผู้ใช้
  - **Example TH**: รูปแบบไม่ถูกต้อง กรุณาตรวจสอบอีกครั้ง
  - **Avoid**: คุณทำไม่ถูกต้อง

- **ไม่สามารถ…ได้**
  - **Thai Preferred**: ยัง…ไม่ได้ในตอนนี้
  - **English Label**: softer denial
  - **Description**: ลดโทนปฏิเสธแข็ง ๆ
  - **Example TH**: ยังทำรายการนี้ไม่ได้ในตอนนี้
  - **Avoid**: ไม่สามารถทำรายการได้

---

### glossary
- **voice**
  - **Thai Preferred**: Voice
  - **English Label**: brand voice
  - **Description**: บุคลิกคงที่ของแบรนด์ในการสื่อสาร
  - **Example TH**: Voice = บุคลิกโดยรวมของแอป

- **tone**
  - **Thai Preferred**: Tone
  - **English Label**: tone
  - **Description**: ระดับอารมณ์/ท่าทีที่ปรับตามสถานการณ์
  - **Example TH**: Tone เปลี่ยนตาม success/error/warning

- **cta**
  - **Thai Preferred**: CTA
  - **English Label**: call to action
  - **Description**: ข้อความบนปุ่มที่บอก action
  - **Example TH**: CTA: ลองใหม่ / ไปที่ตั้งค่า

- **primary_cta**
  - **Thai Preferred**: ปุ่มหลัก
  - **English Label**: primary CTA
  - **Description**: action ที่แนะนำ/สำคัญที่สุด
  - **Example TH**: ปุ่มหลัก: ชำระเงิน

- **secondary_cta**
  - **Thai Preferred**: ปุ่มรอง
  - **English Label**: secondary CTA
  - **Description**: ทางเลือก/ยกเลิก/ทำภายหลัง
  - **Example TH**: ปุ่มรอง: ยกเลิก / ไว้ก่อน

- **helper_text**
  - **Thai Preferred**: Helper text
  - **English Label**: helper text
  - **Description**: คำอธิบายสั้นใต้ field เพื่อช่วยกรอก
  - **Example TH**: เช่น “กรอกอีเมลสำหรับรับใบเสร็จ”

- **empty_state**
  - **Thai Preferred**: Empty state
  - **English Label**: empty state
  - **Description**: หน้าจอที่ไม่มีข้อมูล แนะนำการเริ่มต้น
  - **Example TH**: ยังไม่มีรายการ ลองเริ่มจาก…

- **field_error**
  - **Thai Preferred**: Field-level error
  - **English Label**: field-level error
  - **Description**: error ใต้ช่องกรอก
  - **Example TH**: รูปแบบไม่ถูกต้อง

- **system_error**
  - **Thai Preferred**: System error
  - **English Label**: system error
  - **Description**: error จากระบบ/เซิร์ฟเวอร์
  - **Example TH**: ทำรายการไม่สำเร็จในตอนนี้

- **non_blame**
  - **Thai Preferred**: Non-blaming
  - **English Label**: non-blaming
  - **Description**: เขียนโดยไม่กล่าวโทษผู้ใช้
  - **Example TH**: กรุณาตรวจสอบข้อมูลอีกครั้ง

- **next_step**
  - **Thai Preferred**: Next step
  - **English Label**: next step
  - **Description**: บอกสิ่งที่ผู้ใช้ทำต่อได้ทันที
  - **Example TH**: ตรวจสอบอินเทอร์เน็ต แล้วลองใหม่

- **active_voice**
  - **Thai Preferred**: Active voice
  - **English Label**: active voice
  - **Description**: ประโยคที่ผู้ใช้เห็น action ชัด
  - **Example TH**: กรุณาตรวจสอบข้อมูล

- **reference_code**
  - **Thai Preferred**: รหัสอ้างอิง
  - **English Label**: reference code
  - **Description**: รหัสสำหรับติดต่อ/ติดตามปัญหา
  - **Example TH**: รหัสอ้างอิง: 12345

- **rag_data**
  - **Thai Preferred**: RAG data
  - **English Label**: retrieval augmented generation
  - **Description**: ข้อมูลที่จัดโครงสร้างเพื่อให้ AI ดึงไปตอบ
  - **Example TH**: ไฟล์นี้ใช้เป็น knowledge base

---

### pattern
- **success_generic**
  - **Thai Preferred**: ดำเนินเรียบร้อยแล้ว
  - **English Label**: success confirmation
  - **Description**: ใช้หลังทำงานสำเร็จทั่วไป
  - **Example TH**: ดำเนินเรียบร้อยแล้ว
  - **CTA Primary**: ดูรายละเอียด
  - **CTA Secondary**: ปิด

- **loading_data**
  - **Thai Preferred**: กำลังโหลดข้อมูล…
  - **English Label**: loading
  - **Description**: ใช้ระหว่างโหลดข้อมูล
  - **Example TH**: กำลังโหลดข้อมูล…

- **processing_wait**
  - **Thai Preferred**: กำลังดำเนินการ กรุณารอสักครู่
  - **English Label**: processing
  - **Description**: ใช้ระหว่างประมวลผล
  - **Example TH**: กำลังดำเนินการ กรุณารอสักครู่

- **empty_start**
  - **Thai Preferred**: ยังไม่มีข้อมูล ลองเริ่มจากการเลือกเมนูด้านบน
  - **English Label**: empty state
  - **Description**: ใช้เมื่อหน้าจอว่างครั้งแรก
  - **Example TH**: ยังไม่มีข้อมูล ลองเริ่มจากการเลือกเมนูด้านบน
  - **CTA Primary**: เริ่มต้น
  - **CTA Secondary**: ปิด

- **warning_check_info**
  - **Thai Preferred**: โปรดตรวจสอบข้อมูลให้ถูกต้องก่อนยืนยัน
  - **English Label**: warning
  - **Description**: เตือนก่อนยืนยันรายการสำคัญ
  - **Example TH**: โปรดตรวจสอบข้อมูลให้ถูกต้องก่อนยืนยัน
  - **CTA Primary**: ยืนยัน
  - **CTA Secondary**: แก้ไข

- **permission_location**
  - **Thai Preferred**: เพื่อแสดงบริการใกล้คุณ กรุณาอนุญาตการเข้าถึงตำแหน่ง
  - **English Label**: permission
  - **Description**: ขอ permission พร้อมเหตุผล
  - **Example TH**: เพื่อแสดงบริการใกล้คุณ กรุณาอนุญาตการเข้าถึงตำแหน่ง
  - **CTA Primary**: ไปที่ตั้งค่า
  - **CTA Secondary**: ไม่ตอนนี้
