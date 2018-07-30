## Warsztat: sieci neuronowe
Warsztat ma na celu zapoznanie z koncepcją sieci neuronowych (głębokich) oraz z narzędziami niezbędnymi do jej zastosowania. W ramach tego ćwiczenia użyte będą biblioteki: TensorFlow oraz Keras.

### Przed warsztatem
Przed warsztatem należy odpowiednio przygotować swój komputer. Niezbędne oprogramowanie obejmuje:

- program git do pobrania materiałów szkoleniowych
- pakiet Anaconda służący do zarządzania wersjami Pythona.

#### Git oraz niezbędne repozytoria
Przed szkoleniem należy pobrać i zainstalować program git. Jest on dostępny w wydaniach dla systemu:
 
 - [Windows](https://git-scm.com/download/win)
 - Linux (należy wykorzystać instrukcje instalacji odpowiednie dla posiadanej dystrybucji)
 - [Mac](https://git-scm.com/download/mac)

Kolejnym krokiem jest sklonowanie tego repozytorium:
 ```git@github.com:Semantive/workshop-deeplearning.git```. W dniu szkolenia zaleca się zaktualizowanie wersji kodu poprzez polecenie ```git pull``` wywołane w katalogu z repozytorium.
 
#### Anaconda
Pakiet Anaconda można pobrać z [tej witryny](https://www.anaconda.com/download/). Należy wybrać wersję odpowiednią dla swojego systemu operacyjnego. Na potrzeby warsztatu należy wybrać wersję dla języka Python 3.6.
 
Po zainstalowaniu pakietu i uruchomieniu programu _Anaconda Navigator_  należy dodać niezbędne biblioteki: _TensorFlow_ oraz _Keras_. Aby to wykonać, niezbędne są następujące kroki:
 
1. Przy uruchomionym _Anaconda Navigator_ należy wybrać zakładkę _Środowiska_ (_Environments_).
2. Dla wybranego środowiska (domyślnie: _base (root)_) z wybieraka (_dropdowna_) należy zmienić filtr z pakietów zainstalowanych (_Installed_) na wszystkie (_All_).
3. Korzystając z wyszukiwarki obok dropdowna należy wyszukać oba pakiety. Dla każdego z pakietów należy zaznaczyć pole po lewej stronie nazwy.
  - _tensorflow_ (nie: _r-tensorflow_),
  - _keras_.
4. Aby zainstalować pakiety, pod listą dostępnych paczek należy kliknąć przycisk _Apply_ i potwierdzić swój wybór poprzez przycisk _Apply_ w nowym oknie dialogowym.

#### Notatnik testowy
Aby uniknąć niespodzianek podczas warsztatu należy wykorzystać (i uruchomić) dostarczony w repozytorium notatnik testowy. W tym celu:

1. W programie _Anaconda Navigator_ należy wybrać widok _Home_, a następnie uruchomić (_Launch_) program _Jupyter_. W oknie przeglądarki zostanie otworzona karta z programem.
2. W otwartej karcie należy przejść do katalogu z repozytorium i otworzyć plik ```Notatniki/00_NN_Test_poprawnosci_instalacji.ipynb```.
3. W otwartym notatniku należy uruchomić wszystkie kolejne komórki (w kolejności od góry do dołu). Można to wykonać uruchamiając komórki oddzielnie (np. poprzez kombinację `CTRL+ENTER` bądź wszystkie naraz poprzez `Cell->Run All`.