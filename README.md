


## Linux

- 安装 ibus-rime

```
sudo apt install -y \
    ibus-rime librime-data-wubi librime-data-pinyin-simp

```

- 增加输入源： settings / keyboard / Input Sources :: +



- 安装配置

```
cd ~/.config
git clone --depth 1 https://github.com/FlatMapIO/rime-config.git
ln -s $PWD/rime-config/config $PWD/rime
```


在输入法菜单重新部署


## macOS



```
cd ~/.config
git clone --depth 1 https://github.com/FlatMapIO/rime-config.git
ln -s $PWD/rime-config/config ~/Library/Rime
```