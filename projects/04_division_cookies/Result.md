# โปรเจค 4: การหาร - คุกกี้แบ่งกัน 🍪

### 📝 แบบฝึกหัดที่ 1: เปลี่ยนจำนวนคุกกี้
```c
// หาบรรทัดนี้ในโค้ด:
int total_cookies = 20;    // คุกกี้ทั้งหมด
int friends = 4;           // จำนวนเพื่อน

// ลองเปลี่ยนเป็น:
int total_cookies = 24;    // เพิ่มเป็น 24 ชิ้น
int friends = 6;           // เพิ่มเป็น 6 คน
```
ผลลัพธ์ที่ได้
```
I (1952) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (1952) COOKIES_MATH: ================================
I (1952) COOKIES_MATH: 📖 โจทย์:
I (1952) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (1952) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (1952) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (1952) COOKIES_MATH: 
I (4952) COOKIES_MATH: 🧮 ขั้นตอนการคิด:
I (4952) COOKIES_MATH:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (4952) COOKIES_MATH:    = 24 ÷ 6
I (4952) COOKIES_MATH:    = 4 ชิ้นต่อคน
I (4952) COOKIES_MATH: 
I (4952) COOKIES_MATH: ✅ คำตอบ:
I (4952) COOKIES_MATH:    แต่ละคนได้คุกกี้ 4 ชิ้น
I (4952) COOKIES_MATH:    แบ่งได้พอดี ไม่มีเหลือ
I (4952) COOKIES_MATH: 
I (4952) COOKIES_MATH: 🎨 ภาพประกอบการแบ่ง:
I (4952) COOKIES_MATH:    คุกกี้ทั้งหมด: 🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪🍪 (24 ชิ้น)
I (4952) COOKIES_MATH: 
I (4952) COOKIES_MATH:    เพื่อนคนที่ 1: 
I (4952) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (4952) COOKIES_MATH:    เพื่อนคนที่ 2: 
I (4952) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (4952) COOKIES_MATH:    เพื่อนคนที่ 3: 
I (4952) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (4952) COOKIES_MATH:    เพื่อนคนที่ 4: 
I (4952) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (4952) COOKIES_MATH:    เพื่อนคนที่ 5: 
I (4952) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (4952) COOKIES_MATH:    เพื่อนคนที่ 6: 
I (4952) COOKIES_MATH: 🍪🍪🍪 (4 ชิ้น)
I (4962) COOKIES_MATH: 
I (4962) COOKIES_MATH: 💡 ตัวอย่างเพิ่มเติม:
I (4962) COOKIES_MATH:    คุกกี้ 15 ชิ้น แบ่งให้ 3 คน
I (4962) COOKIES_MATH:    = 15 ÷ 3 = 5 ชิ้นต่อคน, เหลือ 0 ชิ้น
I (4962) COOKIES_MATH: 
I (4962) COOKIES_MATH:    คุกกี้ 13 ชิ้น แบ่งให้ 4 คน
I (4962) COOKIES_MATH:    = 13 ÷ 4 = 3 ชิ้นต่อคน, เหลือ 1 ชิ้น
I (4962) COOKIES_MATH:    (หารไม่ลงตัว)
I (4962) COOKIES_MATH: 
I (4962) COOKIES_MATH: ⚠️  กรณีพิเศษ - หารด้วยศูนย์:
I (4962) COOKIES_MATH:    ถ้าไม่มีเพื่อนมาแบ่ง (หารด้วย 0)
I (4962) COOKIES_MATH:    ไม่สามารถคำนวณได้ในทางคณิตศาสตร์
I (4962) COOKIES_MATH:    ในชีวิตจริง: คุกกี้จะเหลือทั้งหมด
I (4962) COOKIES_MATH: 
I (4962) COOKIES_MATH: 🔄 ความสัมพันธ์กับการคูณ:
I (4962) COOKIES_MATH:    การหาร: 24 ÷ 6 = 4
I (4962) COOKIES_MATH:    การคูณ: 4 × 6 = 24
I (4962) COOKIES_MATH:    การหารและการคูณเป็นการดำเนินการตรงข้ามกัน
I (4962) COOKIES_MATH: 
I (4962) COOKIES_MATH: 📊 สรุปการดำเนินการทั้งหมด:
I (4962) COOKIES_MATH:    การบวก (+): เพิ่มจำนวน
I (4962) COOKIES_MATH:    การลบ (-): ลดจำนวน
I (4962) COOKIES_MATH:    การคูณ (×): บวกซ้ำๆ หลายชุด
I (4962) COOKIES_MATH:    การหาร (÷): แบ่งออกเป็นกลุ่มเท่าๆ กัน
I (4962) COOKIES_MATH: 
I (4962) COOKIES_MATH: 🎓 แนวคิดขั้นสูง:
I (4962) COOKIES_MATH:    1. การหารจะได้ผลหาร (quotient) และเศษ (remainder)
I (4962) COOKIES_MATH:    2. ในภาษา C:
I (4962) COOKIES_MATH:       ผลหาร = a / b
I (4962) COOKIES_MATH:       เศษ = a % b
I (4962) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์เป็นสิ่งสำคัญ
I (4962) COOKIES_MATH:    4. การหารด้วย 1 จะได้ตัวเลขเดิม
I (4962) COOKIES_MATH:    5. การหารตัวเลขด้วยตัวมันเองจะได้ 1
I (4972) COOKIES_MATH: 
I (4972) COOKIES_MATH: 📚 สิ่งที่เรียนรู้:
I (4972) COOKIES_MATH:    1. การหารเลข (Division): a ÷ b = c
I (4972) COOKIES_MATH:    2. การใช้ Modulo operator (%) หาเศษ
I (4972) COOKIES_MATH:    3. การตรวจสอบการหารด้วยศูนย์
I (4972) COOKIES_MATH:    4. ความแตกต่างระหว่างหารลงตัวและไม่ลงตัว
I (4972) COOKIES_MATH:    5. ความสัมพันธ์ระหว่างการหารและการคูณ
I (4972) COOKIES_MATH:    6. การจัดการกรณีพิเศษ (Error Handling)
I (4972) COOKIES_MATH: 
I (4972) COOKIES_MATH: 🎉 จบโปรแกรมแบ่งคุกกี้!
I (4972) COOKIES_MATH: 📖 อ่านต่อในโปรเจคถัดไป: 05_mixed_shopping
I (6972) main_task: Returned from app_main()
```

