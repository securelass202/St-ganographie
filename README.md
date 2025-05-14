# 🕵️‍♀️ Introduction à la Stéganographie

La **stéganographie** est une technique qui permet de **cacher un message ou des données à l’intérieur d’un autre fichier** (comme une image, une vidéo, un son ou un texte), de manière à ce que personne ne soupçonne l’existence de ce message.

---

## 🎯 Différence entre Cryptographie et Stéganographie

| Cryptographie 🔐 | Stéganographie 🕵️‍♀️ |
|------------------|------------------------|
| Chiffre le **contenu** du message | Cache **l’existence** du message |
| Le message est visible, mais illisible sans clé | Le message est totalement invisible |
| Utilise des algorithmes comme AES, RSA, etc. | Utilise des supports comme images, sons, etc. |

---

## 🖼️ Exemple simple

Prenons une image au format `.jpg`. En modifiant légèrement les **bits peu significatifs (LSB)** de certains pixels, on peut y cacher un message texte.  
➡️ À l’œil nu, l’image semble identique. Mais avec les bons outils, on peut extraire le message caché.

---

## 🧰 Outils utiles pour la stéganographie

| Outil | Utilité |
|-------|--------|
| `steghide` | Cacher/extraire des fichiers dans des images ou sons |
| `zsteg` | Cacher/extraire des données dans des images PNG |
| `ExifTool` | Voir ou modifier les métadonnées d'un fichier |
| `OpenStego` | Interface simple pour cacher des données dans des images |
| `Binwalk` | Analyser les fichiers binaires pour y détecter des données cachées |

---

## 🛡️ Importance en Cybersécurité

- Les attaquants peuvent cacher des **commandes malveillantes** dans des fichiers apparemment inoffensifs.
- Des données confidentielles peuvent être **exfiltrées discrètement** via des images ou des sons.
- Lors de **CTF (Capture The Flag)** ou de tests d’intrusion, la stéganographie est une technique couramment utilisée.

---

## 💡 Envie de t’exercer ?

Voici quelques plateformes où tu peux essayer la stéganographie :
- [TryHackMe](https://tryhackme.com)
- [HackTheBox](https://hackthebox.com)
- [CTFlearn](https://ctflearn.com)

---

🔐 *Comprendre la stéganographie, c’est comprendre une des techniques les plus subtiles de l’ingénierie de l’ombre.*  

![Image](https://github.com/user-attachments/assets/99ce0db6-5856-4bb6-96ab-7d07e37755a6)
