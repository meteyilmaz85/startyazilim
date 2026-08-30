# startyazilim.com

Start Yazılım Çözümleri ve Ticaret Ltd. Şti. için tek sayfalık (one-pager) kurumsal web sitesi.

Statik bir HTML dosyası (`index.html`) — build adımı, framework veya bağımlılık gerektirmez.

## Yayınlama: GitHub Pages (ücretsiz)

1. Bu branch `main`'e merge edildikten sonra: **Settings → Pages**
2. **Build and deployment → Source**: `Deploy from a branch`
3. **Branch**: `main` / `/ (root)` seçip **Save**
4. **Custom domain** alanına `startyazilim.com` yazın (repodaki `CNAME` dosyası bunu zaten işaret ediyor) ve **Save**
5. Alan adı sağlayıcınızda (startyazilim.com'u aldığınız yer) aşağıdaki DNS kayıtlarını ekleyin:

   **Apex domain (`startyazilim.com`) için A kayıtları:**
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

   **`www` alt alan adı için CNAME kaydı (opsiyonel ama önerilir):**
   ```
   www.startyazilim.com  →  meteyilmaz85.github.io
   ```

6. DNS yayılması genelde birkaç dakika-birkaç saat sürer. GitHub Pages ayarlarında "Enforce HTTPS" kutusunu işaretleyerek otomatik ücretsiz SSL sertifikası aldırabilirsiniz (DNS doğrulandıktan sonra aktif olur).

Site şu adresten yayında olacak: **https://startyazilim.com**
