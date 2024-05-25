## Motywy WordPress i wtyczki do budowy stron

#### Wybór najlepszego darmowego motywu WordPress zależy od Twoich indywidualnych potrzeb i preferencji. 
#### Poniżej przedstawiam kilka popularnych darmowych motywów WordPress, które są dobrze oceniane przez społeczność:  

- Astra: Jest to lekki motyw, który jest bardzo szybki i oferuje różne opcje personalizacji. Jest kompatybilny z popularnymi wtyczkami jak WooCommerce, Elementor i WPBakery.  
- OceanWP: Ten motyw jest bardzo elastyczny i oferuje wiele opcji personalizacji. Jest również kompatybilny z popularnymi wtyczkami budowania stron.  
- Neve: Neve jest prostym i łatwym w użyciu motywem, który jest dobrze zoptymalizowany pod kątem szybkości. Oferuje również integrację z popularnymi wtyczkami budowania stron.  
- GeneratePress: Jest to jeden z najlżejszych motywów WordPress dostępnych na rynku. Oferuje wiele opcji personalizacji i jest kompatybilny z popularnymi wtyczkami budowania stron.  
- Zakra: Zakra jest łatwym w użyciu, elastycznym motywem, który oferuje wiele opcji personalizacji. Jest kompatybilny z popularnymi wtyczkami budowania stron.  

#### Pamiętaj, że wybór motywu zależy od Twoich indywidualnych potrzeb i preferencji. Zawsze sprawdzaj recenzje i oceny motywu, zanim zdecydujesz się go użyć.

Elementor to popularna wtyczka do budowy stron dla WordPress. Jest to narzędzie typu "przeciągnij i upuść", które pozwala na tworzenie i personalizację stron internetowych bez konieczności pisania kodu. 

Elementor oferuje szeroki zakres funkcji, takich jak: 

 - Wizualny edytor strony: Pozwala na tworzenie i edycję stron na żywo, zobaczyć zmiany na bieżąco.
 - Szablony: Elementor oferuje setki predefiniowanych szablonów, które można użyć jako punktu wyjścia dla nowych stron.
 - Widgety: Elementor zawiera wiele widgetów, które można przeciągnąć i upuść na stronę, takie jak przyciski, formularze, galerie zdjęć i wiele innych.
 - Responsywność: Elementor pozwala na dostosowanie wyglądu strony do różnych rozmiarów ekranów, takich jak komputery stacjonarne, tablety i telefony komórkowe.

Elementor jest dostępny w wersji darmowej, która oferuje podstawowe funkcje, oraz w wersji Pro, która oferuje dodatkowe funkcje, takie jak formularze, animacje, integracje z innymi usługami i wiele innych.

WPBakery to popularna wtyczka do budowy stron dla WordPress. Podobnie jak Elementor, jest to narzędzie typu "przeciągnij i upuść", które pozwala na tworzenie i personalizację stron internetowych bez konieczności pisania kodu.  

WPBakery oferuje wiele funkcji, takich jak:  
 - Wizualny edytor strony: Pozwala na tworzenie i edycję stron na żywo, zobaczyć zmiany na bieżąco.
 - Szablony: WPBakery oferuje wiele predefiniowanych szablonów, które można użyć jako punktu wyjścia dla nowych stron.
 - Elementy: WPBakery zawiera wiele elementów, które można przeciągnąć i upuść na stronę, takie jak przyciski, formularze, galerie zdjęć i wiele innych.
 - Responsywność: WPBakery pozwala na dostosowanie wyglądu strony do różnych rozmiarów ekranów, takich jak komputery stacjonarne, tablety i telefony komórkowe.

WPBakery jest dostępny w wersji płatnej, która oferuje pełny zakres funkcji i wsparcie.

### Polecenia dla dockera
1. Urochomienie projektu: 
- docker-compose -p wordpress-our-company up -d

2. Zatrzymanie projektu i usuniecie kontenerow:
- docker-compose -p wordpress-our-company down

3. Przebudownia projektu po dokoananiu zmian w pliku docker-compose.yml:
- docker-compose -p wordpress-our-company up -d --build

4. Przejście do kontenera:
- docker exec -it wordpress-our-company_wordpress_1 bash

5. Przejscie do kontenera z bazą danych i zalogowanie do bazy danych
- docker exec -it wordpress-our-company_db_1 bash
nastepnie
- mysql -u root -p // hasło: wordpress

### Informacje dodatkowe
1. http://localhost:8000 - wejscie na stronę glówną
