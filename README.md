
# open-arch-reiki
# 🌐 **Open Architectural Ordinance Dataset (Markdown Structured Data)**  
*English version is shown first. 日本語版は下部にあります。*

This project provides a structured Markdown dataset of building‑related municipal ordinances, enforcement regulations, and administrative guidelines.  
The dataset is being developed progressively, starting with Tokyo wards that have high building activity.

---

## **Purpose**

The primary objective of this project is to improve the efficiency of searching and referencing building‑related municipal regulations in architectural design and public administration.  
The dataset is formatted so that **designers, government officials, and AI tools** can easily access and interpret the content.

---

## **Expected Benefits**

- Reduced time and effort required for designers to locate relevant ordinances  
- More efficient administrative review enabled by accurate and well‑structured information  
- AI‑ready formatting suitable for **RAG (Retrieval‑Augmented Generation)** and other LLM workflows  
- Early preparation for **BIM‑based regulatory review expected in 2029**, through standardized data structuring  

---

## **Data Structure**

Chapters, articles, paragraphs, and items of each ordinance are mapped to Markdown heading levels (H1–H6):

- `#` Ordinance title  
- `##` Chapters / Sections  
- `###` Articles / Appendices  
- `####` Paragraphs / Supplementary provisions  
- `#####` Items  
- `######` Sub‑items (for long text)

Tables that are not machine‑readable (e.g., merged cells) are reconstructed into a consistent, machine‑readable format **without altering their meaning**.

This structuring policy is designed with the intention of serving as a **prototype for future municipal data standards**.

---

## **Included Municipal Ordinances and Regulations**

The dataset currently includes building‑related ordinances, enforcement regulations, and administrative guidelines from the following Tokyo wards:

### [**Minato Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/01_minato-ku)
- 港区建築基準法施行細則
- 港区景観条例
- 港区景観条例施行規則
- 港区単身者向け共同住宅等の建築及び管理に関する条例
- 港区単身者向け共同住宅等の建築及び管理に関する条例施行規則
- 港区地区計画の区域内における建築物の制限に関する条例
- 港区自転車等の放置防止及び自転車等駐車場の整備に関する条例
- 港区自転車等の放置防止及び自転車等駐車場の整備に関する条例施行規則
- 港区みどりを守る条例
- 港区みどりを守る条例施行規則
- 港区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 港区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規則
- 港区住宅型総合設計許可要綱
- 港区住宅型総合設計許可要綱実施細目
- 港区開発事業に係る定住促進指導要綱
- 港区開発事業に係る定住促進指導要綱実施要領
- 港区雨水流出抑制施設設置指導要綱

### [**Chiyoda Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/02_Chiyoda-ku)
- 千代田区建築基準法施行細則
- 千代田区景観まちづくり条例
- 千代田区景観まちづくり条例施行細則
- 千代田区総合設計許可要綱
- 千代田区総合設計許可要綱実施細目
- 千代田区中高層階住居専用地区建築条例
- 千代田区中高層階住居専用地区建築条例施行規則
- 千代田区建築協定条例
- 千代田区地区計画の区域内における建築物等の制限に関する条例
- 千代田区地区計画の区域内における建築物等の制限に関する条例施行規則
- 千代田区建築物の耐震改修の促進に関する法律施行細則
- 千代田区住宅基本条例
- 千代田区開発事業に係る住環境整備推進制度要綱
- 千代田区福祉のまちづくりに係る共同住宅整備要綱
- 千代田区高齢者、障害者等の移動等の円滑化の促進に関する法律施行細則
- 千代田区自転車等の放置防止及び自転車駐車場の整備に関する条例
- 千代田区都市の低炭素化の促進に関する法律施行細則
- 千代田区建築物のエネルギー消費性能の向上等に関する法律施行細則
- 千代田区開発事業に係る住環境整備推進制度実施要領
- 千代田区ワンルームマンション等建築物に関する指導要領
- 千代田区ワンルームマンション等建築物に関する指導要綱
- 千代田区建築計画の早期周知に関する条例
- 千代田区緑化推進要綱

### [**Chuo Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/03_Chuo-ku)  
- 建築基準法施行細則
- 中央区地区計画の区域内における建築物の制限に関する条例
- 中央区地区計画の区域内における建築物の制限に関する条例施行規則
- 中央区まちづくり基本条例
- 中央区まちづくり基本条例に定める開発計画への反映事項並びに開発事業に係る協議及び改善指導に関する規則条例
- 中央区の住宅及び住環境に関する基本条例
- 中央区建築協定条例
- 建築基準法第四十二条第二項の規定による道路の指定
- 建築物の耐震改修の促進に関する法律施行細則
- 建築物のエネルギー消費性能の向上等に関する法律施行細則

