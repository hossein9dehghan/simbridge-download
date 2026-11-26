<p align="center"><img src="icon.png" width="96" alt=""></p>

<h1 align="center">SimBridge</h1>

<p align="center">Use the number of one phone on another. An Android phone with a SIM becomes the second line of your iPhone or of a second Android phone, over Bluetooth and Wi‑Fi. No internet, no server, no account, no root.</p>

<p align="center">
<a href="https://hossein9dehghan.github.io/simbridge-download/"><b>Install page</b></a> ·
<a href="../../releases/latest"><b>Download</b></a> ·
<a href="#فارسی"><b>فارسی</b></a>
</p>

---

## What it does

- **Calls:** ring, answer, decline and talk on your iPhone or second Android phone. The Android phone with the SIM stays silent and dark, like a phone with a Bluetooth headset.
- **Messages:** SMS and MMS both ways, with read state and deleting kept in step.
- **Contacts and call history** of the phone with the SIM.
- **The SIM phone itself:** airplane mode, mobile data, Wi‑Fi, ringer and more, from the other phone. Also internet sharing, USSD codes, ringing a lost phone, and mirrored notifications.
- **Private by design:** everything stays on your two phones. Nothing goes through the internet.

## What you need

| Device | Needs |
|---|---|
| Phone with the SIM | Android 8 or later. Call sound on the other phone needs **Android 11 or later** and a Wi‑Fi network for the one-time setup. |
| iPhone or iPad | iOS 26 or later, and SideStore, AltStore or Sideloadly (free, with your own Apple ID). |
| Or a second Android phone | Android 8 or later. Call sound over Bluetooth needs Android 10 or later. |

## Install

