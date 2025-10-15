Başla

Kartı yerleştir
Eğer kart geçerli ise
    Şifreyi gir
    Eğer şifre doğruysa
        Ana menüyü göster
        Menüler: 
            1. Bakiye Sorgulama
            2. Para Çekme
            3. Çıkış

        Seçim yap

        Eğer seçim == 1 ise
            Bakiyeyi göster
            Ana menüye dön

        Eğer seçim == 2 ise
            Çekmek istenen tutarı gir
            Eğer tutar pozitif ve 10’un katı ise
                Eğer bakiye >= tutar ise
                    Bakiyeden tutarı düş
                    Parayı ver
                    İsteğe bağlı: fiş ver
                    "İşlem başarılı" mesajı göster
                Aksi halde
                    "Yetersiz bakiye" mesajı göster
            Aksi halde
                "Geçersiz tutar" mesajı göster
            Ana menüye dön

        Eğer seçim == 3 ise
            Kartı iade et
            "İyi günler" mesajı göster
            Bitir

        Aksi halde
            "Geçersiz seçim" mesajı göster
            Ana menüye dön
    Aksi halde
        "Hatalı şifre" mesajı göster
        Şifre deneme hakkını 1 azalt
        Eğer deneme hakkı 0 ise
            Kartı bloke et
            "Kart bloke edildi" mesajı göster
            Bitir
        Tekrar şifre iste
Aksi halde
    "Kart okunamadı" mesajı göster

Bitir
