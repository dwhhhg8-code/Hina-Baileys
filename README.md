<div align="center">

<img src="https://put.icu/s/qoqrh1yb.jpg" height="120" />

# ᯓ★ Hina Baileys ᯓ★

**مكتبة واتساب (WhatsApp Web) — نسخة ᯓ★ Hina ᯓ★**

![version](https://img.shields.io/badge/version-7.0.0--rc14-25D366)
![license](https://img.shields.io/badge/license-MIT-blue)
![node](https://img.shields.io/badge/node-%3E%3D20-339933)

</div>

---

<div dir="rtl">

## 📌 إيه دي؟

نسخة من مكتبة **Baileys** — المكتبة اللي بتتكلم مع **WhatsApp Web** عن طريق WebSocket — مخصصة ومظبوطة لبوت **ᯓ★ Hina ᯓ★**.

| | |
|---|---|
| **الأصل** | [WhiskeySockets/Baileys](https://github.com/WhiskeySockets/Baileys) @ `v7.0.0-rc14` |
| **الفرع** | `hina` |
| **الحقوق** | © 𝐡𝐚𝐢𝐭𝐡𝐚𝐦 — ᯓ★ Hina ᯓ★ (التعديلات) · Rajeh Taher / WhiskeySockets (الأصل) |
| **الترخيص** | MIT |

---

## ⚡ التثبيت

```json
{
  "dependencies": {
    "@whiskeysockets/baileys": "github:dwhhhg8-code/Hina-Baileys#hina"
  }
}
```

```bash
npm install
```

> `lib/` **مبني وجاهز جوه الريبو** — مفيش `build` وقت التثبيت، فالتثبيت سريع ومستقر.
>
> لو الاستضافة بتمنع `git`، استخدم لينك الأرشيف:
> `https://github.com/dwhhhg8-code/Hina-Baileys/archive/refs/heads/hina.tar.gz`

---

## 🔧 التطوير

```bash
git clone https://github.com/dwhhhg8-code/Hina-Baileys.git
cd Hina-Baileys
npm install
npm run build          # بعد أي تعديل في src/ أو WAProto/
```

> **مهم:** بعد `npm run build` اعمل `git add lib && git commit` — التثبيت بيعتمد على `lib/` المرفوع.
>
> عشان كده شيلنا `prepare` و `prepack` من `package.json`.

---

## 🧩 استخدام سريع

```js
import makeWASocket, { useMultiFileAuthState } from '@whiskeysockets/baileys'

const { state, saveCreds } = await useMultiFileAuthState('session')
const sock = makeWASocket({ auth: state, printQRInTerminal: true })
sock.ev.on('creds.update', saveCreds)
```

---

## 🔗 لينكات

| | |
|---|---|
| 💬 واتساب | [wa.me/201125166486](https://wa.me/201125166486) |
| ✈️ تليجرام | [t.me/haitham_hina26](https://t.me/haitham_hina26) |
| 🐙 جيتهاب | [github.com/hhgdwh40-maker](https://github.com/hhgdwh40-maker) |
| 📢 قناة البوت | [whatsapp.com/channel/0029Vb8QIpSJ3juu0VHRyU0v](https://whatsapp.com/channel/0029Vb8QIpSJ3juu0VHRyU0v) |

---

## 📄 الترخيص

MIT — الأصل لـ **Rajeh Taher / WhiskeySockets**، والتعديلات والبناء لـ **𝐡𝐚𝐢𝐭𝐡𝐚𝐦 — ᯓ★ Hina ᯓ★**.

<div align="center">© 𝐡𝐚𝐢𝐭𝐡𝐚𝐦 - ᯓ★ Hina ᯓ★</div>
راجع ملف [LICENSE](./LICENSE).

</div>
