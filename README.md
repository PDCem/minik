<div align="center">

<img src="docs/clips/tanz_tiktok.gif" width="260" alt="Minik tanzt">

# Minik

### 🚧 Kommt bald

**Ein kleines Hologramm für deinen Tisch.**<br>
Er sieht dich, hört dir zu, redet mit dir und merkt sich, wer du bist.

![Status](docs/badges/status.svg)
![Android](docs/badges/android.svg)
![Gemini Live](docs/badges/gemini.svg)
![Lizenz](docs/badges/lizenz.svg)

</div>

---

## Ein Tag mit Minik

Wenn gerade niemand mit ihm spricht, beschäftigt sich Minik selbst. Jede Szene ist ein kurzer Clip, der nahtlos in den nächsten übergeht.

<table>
  <tr>
    <td align="center"><img src="docs/clips/idle_dj.gif" width="200" alt="Minik am Mischpult"><br><b>Am Mischpult</b></td>
    <td align="center"><img src="docs/clips/idle_astronaut.gif" width="200" alt="Minik als Astronaut"><br><b>Schwerelos</b></td>
    <td align="center"><img src="docs/clips/idle_held.gif" width="200" alt="Minik als Held"><br><b>Kleiner Held</b></td>
  </tr>
  <tr>
    <td align="center"><img src="docs/clips/idle_licht.gif" width="200" alt="Minik mit Licht"><br><b>Ein Licht in der Hand</b></td>
    <td align="center"><img src="docs/clips/tanz_bauchtanz.gif" width="200" alt="Minik beim Bauchtanz"><br><b>Bauchtanz</b></td>
    <td align="center"><img src="docs/clips/zuhoeren.gif" width="200" alt="Minik hört zu"><br><b>Hört dir zu</b></td>
  </tr>
</table>

## Was er kann

- 👂 **Wacht bei „Minik“ auf.** Das Weckwort erkennt er direkt auf dem Handy.
- 💬 **Spricht Deutsch und Türkisch.** Natürlich und ohne Wartezeit über Gemini Live.
- 👀 **Erkennt Gesichter.** Er weiß, wer vor ihm steht, und begrüßt jeden mit Namen.
- 🎙️ **Weiß, wer spricht.** Auch wenn mehrere Leute im Raum sind.
- 📒 **Eine Akte für jeden.** Geburtstage, Lieblingsessen, was gestern war.
- 🌙 **Lernt nachts dazu.** Aus den Gesprächen des Tages schreibt er Neues in seine Akten.
- 📰 **Kennt die Nachrichten.** Er sucht aktuell im Netz, wenn du etwas wissen willst.
- 😴 **Geht schlafen.** „Geh schlafen“ genügt. App zu heißt: Minik ist aus und hört nicht mehr zu.

## Schnellstart

> [!NOTE]
> Minik ist noch in Arbeit. Die erste APK erscheint hier unter **Releases**.

1. APK aus den Releases laden und auf dem Android-Handy installieren.
2. Einen eigenen Gemini-Schlüssel aus [Google AI Studio](https://aistudio.google.com/apikey) eintragen.
3. Minik startet ohne Vorwissen, fragt nach deinem Namen und lernt dich ab da kennen.

Kein Konto, kein Server, kein Abo. Erkennen, Zuhören und Erinnern passieren auf deinem Handy.

## So funktioniert er

```
Kamera ─► Gesicht erkennen (ML Kit + MobileFaceNet)  ─┐
Mikro  ─► Weckwort + Stimme (sherpa-onnx)            ─┼─► Gemini Live ─► Minik spricht + Clip
Akten  ─► lokale Datenbank auf dem Handy             ─┘
```

## Fahrplan

- [ ] Android-App: Gespräch, Weckwort, Gesicht, Stimme, Akten
- [ ] Erste APK in den Releases
- [ ] Minik auf dem Desktop: Figur ohne Hintergrund für Windows, Mac und Linux

## Lizenz

Open Source. Die genaue Lizenz folgt mit der ersten Version.
