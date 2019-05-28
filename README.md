[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SaxMan96/Machine-Learning-Workshop-MINI/master?filepath=WorkShopMerge.ipynb)

# Machine-Learning-Workshop-MINI

Warsztaty z uczenia maszynowego na wydziale MINI Politechniki Warszawskiej - 28 maja 2019

# Uruchomienie notebooka

Jeżeli chcesz uruchomić notebook z warsztatów zdalnie kliknij w baner na górze, a jeżeli chcesz odpalić go lokalnie będziesz musiał zainstalować kilka rzeczy:

## Git

Klikniej w [link](https://git-scm.com/downloads) i postępuj zgodnie z instukcją. Polecam zaznaczyć przy instalacji **Git Bash** i używać właśnie tej konsoli. Jeżelui już to zrobicie to sclonujcie te repozytorium:

```
git clone https://github.com/SaxMan96/Machine-Learning-Workshop-MINI.git
```

## Conda

Użyjemy Condy, żeby zainstalować wszystkie potrzebne pakiety Pythonowe. Mocno polecam zainstalowanie **MiniCondy**, chyba że ktoś jest mega fanem GUI wtedy może zainstalować Anaconda Navigator.

Tu jest [link](https://docs.conda.io/en/latest/miniconda.html), wybierzcie wersję dla **Pythona 3.7**. 
Żeby sprawdzić poprawność instalacji uruchomcie **Anaconda Promt** (Win + "Anaconda Prompt") lub na zwykłej konsoli jeżeli używacie Linuxa lub MacOS i wpiszcie:

```
conda -V
```

upewnijcie się że macie najnowszą wersję, jeżeli nie zróbcie update:

```
conda update conda
```

## Środowisko

Jeżeli udało ci się poprawnie zainstalować conde to zainstalujemy teraz wirtualne środowisko z Pythonem i pakietami. Uruchom Anaconda Prompt, przejdź do folderu z pobranym repozytorium i wpisz:

```
conda env create -f workshop-env.yml
```

To polecenie utworzy środowisko i zainstaluje pakiety.

Gdy już uda ci się ta sztuka wejdź do folderu z repozytorium, kliknij Ctrl + L, wpisz "cmd", naciśnij Enter. Jeżeli nie przestraszyłeś się tego co wyskoczyło na ekran to świetnie, lecimy dalej. 
Wpisz ```activate workshop-env```  (Jeżeli nie znaleziono takiego polecenia to oznacz, że musisz dodać conde do zmiennych środowiskowych - [link](https://stackoverflow.com/questions/44597662/conda-command-is-not-recognized-on-windows-10)) Następnie wystarczy uruchomić nasz notebook poleceniem:

``` jupyter notebook```

następnie wybieramy plik *WorkShopMerge.ipynb* i cieszymy się naszym notebookiem.