### [**Shibuya Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/04_Shibuya-ku)  
- 建築基準法施行細則
- 建築基準法第４２条第２項の規定に基づく道路の指定
- 渋谷区景観条例
- 渋谷区景観条例施行規則
- 渋谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 渋谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規則
- 渋谷区みどりの確保に関する条例
- 渋谷区みどりの確保に関する条例施行規則
- 渋谷区安全・安心なまちづくりのための大規模建築物に関する条例
- 渋谷区安全・安心なまちづくりのための大規模建築物に関する条例施行規則
- 渋谷区建築物再生可能エネルギー利用促進区域内における説明義務の対象となる建築物の用途及び規模を定める条例
- 渋谷区建築物のエネルギー消費性能の向上等に関する法律施行細則

### [**Shinjuku Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/05_Shinjuku-ku)  
- 新宿区建築基準法施行細則
- 新宿区みどりの条例
- 新宿区みどりの条例施行規則
- 新宿区景観まちづくり条例
- 新宿区景観まちづくり条例施行規則
- 新宿区特別工業地区内における建築物の制限に関する条例
- 新宿区建築物の耐震改修の促進に関する法律施行細則
- 新宿区建築物のエネルギー消費性能の向上等に関する法律施行細則
- 新宿区中高層階住環境保全地区の区域内における建築物の制限に関する条例
- 新宿区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 新宿区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [**Bunkyo Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/06_Bunkyo-ku)  
- 文京区建築基準法施行細則
- 文京区みどりの保護条例
- 文京区みどりの保護条例施行規則
- 文京区景観づくり条例
- 文京区景観づくり条例施行規則
- 文京区中高層建築物の建築に係る紛争の予防と調整及び開発事業の周知に関する条例
- 文京区中高層建築物の建築に係る紛争の予防と調整及び開発事業の周知に関する条例施行規則

### [**Shinagawa Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/07_Shinagawa-ku)  
- 品川区建築基準法施行規則
- 品川区みどりの条例
- 品川区みどりの条例施行規則
- 品川区景観条例
- 品川区景観条例施行規則
- 品川区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 品川区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [**Meguro Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/08_Meguro-ku)  
- 建築基準法施行細則
- 目黒区みどりの条例
- 目黒区みどりの条例施行規則
- 目黒区景観条例
- 目黒区景観規則
- 目黒区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 目黒区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規

### [**Toshima Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/09_Toshima-ku)  
- 豊島区建築基準法施行細則
- 豊島区みどりの条例
- 豊島区みどりの条例施行規則
- 豊島区景観条例
- 豊島区景観条例施行規則
- 豊島区中高層建築物の建築に係る紛争の予防及び調整に関する条例
- 豊島区中高層建築物の建築に係る紛争の予防及び調整に関する条例施行規則

### [**Taito Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/10_Taito-ku) 
- 東京都台東区建築基準法施行細則
- 東京都台東区みどりの条例
- 東京都台東区みどりの条例施行規則
- 東京都台東区景観条例
- 東京都台東区景観条例施行規則
- 東京都台東区中高層建築物の建築に係る紛争の予防及び調整に関する条例
- 東京都台東区中高層建築物の建築に係る紛争の予防及び調整に関する条例施行規則

### [**Sumida Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/11_Sumida-ku)  
- 建築基準法施行細則
- 墨田区集合住宅の建築に係る居住環境の整備及び管理に関する条例
- 墨田区集合住宅の建築に係る居住環境の整備及び管理に関する条例施行規則
- 墨田区景観条例
- 墨田区景観規則
- 墨田区中高層建築物の建築に係る紛争の予防及び調整に関する条例
- 墨田区中高層建築物の建築に係る紛争の予防及び調整に関する条例施行規則

### [**Koto Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/12_Koto-ku)
- 江東区建築基準法施行細則
- 江東区みどりの条例
- 江東区みどりの条例施行規則
- 江東区都市景観条例
- 江東区都市景観条例施行規則
- 江東区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 江東区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [**Ota Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/13_Ota-ku)
- 大田区建築基準法施行規則
- 大田区みどりの条例
- 大田区みどりの条例施行規則
- 大田区景観条例
- 大田区景観条例施行規則
- 大田区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 大田区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [**Setagaya Ward**](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/14_Setagaya-ku)
- 世田谷区みどりの基本条例
- 世田谷区風景づくり条例
- 世田谷区風景づくり条例施行規則
- 世田谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 世田谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規則
---

