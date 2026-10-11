# TRON NFT Display Test

Публичные метаданные тестовых NFT в TRON Shasta.

- Контракт: `TCYNtgFoHjDMY33WQLxfGRqgn69UJk9KmV`.
- Сайт: https://ms13dev.github.io/tron-nft-demo/
- JSON: [0.json](https://ms13dev.github.io/tron-nft-demo/0.json), [1.json](https://ms13dev.github.io/tron-nft-demo/1.json).
- Изображение: [nft.png](https://ms13dev.github.io/tron-nft-demo/nft.png), обновлённый пользовательский PNG 2172×724 (фиолетовый щит и надпись AML).
- Внешняя ссылка NFT (`external_url`): https://amlclear.org/

GitHub Pages публикует ветку `main`, корень `/`, HTTPS включён.
Обновление содержимого JSON по этим адресам не требует перевыпуска NFT.
Имя существующей коллекции в контракте остаётся `My Product Promo` (`PROMO`); индивидуальные NFT #0–#3 называются `AML Verification Request`, как исходный NFT #1.

Страница не подключает кошелёк и не запрашивает подписи или операции с активами.
Поддержка полей и время обновления в TronLink/Trust Wallet зависят от приложения и индексатора; HTTP-доступность не доказывает отображение в мобильном кошельке.

## Выпуски с отдельными адресами изображения

NFT #2 использует [2.json](https://ms13dev.github.io/tron-nft-demo/2.json) и [предыдущее изображение](https://ms13dev.github.io/tron-nft-demo/nft-2-437205ca.png).

Для следующего NFT подготовлены [3.json](https://ms13dev.github.io/tron-nft-demo/3.json) и [обновлённое изображение](https://ms13dev.github.io/tron-nft-demo/nft-3-f44eb244.png). В JSON сохранён внешний адрес https://amlclear.org/; он также указан в описании. Файл изображения совпадает с предоставленным пользователем PNG, SHA-256: f44eb2441dcc079db6d22e2a7a04ba045585d986f40533f8c014baa780146ff3.

Публикация метаданных сама по себе не подтверждает выпуск NFT; результат проверяется по транзакции и событию Transfer в Shasta.
