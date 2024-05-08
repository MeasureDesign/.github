<h1>Pravidla pro firemní GitHub</h1>
<h2>Struktura</h2>
<p>Veškeré kódy ukládáme do tematických repository --> https://github.com/MeasureDesign. Každé repository je pro nějaký tematický celek, např. 'Entrance event'. V něm pak budou jednotlivé komponenty pro GTM, BQ queries, JS soubory... Záleží na množství - lze nahrát buď jako samostatné soubory přímo do repository, nebo zařadit do složky.</p>
<b>Rozlišování nástrojů v repository</b>
<p>TBD - PS ověřuje použití tagů</p>
<b>Rozlišování uživatelů</b>
<p>TBD - PS ověřuje pricing</p>

<h2>Hlavička pro BigQuery skripty</h2>
<p>Do každého souboru pro BigQuery přidáváme hlavičku s autorem, firemním kontaktem a popisem query.</p>
<i>
  /*
  ==================================================================================
  Query Title: Sessionization of GA4 data with sources
  Description: This query is designed for defining sessions from GA4 data and attributing sources to them.
  ==================================================================================

  Vašek Jelen | MeasureDesign
  www.measuredesign.cz
  info@measuredesign.cz

  Created On: 2023-01-01
  Last Updated: 2023-01-01

  Usage:
  This query is designed for defining sessions from GA4 data and attributing sources to them.
  

  For questions or contributions, please send us an e-mail: info@measuredesign.cz
  Or submit an issue on our GitHub repository.

  ==================================================================================
*/

-- Your SQL query starts here
  
</i>
