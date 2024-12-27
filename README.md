# IoT Cihazi WAF ile Koruma

Bu çalışmada, IoT cihazlarının güvenliğini artırmak amacıyla bir Web Uygulama Güvenlik Duvarı (WAF) çözümü geliştirilmiş ve IoT cihazlarına yönelik potansiyel güvenlik tehditlerine karşı koruma sağlanmıştır. Çalışma kapsamında Ubuntu işletim sistemi, ModSecurity WAF, Nginx web sunucusu ve MJPG-Streamer aracı kullanılarak IoT cihazlarının güvenliğini sağlamaya yönelik entegre bir sistem oluşturulmuştur.

Proje sonunda gerçekleştirilen sızma testleri, WAF’ın IoT cihazlarını dış saldırılara karşı etkin bir şekilde koruduğunu ortaya koymuştur. ModSecurity’nin HTTP trafiğini analiz ederek kötü amaçlı saldırıları tespit edip engellemesi, sistemin güvenlik seviyesini önemli ölçüde artırmıştır. Bu sayede, IoT cihazlarının ağ üzerinde güvenli bir şekilde çalışması sağlanmış ve potansiyel tehditlere karşı dayanıklı hale gelmeleri hedeflenmiştir.

Sistemin etkinliği yalnızca temel saldırı türleriyle sınırlı kalmamış, daha kapsamlı güvenlik testlerine genişletilerek değerlendirilmesi önerilmiştir. Gerçek dünyadaki IoT cihazlarına entegre edilmeden önce, farklı saldırı senaryoları ile test edilmesi sistemin güvenilirliğini artırabilir. Ayrıca, ModSecurity’nin düzenli olarak güncellenmesi ve yeni tehditlere karşı uyarlanabilir hale getirilmesi, IoT cihazlarının uzun vadeli güvenliğini sağlayacaktır.

Önerilen sistemin bir diğer avantajı, açık kaynaklı yazılımların kullanılmasıyla düşük maliyetli bir çözüm sunmasıdır. Bu özellik, küçük ölçekli işletmeler ve bireysel kullanıcılar için de erişilebilir ve uygulanabilir bir çözüm geliştirilmesine olanak tanır.

Sonuç olarak, bu çalışma, IoT cihazlarının siber tehditlere karşı korunmasında WAF kullanımının önemini bir kez daha vurgulamaktadır. Gelecekteki çalışmalar, IoT güvenliğini artırmak amacıyla daha gelişmiş algoritmalar ve yapay zeka tabanlı çözümlerle desteklenebilir. IoT güvenliği hızla gelişen bir alan olduğundan, bu tür sistemlerin sürekli olarak izlenmesi ve güncellenmesi gerektiği unutulmamalıdır.

