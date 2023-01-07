# ntub-n1094402-n1094408-
N1094402 N1094408


Playing tutorial(One hour Dungeon):

press the space key to enter the game screen.press the up, down, left, right key to move.in the battle mode, here are four keys you can click:
(A) Attack. the normal hit.
(P) Potion. the item which is looked like green drink and it's function is recover the damage.
(B) Blast. the item which looked like red gem and it's function is kill enemy by one turn.
(R) Run. If you encount the enemy that is hard to knock down or you're in deseperate situation. you can press this key to escape.Not only use the potion, you can also cost the food point to recover your damage.If your food point is zero, from now on your life point will reduce, and triggering the condition of game ending is your life point delined to zero.

One hour Dungeon是一款以休閒、簡單操作為導向的RPG遊戲。以無窮盡的樓層為特色，適合想突破自我紀錄的玩家作為消遣時間使用。

·角色: 勇者(玩家)、敵人們。

·場景: 地下城(迷宮)。

·關卡: 無限，以自身能力所及為主。

·劇情: 既昏暗又緊張刺激的地下城裡，勇者正試圖從這曲折的迷宮中擊敗四面八方襲擊的敵人。獲取利益資源的同時，也為了突破更多的樓層而冒險!

·勇者對戰敵人的次數越多，等級也會因此上升，素質會變得更加強大。

·擊破的樓層越多，敵人的攻擊能力上升，也會解鎖新的敵人喔！

·由標題畫面按下空白鍵，進入遊戲主畫面。

·玩家可以使用方向鍵(上、下、左、右)控制角色的移動。

·每個樓層固定配置一個階梯，可以藉以前往下個樓層。

·觸發繭(白色物體)時，可以獲得食物。有時觸發時會遇見敵人，但也可能會誤入陷阱而死亡，觸發寶箱可獲得藥水及火焰。

·食物與生命值會依移動次數消耗，消耗過多會導致角色死亡。

按下[S]鍵可調整整體速度。1為最慢、2為中間、3為最快。 

因觸發繭而遇見敵人時，可以使用[A]、[P]、[B]、[R]鍵擊敗敵人。

·[A] = 攻擊

·[P] = 回血

·[B] = 火焰必殺技

·[R] = 逃跑


我們如何製作：
・載入Pygame模組(pygame)

・載入系統(sys)

・載入其他相關模組(random)

・定義顏色如WHITE = (255, 255, 255)

・定義座標x、y

・利用雙重迴圈，定義dungeon 各物件的值

・定義函數如make_dungeon()、draw_dungeon(bg,fnt)、put_event()…等

・輸入接收的按鍵與執行相關指令(if key[K_UP] and btl_cmd  > 0: #↑鍵) 
・載入外部資源:如圖片(imgWall = pygame.image.load(“wall.png”)、音樂pygame.mixer.Sound(“ohd_se_blaze.ogg”)

・執行main的函數

・更新畫面(display.update)

・指定影格速率(clock)

・執行 

我們在執行時的狀況有以下敘述：
・容易有錯字(漏字、大小寫不分)

・因外部資料匯入問題導致pychram無法找到所需的圖片或音樂

・資料輸入錯誤與錯置(導致產生的畫面有路線不連貫及角色落入死胡同的現象發生)

・程式碼漏打

・因版本問題(如前面所述)而無法正確地執行 


 ※版本問題說明：

一開始使用的版本(Python 3.8及Pygame 1.9.6)，在執行imgItem =[  pygame.imge.load(“……”)……]的情況下，產生因指令套件不存在而無法辨識的問題，推測是因版本尚未擁有執行所需的套件所致，隨後將版本更新成以下版本(Python 3.11及Pygame 2.1.2)，並成功執行。 


以上，謝謝各位的閱讀！

Produced by 陳筱琪(N1094408) and 陳詣涵(N1094402).
[One hour Dungeon 完整遊戲程式碼.docx](https://github.com/Q110011001/ntub-n1094402-n1094408-/files/10326985/One.hour.Dungeon.docx)
