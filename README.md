# 🚀 Eğik Atış ve Hava Direnci (Rüzgar) Simülasyonu

Bu proje, Fizik I dersi kapsamında geliştirilmiş; eğik atış hareketini hava direnci (aerodinamik sürtünme), rüzgar faktörü ve farklı gök cisimlerinin yer çekimi ivmeleri altında simüle eden interaktif bir fizik yazılımıdır.

---

## 👤 Öğrenci Bilgileri

* **Adı Soyadı:** Adem Kaleli
* **Öğrenci No:** 2615501083
* **Ders:** Fizik I
* **Ödev Konusu:** Hava Dirençli ve Rüzgarlı Eğik Atış Hareketi Simülasyonu

---

## 🧮 Matematiksel ve Fiziksel Model

Simülasyonda cisme etki eden toplam kuvvetler Newton'un 2. Yasası ($\vec{F}_{\text{net}} = m \vec{a}$) çerçevesinde bileşenlerine ayrılarak modellenmiştir:

$$\vec{F}_{\text{net}} = \vec{F}_g + \vec{F}_d$$

1. **Yer Çekimi Kuvveti:** $F_g = m \cdot g$
2. **Hava Direnci (Aerodinamik Sürükleme):**
   $$F_d = \frac{1}{2} \rho C_d A v_{\text{rel}}^2$$

* $\rho$: Hava yoğunluğu ($\text{kg/m}^3$)
* $C_d$: Sürükleme katsayısı (Drag Coefficient)
* $A$: Kesit alanı ($\text{m}^2$)
* $v_{\text{rel}}$: Cismin rüzgara göre bağıl hızı ($v_x - v_{\text{rüzgar}}$)

---

## ✨ Özellikler

* 🎯 **Dinamik Parametreler:** Atış açısı ($\theta$), ilk hız ($v_0$), cisim kütlesi ($m$), kesit alanı ve rüzgar hızı ayarlanabilir.
* 🌍 **Ortam Seçenekleri:** Dünya, Ay, Mars, Jüpiter ve Vakum (Sürtünmesiz) yer çekimi modları.
* 📈 **Anlık Veri Paneli:** Maksimum Yükseklik ($H_{\text{max}}$), Toplam Menzil ($R$), Uçuş Süresi ve Çarpma Hızı.
* 🎨 **Yörünge Karşılaştırma:** Farklı parametrelerle yapılan atışlar ekranda renkli izler bırakarak görsel olarak kıyaslanabilir.
