# git-odev
## Commit Nedir?
Commit, bir versiyon kontrol sistemi (örneğin, Git) kullanılarak yapılan bir kayıttır. Bu işlem, projenizdeki dosyalarda yapılan değişiklikleri kaydederek, bu değişiklikleri takip etmenizi ve gerektiğinde geri almanızı sağlar. Commit, projenin farklı aşamalarını ve geçmişini belgelemek için kullanılır.

## Commit Nasıl Yapılır?
Bir değişikliği commit etmek için aşağıdaki adımları izleyebilirsiniz:
   - Değişiklikleri stage'e eklemek için **`git add`** komutunu kullanın: `git add dosya_adı` veya **`git add .`** (tüm değişiklikleri ekler).
   - Commit işlemini gerçekleştirmek için **`git commit`** komutunu kullanın ve bir commit mesajı ekleyin: **`git commit -m "Commit mesajı"`**

## Birden Fazla Dosyanın Commit Edilmesi:
Birden çok dosyada yapılan değişiklikleri tek bir commit içinde toplamak için, önce tüm değişiklikleri stage'e ekleyin (`git add`) ve ardından `git commit` komutunu kullanarak commit işlemini gerçekleştirin. Bu, tüm staged dosyaları tek bir commit altında birleştirir.

## Commit Mesajlarının Önemi:
Commit mesajları, projenizin geçmişini belgelemek ve anlamak için önemlidir. İyi bir commit mesajı yazmak için şunlara dikkat edin:
   - *Kısa ve açıklayıcı olun.*
   - *Değişikliklerin neyi etkilediğini belirtin.*
   - *İlgili bir dil kullanın ve düzenli yazmaya özen gösterin.*

## Commit Geçmişi:
Commit geçmişinizi kontrol etmek ve geçmiş commit'ler arasında dolaşmak için **`git log`** komutunu kullanabilirsiniz. Bu komut, tüm commit'leri ve bunların özetlerini listeler. Eski bir commit'e dönmek için ise **`git checkout <commit_id>`** komutunu kullanabilirsiniz.

## Commit İptali:
Bir commit'i iptal etmek veya bir commit'teki değişiklikleri geri almak için **`git revert`** veya **`git reset`** gibi komutlar kullanılabilir. `git revert` ile bir commit geri alınırken, bir yeni commit oluşturulur ve bu yeni commit, seçilen commit'i geri alır. `git reset` ile ise commit geçmişi değiştirilir, bu nedenle dikkatli kullanılmalıdır.
