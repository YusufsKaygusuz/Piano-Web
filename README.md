# Piano-Web

<h2>🎹 Piano Web 🎶</h2>

🎵 Bu JavaScript uygulaması, bir piyano klavyesi üzerinde tuşa basıldığında ses çalabilen basit bir uygulamadır.

<h3>Nasıl Kullanılır</h3>
<p>🎹 Klavyeden bir tuşa basarak veya fareyle bir tuşa tıklayarak bir not çalabilirsiniz.</p>
<p>🔊 Sesi ayarlamak için ses kaydırıcısını kullanabilirsiniz.</p>
<p>👀 Tuşları gizlemek veya göstermek için tuşları göster/gizle kutusunu işaretleyebilirsiniz.</p>

<h3>Kod Açıklamaları</h3>

<p>🎹 <strong><i>pianoKeys</i></strong> değişkeni, tüm piyano tuşlarını seçer.</p>
<p>🎶 <strong><i>allKeys</i><strong> değişkeni, tüm piyano tuşlarının data-key özniteliğine dayalı olarak bir diziye eklenir.</p>
<p>🔊 <strong><i>audio</i></strong> değişkeni, a.wav dosyasına varsayılan olarak ayarlanır.</p>
<p>🎶 <strong><i>playTune</i></strong> fonksiyonu, çalınacak nota adını (örn. "a", "c#", vb.) parametre olarak alır ve o notanın ses dosyasının yolunu ayarlar ve oynatır. Ayrıca, çalınan tuşa "active" sınıfını ekler ve 150 ms sonra kaldırır.</p>
<p>🎹 forEach yöntemi kullanılarak, tüm tuşlara bir "click" olayı atar ve playTune fonksiyonunu çağırır.</p>
<p>🔊 <strong><i>handleVolume</i></strong> fonksiyonu, ses kaydırıcısı değerini alır ve audio öğesinin ses düzeyini ayarlar.</p>
<p>👀 <strong><i>showHideKeys</i></strong> fonksiyonu, "Tuşları Göster/Gizle" kutusuna tıklama olayını ele alır ve tüm piyano tuşlarının "hide" sınıfını ekler veya kaldırır.</p>
<p>🎹 <strong><i>pressedKey</i></strong> fonksiyonu, bir tuşa basıldığında tetiklenir ve basılan tuşun adını alır ve eğer tüm tuşların dizisinde varsa playTune fonksiyonunu çağırır.</p>
<p>👀 "Tuşları Göster/Gizle" kutusu ve ses kaydırıcısı için "click" veya "input" olayları dinlenir.</p>

<h2>🎵 İyi eğlenceler! 🎶</h2>
