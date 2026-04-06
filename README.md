# SkyBOT
SkyBOT Gpt2 Text Generating Model

Bu projede ile gpt-2 modeli kullanarak kendi Metin Üretme (ince ayarlanmış Fine Tuned) aracı geliştiriyoruz.
Farklı kodlar denedik ve karışık bir proje geçmişi oluştu, Dataset olarak ise Wikipedia Türkçe  veriseti kullanıyoruz.
Bu aşamada ilk olarak 90 milyon satırlık wikipedi dump file'ı verimli olmadı ve temizleyerek 16 milyon satıra indirmemiz gerekti.
colab.research.google.com da A100 T4 ve işlem birimleri ile çalışıyoruz, (işlem biirimi limitimiz dolunca T4 e dönüyoruz)
