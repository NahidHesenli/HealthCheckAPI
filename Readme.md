\# HealthCheck API - Sağlamlıq İzləmə Sistemi



HealthCheck API, istifadəçilərin gündəlik sağlamlıq vəziyyətlərini izləmək, simptomlarını analiz etmək və zərurət yarandıqda onları uyğun həkim ixtisaslarına yönləndirmək üçün nəzərdə tutulmuş RESTful API sistemidir.



\## 📋 Layihə Haqqında

Bu layihə "İT Layihələrin İdarə Edilməsi" fənni çərçivəsində hazırlanır. Layihənin idarəetmə prosesləri \*\*Monday.com\*\* üzərindən, versiya idarəetmə prosesləri isə \*\*Git/GitHub\*\* vasitəsilə həyata keçirilir.



\## 🚀 Əsas Funksionallıqlar (Monday Tapşırıqları)

Layihə aşağıdakı modullardan ibarətdir və hər biri ayrı bir Git branch-i (budağı) üzərindən inkişaf etdirilmişdir:



1\.  \*\*User CRUD:\*\* İstifadəçi qeydiyyatı, giriş və profil idarəetməsi.

2\.  \*\*Symptom Management:\*\* Sistemdə təyin olunmuş simptomların və onların şiddət səviyyələrinin idarə olunması.

3\.  \*\*Daily Check-in:\*\* İstifadəçilərin gündəlik sağlamlıq göstəricilərini sistemə daxil etməsi.

4\.  \*\*Referral Logic:\*\* 3 günlük məlumat analizi nəticəsində istifadəçini müvafiq həkimə yönləndirən biznes məntiqi.

5\.  \*\*Appointment Request:\*\* Yönləndirmədən sonra növbə (randevu) sorğusunun yaradılması mexanizmi.

6\.  \*\*Notification Service:\*\* İstifadəçiyə status yenilənmələri barədə bildirişlərin göndərilməsi.



\## 🛠 İstifadə Olunan Texnologiyalar

\* \*\*Backend:\*\* ASP.NET Core Web API

\* \*\*Database:\*\* PostgreSQL

\* \*\*ORM:\*\* Entity Framework Core

\* \*\*Sənədləşmə:\*\* Swagger (OpenAPI)

\* \*\*Layihə İdarəetməsi:\*\* Monday.com

\* \*\*Versiya İdarəetmə Sistemi:\*\* Git \& GitHub



\## 📂 Git və Branch Strategiyası

Layihədə \*\*Feature Branching\*\* strategiyası tətbiq edilmişdir. Əsas kod bazasını (`main`) qorumaq məqsədilə hər bir yeni funksiya üçün ayrıca budaq açılmış və sınaqdan keçdikdən sonra birləşdirilmişdir (Merge).



\*\*İstifadə Olunan Budaq Strukturu:\*\*

\- `main`: Stabil və hazır versiya.

\- `feature/user-crud`: İstifadəçi əməliyyatları.

\- `feature/symptom`: Simptom modulu.

\- `feature/check-in`: Gündəlik qeydlər.

\- `feature/referral`: Yönləndirmə məntiqi.

\- `feature/appointment`: Növbə sistemi.



\## 👥 Komanda Üzvləri

\* \*\*Nahid Həsənli\*\* (Layihə Rəhbəri və Backend Developer)

\* \*\*Rinat\*\* (Komanda Üzvü)

\* \*\*Semidxand\*\* (Komanda

