# Test Case-lər – Kapital Bank

---

## 🔹 Login / Qeydiyyat Test Case-ləri

| ID   | Type       | Precondition                  | Steps                   | Expected Result           |
|------|-----------|-------------------------|----------------------------|-------------------------------|
| L01  | Pozitiv   | İstifadəçi qeydiyyatdan keçib | Düzgün login və şifrə daxil et | Sistemə uğurla daxil olur     |
| L02  | Pozitiv   | Hesab yoxdur             | Düzgün məlumatlarla qeydiyyat et | Hesab yaradılır               |
| L03  | Pozitiv   | İstifadəçi mövcuddur     | Mobil tətbiqdən giriş et   | Uğurlu giriş edilir           |
| L04  | Pozitiv   | İstifadəçi mövcuddur     | Şifrəni bərpa et           | Yeni şifrə yaradılır          |
| L05  | Pozitiv   | İstifadəçi çıxış edib    | Yenidən login ol           | Hesaba giriş edilir           |
| L06  | Neqativ   | İstifadəçi mövcuddur     | Səhv şifrə daxil et        | Giriş rədd edilir             |
| L07  | Neqativ   | Hesab yoxdur             | Qeydiyyatsız giriş et      | Xəta mesajı çıxır             |
| L08  | Neqativ   | Yoxdur                   | Sahələri boş saxla         | Xəbərdarlıq göstərilir       |
| L09  | Neqativ   | İstifadəçi mövcuddur     | Yanlış email formatı daxil et | Xəta mesajı göstərilir       |
| L10  | Neqativ   | Hesab bloklanıb          | Giriş etməyə çalış         | Giriş qadağan edilir          |

---

## 🔹 Kart Balansına Baxış Test Case-ləri

| ID   | Type       | Precondition                  | Steps                   | Expected Result            |
|------|-----------|-------------------------|----------------------------|-------------------------------|
| B01  | Pozitiv   | İstifadəçi daxil olub    | Kartlar bölməsinə keç      | Balans göstərilir             |
| B02  | Pozitiv   | Kart aktivdir            | Səhifəni yenilə            | Balans yenilənir              |
| B03  | Pozitiv   | Bir neçə kart var        | Kartlar arasında keçid et  | Düzgün balans görünür         |
| B04  | Pozitiv   | İstifadəçi daxil olub    | Balans tarixçəsinə bax     | Tarixçə göstərilir            |
| B05  | Pozitiv   | İnternet aktivdir        | Balans səhifəsini aç       | Məlumat yüklənir              |
| B06  | Neqativ   | İnternet yoxdur          | Balans səhifəsini aç       | Bağlantı xətası çıxır         |
| B07  | Neqativ   | İstifadəçi çıxış edib    | Balansa baxmağa çalış      | Login tələb olunur            |
| B08  | Neqativ   | Kart bloklanıb           | Balansa bax               | Girişə icazə verilmir         |
| B09  | Neqativ   | Sistem işləmir           | Balans aç                  | Sistem xətası göstərilir      |
| B10  | Neqativ   | Sessiya bitib            | Səhifəni yenilə            | Sessiya bitdi mesajı çıxır    |
