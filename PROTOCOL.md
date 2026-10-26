```text
X U L A B   C O L L E C T I V E  //  T H E   R U L E B O O K
[ FOUNDING ARCHITECTS & GOVERNING COUNCIL · WORKING GROUPS · AGPLv3 + DUAL-LICENSE · SLICING PIE POOL ]
```

> **[ [MANIFESTO // MANİFESTO](MANIFESTO.md) ]** · **[ [TR // PROTOKOL VE KURAL KİTABI](#tr--xulab-collective-protokolü-ve-kural-kitabı) ]** · **[ [EN // PROTOCOL & RULEBOOK](#en--xulab-collective-protocol--rulebook) ]** · **[ [TÜZEL POLİTİKALAR // COMMERCIAL POLICY](COMMERCIAL_POLICY.md) ]** · **[ [ROADMAP // YOL HARİTASI](ROADMAP.md) ]**

---

# TR // XULAB COLLECTIVE PROTOKOLÜ VE KURAL KİTABI

Bu doküman, **[Xulab Manifestosu](MANIFESTO.md)**’nun sahadaki operasyonel kural kitabıdır. **Kurucu Mimarlar**ın ve **Üretici Meclisi**’nin yapısını, **Çalışma Grupları** ve **Proje Hücreleri**nin nasıl kurulup denetleneceğini, kurumsal sektöre nasıl `Dual-License` uygulanacağını ve emekçilerin **Katkıcı Kâr Payı Havuzu** ile nasıl ödüllendirileceğini düzenler.

> **SÜRÜM NOTU // `v1.0`:** Bu Protokol ve eki olan **[Tüzel Politikalar](COMMERCIAL_POLICY.md)** ilk sürümdür. Sahadaki pratik ihtiyaçlara, yeni proje deneyimlerine ve ekosistemin büyümesine paralel olarak **Xulab Üretici Meclisi** kararı ile ileride değiştirilmeye ve geliştirilmeye açıktır.

---

## 01 // KOLEKTİF ÇATI, KURUCU MİMARLAR VE ÜRETİCİ MECLİSİ MİMARİSİ

**Xulab Collective**, hantal bürokrasiye takılmamak için klasik bir dernek veya hantal bir kurumsal tüzel kişilik değildir; ortak bir manifesto ve kural kitabı etrafında kenetlenmiş **Açık Kaynak Üretim Kolektifi ve Ortak AR-GE Çatısıdır**. Sistem büyüdükçe, Xulab protokolüne uyan birden fazla otonom ekibin ve bağımsız şirketin ortak GPU sunucusu ve altyapı maliyetlerini bölüşmek üzere federatif bir ağ veya B2B konsorsiyum kurma yetisi açıktır.

### 1. İki Katmanlı Ekosistem: Ortak Meydan ve Üretici Meclisi
- **Ortak Meydan // Açık Alan ve Elek:** Herkese açık GitHub repoları, Discord topluluğu, ücretsiz kullanıcılar, lokal AI bağlayan bağımsız üreticiler, hata raporu ve `Pull Request` gönderenlerden oluşur. Maksimum erişilebilirlik esastır; aynı zamanda yetenek, disiplin ve karakter filtreleme alanı olarak çalışır.
- **Üretici Meclisi // İdari Denetim ve Temsil Kurulu:** Ortak Meydan’da somut üretimle rüştünü ispatlayan, manifestoyu ve bu kural kitabını koruyan üst meclistir. Demokrasi felci veya boş tartışma yoktur; **teknik liyakat ve ortak ilkelere uyum** geçerlidir.

### 2. Üretici Meclisi’nin 4 Bileşeni
Ekosistemdeki tüm üretici güçlerin adil temsili ve kurucu ilkelerin sermayeye karşı korunması için Üretici Meclisi **4 kurucu sütundan** oluşur:

1. **Kurucu Mimarlar ve Manifesto Koruyucuları:**
   - Kolektifin kurucu mimarları `@Rhinofug` ile `@Parapazula` ve anayasal koruyucularıdır. Xulab’ın sermaye tekellerine satılmamasından, açık kaynak çekirdeğin kapatılmamasından ve emekçi sömürüsü yasağının korunmasından nihai olarak sorumludurlar. Anayasal Veto ve Koruma Kilidi `Kurucu Mimarlar` makamındadır.
2. **Çekirdek Mimari ve Protokol Ekibi:**
   - Xulab’ın ana teknik standartlarını, `AAF/OTIO/MCP` protokollerini ve çekirdek DSP/AI mimarisini koruyan ve denetleyen kıdemli mühendislerdir.
3. **Açık Kaynak Proje Liderleri, Co-Yazılımcılar ve Çalışma Grubu Temsilcileri:**
   - Çatı altında `Model A` tamamen ücretsiz proje yürüten liderler, çalışma grubu yürütücüleri ve en yüksek aktif katkı puanına sahip bağımsız Co-Yazılımcılardır.
4. **Tüzel ve Kâr Paylaşımlı Proje Temsilcileri:**
   - Çatı altında `Model B` çift lisans ile kurumsal sektöre lisans kesip **Katkıcı Kâr Payı Havuzu**’nu ve ortak AR-GE altyapısını besleyen tüzel projelerin temsilcileridir. Mecliste söz hakları vardır ancak `Kurucu Mimarlar` onayını veya `AGPLv3` açık kaynak çekirdeğini asla geçersiz kılamazlar.

---

## 02 // ÇALIŞMA GRUPLARI VE PROJE YÖNETİŞİMİ

> **ALTIN YÖNETİŞİM KURALI:**  
> **İdari denetim Üretici Meclisi’nin, teknik ve günlük yürütme ise Proje ve Çalışma Grubu Yöneticilerinindir.** Kurallara ve ortak amaca hizmet ettiği sürece herkes Üretici Meclisi onayıyla dilediği gibi proje veya çalışma grubu açıp çalışabilir.  
> **Tekil Xulab Yetkisi:** Xulab yetkisi ile proje katkı yetkileri birbirinden kopuk bürokratik duvarlarla ayrılmaz. Xulab bünyesindeki her geliştirici ve üretici, **istediği her projeye ve çalışma grubuna özgürce katkı sağlayabilir ve katkı verdiği her tüzel projenin havuzundan doğrudan puanını ve payını alır.**

### 1. Bir Proje veya Çalışma Grubu Nasıl Kurulur?
Xulab çatısı altında açılacak her **Yazılım Projesi** ve her **Çalışma Grubu**, başlangıçta şu **4 alanı** kilitleyerek Üretici Meclisi onayına sunar:

| Alan | Tanımı ve Yetki Sınırı |
| :--- | :--- |
| **1. `Chair / Project Lead` // Yürütücü Lider** | Projenin veya çalışma grubunun günlük teknik yönetiminden, mimari kararlarından ve kod birleştirme süreçlerinden tam yetkiyle sorumlu liderdir. |
| **2. `Council Sponsor` // Meclis Sponsoru** | Üretici Meclisi’nden veya `Kurucu Mimarlar` arasından **1 kişi**, ilgili projenin veya grubun **Sponsoru** olur. Görevi günlük yürütmeye karışmak değil; projenin Xulab Manifestosu’na, `AGPLv3` sınırlarına ve `COMMERCIAL_POLICY.md` kurallarına uyumunu **idari olarak denetlemek** ve Meclis ile proje arasındaki köprü olmaktır. |
| **3. `Charter & Scope` // Başlangıç Beyannamesi** | Projenin `Model A` ücretsiz mi yoksa `Model B` çift lisanslı mı olduğunu, kendi `CONTRIBUTING.md`, `CLA` ve gelir havuzu oranlarını, **ne yapacağını** ve **hangi alanlara karışmayacağını** baştan kilitler. Hazır şablon [`COMMERCIAL_POLICY.md`](COMMERCIAL_POLICY.md) içindedir. |
| **4. `Minimum Squad` // Kuruluş Eşiği** | En az 1 `Lead`, Çalışma Grupları için en az 2–3 aktif üye, 1 `Council Sponsor` ve onaylı `Charter`. |

### 2. Xulab Çekirdek Çalışma Grupları
Yazılım projelerinin yanı sıra, [`ROADMAP.md`](ROADMAP.md) içindeki sürekli hedeflerimizi yürüten **5 Çekirdek Çalışma Grubu** şunlardır:

- **`WG-01 // Audio, DAW & Interoperability Working Group`:** Açık kaynak DAW, DSP, `AAF/OTIO/EDL/MIDI` dönüşüm motorları ve stüdyo entegrasyonu.
- **`WG-02 // Local AI, MCP & Tensor Working Group`:** Lokal silikon üzerinde çalışan ses ve medya AI modelleri, `MCP` ajan protokolleri ve kolektif model ağırlıkları.
- **`WG-03 // Open Education & Breakdown Working Group`:** Stüdyoların meslek sırrı ketumluğunu yıkan açık dersler, yaratım süreci analizleri ve yazılımcı olmayanlar için AI ile kodlama eğitimi.
- **`WG-04 // Guild Standards & Anti-Mobbing Working Group`:** Uluslararası **Mesleki Görev ve Teknik Kalite Tanımı**, keyfi revizyon, mobbing ve taşeron fiyat kırma kalkanı.
- **`WG-05 // Field QA & Debug Working Group`:** Sahadaki araçların gerçek prodüksiyonlarda test edilmesi, çapraz platform doğrulaması ve hata raporlama hattı.

---

## 03 // XULAB ÇATISI ALTINDAKİ İKİ PROJE MODELİ VE KAPSAM AYRIMI

> **TEMEL PROTOKOL İLKESİ VE KAPSAM AYRIMI:**  
> 1. **Yazılım, Motor ve AI Geliştirme Projeleri:** Xulab çatısı altındaki **her yazılım projesi tüzel veya tamamen açık kaynak olabilir.** Ancak **sektörel rekabet yaratacak araçların `Dual-License` modeliyle emekçilere doğrudan gelir kazandırması; çekirdek motorun tam açık kaynak `AGPLv3`, kurumsal hizmetin ise `Dual-License` olması şiddetle önerilir.** Tüzel yazılım projeleri daha en baştan buna göre katkı şartlarını kilitleyip Üretici Meclisi’ne sunmak, şeffafça açıklamak ve oluşan gelir havuzunun belirli bir kısmını, minimum `%5–%10` ve tavsiye edilen `%10–%15` oranında, puan sistemiyle projeyi inşa eden **Co-Yazılımcılara** geri ödemek zorundadır. Saha testi, hata ayıklama ve QA katkıları ise kâr havuzunu sulandırmadan Ücretsiz Pro/Lifetime Lisans ve tek seferlik ödüllerle karşılık bulur. **Açık kaynak geliştirme modeli, piyasadaki şirketlerin yaptığı gibi geliştiriciler üzerinden ücretsiz iş gücü sömürüsü yapmak için asla kullanılmayacaktır.**  
> 2. **Piyasa Medya Üretimi ve Post-Prodüksiyon Hizmet Projeleri:** Yukarıdaki `Dual-License` ve puan havuzu sistemi **yalnızca yazılım ve motor geliştirme** içindir. **Piyasada yapılacak medya üretimi ve post-prodüksiyon hizmet etkinliklerinin kazançları bu yazılım havuzundan tamamen bağımsızdır ve yüzde yüz olarak doğrudan işi üstlenen aktif proje ekibine bırakılır.** Bu ekiplerin de Xulab Manifestosu'ndaki taşeron sömürüsü yapmama, mobbing yasağı ve ekip içi adil paylaşım kurallarına uyması zorunludur.

```text
                 [ XULAB COLLECTIVE // KURUCU MİMARLAR & ÜRETİCİ MECLİSİ ]
                                                 │
        ┌────────────────────────────────────────┼────────────────────────────────────────┐
        ▼                                        ▼                                        ▼
[ WORKING GROUPS // WG-01..05 ]  [ MODEL A: %100 FREE PROJELER ]      [ MODEL B: TÜZEL / DUAL-LICENSE PROJELER ]
• Chair/Lead + Council Sponsor   • Lead + Council Sponsor ile başlar  • Lead + Council Sponsor + Kilitli Charter
• Eğitim, Anti-Mobbing, QA, AI   • Saf AGPLv3 ile herkese ücretsiz    • Motor tam açık AGPLv3, Hizmet Dual-License
• Ortak AR-GE ve Standartlar     • Gönüllü bireysel destek alabilir   • ZORUNLU: Havuzun %5-%15'ini Co-Yazılımcılara
                                                                        puan sistemiyle geri öder!
```

### MODEL A // Tamamen Açık Kaynak ve Ücretsiz Projeler
- **Başlangıç ve Yürütme:** Proje sahibi, projenin tamamen ücretsiz `AGPLv3` olacağını ve katkı yapısını bir **Council Sponsor** eşliğinde **Xulab Üretici Meclisi** onayına sunarak projeyi başlatır ve **Proje Yöneticisi** olarak yürütmeyi üstlenir.
- **Lisans ve Fonlama:** Saf **`AGPLv3`** lisansıyla yayınlanır ve tüm meslektaşlara ücretsizdir. Geliştirici ekip, açık kaynak sürdürülebilirliği için araç içinde gönüllü bireysel destek bağlantıları kullanabilir.

### MODEL B // Tüzel Kişilikli, Copyfarleft Korumalı ve Kâr Paylaşımlı Rekabetçi Projeler
- **Başlangıç, Mimari ve Üçlü Lisans Kilidi:** Sektörel rekabet yaratacak büyük çaplı araçlarda büyük stüdyo tekellerinin aracı kendi iç iş akışlarında bedava çalıştırmasını engellemek için **Üçlü Kilit** uygulanır: Çekirdek SDK ve protokol katmanı derin entegrasyonlu `AGPLv3`, açık ve lite uygulama sürümleri **Ciro ve Ölçek Sınırlı `Copyfarleft` Kaynağı Açık Lisans**, ileri teknoloji otomasyon motoru ve özel AI ağırlıkları ise kurumsal **`Dual-License`** altındadır. Böylece bağımsız emekçiler ve küçük ekipler kodu ücretsiz kullanırken, ciro sınırını aşan kurumsal stüdyolar iç prodüksiyon kullanımları için dahi ticari lisans almak zorundadır.
- **Baştan Kilitlenen Katkı Şartları ve Zorunlu Geri Ödeme Kuralı:** Xulab çatısı altında yer alan her tüzel proje, **daha projenin ilk gününden `CONTRIBUTING.md` ve `CLA` ile katkı ve gelir paylaşım şartlarını açıkça ilan etmek** ve kurumsal sermaye stüdyolarına kestiği `Dual-License` gelir havuzunun **belirli bir yüzdesini puan sistemiyle projeye emek veren Co-Yazılımcılara geri ödemek zorundadır.**

---

## 04 // LİSANSLAMA VE EKOSİSTEM KİLİDİ

Linux’un dağınık telif hatasına düşülmez; JUCE ve Qt gibi fikri mülkiyet merkezileştirilir ancak klasik şirketlerin aksine **gelir, işi üreten emekçilerle paylaşılır:**

1. **Taban Araçlarda Saf `AGPLv3`, Rekabetçi Motorlarda `Copyfarleft` Ciro Sınırlı Açık Lisans ve Derin SDK Kilidi:**
   - Taban topluluk araçlarında `Model A` kapsamında bulut ve SaaS kaçaklarını önlemek için **Saf `AGPLv3`** kullanılır.
   - Sektörel rekabet yaratan ileri teknoloji araçlarda ve açık veya lite sürümlerde ise `Model B` kapsamında büyük stüdyoların iç iş akışı sömürüsünü kesmek için **Ciro Sınırlı Kaynağı Açık `Copyfarleft` Lisanslama** ve **Derin SDK Mimari Kilidi** uygulanır: Bilançosu sınırı aşan hiçbir kurumsal şirket, aracı içeride gizlice veya mikroservis etrafından dolaşarak bedava çalıştıramaz.
2. **Sıfır İstisna ve Rekabet Duvarı:**
   - İnşa ettiğimiz DAW, NLE ve MCP ekosistemine entegre olacak her 3. parti eklenti, MCP aracı veya AI modeli için standart kapalı bağlantı istisnası tanınmaz:
     - Ya kodunu tamamen açık kaynak **`AGPLv3`** yaparak Xulab ekosistemini büyütmek zorundadır,
     - Ya da kapalı kalmak istiyorsa ilgili proje tüzel kişiliğinden **ücretli ticari lisans** satın almak zorundadır.
3. **Kademeli Fiyatlandırma Matrisi:**
   - **Açık Kaynak ve Lokal Bağımsız Üretici:** **ÜCRETSİZ**, `AGPLv3` Açık Kaynak Motor ve lokal donanımda açık AI modelleri.
   - **Bağımsız Freelancer ve Indie:** Sembolik ve erişilebilir ticari lisans.
   - **Kurumsal Sermaye Stüdyosu:** Yüksek bedelli koltuk başı kurumsal lisans.
   - **3. Parti Kapalı Şirketler:** Ekosistemde kapalı ürün satmak isteyen şirketlerden yüksek lisans bedeli ve ciro payı.

---

## 05 // KATKICI KÂR PAYI HAVUZU VE PUAN SİSTEMİ

Model B projelerde açık kaynak geliştiricileri üzerinden asla ücretsiz iş gücü sömürüsü yapılmaması ve her emeğin adil karşılık bulması için **Çift Yönlü CLA ve Puan Sistemi** uygulanır:

- **Çift Yönlü CLA:** Co-Yazılımcı, yazdığı kodun ticari lisanslama haklarını proje tüzel kişiliğine devreder; tüzel kişilik ise net ticari gelirinin sabit **`%X`** oranını şeffaf biçimde **Katkıcı Kâr Payı Havuzu**’na aktarmayı en baştan sözleşmeyle taahhüt eder.
- **Kurucu Çekirdek Baz Puanı:** Proje başlarken kurucu mimarların ortaya koyduğu çekirdek kod puan havuzunun tabanını oluşturur; dışarıdan gelen Co-Yazılımcılar ürettikleri puan oranında havuzdan pay alır, kalan kısım kurucu tüzel kişilikte kalır.
- **Faz 1 // Genesis // Ticari Satış Öncesi:** Havuz açıktır. Tamamlanan her çekirdek mühendislik, DSP, AI ve modül görevi dinamik **"Hisse Puanı"** üretir:
  $$\text{Co-Yazılımcının Payı} = \frac{\text{Aktif Katkıcı Puanı}}{\text{Kurucu Baz Puanı} + \text{Toplam Katkıcı Puanı}}$$
- **Faz 2 // Olgunluk Kilidi // Ticari Satış Sonrası:** Ürün ticari eşiği aştığında erken aşamada risk alan çekirdek ekibin emeğinin sulanmaması için puan havuzu yeni ortaklara kapatılır; sonradan gelen katkılar doğrudan **sabit nakit ödül** alır.

### Sömürü ve Bitmeyen Emeklilik Korumaları: 4 Denge Kilidi
1. **`Cliff` // 6 Ay Uçurum Kuralı:** Bir PR ana dala eklendikten sonra en az **6 ay** çökmeden yaşayacak ve geliştirici kendi modülünün hatalarını temizleyecektir. Erken bırakanın puanı yanar.
2. **`Vesting` // Kademeli Hak Ediş:** Puanın **%25’i** 6 aylık `Cliff` sonunda, kalan **%75’i** ise takip eden **3 ana sürüm** boyunca bakım desteği verdikçe kazanılır.
3. **`Roll-off / Decay` // Pasiflik Erimesi:** Pasifleşen katkıcının puanı her yıl **%25–%50** oranında erir. Yazdığı kod mimariden tamamen kaldırılırsa puanı sıfırlanır.
4. **`Cap` // Tavan Ödeme Çarpanı:** Göreve biçilen başlangıç değerinin belirli bir risk çarpanına, örneğin `5x–8x` nakit ödemeye ulaşıldığında ilgili puanlar emekli olur ve aktif havuzdan düşer.

### Minimum Havuz Payları, Kurucu Baz Puanı ve Hazır Proje Başlangıç Belgesi
Xulab altında yeni bir yazılım projesi açacak geliştirici veya tüzel kişiliklerin doğrudan kullanacağı **Minimum Zorunlu Havuz Taban Oranları**, **Kurucu Çekirdek Baz Puanı**, **Co-Yazılımcı ile Debug/QA Ayrımı** ve kopyalanıp doldurulmaya hazır **Proje Başlangıç Beyannamesi Şablonu** için **[`COMMERCIAL_POLICY.md`](COMMERCIAL_POLICY.md)** belgesine bakınız.

---

# EN // XULAB COLLECTIVE PROTOCOL & RULEBOOK

This document is the operational rulebook of the **[Xulab Manifesto](MANIFESTO.md)**. It defines the role of the **Founding Architects** and the **Governing Council**, how **Working Groups** and **Project Cells** are chartered and overseen, how `AGPLv3 + Dual-Licensing` is enforced against corporate monopolies, and how contributors are rewarded through the **Slicing Pie Point System**.

> **VERSION NOTE // `v1.0`:** This Protocol and the accompanying **[Commercial Policies](COMMERCIAL_POLICY.md)** are in their initial release and remain open to future revision, adaptation, and evolution by decision of the **Xulab Governing Council** as real-world practice requires.

---

## 01 // COLLECTIVE UMBRELLA, FOUNDING ARCHITECTS & GOVERNING COUNCIL ARCHITECTURE

**Xulab Collective** is not a sluggish statutory association or bureaucratic corporate structure; it is an **Open-Source Production Collective and Collaborative R&D Umbrella** with the built-in capacity to scale into a federative network or B2B consortium as multiple autonomous squads and allied companies join to share GPU and infrastructure costs.

### 1. Two-Layer Ecosystem: Open Commons & Governing Council
- **Open Commons // Open Ground & Sieve:** Public GitHub repositories, Discord community, free users, local-AI independent practitioners, QA testers, and PR contributors. Built for maximum accessibility while filtering for skill and character.
- **Governing Council // Administrative Oversight & Representation:** The council of builders proven through concrete `Proof-of-Work` who uphold the Manifesto and this Rulebook.

### 2. The 4 Pillars of the Governing Council
Inspired by proven open-source foundation models while preserving our cooperative roots, the Governing Council comprises **4 pillars**:

1. **Founding Architects & Constitutional Stewards:**
   - The founding architects `@Rhinofug` and `@Parapazula` and constitutional stewards of the collective. Responsible for ensuring Xulab is never sold out to capital monopolies, the open-source core is never enclosed, and anti-exploitation rules remain intact. Constitutional Veto and Safeguard Authority rests with the `Founding Architects`.
2. **Spec & Core Architecture Team:**
   - Senior engineers safeguarding Xulab's core technical standards across `AAF/OTIO/MCP` protocols and core DSP/AI architecture.
3. **Commons & Working Group Delegates:**
   - Leads of `Model A` 100% Free projects, `Working Group` Chairs/Leads, and top point-earning independent Co-Developers.
4. **Dual-License Entity Delegates:**
   - Representatives of `Model B` Dual-License incorporated projects that bill enterprise studios and fund the **Contributor Profit Pool** and shared R&D infrastructure. They hold representation seats but can never override the `Founding Architects` or enclose the `AGPLv3` open-source core.

---

## 02 // WORKING GROUPS & PROJECT GOVERNANCE

> **GOLDEN GOVERNANCE RULE:**  
> **Administrative oversight belongs to the Governing Council; day-to-day technical execution belongs to the Project and Working Group Leads.** As long as an initiative serves our shared rules and purpose, anyone may propose, charter, and run a project or working group with Council approval.  
> **Unified Xulab Standing:** Xulab permissions and project contribution rights are never split into bureaucratic silos. Every developer and practitioner in Xulab **is free to contribute to any project or working group and earn points and profit shares directly from each commercial project they help build.**

### 1. How a Project or Working Group Is Chartered
Every **Software Project** and **Working Group** locks **4 fields** upfront for Governing Council approval:

| Field | Definition & Authority Boundary |
| :--- | :--- |
| **1. `Chair / Project Lead`** | Holds full day-to-day execution authority over technical architecture, task routing, and PR merges. |
| **2. `Council Sponsor`** | **1 member** of the Governing Council or a `Founding Architect` serving as the administrative liaison who verifies compliance with the Manifesto, `AGPLv3`, and `COMMERCIAL_POLICY.md` without micromanaging execution. |
| **3. `Charter & Scope`** | Locks whether the project is `Model A` 100% Free or `Model B` Dual-License, its `CONTRIBUTING.md`, `CLA`, and pool parameters, what is **`In-Scope`**, and what is **`Out-of-Scope`**. Template in [`COMMERCIAL_POLICY.md`](COMMERCIAL_POLICY.md). |
| **4. `Minimum Squad`** | At least 1 `Lead`, 2–3 active members for Working Groups, 1 `Council Sponsor`, and an approved `Charter`. |

### 2. Core Xulab Working Groups
- **`WG-01 // Audio, DAW & Interoperability Working Group`:** Open-source DAW, DSP, `AAF/OTIO/EDL/MIDI` engines including `VCut2DAW`, and studio integration.
- **`WG-02 // Local AI, MCP & Tensor Working Group`:** Local-silicon audio/media AI models, `MCP` agent protocols, and collective model weights.
- **`WG-03 // Open Education & Breakdown Working Group`:** Open vocational courses, creation breakdowns, and AI-assisted coding onboarding for non-programmers.
- **`WG-04 // Guild Standards & Anti-Mobbing Working Group`:** International **Professional Job Description & Technical Quality Standards** against mobbing and rate-slashing.
- **`WG-05 // Field QA & Debug Working Group`:** Production field testing, cross-platform verification, and issue triage.

---

## 03 // TWO PROJECT MODELS UNDER XULAB & SCOPE SEPARATION

> **CORE PROTOCOL MANDATE & SCOPE SEPARATION:**  
> 1. **Software, Engine & AI Development Projects:** **Every software project under Xulab may be either incorporated or 100% open-source.** However, **for tools built to create real industry competition, we strongly recommend the `Dual-License` model so that the tool directly generates income for workers, keeping the core engine 100% open-source under `AGPLv3` while licensing the commercial service layer via `Dual-License`.** Incorporated software projects must lock and submit their contributing terms to the Governing Council from day one, publish them transparently, and pay back a defined percentage of their net revenue pool to **Co-Developers** via a point system anchored by **Founder Baseline Points**, while rewarding **Field QA / Debug** with Free Pro/Lifetime Licenses and one-off Bug Bounties. **Open-source development under Xulab will never be used, as it is in the corporate market, to exploit unpaid developer labor.**  
> 2. **Market Media Production & Post-Production Services:** The `Dual-License` and point-pool system above applies **strictly to software and engine development**. **Revenues from market media production and post-production service engagements are completely independent of this software pool and belong 100% to the active squad executing the work**, provided they strictly abide by the Xulab Manifesto: zero subcontractor exploitation, zero mobbing, and fair distribution among the active production team.

### MODEL A // 100% Free & Open-Source Projects
- **Initiation & Execution:** Chartered with a **Council Sponsor** and approved by the **Governing Council** under locked `100% Free AGPLv3` terms; day-to-day execution is led autonomously by the **Project Lead**.
- **Licensing & Funding:** Released under **Strict `AGPLv3`**, 100% free for all practitioners. May include voluntary peer support links.

### MODEL B // Incorporated, Copyfarleft-Protected & Profit-Sharing Competitive Projects
- **Initiation, Architecture & Triple Licensing Lock:** For high-impact competitive tools, we enforce a **Triple Lock** so studio monopolies cannot run our engines for free inside their internal pipelines: deep-linked SDK libraries under `AGPLv3`, open and lite application builds under **Revenue-Bounded `Copyfarleft` Source-Available Licenses**, and advanced automation engines plus trained AI weights under commercial **`Dual-Licensing`**. Independent workers and small peer teams run the code for free, while corporate studios exceeding the revenue threshold must purchase a commercial license even for internal production use.
- **Upfront Contributing Terms & Mandatory Payout Rule:** Every incorporated project under Xulab **must publish its contributing and profit-sharing terms upfront from day one** and **must return a fixed percentage of its commercial revenue pool to Co-Developers via the `Slicing Pie` point system.**

---

## 04 // LICENSING & ECOSYSTEM LOCK

1. **Strict `AGPLv3` for Foundational Tools + `Copyfarleft` Revenue-Bounded Source-Available & Deep SDK Lock for Competitive Engines:**
   - Foundational community tools under `Model A` use **Strict `AGPLv3`** to close cloud and SaaS loopholes.
   - Competitive industrial engines and their open or lite editions under `Model B` combine **Revenue-Bounded `Copyfarleft` Source-Available Licensing** with **in-process Deep SDK locks** so large corporations cannot bypass licensing through internal pipeline use or microservice wrappers.
2. **Zero Linking Exception:** Every plugin, MCP tool, or AI model integrating into the Xulab DAW/MCP stack must either be **100% open-source under `AGPLv3`** or purchase a **Commercial `Dual-License`**.
3. **4-Tier Pricing Matrix:**
   - **Open-Source / Local Independent Practitioner:** **FREE**, `AGPLv3` Engine + Local open AI models.
   - **Freelancer / Indie:** Affordable indie license & API key.
   - **Corporate Studio:** High-ticket per-seat commercial license & cloud speed.
   - **3rd-Party Closed Vendors:** Commercial license fee + revenue share.

---

## 05 // CONTRIBUTOR PROFIT POOL & `SLICING PIE` POINT SYSTEM

- **Two-Way CLA:** Co-Developers assign commercial licensing rights to the project entity in exchange for a contractually locked **`%X` net revenue share** flowing into the **Contributor Profit Pool**.
- **Founder Baseline Points:** The founding architects' initial core codebase establishes the baseline point denominator so external Co-Developers earn proportional to their real contribution while the remainder stays with the founding entity.
- **Phase 1 // Genesis // Pre-Commercial:** Tasks generate dynamic equity points:
  $$\text{Co-Developer Share} = \frac{\text{Active Contributor Points}}{\text{Founder Baseline Points} + \text{Total Contributor Points}}$$
- **Phase 2 // Maturity Hard Lock // Post-Commercial:** The equity pool locks to protect early builders; new contributions receive direct **Cash Bug Bounties or Feature Grants**.
- **4 Anti-Exploitation Guards:**
  1. **`Cliff` // 6 Months:** Code must survive in `main` for 6 months with active bug maintenance by its author.
  2. **`Vesting`:** 25% vests after the 6-month Cliff; 75% vests across the next 3 major releases.
  3. **`Roll-off / Decay`:** Inactive contributor points decay by 25–50% annually, or reset to 0 if deprecated/removed.
  4. **`Cap`:** Points retire once cumulative payouts reach the task's risk multiplier cap of `5x–8x`.
- **Minimum Pool Floors, Founder Baseline & Ready-to-Use Project Charter:**
  See **[`COMMERCIAL_POLICY.md`](COMMERCIAL_POLICY.md)** for the mandatory minimum profit-pool percentages, **Founder Baseline Points**, **Co-Developer vs. Debug/QA separation**, and the copy-pasteable **Software Project Charter Template**.

```text
------------------------------------------------------------------------
MANIFESTO          See MANIFESTO.md
COMMERCIAL POLICY  See COMMERCIAL_POLICY.md
ROADMAP            See ROADMAP.md
COLLECTIVE         https://github.com/xulab-collective
ARCHITECTS         Furkan Utku Gerçik // @Rhinofug // Founding Architect
                   Muhammed Kol // @Parapazula // Co-Architect
LICENSE            GNU Affero General Public License v3.0 // AGPLv3 // Dual-License
------------------------------------------------------------------------
```
