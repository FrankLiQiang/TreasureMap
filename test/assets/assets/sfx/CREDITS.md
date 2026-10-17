# 音效来源

牌和金币的声音来自真实录音，由 `tool/make_sfx.py`、`tool/make_coin_sfx.py` 剪辑；提示音由 `tool/gen_sfx.py` 合成，金币落桌声由 `tool/make_coin_drop.py` 合成。

| 文件 | 来源 | 许可 |
|---|---|---|
| select0–3、deselect0–2、land0–2 | freesound.org #329099 "Domino pieces 1"，作者 Macif | CC0 |
| coin0–3 | Kenney "RPG Audio"（www.kenney.nl）中的 handleCoins2，由 `tool/make_coin_sfx.py` 变调 | CC0 |
| coinDrop0–7、coinShower | 程序合成（`tool/make_coin_drop.py`） | — |
| deal、deal_pluck（备用）、ding0–9、win、wrong | 程序合成 | — |
| cheer | BigSoundBank #0236 "Shouts and Applauses of Teens #1"（bigsoundbank.com），转单声道、淡入淡出、响度归一 | CC0 |
