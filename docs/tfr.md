 

# Trattamento di fine rapporto (TFR)

- TFR annuo = (RAL / 13.5) - (RAL * 0.005) = RAL * 0.069074


-  La rivalutazione annua del TFR è del 1,5% + 75% del tasso di inflazione (che si aggira sui 1.2 %)
  - quando me lo danno verrà applicata l’aliquota IRPEF media di tassazione dei cinque anni antecedenti la cessazione dell’attività lavorativa
  - garantito dall'INPS
- Posso destinarlo al [fondo pensione](fondo-pensione.md)

## Tassazione

1. Calcolo la base imponibile equivalente

   ```
   BIE = TFR_lordo * 12 / anni_lavorati
   ```

2. Calcolo l'aliquota equivalente `AE` applicando gli scaglioni IRPEF a `BIE`

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

- <https://www.altroconsumo.it/soldi/lavoro-pensione/news/fondo-pensione-riavere-indietro-i-soldi>
- <https://finanzacafona.it/2020/05/fondo-pensione-integrativa-investimento.html>

