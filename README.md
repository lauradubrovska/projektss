# Projektss


# Euronics iPhone Datu Izguve

## Uzdevums

Šī programma ļauj iegūt informāciju par iPhone produktiem no Euronics vietnes. Lietotājs var norādīt konkrēta iPhone modeļa nosaukumu, un lietojumprogramma parādīs attiecīgos produktus ar saistītiem datiem. Lietojumprogramma parādīs tālruņa variantus ar līdzīgiem nosaukumiem, parādīs produkta attēlu, produkta cenu un saiti uz produktu. Tā arī izveido Excel failu ar visiem produktiem no Euronics tīmekļa vietnes.

## Python Bibliotēkas

Projekts izmanto vairākas Python bibliotēkas:

- `requests` - Tiešsaistes datu ieguve.
- `BeautifulSoup` - HTML analīze un datu izguve.
- `dataclasses` - Datu klasēm vienkārša sintakse.
- `xlsxwriter` - Excel failu veidošana un datu ievietošana.

## Programmatūras Izstrādes Gaita

1. **Datu Ieguve:** Izmantojot `requests` un `BeautifulSoup`, tiek iegūti dati no Euronics tīmekļa vietnes.
2. **Datu Apstrāde:** Dati tiek attīrīti un formatēti, izmantojot funkcijas kā `remove_extra_spaces`, `format_price` un `three_symbols_price`.
3. **Datu Saglabāšana:** Izstrādāta funkcija `create_excel_file`, kas saglabā apstrādātos datus Excel failā.

## Programmas Izmantošana

Programmu iespējams izmantot, ievadot komandu terminālā:

```bash
2.py <iphone_model>
Kur <iphone_model> ir vēlamā iPhone modeļa nosaukums.

## Video Par Programmas Darbību

Jūsu Programmas Darbības Video
Piemērs:
https://failiem.lv/f/drushmgpj6

Ja vēlaties iegūt informāciju par iPhone 11, izmantojot programmu, ievadiet šādu komandu:
python 2.py iPhone 11

## Biblioteka

Lai varētu izpildīt programmu, ir nepieciešams instalēt šādas atkarības:
pip install requests
pip install beautifulsoup4
pip install xlsxwriter

## Autori
Poliakov Bohdan 231RDB415 12 gr. bohdan.poliakov@edu.rtu.lv
Laura Dubrovska 231RDB049 11 gr. laura.dubrovska@edu.rtu.lv

