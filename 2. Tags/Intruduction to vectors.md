# Chapter 1 – Introduction to Vectors

## Bevezetés
- A lineáris algebra középpontjában két alapművelet áll:
  - Vektorok összeadása: $v + w$
  - Számokkal való szorzás (skalárral való szorzás): $cv$, $dw$
- Ezek kombinálása adja a **lineáris kombinációt**: $cv + dw$

## Lineáris kombináció
- Fogalom: több vektor összeadása skalárral való szorzás után.
- Példa:
  - $v + w = [ \cdot ] + [ \cdot ]$
  - Ez megfelel $c = d = 1$ választásnak.
- Különböző szerepek:
  - **Egy konkrét kombináció**: pl. $c = 2, d = 1 \;\;\Rightarrow\;\; cv + dw = (4, 5)$
  - **Minden lehetséges kombináció**: $c$ és $d$ minden értéke → teljes halmaz

## Geometriai értelmezés
- $cv$: az összes ilyen vektor egy egyenesen fekszik.
- Ha $w$ nincs ezen az egyenesen → $cv + dw$ kitölti a síkot.
- Többdimenziós eset:
  - 4 vektor ($u, v, w, z$) a 4D térben → kombinációik: $cu + dv + ew + fz$
  - Kitölthetik az egész teret, de előfordulhat, hogy csak síkban vagy egyenesben vannak.

## Fejezet célja
- Központi fogalmak bemutatása, amelyekre az egész lineáris algebra épül.
- Kezdet:
  - 2D és 3D vektorok (vizuálisan ábrázolhatók).
- Kiterjesztés:
  - Magasabb dimenziók ($n$-dimenziós tér).
  - Mentális kép érvényes marad, még ha rajzolás nem lehetséges.

## A fejezet felépítése
1. **1.1 Vektorműveletek**
   - Összeadás: $v + w$
   - Lineáris kombináció: $cv + dw$
2. **1.2 Skaláris szorzat**
   - Definíció: $v \cdot w$
   - Vektor hossza: $\|v\|$
3. **1.3 Alapfogalmak**
   - Mátrix: $A$
   - Lineáris egyenletrendszer: $Ax = b$
   - Megoldás: $x = A^{-1}b$ (amennyiben $A$ invertálható)