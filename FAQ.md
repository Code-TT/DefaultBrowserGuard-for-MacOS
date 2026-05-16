# Frequently Asked Questions (FAQ)

## Why does macOS reset my default apps?

macOS occasionally has problems permanently saving third-party apps as default. This is especially common after full restarts – when the Mac was shut down and boots up again – causing the system to revert to Safari and Apple Mail. Waking from standby or sleep mode usually does not trigger this. Intentional or not – annoying either way. DefaultBrowserGuard monitors this setting and warns you immediately.

## What does DefaultBrowserGuard cost?

DefaultBrowserGuard is currently **100% free** to use. There are no hidden subscriptions or in-app purchases.

If you like the app, feel free to voluntarily give a small tip via [Buy Me a Coffee](https://buymeacoffee.com/trella).

## Does the app slow down my Mac?

No. The app is extremely lightweight and consumes virtually no CPU or RAM resources. It runs unobtrusively in the background in your menu bar.

## Which macOS versions are supported?

DefaultBrowserGuard requires **macOS 14.6 or newer** and runs natively on Apple Silicon (M1-M5) as well as Intel Macs.

## What happens to my data?

Your privacy is important to us. DefaultBrowserGuard only collects completely anonymous, non-traceable analytics data via aptabase.com to improve the app. No personal data, IP addresses or content is collected.

## Does it work with my browser / email client?

Very likely. We support Safari, Chrome, Firefox, Edge, Brave, Arc, Opera, Vivaldi, DuckDuckGo, Orion as well as Apple Mail, Outlook, Thunderbird, Betterbird, Spark, Airmail, Canary Mail, Mimestream and many more.

## Why isn't the app on the App Store?

Sometimes the best things need their own path. A direct download gives us more freedom for updates, features, and fair pricing – and gives you full control over your software.

## Why does macOS show a warning when opening the app?

macOS Gatekeeper blocks apps without a paid Apple signature. This is a standard security feature, not a malware warning. A single click on "Open" in the dialog or a quick Terminal command is enough:

```bash
xattr -d com.apple.quarantine /Applications/DefaultBrowserGuard.app
```

## Is the app really safe if it's not signed?

Yes. "Not signed" simply means there is no paid Apple Developer certificate – it does not mean the app is harmful. DefaultBrowserGuard runs exclusively locally on your Mac.

## Can I open the app without the Terminal?

Yes – on older macOS versions, a right-click (or Ctrl+click) on the app → "Open" is enough. The dialog will then show an "Open" button despite the warning. Starting with macOS Sequoia, this sometimes no longer works, leaving only the Terminal command.

## Do I have to repeat the Terminal command after every update?

Yes. Every time a new version is downloaded, macOS re-marks the file with the quarantine flag. The command must therefore be run once per download.

## How do I change the default browser on Mac?

Open System Settings and go to "Desktop & Dock" → "Default web browser". There you select your preferred browser. Problem: macOS often resets this setting back to Safari after restarts or updates.

## How do I change the default email client on Mac?

To change the default email client, you must open the Apple Mail app, then go to Settings → General and select your desired client under "Default email reader". Yes, even if you don't want to use Apple Mail, you have to open the app for this. Or simply use DefaultBrowserGuard and change the default email client centrally with one click.

## Are default apps reset after a macOS update?

Yes, unfortunately this is a common problem. Many users report that after every macOS update, Safari is set as the default browser and Apple Mail as the default email client again – without warning and without asking.

## What to do when Chrome is no longer the default browser?

Go to System Settings → "Desktop & Dock" → "Default web browser" and select Chrome again. So you don't have to repeat this after every restart, DefaultBrowserGuard monitors your setting and automatically restores Chrome.

## Do I need DefaultBrowserGuard for Arc, Brave, or Opera?

Yes, all browsers are affected – whether Chrome, Firefox, Edge, Brave, Arc, Opera, or Vivaldi. As soon as it's not an Apple-owned browser, macOS can reset the setting after restarts or updates.

---

[More questions? Report an issue](../../issues)
