# الحدود المعروفة / Known limitations

- Windows x64 Beta preview; the installer has no Authenticode publisher certificate. .NET is bundled; media conversion requires separate FFmpeg/FFprobe.
- Video, audio, still-image profiles and ordinary/AES ZIP are available. PDF/Office, OCR, other archive engines, recording, downloading and disc tools are not integrated.
- Codec/container and device compatibility apply. Complete multitrack, subtitles, animation, HDR or metadata preservation is not guaranteed.
- GPU support varies by hardware, driver and encoder. Short checks are not long-run stability or speed benchmarks.
- Acrylic and motion depend on Windows and accessibility preferences. Not all DPI, multi-monitor, touchpad or long-duration workloads are qualified.
- ZIP AES does not hide filenames. ZIP64/split archives and ZipCrypto are unsupported. For broad interoperability, test your chosen password with the receiving application; Unicode compatibility varies. Saved passwords are tied to the Windows account.
- Portable ZIP copies do not update in place. Restart for installation requires consent. A live GitHub-to-installed upgrade and automatic rollback remain unqualified.

هذه نسخة تجريبية. تختلف قدرات الترميز والتسريع والمظهر حسب الجهاز والمحرك وWindows. لا تُعمم نتائج عينة أو جهاز على كل الحالات. راجع [دليل التثبيت](INSTALL_0.9.md) و[مساعدة التحديث](UPDATE_TROUBLESHOOTING.md).
