# TRON NFT Display Test

Публичные метаданные существующих NFT #0 и #1 в TRON Shasta.

- Контракт: `TCYNtgFoHjDMY33WQLxfGRqgn69UJk9KmV`.
- Сайт: https://ms13dev.github.io/tron-nft-demo/
- JSON: [0.json](https://ms13dev.github.io/tron-nft-demo/0.json), [1.json](https://ms13dev.github.io/tron-nft-demo/1.json).
- Изображение: [nft.png](https://ms13dev.github.io/tron-nft-demo/nft.png), исходный пользовательский PNG 1254×1254 (белый щит на фиолетовом фоне).
- Внешняя ссылка NFT (`external_url`): https://amlclear.org/

GitHub Pages публикует ветку `main`, корень `/`, HTTPS включён.
Обновление содержимого JSON по этим адресам не требует перевыпуска NFT.
Имя существующей коллекции в контракте остаётся `My Product Promo` (`PROMO`); индивидуальные JSON используют нейтральное имя `TRON NFT Display Test`.

Страница не подключает кошелёк и не запрашивает подписи или операции с активами.
Поддержка полей и время обновления в TronLink/Trust Wallet зависят от приложения и индексатора; HTTP-доступность не доказывает отображение в мобильном кошельке.

## Подготовленный следующий выпуск

Для нового теста опубликованы [2.json](https://ms13dev.github.io/tron-nft-demo/2.json) и [отдельный URL исходного PNG](https://ms13dev.github.io/tron-nft-demo/nft-2-437205ca.png). В JSON есть `external_url: https://amlclear.org/`; адрес сайта также указан текстом в описании. Публикация этих файлов сама по себе не означает выпуск токена: требуется подпись владельца контракта.