### 📝 แบบฝึกหัดที่ 2: เพิ่มการตรวจสอบหารลงตัว
เพิ่มการตรวจสอบว่าหารลงตัวไหม:
```c
int cookies_per_person = total_cookies / friends;
int remaining_cookies = total_cookies % friends;

if (remaining_cookies == 0) {
    ESP_LOGI(TAG, "✅ หารลงตัว! ทุกคนได้เท่ากัน");
} else {
    ESP_LOGI(TAG, "⚠️ หารไม่ลงตัว! เหลือ %d ชิ้น", remaining_cookies);
}
```
ผลลัพธ์ที่ได้
```
I (2096) CookieSharing: 🍪 จำนวนคุกกี้ทั้งหมด: 29
I (2096) CookieSharing: 👫 จำนวนเพื่อน: 7
I (2096) CookieSharing: 
I (2096) CookieSharing: 🧮 ขั้นตอนการคิด:
I (2096) CookieSharing:    คุกกี้ทั้งหมด ÷ จำนวนเพื่อน
I (2096) CookieSharing:    = 29 ÷ 7
I (2096) CookieSharing:    = 4 ชิ้นต่อคน
I (2096) CookieSharing:    เศษที่เหลือ = 1 ชิ้น
I (2096) CookieSharing: 
I (2096) CookieSharing: ⚠️ หารไม่ลงตัว! เหลือ 1 ชิ้นที่แบ่งไม่ลงตัว
I (2096) CookieSharing: 
I (2096) CookieSharing: 📊 ตารางสูตรคูณของ 4:
I (2096) CookieSharing:    1 x 4 = 4
I (2096) CookieSharing:    2 x 4 = 8
I (2096) CookieSharing:    3 x 4 = 12
I (2096) CookieSharing:    4 x 4 = 16
I (2096) CookieSharing:    5 x 4 = 20
I (2096) CookieSharing:    6 x 4 = 24
I (2096) CookieSharing:    7 x 4 = 28
I (2096) CookieSharing:    8 x 4 = 32
I (2096) CookieSharing:    9 x 4 = 36
I (2096) CookieSharing:    10 x 4 = 40
I (2096) CookieSharing: 
I (2096) CookieSharing: 🎁 เริ่มแจกคุกกี้:
I (2096) CookieSharing:    เพื่อนคนที่  1 ได้คุกกี้: 🍪 x 4
I (2396) CookieSharing:    เพื่อนคนที่  2 ได้คุกกี้: 🍪 x 4
I (2696) CookieSharing:    เพื่อนคนที่  3 ได้คุกกี้: 🍪 x 4
I (2996) CookieSharing:    เพื่อนคนที่  4 ได้คุกกี้: 🍪 x 4
I (3296) CookieSharing:    เพื่อนคนที่  5 ได้คุกกี้: 🍪 x 4
I (3596) CookieSharing:    เพื่อนคนที่  6 ได้คุกกี้: 🍪 x 4
I (3896) CookieSharing:    เพื่อนคนที่  7 ได้คุกกี้: 🍪 x 4
I (4196) CookieSharing: 📦 คุกกี้ที่เหลือ: 🍪 x 1
I (4196) CookieSharing: 💡 คุณอาจกินเอง หรือแจกให้คนอื่นเพิ่มก็ได้!
I (4196) main_task: Returned from app_main()
```





