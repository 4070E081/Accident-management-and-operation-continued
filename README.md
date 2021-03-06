# Accident-management-and-operation-continued
## 非技術性風險
```
人為破壞
		盜賊入侵
		社交工程
		內部有心人士
自然災害
		火災
		水災
		地震
公共事故
		停電
		停水
		戰爭或社運
```
## 門禁管制
```
警衛或接待員仍然是門禁管制的最佳選擇，他們人性化、機動、並且判斷合理，遠優於任何科技防禦設備。但他們若缺乏訓練、沒有紀律則會造成組織「錯誤的安全感 (false sense of security)」，以為有保障而鬆懈，反而造成組織更加脆弱。
```
## 入侵感應設備
```
入侵感應設備的種類較多：
最常用於圍牆上的是當物件通過時，靠切割紅外線光束來感應。
被動式紅外線感應器可以感應體熱的輻射。也有利用超音波反射、微波感應或氣壓感應。
```
## 防範社交工程 – 員工教育訓練
```
資訊安全認知 (awareness)：目的是讓大家注意資訊安全的重要。可以播放錄影帶、在組織內部刊物撰文宣導、製作海報等。若以演講方式實施，通常不會談太深入的細節，可以多講案例和攻擊者的手法等。
資訊安全訓練 (training)：著重於訓練工作上所需要的資訊安全知識與技巧。要說明組織的安全需求，並讓員工知道自己對資訊安全所應盡的責任。對個別員工可能需要更深入的訓練，例如設定防火牆或執行資訊安全內部稽核等。
資訊安全教育 (education)：訓練通常專注在必須的技巧；教育則更深入與全面。較大型的組織應該培植自己的資訊安全專家 (例如取得CISSP 或 ISMS-LA 證照者)，負責公司資訊安全工作，並訓練其他員工。
```
## 自然災害與火災的預防
```
自然災害只破壞資訊的可用性 (A)，但與機密性 (C) 和完整性 (I) 無關。因此防禦方法以系統備援或資料備份為主，只要能延續可用性就大致沒問題。
```
## 閉路監視設施 
```
偵測 (detection)：偵測到物件。
識別 (recognition)：識別那個物件是什麼。
指認 (identification)：指認物件的部分細節。
```
## 火災偵測器
```
離子型煙幕偵測器 (ionization-type smoke detectors)：火焰燃燒產生導電之離子，使接收器中的電流訊號增強。
```
## 滅火設備 FM-200
```
氣體性滅火藥劑 (如FM200) ：平常以液態加壓存於容器內，啟動噴放時即汽化迅速與空氣混合；是一種快速滅火藥劑。
因FM-200 TM自動滅火設備係應用於全區域放射系統(Total Flodding)環境，應於偵知火災發生，設備動作前，自動連動關閉空調、排氣系統等開口部。
FM-200 TM自動滅火設備概由氣體管路系統與自動偵測控制系統兩部份組成。氣體管路系統由藥劑儲存鋼瓶、釋放閥、(或選擇閥)、管路、噴頭、、等組成，用於儲存、運送滅火藥劑，以達到提供滅火藥劑之作用；自動偵測控制系統由自動滅火控制盤、探測器、警報裝置、手動/自動啟動裝置、、等組成，用於自動偵測、告警、手動或自動釋放氣體管路系統，達到自動滅火之功能。
```
## 降低地震及其他天然災害損失
```
建立完整的系統備援及資料備份。「異地備援」與主機房最好距離三十公里以上，避免處在同一地震帶。
```
## 公共事故引發的損失
```
重要的設備應該有不斷電系統 (UPS)，組織最好自備發電機以備不時之需；若經費允許可增加備援UPS與發電機。
自備發電機除了能讓資訊系統在停電時持續運作外，也可供應機房冷氣機的電源，避免密閉機房的溫度升高造成電腦故障。
```
## 媒體資料的清除
```
對極機密的資料來說，以正常磁頭寫入還是可能殘留「資料剩磁 (data remanence)」。這時可以使用磁場中和機 (degausser) 將磁碟內每位元的磁性都調為中性。
```
## 磁碟損毀與 RAID
```
RAID:是把多個硬碟組合成為一個邏輯磁區，因此，作業系統只會把它當作一個硬碟。RAID常被用在伺服器電腦上，並且常使用完全相同的硬碟作為組合。由於硬碟價格的不斷下降與RAID功能更加有效地與主機板整合，它也成為普通用戶的一個選擇，特別是需要大容量儲存空間的工作。

RAID 0 亦稱為帶區集(striping)。它將兩個以上的磁碟並聯起來，成為一個大容量的磁碟。在存放資料時，分段後分散儲存在這些磁碟中，因為讀寫時都可以並列處理，所以在所有的級別中，RAID 0的速度是最快的。但是RAID 0既沒有冗餘功能，也不具備容錯能力，如果一個磁碟（物理）損壞，所有資料都會遺失，危險程度與JBOD相當。
RAID 2 是將兩組以上的N個磁碟相互作為鏡像，並在一些多執行緒作業系統中能有很好的讀取速度，理論上讀取速度等於硬碟數量的倍數，與RAID 0相同。只要一個磁碟

```
## 災難造成的影響
```
直接的財產損失
客戶失去信心
災害復原成本過大
失去關鍵技術或生產能力
失去主要領導人或技術擁有者
```
## NIST 800-34 的七個步驟
```
https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-34r1.pdf
建立緊急應變政策
	尋找相關條文與需求
	建立緊急應變政策
	核准政策
	宣導政策
進行業務衝擊分析
	識別主要資訊資源
	識別衝擊與承受度
	訂定復原的順序
識別預防控制
	建置控制
	維護控制
訂定復原策略 
	識別方法
	將方法整合進系統架構
建立緊急應變計畫
	支援訊息
	通知與啟動階段
	復原階段
	重建階段
訓練、測試、演練
	建立測試的目標
	設定成功的標準
	記錄經驗
	整合進計畫
	訓練員工
計畫的維護
	檢討及更新計畫
	協調內、外部組織
	控制文件的分發
	控制文件的變更
```
##  異地備援
```
冷備援 (cold sites)：提供一個緊急事件下的一個可以繼續操作的建築空間，擁有電源、空調等基本設備，但沒有任何電腦硬體。
暖備援 (warm sites)：通常只有某部份的執行環境(某些硬體、週邊裝置)，並沒有完整的設備或軟體安裝。
熱備援 (hot sites)：隨時軟硬體及人員準備妥當，一旦緊急應變計畫啟動，可在幾小時內復原資訊服務。
全備援 (mirrored sites)：平時就與主機房完全同步備援，系統完全相同且資訊即時備份。一旦主機房服務中斷，備援系統立即啟動。
```
