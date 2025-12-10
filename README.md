# DayProgressBar - Rainmeter Skin

一个简洁美观的 Rainmeter 进度条皮肤，用于显示日常时间进度和项目截止日期倒计时。

## 功能特点

- **DayProgress**: 显示当天时间段的进度（例如工作时间、学习时间等）
- **Deadline**: 显示项目截止日期的倒计时进度
- 分阶段颜色变化，直观展示进度状态
- 完全可自定义的时间、颜色和尺寸

## 安装方法

1. 确保已安装 [Rainmeter](https://www.rainmeter.net/)
2. 下载本皮肤
3. 将 `DayProgressBar` 文件夹复制到 Rainmeter 皮肤目录（通常是 `C:\Users\你的用户名\Documents\Rainmeter\Skins\`）
4. 在 Rainmeter 管理器中加载皮肤

## 使用说明

### DayProgress - 日常进度条

打开 `DayProgressBar\DayProgress\DayProgress.ini` 进行配置：

```ini
; 设置开始时间和结束时间（24小时制）
StartTime=10:00
EndTime=20:00

; 设置进度阶段分隔点（百分比）
Stage1End=25  ; 0-25% 使用颜色1
Stage2End=75  ; 25-75% 使用颜色2
              ; 75-100% 使用颜色3

; 自定义颜色（R,G,B,透明度）
BarColor1=100,200,100,255  ; 绿色
BarColor2=50,170,250,250   ; 蓝色
BarColor3=255,200,50,255   ; 橙色

; 设置尺寸
W=300  ; 宽度
H=12   ; 高度
```

### Deadline - 截止日期倒计时

打开 `DayProgressBar\Deadline\Deadline.ini` 进行配置：

```ini
; 设置起始日期和截止日期
StartDate=2025-12-01 09:00:00
EndDate=2025-12-25 18:00:00

; 设置进度阶段分隔点
Stage1End=25  ; 0-25% 使用颜色1（绿色，刚开始）
Stage2End=75  ; 25-75% 使用颜色2（橙色，进行中）
              ; 75-100% 使用颜色3（红色，即将到期）
```

## 自定义选项

所有皮肤都支持以下自定义选项：

- **时间设置**: 根据需求设置时间段或日期范围
- **颜色方案**: 自定义各阶段进度条颜色、背景色、文字颜色
- **尺寸调整**: 修改进度条宽度和高度
- **字体大小**: 调整显示文字的字体大小

## 许可证

MIT License

## 贡献

欢迎提交 Issue 和 Pull Request！

## 作者

Seanicu
