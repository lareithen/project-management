# İsimlendirme Kuralları

Geliştirme süreçleri boyunca standart sağlamak adına aşağıdaki kurallar uygulanmalıdır:

## 1. Issue ve Pull Request Başlıkları
Issue ve PR oluştururken başlık formatı standart olarak `<scope>: <desc>` şeklinde olmalıdır.
Sadece aşağıdaki scope'lar kullanılacaktır:

- `feat`: Yeni bir özellik eklenmesi
- `refactor`: Mevcut kodun davranışını değiştirmeden iyileştirilmesi
- `bug`: Hatalı çalışan bir yerin düzeltilmesi
- `chore`: Derleme süreci, paket yönetimi veya dış araçlarla ilgili rutin işler
- `docs`: Dokümantasyonla ilgili ekleme veya düzenlemeler

**Issue/PR Başlığı Örnekleri:**
- `feat: add user authentication`
- `feat: create dashboard layout`
- `refactor: simplify calculate total function`
- `refactor: clean up unused variables`
- `bug: resolve null pointer in user profile`
- `bug: fix text overflow on mobile screens`
- `chore: update dependencies`
- `chore: configure github actions`
- `docs: update readme with setup instructions`
- `docs: add api reference`

## 2. Commit Mesajları
Commit atarken [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) standartlarına uyulmalıdır. Issue/PR etiketlerinden farklı olarak, commit tiplerinde Conventional Commits'in kendi standart tipleri (`fix`, `feat`, `chore`, `refactor`, vb.) geçerlidir.

**Commit Mesajı Örnekleri:**
- `feat: implement login api endpoint`
- `feat: add export button to reports`
- `fix: correct tax calculation logic`
- `fix: prevent duplicate form submissions`
- `refactor: move constants to config file`
- `refactor: optimize database queries`
- `chore: bump webpack version`
- `chore: add prettier formatting rules`
- `docs: fix typo in installation guide`
- `docs: clarify branching strategy`
