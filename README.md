# blossom-algorithm
## Nedir ,Nasıl Kullanılır?
Graph teorisinde, Blossom algoritması  grafikler üzerinde maksimum eşleşmeler oluşturmak için kullanılan bir algoritmadır .  Bu algoritma, özellikle çiftleştirme problemleri için kullanılır. Algoritma Jack Edmonds tarafından 1961'de geliştirildi, Ve 1965'te yayınlandı. Eşleştirme, grafikteki artırma yolları boyunca ilk boş eşleştirmeyi yinelemeli olarak geliştirerek oluşturulur. İki parçalı eşlemeden farklı olarak , yeni anahtar fikir, grafikteki (blossom) tek uzunluktaki bir döngünün tek bir köşeye daraltılması ve aramanın daraltılmış grafikte yinelemeli olarak devam etmesidir.Blossom algoritması, Karp'in minimum kesim algoritması ve Edmonds'un matroid çizelgesi algoritması gibi diğer graf tabanlı problemler için önemli bir araçtır. Blossom algoritması, özellikle max-flow min-cut problemlerinin çözümünde kullanılan augmenting path algoritması ile benzerlik gösterir Ancak, augmenting path algoritması sadece ağda bir maksimum akış bulmaya yönelikken, Blossom algoritması çiftleştirme problemlerini çözmek için tasarlanmıştır. Blossom algoritması, NP-hard bir problemin çözümü için kullanılır. Ancak, pratik uygulamalarda oldukça etkilidir ve çiftleştirme problemlerinin çözümü için sıklıkla tercih edilir.

En iyi, en kötü ve ortalama çalışma sınırları algoritmanın varyasyonuna ve kullanılan girdiye bağlıdır.

En iyi durumda, algoritma O(E+V log V) zaman karmaşıklığına sahip olabilir. Bu durumda, graf çok seyrek ise ve BFS işlemi sırasında çok fazla artırıcı yol bulunuyorsa gerçekleşebilir.

En kötü durumda zaman karmaşıklığı O(n^4) dır, burada n, grafın toplam düğüm sayısıdır. Eğer graf tamamlayıcı çiftler grafi ise O(n^3) olarak hesaplanabilir. Ancak, pratikte bu süre nadiren gerçekleşir ve birçok durumda daha az olur.

Ortalama durumda, Blossom algoritmasının zaman karmaşıklığı O(E^2V) olarak tahmin edilir. Ancak, varyasyonlarına ve uygulama senaryolarına göre farklılık gösterebilir.

Matematiksel ve asimptotik analizler yaparak, en iyi durumda E+V log V, en kötü durumda E^3 ve ortalama durumda E^2V karmaşıklığına sahip olan Blossom algoritmasının çalışma sınırları belirlenebilir.

<img src="https://github.com/1210505028/blossom-algorithm/blob/main/blossom1.png" width="auto">
