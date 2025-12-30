# 🧾 LIDL Pirkimų Istorijos Analizė

### 🚀 [Atidaryti filą Google Colab](https://colab.research.google.com/drive/1VOIMMLCs3-OrqgzJRraDMctA6CC0E861?usp=sharing) - *Spustelėkite nuorodą, kad atidarytumėte notebook’ą ir paleistumėte jį iš karto!*

Šis Jupyter/Colab notebook’as leidžia paprastai peržiūrėti **Jūsų** „Lidl“ pirkimų statistiką, jei naudojatės LIDL programėle.  
Projektas skirtas **mokymuisi ir asmeniniam naudojimui**.  

Notebook automatiškai surenka Jūsų kvitus, apdoroja duomenis ir pateikia duomenis apie:

- Bendrai išleistą sumą
- Vidutinį pirkinių krepšelio dydį
- Išlaidas pagal parduotuves
- Išlaidas pagal metus ir mėnesius

---

## 🔑 Prisijungimas prie „Lidl“ duomenų

Kad notebook’as galėtų surinkti Jūsų pirkimus, reikia **asmeninio prisijungimo rakto (auth token)**.

> ⚠️ **SVARBU**
>
> - Rakto **negalima dalintis**  
> - Jis **laikinas ir asmeninis**  
> - Baigus darbą, rekomenduojama **ištrinti raktą**

---

## 🧭 Kaip įrašyti savo auth token

1. Prisijunkite prie savo „Lidl“ paskyros naršyklėje  
2. Paspauskite **F12** (atidarys kūrėjo įrankiai)  
3. Suraskite Cookies/Slapukai:
   - 🦊 **Firefox**: Storage/Saugykla → Cookies  
   - 🌐 **Chrome**: Application/Programa → Storage → Cookies  
4. Pasirinkite svetainę `https://www.lidl...`  
5. Nukopijuokite **authToken**  
6. Įklijuokite jį į notebook’ą
7. Google Colab paspauskite Run all / Vykdyti viską
8. Palaukite ~30–60 sekundžių kol bus atlikta analizė

>🔒 Visi rezultatai generuojami tik Jūsų Colab kopijoje.
