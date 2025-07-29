### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนถุงลูกอม
```c
// หาบรรทัดนี้ในโค้ด:
int candy_bags = 5;         // จำนวนถุง
int candies_per_bag = 6;    // ลูกอมต่อถุง

// ลองเปลี่ยนเป็น:
int candy_bags = 7;         // เพิ่มเป็น 7 ถุง
int candies_per_bag = 8;    // ลูกอมถุงละ 8 เม็ด
```

```
I (2025) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (2025) CANDIES_MATH: ====================================
I (2025) CANDIES_MATH: 📖 โจทย์:
I (2025) CANDIES_MATH:    มีถุงลูกอม: 7 ถุง
I (2025) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (2025) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (2025) CANDIES_MATH: 
I (5025) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (5025) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (5025) CANDIES_MATH:    = 7 × 8
I (5025) CANDIES_MATH:    = 56 เม็ด
I (5025) CANDIES_MATH: 
I (5025) CANDIES_MATH: ✅ คำตอบ:
I (5025) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (5025) CANDIES_MATH: 
I (5025) CANDIES_MATH: 🎨 ภาพประกอบ:
I (5025) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5025) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5025) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5025) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5025) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5025) CANDIES_MATH:    รวม:     56 เม็ด
I (5025) CANDIES_MATH: 
I (5025) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (5025) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (5035) CANDIES_MATH:    การบวกซ้ำๆ:
I (5035) CANDIES_MATH:                   8
I (5035) CANDIES_MATH:                 + 8
I (5035) CANDIES_MATH:                 + 8
I (5035) CANDIES_MATH:                 + 8
I (5035) CANDIES_MATH:                 + 8
I (5035) CANDIES_MATH:                 + 8
I (5035) CANDIES_MATH:                 + 8 = 56
I (5035) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (5035) CANDIES_MATH: 
I (5035) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (5035) CANDIES_MATH:    1 × 8 = 8
I (5335) CANDIES_MATH:    2 × 8 = 16
I (5635) CANDIES_MATH:    3 × 8 = 24
I (5935) CANDIES_MATH:    4 × 8 = 32
I (6235) CANDIES_MATH:    5 × 8 = 40
I (6535) CANDIES_MATH:    6 × 8 = 48
I (6835) CANDIES_MATH:    7 × 8 = 56
I (7135) CANDIES_MATH:    8 × 8 = 64
I (7435) CANDIES_MATH:    9 × 8 = 72
I (7735) CANDIES_MATH:    10 × 8 = 80
I (8035) CANDIES_MATH: 
I (8035) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (8035) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (8035) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (8035) CANDIES_MATH: 
I (8035) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (8035) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (8035) CANDIES_MATH: 
I (8035) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (8035) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (8035) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (8035) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (8035) CANDIES_MATH: 
I (8035) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (8035) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (8035) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (8035) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (8035) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (8035) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (8035) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (8045) CANDIES_MATH: 
I (8045) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8045) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (8045) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (8045) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (8045) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (8045) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (8045) CANDIES_MATH: 
I (8045) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (8045) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (10045) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 2: เพิ่มลูกอมหลายรส
เพิ่มลูกอมหลายรส:
```c
int strawberry_bags = 3;    // ถุงรสสตรอเบอร์รี่
int orange_bags = 2;        // ถุงรสส้ม
int grape_bags = 4;         // ถุงรสองุ่น

int total_bags = strawberry_bags + orange_bags + grape_bags;
int total_candies = total_bags * candies_per_bag;

ESP_LOGI(TAG, "🍓 สตรอเบอร์รี่: %d ถุง = %d เม็ด", 
         strawberry_bags, strawberry_bags * candies_per_bag);
ESP_LOGI(TAG, "🍊 รสส้ม: %d ถุง = %d เม็ด", 
         orange_bags, orange_bags * candies_per_bag);
ESP_LOGI(TAG, "🍇 รสองุ่น: %d ถุง = %d เม็ด", 
         grape_bags, grape_bags * candies_per_bag);
