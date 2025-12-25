<div align="center">
	<a href="https://go.warp.dev/yazi" target="_blank">
		<sup>تشکر ویژه از:</sup>
		<br>
		<img alt="Warp sponsorship" width="400" src="https://github.com/warpdotdev/brand-assets/blob/main/Github/Sponsor/Warp-Github-LG-02.png">
		<br>
		<h>Warp، ساخته شده برای برنامه‌نویسی با چند عامل هوش مصنوعی</b>
		<br>
		<sup>موجود برای macOS، لینوکس و ویندوز</sup>
	</a>
</div>

<br>

## Yazi - ⚡️ مدیریت فایل ترمینال فوق‌العاده سریع

Yazi (به معنی «اردک») یک مدیریت فایل ترمینال نوشته شده با Rust است که بر اساس I/O غیرمسدودکننده (async) طراحی شده است. هدف آن ارائه تجربه‌ای کارآمد، کاربرپسند و قابل تنظیم برای مدیریت فایل‌ها است.

💡 مقاله جدیدی که عملکرد داخلی آن را توضیح می‌دهد: [چرا Yazi سریع است؟](https://yazi-rs.github.io/blog/why-is-yazi-fast)

* 🚀 **پشتیبانی کامل از Async**: همه عملیات I/O به صورت غیرهمزمان انجام می‌شوند و وظایف CPU در چندین رشته پخش می‌شوند تا بیشترین بهره از منابع گرفته شود.
* 💪 **زمان‌بندی و مدیریت قدرتمند وظایف Async**: ارائه به‌روزرسانی پیشرفت بلادرنگ، لغو وظایف و اختصاص اولویت داخلی برای وظایف.
* 🖼️ **پشتیبانی داخلی از چند پروتکل تصویر**: همچنین با Überzug++ و Chafa یکپارچه شده، تقریباً تمام ترمینال‌ها را پوشش می‌دهد.
* 🌟 **هایلایت کد و دیکد تصاویر داخلی**: همراه با مکانیزم پیش‌بارگذاری، بارگذاری تصاویر و فایل‌های عادی را بسیار سریع می‌کند.
* 🔌 **سیستم افزونه همزمان**: افزونه‌های رابط کاربری، افزونه‌های عملکردی، پیش‌نمایش‌دهنده/پیش‌بارگذار/جستجوگر/دریافت‌کننده سفارشی؛ تنها بخش‌هایی از Lua.
* 📡 **سرویس توزیع داده‌ها**: بر پایه معماری کلاینت-سرور (بدون نیاز به فرآیند سرور اضافی)، با مدل انتشار-اشتراک مبتنی بر Lua، ارتباط بین نمونه‌ها و پایداری وضعیت.
* 📦 **مدیریت بسته‌ها**: نصب افزونه‌ها و تم‌ها با یک دستور، به‌روزرسانی خودکار یا قفل کردن نسخه مشخص.
* 🧰 ادغام با ripgrep، fd، fzf، zoxide
* 💫 اجزای ورودی/pick/confirm/which/notify مشابه Vim، تکمیل خودکار مسیرهای cd
* 🏷️ پشتیبانی چند تب، انتخاب بین دایرکتوری‌ها، پیش‌نمایش قابل اسکرول (برای ویدئو، PDF، آرشیو، کد، دایرکتوری‌ها و غیره)
* 🔄 تغییر نام دسته‌ای، استخراج آرشیو، حالت تصویری، انتخاب‌کننده فایل، [ادغام با Git](https://github.com/yazi-rs/plugins/tree/main/git.yazi)، [مدیریت مانت](https://github.com/yazi-rs/plugins/tree/main/mount.yazi)
* 🎨 سیستم تم، پشتیبانی از ماوس، سطل زباله، طرح‌بندی سفارشی، سیستم فایل مجازی، CSI u، OSC 52
* ... و بیشتر!

[https://github.com/sxyazi/yazi/assets/17523360/92ff23fa-0cd5-4f04-b387-894c12265cc7](https://github.com/sxyazi/yazi/assets/17523360/92ff23fa-0cd5-4f04-b387-894c12265cc7)

## وضعیت پروژه

نسخه بتای عمومی، قابل استفاده به عنوان ابزار روزانه.

Yazi در حال حاضر در توسعه سنگین است و انتظار تغییرات شکسته‌کننده داشته باشید.

## مستندات

* استفاده: [https://yazi-rs.github.io/docs/installation](https://yazi-rs.github.io/docs/installation)
* ویژگی‌ها: [https://yazi-rs.github.io/features](https://yazi-rs.github.io/features)

## بحث و گفتگو

* سرور Discord (به زبان انگلیسی): [https://discord.gg/qfADduSdJu](https://discord.gg/qfADduSdJu)
* گروه تلگرام (به زبان چینی): [https://t.me/yazi_rs](https://t.me/yazi_rs)

## پیش‌نمایش تصویر

| پلتفرم                                                                       | پروتکل                                 | پشتیبانی                               |
| ---------------------------------------------------------------------------- | -------------------------------------- | -------------------------------------- |
| [kitty](https://github.com/kovidgoyal/kitty) (>= 0.28.0)                     | [Kitty unicode placeholders][kgp]      | ✅ داخلی                                |
| [iTerm2](https://iterm2.com)                                                 | [Inline images protocol][iip]          | ✅ داخلی                                |
| [WezTerm](https://github.com/wez/wezterm)                                    | [Inline images protocol][iip]          | ✅ داخلی                                |
| [Konsole](https://invent.kde.org/utilities/konsole)                          | [Kitty old protocol][kgp-old]          | ✅ داخلی                                |
| [foot](https://codeberg.org/dnkl/foot)                                       | [Sixel graphics format][sixel]         | ✅ داخلی                                |
| [Ghostty](https://github.com/ghostty-org/ghostty)                            | [Kitty unicode placeholders][kgp]      | ✅ داخلی                                |
| [Windows Terminal](https://github.com/microsoft/terminal) (>= v1.22.10352.0) | [Sixel graphics format][sixel]         | ✅ داخلی                                |
| [st with Sixel patch](https://github.com/bakkeby/st-flexipatch)              | [Sixel graphics format][sixel]         | ✅ داخلی                                |
| [Warp](https://www.warp.dev) (macOS/Linux فقط)                               | [Inline images protocol][iip]          | ✅ داخلی                                |
| [Tabby](https://github.com/Eugeny/tabby)                                     | [Inline images protocol][iip]          | ✅ داخلی                                |
| [VSCode](https://github.com/microsoft/vscode)                                | [Inline images protocol][iip]          | ✅ داخلی                                |
| [Rio](https://github.com/raphamorim/rio)                                     | [Inline images protocol][iip]          | ❌ تصاویر با اندازه اشتباه رندر می‌شوند |
| [Black Box](https://gitlab.gnome.org/raggesilver/blackbox)                   | [Sixel graphics format][sixel]         | ✅ داخلی                                |
| [Bobcat](https://github.com/ismail-yilmaz/Bobcat)                            | [Inline images protocol][iip]          | ✅ داخلی                                |
| X11 / Wayland                                                                | پروتکل سیستم پنجره                     | ☑️ [Überzug++][ueberzug] لازم است      |
| Fallback                                                                     | [ASCII art (Unicode block)][ascii-art] | ☑️ [Chafa][chafa] لازم است             |

جزئیات در: [https://yazi-rs.github.io/docs/image-preview](https://yazi-rs.github.io/docs/image-preview)

<!-- Protocols -->

[kgp]: https://sw.kovidgoyal.net/kitty/graphics-protocol/#unicode-placeholders
[kgp-old]: https://github.com/sxyazi/yazi/blob/main/yazi-adapter/src/drivers/kgp_old.rs
[iip]: https://iterm2.com/documentation-images.html
[sixel]: https://www.vt100.net/docs/vt3xx-gp/chapter14.html
[ascii-art]: https://en.wikipedia.org/wiki/ASCII_art

<!-- Dependencies -->

[ueberzug]: https://github.com/jstkdng/ueberzugpp
[chafa]: https://hpjansson.org/chafa/

## تشکر ویژه

<img alt="RustRover logo" align="right" width="200" src="https://resources.jetbrains.com/storage/products/company/brand/logos/RustRover.svg">

تشکر از تیم RustRover برای ارائه مجوزهای متن‌باز جهت حمایت از نگهداری Yazi.

مشارکت‌کنندگان فعال می‌توانند با @sxyazi تماس بگیرند تا در صورت موجود بودن، مجوز دریافت کنند.

## مجوز

Yazi تحت مجوز MIT است. برای اطلاعات بیشتر فایل [LICENSE](LICENSE) را بررسی کنید.
