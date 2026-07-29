# İsimlendirme Kuralları

Geliştirme süreçleri boyunca standart sağlamak adına aşağıdaki kurallara uyulmalıdır:

- **Commit Mesajları:** Commit atarken [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standartlarına uyulmalıdır.
- **Issue ve Pull Request Başlıkları:** Issue ve PR oluştururken başlık formatı standart olarak `<scope>: <description>` şeklinde olmalıdır.

Issue ve Pull Request başlıkları için kullanılabilecek scope'lar şunlardır:
- `feat`: Yeni bir özellik geliştirilmesi
- `refactor`: Mevcut kodun davranışını değiştirmeden iyileştirilmesi
- `fix`: Hatalı çalışan bir yerin düzeltilmesi
- `hotfix`: Canlı sistemde acil düzeltme gerektiren sorunlar
- `docs`: Dokümantasyonla ilgili ekleme veya düzenlemeler

## Örnekler
Aşağıdaki örnekler hem commit mesajları hem de issue/PR başlıkları için kullanılabilir.

- `feat: add user authentication`
- `fix: resolve null pointer in user profile`
- `refactor: move constants to separate config file`
- `refactor: optimize database queries for products`
- `feat: implement payment gateway integration`
- `hotfix: resolve infinite loop in background job`
- `docs: update readme with setup instructions`
- `hotfix: patch security vulnerability in login`
