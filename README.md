# TUTORIAL SPRING BOOT DASAR


### Apa itu Spring?
* Spring adalah proyek sumber terbuka yang menyediakan pendekatan modular yang efisien untuk membuat aplikasi dengan Java. Nama Spring sendiri biasanya mengacu pada kerangka kerja aplikasi itu sendiri atau keseluruhan kelompok proyek atau modul.

### Pengenalan Spring Framework
* Spring Framework adalah framework open source berbasis java yang menyediakan infrastruktur yang komprehensif dalam mengembangkan aplikasi java dengan mudah dan cepat.
* Spring Framework menggunakan teknik pemrograman yang sederhana, model pemrograman dengan Spring cukup mudah, namun rapi. Hal Ini memudahkan bagi para developer pemula untuk mempelajarinya.
* Dengan menggunakan Spring Framework, developer dapat membuat aplikasi enterprise ataupun web. Selain itu juga, para developer dapat membuat aplikasi untuk keamanan dan aplikasi yang terkait dengan big data
* [https://socs.binus.ac.id/2017/10/04/framework-spring-java/]

### Pengenalan Spring Boot
* Spring Boot dirilis pertama kali pada tahun 2014 oleh tim Sprint di Pivotal. Pivotal adalah sebuah perusahaan yang menyediakan dukungan untuk Spring. 
* Spring Boot adalah framework untuk mengembangkan aplikasi berbasis Java. Framework ini memiliki komunitas developer yang besar dan aktif. Spring Boot dapat digunakan untuk membangun berbagai macam jenis aplikasi. Contohnya microservice, dan web. 
* Tujuan dibuatnya Spring Boot yaitu untuk mempermudah pembuatan aplikasi dan layanan production-grade berbasis Spring dengan konfigurasi minimal.
* Spring Boot memberikan fitur dan tools tambahan di atas framework Spring. Hal ini membuat pengembangan dan deploy aplikasi spring lebih mudah untuk dilakukan. Spring Boot dirancang untuk membuat bootstrapping dan pengembangan aplikasi Spring yang baru menjadi lebih sederhana.
* [https://josikie.com/apa-itu-spring-boot/]

### Ekosistem Pendukung
* Spring memiliki ekosistem pendukung yang sangat besar
* Spring sendiri tidaklah digunakan untuk menggantikan framework yang sudah ada, melainkan menjahit framework-framework yang sudah ada, menjadi framework yang saling terintegrasi
* Spring bisa digunakan terintegrasi dengan baik dengan Bean Validation, Java Persistence API, Servlet, dan lain-lain
* Selain itu juga Spring bisa diintegrasikan dengan teknologi yang tidak standar bawaan Java, seperti MongoDB, Consul, Vault, Cassandra, dan lain-lain

### Inversion of Control
* Inversion of Control (IoC) merupakan prinsip dalam pembuatan perangkat lunak, dimana kita melakukan pemindahan kontrol untuk objek atau program ke sebuah container di framework
* Tidak seperti biasanya ketika kita membuat aplikasi, dimana kita selalu melakukannya secara manual, dalam IoC, kita menyerahkan banyak pekerjakan ke container IoC 
* Container IoC memiliki kontrol untuk melakukan eksekusi program kita, memanajemen object pada program kita dan melakukan abstraction terhadap program kita
* Saat menggunakan framework IoC, kita biasanya akan mengikuti cara kerja framework tersebut
Spring Inversion of Control
* Spring bisa dibilang adalah framework IoC, dimana kita akan menyerahkan banyak sekali pekerjaan dalam program kita ke Spring
* * Kode program kita akan mengikuti cara kerja Spring
Diagram Inversion of Control

Configuration
* Untuk membuat ApplicationContext menggunakan Annotation, pertama kita bisa perlu membuat Configuration class
* Configuration Class adalah sebuah class yang terdapat annotation @Configuration pada class tersebut

* Kode : HelloWorldConfiguration
 
Membuat Application Context
* Selanjutnya, setelah membuat Class Configuration, kita bisa menggunakan class AnnotationConfigApplicationContext untuk membuat Application Context
* [https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/context/annotation/AnnotationConfigApplicationContext.html] 
* Kode : Membuat Application Context
