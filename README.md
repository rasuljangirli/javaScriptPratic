## JAVASCRIPT başlanğıc səviyyədən irəli səviyyəyə qədər

Medium hesabımda məqalələrimlə tanış olmaq üçün [klikləyin](https://medium.com/@rasuljangirli).
 

Bu repomda həm öyrənmə həm də öyrətmə prosesində istifadə etdiyim proyektlər yer alır. Ümumilikdə repoda olan proyektlərdə hər mövzuya toxunmağa çalışmışam. Ənənəvi qayda olarağ ilk öncə sadə daha sonra isə nisbətən mürəkkəb kodlar yazılacaq. Önəmli olan `JavaScriptin` bizə təqdim etdiyi funksionallıqları yerli yerində düzgün şəkildə istifadə etməkdir. Çalışın kod sətirlərini incələdikdən sonra ilk öncə kodları özünüz yazmağa cəhd edin və özünüzdən əlavələrdə edin. Təbii olarağ fərqli yollarla da yaza bilərsiniz, müxtəlif yol və üsullar mövcuddur. Əsas məsələ lazım olan yerə ən qısa yoldan, ən sərfəli formada və təhlükəsiz şəkildə çatmağıdır. Uğurlar olsun :)


### PROYEKTLƏR HAQQINDA MƏLUMAT:

  * ### Bədən Kütlə Indeksi - filename: `bodyMassIndex`
    
    Bu faylda bizə gələn iki dəyər `Boy` və `Çəki` əsasında müəyyən hesablama ilə bir dəyər alırıq. Daha sonra isə `if else` ilə müəyyən dərəcələr qoyuruq ki, dəyər bu aralıqdadırsa, çıxış dəyəri bu olsun; yox, əgər digər aralıqdadırsa, çıxış dəyəri bu olsun. Əsas məqsəd gələn dəyərlər əsasında müəyyən bir dəyər hesablaya bilmək və həmin dəyərin hansı aralıqda olduğunu yoxlayaraq müəyyən nəticə çıxarmaqdır.



  * ### Həftənin Günləri - filename: `DaysOfTheWeek`
  
    Bu proyektdə `Javascriptin` bizə təqdim etdiyi `switch` və ` case`-dən istifadə etdik. Sadə bir təcrübə ilə bu funksionallıqdan istifadə etmiş olduğ. Burada səhivə açıldıgı zaman istifadəçinin qarşısına bir `prompt` çıxır və içərisində mətn var. İstifadəçi bu mətndə seçimlərini görür. həftənin hər hansı gününü seçdikdə o `console` vasitəsi ilə istifadəçiyə göstərilir. əgər aralığ xaricində seçim edərsə Error )) yazısı çıxır. 
    

  * ### ATM App - filename: `atmApp`
    
      Bu proyektdə də `Javascriptin` bizə təqdim etdiyi `switch` və ` case`-dən istifadə etdik. Təbii ki gerçək ATM daha fərqli dərin alqoritimlərlə işləyir. Biz sadəcə sadə formada buna bənzər bir proyekt hazırladıq. Önəmli olan kodu incələməkdir və özünüzdən əlavələr etmək başqa yollarla eyni kodu yazmaqdır. Burada istifadəçinin balansı öncədən bir dəyərə bərabərdir. Daxil edilən dəyər əsasında yani istifadəçinin seçimi nəticəsinə ekrana uyöun cavablar çıxarırıq

  * ### Vurma Cədvəli - filename: `multiplicetionTable`
      
      Bu proyektdə `for loop` istifadə edilərək iç-içə dövrlər yazılmışdır. Burada biz vurma cədvəlini yazmaq üçün iki dövür yazmışıq və bu dövrlər iç-içə olduğu üçün ən kənar loop məcbur içindəki loop-un işini bitirməsini gözləyəcək. Bu zaman ən xaricdə olan loopun dəyəri sabit qalaraq içdəki loop daxilindəki proseslərə tabe olacaq. İç loop bitdikdən sonra artıq kənardakı loop növbəti dəyəri vermiş olacaq. Bu formada müəyyən bir `console` çıxdısı alırıq.

  * ### Sadə Ədəd - filename: `primeNumber`
      
      Bu proyektdə `for loop` və `if else` istifadə edilərək daxil edilən rəqəmin (ədədin) sadə olub olmadığını yoxlayırıq. Ümumilikdə kodlar arasında da qeydlər yazılmışdır. Qeydlərə baxaraq kodu daha aydın anlamağ mümkündür.

  * ### Factorial tapmağ - filename: `findingFactorials`
    
      Burada sadə bir şəkildə factorial tapmağ üçün `for` yazmışığ. Ümumilikdə çox sadə gələ bilər sadəcə başlanğıc səviyyədəsinizsə bu sizin üçün sizin zehninizin javascriptdə görüləcək işlər və yazılacaq kodlar üçün əla təcrübədir. Çalışıb bu kodları fərqli formalarda yazın özünüzdən əlavələr edin dəyişgənlərin yerini dəyişdirin v.s.

  * ### Armstrong ədəd tapmağ - filename: `findingArmstrongNumber`
      
    BU kodları anlamağ üçün ilk öncə Armstrong ədəd nədir onu bilmək lazımdır. Kod daxilində bununla bağlı qeydim mövcuddur. Daha sonra isə kod sətrində ilk öncə biz `for` ilə ədədin hər bir rəqəmini tuta biləcək şəkildə dövr edirik. Bu tutulan rəqəmlər üzərində əməliiyat aparıb müəyyən dəyişgəndə bunu saxlayırıq. daha sonra isə `if else` ilə yoxlama işi aparırığ və buna uyğun nəticə göstərilmiş olur.

  * ### Hərf tapmağ - filename: `findingLetter`
      
    Burada isə bizim yazdığımız kod gələn mətnin içində bir hərfin nə qədər olduğunu tapır. Burada diqqət edilməli olan məqam kodun böyük kiçik hərfləri fərqli element olarağ qəbul etməsidir. Əgər bunu aradan qaldırmağ istəyiriksə `if` blokunda yoxlama hissəsində hər iki tərəfi ya böyük hərflərə çevirib yada kiçik hərflərə çevirib yoxlama apara bilərik.


  * ### Mükəmməl ədəd tapmağ - filename: `findingPerfectNumber`
      
    Bu kodu yaza bilmək üçün ilk öncə mükəmməl ədədin nə olduğunu bilmək lazımdır. Bununla bağlı kod daxilində xüsusi qeydlər və izah mövcuddur. Qısa olarağ isə burada məlumat olarağ deyim ki bu kod parçasında `function` `for` `if else` istifadə edərək daha sonra `let` ilə dəyişgən təyin edilməsi və ona müxtəlif təsirlərin olunmasını görə bilirik. 

  * ### Product tapmağ - filename: `productSearch`
      
    İlk öncə, müəyyən **məhsullar** (product) haqqında məlumat toplusu yaratdıq. Bu məlumatları **productList** adlı array-də topladıq. Daha sonra istifadəçidən gələn məhsul adı ilə **productList** array-indəki məlumatların **productName** hissələrini qarşılaşdırdıq və uyğun gələn adlara sahib məlumatları başqa bir array-ə **push** metodu ilə, yəni **filtr edilmiş** array-ə əlavə etdik. Artıq əlimizdə istifadəçinin istədiyi filtr edilmiş məlumatlar mövcuddur. 

    Sonrakı addım bu məlumatları istifadəçiyə təqdim etməkdir. Bunun üçün başqa bir **funksiya** yazdıq və bu filtr edilmiş məlumatların toplandığı array-i həmin funksiyaya parametr olaraq verdik. Funksiya daxilində sadəcə bu array üzərində dönərək lazım olan hissələri ekrana **console** vasitəsilə yazdırırıq.

    Normalda bu məlumatlar bizə **API** sorğuları etdiyimiz zaman back-end tərəfindən gələcək. Bu halda özümüzün məlumat yaratmağımıza ehtiyac olmayacaq. Burada yalnız müəyyən funksionallıqları göstərmək üçün bu formada məlumat yazdıq.

  * ### Todo List - filename: `todoList`
      
    Bu layihə, əvvəlki layihələrlə müqayisədə daha geniş kodların yazıldığı bir proyekt olaraq qarşımıza çıxır. Bu **todo siyahısında** (todo list) todo əlavə edilməsi, onların **filtr edilməsi**, istənməyən todoların **silinməsi** və ya **hamısının silinməsi** kimi funksionallıqlar mövcuddur.

    Kod tərəfinə nəzər yetirsək, məlumatların saxlanması üçün **local storage**-dən istifadə olunduğunu görərik. Bundan əlavə, istifadəçi məlumat daxil etmədən klik etdiyi zaman müəyyən **məhdudiyyətlər** və **bildirişlər** göstərilir. Eyni qaydada, heç bir todo olmadığı halda filtr etdiyimiz zaman da **bildiriş** çıxarılması nəzərdə tutulub.

    **Xüsusi bir tapşırıq** olaraq, filtr inputunda heç bir dəyər olmadığı halda belə `Backspace` (sil) düyməsinə basıldığında **bildiriş** çıxır. Bu problemi aradan qaldırarağ düzəliş edə bilərsiniz:)


    
---

Medium hesabımda məqalələrimlə tanış olmaq üçün [klikləyin](https://medium.com/@rasuljangirli).
