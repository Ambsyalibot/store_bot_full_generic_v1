النسخة الكاملة الأساسية - متجر تيليجرام عام للمنتجات والخدمات الرقمية المشروعة

الملفات:
- bot.py
- requirements.txt
- .replit

الإعدادات المطلوبة في Replit Secrets:
BOT_TOKEN=توكن البوت
ADMIN_ID=7007160064
SUPPORT_USERNAME=Dmaardone
RESERVE_MINUTES=5

مكان مفاتيح Binance لاحقًا:
Replit -> Tools -> Secrets

أضيفي هناك:
BINANCE_API_KEY=...
BINANCE_SECRET_KEY=...

ثم في أعلى bot.py ستجدين تعليقًا يوضح مكان قراءتها:
# BINANCE_API_KEY = os.getenv("BINANCE_API_KEY", "")
# BINANCE_SECRET_KEY = os.getenv("BINANCE_SECRET_KEY", "")

تشغيل محلي:
pip install -r requirements.txt
python bot.py
