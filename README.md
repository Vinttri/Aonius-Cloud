# Aonius Cloud

Приложение Aonius Cloud для облака: Talk, Почта, Файлы, Календарь в одном окне.
The Aonius Cloud app for the cloud: Talk, Mail, Files, Calendar in one window.

Установщики — в разделе [Releases](https://github.com/Vinttri/Aonius-Cloud/releases/latest).
Installers are under [Releases](https://github.com/Vinttri/Aonius-Cloud/releases/latest).

| Файл / File | Для чего / For |
|---|---|
| `Aonius Cloud … (Apple silicon).dmg` | Mac с процессором Apple (M1 и новее) / Macs with Apple chips |
| `Aonius Cloud … (Intel).dmg` | Mac с процессором Intel / Intel Macs |
| `Aonius-Cloud-Setup-…-x64.exe` | Windows 10/11, обычные компьютеры / most PCs |
| `Aonius-Cloud-Setup-…-arm64.exe` | Windows 11 на ARM / Windows 11 on ARM |
| `Aonius Cloud … (Android).apk` | Телефоны и планшеты Android / Android phones and tablets |

Приложение обновляется само: «Настройки приложения» → «Обновления». Список обновлений
(`updates.json`) подписан, и приложение ставит только файлы из подписанного списка с
совпадающей контрольной суммой (sha256).

The app updates itself: App Settings → Updates. The update list (`updates.json`) is signed,
and the app installs only files from the signed list whose sha256 matches.

iPhone: через TestFlight / via TestFlight.