The easiest way is the **[install page](https://hossein9dehghan.github.io/simbridge-download/)**. Open it on each phone. The files are also in **[Releases](../../releases/latest)**.

### 1. The Android phone with the SIM

1. Download `SimBridge-android-*.apk` on that phone and open it. Allow installing from this source. Play Protect may warn about an app it doesn't know.
2. Open SimBridge and choose **This phone has the SIM**.
3. Follow the four setup steps: **Permissions**, **Turn it on**, **Pair your other phone**, **Call audio**.
4. Set SimBridge's battery use to **Unrestricted**, so Android doesn't stop it while the phone sleeps.

**Call audio** (Android 11 or later): SimBridge starts a small helper through Android's own *Wireless debugging*. It needs Developer options on and a Wi‑Fi network, once. The app shows each step. Messages and ringing work without it.

### 2a. iPhone or iPad

1. Set up **SideStore** once: **[step-by-step guide](https://hossein9dehghan.github.io/simbridge-download/sidestore.html)** (needs a computer and a cable once, about 15 minutes). It signs apps with your Apple ID on the iPhone itself. AltStore or Sideloadly work too.
2. Add this source to SideStore or AltStore, then install SimBridge from it:
   ```
   https://hossein9dehghan.github.io/simbridge-download/source.json
   ```
   Or install the `.ipa` file from Releases with Sideloadly.
3. Turn on **Settings › Privacy & Security › Developer Mode**.
4. Open SimBridge and scan the code shown on the Android phone.

### 2b. Or a second Android phone

1. Install the same Android file and choose **This is the second phone**.
2. Scan the code shown on the phone with the SIM.

## Good to know

- With a free Apple ID an app runs for **7 days**. SideStore renews it on the iPhone while it is on Wi‑Fi. A separate Apple ID for this is the safer choice, and never give its password to anybody.
- **Emergency calls:** always use a phone itself, never SimBridge.
- Check the files with `SHA256SUMS.txt` (`shasum -a 256 -c SHA256SUMS.txt`).
- This is an early version (0.1). Please report problems in [Issues](../../issues).

---

<div dir="rtl" lang="fa">

## فارسی

**SimBridge** شماره‌ی یک گوشی را روی گوشی دیگر می‌آورد. گوشی اندروید سیم‌کارت‌دار، از راه بلوتوث و Wi‑Fi، خط دوم آیفون یا گوشی اندروید دوم شما می‌شود. بدون اینترنت، بدون سرور، بدون حساب و بدون روت.

**[صفحه‌ی نصب](https://hossein9dehghan.github.io/simbridge-download/)** · **[دانلود](../../releases/latest)**

### چه می‌کند

- **تماس:** زنگ، جواب، رد و صحبت روی آیفون یا گوشی دوم. گوشی سیم‌کارت‌دار ساکت و تاریک می‌ماند، مثل وقتی هدست بلوتوث وصل است.
- **پیامک و MMS** در هر دو جهت. خوانده‌شدن و پاک‌شدن پیام‌ها روی هر دو گوشی یکی می‌ماند.
- **مخاطبین و سابقه‌ی تماس** گوشی سیم‌کارت‌دار.
- **کنترل گوشی سیم‌کارت‌دار از گوشی دیگر:** حالت هواپیما، داده، Wi‑Fi، زنگ و… . همچنین اشتراک اینترنت، کدهای USSD، زنگ زدن به گوشی گم‌شده و آینه‌ی اعلان‌ها.
- **حریم خصوصی:** همه‌چیز فقط روی دو گوشی شما می‌ماند و چیزی از اینترنت رد نمی‌شود.

### چه لازم است

- **گوشی سیم‌کارت‌دار:** اندروید ۸ یا جدیدتر. صدای تماس روی گوشی دیگر **اندروید ۱۱ یا جدیدتر** می‌خواهد، و برای راه‌اندازی یک‌باره یک شبکه‌ی Wi‑Fi.
- **آیفون یا آیپد:** iOS 26 یا جدیدتر، و SideStore، AltStore یا Sideloadly (رایگان، با Apple ID خودتان).
- **یا یک گوشی اندروید دوم:** اندروید ۸ یا جدیدتر. صدای تماس از راه بلوتوث اندروید ۱۰ یا جدیدتر می‌خواهد.

### نصب

ساده‌ترین راه **[صفحه‌ی نصب](https://hossein9dehghan.github.io/simbridge-download/)** است. آن را روی هر گوشی باز کنید. فایل‌ها در بخش **[Releases](../../releases/latest)** هم هستند.

**۱. گوشی اندروید سیم‌کارت‌دار**
1. فایل `SimBridge-android-*.apk` را روی همان گوشی دانلود و باز کنید. نصب از این منبع را اجازه دهید. ممکن است Play Protect درباره‌ی برنامه‌ی ناآشنا هشدار بدهد.
2. SimBridge را باز کنید و «این گوشی سیم‌کارت دارد» را انتخاب کنید.
3. چهار قدم راه‌اندازی را بروید: مجوزها، روشن کردن، جفت کردن گوشی دیگر، صدای تماس.
4. مصرف باتری SimBridge را «نامحدود» کنید تا اندروید در خواب گوشی متوقفش نکند.

**صدای تماس** (اندروید ۱۱ یا جدیدتر): SimBridge یک کمک‌برنامه‌ی کوچک را از راه «اشکال‌زدایی بی‌سیم» خود اندروید روشن می‌کند. برای این کار گزینه‌های برنامه‌نویس باید روشن باشد و یک بار به Wi‑Fi نیاز است. خود برنامه قدم‌به‌قدم راهنمایی می‌کند. پیامک و زنگ بدون آن هم کار می‌کنند.

**۲. آیفون یا آیپد**
1. **SideStore** را یک بار راه بیندازید: **[آموزش قدم‌به‌قدم](https://hossein9dehghan.github.io/simbridge-download/sidestore.html)** (فقط یک بار کامپیوتر و کابل لازم است، حدود ۱۵ دقیقه). برنامه‌ها را با Apple ID شما روی خود آیفون امضا می‌کند. AltStore یا Sideloadly هم کار می‌کنند.
2. این منبع را به SideStore یا AltStore اضافه کنید و SimBridge را از آن نصب کنید:
   `https://hossein9dehghan.github.io/simbridge-download/source.json`
   یا فایل `.ipa` را از Releases با Sideloadly نصب کنید.
3. در Settings › Privacy & Security، گزینه‌ی **Developer Mode** را روشن کنید.
4. SimBridge را باز کنید و کدی را که گوشی اندروید نشان می‌دهد اسکن کنید.

**یا گوشی اندروید دوم:** همان فایل اندروید را نصب کنید، «این گوشی دوم است» را انتخاب کنید و کد گوشی سیم‌کارت‌دار را اسکن کنید.

### خوب است بدانید

- با Apple ID رایگان برنامه **۷ روز** کار می‌کند. SideStore وقتی آیفون به Wi‑Fi وصل باشد تمدیدش می‌کند. بهتر است برای این کار یک Apple ID جدا بسازید و رمزش را به هیچ‌کس ندهید.
- **تماس اضطراری** را همیشه از خود گوشی بگیرید، نه از SimBridge.
- درستی فایل‌ها را با `SHA256SUMS.txt` بررسی کنید.
- این نسخه‌ی اولیه (0.1) است. مشکلات را در [Issues](../../issues) بنویسید.

</div>
