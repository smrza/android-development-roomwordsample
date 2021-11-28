Persistentní ukládání dat do SQLite pomocí Android Room

- cílem cvičení je implementace příkladové aplikace (Databáze/seznam slov), která ukládá data perzistentně pomocí knihoven Android Room
- aplikace bude strukturovaná a bude využívat architektonických komponent Android Jetpack
- v rámci aplikace budou implementovány následující třídy: 
  - MainActivity - používá observer pro sledování LiveData a Adaptér pro poskytnutí dat RecyclerView komponentě
  - NewWordActivity - vložení nového slova do databáze slov
  - WordViewModel - poskytuje data view komponentám prostřednictvím LiveData objektů, data získává z WordRepository
  - WordRepository - třída učená pro přístup k datům, může být využita zejména v rámci práce s více datovými zdroji
- aplikace dále bude využívat tříd Entity (definice data třídy), DAO (metody pro přístup k databázi a práci s entitami) a Room Database (pro přístup k databázi SQLite)

Implementace je detailně popsána v tutoriálu: https://developer.android.com/codelabs/android-room-with-a-view-kotlin/#0
