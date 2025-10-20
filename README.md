<h1>Projekt Grupowy : System-AAL </h1>
Oficjalnie zakładam nowe repozytorium na githubie w celu przechowywania wszelkich potrzebnych plików i pomysłów do utworzenia projektów - Pan Kierownik
<br>
Zachęcam do wrzucania tutaj waszych pomysłów jak możemy realizować założenia, zbudować urządzenia, pomysły na aplikację, przydatne filmiki, linki, plany na przyszłość. Fajnie by było gdybyśmy powoli zaczęli ogarniać harmonogram i określać sobie w głowie co chcecie robić tak właściwie.

<h3> Dane kontaktowe do naszego opiekuna - dr hab. inż. Sławomira Ambroziaka </h3>
<ul>
<li>email: 
slawomir.ambroziak@pg.edu.pl</li> 
<li>tel: 
583471577 (myśle, że fake)</li>
<li>stacjonuje w EA 406</li>
</ul>
<h3>Dane kontaktowe do koordynatora projektów na WETI - dr inż. Sławomir Gajewski</h3>
<ul>
<li>email: 
slawomir.gajewski@pg.edu.pl</li> 
<li>stacjonuje w EA 434</li>
<li>konsultacje: poniedziałek 11:30 - 12:30 (lub inny termin jeśli się z nim umówimy)</li>
</ul>

<h3>Co musimy zrobić !!!!</h3>
* Zdefiniować harmonogram i dać go do zatwierdzenia opiekunowi (niektóre daty będą narzucone przez koordynatora) <br>
* Stworzyć i terminowo umieszczać w SPG (Studenckie projekty grupowe na mojaPG) wymaganej dokumentacji projektowej <br>
* Opracować plakat (w języku polskim i angielskim), umieścić go w systemie pod koniec
I semestru oraz zaaktualizować na koniec II semestru. Plakat zawiera informacje o temacie,
wykonawcach, podstawowych zadaniach i osiągniętych rezultatach; plakat studenci wykonują wg
jednolitego wzorca (patrz „zasady dokumentowania wyników); - może to skopiowałem, ale tylko może <br>
* Opracować prezentację na koniec 1 sem i wrzucić na PG <br>
* Obviously zrobić projekt i spełnić ew. dodatkowe wymagania określone przez opiekuna

<h3>Dodatkowy dysk OneDrive</h3>
https://pgedupl-my.sharepoint.com/:f:/g/personal/s198415_student_pg_edu_pl/EogACVnk2wdOuXVCr_lWY64BhTcPNu8-9S_a8h293hBznQ?e=LCc9S4 <br>
================================================================================
<h2> Poradnik klonowania repozytorium na swoj komputer i edytowania z poziomu gitbash </h2>
<ol>
  <li> Pobranie gitbasha - 
  Pierwsze co chcemy zrobic, to pobrac gitbasha na komputer (jestem pewien, ze i tak go macie po zajeciach z przeszlych semestrow, ale dla swietego spokoju dam linka) https://git-scm.com/install/windows </li>
  <li> Konfiguracja danych użytkownika - otwieramy basha, pojawi nam się okno komend. Wpisujemy dwie formułki. W mailu wpiszcie maila, z ktorego korzystacie na githubie.<br>
  git config --global user.name "Twoje Imię" <br>
  git config --global user.email "twojemail@example.com" <br>
  </li>
  <li> Klonowanie repozytorium - Aby pobrac repo na swoj komputer nalezy wpisać: <br>
  git clone https://github.com/ev3nt-h0riz0n/Projekt-Grupowy---System-AAL <br>
  Repozytorium powinno być teraz w formie foldery w Mój Komputer -> Użytkownicy -> Wasz użytkownik jakkolwiek się nazywa -> Projekt-Grupowy---System-AAL
  </li>
  <li> Sprawdzenie czy jesteście zdalnie połączeni <br>
  cd Projekt-Grupowy---System-AAL <br>
  git remote -v<br>
  Jeśli wszystko poszło git, to powinny wam się wyświetlić takie linijki: <br>
  origin  https://github.com/nazwa-uzytkownika/nazwa-repo.git (fetch)<br>
  origin  https://github.com/nazwa-uzytkownika/nazwa-repo.git (push)</li>
</ol>

<h3>Zasady korzystania z repozytorium</h3>
W związku z tym, że każde pliki są dla nas ważne - nawet stare wersje (szczególnie dokumentacji) - bardzo zachęcam do tworzenia różnych wersji i nie nadpisywania. Chciałbym też żebyście zapoznali się z ideą branchy (rozgałęzienia) na githubie. Tutaj mam na myśli kod do oprogramowania! Jest pełno filmików na yt o tym. W najbliższym czasie dodam ustawienie, że przy mergowaniu branchy będzie potrzebne zatwierdzenie dodatkowych dwóch lub jednej innej osoby z zespołu (Ik, wydaje się kontrolujące, ale to dla naszego bezpieczeństwa).

<h3>Pomysły: </h3>
* Stworzenie przykładowego trójwymiarowego projektu, który wizualizuje mniej więcej rozkład przykładowego pokoju, w którym znajdują się nasze rozwiązania, potem przy sprawozdaniach będziemy mogli np. opisać strzałeczkami różne funkcje. Jeszcze nie wiem czy chcemy osobne sprzęty np. przygotować, które można zamontować itd.

<h3>Tipy:</h3>
* Dzisiaj na wykładach z mikrokontrolerów dowiedzieliśmy się, że połączenie Zigbee z under(coś) zapewnia długą i stabliną pracę mikrokontrolerów przez parę miesięcy (przydatne)

<h3>Linki:</h3>
<ul>
  <li> https://www.aal-europe.eu - strona główna AAL </li>
  <li> https://forms.cloud.microsoft/?redirecturl=https%3a%2f%2fforms.cloud.microsoft%2fPages%2fDesignPageV2.aspx%3fsubpage%3ddesign%26FormId%3dVgN2hiIAb0i3k6LUcLulpXwXtBwY44hDiZ9RHeia7JdUNDM4R1BFWFUwNDhZUFhPWElBTEZSNjRaUi4u%26Token%3d1eedb08d73164e9fa5a7b84a12db9540%26fbclid%3dIwY2xjawNTs4JleHRuA2FlbQIxMQABHuWTceaJq_QNHwsK_LOTx6zlAMYQqrRXF0Fs_dOZopunxdmWREJzdG9uVWdt_aem_e5BhilTqJEqQfDNaFxh7Og&auth_pvr=OrgId - link do ankiety </li>
</ul>

I BŁAGAM NIE NADPISUJCIE W PRZYSZŁOŚCI PLIKÓW, JEŚLI NIE JESTEŚCIE PEWNI, ŻE DZIAŁA I BEZ KONSULTACJI DZIEKUJE
<img width="1131" height="451" alt="image" src="https://github.com/user-attachments/assets/f05ceebb-abae-4683-bfb2-4b971be0a0b3" />