## **License**

- **Original texts**: Municipal ordinance databases (not subject to copyright under Article 13 of the Copyright Act of Japan)  
- **Structuring & Markdown conversion**: markdown-arch-bugyo  
- **License**: CC BY 4.0  
- Wording follows the original text  
- Table layouts are reconstructed for machine readability  
- For accuracy and updates, always refer to the official municipal ordinance databases  

---

## **Disclaimer**

Although this dataset is created based on the original texts, accuracy and currency are not guaranteed.  
For legal decisions, always consult the original documents and qualified professionals.

---

## **Update Policy**

Updates are made when ordinance revisions are confirmed.  
See commit logs for detailed update history.

---

## **Related Links**

- note：[[URL](https://note.com/md_arch_bugyo/n/n884d24b2577d)]
- Minato Ward ordinance database：[[URL](https://www1.g-reiki.net/city.minato.tokyo/reiki_menu.html)]
- Chiyoda Ward ordinance database：[[URL](https://ops-jg.d1-law.com/opensearch/SrFeF01/init?jctcd=8A8016805F)]
- Chuo Ward ordinance database：[[URL](https://krg103.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- Shibuya Ward ordinance database：[[URL](https://krg114.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- Shinjuku Ward ordinance database：[[URL](https://krg105.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- Bunkyo Ward ordinance database：[[URL](https://krg106.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- Shinagawa Ward ordinance database：[[URL](https://www.city.shinagawa.tokyo.jp/reiki/reiki_menu.html)]
- Meguro Ward ordinance database：[[URL](https://www1.g-reiki.net/meguro/reiki_menu.html)]
- Toshima Ward ordinance database：[[URL](https://krl600.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- Taito Ward ordinance database：[[URL](https://www1.g-reiki.net/taito/reiki_menu.html)]
- Sumida Ward ordinance database：[[URL](https://www.city.sumida.lg.jp/wkg/reiki_int/reiki_menu.html)]
- Koto Ward ordinance database：[[URL](https://www1.g-reiki.net/city.koto/reiki_menu.html)]
- Ota Ward ordinance database：[[URL](https://www1.g-reiki.net/cityota.reiki/reiki_menu.html)]
- Setagaya Ward ordinance database：[[URL](https://ops-jg.d1-law.com/opensearch/SrFeF01/init?jctcd=8A801680C5)

---

# **日本語版 **

# open-arch-reiki
# 建築関連条例等 構造化データ集（Markdown形式）

建築関連条例・基準・要綱等を構造化（Markdown形式）データに変換し、
公開するオープンデータプロジェクトです。
現状は23区内の建築需要の高い区から順次整備中です。

## 目的

営繕業務における関係条例の検索効率化を主目的とし、
設計者・行政担当者・AIツールが条例を参照しやすい形式で提供します。

## 期待する効果

- 設計者の条例検索コストの削減
- 精度の高い計画による行政審査の効率化
- AI-Ready化（RAG等への活用）
- 2029年BIMデータ審査への準備としてのデータ構造化

## データ構造について

条例の章・条・項・号をMarkdownの見出し階層（H1〜H6）に対応させています。
- "#" 条例タイトル
- "##" 章、款、目、節
- "###" 条、別表
- "####" 項、附則
- "#####" 号
- "######" 号以下で文字数の多い場合
表についてはAIが読み込めない形式（セル結合等）を、
意味を変えずに機械可読な形式に再構成しています。

この構造化の方針は、将来的な自治体データ標準のプロトタイプとなることを
意識して設計しています。

## 収録自治体の条例・施行規則等

### [港区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/01_minato-ku)
- 港区建築基準法施行細則
- 港区景観条例
- 港区景観条例施行規則
- 港区単身者向け共同住宅等の建築及び管理に関する条例
- 港区単身者向け共同住宅等の建築及び管理に関する条例施行規則
- 港区地区計画の区域内における建築物の制限に関する条例
- 港区自転車等の放置防止及び自転車等駐車場の整備に関する条例
- 港区自転車等の放置防止及び自転車等駐車場の整備に関する条例施行規則
- 港区みどりを守る条例
- 港区みどりを守る条例施行規則
- 港区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 港区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規則
- 港区住宅型総合設計許可要綱
- 港区住宅型総合設計許可要綱実施細目
- 港区開発事業に係る定住促進指導要綱
- 港区開発事業に係る定住促進指導要綱実施要領
- 港区雨水流出抑制施設設置指導要綱

### [千代田区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/02_Chiyoda-ku)
- 千代田区建築基準法施行細則
- 千代田区景観まちづくり条例
- 千代田区景観まちづくり条例施行細則
- 千代田区総合設計許可要綱
- 千代田区総合設計許可要綱実施細目
- 千代田区中高層階住居専用地区建築条例
- 千代田区中高層階住居専用地区建築条例施行規則
- 千代田区建築協定条例
- 千代田区地区計画の区域内における建築物等の制限に関する条例
- 千代田区地区計画の区域内における建築物等の制限に関する条例施行規則
- 千代田区建築物の耐震改修の促進に関する法律施行細則
- 千代田区住宅基本条例
- 千代田区開発事業に係る住環境整備推進制度要綱
- 千代田区福祉のまちづくりに係る共同住宅整備要綱
- 千代田区高齢者、障害者等の移動等の円滑化の促進に関する法律施行細則
- 千代田区自転車等の放置防止及び自転車駐車場の整備に関する条例
- 千代田区都市の低炭素化の促進に関する法律施行細則
- 千代田区建築物のエネルギー消費性能の向上等に関する法律施行細則
- 千代田区開発事業に係る住環境整備推進制度実施要領
- 千代田区ワンルームマンション等建築物に関する指導要領
- 千代田区ワンルームマンション等建築物に関する指導要綱
- 千代田区建築計画の早期周知に関する条例
- 千代田区緑化推進要綱

### [中央区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/03_Chuo-ku)
- 建築基準法施行細則
- 中央区地区計画の区域内における建築物の制限に関する条例
- 中央区地区計画の区域内における建築物の制限に関する条例施行規則
- 中央区まちづくり基本条例
- 中央区まちづくり基本条例に定める開発計画への反映事項並びに開発事業に係る協議及び改善指導に関する規則条例
- 中央区の住宅及び住環境に関する基本条例
- 中央区建築協定条例
- 建築基準法第四十二条第二項の規定による道路の指定
- 建築物の耐震改修の促進に関する法律施行細則
- 建築物のエネルギー消費性能の向上等に関する法律施行細則

### [渋谷区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/04_Shibuya-ku)
- 建築基準法施行細則
- 建築基準法第４２条第２項の規定に基づく道路の指定
- 渋谷区景観条例
- 渋谷区景観条例施行規則
- 渋谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 渋谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規則
- 渋谷区みどりの確保に関する条例
- 渋谷区みどりの確保に関する条例施行規則
- 渋谷区安全・安心なまちづくりのための大規模建築物に関する条例
- 渋谷区安全・安心なまちづくりのための大規模建築物に関する条例施行規則
- 渋谷区建築物再生可能エネルギー利用促進区域内における説明義務の対象となる建築物の用途及び規模を定める条例
- 渋谷区建築物のエネルギー消費性能の向上等に関する法律施行細則

### [新宿区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/05_Shinjuku-ku)
- 新宿区建築基準法施行細則
- 新宿区みどりの条例
- 新宿区みどりの条例施行規則
- 新宿区景観まちづくり条例
- 新宿区景観まちづくり条例施行規則
- 新宿区特別工業地区内における建築物の制限に関する条例
- 新宿区建築物の耐震改修の促進に関する法律施行細則
- 新宿区建築物のエネルギー消費性能の向上等に関する法律施行細則
- 新宿区中高層階住環境保全地区の区域内における建築物の制限に関する条例
- 新宿区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 新宿区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [文京区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/06_Bunkyo-ku)
- 文京区建築基準法施行細則
- 文京区みどりの保護条例
- 文京区みどりの保護条例施行規則
- 文京区景観づくり条例
- 文京区景観づくり条例施行規則
- 文京区中高層建築物の建築に係る紛争の予防と調整及び開発事業の周知に関する条例
- 文京区中高層建築物の建築に係る紛争の予防と調整及び開発事業の周知に関する条例施行規則

### [品川区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/07_Shinagawa-ku)
- 品川区建築基準法施行規則
- 品川区みどりの条例
- 品川区みどりの条例施行規則
- 品川区景観条例
- 品川区景観条例施行規則
- 品川区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 品川区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [目黒区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/08_Meguro-ku)
- 建築基準法施行細則
- 目黒区みどりの条例
- 目黒区みどりの条例施行規則
- 目黒区景観条例
- 目黒区景観規則
- 目黒区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 目黒区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規

### [豊島区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/09_Toshima-ku)
- 豊島区建築基準法施行細則
- 豊島区みどりの条例
- 豊島区みどりの条例施行規則
- 豊島区景観条例
- 豊島区景観条例施行規則
- 豊島区中高層建築物の建築に係る紛争の予防及び調整に関する条例
- 豊島区中高層建築物の建築に係る紛争の予防及び調整に関する条例施行規則

### [台東区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/10_Taito-ku)
- 東京都台東区建築基準法施行細則
- 東京都台東区みどりの条例
- 東京都台東区みどりの条例施行規則
- 東京都台東区景観条例
- 東京都台東区景観条例施行規則
- 東京都台東区中高層建築物の建築に係る紛争の予防及び調整に関する条例
- 東京都台東区中高層建築物の建築に係る紛争の予防及び調整に関する条例施行規則

### [墨田区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/11_Sumida-ku)
- 建築基準法施行細則
- 墨田区集合住宅の建築に係る居住環境の整備及び管理に関する条例
- 墨田区集合住宅の建築に係る居住環境の整備及び管理に関する条例施行規則
- 墨田区景観条例
- 墨田区景観規則
- 墨田区中高層建築物の建築に係る紛争の予防及び調整に関する条例
- 墨田区中高層建築物の建築に係る紛争の予防及び調整に関する条例施行規則

### [江東区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/12_Koto-ku)
- 江東区建築基準法施行細則
- 江東区みどりの条例
- 江東区みどりの条例施行規則
- 江東区都市景観条例
- 江東区都市景観条例施行規則
- 江東区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 江東区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [大田区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/13_Ota-ku)
- 大田区建築基準法施行規則
- 大田区みどりの条例
- 大田区みどりの条例施行規則
- 大田区景観条例
- 大田区景観条例施行規則
- 大田区中高層建築物の建築に係る紛争の予防と調整に関する条例
- 大田区中高層建築物の建築に係る紛争の予防と調整に関する条例施行規則

### [世田谷区](https://github.com/markdown-arch-bugyo/open-arch-reiki/tree/main/14_Setagaya-ku)
- 世田谷区みどりの基本条例
- 世田谷区風景づくり条例
- 世田谷区風景づくり条例施行規則
- 世田谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例
- 世田谷区中高層建築物等の建築に係る紛争の予防と調整に関する条例施行規則
  
## ライセンス

- **原典**：各自治体例規集（著作権法第13条により著作権の対象外）
- **構造化・Markdown変換**：[markdown-arch-bugyo]
- **ライセンス**：CC BY 4.0
- 文言は原文に準拠しています
- 表のレイアウトは機械可読性のため再構成しています
- 最新性・正確性は各自治体の公式例規集を参照してください

## 免責事項

本データは原典に基づき作成していますが、
内容の正確性・最新性を保証するものではありません。
法的判断が必要な場合は必ず原典および専門家にご確認ください。

## 更新方針

条例改正が確認された場合、順次更新します。
更新履歴はコミットログを参照してください。

## 関連リンク

- note：[[URL](https://note.com/md_arch_bugyo/n/n884d24b2577d)]
- 原典（港区例規集）：[[URL](https://www1.g-reiki.net/city.minato.tokyo/reiki_menu.html)]
- 原典（千代田区例規集）：[[URL](https://ops-jg.d1-law.com/opensearch/SrFeF01/init?jctcd=8A8016805F)]
- 原典（中央区例規集）：[[URL](https://krg103.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- 原典（渋谷区例規集）：[[URL](https://krg114.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- 原典（新宿区例規集）：[[URL](https://krg105.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- 原典（文京区例規集）：[[URL](https://krg106.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- 原典（品川区例規集）：[[URL](https://www.city.shinagawa.tokyo.jp/reiki/reiki_menu.html)]
- 原典（目黒区例規集）：[[URL](https://www1.g-reiki.net/meguro/reiki_menu.html)]
- 原典（豊島区例規集）：[[URL](https://krl600.legal-square.com/HAS-Shohin/page/SJSrbLogin.jsf)]
- 原典（台東区例規集）：[[URL](https://www1.g-reiki.net/taito/reiki_menu.html)]
- 原典（墨田区例規集）：[[URL](https://www.city.sumida.lg.jp/wkg/reiki_int/reiki_menu.html)]
- 原典（江東区例規集）：[[URL](https://www1.g-reiki.net/city.koto/reiki_menu.html)]
- 原典（大田区例規集）：[[URL](https://www1.g-reiki.net/cityota.reiki/reiki_menu.html)]
- 原典（世田谷区例規集）：[[URL](https://ops-jg.d1-law.com/opensearch/SrFeF01/init?jctcd=8A801680C5)


