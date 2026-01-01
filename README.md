# Notejot

___Jot your ideas___

A stupidly-simple notes application for any type of short term notes or ideas.

- 🟡 Color your notes in 8 different colors
- 📓 Classify them in notebooks
- 🔤 Format text to your liking
- 📌 Pin your most important ones

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.github.lainsce.Notejot
flatpak run io.github.lainsce.Notejot
```

## Building

```
git clone git@github.com:flathub/io.github.lainsce.Notejot.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.lainsce.Notejot.json
```

---

**Technologies**: GNOME, GTK4, Vala, Libhelium
