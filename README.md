# ym-bendo
列出陽明活動有便當的場次，我想吃便當，

陽明便當網：<https://portal.ym.edu.tw/umchi/activity/>   
陽明交大合校後的： <https://ymportal.nycu.edu.tw/umchi/activity/>   

## 使用
* 安裝[chrome](https://www.google.com/intl/zh-TW/chrome/)與下載[chrome-driver](https://chromedriver.chromium.org/)

* 安裝一些套件
    ```
    pip install -r requirements.txt
    ```
* `jupyter-notebook`
* 打開bendo.ipynb，`driver_path`改成自己的chrome-driver路徑
  ```
  driver_path = Path("/home/wenlin/d/custom_command/chromedriver")
  base_url = 'https://portal.ym.edu.tw/umchi/activity/'
  ```
* jupyter內按按按

## TO-DO
想說合校之後，應該就沒這種便當，所以就做到這裡沒搞了，但目前好像還很多，不過... 好像我也要畢業走人，所以想實行的功能就給其他人了

- [ ] line bot整合
- [ ] 自動報名
- [ ] 提醒你當天有便當吃

