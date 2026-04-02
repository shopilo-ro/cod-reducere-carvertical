# Cod reducere carVertical — fetch automat de pe shopilo.ro

Modul Python pentru fetch automat de **coduri de reducere carVertical** de pe [shopilo.ro](https://shopilo.ro/magazin/carvertical.com). Returneaza **cupoane carVertical** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-ro.github.io/cod-reducere-carvertical](https://shopilo-ro.github.io/cod-reducere-carvertical/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-ro/cod-reducere-carvertical
cd cod-reducere-carvertical
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "carVertical",
    "code": "SHOPILO20",
    "discount": "20%",
    "description": "20% reducere la verificarea istoricului auto",
    "expires": "2026-10-02",
    "source": "https://shopilo.ro/magazin/carvertical.com"
  }
]
```

## Cupoane carVertical disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 20% | 20% reducere la verificarea istoricului auto | [shopilo.ro](https://shopilo.ro/magazin/carvertical.com) |

Codurile active: **[shopilo.ro/magazin/carvertical.com](https://shopilo.ro/magazin/carvertical.com)**

## Intrebari frecvente

### Cum folosesc un cod de reducere carVertical?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.ro](https://shopilo.ro/magazin/carvertical.com), adauga produsele in cos pe carVertical, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele carVertical?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri carVertical?
Pagina [shopilo.ro/magazin/carvertical.com](https://shopilo.ro/magazin/carvertical.com) este actualizata zilnic cu cele mai noi cod reducere carVertical, voucher carVertical si cupon promotional carVertical.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre carVertical

carVertical este unul dintre magazinele online populare. Gasesti pe [shopilo.ro](https://shopilo.ro/magazin/carvertical.com) cele mai bune cod reducere carVertical, cupoane carVertical verificate si voucher carVertical active, actualizate zilnic.

## Instalare npm

```bash
npm install cod-reducere-carvertical
```

```javascript
const { fetchCoupons } = require('cod-reducere-carvertical');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.ro](https://shopilo.ro)
