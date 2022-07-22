
# Version Control System (Versiya Nəzarət Sistemi VNS)
## VNS nədir? 

VNS kodda edilən dəyişiklikləri fayllar şəklində qeyd etməyə kömək edən proqram nəzarət vasitəsidir. 

### VNS-nin önəmi

Proqram kodları bir qrup proqramçı tərəfindən birgə hazırlanır. Hər bir proqramçı müxtəlif məkanlarda ola bilər. VNS tam olaraq bu anda öz faydasını göstərir. VNS mənbə koduna olan dəyişikliklərin kim tərəfindən və nə edildiyi kimi məlumatları səmərəli şəkildə izləməyə kömək edən proqram təminatıdır.
Əsasən Versiyaya nəzarət sistemi müəyyən proqram təminatında edilən dəyişiklikləri izləyir və hər modifikasiyanın qeydə alır. Əgər əlavə edilən yeni xüsusiyyətlər düzgün işləmirsə, versiyaya nəzarət sistemi bizim işimizi izlədiyi üçün yeni dəyişiklikləri yox sayıb əvvəlki versiya ilə davam etməyimizi təmin edir. 

Versiya nəzarət sisteminin üstünlükləri:
-	Səmərəli əməkdaşlıq qazandırır,
-	layihənin inkişaf sürətini artırır,
-	yaxşı ünsiyyət yardımı artırır və beləcə məhsuldarlığı artırır, 
-	məhsulların çatdırılmasını və işçilərin bacarıqlarını sürətləndirir,
-	mütəmadi izləmə ilə xətaları və ortaya çıxa biləcək fəlakətləri azaldır,
-	məkan məhdudiyyətini aradan qaldırır,
-	hər yeni versiya üçün fərqli nüsxə saxlayır,
-	versiya təsdiqlənmədiyi müddətcə əsas fayla birləşdirilmir.
-	Kimin nə zaman, nə üçün və nə kimi dəyişikliklər etdiyi barədə məlumat verir 
- Ən məşhur nümunə Git, Helix core, Microsoft TFS,

## Versiya İdarəetmə Sisteminin istifadəsi: 

### Anbar

Layihə zamanı dəyişikliklərin tutulduğu yer. 

### İşin nüsxəsi (bəzən yoxlama kimi də adlandırılır)

Başqalarının işinə təsir etmədən bütün faylların şəxsi surəti üzərində redaktə edə bilərsiniz. 	Edilmiş dəyişiklikləri depoya köçürə bilərsiniz. 

### Qrupda işləmək

Mənbə kod üzərində istədiyini kimi dəyişiklik edə bilməzsiniz. Çünki bu istifadəçiyə narahatlıq yarada bilər. Komandada işləmək, əməkdaşlıq etmək və onların dəyişikliklərinə uyğunlaşmaq lazımdır. VNS arzuolunmaz dəyişikliklərin qarısını alır. 

## Versiyaya Nəzarət Sistemlərinin növləri:  
-	Yerli Versiya Nəzarət Sistemləri – YVNS 
-	Mərkəzləşdirilmiş Versiya Nəzarət Sistemləri – MVNS 
-	Paylanmış Versiya Nəzarət Sistemləri - PVNS

### YVNS
-	YVNS lokal kompüterinizdə yerləşən və hər bir fayl dəyişikliyinin patch kimi saxlandığı yerli verilənlər bazasıdır. Hər bir patch dəsti yalnız son versiyasından bəri fayla edilmiş dəyişiklikləri ehtiva edir. Faylın hər hansı bir anda necə göründüyünü görmək üçün həmin ana qədər fayla bütün müvafiq patch-ləri əlavə etmək lazımdır.
-	Əsas problem hər şeyin lokal olaraq saxlanmasıdır. Əgər bazaya nəsə olsa bütün patch-lər itər. Əgər tək bir versiyaya nəsə baş versə o versiyadan sonra edilən bütün dəyişikliklər itərdi.
-	Həmçinin, komanda ilə əməkdaşlıq etmək demək olar ki, mümkün deyil.

### MVNS
-	MVNS-də bütün fayl versiyaları bir serverdə tutulur.
-	MVNS istifadəçinin eyni vaxtda fayllara daxil olmasına, serverdən lokal kompüterinə fayl çəkməsinə, lokal kompütedən serverə fayl ötürməsinə imkan verir.
-	Layihədəki hər kəsin nə etdiyi bu versiyada bilinir. 
-	Komanda ilə asan əməkdaşlıq etməyə imkan verir.
-	Əsas problem hər şeyin mərkəzləşdirilmiş serverdə saxlanmasıdır. Çünki serverdə nəsə baş verərsə, heç kim versiya dəyişikliklərini saxlaya, faylları çəkə və ya ümumiyyətlə əməkdaşlıq edə bilməyəcək. 
-	Mərkəzləşdirilmiş versiya idarəetmə sistemlərinin ən məşhur nümunələri Microsoft Team Foundation Server (TFS) və SVN-dir.

### PVNS
-	PVNS-də hər kəs bütün layihənin lokal nüsxəsinə sahibdir.
-	Bu modellə, əgər server əlçatmaz olarsa, müştəri anbarlarından hər hansı biri layihənin versiyasının surətini istənilən digər müştəriyə göndərə və ya əlçatan olduqda yenidən serverə göndərə bilər. Bir müştəridə daha sonra asanlıqla yayıla bilən düzgün bir nüsxə olması kifayətdir.
-	Git paylanmış versiya idarəetmə sistemlərinin ən məşhur nümunəsidir.

## İstinadlar

Bu yazı aşağıdaki mənbələrdən yararlanılaraq hazırlanmışdır:

- https://serengetitech.com/tech/introduction-to-git-and-types-of-version-control-systems/
- https://www.geeksforgeeks.org/version-control-systems/
- https://www.educba.com/jira-vs-github/ 
