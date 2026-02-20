# Template ระบบ opencode-line-playground สำหรับ วิจัย/พัฒนา ผ่าน OpenCode LINE Bot

## 🎯 Best Practice

### 1 Repo → 1 LINE Group
- สร้าง 1 GitHub repo ต่อ 1 LINE Group
- เชิญ member ทุกคนเข้า group
- เชิญ LINE OA `@onboard-opencode` (https://line.me/ti/p/@525vvsgv) เข้า group ด้วย

### Workflow
```
1. สร้าง issue ใน repo
2. สร้าง branch จาก issue
3. เขียน code ใน branch
4. สร้าง PR (อย่าลืม link issue เช่น closes #123)
5. รอ CI pass + approval
6. Merge → Auto deploy ไป Cloudflare Pages
```

## 🚀 Quick Start

```bash
git clone https://github.com/monthop-gmail/opencode-line-playground-template-000.git
cd opencode-line-playground-template-000
# เขียน code ของคุณ
git add . && git commit -m "Add my bot" && git push origin main
```

## 🔄 CI/CD
- **CI**: ต้อง link issue ใน PR
- **Deploy**: Auto deploy หลัง push main

## 📞 ติดต่อ
https://github.com/monthop-gmail/opencode-line/issues

