📂 期末實作模組說明
1. 軟體基石：組譯器與虛擬機 (Project 6 ~ 8)
Project 6 - Assembler：實作一個組譯器，將「符號化」的組合語言轉換為電腦能執行的 0101 二進位碼。

Project 7 & 8 - VM Translator：實作堆疊式架構 (Stack-based) 的虛擬機編譯器。這是銜接高階語言與底層指令集的關鍵，負責處理算術運算與複雜的程序呼叫（Function Call）。

2. 編譯技術：從高階到中介 (Project 10 ~ 11)
Project 10 & 11 - Jack Compiler：

語法分析：將 Jack 語言（種類似 Java 的物件導向語言）進行標記化（Tokenizing）與解析。

代碼生成：將解析後的語法結構轉換為 VM Code。

學習重點：理解符號表（Symbol Table）與遞迴下降分析法。

3. 系統底層：作業系統 (Project 12)
這是專案的最頂層，實作了八大核心類別，讓 Jack 語言能具備基本的生存能力：

Math: 提供乘除法與平方根等數學運算。

Memory: 管理堆積（Heap）空間與動態記憶體分配。

Screen & Output: 實作圖形繪製演算法（如直線、圓形）與文字輸出。

Keyboard & String: 處理使用者輸入與動態字串操作。

🛠 使用技術與工具
開發語言：Jack Language, Python/C++ (用於開發 Compiler/VM)。

環境：HardwareSimulator, CPUEmulator, VMEmulator。

核心觀念：編譯原理、堆疊運算、記憶體管理、中斷與系統呼叫。

💡 專案總結
從 0 號資料夾的 Nand 閘開始，到 12 號資料夾的作業系統，這個專案體現了「抽象化」的力量：每一層的複雜度都被封裝，最終讓我們能在自己親手造出的 CPU 上執行自己寫的作業系統