```
```
I (2037) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (2037) CANDIES_MATH: ====================================
I (2037) CANDIES_MATH: 📖 โจทย์:
I (2037) CANDIES_MATH:    มีถุงลูกอม: 7 ถุง
I (2037) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (2037) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (2037) CANDIES_MATH: 
I (5037) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (5037) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (5037) CANDIES_MATH:    = 7 × 8
I (5037) CANDIES_MATH:    = 56 เม็ด
I (5037) CANDIES_MATH: 
I (5037) CANDIES_MATH: ✅ คำตอบ:
I (5037) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (5037) CANDIES_MATH: 
I (5037) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (5037) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (5037) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (5037) CANDIES_MATH: 🎨 ภาพประกอบ:
I (5037) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5037) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5037) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5037) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5037) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5037) CANDIES_MATH:    ถุงที่ 6: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5037) CANDIES_MATH:    ถุงที่ 7: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5037) CANDIES_MATH:    รวม:     56 เม็ด
I (5047) CANDIES_MATH: 
I (5047) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (5047) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (5047) CANDIES_MATH:    การบวกซ้ำๆ:
I (5047) CANDIES_MATH:                   8
I (5047) CANDIES_MATH:                 + 8
I (5047) CANDIES_MATH:                 + 8
I (5047) CANDIES_MATH:                 + 8
I (5047) CANDIES_MATH:                 + 8
I (5047) CANDIES_MATH:                 + 8
I (5047) CANDIES_MATH:                 + 8 = 56
I (5047) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (5047) CANDIES_MATH: 
I (5047) CANDIES_MATH: 📊 ตารางสูตรคูณ 8:
I (5047) CANDIES_MATH:    1 × 8 = 8
I (5347) CANDIES_MATH:    2 × 8 = 16
I (5647) CANDIES_MATH:    3 × 8 = 24
I (5947) CANDIES_MATH:    4 × 8 = 32
I (6247) CANDIES_MATH:    5 × 8 = 40
I (6547) CANDIES_MATH:    6 × 8 = 48
I (6847) CANDIES_MATH:    7 × 8 = 56
I (7147) CANDIES_MATH:    8 × 8 = 64
I (7447) CANDIES_MATH:    9 × 8 = 72
I (7747) CANDIES_MATH:    10 × 8 = 80
I (8047) CANDIES_MATH: 
I (8047) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (8047) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (8047) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (8047) CANDIES_MATH: 
I (8047) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (8047) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (8047) CANDIES_MATH: 
I (8047) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (8057) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน (เช่น ไข่ 4 + 2 = 6)
I (8057) CANDIES_MATH:    การลบ (-): ลดจำนวน (เช่น ของเล่น 8 - 3 = 5)
I (8057) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ (เช่น ลูกอม 5 × 6 = 30)
I (8057) CANDIES_MATH: 
I (8057) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (8057) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (8057) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (8057) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (8057) CANDIES_MATH:       7 × 0 = 0 (ไม่มีถุงลูกอม)
I (8057) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (8057) CANDIES_MATH:       8 × 1 = 8 (มีถุงเดียว)
I (8057) CANDIES_MATH: 
I (8057) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8057) CANDIES_MATH:    1. การคูณเลข (Multiplication): a × b = c
I (8057) CANDIES_MATH:    2. การใช้ for loop สำหรับการทำซ้ำ
I (8057) CANDIES_MATH:    3. ความสัมพันธ์ระหว่างการคูณและการบวกซ้ำๆ
I (8057) CANDIES_MATH:    4. คุณสมบัติพิเศษของการคูณ
I (8057) CANDIES_MATH:    5. การแสดงผลแบบตาราง
I (8057) CANDIES_MATH: 
I (8057) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (8057) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (10057) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 3: สร้างตารางสูตรคูณ
เพิ่มการแสดงตารางสูตรคูณ:
```c
ESP_LOGI(TAG, "📊 ตารางสูตรคูณของ %d:", candies_per_bag);
for (int i = 1; i <= 10; i++) {
    ESP_LOGI(TAG, "   %d x %d = %d", i, candies_per_bag, i * candies_per_bag);
}
```
```
I (2048) CANDIES_MATH: 🍬 เริ่มต้นโปรแกรมนับลูกอมในถุง 🍬
I (2048) CANDIES_MATH: ====================================
I (2048) CANDIES_MATH: 📖 โจทย์:
I (2048) CANDIES_MATH:    มีถุงลูกอม: 7 ถุง
I (2048) CANDIES_MATH:    ถุงละ: 8 เม็ด
I (2048) CANDIES_MATH:    ❓ มีลูกอมทั้งหมดกี่เม็ด?
I (2048) CANDIES_MATH: 
I (5048) CANDIES_MATH: 🧮 ขั้นตอนการคิด:
I (5048) CANDIES_MATH:    จำนวนถุง × ลูกอมต่อถุง
I (5048) CANDIES_MATH:    = 7 × 8
I (5048) CANDIES_MATH:    = 56 เม็ด
I (5048) CANDIES_MATH: 
I (5048) CANDIES_MATH: ✅ คำตอบ:
I (5048) CANDIES_MATH:    มีลูกอมทั้งหมด 56 เม็ด
I (5048) CANDIES_MATH: 
I (5048) CANDIES_MATH: 🍓 สตรอเบอร์รี่: 3 ถุง = 24 เม็ด
I (5048) CANDIES_MATH: 🍊 รสส้ม: 2 ถุง = 16 เม็ด
I (5048) CANDIES_MATH: 🍇 รสองุ่น: 4 ถุง = 32 เม็ด
I (5048) CANDIES_MATH: 🎨 ภาพประกอบ:
I (5048) CANDIES_MATH:    ถุงที่ 1: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5048) CANDIES_MATH:    ถุงที่ 2: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5048) CANDIES_MATH:    ถุงที่ 3: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5048) CANDIES_MATH:    ถุงที่ 4: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5048) CANDIES_MATH:    ถุงที่ 5: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5048) CANDIES_MATH:    ถุงที่ 6: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5048) CANDIES_MATH:    ถุงที่ 7: 🍬🍬🍬🍬🍬🍬 (8 เม็ด)
I (5048) CANDIES_MATH:    รวม:     56 เม็ด
I (5048) CANDIES_MATH: 
I (5058) CANDIES_MATH: 🔄 เปรียบเทียบกับการบวกซ้ำๆ:
I (5058) CANDIES_MATH:    การคูณ: 7 × 8 = 56
I (5058) CANDIES_MATH:    การบวกซ้ำๆ:
I (5058) CANDIES_MATH:                   8
I (5058) CANDIES_MATH:                 + 8
I (5058) CANDIES_MATH:                 + 8
I (5058) CANDIES_MATH:                 + 8
I (5058) CANDIES_MATH:                 + 8
I (5058) CANDIES_MATH:                 + 8
I (5058) CANDIES_MATH:                 + 8 = 56
I (5058) CANDIES_MATH:    ผลลัพธ์เหมือนกัน! การคูณคือการบวกซ้ำๆ
I (5058) CANDIES_MATH: 
I (5058) CANDIES_MATH: 📊 ตารางสูตรคูณของ 8:
I (5058) CANDIES_MATH:    1 x 8 = 8
I (5358) CANDIES_MATH:    2 x 8 = 16
I (5658) CANDIES_MATH:    3 x 8 = 24
I (5958) CANDIES_MATH:    4 x 8 = 32
I (6258) CANDIES_MATH:    5 x 8 = 40
I (6558) CANDIES_MATH:    6 x 8 = 48
I (6858) CANDIES_MATH:    7 x 8 = 56
I (7158) CANDIES_MATH:    8 x 8 = 64
I (7458) CANDIES_MATH:    9 x 8 = 72
I (7758) CANDIES_MATH:    10 x 8 = 80
I (8058) CANDIES_MATH: 
I (8058) CANDIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (8058) CANDIES_MATH:    ถ้ามีถุงลูกอม 3 ถุง ถุงละ 8 เม็ด
I (8058) CANDIES_MATH:    จะได้ลูกอม 3 × 8 = 24 เม็ด
I (8058) CANDIES_MATH: 
I (8058) CANDIES_MATH:    ถ้ามีถุงลูกอม 7 ถุง ถุงละ 4 เม็ด
I (8058) CANDIES_MATH:    จะได้ลูกอม 7 × 4 = 28 เม็ด
I (8058) CANDIES_MATH: 
I (8058) CANDIES_MATH: 🔄 เปรียบเทียบการดำเนินการ:
I (8058) CANDIES_MATH:    การบวก (+): เพิ่มจำนวน
I (8058) CANDIES_MATH:    การลบ (-): ลดจำนวน
I (8058) CANDIES_MATH:    การคูณ (×): บวกซ้ำๆ
I (8058) CANDIES_MATH: 
I (8058) CANDIES_MATH: 🎓 แนวคิดขั้นสูง:
I (8058) CANDIES_MATH:    1. การคูณมีคุณสมบัติการสับเปลี่ยน:
I (8058) CANDIES_MATH:       7 × 8 = 8 × 7 = 56
I (8058) CANDIES_MATH:    2. การคูณด้วย 0 จะได้ 0 เสมอ:
I (8058) CANDIES_MATH:       7 × 0 = 0
I (8058) CANDIES_MATH:    3. การคูณด้วย 1 จะได้ตัวเลขเดิม:
I (8058) CANDIES_MATH:       8 × 1 = 8
I (8058) CANDIES_MATH: 
I (8058) CANDIES_MATH: 📚 สิ่งที่เรียนรู้:
I (8058) CANDIES_MATH:    1. การคูณเลข (Multiplication)
I (8058) CANDIES_MATH:    2. การใช้ for loop
I (8058) CANDIES_MATH:    3. การบวกซ้ำๆ
I (8068) CANDIES_MATH:    4. คุณสมบัติการคูณ
I (8068) CANDIES_MATH: 
I (8068) CANDIES_MATH: 🎉 จบโปรแกรมนับลูกอมในถุง!
I (8068) CANDIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 04_division_cookies
I (10068) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 4: แจกลูกอมให้เพื่อน
คำนวณการแจกลูกอม:
```c
int friends = 12;           // จำนวนเพื่อน
int candies_per_friend = total_candies / friends;  // ลูกอมต่อคน
int remaining_candies = total_candies % friends;   // ลูกอมที่เหลือ

