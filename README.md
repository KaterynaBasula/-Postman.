Встановлюємо Postmen, відкриваємо його та створюємо новий запит типа GET.

![image](https://github.com/user-attachments/assets/ab64e362-79b6-4aaf-8642-9ed9aea30b9a)

Параметри запиту:
start=YYYYMMDD – Дата початку періоду у форматі YYYYMMDD без
роздільників;
end= YYYYMMDD – Дата завершення періоду у форматі YYYYMMDD без
роздільників;
valcode=usd – символьний код валюти (не обов’язковий параметр), якщо цей
параметр не заначено, то у результаті буде вибірка за період по всім валютам;
sort=exchangedate – назва поля по якому виконується сортування (exchangedate/
r030/сс/rate);
order= desc - метод сортування (desc – за спаданням, asc – за зростанням);
json- формат надання інформації.

У моєму прикладі ми дізнаємося курс НБУ з 23.09.2024 по 29.09.2024.
Натискаємо Sent та бачимо результат.

![image](https://github.com/user-attachments/assets/51a6468b-b453-4522-b660-474a04ef7237)

Тепер отримаємо курс НБУ у форматі XML.

![image](https://github.com/user-attachments/assets/4f4b6db3-4356-4b11-9cad-913ada49a481)

Як можна побачити запит GET відрізняється тільки тим, що у кінці ми не додаємо &json.
Натискаємо Sent та бачимо наступний результат.

![image](https://github.com/user-attachments/assets/f764e2e9-ec26-4328-b5c2-baeafd79cd14)

