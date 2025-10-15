# Fully Dressed Use Case

**ID:** UC-1  
**Heiti:** Skoða og framkvæma dagáætlun sjúklinga  
**Aðal aðili:** Starfsmaður sambýlis  
**Aukaaðilar:** Sjúklingar, Kerfisstjóri  

## Forsendur
- Starfsmaður er skráður inn í kerfið með réttum aðgangi.  
- Dagáætlun sjúklinga hefur verið búin til fyrir daginn.  
- Starfsmaður hefur aðgang að snjalltæki með uppsettu forriti.  

## Eftirskilyrði
- Verkefni dagsins hafa verið merkt sem framkvæmd eða lokið.  
- Kerfið hefur haldið utan um hvaða verkefni hafa verið framkvæmd og hvenær.  
- Ef verkefni hafa ekki verið framkvæmd innan tilskilins tíma, hefur kerfið sent tilkynningar.

## Aðalflæði
1. Starfsmaður skráir sig inn í kerfið.  
2. Kerfið birtir lista yfir sjúklinga sem starfsmaður er ábyrgur fyrir þann dag.  
3. Starfsmaður velur sjúkling til að skoða dagáætlun hans.  
4. Kerfið birtir skipulag dagsins, þar með talið lyfjagjafir, viðburði og aðrar athafnir.  
5. Starfsmaður framkvæmir verkefni samkvæmt áætlun.  
6. Þegar verkefni er lokið, merkir starfsmaður það sem „lokið“ í kerfinu.  
7. Kerfið skráir tímann og uppfærir stöðu verkefnisins.  
8. Starfsmaður getur haldið áfram að framkvæma önnur verkefni í áætluninni.  

## Valflæði
- **A1: Starfsmaður vill sjá bjargráð sjúklings áður en verkefni er framkvæmt**  
  1. Starfsmaður smellir á hnapp „Bjargráð“.  
  2. Kerfið birtir upplýsingar um hvað má eða má ekki segja og hvernig á að hegða sér við viðkomandi sjúkling.  
  3. Starfsmaður framkvæmir verkefnið með þessum upplýsingum í huga og heldur síðan áfram í skref 6 í aðalflæði.  

## Undantekningar
- **E1: Kerfið nær ekki að hlaða dagáætlun**  
  - Kerfið birtir villuboð og gefur starfsmanni kost á að reyna aftur eða hafa samband við kerfisstjóra.  
- **E2: Starfsmaður gleymir að merkja verkefni sem lokið**  
  - Kerfið sendir sjálfvirka tilkynningu eftir ákveðinn tíma sem minnir starfsmann á að uppfæra stöðuna.  

## Tengsl
- Kröfur: FR-1 (Skoða dagáætlun), FR-2 (Merkja verkefni sem lokið), FR-3 (Senda tilkynningar), UR-1 (Aðgengi starfsfólks), UR-2 (Bjargráð), BO-1 (Auka sjálfstæði og draga úr mistökum)
