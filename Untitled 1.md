Rendben — oldjuk meg **analitikusan** az egyenletet:

  

$$0 = 100 \sin x \cos x - 100 \cos x - 2 \cdot 9.81$$

  

Először egyszerűsítjük:

$$0 = 100 \cos x (\sin x - 1) - 19.62$$

  

Most rendezzük:

$$100 \cos x (\sin x - 1) = 19.62$$

  

Osszuk el mindkét oldalt 100-zal:

$$\cos x (\sin x - 1) = 0.1962$$

  

Ezt most fejtsük ki:

$$\cos x \sin x - \cos x = 0.1962$$

  

Használhatjuk a szinusz kétszögre vonatkozó azonosságot:

$$\sin(2x) = 2 \sin x \cos x \quad \Rightarrow \quad \sin x \cos x = \frac{1}{2} \sin(2x)$$

  

Behelyettesítve:

$$\frac{1}{2} \sin(2x) - \cos x = 0.1962$$

  

Szorzunk kettővel:

$$\sin(2x) - 2\cos x = 0.3924$$

---

Ez egy **transzcendens** egyenlet, amit nem lehet zárt alakban megoldani trigonometrikus függvények nélkül — de **analitikusan** átalakítható más formára.

  

Tegyük fel, hogy $\cos x \neq 0$. Ekkor $\tan x$-ra kifejezhetjük.

  

Használjuk a képletet:

$$\sin(2x) = 2 \sin x \cos x = 2 \cos^2 x \tan x$$

  

Behelyettesítve:

$$2 \cos^2 x \tan x - 2 \cos x = 0.3924$$

  

Osszuk el 2-vel:

$$\cos^2 x \tan x - \cos x = 0.1962$$

  

Most fejezzük ki $\cos x$-ot $\tan x$ segítségével:

$$\cos^2 x = \frac{1}{1+\tan^2 x}$$

$$\sin x = \frac{\tan x}{\sqrt{1+\tan^2 x}}$$

  

Tehát:

$$\frac{\tan x}{1+\tan^2 x} - \frac{1}{\sqrt{1+\tan^2 x}} = 0.1962$$

  

Ez az egyenlet $\tan x$-ra már numerikusan megoldható.

De az analitikus forma eddig terjed – **nincs zárt trigonometrikus megoldása** egyszerű függvényekkel.

---

Ha viszont közelítő érték is érdekel, akkor számolhatunk:

  

Kísérletképpen nézzük meg, hol lehet a megoldás:

$\sin x \cos x$ maximuma $0.5$, tehát a bal oldal legnagyobb értéke:

$$100(0.5 - 1) - 19.62 = -69.62 \neq 0$$

Ez nem jó irányban van – próbáljunk pozitív előjelet elérni.

  

De ha $\cos x$ negatív, akkor a szorzat pozitív is lehet, tehát a megoldás $\cos x < 0$ tartományban lesz, vagyis $x \in (\pi/2, 3\pi/2)$.