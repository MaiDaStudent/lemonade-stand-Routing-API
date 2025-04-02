# 🍋 Lemonade Stand App – React, Routing & Redux

Dette projekt er lavet som en del af en skoleopgave i faget React, hvor formålet er at bygge en "Lemonade Stand"-webapp med:

- 🔁 React Router
- 🧠 Redux Toolkit (global state)
- 🍹 API-integration (TheCocktailDB)
- 🛒 Indkøbskurv (Cart)

---

## ✨ Funktioner

✅ Hjemmeside med dynamisk profit (Redux)  
✅ Shop-side med citron-drinks hentet fra ekstern API  
✅ Knapper der tilføjer produkter til indkøbskurven  
✅ Kurv-side med mulighed for at øge/mindske antal eller fjerne produkter  
✅ Total antal produkter vises  
✅ Projektstruktur med `components/`, `pages/` og `redux/`

---

## 🧭 Routing (via React Router)

| URL           | Side      | Beskrivelse                            |
|---------------|-----------|----------------------------------------|
| `/`           | Home      | Viser profit og velkomst               |
| `/shop`       | Shop      | Henter citron-drikke via API           |
| `/cart`       | Cart      | Viser kurv, rediger og fjern varer     |

---

## 🧠 Global State med Redux Toolkit

### profitSlice
- `sellLemonade` ➕ +$5  
- `buyLemons` ➖ -$2  

### cartSlice
- `addToCart`
- `removeFromCart`
- `increaseQuantity`
- `decreaseQuantity`

---

## 🍹 Data: Cocktail API
Citron-drikke hentes fra: https://www.thecocktaildb.com/api/json/v1/1/search.php?s=lemon


---

## 🚀 Sådan starter du appen

1. Installer afhængigheder:
```bash
npm install