ESP_LOGI(TAG, "👥 แจกให้เพื่อน %d คน:", friends);
ESP_LOGI(TAG, "   คนละ %d เม็ด", candies_per_friend);
ESP_LOGI(TAG, "   เหลือ %d เม็ด", remaining_candies);
```
```
I (2018) 🧸 SubtractionToys: 🧸 ของเล่นก่อนแจก: 15 ชิ้น
I (2018) 🧸 SubtractionToys: 🎁 แจกให้เพื่อน: 7 ชิ้น
I (2018) 🧸 SubtractionToys: 📦 ของเล่นที่เหลือ: 8 ชิ้น
I (2018) 🧸 SubtractionToys: ✅ ของเล่นพอแจก
I (2018) 🧸 SubtractionToys: 📦 ของเล่นทั้งหมด (รวมตุ๊กตา + หุ่นยนต์): 22 ชิ้น
I (2018) 🧸 SubtractionToys: 🍬 ลูกอมถุงละ 3 เม็ด x 4 ถุง = รวม 12 เม็ด
I (2018) 🧸 SubtractionToys: 📊 ตารางสูตรคูณของ 3:
I (2018) 🧸 SubtractionToys:     1 x 3 =  3
I (2018) 🧸 SubtractionToys:     2 x 3 =  6
I (2018) 🧸 SubtractionToys:     3 x 3 =  9
I (2018) 🧸 SubtractionToys:     4 x 3 = 12
I (2018) 🧸 SubtractionToys:     5 x 3 = 15
I (2018) 🧸 SubtractionToys:     6 x 3 = 18
I (2018) 🧸 SubtractionToys:     7 x 3 = 21
I (2018) 🧸 SubtractionToys:     8 x 3 = 24
I (2018) 🧸 SubtractionToys:     9 x 3 = 27
I (2018) 🧸 SubtractionToys:    10 x 3 = 30
I (2018) 🧸 SubtractionToys: 
I (2018) 🧸 SubtractionToys: 👥 แจกลูกอมให้เพื่อน 12 คน:
I (2018) 🧸 SubtractionToys:    คนละ 1 เม็ด
I (2018) 🧸 SubtractionToys:    เหลือ 0 เม็ด
I (2018) 🧸 SubtractionToys:    เพื่อนคนที่  1 ได้ลูกอม: 🍬 x 1
I (2168) 🧸 SubtractionToys:    เพื่อนคนที่  2 ได้ลูกอม: 🍬 x 1
I (2318) 🧸 SubtractionToys:    เพื่อนคนที่  3 ได้ลูกอม: 🍬 x 1
I (2468) 🧸 SubtractionToys:    เพื่อนคนที่  4 ได้ลูกอม: 🍬 x 1
I (2618) 🧸 SubtractionToys:    เพื่อนคนที่  5 ได้ลูกอม: 🍬 x 1
I (2768) 🧸 SubtractionToys:    เพื่อนคนที่  6 ได้ลูกอม: 🍬 x 1
I (2918) 🧸 SubtractionToys:    เพื่อนคนที่  7 ได้ลูกอม: 🍬 x 1
I (3068) 🧸 SubtractionToys:    เพื่อนคนที่  8 ได้ลูกอม: 🍬 x 1
I (3218) 🧸 SubtractionToys:    เพื่อนคนที่  9 ได้ลูกอม: 🍬 x 1
I (3368) 🧸 SubtractionToys:    เพื่อนคนที่ 10 ได้ลูกอม: 🍬 x 1
I (3518) 🧸 SubtractionToys:    เพื่อนคนที่ 11 ได้ลูกอม: 🍬 x 1
I (3668) 🧸 SubtractionToys:    เพื่อนคนที่ 12 ได้ลูกอม: 🍬 x 1
I (3818) 🧸 SubtractionToys: 🎉 แจกหมดพอดี ไม่มีเหลือ!
I (3818) main_task: Returned from app_main()
```
