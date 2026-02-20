# Template ระบบ opencode-line-playground สำหรับ วิจัย/พัฒนา ผ่าน OpenCode LINE Bot

## 🎯 Best Practice

### 1 Repo → 1 LINE Group
- สร้าง 1 GitHub repo ต่อ 1 LINE Group
- เชิญ member ทุกคนเข้า group
- เชิญ LINE OA `@onboard-opencode` (https://line.me/ti/p/@525vvsgv) เข้า group ด้วย

## 📋 วิธีใช้งาน

### 1. สร้าง Project ใหม่
ส่ง prompt นี้ให้ OpenCode LINE Bot:

```
ช่วยสร้าง repo ใหม่โดยใช้ template จาก 
monthop-gmail/opencode-line-playground-template-000 เป็นแนวทาง

1. สร้าง GitHub repo ชื่อ opencode-line-playground-001
2. Copy workflows จาก template
3. ตั้งค่า branch protection
4. Deploy ไป Cloudflare Pages
```

### 2. ขั้นตอนหลังได้ Repo
```
1. สร้าง Cloudflare Pages project ใหม่ (ชื่อเดียวกับ repo)
2. เพิ่ม secrets CF_API_TOKEN, CF_ACCOUNT_ID ใน repo
3. Clone repo → เขียน code → Push → Auto deploy!
```

### 3. Workflow การทำงานใน Repo
```
1. สร้าง issue ใน repo
2. สร้าง branch จาก issue
3. เขียน code ใน branch
4. สร้าง PR (อย่าลืม link issue เช่น closes #123)
5. รอ CI pass + approval
6. Merge → Auto deploy ไป Cloudflare Pages
```

## 🔄 CI/CD
- **CI**: ต้อง link issue ใน PR
- **Deploy**: Auto deploy หลัง push main

## 📞 ติดต่อ
https://github.com/monthop-gmail/opencode-line/issues

