# Music‑App

An **offline Android music player** written in **Kotlin** that lets you enjoy the songs stored on your device with a modern, Material‑You inspired interface.

---

## ⭐ Features

| Category                      | Highlights                                                                                                                     |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Core playback**             | • Play, pause, next, previous<br>• Shuffle & repeat modes<br>• Seek‑bar with exact scrubbing                                   |
| **Library**                   | • Scans local storage for audio (`.mp3`, `.wav`, etc.)<br>• Sort & filter by name, date added or file size<br>• Instant search |
| **Playlists & queue**         | • Create unlimited playlists, add / remove tracks<br>• "Play Next" queue management                                            |
| **Favourites**                | • One‑tap to add / remove favourite tracks                                                                                     |
| **Now Playing**               | • Expandable bottom‑sheet<br>• Album‑art blurred backdrop<br>• On‑screen volume & booster slider                               |
| **Notifications**             | • Media‑style notification with controls, album art and seek‑bar (Android 13 compatible)                                       |
| **Sleep timer**               | • Automatically stop playback after a set time                                                                                 |
| **Audio booster & equalizer** | • Built‑in 5‑band EQ and bass‑boost for wired / Bluetooth output                                                               |
| **Settings**                  | • Choose accent gradient<br>• Enable/disable animations & haptics                                                              |

<sup>Icons and layouts for favourites, equalizer, booster, timer, playlist, search and more can be seen in the `drawable/` and `layout/` resources in the repository.([github.com](https://github.com/akshat-2411/Music-App/commit/f2e826dfe8079f2305488c2a2c9f6438bbca35c3))</sup>

---

## 📸 Screenshots

The `music_player_screenshots/` folder contains high‑resolution previews of the main screens. Feel free to add them here once GitHub renders the images. ([github.com](https://github.com/akshat-2411/Music-App/tree/main/music_player_screenshots))

---

## 🏗️ Built With

* **Kotlin** – 100 % of the codebase
* **Android Jetpack** (AppCompat, RecyclerView, ViewBinding, MediaSession)
* **Material Components** for Material 3 design
* **MediaPlayer API** for audio playback (replaceable with ExoPlayer)
* **Glide** for fast album‑art loading

---

## 🚀 Getting Started

1. **Clone** the repo

   ```bash
   git clone https://github.com/akshat-2411/Music-App.git
   ```
2. **Open** the project in **Android Studio Flamingo** (or newer).
3. Let Gradle sync and download dependencies.
4. **Run** on an Android device or emulator (minSdk ≈ 21).

> **Tip:** If you hit a *“Missing `MEDIA_CONTENT_CONTROL` permission”* error on Android 13+, grant the **Notification** permission from system settings.

---

## 🧑‍💻 Contributing

Pull requests are welcome! If you’d like to:

1. **Fork** the project & create your feature branch.
2. Commit your changes with clear messages.
3. **Open** a pull request describing what you’ve changed.

Please keep code style consistent and run *ktlint* before pushing.

---

## 📜 License

Distributed under the **GPL‑3.0** license. See [`LICENSE`](LICENSE) for more information.

---

> *Made with ❤️ by [Akshat Sharma](https://github.com/akshat-2411)*
