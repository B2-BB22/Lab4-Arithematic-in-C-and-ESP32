### แบบฝึกหัดที่ 1: เปลี่ยนจำนวนไข่
```c
// หาบรรทัดนี้ในโค้ด:
int eggs_already_have = 4;    // ไข่ไก่ที่แม่มีอยู่แล้ว
int eggs_new_today = 2;       // ไข่ไก่ที่ไก่ออกวันนี้

// ลองเปลี่ยนเป็น:
int eggs_already_have = 8;    // เพิ่มเป็น 8 ฟอง
int eggs_new_today = 3;       // เพิ่มเป็น 3 ฟอง
```

### Result
```c
I (6540) main_task: Started on CPU0
I (6540) main_task: Calling app_main()
I (6550) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (6550) EGGS_MATH: =====================================
I (6550) EGGS_MATH: 📖 โจทย์:
I (6550) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 8 ฟอง
I (6550) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 3 ฟอง
I (6550) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (6550) EGGS_MATH:
I (9550) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (9550) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (9550) EGGS_MATH:    = 8 + 3
I (9550) EGGS_MATH:    = 11 ฟอง
I (9550) EGGS_MATH:
I (9550) EGGS_MATH: ✅ คำตอบ:
I (9550) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (9550) EGGS_MATH: 
I (9550) EGGS_MATH: 🎨 ภาพประกอบ:
I (9550) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚🥚🥚🥚🥚 (8 ฟอง)
I (9550) EGGS_MATH:    ไข่ใหม่: 🥚🥚🥚 (3 ฟอง)
I (9550) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (9550) EGGS_MATH: 
I (9550) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (9550) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (9550) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (9550) EGGS_MATH:
I (9550) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (9560) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (9560) EGGS_MATH:
I (9560) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (9560) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (9560) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (9560) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (9560) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (9560) EGGS_MATH:
I (9560) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (9560) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (11560) main_task: Returned from app_main()
```

### แบบฝึกหัดที่ 2: เพิ่มไข่เป็ด
```c
int duck_eggs = 3;            // ไข่เป็ดที่แม่มี
int total_all_eggs;           // ไข่ทั้งหมด (ไก่ + เป็ด)
```

### Result
```c
I (5955) spi_flash: detected chip: winbond
I (5965) spi_flash: flash io: dio
I (5978) main_task: Started on CPU0
I (5988) main_task: Calling app_main()
I (5988) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (5988) EGGS_MATH: =====================================
I (5988) EGGS_MATH: 📖 โจทย์:
I (5988) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 8 ฟอง
I (5988) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 3 ฟอง
I (5988) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (5988) EGGS_MATH: 
I (8988) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (8988) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (8988) EGGS_MATH:    = 8 + 3
I (8988) EGGS_MATH:    = 11 ฟอง
I (8988) EGGS_MATH:
I (8988) EGGS_MATH: 🦆 และแม่มีไข่เป็ด: 3 ฟอง
I (8988) EGGS_MATH: 🥚 ไข่ทั้งหมด (ไก่+เป็ด): 14 ฟอง
I (8988) EGGS_MATH: ✅ คำตอบ:
I (8988) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (8988) EGGS_MATH:    ไข่รวมทั้งหมด (ไก่ + เป็ด) คือ 14 ฟอง
I (8988) EGGS_MATH:
I (8988) EGGS_MATH: 🎨 ภาพประกอบ:
I (8988) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚🥚🥚🥚🥚 (8 ฟอง)
I (8988) EGGS_MATH:    ไข่ใหม่: 🥚🥚🥚 (3 ฟอง)
I (8988) EGGS_MATH:    รวมไก่: 🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (8988) EGGS_MATH:    ไข่เป็ด: 🥚🥚🥚 (3 ฟอง)
I (8988) EGGS_MATH:    รวมทั้งหมด: 🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚🥚 (14 ฟอง)
I (8988) EGGS_MATH:
I (8988) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (8988) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (8988) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (8988) EGGS_MATH: 
I (8988) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (8988) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (8988) EGGS_MATH:
I (8988) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (8988) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (8988) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (8988) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (8988) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (8988) EGGS_MATH: 
I (8988) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (8988) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (10988) main_task: Returned from app_main()
```
### แบบฝึกหัดที่ 3: สร้างโจทย์ของตัวเอง

ลองเปลี่ยนเป็นโจทย์อื่น เช่น:

🍎 แอปเปิ้ลในตะกร้า
📚 หนังสือบนชั้น
🚗 รถในลานจอด
🌟 ดาวในท้องฟ้า

### Result
```c
I (16280) CAR_PARK: 🧮 ขั้นตอนการคิด:
I (16280) CAR_PARK:    รถเดิมที่จอดอยู่ + รถที่เข้ามาเพิ่ม
I (16280) CAR_PARK:    = 5 + 5
I (16280) CAR_PARK:    = 10 คัน
I (16280) CAR_PARK: 
I (16280) CAR_PARK: ✅ คำตอบ:
I (16280) CAR_PARK:    ตอนนี้ในลานจอดมีรถทั้งหมด 9 คัน
I (16280) CAR_PARK: 
I (16280) CAR_PARK: 🎨 ภาพประกอบ:
I (16280) CAR_PARK:    รถเดิม: 🚗🚗🚗🚗🚗 (5 คัน)
I (16280) CAR_PARK:    รถที่เข้าใหม่: 🚗🚗🚗🚗🚗 (5 คัน)
I (16280) CAR_PARK:    รวม: 🚗🚗🚗🚗🚗🚗🚗🚗🚗🚗 (10 คัน)
I (16280) CAR_PARK:
I (16280) CAR_PARK: 💡 ตัวอย่างเพิ่มเติม:
I (16280) CAR_PARK:    ถ้ามีรถจอดอยู่แล้ว 5 คัน และมีเข้ามาอีก 2 คัน
I (16280) CAR_PARK:    จะมีรถทั้งหมด 5 + 2 = 7 คัน
I (16280) CAR_PARK:
I (16280) CAR_PARK:    ถ้ามีรถจอดอยู่แล้ว 2 คัน และมีเข้ามาอีก 4 คัน
I (16280) CAR_PARK:    จะมีรถทั้งหมด 2 + 4 = 6 คัน
I (16280) CAR_PARK:
I (16280) CAR_PARK: 📚 สิ่งที่เรียนรู้:
I (16280) CAR_PARK:    1. การบวกเลข (Addition): a + b = c
I (16280) CAR_PARK:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (16280) CAR_PARK:    3. การแสดงผลด้วย ESP_LOGI
I (16280) CAR_PARK:    4. การแก้โจทย์แบบมีขั้นตอน
I (16280) CAR_PARK:
I (16290) CAR_PARK: 🎉 จบโปรแกรมนับรถในลานจอด!
I (16290) CAR_PARK: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_bicycles
I (16290) main_task: Returned from app_main()
```
