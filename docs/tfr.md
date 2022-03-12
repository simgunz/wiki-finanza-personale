 

# Trattamento di fine rapporto (TFR)

- TFR annuo = (RAL / 13.5) - (RAL * 0.005) = RAL * 0.069074


-  La rivalutazione annua del TFR è del 1,5% + 75% del tasso di inflazione (indice FOI al 31 dicembre)
-  Si rivaluta il montante TFR accantonato al 31 dicembre 2019 usando il risultatodella formula sopra al 31 dicembre 2020 (il TFR accantonato nell'anno in corso non si rivaluta).
-  È garantito dall'INPS quando viene mantenuto in azienda
- Posso destinarlo al [fondo pensione](fondo-pensione.md)

## Tassazione

1. Calcolo la base imponibile equivalente

   ```
   BIE = TFR_lordo * 12 / anni_lavorati
   ```

   - `anni_lavorati` in azienda specifica

   - `BIE ~= 0.88 * RAL_medio`

2. Calcolo il valore assoluto dell'aliquota equivalente `AE` applicando gli scaglioni IRPEF a `BIE`

3. Calcolo l'aliquota media

   ```
   AM = AE / BIE
   ```

4. Calcolo il TFR netto

   ```
   TFR_netto = TFR_lordo * (1 - AM)
   ```

## Riferimenti

- [INPS - TFR dipendenti pubblici](https://www.inps.it/prestazioni-servizi/il-trattamento-di-fine-rapporto-tfr-per-i-dipendenti-pubblici)
- [ISTAT - Indice FOI](https://www.istat.it/it/archivio/30440)
- <https://www.altroconsumo.it/soldi/lavoro-pensione/news/fondo-pensione-riavere-indietro-i-soldi>
- <https://finanzacafona.it/2020/05/fondo-pensione-integrativa-investimento.html>

