```text
X U L A B   C O L L E C T I V E  //  C O M M E R C I A L   P O L I C I E S   &   T E M P L A T E
[ YAZILIM TÜZEL POLİTİKALARI · MİNİMUM HAVUZ ORANLARI · KURUCU BAZ PUANI · PROJE BEYANNAMESİ ]
```

> **[ [MANIFESTO // MANİFESTO](MANIFESTO.md) ]** · **[ [PROTOCOL // KURAL KİTABI](PROTOCOL.md) ]** · **[ [ROADMAP // YOL HARİTASI](ROADMAP.md) ]** · **[ [TR // TÜZEL POLİTİKALAR](#tr--xulab-tüzel-politikalar-minimum-paylar-ve-proje-başlangıç-rehberi) ]** · **[ [EN // COMMERCIAL POLICIES](#en--xulab-commercial-policies-minimum-floors--project-charter-guide) ]**

---

# TR // XULAB TÜZEL POLİTİKALAR, MİNİMUM PAYLAR VE PROJE BAŞLANGIÇ REHBERİ

Bu belge, **Xulab Collective** çatısı altında **Yazılım, Motor ve AI Geliştirme** amacıyla **Model B Tüzel ve Çift Lisanslı** veya **Model A Tamamen Ücretsiz `AGPLv3`** proje başlatmak isteyen geliştirici ve şirketler için hazırlanmış **standart referans tablosu ve hazır başlangıç şablonudur**.

> **SÜRÜM NOTU // `v1.0`:** Bu Tüzel Politikalar belgesi ve içerdiği referans oranlar ilk sürümdür; sahadaki pratik ihtiyaçlara göre **Xulab Üretici Meclisi** kararı ile ileride değiştirilmeye ve geliştirilmeye açıktır.

> **KAPSAM AYRIMI // YAZILIM GELİŞTİRME VE PİYASA MEDYA HİZMETİ:**  
> Bu belgedeki `Dual-License` gelir havuzu ve puan sistemi **yalnızca Yazılım, DSP ve AI Araç Geliştirme** projeleri içindir.  
> **Piyasada yürütülecek medya üretimi ve post-prodüksiyon hizmet projelerinin kazançları bu yazılım havuzundan tamamen bağımsızdır ve yüzde yüz olarak doğrudan işi üstlenen aktif proje ekibine bırakılır.** Sahada medya ve post-prodüksiyon işi yapan ekiplerin de Xulab Manifestosu'ndaki taşeron sömürüsü yapmama, mobbing yasağı ve ekip içi şeffaf ve adil paylaşım ilkelerine uyması zorunludur.

---

## 01 // YAZILIM KATKICI KÂR PAYI HAVUZU: MİNİMUM TABAN VE TAVSİYE EDİLEN ORANLAR

> **Hesaplama Kuralı // Net Ticari Gelir:** Havuz payı `%X`, ödeme altyapısı komisyonları ve varsa doğrudan bulut GPU/API sunucu faturası düşüldükten sonra kalan **Net Lisans ve Hizmet Geliri** üzerinden hesaplanır.

| Yazılım Proje Kategorisi | Zorunlu Minimum Taban | Tavsiye Edilen Standart Oran | Kapsam ve Açıklama |
| :--- | :---: | :---: | :--- |
| **1. Saf Yazılım ve Lokal Motor**<br>*DAW, NLE, DSP Eklentisi, Masaüstü ve CLI Araçları* | **Min. `%10`** | **`%12 – %15`**<br>*Tavan: `%20`* | Sunucu ve GPU maliyeti olmayan, çekirdeği `AGPLv3` açık kaynak olup kurumsal sektöre `Dual-License` satan projeler. |
| **2. Hibrit: Açık Motor ve Özel Eğitilmiş AI Ağırlıkları**<br>*Lokal/Şifreli Ağırlıklar + Ticari Lisans* | **Min. `%7.5`** | **`%10 – %15`** | Tüzel kişiliğin yüksek veri temizliği, telif ve model eğitimi maliyeti üstlendiği hibrit AI ve DSP projeleri. |
| **3. Yoğun Bulut ve GPU Servisi**<br>*Bulut Tabanlı AI, Mix ve Render* | **Min. `%5`** *Net* | **`%10 – %12`** *Net* | Doğrudan bulut GPU ve VRAM faturası düşüldükten sonra kalan net hizmet geliri üzerinden dağıtılır. |
| **4. Xulab Ortak Altyapı ve AR-GE Kesintisi** | **`%0 – %2.5`** | **`%1 – %2`** | Xulab'ın ortak sunucu, test ve organizasyon altyapısını kullanan tüzel projelerin kolektif AR-GE kasasına bıraktığı sembolik pay. |

---

## 02 // CO-YAZILIMCI VE DEBUG/QA AYRIMI İLE KURUCU BAZ PUANI

Proje getiren şirketin ve kurucuların emeğinin korunması ve dışarıdan gelen üst düzey yazılımcıların havuzunun sulanmaması için şu **iki kural** kesin olarak uygulanır:

### 1. Kurucu Çekirdek Puanı // Havuz Koruma Kuralı
- Proje başlarken, kurucu mimarların ortaya koyduğu mevcut çekirdek kod ve mimari de puan havuzunun tabanını, örneğin `10.000 Puan` olarak oluşturur.
- Dışarıdan katılan bir Co-Yazılımcı `1.000 Puanlık` bir modül geliştirdiğinde havuzun $\frac{1.000}{10.000 + 1.000} = \%9.09$’unu alır; havuzun kalan `%90.91`’lik kısmı kurucu şirkette kalır. Böylece **1 kişinin küçük bir katkı yapıp tüm havuzu tek başına yutması matematiksel olarak imkansızdır; dışarıdan ne kadar gerçek mühendislik katkısı gelirse havuzdan sadece o kadarı çıkar.**

### 2. Co-Yazılımcı Kâr Havuzu ve Debug/QA Lisans Ödülü Ayrımı
Maaş ödemeden üst düzey mühendis çekmek ile saha testçilerini ödüllendirmek birbirine karıştırılmaz:

| Katkı Seviyesi ve Türü | Kimler Dahildir? | Karşılık ve Ödüllendirme Modeli | Puan ve Çarpan |
| :--- | :--- | :--- | :---: |
| **`Tier-1` // Çekirdek Mimari, DSP ve AI Motoru** | C++/Rust/JUCE motoru, gerçek zamanlı DSP, tensor ve LLM eğitimi, AAF/OTIO/MCP çekirdeği yazanlar | **Kâr Payı Havuzu Ortağı** | **`500 – 2.500 Puan`**<br>*Çarpan: `2.0x`* |
| **`Tier-2` // Ana Özellik ve Modül Geliştirme** | Yeni fonksiyonel modül, masaüstü UI/UX mimarisi, yeni DAW ve format entegrasyonu yazanlar | **Kâr Payı Havuzu Ortağı** | **`100 – 500 Puan`**<br>*Çarpan: `1.5x`* |
| **`Tier-3` // Küçük Hata Çözümü ve Yama** | Tekil çökme çözümü, küçük yama veya dokümantasyon PR'ı gönderenler | **Kâr havuzuna girmez:** **Ücretsiz Pro Lisans** ve proje kâra geçtiğinde **Tek Seferlik Nakit Ödül** | **Sabit Ödül ve Lisans** |
| **`Tier-4` // Saha Testi ve Geri Bildirim** | Programı sahada test eden, hata raporlayan ve iş akışı geri bildirimi veren pratisyenler | **Kâr havuzuna girmez:** **Xulab Seçkisi Ücretsiz `Lifetime Core / Pro` Lisansı** ve Erken Erişim | **Ücretsiz Lisans Erişimi** |

---

## 03 // HAK EDİŞ, ERİME VE TAVAN REFERANS DEĞERLERİ

`Tier-1` ve `Tier-2` Co-Yazılımcılar için geçerli standart koruma parametreleri:

| Mekanizma | Zorunlu Sınır | Tavsiye Edilen Standart Değer | Koruma Kuralı |
| :--- | :---: | :---: | :--- |
| **1. `Cliff` // Uçurum Süresi** | **Maks. `6 Ay`** | **`6 Ay` veya ilk ticari sürüm** | Kod `main` dalına girdikten sonra 6 ay çökmeden yaşamalı ve yazarı kendi modülünün hatalarını temizlemelidir. Kötü niyetle kod silip puan yakmak Üretici Meclisi denetimindedir ve geçersizdir. |
| **2. `Vesting` // Kademeli Hak Ediş** | **Min. `%25` Cliff sonunda** | **`%25` 6. Ay + `%25 x 3 Sürüm`** | 6. ayda puanın `%25`'i kesinleşir; kalan `%75`'i takip eden 3 ana veya ara sürüm boyunca bakım desteği verdikçe açılır. |
| **3. `Roll-off / Decay` // Pasiflik Erimesi** | **Maks. `%50 / Yıl`** | **Yıllık `%25` Erime** | Projeyi tamamen bırakan ve bakım yapmayan kişinin puanı her yıl `%25` oranında erir; böylece havuz aktif çalışanları beslemeye devam eder. |
| **4. `Cap` // Tavan Ödeme Çarpanı** | **Min. `5x`** | **`5x – 8x` Nakit Çarpanı** | Katkıcının havuzdan aldığı kümülatif nakit ödeme, yaptığı işin başlangıç referans değerinin **`5x–8x`** katına ulaştığında o puanlar emekli olur. |
| **5. `Payout` // Dağıtım Takvimi** | **En geç `3 Ayda Bir`** | **Her Çeyrek Sonu** | Havuz gelir tablosu şeffaf olarak açıklanır ve ödemeler en geç 3 ayda bir dağıtılır. |

---

## 04 // KADEMELİ `DUAL-LICENSE` FİYATLANDIRMA REHBERİ

| Kademe | Hedef Kitle | Lisans Türü | Tavsiye Edilen Fiyat Çarpanı |
| :--- | :--- | :--- | :--- |
| **Kademe 0 // Lokal Bağımsız, Kolektif ve Açık Kod** | Bağımsız emekçiler, öğrenciler, kolektifler ve ciro sınırı altındaki bireysel üreticiler | **`AGPLv3` ve `Copyfarleft` Ciro Sınırlı Açık Lisans** | **`$0` // Tamamen Ücretsiz** |
| **Kademe 1 // Indie ve Freelancer** | Yıllık brüt geliri `< $50.000` olan bağımsız profesyoneller | **Indie Ticari Lisans** | **`1x` Baz Fiyat // Erişilebilir** |
| **Kademe 2 // Butik Stüdyo** | Yıllık geliri `$50.000 – $250.000` arası, `2–5 koltuk` küçük ekipler | **Pro Ticari Lisans** | **`3x – 5x` Baz Fiyat // Koltuk başı** |
| **Kademe 3 // Kurumsal Sermaye** | Yıllık geliri `> $250.000` olan büyük post-prodüksiyon stüdyoları ve medya tekelleri | **Enterprise `Dual-License`** | **`10x – 25x` Baz Fiyat // Koltuk başı + SLA** |
| **Kademe 4 // 3. Parti Kapalı Şirketler** | Motoru veya modülü kendi kapalı ticari ürününe gömmek isteyen şirketler | **OEM `Dual-License`** | **Yüksek Peşin Lisans + Brüt Cirodan `%5 – %15` Pay** |

---

## 05 // HAZIR YAZILIM PROJE BAŞLANGIÇ BEYANNAMESİ // `XULAB_CHARTER.md`

Xulab çatısı altında yeni bir yazılım projesi açmak isteyen herkes, aşağıdaki şablonu doldurup projesinin ana dizinine `CONTRIBUTING.md` veya `XULAB_CHARTER.md` olarak koyar ve **Xulab Üretici Meclisi** onayına sunar:

```markdown
# XULAB SOFTWARE PROJECT CHARTER // YAZILIM PROJE BAŞLANGIÇ BEYANNAMESİ

- **Proje Adı:** [Örn: ProjectName]
- **Proje Yöneticisi // Chair / Project Lead:** [@kullanici_adi]
- **Meclis Sponsoru // Council Sponsor:** [@sponsor_kullanici_adi]
- **Proje Kapsamı // In-Scope & Out-of-Scope:** [Bu projenin ne yaptığı ve hangi alanlara karışmadığı]
- **Proje Modeli:** [ ] Model A // %100 Free AGPLv3  |  [ ] Model B // Tüzel / Açık Motor AGPLv3 + Dual-License
- **Tüzel Kişilik // Sadece Model B ise:** [Şirket Adı ve Ülke]
- **Açık Çekirdek ve Kaynak Lisansı:** [ ] Saf AGPLv3 // Model A  |  [ ] Copyfarleft Ciro Sınırlı Açık Lisans + AGPLv3 Derin SDK + Dual-License // Model B
- **Co-Yazılımcı Kâr Payı Havuzu Oranı // Model B:** Net Ticari Gelirin %[15]'i // Zorunlu Taban: %5-%10
- **Kurucu Çekirdek Baz Puanı // Founder Baseline:** [10.000 Puan]
- **Ödüllendirme Ayrımı:**
  - Tier-1 & Tier-2 // Co-Yazılımcılar / Çekirdek ve Modül Geliştirme: Slicing Pie Kâr Havuzu Ortağı
  - Tier-3 & Tier-4 // Debug / QA / Saha Testi: Ücretsiz Pro/Lifetime Lisans ve Tek Seferlik Bug Bounty
- **Hak Ediş Parametreleri // Model B:**
  - Cliff // Uçurum Süresi: [6 Ay]
  - Vesting // Kademeli Hak Ediş: [%25 Cliff sonunda + %75 takip eden 3 sürümde]
  - Pasiflik Erimesi // Annual Decay: [Yıllık %25]
  - Tavan Çarpanı // Payout Cap: [6x - 8x]
  - Dağıtım Periyodu: [Her Çeyrek Sonu / 3 Ayda Bir]
- **İdari Denetim ve Taahhüt:** Bu proje Xulab Collective Manifesto ve Protokolü'ne tabidir. İdari denetim Xulab Üretici Meclisi'ne, teknik yürütme Proje Yöneticisi'ne aittir.
```

---

# EN // XULAB COMMERCIAL POLICIES, MINIMUM FLOORS & PROJECT CHARTER GUIDE

This document defines the **mandatory minimum floors, Founder Baseline protection, Co-Developer vs. QA reward separation, and ready-to-use Project Charter template** for launching **Software, Engine, and AI Development** projects under **Xulab Collective**.

> **VERSION NOTE // `v1.0`:** These Commercial Policies and reference rates are in their initial release and remain open to future revision and refinement by decision of the **Xulab Producer Council**.

> **SCOPE SEPARATION // SOFTWARE R&D vs. MARKET MEDIA SERVICES:**  
> The `Dual-License` revenue pool and point system defined here apply **strictly to Software, DSP, and AI Tool Development** projects.  
> **Revenues generated from market media production and post-production service engagements are completely independent of this software pool and belong 100% to the active squad executing the work**, provided the squad strictly adheres to the Xulab Manifesto: zero subcontractor exploitation, zero mobbing, and fair internal revenue sharing among the active team.

---

## 01 // SOFTWARE CONTRIBUTOR PROFIT POOL: MINIMUM FLOORS & RECOMMENDED RATES

| Software Project Category | Mandatory Minimum Floor | Recommended Standard Rate | Scope & Description |
| :--- | :---: | :---: | :--- |
| **1. Pure Software & Local Engine**<br>*DAW, NLE, DSP Plugins, Desktop/CLI Tools* | **Min. `10%`** | **`12% – 15%`**<br>*Max: `20%`* | Zero cloud cost projects keeping the core `AGPLv3` while selling `Dual-Licenses` to enterprise studios. |
| **2. Hybrid: Open Engine + Trained AI Weights**<br>*Local/Encrypted Weights + Commercial License* | **Min. `7.5%`** | **`10% – 15%`** | Hybrid AI/DSP projects where the legal entity funds heavy dataset curation, legal clearance, and model training. |
| **3. Heavy Cloud / GPU Service**<br>*Cloud AI, Mix, Render* | **Min. `5%`** *Net* | **`10% – 12%`** *Net* | Distributed from net service revenue after deducting direct cloud GPU/VRAM server bills. |
| **4. Xulab Shared Infrastructure / R&D Pool** | **`0% – 2.5%`** | **`1% – 2%`** | Symbolic contribution to Xulab's shared GPU, testing, and collective R&D treasury. |

---

## 02 // CO-DEVELOPER vs. DEBUG/QA SEPARATION & FOUNDER BASELINE

### 1. Founder Baseline Points
- At project inception, the founding architects' existing core codebase and architecture establish the pool's baseline denominator, such as `10,000 Points`.
- If an external Co-Developer contributes a `1,000-Point` module, they receive $\frac{1,000}{10,000 + 1,000} = 9.09\%$ of the pool, while the remaining `90.91%` stays with the founding entity. **No single small contribution can ever swallow the entire pool.**

### 2. Co-Developers vs. Debug / QA
| Contribution Tier & Type | Who Qualifies? | Compensation Model | Points / Multiplier |
| :--- | :--- | :--- | :---: |
| **`Tier-1` // Core Architecture, DSP & AI Engine** | Builders of C++/Rust/JUCE engines, real-time DSP, tensor/LLM training, AAF/OTIO/MCP core | **Profit Pool Partner** | **`500 – 2,500 Pts`**<br>*Multiplier: `2.0x`* |
| **`Tier-2` // Major Feature & Module Engineering** | Builders of new functional modules, UI/UX architecture, DAW/format integrations | **Profit Pool Partner** | **`100 – 500 Pts`**<br>*Multiplier: `1.5x`* |
| **`Tier-3` // Minor Bug Fix & Patch** | Single crash fixes, minor patches, documentation PRs | **Not in equity pool:** **Free Pro License** + **One-Off Cash `Bug Bounty`** | **Fixed Bounty / License** |
| **`Tier-4` // Field Testing & Workflow Feedback** | Practitioners testing builds, reporting bugs, and validating workflows | **Not in equity pool:** **Free `Lifetime Core / Pro` License** & Early Access | **Free License Access** |

---

## 03 // VESTING, DECAY & CAP REFERENCE PARAMETERS

| Mechanism | Mandatory Hard Limit | Recommended Standard | Protection Rule |
| :--- | :---: | :---: | :--- |
| **1. `Cliff` Period** | **Max. `6 Months`** | **`6 Months` or v1.0 release** | Code must survive in `main` for 6 months with active bug fixes by its author. |
| **2. `Vesting` Schedule** | **Min. `25%` at Cliff** | **`25%` Month 6 + `25% x 3 Releases`** | 25% vests at the 6-month Cliff; the remaining 75% vests across the next 3 releases with active maintenance. |
| **3. `Roll-off / Decay`** | **Max. `50% / Year`** | **`25% Annual Decay`** | Points of inactive contributors decay by 25% per year so the pool continues rewarding active maintainers. |
| **4. `Payout Cap`** | **Min. `5x` Multiplier** | **`5x – 8x` Cash Multiplier** | Points retire once cumulative cash payouts reach `5x–8x` of the task's initial baseline valuation. |
| **5. `Payout Cadence`** | **At least `Quarterly`** | **Every Quarter** | Pool financials are published transparently and paid out at least once per quarter. |

---

## 04 // READY-TO-USE SOFTWARE PROJECT CHARTER // `XULAB_CHARTER.md`

```markdown
# XULAB SOFTWARE PROJECT CHARTER

- **Project Name:** [e.g., ProjectName]
- **Project Lead // Chair / Lead:** [@username]
- **Council Sponsor // Founding Architect or Governing Council Member:** [@sponsor_username]
- **Project Scope // In-Scope & Out-of-Scope:** [Explicit boundaries of what the project builds and what is out of scope]
- **Project Model:** [ ] Model A // 100% Free AGPLv3  |  [ ] Model B // Incorporated / AGPLv3 Engine + Dual-License
- **Legal Entity // Model B only:** [Company Name & Jurisdiction]
- **Core & Source License:** [ ] Strict AGPLv3 // Model A  |  [ ] Copyfarleft Revenue-Bounded Source-Available + AGPLv3 Deep SDK + Dual-License // Model B
- **Co-Developer Profit Pool Share // Model B:** [15]% of Net Commercial Revenue // Mandatory Floor: 5%–10%
- **Founder Baseline Points:** [10,000 Points]
- **Reward Separation:**
  - Tier-1 & Tier-2 // Co-Developers / Core & Module Engineering: Slicing Pie Profit Pool Partners
  - Tier-3 & Tier-4 // Debug / QA / Field Testing: Free Pro/Lifetime License & One-Off Bug Bounties
- **Vesting & Point Parameters // Model B:**
  - Cliff Period: [6 Months]
  - Vesting Schedule: [25% at Cliff + 75% across next 3 releases]
  - Annual Inactivity Decay: [25% / year]
  - Payout Cap Multiplier: [6x - 8x]
  - Payout Cadence: [Quarterly]
- **Oversight & Commitment:** This project operates under the Xulab Collective Manifesto and Rulebook. Administrative oversight belongs to the Xulab Producer Council; technical execution belongs to the Project Lead.
```
