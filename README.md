# Leon & Fina – Veröffentlichungen

Dieses **öffentliche** Repository enthält ausschließlich fertige, geprüfte
Veröffentlichungen von „Leon & Fina“. Der Quellcode liegt im privaten
Repository `leon-und-fina`.

| Inhalt | Ort |
|---|---|
| Update-Manifest (nativ) | `releases/<version>/manifest.json` → als GitHub Release veröffentlicht |
| Feste Update-Adresse (Windows, macOS, Linux, Android, iOS) | `https://github.com/Mr-KinA/leon-und-fina-releases/releases/latest/download/manifest.json` |
| Feste Update-Adresse (Browser) | `https://mr-kina.github.io/leon-und-fina-releases/stable/manifest.json` |
| Inhaltspakete (Kapitel, Klassenstufen, Kosmetik) | Release-Dateien bzw. `pages/stable/pakete/` |
| Web-Version zum Testen | `https://mr-kina.github.io/leon-und-fina-releases/spiel/` |
| Öffentlicher Signaturschlüssel | `oeffentlicher_schluessel.pem` |

Jedes Manifest ist mit RSA-SHA256 signiert (`manifest.json.sig`). Das Spiel
akzeptiert nur Manifeste mit gültiger Signatur und Pakete, deren SHA-256 und
Größe exakt zum Manifest passen. Pakete enthalten nie Programmcode.

> Hinweis Prototyp: Die aktuellen Dateien sind mit einem **Testschlüssel**
> signiert. Vor der ersten echten Veröffentlichung wird ein neuer Schlüssel
> erzeugt und nur als GitHub-Secret hinterlegt.

Ablauf und Regeln: siehe `docs/RELEASE_PROCESS.md` im Quellcode-Repository.
