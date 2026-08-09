# XERIA 1.9.1 Release Notes

Released: August 9, 2026

## English

### Summary

XERIA 1.9.1 adds comprehensive display compatibility for high-DPI settings and different screen resolutions. The interface now scales automatically to the available screen area, switches to compact navigation on low-resolution displays, fits secondary windows within the usable screen area, and preserves usability across monitors with different DPI settings.

Rendering quality for small text and Trace Code watermarks has also been improved, including very small watermark size settings, while preserving non-selectable and non-copyable output behavior. Localized navigation tooltips, additional window sizing and layout improvements, and a streamlined Dropbox connection flow are included.

### Detailed changes

- Added adaptive scaling for high-DPI settings and different screen resolutions.
- Improved interface compatibility for displays with a resolution of 1024 × 768 or higher.
- Added automatic compact sidebar behavior for low-resolution displays and narrow windows.
- Added dynamic navigation tooltips in all nine supported interface languages.
- Restored the full sidebar automatically when the window becomes wide enough again.
- Added dynamic minimum width and height limits for the main window.
- Improved transitions between maximized, restored, and manually resized window states.
- Automatically fitted large custom windows and file-selection dialogs within the usable screen area.
- Improved behavior when moving XERIA between monitors with different DPI settings.
- Corrected window positioning, taskbar, and monitor work-area calculations.
- Kept PDF preview, watermark positioning, zoom, and page navigation compatible with the new scaling system.
- Improved rendering quality for small text and Trace Code watermarks.
- Improved sharpness and stability of text-based watermarks at very small size settings.
- Preserved non-selectable and non-copyable behavior for text and Trace Code watermarks while improving rendering quality.
- Streamlined the Dropbox connection flow and removed the unnecessary pre-connection information dialog.

## Türkçe

### Özet

XERIA 1.9.1 ile yüksek DPI ayarları ve farklı ekran çözünürlükleri için kapsamlı görüntü uyumluluğu eklendi. Arayüz artık ekranın kullanılabilir alanına göre otomatik ölçekleniyor, düşük çözünürlüklerde kompakt navigasyona geçiyor, ayrı pencereleri kullanılabilir ekran alanına sığdırıyor ve farklı DPI değerlerine sahip monitörlerde kullanılabilirliği koruyor.

Küçük boyutlardaki metin ve Trace Code filigranlarının görüntü kalitesi, çok küçük filigran boyutları dahil olmak üzere iyileştirildi; filigranların PDF üzerinde normal metin gibi seçilemez ve kopyalanamaz davranışı korundu. Çok dilli navigasyon araç ipuçları, ek pencere boyutlandırma ve yerleşim iyileştirmeleri ile sadeleştirilmiş Dropbox bağlantı akışı da bu sürüme dahil edildi.

### Ayrıntılı değişiklikler

- Yüksek DPI ve farklı ekran çözünürlükleri için adaptif ölçeklendirme eklendi.
- 1024 × 768 ve üzerindeki ekranlar için arayüz uyumluluğu geliştirildi.
- Düşük çözünürlükte ve dar pencerelerde otomatik kompakt sidebar desteği eklendi.
- Kompakt navigasyon ikonlarına dokuz dilde dinamik araç ipuçları eklendi.
- Pencere yeniden genişletildiğinde sidebar'ın otomatik olarak normal görünüme dönmesi sağlandı.
- Ana pencere için dinamik minimum genişlik ve yükseklik sınırları eklendi.
- Tam ekran, normal pencere ve manuel yeniden boyutlandırma geçişleri iyileştirildi.
- Büyük özel pencereler ve dosya seçim ekranları kullanılabilir ekran alanına otomatik olarak sığdırıldı.
- Farklı DPI değerlerine sahip monitörler arasında geçiş davranışı iyileştirildi.
- Pencere konumu, görev çubuğu ve kullanılabilir monitör alanı hesaplamaları düzeltildi.
- PDF önizleme, filigran konumlandırma, yakınlaştırma ve sayfa geçişleri yeni ölçeklendirme sistemiyle uyumlu hale getirildi.
- Küçük boyutlardaki metin ve Trace Code filigranlarının görüntü kalitesi iyileştirildi.
- Çok küçük boyutlarda metin tabanlı filigranların keskinliği ve kararlılığı geliştirildi.
- Metin ve Trace Code filigranlarının normal PDF metni gibi seçilemez ve kopyalanamaz davranışı korunarak render kalitesi geliştirildi.
- Dropbox bağlantı akışı sadeleştirildi ve bağlantı öncesindeki gereksiz bilgilendirme penceresi kaldırıldı.