### 📝 แบบฝึกหัดที่ 3: หาจำนวนเพื่อนที่เหมาะสม
ลองหาว่าคุกกี้ 30 ชิ้น จะแจกให้กี่คนได้หารลงตัว:
```c
int cookies = 30;
ESP_LOGI(TAG, "🔍 คุกกี้ %d ชิ้น หารลงตัวกับ:", cookies);

for (int people = 1; people <= 10; people++) {
    if (cookies % people == 0) {
        ESP_LOGI(TAG, "   ✅ %d คน → คนละ %d ชิ้น", 
                 people, cookies / people);
    }
}
```
ผลลัพธ์ที่ได้
```
I (2003) COOKIES_MATH: 🍪 เริ่มต้นโปรแกรมแบ่งคุกกี้ 🍪
I (2003) COOKIES_MATH: ================================
I (2003) COOKIES_MATH: 📖 โจทย์:
I (2003) COOKIES_MATH:    มีคุกกี้: 24 ชิ้น
I (2003) COOKIES_MATH:    จะแบ่งให้เพื่อน: 6 คน
I (2003) COOKIES_MATH:    ❓ แต่ละคนได้คุกกี้กี่ชิ้น?
I (2003) COOKIES_MATH: 
I (5003) COOKIES_MATH: 🔍 คุกกี้ 30 ชิ้น หารลงตัวกับ:
I (5003) COOKIES_MATH:    ✅ 1 คน → คนละ 30 ชิ้น
I (5003) COOKIES_MATH:    ✅ 2 คน → คนละ 15 ชิ้น
I (5003) COOKIES_MATH:    ✅ 3 คน → คนละ 10 ชิ้น
I (5003) COOKIES_MATH:    ✅ 5 คน → คนละ 6 ชิ้น
I (5003) COOKIES_MATH:    ✅ 6 คน → คนละ 5 ชิ้น
I (5003) COOKIES_MATH:    ✅ 10 คน → คนละ 3 ชิ้น
I (7003) main_task: Returned from app_main()
```
