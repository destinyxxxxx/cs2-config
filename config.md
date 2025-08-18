[TOC]

# CS配置

## 显示子弹轨迹
```
r_drawtracers_firstperson "1";
```

---

## 关闭自动帮助提示
```
cl_autohelp "0";
```

---

## 遥测

### 显示网络波动
```
cl_hud_telemetry_net_misdelivery_show "2";
```

### 显示延迟
```
cl_hud_telemetry_ping_show "2";
```

### 显示帧间时间与FPS
```
cl_hud_telemetry_frametime_show "2";
```

### 禁用屏幕上的FPS计数器
```
cl_showfps "0";
```

---

## 设置最大帧率
```
fps_max "999";
```

---

## Hud

### 显示目标的名字和血量
```
hud_showtargetid "1";
```

### Hud大小
```
hud_scaling "1";
```

### Hud颜色
```
cl_hud_color "4";
```

### 玩家大计数
```
cl_teamcounter_playercount_instead_of_avatars "1";
```

---

## 雷达

### 雷达Hud大小
```
cl_hud_radar_scale "0.910000";
```

### 雷达保持玩家居中
```
cl_radar_always_centered "1";
```

### 雷达旋转
```
cl_radar_rotate "1";
```

### 雷达人物标点大小
```
cl_radar_icon_scale_min "0.500000";
```

### 雷达地图缩放
```
cl_radar_scale "0.4";
```

---

## 显示设置
调整全屏模式下的伽玛值，值为2.0可以使屏幕更亮
```
r_fullscreen_gamma "2.0";
```

###  亮度
93%

### 纵横比
16:9

### 显示模式
全屏

## 高级视频设置

### 全局阴影效果
高

### 模型/贴图细节
低

### 阴影细节
低

### 增强角色对比度
已禁用

### 多重采样抗锯齿
4x MSAA

### 贴图过滤模式
双线性

### 等待垂直同步
已禁用

### 粒子细节
低

### 环境光遮蔽
已禁用

### 高动态范围
性能

### Fidelity FX超级分辨率
已禁用（最高品质）

### NAIDIA Reflex低延迟
已禁用

---

## 声音设置

### 关闭耳机 EQ(均衡器) 增强
```
snd_headphone_eq "0";
```

### 控制声音空间化（定位）时的插值强度
```
snd_spatialize_lerp "0.5";
```

### 关闭 Steam Audio 的透视校正（声音衰减与角度修正）
```
snd_steamaudio_enable_perspective_correction "0";
```

### 设置音频混音的缓冲时长
```
snd_mixahead "0.011";
```

### 回合最后 10 秒的警告音
```
snd_tensecondwarning_volume "0.05";
```

### 菜单音乐
```
snd_menumusic_volume "0";
```

### 任务目标提示音
```
snd_mapobjective_volume "0";
```

### 死亡视角音效
```
snd_deathcamera_volume "0";
```

### MVP 音效
```
snd_mvp_volume "0";
```

### 回合行动提示音
```
snd_roundaction_volume "0";
```

### 回合结束音效
```
snd_roundend_volume "0";
```

### 回合开始音效
```
snd_roundstart_volume "0";
```

---

## 按键绑定

### 按键解绑
```
unbind "t";
unbind "z";
unbind "x";
unbind "c";
unbind "v";
unbind "i";
```

### 手雷
```
bind "z" "slot6";
```

### 闪光弹
```
bind "t" "slot7";
```

### 燃烧瓶
```
bind "x" "slot10";
```

### 烟雾弹
```
bind "c" "slot8";
```

### 使用
```
bind "e" "+use";
```

### 监视武器
```
bind "f" "+lookatweapon";
```

### 购买菜单
```
bind "b" "buymenu";
```

### 丢弃武器
```
bind "g" "drop";
```

### 切换左/右手持枪视角
```
bind "h" "switchhands";
```

### 蹲
```
bind "ctrl" "+duck;
```

### 静步
```
bind "shift" "+sprint";
```

### 跳
```
bind "space" "+jump";
```

### 滚轮跳
```
bind "mwheeldown" "+jump";
bind "mwheelup" "+jump";
```

### 按键语音
```
bind "k" "+voicerecord";
bind "mouse4" "+voicerecord";
```

### 快捷聊天轮盘
```
bind "o" "+radialradio3";
```

### 涂鸦菜单
```
bind "mouse5" "+spray_menu";
```

### 丢刀
```
bind "n" "say_team !drop";
```

### 跳投
```
bind "v" "+jump;+pwathrow;";
```

### w+跳投
```
bind "j" "+pwawjump;+pwathrow";
```

### 跑图训练

#### 回放上一个道具
```
bind "i" "pwa_rethrow_last_grenade";
```

#### 清除烟雾弹
```
bind "l" "pwa_kill_smokegrenade";
```

#### 飞天
```
bind "p" "noclip";
```

---

## 灵敏度

### DPI
+ 800

### 鼠标灵敏度
```
sensitivity "0.9";
```

### 缩放灵敏度倍数
```
zoom_sensitivity_ratio "1.2";
```

---

## 持枪视角
```
viewmodel_fov 68; viewmodel_offset_x 2.5; viewmodel_offset_y 0; viewmodel_offset_z -1.5; viewmodel_presetpos 2; cl_usenewbob false;
```

---

## 准星代码

### 载物准星
```
CSGO-UF6bG-z2DWa-jFYCi-QAqX9-PX6uC
```

### NiKo准星
```
CSGO-MXQrt-xQWeR-wnuzU-t4cLq-qKwLA
```