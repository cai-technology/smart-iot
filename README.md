# CAI Bootstrap

Adaugă acest Raspberry Pi în contul tău **Smart-IoT** și îl conectează la
cluster-ul CAI Technology. După instalare nu mai trebuie să rulezi nimic
manual — addon-ul se ocupă singur de înregistrare, sincronizare oră și
heartbeat.

## După instalare — 3 pași

1. **Click „Open Web UI"** (butonul din dreapta-jos pe pagina addon-ului).
2. **Pasul 1 din 3** — introdu codul claim primit pe email de la instalator
   (formatul `ABCD-EFGH-JKLM`, 12 caractere). Spațiile și liniuțele se
   completează automat.
3. **Pasul 2 + 3** — confirmă asocierea pe `auth.caitech.ro` (login cu
   contul tău CAI) și gata.

După acești 3 pași, device-ul tău apare în dashboard la
[https://app.smart-iot.caitech.ro](https://app.smart-iot.caitech.ro)
și trimite status periodic (default la fiecare 5 minute).

## Setări recomandate

Versiunea 0.1.8+ aplică automat la prima pornire:

- **Show in sidebar** = ON — addon-ul apare în sidebar ca „Pair Device"
- **Auto update** = ON — primești update-uri ale addon-ului automat
- **Watchdog** = ON — addon-ul repornește automat dacă se oprește
- **Start on boot** = ON (default Home Assistant)

Le poți schimba oricând din UI; addon-ul nu suprascrie alegerea ta a doua
oară.

## Update-uri Home Assistant OS

Smart-IoT este testat pe HAOS-ul livrat în imaginea factory CAI. **Dacă
schimbi update channel-ul HA (Settings → System → Updates) către `beta`
sau `dev`, garanția și mentenanța se anulează** — vezi contract.
Addon-ul raportează automat versiunea HAOS la cluster; modificarea
canalului este vizibilă imediat instalatorului în dashboard.

## Suport

- **Site oficial**: [https://www.caitech.ro](https://www.caitech.ro)
- **Documentație produs**: [https://smart-iot.caitech.ro/manual](https://smart-iot.caitech.ro/manual)
- **Probleme**: contactează instalatorul tău; el are dashboard cu
  starea device-ului în timp real.
