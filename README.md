🧠 **Gelişmiş Yapay Zeka Sohbet Botu**  
🚀 **Proje Genel Bakış**  
Groq Memory Manager, yapay zekâ bağlamsal belleği geliştirmek ve optimize etmek için tasarlanmış yenilikçi bir araçtır. İnternet bağlantısını kullanarak webde arama yapma özelliği ile zenginleştirilen bu sistem, Stixyie tarafından geliştirilmiştir ve kalıcı, bölümlenmiş, akıllı bellek yönetimi için benzersiz bir çözüm sunar.  

✨ **Temel Özellikler**  
- **Akıllı Bellek Bölümlendirme**: Büyük bellek dosyalarını dinamik olarak yönetilebilir parçalara böler.  
- **Kalıcı Depolama**: Her kullanıcı için benzersiz zaman damgalarıyla bellek dosyalarını saklar.  
- **Bağlamsal Etkileşim**: Bellek bağlamını Groq API ile sorunsuz bir şekilde entegre eder.  
- **Uyarlanabilir Kayıt Tutma**: Bellek işlemleri için kapsamlı kayıt yönetimi.  
- **Güvenli Ortam Yönetimi**: API anahtarlarını güvenle saklar.  
- **Web Arama Entegrasyonu**: İnternet bağlantısını kullanarak güncel bilgilere erişim sağlar.  

🔧 **Teknik Özellikler**  
**Bellek Kalıcılığı ve İşlemleri**  
- Bellek parçalarını kaydedebilir ve çağırabilirim:  
  ```python  
  memory_manager.save_memory_file("Detaylı konuşma bağlamı", "kullanıcı_id")  
  response = memory_manager.transmit_memory_to_groq("kullanıcı_id", "Önceki konuşmamıza devam edelim")  
  ```  

**Akıllı Bölümlendirme**  
- Büyük bellek dosyalarını 4096 karakterlik parçalara böler, bağlamı korur.  

**Web Arama Entegrasyonu**  
- İnternet bağlantısını kullanarak bilgi toplar ve bağlama uygun cevaplar sunar:  
  ```python  
  web_search_results = memory_manager.search_web("aranacak konu")  
  ```  

🌟 **Beni Özel Yapan Nedir?**  
- **Bilişsel Süreklilik**: Bağlamı etkileşimler arasında korur.  
- **Ölçeklenebilir Mimari**: Çoklu kullanıcı ve büyük bellek dosyalarını destekler.  
- **Gizlilik Odaklı**: Yerel depolama ve güvenli veri aktarımı sağlar.  
- **Web Tabanlı Zekâ**: Anlık web aramaları ile dinamik bilgi sağlar.  

🔬 **Teknik Yeteneklerim**  
- **Dil**: Python  
- **AI Entegrasyonu**: Groq API  
- **Web Arama**: İnternet bağlantısıyla dinamik sorgulama  
- **Kütüphaneler**:  
  - `groq`: AI etkileşimi  
  - `python-dotenv`: Ortam değişkeni yönetimi  
  - `requests`: Web sorguları  
  - `logging`: İşlem izleme  

🚀 **Başlangıç**  
1. Depoyu klonlayın.  
2. Gerekli bağımlılıkları yükleyin:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Groq API anahtarınızı ve web sorguları için gerekli ayarları `.env` dosyasına ekleyin:  
   ```env  
   GROQ_API_KEY=your_api_key_here  
   ```  

🤝 **Katkı Sağlama**  
Sorunları bildirip, pull request gönderebilir veya projeyi forklayabilirsiniz. Katkılarınız her zaman memnuniyetle karşılanır!  

📜 **Lisans**  
GPL-3.0 lisansı.  

👨‍💻 **Hakkında**  
Stixyie, yapay zekâ teknolojisini ileriye taşımaya tutkuyla bağlı yenilikçi bir geliştiricidir. Diğer projeleri GitHub'da keşfedin!  
