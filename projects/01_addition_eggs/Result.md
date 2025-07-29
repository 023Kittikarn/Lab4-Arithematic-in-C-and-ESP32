### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนไข่
```c
// หาบรรทัดนี้ในโค้ด:
int eggs_already_have = 4;    // ไข่ไก่ที่แม่มีอยู่แล้ว
int eggs_new_today = 2;       // ไข่ไก่ที่ไก่ออกวันนี้

// ลองเปลี่ยนเป็น:
int eggs_already_have = 8;    // เพิ่มเป็น 8 ฟอง
int eggs_new_today = 3;       // เพิ่มเป็น 3 ฟอง

I (2873) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (2873) EGGS_MATH: =====================================
I (2873) EGGS_MATH: 📖 โจทย์:
I (2873) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 8 ฟอง
I (2873) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 3 ฟอง
I (2873) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (2873) EGGS_MATH: 
I (5873) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (5873) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (5873) EGGS_MATH:    = 8 + 3
I (5873) EGGS_MATH:    = 11 ฟอง
I (5873) EGGS_MATH: 
I (5873) EGGS_MATH: ✅ คำตอบ:
I (5873) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (5873) EGGS_MATH: 
I (5873) EGGS_MATH: 🎨 ภาพประกอบ:
I (5873) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚 (8 ฟอง)
I (5873) EGGS_MATH:    ไข่ใหม่: 🥚🥚 (3 ฟอง)
I (5873) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (5873) EGGS_MATH: 
I (5873) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (5873) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (5873) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (5873) EGGS_MATH: 
I (5873) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (5873) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (5873) EGGS_MATH: 
I (5873) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (5873) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (5873) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (5883) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (5883) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (5883) EGGS_MATH: 
I (5883) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (5883) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (7883) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 2: เพิ่มไข่เป็ด
เพิ่มโค้ดนี้หลังบรรทัด `int total_eggs;`:
```c
int duck_eggs = 3;            // ไข่เป็ดที่แม่มี
int total_all_eggs;           // ไข่ทั้งหมด (ไก่ + เป็ด)
แล้วเพิ่มการคำนวณหลังบรรทัด `total_eggs = eggs_already_have + eggs_new_today;`:
```c
total_all_eggs = total_eggs + duck_eggs;
// แสดงผลไข่เป็ด
ESP_LOGI(TAG, "🦆 และแม่มีไข่เป็ด: %d ฟอง", duck_eggs);
ESP_LOGI(TAG, "🥚 ไข่ทั้งหมด (ไก่+เป็ด): %d ฟอง", total_all_eggs);
```
```
I (2700) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (2700) EGGS_MATH: =====================================
I (2700) EGGS_MATH: 📖 โจทย์:
I (2700) EGGS_MATH:    แม่มีไข่ไก่อยู่แล้ว: 8 ฟอง
I (2700) EGGS_MATH:    เมื่อเช้าไก่ออกไข่เพิ่ม: 3 ฟอง
I (2700) EGGS_MATH:    ❓ วันนี้แม่มีไข่ไก่รวมกี่ฟอง?
I (2700) EGGS_MATH: 
I (5700) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (5700) EGGS_MATH:    ไข่ไก่ที่มีอยู่ + ไข่ไก่ที่ออกใหม่
I (5700) EGGS_MATH:    = 8 + 3
I (5700) EGGS_MATH:    = 11 ฟอง
I (5700) EGGS_MATH: 
I (5700) EGGS_MATH: ✅ คำตอบ:
I (5700) EGGS_MATH:    วันนี้แม่มีไข่ไก่ทั้งหมด 11 ฟอง
I (5700) EGGS_MATH: 
I (5700) EGGS_MATH: 🦆 และแม่มีไข่เป็ด: 3 ฟอง
I (5700) EGGS_MATH: 🥚 ไข่ทั้งหมด (ไก่+เป็ด): 14 ฟอง
I (5700) EGGS_MATH: 🎨 ภาพประกอบ:
I (5700) EGGS_MATH:    ไข่เดิม: 🥚🥚🥚🥚 (8 ฟอง)
I (5700) EGGS_MATH:    ไข่ใหม่: 🥚🥚 (3 ฟอง)
I (5700) EGGS_MATH:    รวม:    🥚🥚🥚🥚🥚🥚 (11 ฟอง)
I (5700) EGGS_MATH: 
I (5700) EGGS_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (5700) EGGS_MATH:    ถ้าแม่มีไข่ 7 ฟอง และไก่ออกไข่ 3 ฟอง
I (5700) EGGS_MATH:    จะได้ไข่ทั้งหมด 7 + 3 = 10 ฟอง
I (5700) EGGS_MATH: 
I (5700) EGGS_MATH:    ถ้าแม่มีไข่ 10 ฟอง และไก่ออกไข่ 5 ฟอง
I (5700) EGGS_MATH:    จะได้ไข่ทั้งหมด 10 + 5 = 15 ฟอง
I (5700) EGGS_MATH: 
I (5700) EGGS_MATH: 📚 สิ่งที่เรียนรู้:
I (5700) EGGS_MATH:    1. การบวกเลข (Addition): a + b = c
I (5700) EGGS_MATH:    2. การใช้ตัวแปร (Variables) เก็บค่า
I (5700) EGGS_MATH:    3. การแสดงผลด้วย ESP_LOGI
I (5700) EGGS_MATH:    4. การแก้โจทย์แบบมีขั้นตอน
I (5700) EGGS_MATH: 
I (5700) EGGS_MATH: 🎉 จบโปรแกรมนับไข่ไก่ของแม่!
I (5700) EGGS_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 02_subtraction_toys
I (7700) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 3: สร้างโจทย์ของตัวเอง
ลองเปลี่ยนเป็นโจทย์อื่น เช่น:
- 🍎 แอปเปิ้ลในตะกร้า
- 📚 หนังสือบนชั้น  
- 🚗 รถในลานจอด
- 🌟 ดาวในท้องฟ้า

```
I (2715) EGGS_MATH: 🥚 เริ่มต้นโปรแกรมนับไข่ไก่ของแม่ 🥚
I (2715) EGGS_MATH: =====================================
I (5715) EGGS_MATH: มีแอปเปิ้ลอยู่แล้ว : 200 ผล
I (5715) EGGS_MATH: เพิ่มแอปเปิ้ล : 100 ผล
I (5715) EGGS_MATH: รวมมีแอปเปิ้ลอยู่ในตะกร้าทั้งหมด : 300 ผล
I (5715) EGGS_MATH: 
I (5715) EGGS_MATH: 
I (5715) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (5715) EGGS_MATH:    แอปเปิ้ลที่มีอยู่ + แอปเปิ้ลที่เพิ่มเข้ามา
I (5715) EGGS_MATH:    = 200 + 100
I (5715) EGGS_MATH:    = 300 ผล
I (5715) EGGS_MATH: 
I (5715) EGGS_MATH: ✅ คำตอบ:
I (5715) EGGS_MATH:    รวมมีแอปเปิ้ลอยู่ในตะกร้าทั้งหมด 300 ผล
I (5715) EGGS_MATH: 
I (5725) EGGS_MATH: 🎨 ภาพประกอบ:
I (5725) EGGS_MATH:    แอปเปิ้ลเดิม: 🍎 (200 ฟอง)
I (5725) EGGS_MATH:    แอปเปิ้ลใหม่: 🍎 (100 ฟอง)
I (5725) EGGS_MATH:    รวม:   🍎 (300 ฟอง)
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: มีหนังสืออยู่ 5 เล่ม
I (5725) EGGS_MATH: เพิ่มหนังสืออีก 1 เล่ม
I (5725) EGGS_MATH: มีหนังสือบนชั้นวางทั้งหมด 6 เล่ม
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (5725) EGGS_MATH:    หนังสือที่มีอยู่ + หนังสือที่เพิ่มเข้ามา
I (5725) EGGS_MATH:    = 5 + 1
I (5725) EGGS_MATH:    = 6 เล่ม
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: ✅ คำตอบ:
I (5725) EGGS_MATH:    รวมมีหนังสืออยู่บนชั้นวางทั้งหมด 6 เล่ม
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: 🎨 ภาพประกอบ:
I (5725) EGGS_MATH:    หนังสือเดิม: 📚 (5 เล่ม)
I (5725) EGGS_MATH:    หนังสือใหม่: 📚 (1 เล่ม)
I (5725) EGGS_MATH:    รวม:   📚 (6 เล่ม)
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: มีรถจอดอยู่ : 23 คัน
I (5725) EGGS_MATH: มีรถมาจอดเพิ่ม : 7 คัน
I (5725) EGGS_MATH: มีรถจอดทั้งหมด : 30 คัน
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (5725) EGGS_MATH:    รถที่มีอยู่ + รถที่เพิ่มเข้ามา
I (5725) EGGS_MATH:    = 23 + 7
I (5725) EGGS_MATH:    = 30 คัน
I (5725) EGGS_MATH: 
I (5725) EGGS_MATH: ✅ คำตอบ:
I (5725) EGGS_MATH:    รวมมีรถที่จอดทั้งหมด 30 คัน
I (5735) EGGS_MATH: 
I (5735) EGGS_MATH: 🎨 ภาพประกอบ:
I (5735) EGGS_MATH:    รถเดิม : 🚗 (23 คัน)
I (5735) EGGS_MATH:    รถใหม่ : 🚗 (7 คัน)
I (5735) EGGS_MATH:    รวม :   🚗 (30 คัน)
I (5735) EGGS_MATH: 
I (5735) EGGS_MATH: มีดาวอยู่บนฟ้า : 3 ดวง
I (5735) EGGS_MATH: ดวงดวงเลือนหายไป : 2 ดวง
I (5735) EGGS_MATH: เหลือดาวบนฟ้าทั้งหมด : 5 ดาว
I (5735) EGGS_MATH: 
I (5735) EGGS_MATH: 
I (5735) EGGS_MATH: 🧮 ขั้นตอนการคิด:
I (5735) EGGS_MATH:    ดวงดาวที่มีอยู่ + ดวงดาวที่ลบไป
I (5735) EGGS_MATH:    = 3 + 2
I (5735) EGGS_MATH:    = 5 ดวง
I (5735) EGGS_MATH: 
I (5735) EGGS_MATH: ✅ คำตอบ:
I (5735) EGGS_MATH:    มีดวงดาวทั้งอยู่บนฟ้าทั้งหมด 5 ดวง
I (5735) EGGS_MATH: 
I (5735) EGGS_MATH: 🎨 ภาพประกอบ:
I (5735) EGGS_MATH:    ดวงดาวเดิม: 🌟 (3 ดวง)
I (5735) EGGS_MATH:    ดวงดาวใหม่: 🌟 (2 ดวง)
I (5735) EGGS_MATH:    รวม:   🌟 (5 ดวง)
I (5735) EGGS_MATH: 
I (7735) main_task: Returned from app_main()
```
