# PCA-Mini-Project-for-Face-Recognition
In this project we have utilized eigen value and vector to recognise faces.

در این پروژه، از یک دیتاست مربوط به دسته‌بندی چهره‌ها استفاده شده است که داده‌های آن به دو صورت عکس وآرایه می‌باشد.

با استفاده از تابع PCA ۱۵۰ کامپوننت اصلی پیدا شده و توسط آن یک آرایه جدید که تشکیل شده از ۱۵۰ عکس است ساخته می‌شود.
آرایه جدید همان eigenfaces می‌باشد.
در واقع در هر سطر از این آرایه جدید، مختصات جدیدی یافت شده که اطلاعات مربوط به ۱۸۵۰ feature را خلاصه می‌کند. یعنی سطر اول آن بیشترین اطلاعات را در خود دارد و به همین ترتیب کمتر می‌شود.
بنابراین با استفاده از این کامپوننت‌ها داده‌های آموزشی جدید با انجام transform روی داده های آموزشی قدیمی بدست می‌آید.