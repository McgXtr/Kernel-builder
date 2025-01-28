# Kernel-builder

Run docker push sado54/android-kernel-builder-debian:tagname

Depozitif Genel Bakış Resim Adı: sado54/android-kernel-builder-debian

Açıklama : Bu Docker görüntüsü, Android çekirdek geliştirme ve derleme için gerekli araçlara sahip Debian tabanlı bir ortam sağlar. Çeki geliştirme için gerekli çeşitli derleme araçları, çapraz derlemeler ve kütüphaneler dikkatlice kurulmuştur. Bu şekilde, Android çekirdek derlemesi izole bir Docker kakında kolayca yapılabilir.

Ana Aletler ve Kütüphaneler dahildir GCC ve Clang: C / C++ derlemesi için. Yapın ve Yapı Yapın Python 2 ve Python 3: Farklı sürümlerle uyumlu geliştirme. Çapraz Derleyiciler: gcc-arz-linux-gnueabi, gcc-arm-linux-gnueaif, ARM platformları için çapraz yapı-temel-arz 64. Kernel Kütüphaneleri: libncurses-dev, libssl-dev, libelf-dev gibi gelişme için gerekli kütüphaneler. Android Geliştirme Araçları: android-sdk, adb, fastboot. Kullanın Görüntüyü kullanarak bir konteyner başlatmak için:

docker run -it sado54/android-kernel-builder-debian /bin/bash

Bu komut, konteyner içinde etkileşimli bir terminalle çalışma fırsatı sağlar.

Örnek Kullanım Senaryosu Bu görüntü Android çekirdek geliştirme için gerekli araçları sağlarken, diğer çekirdek veya sistem geliştirme süreçlerinde de kullanılabilir. İzole gelişim ortamı gerektiren projeler için idealdir.
