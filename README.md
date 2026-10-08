# 🎮 MatArcade - 9. Sınıf Maarif Modeli Matematik Platformu

> **2026-2027 Yeni Müfredat (Türkiye Yüzyılı Maarif Modeli)** odaklı, öğrencilerin bayılarak oynayacağı, sıkıcı test formatından tamamen arındırılmış, 60 FPS HTML5 Canvas ve Fizik motorlarıyla donatılmış, mobil öncelikli (mobile-first) tek sayfalık Web & PWA Uygulaması.

---

## 🎨 Tasarım Dili ve Mimarisi
- **iOS 18 & Clean FinTech Estetiği:** Kirli beyaz, buz mavisi ve lila yumuşak geçişler (`#f8fafc` ➔ `#f1f5f9` ➔ `#e2e8f0`).
- **Cam Efekti (Glassmorphism):** `backdrop-blur-xl`, `bg-white/85`, pastel kenarlıklar ve yumuşak gölgeler.
- **Dahili Web Audio API Ses Motoru:** Sıfır harici ses dosyası bağımlılığı; lazer sesleri, patlama basları, kılıç kesme ve motor itiş efektleri %100 çevrimdışı (offline) sentetik üretilir.
- **Zero-Setup (Kullanıcı Girişsiz):** `localStorage` üzerinden XP, lig seviyesi, günün serisi (streak) ve rozet takibi.

---

## 🕹️ Birebir Oynanabilir 7 Hakiki Arcade Oyunu

1. **⚡ Mantık Düellosu (Gate Runner - 2D Cyberpunk Ray Koşucusu):**
   - Ekranda hızla akan yıldız tüneli! Gemi ekranın soluna veya sağına dokunarak şerit değiştirir.
   - Karşıdan hızla gelen neon enerji kapıları (`1 - Doğru` ve `0 - Yanlış`). Yukarıdaki önermeye (`1 ∧ 0`, `p ⇒ 1` vb.) göre doğru kapıdan geçerek çarpanı katla, yanlış kapıya çarparsan canın gider!
2. **🎯 Venn Kesişim Sapanı (Set Drop - Slingshot Physics):**
   - Angry Birds tarzı fizik sapanı! Parmağınla sayı topunu tutup geriye çek, nişan çizgisini ayarla ve fırlat.
   - Sayıyı havada yerçekimiyle kavis çizdirerek A (Çift Sayılar), B (3'ün Katları) veya mor parlayan A ∩ B Kesişim havuzuna tam isabetle sok!
3. **⚖️ Denklem Terazisi (Physics Balance Lab):**
   - Gerçek yaylanma salınımlı mekanik fizik terazisi! Sol kefede `2x + 4` blokları, sağda `14` kg ağırlık.
   - Mıknatıs aletiyle sabiti yok et, lazer dilimleyiciyle katsayıyı böl, terazinin ibresi tam yeşil 0 çizgisine kilitlendiğinde dengeyi sağla!
4. **🛡️ Mutlak Değer Lazer Savunması (Laser Space Defender):**
   - Missile Command / Space Invaders kalkan savunması!
   - `|x| ≤ 4` kuralı aktif. Ekrana dokunduğun yere lazer tareti ateş açar. `|x| > 4` olan tehlikeli kırmızı meteorları patlat, `|x| ≤ 4` mavi dost kristalleri üsse alarak kalkanını tamir et!
5. **🚀 Oran Roketi (Rocket Tunnel Flight - Jetpack/Flappy Arcade):**
   - Ekrana basılı tutarak roketin motorunu ateşle (Thrust 🚀) ve havada yüksel, bırakınca süzül!
   - İlerideki tünel kapılarından matematiksel olarak doğru orantı kapısından (örn: `8 Gün`) uçarak geç, yakıt deposunu %100 yapıp uzaya fırlat!
6. **💣 Bölünebilme Bombası (Fruit Slice Rush):**
   - Fruit Ninja tarzı kılıç kesme aksiyonu! Saatli bomba geri sayarken aşağıdan havaya fırlatılan sayılardan 3'e bölünenleri parmağını kaydırarak havada ikiye dilimle ve bombayı imha et!
7. **🃏 Swipe Formül Kartları (3D Card Fling & Albüm):**
   - Dokunmatik savurma fiziğiyle (velocity & fling) kartları sağa/sola fırlat, Maarif formüllerini ezberlemeden eğlenceli bir refleks haline getir.

---

## 🚀 Çalıştırma & Mobilden Açma

1. Bilgisayarda terminalden şu komutu girin (tüm cihazlara açık Wi-Fi bağlantısı):
   ```bash
   cd /Users/gokalpemirbas/.gemini/antigravity/scratch/matematik-arcade
   python3 -m http.server 8080 --bind 0.0.0.0
   ```
2. Telefonunuzun tarayıcısından (iPhone Safari / Android Chrome):
   ```text
   http://192.168.1.133:8080
   ```
   adresine giderek oynayabilirsiniz!
