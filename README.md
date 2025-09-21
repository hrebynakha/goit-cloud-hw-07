# goit-cloud-hw-07

1. Створення S3-бакету

Відкрити AWS S3 → Buckets.
![bucket](images/bucket.png)

2. Налаштування публічного доступу до S3

Відкрити Permissions у створеному S3-бакеті.

![access](images/bucket-public-access.png)

3. Завантаження файлу в S3

Відкрити створений S3-бакет → Objects.

![file](images/file.png) 4. Створення CloudFront-дистрибуції

Відкрити AWS CloudFront → Distributions.

![distr](images/distr.png)

5. Перевірку політики кешування та доступу

Відкрити CloudFront → Distributions → Ваш Distribution → Behaviors.

![Behaviors](images/policy.png)
-->  
Cache policy (CachingOptimized) та Allowed HTTP methods (GET, HEAD).
![methods](images/methods.png)

6. Видалення ресурсів

Відкрити CloudFront → Distributions.

![deltedcf](images/delcf.png)

Відкрити S3 → Buckets, очистити бакет, видалити його.
![dels3](images/dels3.png)
