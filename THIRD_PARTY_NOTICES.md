# Üçüncü Taraf Varlıklar ve Lisanslar

Oyun dağıtılırken (Steam sayfası / oyun içi "Emeği Geçenler" ekranı) bu bildirimler eklenmelidir.

## Microsoft Rocketbox Avatar Library — MIT
Karakterler (`Female_Adult_06` "Hatice Teyze", `Female_Adult_09` "Nermin Teyze", `Male_Child_01` "Torun Efe") ve animasyonlar.
Kaynak: https://github.com/microsoft/Microsoft-Rocketbox
Konum: `Assets/_Project/Art/Rocketbox/`

```
MIT License

Copyright (c) 2020 Microsoft

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

`RocketboxImportSettings.cs`, Rocketbox'ın `FixRocketboxMaxImport.cs` dosyasından uyarlanmıştır (aynı MIT lisansı).

## Kenney Furniture Kit — CC0 (kamu malı)
Oynanabilir evin bütün mobilya ve eşyaları (mutfak, salon, banyo, çocuk ve yatak odası). Atıf zorunlu değildir.
Kaynak: https://kenney.nl/assets/furniture-kit — Konum: `Assets/_Project/Art/Kenney/`

## Seslendirme — Piper TTS + DFKI Türkçe sesi (CC BY-NC-SA 4.0)
Hikaye ve oyun içi replikler `Tools/generate_voices.py` ile üretildi: Piper TTS (MIT, https://github.com/rhasspy/piper)
ve `tr_TR-dfki-medium` sesi. Ses verisi: DFKI / MaryTTS `dfki-ot-data` (https://github.com/marytts/dfki-ot-data),
lisans **CC BY-NC-SA 4.0** — ticari olmayan kullanım. Seslerin perdesi/temposu karakterlere göre değiştirilmiştir;
türetilen ses dosyaları (`Assets/_Project/Resources/Voice/`) aynı lisansla paylaşılır.
**Oyun satılacaksa bu sesler değiştirilmelidir** (kendi kaydın veya ticari lisanslı bir TTS).

## Inter yazı tipi — SIL Open Font License 1.1
Arayüz ve sahne yazıları. Telif: The Inter Project Authors (https://github.com/rsms/inter).
Lisans metni: `Assets/_Project/Resources/Fonts/Inter-LICENSE.txt`

## Poly Haven — CC0 (kamu malı)
Mobilyalar, eşyalar ve yüzey dokuları. Atıf zorunlu değildir ama nezaketen önerilir.
Kaynak: https://polyhaven.com — Konum: `Assets/_Project/Art/PolyHaven/`

Modeller: sofa_02, modern_arm_chair_01, modern_coffee_table_01, modern_wooden_cabinet, side_table_01,
potted_plant_01, potted_plant_02, hanging_picture_frame_01, hanging_picture_frame_02, wall_clock,
book_encyclopedia_set_01, standing_picture_frame_01, ceramic_vase_01, dining_table, dining_chair_02,
electric_stove, vintage_electric_kettle, jug_01, wooden_bowl_01, pot_enamel_01, lubricant_spray
(modern_ceiling_lamp_01 ve vintage_microwave indirildi ama kullanılmıyor).

Dokular: laminate_floor_02, plastered_wall, marble_01, kitchen_wood, poly_wool_herringbone
(ceiling_interior ve square_tiled_wall indirildi ama kullanılmıyor).

Not: Rengârenk evin dokuları, hikaye mekânları, hamamböceği karakterleri, bütün ses efektleri ve müzik kodla üretilmiştir (`ProceduralTextures`, `YuvaBuilder`, `RoachCharacterBuilder`, `SoundSynth`); üçüncü taraf varlık içermez.
