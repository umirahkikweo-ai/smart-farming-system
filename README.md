# Nyaraka za Mfumo wa Smart Farming (Documentation)

## 1. Utangulizi
Mfumo wa **Smart Farming** ni mfumo rahisi wa kidijitali uliotengenezwa kwa ajili ya kuwasaidia wakulima kusimamia na kufuatilia mashamba yao kwa urahisi kupitia mtandao. Mfumo huu ni mfano (prototype) unaoonyesha jinsi taarifa za shambani kama vile unyevu wa udongo na joto zinavyoweza kuonyeshwa kwa mkulima.

## 2. Teknolojia Zilizotumika
Mfumo huu umejengwa kwa kutumia teknolojia za msingi za utengenezaji wa tovuti (Web Development), ambazo ni:
- **HTML5:** Inatumika kujenga muundo wa kurasa zote za tovuti.
- **CSS3:** Inatumika kuweka muonekano, rangi, na mpangilio mzuri unaovutia. (Imetumika _Flexbox_ na _CSS Variables_ kurahisisha kodi).

*Kumbuka: Mfumo huu hauna JavaScript (ili kurahisisha uelewa kwa sasa), hivyo mwingiliano wa kikodi (kama fomu kufanya kazi) unahitaji kuunganishwa na mfumo wa nyuma (backend) hapo baadaye.*

---

## 3. Muundo wa Faili (File Structure)
Mfumo una jumla ya faili 7 muhimu ambazo ziko kwenye folda moja. Hapa kuna maelezo ya kila faili:

### 📄 Faili la Muonekano (CSS)
* `style.css`: Hili ni faili linalodhibiti muonekano wa kurasa zote. Rangi, ukubwa wa maandishi, na mipangilio yote ipo hapa. Kwa kutumia faili moja kwa kurasa zote, inakuwa rahisi kufanya mabadiliko sehemu moja yakaathiri mfumo mzima.

### 🌐 Kurasa za HTML (Kurasa 6)
1. **`index.html` (Mwanzo):** 
   Ukurasa wa kwanza unaomkaribisha mtumiaji. Una maelezo mafupi na viungo vya kwenda kurasa nyingine.
2. **`kuhusu.html` (Kuhusu Sisi):** 
   Ukurasa unaoelezea dira, malengo, na dhumuni la mfumo huu wa Smart Farming.
3. **`huduma.html` (Huduma):** 
   Unaorodhesha huduma zinazotolewa na mfumo, kama vile umwagiliaji wa kiotomatiki, upimaji wa hali ya hewa, na ripoti za shamba.
4. **`dashibodi.html` (Dashibodi):** 
   Hili ndio jicho la mkulima. Inaonyesha hali ya shamba kwa wakati huo (Unyevu 45%, Joto 28°C) na ina kitufe cha kuwasha/kuzima pumpu ya maji.
5. **`mawasiliano.html` (Mawasiliano):** 
   Ina fomu rahisi inayomruhusu mtumiaji kujaza jina, namba ya simu, na ujumbe kisha kutuma kwa wasimamizi wa mfumo.
6. **`ingia.html` (Ingia/Login):** 
   Fomu inayomruhusu mkulima kuweka barua pepe na nywila (password) ili kuingia kwenye dashibodi yake.

---

## 4. Jinsi ya Kutumia (Kufungua Mfumo)
Kutumia au kuangalia mfumo huu ni rahisi sana, hauhitaji programu maalum za server:
1. Fungua folda lenye haya mafaili (`d:\projects\first year\smart farming syste`).
2. Bofya mara mbili (Double-click) faili lolote la HTML, kuanzia na **`index.html`**.
3. Faili litajifungua kwenye kivinjari (Browser) chako kama vile Google Chrome, Microsoft Edge, au Safari.
4. Tumia menyu ya juu (Header) kubofya na kutembelea kurasa zote.

---

## 5. Jinsi ya Kufanya Mabadiliko (Customization)

### 🎨 Kubadilisha Rangi ya Mfumo
Ikiwa unataka kubadilisha rangi (kwa mfano, kubadilisha kijani iwe bluu), huhitaji kupitia kila ukurasa.
1. Fungua faili la `style.css` kwa kutumia programu ya Notepad, VS Code au programu yoyote ya kuandikia kodi.
2. Nenda mstari wa 10 mpaka wa 14 kwenye sehemu iliyoandikwa `:root`.
3. Badilisha kodi ya rangi, Mfano: 
   ```css
   :root {
       --primary-color: #0000FF; /* Rangi Mpya (Bluu) */
       --secondary-color: #fbc02d; 
   }
   ```

### 📝 Kubadilisha Maandishi
Kama unataka kubadilisha maneno yanayoonekana kwenye tovuti:
1. Fungua ukurasa wa HTML unaotaka kubadilisha (mfano, `kuhusu.html`).
2. Tafuta maneno unayotaka kuyabadilisha (yataonekana kati ya tags za HTML kama `<p>`, `<h2>`, au `<h3>`).
3. Futa maneno ya zamani na uandike mapya. Hifadhi (Save) faili na ufungue tena kwenye browser (au ufanye Refresh).

---
*Imeandaliwa kwa ajili ya Mradi wa Mwaka wa Kwanza - Smart Farming System.*
