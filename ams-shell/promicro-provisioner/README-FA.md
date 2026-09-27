# Pro Micro Provisioner
ابزار مستقل ویندوز برای ATmega32U4 Pro Micro 5V/16MHz. برنامه هویت آموزشی تصادفی می‌سازد، ARM 2.8.2 را با `ams_key.h` محلی کامپایل می‌کند، ArduinoISP را با handshake واقعی STK500 پیدا می‌کند، یک‌بار erase انجام می‌دهد و سپس Application و Caterina سفارشی را می‌نویسد و Verify می‌کند.

`ams_key.h` عمداً در مخزن نیست و باید هنگام اجرا انتخاب شود. VID/PIDهای آزمایشی برای استفاده خصوصی کلاس هستند.
