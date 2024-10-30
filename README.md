## Gereksinimler

- PHP >= 8.0
- Composer
- Node.js >= 14
- NPM (Node Package Manager)

## Kurulum Adımları

1. **Projeyi Klonlayın:** Öncelikle projeyi GitHub'dan bilgisayarınıza klonlayın.
   
   `git clone https://github.com/melike-kls/vite-laravel-bootstrap.git`

2. **Proje Klasörüne Geçin:** Klonladığınız proje klasörüne geçin.
   
   `cd vite-laravel-bootstrap`

3. **Gerekli Paketleri Yükleyin:** Proje bağımlılıklarını yüklemek için aşağıdaki komutları çalıştırın.
   
   `composer install`  
   `npm install`

4. **.env Dosyasını Oluşturun:** `.env.example` dosyasını `.env` dosyası olarak kopyalayın.
   
   `cp .env.example .env`

5. **Uygulama Anahtarını Oluşturun:** Laravel uygulama anahtarını oluşturmak için aşağıdaki komutu çalıştırın.
   
   `php artisan key:generate`

6. **Veritabanı Ayarlarını Yapın:** `.env` dosyasını açarak veritabanı ayarlarınızı güncelleyin.


7. **Geliştirme Sunucusunu Başlatın:** Projeyi başlatmak için aşağıdaki komutu çalıştırın.
   
   `php artisan serve`

8. **Vite'yi Başlatın:** Vite geliştirme sunucusunu başlatmak için yeni bir terminal penceresi açın ve aşağıdaki komutu çalıştırın.
   
   `npm run dev`

9. **Uygulamayı Görüntüleyin:** Tarayıcınızda `http://127.0.0.1:8000` adresine gidin.


## Katkıda Bulunma

Bu proje, sadece fork'lanabilir ve kişisel projelerinizde kullanılabilir. Orijinal projede değişiklik yapmak mümkün değildir.
