# Some interesting script for ICLAB
[TOC]
## 功能介紹
1. **登入時顯示目前 quota 百分比**
    ![](https://hackmd.io/_uploads/BJEdAREzT.png =500x)
2. **快速切換資料夾**
    ```
    輸入 <kbd>0</kbd> 快速切換到 `00_TESTBED`
    輸入 <kbd>1</kbd> 快速切換到 `01_RTL`
    輸入 <kbd>2</kbd> 快速切換到 `02_SYN`
    輸入 <kbd>3</kbd> 快速切換到 `03_GATE`
    輸入 <kbd>4</kbd> 快速切換到 `04_MEM`
    輸入 <kbd>9</kbd> 快速切換到 `09_SUBMIT`
    輸入 <kbd>m</kbd> 快速切換到 `Memory`
    ```
    ![](https://hackmd.io/_uploads/rkrX1yBfa.gif)
3. **一鍵修改 clk peroid**
    輸入 <kbd>c</kbd> 查看目前 `clk` 設定
    輸入 <kbd>c</kbd> <kbd>peroid</kbd>修改並顯示 `clk`
    ![](https://hackmd.io/_uploads/H1bweyrGT.gif)
4. **一鍵開啟/關閉 fsdb**
    輸入 <kbd>f</kbd> 查看目前 `fsdb` 設定
    輸入 <kbd>f</kbd> <kbd>rtl</kbd> <kbd>on/off</kbd>修改並顯示 `rtl fsdb` 設定
    輸入 <kbd>f</kbd> <kbd>gate</kbd> <kbd>on/off</kbd>修改並顯示 `gate fsdb` 設定
    輸入 <kbd>f</kbd> <kbd>post</kbd> <kbd>on/off</kbd>修改並顯示 `post fsdb` 設定
    ![](https://hackmd.io/_uploads/SkwQzyHzT.gif)
5. **一鍵開啟 DesignWare IP User Guide**
    輸入 <kbd>dwip</kbd> 開啟 DesignWare IP Pdf
    輸入 <kbd>io</kbd> 開啟 IO Pdf
    ![](https://hackmd.io/_uploads/rJpx7krGa.gif)

## 腳本內容與設定方式
1. 切換回家目錄
    ```sh=
    cd $HOME
    ```
2. 將 `src` 內的 `.cshrc` 和 `script` 資料夾直接丟到家目錄內
    ![image](https://hackmd.io/_uploads/SkVb7sCnA.png)
3. Terminal 輸入指令: `source $HOME/.cshrc`
4. **之後如果要修改Lab路徑**
    * 編輯`~script/setting.csh`中的`set FOLDER="Lab??/Exercise"`
    * 或直接輸入`setting`，將跳出 ![](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/512px-Visual_Studio_Code_1.35_icon.svg.png =12x) VSCode 視窗後編輯
    ![](https://hackmd.io/_uploads/HJID4ErMa.png)

