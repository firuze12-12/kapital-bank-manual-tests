# Kapital Bank – Filial Axtarışı Manual Test Cases

---

# Pozitiv Test Cases

| Test İD | Funksionallıq | Test Növü | Steps | Expected Result |
|----------|--------------|------------|-------|----------------|
| TC_FA_01 | Filial Axtarışı | Pozitiv | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.”Filial” bölməsini seç<br>4.Şəhər siyahısından ”Bakı” seç | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. Filial<br>4. Bakıdakı filiallar siyahısı düzgün göstərilir https://www.kapitalbank.az/locations/branch/baku |
| TC_FA_02 | Filial Axtarışı | Pozitiv | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.”Filial” bölməsini seç<br>4.Şəhər siyahısından ”Gəncə” seç | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. Filial<br>4. Gəncədəki filiallar siyahısı düzgün göstərilir https://www.kapitalbank.az/locations/branch/ganja |
| TC_FA_03 | Filial Axtarışı | Pozitiv | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.”Bankomat” bölməsini seç<br>4.Şəhər siyahısından ”Bakı” seç | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. https://www.kapitalbank.az/locations/atm/all<br>4. Bakıdakı yalnız ATM olan filiallar siyahısı düzgün göstərilir https://www.kapitalbank.az/locations/atm/baku |
| TC_FA_04 | Filial Axtarışı | Pozitiv | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.”Ödəniş Terminalı” bölməsini seç<br>4.Şəhər siyahısından ”Gəncə” seç | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. https://www.kapitalbank.az/locations/atm/all/payment_terminal<br>4. Gəncədəki yalnız ödəniş terminalı olan filiallar siyahısı göstərilir https://www.kapitalbank.az/locations/atm/ganja/payment_terminal |
| TC_FA_05 | Filial Axtarışı | Pozitiv | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.”Rəqəmsal Mərkəz” bölməsini seç<br>4.Şəhər siyahısından ”Bakı” seç | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. https://www.kapitalbank.az/locations/branch/all/reqemsal-merkez<br>4. Bakıdakı bütün rəqəmsal mərkəzlər siyahısı düzgün göstərilir https://www.kapitalbank.az/locations/branch/baku/reqemsal-merkez |

---

#  Neqativ Test Cases

| Test İD | Funksionallıq | Test Növü | Steps | Expected Result |
|----------|--------------|------------|-------|----------------|
| TC_FA_01 | Filial Axtarışı | Neqativ | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.Axtarış sahəsinə şəhər adı yaz<br>4.Axtar buttonuna klik et | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. Sumqayıt<br>4. Axtarış düyməsi klik olunmur və heç bir nəticə göstərilmir |
| TC_FA_02 | Filial Axtarışı | Neqativ | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.”Rəqəmsal Mərkəz” bölməsini seç<br>4.Şəhər siyahısında mövcud olmayan şəhər Sumqayıt seç | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. https://www.kapitalbank.az/locations/branch/all/reqemsal-merkez<br>4. Siyahıda yalnız Bakı və Gəncə göstərilir |
| TC_FA_03 | Birbank Private | Neqativ | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.”Birbank Private” bölməsinə daxil ol<br>4.Şəhər siyahısını aç | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. https://www.kapitalbank.az/locations/atm/all/private<br>4. Siyahıda yalnız Bakı şəhəri göstərilir, digər şəhərlər mövcud deyil və seçilə bilmir |
| TC_FA_04 | Cash-in ATM | Neqativ | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.Cash-in bölməsinə daxil ol<br>4.Siyahıda mövcud olmayan şəhər Şəmkir axtar | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. https://www.kapitalbank.az/locations/atm/all/cash_in<br>4. Şəmkir şəhəri siyahıda göstərilmir və seçilə bilmir |
| TC_FA_05 | Filial Axtarışı | Neqativ | 1.Kapital Bank saytına daxil ol<br>2.”Xidmət Şöbəsi” buttonuna klik et<br>3.Filial bölməsinə daxil ol<br>4.Axtarış sahəsinə xüsusi simvollar yaz<br>5.Axtarış buttonuna klik et | 1.Sayt açılır. https://www.kapitalbank.az<br>2. https://www.kapitalbank.az/locations<br>3. https://www.kapitalbank.az/locations/branch/all<br>4. @@##<br>5. Sistem nəticə göstərmir və səhv sistem xətası baş vermir |
