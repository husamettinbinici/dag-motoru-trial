# 🏍️ Dağ Motorcusu: Moto Trial / Racer

> **Dağ yamaçlarında gazı kökle, yön tuşlarıyla havada dengede kal ve rampalardan uç!**

[![HTML5 / Canvas](https://img.shields.io/badge/Tech-HTML5%20Physics%20%7C%20Web%20Audio-orange)](index.html)
[![Unreal Engine 5](https://img.shields.io/badge/Engine-Unreal%20Engine%205%20Physics%20Constraints-blue)](unreal_engine_moto_rehberi.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🎮 Kontroller & Oynanış

* **Yukarı Ok / W:** Gaz Ver (Arka tekerlek torku ve motor devri artışı)
* **Aşağı Ok / S:** Fren / Geri (Tekerlek sönümleme)
* **Sol Ok / A:** Geriye Yaslan / Ön Kaldır (Wheelie & Havada denge)
* **Sağ Ok / D:** İleriye Yaslan / Burun İndir (Tırmanış & Stoppie)
* **Boşluk (Space):** Kazadan sonra anında yeniden başla

### Özellikler:
* **Çift Tekerlek & Süspansiyon Fiziği:** Engebeli arazilerde yaylanma ve zıplama tepkileri.
* **Dinamik Ses Motoru:** Gaz verdikçe yükselen gerçekçi 2-zamanlı motor devir sesi (Web Audio API).
* **Takla & Denge Bonusu:** 360 derece ön veya arka takla attığınızda ekstra puan.
* **Kaza Tespiti:** Sürücünün kafası yere değdiğinde düşüş ve kaza ekranı.

---

## 🛠️ Unreal Engine 5 Entegrasyonu

Projede Unreal Engine 5 için hazırlanmış hem 2D Paper2D hem de 3D Skeletal Mesh varlıkları mevcuttur:

👉 **[Unreal Engine 5 Blueprint & Mimari Rehberi](unreal_engine_moto_rehberi.md)**

### Varlıklar (`UnrealEngine_Assets/`):
* `Motosiklet_Govde.png` & `Motosiklet_Tekerlek.png`: Yüksek çözünürlüklü parçalar.
* `Surucu_Animasyon/`: Denge hareketlerine göre sürücünün eğilme animasyon kareleri.
* `3D_Model/SK_DagMotoru_Rigged.glb`: UE5'e sürükle-bırak yöntemiyle doğrudan aktarılabilen iskeletli ve tekerlek animasyonlu 3D model.

---

## 📜 Lisans

Bu proje [MIT Lisansı](LICENSE) kapsamında açık kaynak olarak geliştirilmiştir.
