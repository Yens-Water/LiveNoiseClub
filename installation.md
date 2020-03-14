# FoxDot x livecoding x VScode

###### tags: `vscode`

> :video_game: 最近想重拾livecoding的創作方式， 想改用atom作為編譯介面，按照FoxDot官方網站（https://foxdot.org/installation/ ）去做，但是Atom並沒有抓到python3，一直指向python2，也沒有地方可以做更改，因此轉向vs code 作為編譯介面。

## :memo: 如何在VScode裡裝FoxDot與指向Python3
>supercollider/FoxDot/Python3的安裝就不在此文件做說明了。

### 按 Extension 中安裝FoxDot
- 搜尋FoxDot 並安裝
![](https://i.imgur.com/NvGyhKD.png)
- 發現這個extension全世界只有9個人下載XDDDD，往下拉 Details 就會看見Extension Setting可以指定Python路徑，即是我們想要的功能！
![](https://i.imgur.com/aOWeNcD.png)
- 打開自己電腦的Terminal找到Python3路徑，並複製路徑。
> $ which python3
- 在vs code 裡 按extension setting，並貼上自己的python3 path
![Uploading file..._yapun7y5h]()
![](https://i.imgur.com/lMzwSo7.png)


### 每次開啟操作
> 就一步一步操作吧！

- [ ] 開啟 SuperCollider 並打下 FoxDot.start，按command+enter 做執行
![](https://i.imgur.com/rGsYNIO.png)
- [ ] 在terminal 裡打 $code . ，去開啟vscode，並打＄touch 檔案名.py 去成立新檔案
- [ ] 在vscode 裡 command+shift+p，按下FoxDot:Start
![](https://i.imgur.com/Z11tn2K.png)
- [ ] 要執行每一下時按下 command+enter 即可



:::info
FoxDot live coding 教學：https://foxdot.org/start/