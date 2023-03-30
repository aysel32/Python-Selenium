# Python-Selenium
Kodlama-io Python Kampı

Pytest-Decoratorler
PyTest, Python dilinde bir test çerçevesidir ve test fonksiyonlarının yazılmasını ve yürütülmesini kolaylaştırmak için bir dizi decorator sağlar. Decoratorlar, test fonksiyonlarının özelliklerini ve davranışlarını özelleştirmek için kullanılır. PyTest, aşağıdaki gibi birkaç temel decorator sağlar:

@pytest.fixture: Test fonksiyonları için fixture'ları tanımlamak için kullanılır. Fixture'lar, test fonksiyonlarının ihtiyaç duyduğu önceden tanımlanmış durumları sağlamak için kullanılır.

@pytest.mark.parametrize: Parametreli testleri tanımlamak için kullanılır. Bu decorator, aynı test fonksiyonunu farklı parametrelerle birden çok kez çağırmayı sağlar.

@pytest.mark.skip: Bir testi atlamak için kullanılır. Bu decorator, belirli koşullar altında bir testin çalıştırılmasını engeller.

@pytest.mark.xfail: Bir testin hatalı sonuç vermesini beklediğimiz durumlar için kullanılır. Bu decorator, testin hata vermesini bekler ve hata çıktısını görmezden gelir.

@pytest.mark.timeout: Bir testin belirli bir sürede tamamlanmasını beklediğimiz durumlar için kullanılır. Bu decorator, bir testin belirli bir sürede tamamlanmaması durumunda testi sonlandırır.

Bu decoratorlerin yanı sıra PyTest, kullanıcıların kendi özel decorator'larını da yazmalarına izin verir. Bu özellik, test sürecini özelleştirme ve test fonksiyonlarına özel davranışlar eklemek için oldukça faydalıdır.
