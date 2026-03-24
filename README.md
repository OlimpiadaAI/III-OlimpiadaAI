# III Olimpiada Sztucznej Inteligencji / 3rd Polish AI Olympiad
<p align="center">
  <img src="logo_oai.png" alt="LogoIIIOAI" width="30%">
</p>

Witamy w repozytorium z zadaniami III Olimpiady Sztucznej Inteligencji. Olimpiada jest skierowana do uczniów szkół średnich i podstawowych z całej Polski, którzy interesują się sztuczną inteligencją. Celem jest zwiększenie zainteresowania AI i wyłonienie składów reprezentacji na zawody międzynarodowe.

## Informacje ogólne
**Strona główna:** [Olimpiada Sztucznej Inteligencji](https://www.oai.edu.pl/o-olimpiadzie)

Trzecia edycja Olimpiady odbędzie się w trzech etapach:
- Pierwszy etap, online, 01.12.2025 - 25.01.2026. 
- Drugi etap, regionalny, w Krakowie, Poznaniu, Warszawie i Wrocławiu, 13 - 15.03.2026 
- Trzeci etap, finał, w Poznaniu, 17 - 19.04.2026. 

Regulamin jest dostępny na naszej [stronie](https://www.oai.edu.pl/dokumenty/regulamin).

Oficjalnym kanałem komunikacji z uczestnikami będzie platforma Discord. Dostęp do niej otrzymują uczestnicy po dokonaniu rejestracji.

## Zadania
W ramach pierwszego etapu Olimpiady uczestnicy zmierzą się z następującymi wyzwaniami:
1. **Filtry konwolucyjne** - Wprowadzenie do jednej z najważniejszych metod wizji komputerowej
2. **Klasyfikacja wieloetykietowa** - Przetwarzanie obrazków zawierających różne obiekty
3. **Szept czy krzyk** - Klasyfikacja danych audio
4. **Zmiany semantyczne** - Analiza zanurzeń słów pod kątem zmiany znaczenia
5. **Segmentacja multispektralna** - Segmentacja obrazów satelitarnych

Uwaga: Kolejność zadań w pierwszym etapie została ustalona tak, aby ich trudność stopniowo rosła. Pamiętaj jednak, że odbiór poziomu trudności jest kwestią indywidualną. Jeśli napotkasz trudności przy konkretnym zadaniu, spróbuj zmierzyć się z zadaniem o wyższym numerze — może okazać się dla Ciebie łatwiejsze.

W drugim etapie uczestnicy mierzyli się z zadaniami:
1. **Optymalizator Malarza** -- odtwarzanie hiperparametrów użytych do wygenerowania obrazu.
2. **Predyktor Tokenów** -- przewidywanie, które podsłowa pojawią w suffiksie danego promptu.
3. **Drzewa Decyzyjne** -- automatyzacja procesu przekształcenia danych oraz doboru hiperparametrów.
4. **Kolorowanie z GANem** -- odtwarzanie kolorowych wersji, z monochromatycznych obrazów

## Sposób oddawania zadań
Uczestnicy będą rozwiązywać zadania samodzielnie i przesyłać je do Komitetu Merytorycznego za pomocą Platformy Konkursowej. Dostęp do niej jest udostępniany uczestnikom po rejestracji. Każde zadanie będzie wymagało przesłania pliku Jupyter Notebook z rozwiązaniem. Wszystkie prace będą oceniane automatycznie na Platformie Konkursowej.

## Środowisko
Lista dopuszczalnych pakietów znajduje się w pliku `environment.yml`, osobno dla każdego zadania. Rozwiązania były testowane przy użyciu Pythona 3.11/3.12. Na potrzeby pracy nad zadaniami, zalecamy wykorzystanie środowiska online [Google Colab](https://colab.google/). lub stworzenie środowiska lokalnego z wykorzystaniem [Anacondy](https://docs.anaconda.com/) (instrukcję instalacji środowiska z pliku YML znajdziesz [tutaj](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file)).


> Uwaga: To samo rozwiązanie uruchomione w środowisku lokalnym lub Google Colab może zwracać inne wyniki niż na Platformie Konkursowej. Ostateczna ocena Twojego zadania zostanie wyliczona na Platformie Konkursowej.

## Kryteria oceny
Oceny za zadania zostaną wyliczone na podstawie podanych w treściach zadań kryteriów. Za każde zadanie w pierwszym etapie uczestnicy mogą zdobyć maksymalnie 100 punktów.

## Licencje
Repozytorium korzysta z następujących zasobów objętych licencjami:
- Zbiór danych `HistWords`, licencja Apache 2.0
```
William L. Hamilton, Jure Leskovec, and Dan Jurafsky. ACL 2016. Diachronic Word Embeddings Reveal Statistical Laws of Semantic Change.
```
- Zbiór danych `Fashion MNIST`, licencja MIT
- Zbiór danych zadania `Filtry konwolucyjne` został zebrany z obrazów dostępnych na stronie `https://unsplash.com/`, na [licencji](https://unsplash.com/license)
- Zbiór danych `BigEarthNet` użyty w zadaniu `Segmentacja multispektralna`, dostępny na licencji [CDLA permissive 1.0](https://cdla.dev/permissive-1-0/)
- model [GPT2XL](https://huggingface.co/openai-community/gpt2-xl), licencja MIT.
```
@article{radford2019language,
  title={Language models are unsupervised multitask learners},
  author={Radford, Alec and Wu, Jeffrey and Child, Rewon and Luan, David and Amodei, Dario and Sutskever, Ilya and others},
  journal={OpenAI blog},
  volume={1},
  number={8},
  pages={9},
  year={2019}
}
```
- model StyleGAN, licencja MIT
```
@misc{karras2020analyzingimprovingimagequality,
      title={Analyzing and Improving the Image Quality of StyleGAN}, 
      author={Tero Karras and Samuli Laine and Miika Aittala and Janne Hellsten and Jaakko Lehtinen and Timo Aila},
      year={2020},
      eprint={1912.04958},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/1912.04958}, 
}
```
- Zbiór danych w zadaniu `Kolorowanie z GANem` pochodzi ze strony `https://thispersondoesnotexist.com/`

## Kontakt
W razie pytań lub wątpliwości, prosimy o kontakt przez platformę Discord lub e-mail: [oai@cs.uni.wroc.pl](mailto:oai@cs.uni.wroc.pl) albo wiadomości bezpośrednio na Platformie Konkursowej (można ustawić, aby były widoczne tylko dla Komitetu Merytorycznego tzw. wiadomości prywatne).

Życzymy powodzenia w rozwiązywaniu zadań!
