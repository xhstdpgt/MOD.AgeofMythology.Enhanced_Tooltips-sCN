参考了 [url=https://steamcommunity.com/sharedfiles/filedetails/?id=2151972324] Ippert's Enhanced Tooltips [/url] 的额外数据（感谢 NtRs. Ippert 的分享）
然后想着顺便翻译成简体中文，结果不止于此…………
相比en文件，cn文件缺少了太多的翻译代码，遂补充核对。

其次。原字体显示异常，经排查发现：是cn“台語”使用的日文汉字导致的，游戏本体自带其他字库，已经修复为黑体。
[<MSKFile typeFace = "ＭＳ Ｐゴシック" file = "mspgthc.msk"/>,……<param TypeFace = "ＭＳ Ｐゴシック"/>……] ↓
[<MSKFile typeFace = "SimHei" file = "simhei.msk"/>,……[<param TypeFace = "SimHei"/>]

还有，顺手拉高了一点历史界面里关于单位的详细描述的文本框的高度。暂时没发现遮挡问题（如果有，请告诉我遮挡了什么）——在“建筑”、“升级”的下面，多留了一块位置

P.S.:注意到！在en里还有个“LANG_XX”（对比“LANG_CN”）链接可以写自定义语言，所以使用了这个代码。【请在语言选项下选择“简体中文（MOD语言）”】
兼容性：理论上不会与其他汉化模组冲突覆盖（因为用的[LANG_XX  "Custom Language"]而不是[LANG_CN  "台語 (Chinese)"]）。
