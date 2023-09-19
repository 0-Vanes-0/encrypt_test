# encrypt_test

Прогресс работы:

1. Был выполнен поиск библиотеки в Интернете
2. Выбрана openssl, скачана
3. Чтение help и примеров в StackOverflow
4. Для шифрования использовалась команда: openssl enc -in secret_info.txt -out si.enc -e -aes256
5. Был введён кастомный пароль (хотя можно подать файл, внутри котоорго написан ключ)
6. Для дешифровки использовалась команда: openssl enc -in si.enc -out secret_info_decrypted.txt -d -aes256
7. Файлы secret_info.txt и secret_info_decrypted.txt были проверены н совпадение
