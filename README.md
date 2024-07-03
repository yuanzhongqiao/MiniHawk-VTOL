<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text">
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/MiniHawkIso.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/MiniHawkIso.png" width="400" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迷你鹰垂直起降</font></font><a name="user-content-head-brief"></a></h1><a id="user-content-minihawk-vtol-" class="anchor" aria-label="永久链接：MiniHawk-VTOL" href="#minihawk-vtol-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MiniHawk VTOL 是一款 3D 打印的三旋翼/固定翼混合飞机，能够垂直起飞和降落。与其前身</font></font><a href="https://diydrones.com/profiles/blogs/the-orange-hawk-tricopter-flying-wing-vtol-uav" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OrangeHawk VTOL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一样，MiniHawk 旨在用于 R/C、FPV 和 UAV 实验。此存储库中提供了机械图稿、构建说明和配置设置。</font></font></p>
<blockquote>
<p dir="auto"><strong><g-emoji class="g-emoji" alias="warning"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚠️</font></font></g-emoji><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自述文件 - 项目稳定性和新版本</font></font><g-emoji class="g-emoji" alias="warning"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚠️</font></font></g-emoji><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 2022 年 3 月 18 日：您很可能是通过 YouTube 视频上的链接偶然发现这个项目的，例如</font></font><a href="https://www.youtube.com/watch?v=FYqH4kHllrU" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何不进行 VTOL 无人机飞行测试</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或其他视频之一。如果您想尝试制作这个项目，那就去做吧！截至撰写本文时，此 repo 上的所有 STL 文件、本文左侧的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.0 版 - 修补程序和 2.1 预览</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zip 文件以及最近上传到 Hackaday.io 页面的文件都是“安全的”。以前，存在一些设计缺陷（旧的倾斜机舱设计），但这些问题仅存在于 2 月 23 日修补程序之前的 2.0 版 STL 中。同样，此处</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分支上的所有内容都应该可以安全构建，并且在 2022 年的大部分时间都不会改变。</font></font></strong></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在，话虽如此，但新版本 2.1 即将发布。但是，目前，这个新版本不会更改任何当前的 STL，因此，您可以完全放心使用 STL，一切都运行良好，飞行效果也很好，并且直到今年年底或明年年初才会发布飞机设计的任何更改。V2.1 的发布将添加一些新的奖励 STL/功能，否则只是完善演示或重写文档。几个月来，我一直停留在 2.1 版的预发布阶段，因此本 README 的某些部分正在重写，例如构建说明和添加零件树图等。以下是我对当前构建项目的建议：</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/StephenCarlson/MiniHawk-VTOL/tree/development#build-sequence-"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发分支构建说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，了解更新的构建说明。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览</font></font><a href="https://github.com/StephenCarlson/MiniHawk-VTOL/tree/development/doc-Documentation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发分支文档文件夹</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以查找所有新的构建说明图像；其中许多尚未在更新的构建说明中添加或使用。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">观看</font></font><a href="https://www.youtube.com/watch?v=nICNlJhoEvw" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“100 秒内完成 MiniHawk-VTOL 组装”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以查看动画构建步骤。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://github.com/StephenCarlson/MiniHawk-VTOL#build-sequence-"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与下面的旧版本构建说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进行交叉引用</font><font style="vertical-align: inherit;">。您将看到旧版本 1.0 发行版的图像和步骤，因此请忽略不存在的功能或在 1.5 年内重新设计的功能。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">抱歉弄得一团糟，希望对您有所帮助。我喜欢在有空的时候推广和完善这个项目。如果您有任何问题，请告诉我，祝您玩得开心！-Steve</font></font></strong></p>
</blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">里程碑</font></font></strong></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">日期</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">事件</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2020 年 10 月 15 日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始版本（v1.0）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2021 年 10 月 2 日</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本 2（v2.0，MH7_ 前缀）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预发布</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本 2.1</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年第一季度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本 2.2</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hackaday 的项目页面：</font></font><a href="https://hackaday.io/project/175286-minihawk-vtol" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HACKADAY.IO 页面</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MiniHawk 设计细节和功能在此讨论：</font></font><a href="https://www.rcgroups.com/forums/showthread.php?3986653-MiniHawk-VTOL-A-3D-Printed-Tricopter-Tilt-Rotor-Fixed-Wing-Plank" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RCGroups VTOLs 论坛主题</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区成员推荐的 MiniHawk-VTOL 构建：</font></font><a href="https://www.rcgroups.com/forums/showthread.php?3750791-KatanaGuy-s-MiniHawk-VTOL" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RCGroups 3D 打印论坛主题</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">随附的构建视频系列：</font></font><a href="https://www.youtube.com/playlist?list=PLEMjH2uELUcYI_DS1zthgjE4Su79LeA_G" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YouTube 播放列表</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Betaflight VTOL 固件版本：</font></font><a href="https://github.com/StephenCarlson/betaflight/tree/vtol-motor-mix"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">vtol-motor-mix</font></font></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h1><a id="user-content-table-of-contents" class="anchor" aria-label="固定链接：目录" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li><a href="#head-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简介</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
1.1</font></font><a href="#head-description"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
1.2</font></font><a href="#head-usage"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用此 Repo</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
1.3</font></font><a href="#head-faqs"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">备注/常见问题解答</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
1.4</font></font><a href="#head-metrics"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指标</font></font></a></li>
<li><a href="#build-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建信息</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
2.1</font></font><a href="#build-tools"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐工具</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
2.2</font></font><a href="#build-components"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">组件和电子设备</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
2.3</font></font><a href="#build-airframeparts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机身零件清单</font></font></a></li>
<li><a href="#buildseq-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建步骤</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
3.1</font></font><a href="#buildseq-part1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 1 部分 - 机身结构</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
3.2</font></font><a href="#buildseq-part2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 2 部分 - 连杆和伺服装置</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
3.3</font></font><a href="#buildseq-part3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 3 部分 - 电子设备和精加工</font></font></a></li>
<li><a href="#flight-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行测试</font></font></a></li>
<li><a href="#3dprinting-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3D 打印指南</font></font></a></li>
<li><a href="#arduplane-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArduPlane</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> 
6.1 </font></font><a href="#arduplane-controlsconfig"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">R/C 控制配置</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
6.2</font></font><a href="#arduplane-connections"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行控制器连接</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
6.3</font></font><a href="#arduplane-parameters"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
6.4</font></font><a href="#arduplane-remarks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">备注</font></font></a></li>
<li><a href="#license-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></a></li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font><a name="user-content-head-description"></a></h2><a id="user-content-description-" class="anchor" aria-label="固定链接：描述" href="#description-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MiniHawk 是一款 3D 打印的垂直起降飞机。它在设计时充分考虑了可打印性，旨在为社区提供一个通用且易于操作的垂直起降试验台，供大家进行实验和调试。该飞行器使用三 (3) 个无刷直流电机作为推进器，前向电机对倾斜，用于前向飞行和偏航控制，后向电机固定，仅用于悬停。四 (4) 个伺服器用于倾斜前向电机并控制机翼的升降副翼控制面。机身为“板式”机翼，中间机身装有航空电子设备和电池，内部导管通向发动机舱和伺服器。双垂直稳定翼提供适度的方向稳定性。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何使用这个 Repo</font></font><a name="user-content-head-usage"></a></h2><a id="user-content-how-to-use-this-repo-" class="anchor" aria-label="永久链接：如何使用这个 Repo" href="#how-to-use-this-repo-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目托管在 GitHub 上，它传统上是一个软件存储库网站，但该格式非常适合 MiniHawk-VTOL 等硬件项目，其中的一些功能非常有用：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个部分文件的历史记录都是可访问的；如果您需要旧版本，只要您“克隆”了存储库，即使离线也可以访问。（请注意，克隆存储库意味着下载数百 MB。）</font></font></li>
<li><a href="https://github.com/StephenCarlson/MiniHawk-VTOL/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">版本和发布版的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布方式与软件项目一样，包括设定里程碑和规划未来发布版，让社区了解下一步计划。发布版是一组压缩版基本文件，放在 zip 存档中，代表项目在设计稳定且值得广泛公开发布时的快照。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://github.com/StephenCarlson/MiniHawk-VTOL/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“问题”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项</font><font style="vertical-align: inherit;">卡允许社区通过提供反馈或贡献来改进设计，从而参与设计的演变。</font></font></li>
<li><font style="vertical-align: inherit;"></font><a href="https://github.com/StephenCarlson/MiniHawk-VTOL/discussions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“讨论”</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选项</font><font style="vertical-align: inherit;">卡是项目交流的另一个位置。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然我已经描述了托管环境，但您不需要创建 GitHub 帐户或参与该项目；而且您很可能只是对下载 STL 和制作飞机感兴趣。以下是您需要做的事情：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点击</font><font style="vertical-align: inherit;">此网页右上角的</font></font><a href="https://github.com/StephenCarlson/MiniHawk-VTOL/releases/latest"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最新版本。这将带您进入最新的稳定设计版本。</font></font></a><font style="vertical-align: inherit;"></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读描述以了解发布中的新内容或值得注意的内容，然后查看 Assets 部分并找到名为 的 .zip 文件</font></font><code>MiniHawk-VTOL-x.x.x.zip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其中“x”是发布版本号。跳过</font></font><code>Source Code</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载，因为这些是由 GitHub 自动生成的，代表项目的全部内容，除非您真的想要全部内容，否则您可能不会对它们感兴趣。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解压存档并检查文件。您正在阅读的 README 的快照包含在 README.md 文件中，并且应该可以用任何文本编辑器打开它。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照下面的</font></font><a href="#buildseq-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建步骤</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">操作。应该可以打印此页面或将其保存为 PDF。如果您精通代码，则这些内容都是用 Markdown 编写的，应该可以在您喜欢的任何文本编辑器或 Markdown 渲染器中呈现。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">备注/常见问题</font></font><a name="user-content-head-faqs"></a></h2><a id="user-content-remarks--faqs-" class="anchor" aria-label="固定链接：备注/常见问题" href="#remarks--faqs-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于这是完全 3D 打印的机身，因此成品飞行器相当重，这是一个缺点，尤其是在悬停飞行模式下。因此，在添加任何额外重量时要小心谨慎。对于标准 PLA 上使用 0.4 毫米喷嘴的推荐打印设置，仅机身重量就略高于 460 克，成品飞行器的总重量在 1000 克到 1200 克之间。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该项目中使用的零件在无人机竞赛和遥控飞机市场上很常见。可以使用标准电机，例如 2207、2306 或类似电机。发动机舱设计规定最大电机钟形直径为 29 毫米，但与要求更严格的先前设计版本相比，这一要求有所放宽。球头螺栓连杆可能是使用最具体的部件，Dubro #181、Dubro #190 甚至 Dubro #367 都是可接受的选项。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">车辆的空气动力学和稳定性仍在分析中，可能会进行修订。用于空气动力学分析的 CFD 姿势/案例已纳入独立研究。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从此设计的第 2 版开始，项目文件以“MH7”为前缀，因为这是 MiniHawk VTOL 设计的第 7 次内部修订。存储库中可能保留了一些旧的“MH5”部件；这些部件来自旧版本。此外，“MH#”前缀是偶然的，不要与 MH 翼型系列混淆，该飞行器使用的是 MH45。通常，“MiniHawk-VTOL”是此设计和任何即将发布的修订的正确名称。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该车辆是在 Autodesk Inventor Professional 2019 中设计的。虽然编译的 STL 以开放访问形式提供，但在撰写本文时，该车辆的实体模型和装配源文件尚未公开；如需获取副本或进一步开发，请联系我。一项小改动：一些零件（如舱口/盖子）的 STEP/STP 版本已包含在社区衍生产品中。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个部件都有一些变体，例如带和不带 NACA 通风口的机头版本。翼尖小翼有“普通”版本或带 GPS 或其他设备的挖孔版本。舱口/盖子有 FPV 变体，支持 Foxeer -Nano 相机外形尺寸（15 毫米宽），并具有 30.5 毫米网格，用于视频发射器，例如 AKK Infinite DVR。所有部件选项和变体都详细说明在下方的</font></font><a href="#build-airframeparts"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">零件树图</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指标</font></font><a name="user-content-head-metrics"></a></h2><a id="user-content-metrics-" class="anchor" aria-label="固定链接：指标" href="#metrics-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">价值</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翼展</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">800毫米</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翼面积</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">15.6分米^2</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">长宽比</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4.1</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翼型（根部和尖端）</font></font></td>
<td><a href="https://www.mh-aerotools.de/airfoils/mh45koo.htm" title="MH45 机翼，马丁·赫普勒拍摄" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">马航 45</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">长度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">520毫米</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">转子间距</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">315 毫米圆</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">锂聚合物电池</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4s，1300-1500毫安时（约160克）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">马达（前）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2207或2306 2300-2600kV</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发动机（后）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2207或2306~2000kV</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伺服器</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HS-65HB/MG 或等同物</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行控制器（尺寸）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">30.50mm 至 16.0mm 网格</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">螺旋桨（前）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5050 至 ~5249</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">螺旋桨（后）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6030 至 ~5249</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全力重量</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1000g 至 ~1200g（含 PLA）</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MiniHawk 构建零件清单和工具</font></font><a name="user-content-build-brief"></a></h1><a id="user-content-minihawk-build-parts-list-and-tools-" class="anchor" aria-label="永久链接：MiniHawk 构建零件清单和工具" href="#minihawk-build-parts-list-and-tools-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推荐的工具和设备</font></font><a name="user-content-build-tools"></a></h2><a id="user-content-recommended-tools-and-equipment-" class="anchor" aria-label="永久链接：推荐的工具和设备" href="#recommended-tools-and-equipment-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">FDM/FFF 3D 打印机，构建体积大于 23.1x210.7x150mm（构建高度为 330mm 或更大将允许将机头和机翼作为单个部件打印，而不是分开打印。）</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">焊接站及电子制作相关工具和材料</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手工工具：钳子、斜口钳、砂纸、美工刀/手术刀、手钻等</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">胶粘剂及耗材：氰基丙烯酸酯胶、热熔胶枪、胶带</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">元件和电子产品</font></font><a name="user-content-build-components"></a></h2><a id="user-content-components-and-electronics-" class="anchor" aria-label="固定链接：元件和电子产品" href="#components-and-electronics-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数量</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">商品描述</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行控制器（3 个电机、4 个伺服输出）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mRo PixRacer Pro、Matek F405-WING 或 F765-WING</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">皮托管、GPS、远程无线电、FPV 摄像头 + VTx 等</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">额外必备航空电子设备</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果飞行控制器中未内置 UBEC，则使用伺服电源。</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Castle Creations 10 安培可调 BEC</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">R/C 接收器，8+ 通道，SBUS 或 PPM 输出</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ESC（4s，40A 或更好）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EMAX Formula 系列 32 位 45A 电调</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2207 或 2306 ~2500KV BLDC 电机 (外径 &lt; 29mm)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">T-Motor VELOX V2 2207 2550Kv（注1）</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2207 或 2306 ~2000KV BLDC 电机</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">T-Motor VELOX V2 2306 1950Kv (注2)</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4s1300 Lipoly（60C 或更高）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RDQ 14.8V 4S 1300mAh 100C</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">XT60 尾纤或同等产品。</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HS-65HB 伺服（或同等产品）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升降舵伺服装置，参见（注 3）。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HS-5065MG 伺服（或同等产品）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电机倾斜伺服器，参见（注 4）。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">碳纤维翼梁，长度&lt;640mm，外径&lt;=6.5mm</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于加强机翼。圆形或方形</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）Du-Bro SKU#118 小型尼龙铰链</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">副翼加强，见（注释 5）。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">M2 或 M3 安装硬件（螺母、螺栓、支架）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于安装飞行控制器、托盘。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6 英寸伺服延长线</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(注6)</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">公对公伺服延长线</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行控制器到接收器 PPM/SBUS 连接。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2-56 链环 U 形夹 (注 7)</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">四 (4) 个伺服臂连接。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2-56 螺纹联动杆，长度&gt;=52mm</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">升降副翼推杆，距螺纹尖端 45 毫米处呈 L 形弯曲。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）Du-Bro SKU#855 E/Z Links 0.72（2-56）夹子</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了固定 L 形弯头，可以用 Z 形弯头代替。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1/16 英寸 2-56 球形连杆和耦合器对</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Dubro #181 或 Dubro #190，参见（注释 8）。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2-56 全螺纹杆，长度=70mm</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">末端 1=(链接 2-56 U 形夹), 末端 2=(2-56 球形连接器)</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2-56 光杆，长度=40mm</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">(注9)</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）3mm 螺栓或轴，长度=44mm</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想在倾斜臂上使用滚珠轴承。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）3x6x2.5mm 滚珠轴承</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">俗称 MR63ZZ，用于倾斜臂支撑。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）WS2812 5050 SMD（或同等可寻址 LED）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用磁线焊接，安装在翼尖。</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">M4 或 M5 支撑螺母</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果需要，请更换默认的螺旋桨螺母</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">50xx 螺旋桨，顺时针旋转</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">左/左舷螺旋桨，5 英寸</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">50xx 螺旋桨，逆时针旋转</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">右舷螺旋桨，5 英寸</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">50xx 或 60xx 螺旋桨，逆时针旋转</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尾部螺旋桨，Dalprop 可折叠 F6 6048 三叶</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尼龙搭扣电池带</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）电池电压监测器/警报蜂鸣器</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果未包括，则用于飞行控制器。</font></font></td>
</tr>
</tbody>
</table>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注 1：前电机的外径不应大于 29 毫米，能够产生 500g 至 800g 的静态推力（全油门），俯仰速度约为 20 米/秒（半油门），螺旋桨为 5 英寸。注 2：尾电机的</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
外径可以达到 30 毫米或更大，能够产生 700g 至 1000g 的静态推力（全油门），螺旋桨最大为 6 英寸。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
注 3：伺服托架设计用于宽度不超过 26 毫米的伺服器，从安装片底部到伺服器底部为 17.5 毫米，从输出轴顶部到伺服器底部为 32 毫米，厚度为 12 毫米。应该适合大多数“亚微型”伺服器。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
注 4：口袋尺寸与上述相同，但这些将被严重滥用，必须相当坚固。或者只是指望大量剥离非金属齿轮伺服器。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
注 5：可以省略，但 3D 打印的升降副翼上的活动铰链最终会失效，需要适当修补。Dubro #118 每包 6 个，Dubro #119 每包 15 个。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
注 6：或者，切断伺服电缆并焊接电缆的直线延长线以连接到飞行控制器，并留出一些松弛部分。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
注 7：U 形夹和杆可以成套购买，例如 Du-Bro #185，这是一套 5 根杆，已连接好 U 形夹。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
注 8：球形连杆螺纹尺寸应为 1/16 英寸/62.5 密耳/1.59 毫米。这种零件更受欢迎的变体有一个 2-56（86 密耳）螺纹尺寸的球，它有点大，但应该可以适应发动机舱倾斜安装部件。如果您只能订购公制硬件，2 毫米螺纹尺寸应该没问题。请注意，这是球形连杆螺柱螺纹尺寸；球形连杆螺柱连接到球形连杆座/耦合器，该球形连杆座/耦合器可捕获螺纹杆，然后连接到伺服臂。伺服臂和球形连杆座/耦合器之间的连接杆可以是任何尺寸，但此处假定为 2-56。注 9：直径=[1.83mm 至 1.87mm]，由 2-56 伺服推杆的备用件制成。使用无螺纹光滑杆，仅将一端稍微粗糙/滚花，以便压入机舱。</font></font></p>
</blockquote>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机身部件</font></font><a name="user-content-build-airframeparts"></a></h2><a id="user-content-airframe-parts-" class="anchor" aria-label="永久链接：机身部件" href="#airframe-parts-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>MiniHawk-VTOL Version 2.1 Aircraft
|-- Fuselage/Body  
|   |-- Empennage/Tail
|   |   |-- Print Option 1: As a Single Part - No Split, but layers are not aligned for max. strength
|   |   |   |-- MH7_Empennage-Full.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts with print layers aligned for strength
|   |       |-- Print Option 2a: Explicit Print Supports
|   |       |   |-- MH7_Empennage-PrintSupports.stl
|   |       |
|   |       |-- Print Option 2b: No Explicit Print Supports, plain part
|   |           |-- MH7_Empennage.stl
|   |
|   |-- Nose
|   |   |-- Print Option 1: Full Nose - No Split
|   |   |   |-- MH7_Nose.stl
|   |   |
|   |   |-- Print Option 2: Nose in Two Pieces
|   |       |-- MH7_Nose_A.stl
|   |       |-- MH7_Nose_B.stl
|   |
|   |-- Avionics (Flight Controller) Tray
|   |   |-- Part Variant: Solid Tray, No Vibration Dampening
|   |   |   |-- MH7_AvionicsTray.stl
|   |   |
|   |   |-- Part Variant: Leaf-Spring Compliant-Mechanism Vibration-Dampening Version
|   |       |-- MH7_AvionicsTray2.stl
|   |
|   |-- Battery Tray
|       |-- MH7_BatteryTray.stl
|
|-- Hatch/Lid
|   |-- Part Variant: FPV 16mm-sized Camera and VTx Support
|   |   |-- Print Option 1: Long-axis Symmetric Half (TODO: Needs to be restored to -Full)
|   |   |   |-- MH7_Hatch-FPV-16mm.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for nicer print
|   |       |-- MH7_Hatch-FPV-16mm_a.stl
|   |       |-- MH7_Hatch-FPV-16mm_b.stl
|   |
|   |-- Part Variant: Vented with NACA Duct
|   |   |-- Print Option 1: Entire thing, split it yourself
|   |   |   |-- MH7_Hatch-Vented.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for nicer print
|   |       |-- MH7_Hatch-Vented_a.stl
|   |       |-- MH7_Hatch-Vented_b.stl
|   |
|   |-- Locking Latch Mechanism
|       |-- MH7_Hatch_LockingLatch.stl
|       |-- 1.85mm Steel Pin, Length=30mm
|
|-- Left Wing  
|   |-- Part Variant: Plain Wing
|   |   |-- Print Option 1: Entire wing
|   |   |   |-- MH7_WingLeft.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for smaller printers
|   |       |-- MH7_WingLeft_A.stl
|   |       |-- MH7_WingLeft_B.stl
|   |
|   |-- Part Variant: Solar Wing
|   |   |-- Print Option 1: Entire wing
|   |   |   |-- MH7_WingLeft-Solar.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for smaller printers
|   |       |-- MH7_WingLeft_A.stl
|   |       |-- MH7_WingLeft_B.stl
|   |
|   |-- Elevon Control Horn
|       |-- MH7_ControlHorn.stl
|
|-- Left Fin  
|   |-- MH7_FinLeft_Lower.stl  
|   |-- MH7_FinLeft_Upper.stl  
|
|-- Left Nacelle
|   |-- Part Variant: Ball Bearing Version
|   |   |-- MH7_Nacelle_A-Bearing.stl
|   |   |-- MH7_Nacelle_B-Bearing.stl
|   |
|   |-- Part Variant: Non-Ball Bearing Version
|   |   |-- MH7_Nacelle_A-NoBearing.stl
|   |   |-- MH7_Nacelle_B-NoBearing.stl
|   |
|   |-- Motor Tilt-Mount
|       |-- Part Variant: Ball Bearing Version
|       |   |-- MH7_TiltMount_A-Bearing.stl
|       |   |-- 3mm Shaft or Threaded Bolt, Length=44mm
|       |
|       |-- Part Variant: Non-Ball Bearing Version
|       |   |-- MH7_TiltMount_A-NoBearing.stl
|       |   |-- 1.85mm Steel Pin, Length=40mm
|       |
|       |-- MH7_TiltMount_B.stl
|       |-- BLDC Motor
|    
|-- Left Winglet
|   |-- Part Variant: Plain Winglet
|   |   |-- MH7_WingletLeft.stl
|   |
|   |-- Part Variant: GPS Pocket
|       |-- MH7_WingletLeft-GPS.stl
|
|-- Right {Wing, Fin, Nacelle, Motor Tilt-Mount, Winglet} 
|   |-- For each of the symmetric parts, to create the right-side version, simply mirror the part in your slicer software. 
        Be _very careful_ please! Be sure you understand how all the parts go together, particularly the Nacelle pieces: 
        The nacelle _A piece is always near the aircraft center body, with the _B piece on the outboard side, aligned with 
        the servos and away from the center body. You should print four unique Nacelle pieces, with no two alike: 
        Two non-mirrored pieces of _A and _B, and two mirrored pieces of _A and _B.

Supporting Devices and Parts
|-- Weight &amp; Balance Jackpoint Stand
|   |-- Nacelle-Support Beam
|   |   |-- MH7_WeightBalanceStand_Beam.stl
|   |   |-- MH7_WeightBalanceStand_Support.stl
|   |   |-- Two 1.85mm Steel Pins, Length=50mm each
|   |
|   |-- Empennage-Support Jack
|       |-- MH7_WeightBalanceStand_Foot.stl
|       |-- MH7_WeightBalanceStand_Support.stl (After gluing, bend the legs with hot water to form a triangle stance)
|       |-- 1.85mm Steel Pin, Length=50mm
|
|-- STEP/STP Version of the Hatch/Lid for Community Mods
    |-- MH7_Hatch_RELEASED.stp
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="MiniHawk-VTOL Version 2.1 Aircraft
|-- Fuselage/Body  
|   |-- Empennage/Tail
|   |   |-- Print Option 1: As a Single Part - No Split, but layers are not aligned for max. strength
|   |   |   |-- MH7_Empennage-Full.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts with print layers aligned for strength
|   |       |-- Print Option 2a: Explicit Print Supports
|   |       |   |-- MH7_Empennage-PrintSupports.stl
|   |       |
|   |       |-- Print Option 2b: No Explicit Print Supports, plain part
|   |           |-- MH7_Empennage.stl
|   |
|   |-- Nose
|   |   |-- Print Option 1: Full Nose - No Split
|   |   |   |-- MH7_Nose.stl
|   |   |
|   |   |-- Print Option 2: Nose in Two Pieces
|   |       |-- MH7_Nose_A.stl
|   |       |-- MH7_Nose_B.stl
|   |
|   |-- Avionics (Flight Controller) Tray
|   |   |-- Part Variant: Solid Tray, No Vibration Dampening
|   |   |   |-- MH7_AvionicsTray.stl
|   |   |
|   |   |-- Part Variant: Leaf-Spring Compliant-Mechanism Vibration-Dampening Version
|   |       |-- MH7_AvionicsTray2.stl
|   |
|   |-- Battery Tray
|       |-- MH7_BatteryTray.stl
|
|-- Hatch/Lid
|   |-- Part Variant: FPV 16mm-sized Camera and VTx Support
|   |   |-- Print Option 1: Long-axis Symmetric Half (TODO: Needs to be restored to -Full)
|   |   |   |-- MH7_Hatch-FPV-16mm.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for nicer print
|   |       |-- MH7_Hatch-FPV-16mm_a.stl
|   |       |-- MH7_Hatch-FPV-16mm_b.stl
|   |
|   |-- Part Variant: Vented with NACA Duct
|   |   |-- Print Option 1: Entire thing, split it yourself
|   |   |   |-- MH7_Hatch-Vented.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for nicer print
|   |       |-- MH7_Hatch-Vented_a.stl
|   |       |-- MH7_Hatch-Vented_b.stl
|   |
|   |-- Locking Latch Mechanism
|       |-- MH7_Hatch_LockingLatch.stl
|       |-- 1.85mm Steel Pin, Length=30mm
|
|-- Left Wing  
|   |-- Part Variant: Plain Wing
|   |   |-- Print Option 1: Entire wing
|   |   |   |-- MH7_WingLeft.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for smaller printers
|   |       |-- MH7_WingLeft_A.stl
|   |       |-- MH7_WingLeft_B.stl
|   |
|   |-- Part Variant: Solar Wing
|   |   |-- Print Option 1: Entire wing
|   |   |   |-- MH7_WingLeft-Solar.stl
|   |   |
|   |   |-- Print Option 2: Split into Two Parts for smaller printers
|   |       |-- MH7_WingLeft_A.stl
|   |       |-- MH7_WingLeft_B.stl
|   |
|   |-- Elevon Control Horn
|       |-- MH7_ControlHorn.stl
|
|-- Left Fin  
|   |-- MH7_FinLeft_Lower.stl  
|   |-- MH7_FinLeft_Upper.stl  
|
|-- Left Nacelle
|   |-- Part Variant: Ball Bearing Version
|   |   |-- MH7_Nacelle_A-Bearing.stl
|   |   |-- MH7_Nacelle_B-Bearing.stl
|   |
|   |-- Part Variant: Non-Ball Bearing Version
|   |   |-- MH7_Nacelle_A-NoBearing.stl
|   |   |-- MH7_Nacelle_B-NoBearing.stl
|   |
|   |-- Motor Tilt-Mount
|       |-- Part Variant: Ball Bearing Version
|       |   |-- MH7_TiltMount_A-Bearing.stl
|       |   |-- 3mm Shaft or Threaded Bolt, Length=44mm
|       |
|       |-- Part Variant: Non-Ball Bearing Version
|       |   |-- MH7_TiltMount_A-NoBearing.stl
|       |   |-- 1.85mm Steel Pin, Length=40mm
|       |
|       |-- MH7_TiltMount_B.stl
|       |-- BLDC Motor
|    
|-- Left Winglet
|   |-- Part Variant: Plain Winglet
|   |   |-- MH7_WingletLeft.stl
|   |
|   |-- Part Variant: GPS Pocket
|       |-- MH7_WingletLeft-GPS.stl
|
|-- Right {Wing, Fin, Nacelle, Motor Tilt-Mount, Winglet} 
|   |-- For each of the symmetric parts, to create the right-side version, simply mirror the part in your slicer software. 
        Be _very careful_ please! Be sure you understand how all the parts go together, particularly the Nacelle pieces: 
        The nacelle _A piece is always near the aircraft center body, with the _B piece on the outboard side, aligned with 
        the servos and away from the center body. You should print four unique Nacelle pieces, with no two alike: 
        Two non-mirrored pieces of _A and _B, and two mirrored pieces of _A and _B.

Supporting Devices and Parts
|-- Weight &amp; Balance Jackpoint Stand
|   |-- Nacelle-Support Beam
|   |   |-- MH7_WeightBalanceStand_Beam.stl
|   |   |-- MH7_WeightBalanceStand_Support.stl
|   |   |-- Two 1.85mm Steel Pins, Length=50mm each
|   |
|   |-- Empennage-Support Jack
|       |-- MH7_WeightBalanceStand_Foot.stl
|       |-- MH7_WeightBalanceStand_Support.stl (After gluing, bend the legs with hot water to form a triangle stance)
|       |-- 1.85mm Steel Pin, Length=50mm
|
|-- STEP/STP Version of the Hatch/Lid for Community Mods
    |-- MH7_Hatch_RELEASED.stp" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建序列</font></font><a name="user-content-buildseq-brief"></a></h1><a id="user-content-build-sequence-" class="anchor" aria-label="永久链接：构建序列" href="#build-sequence-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下说明假设已打印了整套机身部件，如上文所述。有关</font><font style="vertical-align: inherit;">每个部件的典型切片机设置的详细信息，请参阅</font></font><a href="#3dprinting-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3D 打印指南部分。此外，3MF 生产文件可在</font></font></a><font style="vertical-align: inherit;"></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/3mf-Implementations"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3mf-Implementations</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> repo 文件夹中找到，但打印设置是否正确传输到您的特定打印机则有点冒险。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 1 部分 - 机身结构和发动机支架/倾斜附件</font></font><a name="user-content-buildseq-part1"></a></h2><a id="user-content-part-1---airframe-structures-and-motor-mounttilt-attachment-" class="anchor" aria-label="永久链接：第 1 部分 - 机身结构和发动机支架/倾斜附件" href="#part-1---airframe-structures-and-motor-mounttilt-attachment-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">清洁所有 3D 打印部件，移除所有边缘/支撑材料。去除所有毛刺或瑕疵。对于每个机翼，小心地雕刻掉铰链加固孔中的任何拉丝或过度挤压，以便铰链销钉可以安装。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-1.png" title="图 1 - 铰链销间隙"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 1</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">皮托管轴和其他小部件也可能有拉丝，应将其移除。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果需要，小心地切开升降副翼（</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告！</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">只在两端切开槽以允许表面偏转，不要切掉整个升降副翼）。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-2.png" title="图 2 - 副翼运动切入"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 2</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻轻地上下运动每个表面，直到活动铰链建立。最好的开始方式是使用坚固的平面物体向下弯曲升降副翼（好像机头向下俯仰），以均匀分布控制表面上的压力。只做您感觉舒适的程度，然后反方向。继续轻轻运动铰链，直到它移动 +/- 30 度。如果您使用 PLA 或其他加工硬化材料打印，请不要继续循环铰链，直到安装了加固胶带或扣件；只有这样，铰链才能进一步磨合，直到它可以顺畅移动。</font></font></p>
</li>
</ol>


<table>
  <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-1.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-1.png" alt="图1" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 1. 铰链销间隙</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-2.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-2.png" alt="图 2" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 2. 升降副翼运动切入</font></font></td>
  </tr>
</tbody></table> 
<ol start="3" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用薄/中等氰基丙烯酸酯将顶篷/舱盖各部分粘合在一起，然后放在一边固化。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-3.png" title="图 3 - 舱口/盖子粘合"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 3</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用氰基丙烯酸酯将尾翼两半粘合在一起。（如果您打印的是全单件版本，请跳过此步骤。）放在一边固化。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-4.png" title="图 4-尾翼两半粘合"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 4</font></font></a></p>
</li>
</ol>
<table>
  <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-3.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-3.png" alt="图 3" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 3. 舱口/盖子粘合</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-4.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-4.png" alt="图 4" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 4. 尾翼两半粘合</font></font></td>
  </tr>
</tbody></table> 
<ol start="5" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将控制喇叭部件压入升降副翼以测试配合度。控制喇叭从顶部插入，穿过升降副翼，孔位于铰链线下方的中心，与升降副翼伺服连杆成一线。部件应与升降副翼顶面齐平，大约高出表面 0.5 毫米。配合应紧密，但不要用力过猛地压入控制喇叭，否则可能会分裂打印层并造成损坏。如果太紧，请小心地从升降副翼的插槽中雕刻掉任何毛刺或过度挤压，或将控制喇叭打磨得更薄。使用氰基丙烯酸酯将控制喇叭部件 (2) 粘合到每个升降副翼（左翼和右翼）中。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-5.png" title="图 5-升降副翼控制喇叭安装"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 5</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 Du-Bro 尼龙迷你铰链件（每机翼 3 个，Du-Bro SKU#118）粘到每个升降副翼铰链的凹槽中。热熔胶或氰基丙烯酸酯应该有效。3M™ Transpore™ 医用胶带也是一种可行的铰链加固解决方案，可以现在使用，也可以在构建过程中稍后使用。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻轻打磨粘合的尾翼/尾部接口表面，直至光滑平整/齐平。对机身/机头进行试装，以确认接头正确齐平，然后使用氰基丙烯酸酯粘合到机身/机头。放在一边固化。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-6.png" title="图 6-尾翼/尾部附件"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 6</font></font></a></p>
</li>
</ol>
<table>
  <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-5.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-5.png" alt="图 5" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 5. 升降舵控制喇叭安装（从顶部插入插槽）</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-6.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-6.png" alt="图 6" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 6. 尾翼/尾部附件</font></font></td>
  </tr>
</tbody></table> 
<ol start="8" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将发动机舱对的两半粘合在一起；</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这里要小心！</font></font></strong><font style="vertical-align: inherit;"></font><code>_A</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个发动机舱由一个和一块</font><font style="vertical-align: inherit;">组成</font></font><code>_B</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。总共应该有四个发动机舱部件，每个部件都是独一无二的：一个</font></font><code>_A</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>_B</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是非镜像的，一个</font></font><code>_A</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>_B</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是镜像的。没有</font></font><code>_A</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于螺柱臂的切口，而有</font></font><code>_B</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。这些</font></font><code>_A</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部件始终最靠近飞机的中心机身，并且这些</font></font><code>_B</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部件始终在外侧与伺服器对齐。使用氰基丙烯酸酯尽可能小心和精确地将各部件粘合在一起。放在一边固化。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-7.png" title="图 7-发动机舱两半粘接"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 7</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">轻轻打磨已完成的机身/机身上的两个翼根接口表面，直到平齐光滑。试装碳纤维翼梁，并确认其没有被任一机翼的翼梁轴上的任何瑕疵所阻碍。如果有瑕疵，请发挥创造力；通常用力戳一下翼梁就可以清除瑕疵，而不会损坏 3D 打印的轴。如果翼梁没有完全填满翼梁轴（内径 7 毫米），例如碳翼梁是 5 毫米圆管，则临时制作垫片或其他填充物以使配合紧密，例如用胶带包裹翼梁的两端和靠近中心的位置，以便翼梁进入中央机身腔。在翼梁存在以提供对齐的情况下，将两个机翼试装到各自的表面上，以确认接头正确平齐。将翼梁置于中心，使其均等地延伸到左右机翼。 （640 毫米是支撑的最长翼梁长度。较短的翼梁也可以，只要它居中即可。）拆下机翼。此时，如果需要，可以将翼梁粘合到机身上。（如果您计划以后重复使用翼梁，则可以不使用任何粘合剂安装翼梁，例如如果飞机报废但翼梁幸存下来。）使用氰基丙烯酸酯将左翼或右翼粘合到机身（不建议同时连接两者）。放在一边固化。当第一个机翼固化后，粘合第二个机翼并放在一边固化。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-8.png" title="图 8 - 翼部附件"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 8</font></font></a></p>
</li>
</ol>
<table>
  <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-7.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-7.png" alt="图 7" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 7. 发动机舱两半粘接</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-8.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-8.png" alt="图 8" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 8. 机翼附件</font></font></td>
  </tr>
</tbody></table> 
<ol start="10" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将每个发动机支架（倾斜支架/吊舱）与其各自的完整机舱进行试装。根据需要打磨或修整，使发动机支架能够完全向前倾斜，并能够向上倾斜超过 90 度。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-9.png" title="图 9 - 机舱口袋精加工"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 9</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（机舱非滚珠轴承版本）对于每个机舱，其各自的电机支架对齐并存在，使用 1.58 毫米（1/16 英寸，62.5 密耳）钻头进行铰孔（钻孔至尺寸）。 （应为要安装的铰链杆直径的 85% 至 90%。在这种情况下，铰链杆直径为 1.84 毫米或 72 密耳。）将电机支架和机舱放在一起。通过使用磨床或砂轮磨尖，将一段铰链杆调整为最终精密铰孔工具。使用这种临时铰孔工具将每个机舱支架对中的孔铰孔至最终直径 1.84 毫米（72 密耳）。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-10.png" title="图 10 - 轴孔和螺栓孔铰孔"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 10</font></font></a></p>
</li>
</ol>
<table>
  <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-9.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-9.png" alt="图 9" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 9. 发动机舱口袋精加工</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-10.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-10.png" alt="图 10" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 10. 轴孔和螺栓孔铰孔</font></font></td>
  </tr>
</tbody></table> 
<ol start="12" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（机舱滚珠轴承版本）参考上述非滚珠轴承机舱设计步骤，但使用 3.00 毫米（7/64 英寸，118 密耳）钻头来铰轴。机械摩擦关系是颠倒的，电机倾斜安装与插入轴具有强摩擦配合，机舱叉/臂中的滚珠轴承提供平滑的旋转界面。将滚珠轴承压入凹槽，仅在适当的情况下使用轻微加热。即兴设计一个轴固定解决方案，该解决方案还可以固定轴承并防止任一轴承脱落。避免即兴设计一种在机舱“叉”上进行压缩的解决方案，因为这会导致束缚和摩擦。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（机舱非滚珠轴承版本）从各自的机舱中取出每个电机支架，并仅将电机支架孔扩孔至下一个更大的钻头尺寸，但不得超过铰链杆直径的 107%。这样可以使外机舱臂与金属轴有摩擦配合，而内电机支架能够平稳旋转，塑料与金属之间。太大会导致过度游动和可能的咔嗒声；太小会导致卡住。1.95 毫米（77 密耳，5/64 英寸）对于 1.84 毫米直径的铰链杆来说是可以接受的。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（机舱非滚珠轴承版本）切割铰链杆件，长度不超过 40 毫米。如果需要，将一端或两端打毛/滚花。通过相应的电机支架将每个铰链杆压入每个机舱。验证每个电机支架是否可以自由旋转，并且铰链间隙最小。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于每个电机支架，如果您使用推荐的 1/16 球头螺栓，请将电机支架连杆支架孔扩孔至 1.19 毫米（3/64 英寸，47 密耳）。这可能会扩孔以适应更大的球头螺栓螺纹尺寸，例如 2-56（1.84 毫米，72 密耳），在这种情况下请谨慎判断。扩孔应约为要安装的螺纹球连杆大直径的 80%。将螺纹球连杆安装到连杆支架孔中。电机支架可承受高达 8 毫米的螺纹球头螺栓深度。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将每个发动机舱粘合到各自的机翼上；注意球形连杆应与各自的伺服连杆槽/孔对齐。氰基丙烯酸酯在 PLA 上效果很好，但由于这是飞机上承重较高的结构之一，因此环氧树脂也是候选材料。在胶水固化时，验证对齐情况并调整/调整位置。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-11.png" title="图 11 - 机舱附件"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 11</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将垂直尾翼的下部和上部粘合在一起。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-13.png" title="图 13 - 船底板连接"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 13</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（下部有时称为“翼板”。）将两个垂直尾翼粘合到各自的机翼上。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-12.png" title="图 12 - 垂直稳定器附件"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 12</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">氰基丙烯酸酯应该足够了。</font></font></p>
</li>
</ol>
<table>
  <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-11.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-11.png" alt="图 11" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 11. 发动机舱附件</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-12.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-12.png" alt="图 12" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 12.垂直稳定器附件</font></font></td>
  </tr>
  <tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-13.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-13.png" alt="图 13" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 13. 船底板附件</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-14.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-14.png" alt="图 14" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 14. 连杆和运动</font></font></td>
  </tr>
</tbody></table> 
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 2 部分 - 连杆和部件安装</font></font><a name="user-content-buildseq-part2"></a></h2><a id="user-content-part-2---linkages-and-component-mounting-" class="anchor" aria-label="永久链接：第 2 部分 - 连杆和组件安装" href="#part-2---linkages-and-component-mounting-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将前两个电机安装在各自的电机支架上。电机引线可能有热缩管，可能会干扰或束缚电线；如有必要，请重新加工。使用每个电机应随附的 M3 螺纹螺栓套件安装电机。注意不要让任何安装螺栓过度伸入电机电枢/定子。确认每个电机都能自由转动并固定牢固。将电线穿过机翼并进入主舱，并测试当电机支架在前倾和悬停倾斜位置之间俯仰时电线的伸缩行为。对于每个电机，连接每个电机应随附的螺旋桨轮毂硬件套件，以便它可以驱动标准的 5 英寸螺旋桨。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后置电机应使用电机附带的 M3 螺纹螺栓安装到尾部。根据需要将电机电线穿过任一电线管道通道到主舱。（首选/传统通道是左/左舷管道，保留右/右舷通道用于天线和 LED 接线。）验证电机是否自由旋转且固定良好。连接应随电机提供的螺旋桨轮毂硬件套件，以便它可以驱动标准的 6 英寸螺旋桨。验证螺旋桨是否清除垂直稳定翼，并根据需要修剪尖端，或向下选择 5 英寸螺旋桨。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电机支架倾斜伺服器应在标准 RC PWM 信号上进行测试和居中，脉冲宽度为 1000us、1500us 和 2000us。连接一个孔到中心间距为 19.3mm（0.76 英寸）的伺服臂。这个值很关键，因为倾斜前电机支架的联动行为无法轻易修改，任何小于这个值的长度都会导致电机倾斜达不到悬停和反扭矩（偏航）控制所需的角度。比这个长度更长的臂将无法装入联动槽/槽中。无论安装的臂尽可能接近 19.3mm，测试伺服器是否适合伺服槽，并验证在 1000us 和 2000us 脉冲宽度之间，臂是否舒适地缩回槽/槽中，并从该点完全扫描约 90 到 95 度。验证最佳伺服臂花键位置，并用螺栓将臂固定到位。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-14.png" title="图 14 - 连杆和运动"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图-14</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于每个升降舵伺服器，重复上述相同的步骤，但伺服臂的孔到中心距离约为 9.5 毫米（3/8 英寸）。此长度可以稍长或稍短，效果是增加或减少升降舵控制行程。对于具有奇数花键齿数的伺服器（例如 Hitec HS-65HB 的 B1 花键有 25 个齿），为了获得最居中和对称的解决方案，将伺服器置于 1500us 脉冲宽度的中心，并在每个 90 度位置之间交替连接 4 臂输出喇叭，以找到最正交/居中的位置，然后切断 3 个不需要的臂。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确认连接到伺服臂的连杆夹能够自由连接和旋转。可能需要铰孔每个伺服臂，铰孔值通常为 1.59 毫米（1/16 英寸，62 密耳）。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将伺服线穿过每个机翼底部的导管通道，到达主舱。假设所有伺服都有 6 英寸（约 150 毫米）的尾纤，Elevon 伺服会有些松弛，但倾斜伺服会刚好到达主舱。可以添加伺服延长线，或者用一段 3 线伺服导线/电缆延长伺服尾纤，或者可以丢弃 3 针伺服连接器，以便以后直接焊接（如果需要）。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">伺服线束以某种形式完成之后，使用热熔胶将伺服器粘合到机身。请注意，根据所用的打印材料，机身可能会在粘合位置出现变形或熔化。（这被认为是一种安装伺服器的一些糟糕方法，将来可能会修改。抱歉。）验证伺服器是否可以产生最大扭矩而不会脱离机身。还请注意，在伺服器安装中可以探索替代方案，例如双面胶带，但不建议使用氰基丙烯酸酯或环氧树脂。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过在所用的 2-56 连杆对的螺纹尖端处创建一个 45 毫米的 L 形弯头来形成升降副翼控制杆。测试安装固定 Du-Bro E/Z Links 0.72 (2-56) 固定夹，并根据需要修改弯头并将其切割平齐。或者，可以形成传统的 Z 形弯头以根据需要取消固定夹。对于每个升降副翼，将其控制杆连接到升降副翼控制臂，并将 U 形夹连接到相应的伺服臂。拆卸、转动 U 形夹，并根据需要重新连接，直到升降副翼齐平，同时伺服器位于 1500us 的中心。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从全螺纹 2-56 杆上切下两 (2) 个 70 毫米长的部件，以形成倾斜控制杆对。（请勿将这些杆 L 形弯曲或 Z 形弯曲。）使用砂轮或砂纸将切割端软化，以便它们可以轻松拧入尼龙球形连杆耦合器。将球形连杆耦合器和连杆 U 形夹拧上，并将其分别连接到各自的伺服臂或球形连杆头。根据需要拆卸-转动-重新连接，例如当伺服尽可能接近上止点（臂缩回井/槽）时，没有卡住或干扰，同时倾斜电机支架牢固地向前并压在机舱上。如前所述，U 形夹应连接到伺服臂上最高的孔，距离臂 19.3 毫米。可能需要稍微弯曲此杆，以使伺服臂完全缩回，而不会让 U 形夹撞击臂。如果电机支架缩回时伺服过度拉伸，请进行相应调整。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告！</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果伺服在 U 形夹与伺服臂绑定时拉伸，伺服可能会发生故障，伺服 H 桥驱动器或伺服电机可能会烧坏。请小心并善待伺服。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上述步骤假设伺服器在最终安装时已通电并已受控，但为了完整起见，此步骤将验证伺服器是否能够启动且未受压。对于每个伺服器，访问 1000us-1500us-2000us 并观察升降副翼或电机支架上的偏转，并验证是否存在过度的束缚或压力。对于每个电机支架，通过向前轻轻拉动电机（约 300 克力）模拟前飞期间表现出的负载，同时主动命令伺服器在前飞和悬停之间倾斜。运动应平稳且无冻结/停止行为。升降副翼应在控制表面轻负载的情况下启动全范围。</font></font></p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 3 部分 - 电子设备和最终配置</font></font><a name="user-content-buildseq-part3"></a></h2><a id="user-content-part-3---electronics-and-final-configuration-" class="anchor" aria-label="永久链接：第 3 部分 - 电子设备和最终配置" href="#part-3---electronics-and-final-configuration-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据需要焊接飞行控制器。这通常意味着焊接针头以连接来自伺服器和 ESC 的 3 针伺服连接器。焊接电池连接导线（XT60 或根据需要）。为飞行控制器供电并验证其是否正确启动和通信。默认（可能是多旋翼）固件对于接下来的几个步骤来说没问题；请注意，在配置飞行控制器输出之前，伺服器</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不应</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">连接到飞行控制器。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将电池和飞行控制器托盘粘合到主托架中。这可以使用 M3 硬件和充足的热熔胶以及一些铰孔（如果需要）来完成。电池托盘可以永久安装，但保留一些拆卸飞行控制器托盘的能力，因为安装/拆卸飞行控制器需要接触到该托盘的底部。另请注意：如果使用</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/stl-SourceFiles/MH7_ControllerTray2.stl"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“板簧”飞行控制器托盘</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，则应在安装飞行控制器的下侧附上约 30g 至 40g 的压载重量。自粘铅重物效果很好。压载物的原因是将振动传递函数的转角频率驱动到远低于 20 Hz 左右。还请注意，如果按原样使用，柔性“板簧”机制可以表现出谐波振动模式，并且可能需要即兴制作粘弹性阻尼解决方案，例如通过在之字形的折叠之间注入热熔胶。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将 BLDC 电机引线焊接到各个 ESC，或使用子弹连接器或其他所需方式。将 ESC 电源连接直接焊接到飞行控制器的配电区域，或根据需要焊接到中间连接。从电机上拆下螺旋桨。小心地打开飞行控制器的电源，例如使用“烟雾塞”或限流电源，并验证电源系统是否正确接线。对 ESC 进行编程以获得正确的旋转方向：左舷/左侧电机为顺时针 (CW)，右舷/右侧电机为逆时针 (CCW)。（如果使用 BLHeli Passthru 模式对 ESC 进行编程，则 ESC 可以连接到飞行控制器上的任何输出。）后置电机在技术上可以是任意方向，但我</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">强烈</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建议逆时针 (CCW)。这是一种自紧配置，因此在正常运行中不太可能自行松开。这也允许大多数非多旋翼螺旋桨选项（大多数螺旋桨是 CCW），并强制采用一致的传统，允许将来对称共享 PID 配置文件和控制方案。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-15.png" title="图 15 - 螺旋桨旋转方向"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 15</font></font></a></p>
</li>
</ol>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于螺旋桨旋转方向的简要说明：前部电机具有上述顺时针和逆时针方向的原因在于，当飞行器向前飞行并立即被命令悬停时，前进叶片尽可能远离横梁（朝向翼尖），而后退叶片更靠近主体。这应该允许在过渡期间更好地控制滚转，并且通过在此条件下将每个转子的有效升力中心放置得稍微宽一些，任何 PID 控制作用都更有可能保持受限并被稍长的力臂稍微减弱。这也遵循了四旋翼飞行器的典型配置，其前部前进叶片也放置在弧的外侧。</font></font></p>
</blockquote>
<ol start="4" dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此时，使用任何特定固件或与控制 Tricopter VTOL 固定翼飞行器相关的设置配置飞行控制器。请参阅下面的</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/arduplane-brief"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArduPlane 设置</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。将伺服和 ESC 接头连接到其所需的引脚。安装 R/C 接收器并根据需要连接到飞行控制器。将飞行控制器安装到其托盘上，并将托盘固定在主托架内。为飞行器供电并验证飞行控制器方向是否正确，伺服器是否正确控制，以及控制面力是否在正确的方向上。在飞行控制器配置器（ArduPilot Mission Planner 或同等软件）中根据需要反转和微调伺服输出。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（可选）WS2812 LED 可以安装在每个翼尖上，前提是每个都是 SMD5050 或更小的封装，并将电线直接焊接到封装焊盘上，然后安装在每个翼尖的灯井中。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用胶带或双面胶垫将 ESC 存放到主舱侧壁。存放多余的电线，并清理主舱内部。使用 Velcro 带、胶带或其他措施固定电池。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将螺旋桨重新安装到各自的电机上。检查旋转方向是否正确，如上文步骤 3 和</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-15.png" title="图 15 - 螺旋桨旋转方向"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 15</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中所述。如果需要避免接触垂直尾翼，后螺旋桨的尖端应该稍微修剪一下。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞机的重心应位于机翼前缘后方 28 毫米处。这比近端托盘安装孔前方 2 毫米。机翼底部靠近机头的“靶心”触觉凸起的中心位于 28 毫米处。这是一个重要的指标，重心可能仅从此点向后移动最多 2 毫米或 3 毫米，但会增加稳定性风险。飞机将无法在重心向后约 33 毫米的情况下静态稳定飞行，因为中性点位于此点附近。重心应位于机翼前缘后方 26 毫米至 30 毫米之间。使用重量和平衡支架和电子秤，详情如下：</font></font><a href="https://github.com/StephenCarlson/MiniHawk-VTOL/issues/12#issuecomment-828814266" data-hovercard-type="issue" data-hovercard-url="/StephenCarlson/MiniHawk-VTOL/issues/12/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">问题 #12</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于此飞行器既是固定翼飞行器又是多旋翼飞行器，因此此处所述的重心适用于固定翼飞行器，任何重心测量都应在发动机倾斜到前飞状态、螺旋桨安装好且盖子固定的情况下进行。将电池向前或向后移动以达到适当的平衡，或者在必要时在机头尖端内添加压舱物。</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-16.png" title="图 16 - 质心"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图 16</font></font></a></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">采取任何其他必要措施，使飞行器做好飞行准备。贴花、油漆或热激活覆盖物都是可行的。飞行器重量应达到约 1000 克至 1200 克，如果使用标准 PLA 打印，3D 打印机身本身的重量约为 460 克。</font></font></p>
</li>
</ol>
<table>
  <tbody><tr>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-15.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-15.png" alt="图 15" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 15.螺旋桨旋转方向</font></font></td>
    <td>
      <a target="_blank" rel="noopener noreferrer" href="/StephenCarlson/MiniHawk-VTOL/blob/master/doc-Documentation/Figure-16.png"><img src="/StephenCarlson/MiniHawk-VTOL/raw/master/doc-Documentation/Figure-16.png" alt="图 16" height="240" width="auto" style="max-width: 100%;"></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
      图 16. 质心</font></font></td>
  </tr>
</tbody></table> 
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行测试</font></font><a name="user-content-flight-brief"></a></h1><a id="user-content-flight-testing-" class="anchor" aria-label="永久链接：飞行测试" href="#flight-testing-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对该飞行器进行飞行调试的全新方法大致遵循以下步骤：</font></font></p>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">探索悬停飞行 PID。这可以使用试验台设置和滚转、俯仰和偏航的轴隔离来完成。悬停到前飞和反向转换的增益调度也可以通过俯仰隔离配置进行，但对于接近前飞的角度而没有等效相对风力发电的情况，相关性会降低。（ArduPlane 本质上会进行这种计算，将 VTOL 实现到其他飞行堆栈可能需要开发增益调度表。）</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">继续进行 PID 调节，直到演示自由悬停跳跃和静态悬停。调节位置保持行为并演示自主返回着陆功能。演示强大的失控恢复和稳定性。调节风向标行为直到满意。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确认飞机的重量和平衡（距机翼前缘 26 毫米至 30 毫米）。验证俯仰在巡航速度（19 米/秒）下是否静态稳定。还要验证飞机方向是否稳定（静态风向标）。调整副翼上的俯仰，以 19 米/秒的速度产生水平滑行。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确认控制面偏转对于飞行员输入和自动驾驶仪对飞机运动和姿势的稳定响应都是正确的。如果有必要，大幅降低前飞 PID。手动启动飞机进行前飞，并确认其可控且稳定。请注意，如果控制偏差过大，控制可能会非常灵敏和快速。退出固定翼飞行，悬停并安全着陆。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果飞机在上一步中仍然完好无损且功能正常，请执行 AUTOTUNE 或同等操作，以获得适合前飞的合理 PID。调整航路点跟随行为并演示一致的导航。如果适用，从固定翼飞行开始演示自主着陆。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">悬停爬升至至少 50 米，并尝试向前飞行 VTOL 转换。调整转换行为，直到飞行器始终进入向前飞行状态。无论是有人驾驶还是自动驾驶，转换过程都应该相同。</font></font></p>
</li>
</ol>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该飞行器设计为以机头上仰姿态（正攻角）悬停。这样做的原因是，当机头下降到水平时，推力矢量会使飞行器初始向前漂移。建立向前轨迹后，发动机倾斜到 50/50 中间点，飞行器可以加速。然后发动机下降到完全向前飞行的位置。</font></font></p>
</blockquote>
<ol start="8" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示从发射到着陆的完全自主任务，包括正向和反向转换行为。</font></font></li>
</ol>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3D 打印指南</font></font><a name="user-content-3dprinting-brief"></a></h1><a id="user-content-3d-printing-guidelines-" class="anchor" aria-label="永久链接：3D 打印指南" href="#3d-printing-guidelines-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与其他 3D 打印的 R/C 飞机不同，MiniHawk 没有明确指定的任何内部结构，例如肋骨或纵梁；仅定义了飞机的外模线和舱室、接线导管和安装点。内部结构取决于在用于转换 3D 打印体积定义的切片软件中选择的任何填充图案。内部结构可能会在未来的修订中明确定义，但除此之外，由建造者定义使用的填充图案。以下部分提供了每个机身部件集的推荐设置（与 3MF 文件中的设置相匹配）。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">范围</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">左翼与右翼</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">鼻子</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">尾翼</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">舱口/盖子</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机舱</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">电机倾斜支架</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">層高</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">室壁厚度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.4毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.4毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.4毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.4毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.8 毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.8 毫米</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">顶部厚度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.6 毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.6 毫米</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">底部厚度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.2毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.6 毫米</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.6 毫米</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">顶部底部主模式</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线条</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同心</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线条</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线条</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线条</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线条</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始底层模式</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同心</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同心</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同心</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">同心</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线条</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线条</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">填补墙之间的空隙</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到处</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Z 缝对齐</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户指定（注 1）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SharpestCorner，隐藏接缝</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SharpestCorner，隐藏接缝</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SharpestCorner，隐藏接缝</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最锐利的角落，露出接缝</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最锐利的角落，露出接缝</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">填充密度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5.00％</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10.00％</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10.00％</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10.00％</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">20.00％</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">30.00％</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">填充图案</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">立方体</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">立方体</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">立方体</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">立方体</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">立方体</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">立方体</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">填充线方向</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">90度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0度（注2）</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">90度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0度</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成支持</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无处</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持安置</font></font></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">触摸构建板</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支撑悬垂角度</font></font></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">70度</font></font></td>
<td></td>
</tr>
</tbody>
</table>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注 1：强制发生在机翼后缘。</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
注 2：为了获得最佳结构，在 X 方向上略微偏移。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 MH7_ControlHornSet 和 MH7_TraySet，打印 100% 实心或根据需要。如果可能，这些部件可以用激光切割。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArduPlane 设置</font></font><a name="user-content-arduplane-brief"></a></h1><a id="user-content-arduplane-settings-" class="anchor" aria-label="永久链接：ArduPlane 设置" href="#arduplane-settings-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然 MiniHawk-VTOL 最初是使用 BetaFlight 航空电子生态系统开发的，但 ArduPilot 是当前设计的推荐生态系统。此文本部分取代了 v2.0.0 之前存在于此部分的原始 Betaflight 设置说明。旧的 Betaflight 设置说明可在 README.md 文件修订历史记录中找到。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">R/C 控制器配置（模式 2 控制器）</font></font><a name="user-content-arduplane-controlsconfig"></a></h2><a id="user-content-rc-controller-configuration-mode-2-controller-" class="anchor" aria-label="永久链接：R/C 控制器配置（模式 2 控制器）" href="#rc-controller-configuration-mode-2-controller-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">遥控频道</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">描述</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1000微秒</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1500微秒</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2000我们</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">笔记</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通道 1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卷</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向左滚动</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">居中</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向右滚动</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通道 2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">沥青</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机头向上</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中性的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机头朝下</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通道 3</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">节流阀/集体</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">闲置的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">50% 推力</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">100% 推力</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 QSTABILIZE 和 QLOITER/QHOVER 之间切换时要小心</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通道 4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">舵</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向左偏航</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中性的</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">右偏航</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通道 5</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行模式选择</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">宽带无线接入</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稳定</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自动/返航/自动调谐</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3 位置开关，2000us 由混合第二个 R/C 开关形成</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通道 6</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动覆盖</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已禁用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">---</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动模式激活！</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RC6_OPTION=51，适用于手动发射前飞</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">7 通道</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">布防开关</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已禁用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">---</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">武装！</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RC7_OPTION=41，ArduPilot 布防/撤防开关</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8 通道</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">瞬时开关</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已禁用</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">---</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSD、反转模式等</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OSD 屏幕循环、反转 (RC8_OPTION=43)，其他杂项用途</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，手动模式非常难用，应很少使用。它被包含在上文中，作为一种“作弊”来强制 ArduPlane VTOL 状态机在布防时保持向前飞行，例如当您想要手动发射飞机以跳过 VTOL 悬停和向前过渡时。首先使用 CH 5 飞行模式选择开关将飞机设置为 FBWA，然后只打开手动覆盖开关片刻，然后返回禁用状态（飞行模式返回到飞行模式开关设置的 FBWA）。否则，如果您只选择 FBWA 然后布防，飞机会立即恢复到 ArduPlane VTOL 向前过渡行为，所有三个电机都在悬停状态下旋转。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">飞行控制器连接</font></font><a name="user-content-arduplane-connections"></a></h2><a id="user-content-flight-controller-connections-" class="anchor" aria-label="永久链接：飞行控制器连接" href="#flight-controller-connections-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下表适用于 mRobotics PixRacer Pro。这应该适用于任何其他与 ArduPlane 兼容的飞行控制器。</font></font></p>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">别针 ＃</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">控制端点</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S1</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">右电机电调</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S2</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">左电机电调</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S3</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无连接 (BEC)</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S4</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">后/尾电机 ESC</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S5</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">左倾斜伺服</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S6</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">右倾斜伺服</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S7</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">左升降舵伺服装置</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">S8</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">右升降舵伺服装置</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArduPlane 参数</font></font><a name="user-content-arduplane-parameters"></a></h2><a id="user-content-arduplane-parameters-" class="anchor" aria-label="永久链接：ArduPlane 参数" href="#arduplane-parameters-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面的参数文件代表使用 mRo PixRacer Pro 飞行控制器的典型 MiniHawk-VTOL 上使用的设置。基本设置应适用于任何与 ArduPlane 兼容的飞行控制器，例如 Matek F405-WING 或类似产品，但需要进行一些调整。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">警告！</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果意外连接，现代 ESC 协议（例如 OneShot 或 DShot）无法与伺服器很好地配合使用。伺服器最多会过滤掉数据包，但在某些情况下伺服器会烧坏。不要将伺服器插入 ESC 输出！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mRo PixRacer Pro：</font></font><a href="/StephenCarlson/MiniHawk-VTOL/blob/master/cfg-Config/ArduPlane_MiniHawk_mRo_PixRacerPro.param"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArduPlane_MiniHawk_mRo_PixRacerPro.param</font></font></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然上述参数文件有超过 1100 个参数，但下面将检查一些基本参数：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>| Parameter,Value        | Notes                                                      |
| ---------------------- | ---------------------------------------------------------- |
| ARSPD_FBW_MAX,32       | Full-Throttle produces around 32 to 34 m/s sprint velocity |
| ARSPD_FBW_MIN,17       | Stall is near 15 m/s for a typical MiniHawk-VTOL           |
| ARSPD_RATIO,1.9936     | Make sure this is calibrated for your aircraft             |
| ARSPD_TUBE_ORDER,0     | While this can be automatic (3), manually set is better    |
| ARSPD_TYPE,1           | MS4525D0 Pressure Sensor, adjust as needed                 |
| ARSPD_USE,1            | Force the aircraft to use the pitot probe, no synthetic    |
| AUTOTUNE_LEVEL,7       | 7 or 8 works best for the MiniHawk-VTOL                    |
| EK2_ENABLE,0           | EKF2 is Disabled, in favor of EKF3                         |
| EK3_ENABLE,1           | EKF3 was used for most flight testing of the design        |
| FLTMODE_CH,5           | Flight Mode Channel                                        |
| FLTMODE1,5             | FBWA, 3-position switch "Down" detent                      |
| FLTMODE2,19            | QLOITER, 3-position switch "Middle" detent                 |
| FLTMODE3,17            | QSTABILIZE, 3-position switch "Up" detent                  |
| FLTMODE4,17            |                                                            |
| FLTMODE5,17            |                                                            |
| FLTMODE6,10            | AUTO, 2nd R/C switch that overrides the 3-position switch  |
| FS_LONG_ACTN,1         | Failsafe Settings used in development                      |
| FS_LONG_TIMEOUT,3      |                                                            |
| FS_SHORT_ACTN,1        |                                                            |
| FS_SHORT_TIMEOUT,1     |                                                            |
| KFF_RDDRMIX,0          | Remove any possible rudder mixing                          |
| LIM_PITCH_MAX,2000     | Pitch and Roll Angle Limits                                |
| LIM_PITCH_MIN,-2500    |                                                            |
| LIM_ROLL_CD,5500       |                                                            |
| MIXING_GAIN,0.5        | Elevon Stick Mixing, value here should be default          |
| NAVL1_PERIOD,11        | More aggressive navigation is possible, 11 to 14 tested    |
| PTCH_RATE_D,0          | Pitch PIDs, these values are mild, AUTOTUNE will increase  |
| PTCH_RATE_FF,0.345     |                                                            |
| PTCH_RATE_FLTD,4       |                                                            |
| PTCH_RATE_FLTE,7       |                                                            |
| PTCH_RATE_FLTT,1.5     |                                                            |
| PTCH_RATE_I,0.15       |                                                            |
| PTCH_RATE_IMAX,0.666   |                                                            |
| PTCH_RATE_P,0.04       |                                                            |
| PTCH_RATE_SMAX,150     |                                                            |
| PTCH2SRV_RLL,1         |                                                            |
| PTCH2SRV_RMAX_DN,90    |                                                            |
| PTCH2SRV_RMAX_UP,90    |                                                            |
| PTCH2SRV_TCONST,0.4    |                                                            |
| Q_A_ACCEL_P_MAX,110000 | VTOL R/P/Y Angular accelerations used in development       |
| Q_A_ACCEL_R_MAX,110000 |                                                            |
| Q_A_ACCEL_Y_MAX,27000  |                                                            |
| Q_A_RAT_PIT_D,0.0005   | VTOL Pitch PIDs                                            |
| Q_A_RAT_PIT_FF,0       |                                                            |
| Q_A_RAT_PIT_FLTD,15    |                                                            |
| Q_A_RAT_PIT_FLTE,0     |                                                            |
| Q_A_RAT_PIT_FLTT,20    |                                                            |
| Q_A_RAT_PIT_I,0.15     |                                                            |
| Q_A_RAT_PIT_IMAX,0.5   |                                                            |
| Q_A_RAT_PIT_P,0.15     |                                                            |
| Q_A_RAT_PIT_SMAX,0     |                                                            |
| Q_A_RAT_RLL_D,0.003    | VTOL Roll PIDs                                             |
| Q_A_RAT_RLL_FF,0       |                                                            |
| Q_A_RAT_RLL_FLTD,15    |                                                            |
| Q_A_RAT_RLL_FLTE,0     |                                                            |
| Q_A_RAT_RLL_FLTT,20    |                                                            |
| Q_A_RAT_RLL_I,0.25     |                                                            |
| Q_A_RAT_RLL_IMAX,0.5   |                                                            |
| Q_A_RAT_RLL_P,0.45     |                                                            |
| Q_A_RAT_RLL_SMAX,0     |                                                            |
| Q_A_RAT_YAW_D,0.02     | VTOL Yaw PIDs                                              |
| Q_A_RAT_YAW_FF,0.1     |                                                            |
| Q_A_RAT_YAW_FLTD,0     |                                                            |
| Q_A_RAT_YAW_FLTE,10    |                                                            |
| Q_A_RAT_YAW_FLTT,20    |                                                            |
| Q_A_RAT_YAW_I,0.1      |                                                            |
| Q_A_RAT_YAW_IMAX,0.5   |                                                            |
| Q_A_RAT_YAW_P,0.6      |                                                            |
| Q_A_RAT_YAW_SMAX,0     |                                                            |
| Q_ANGLE_MAX,3000       | VTOL Pitch and Roll Angle Limits                           |
| Q_ASSIST_ALT,0         | Disable VTOL Assist where possible                         |
| Q_ASSIST_ANGLE,0       |                                                            |
| Q_ASSIST_DELAY,0.5     |                                                            |
| Q_ASSIST_SPEED,0       |                                                            |
| Q_AUTOTUNE_AGGR,0.1    | VTOL Autotune settings used in development                 |
| Q_AUTOTUNE_AXES,2      |                                                            |
| Q_AUTOTUNE_MIN_D,0.001 |                                                            |
| Q_ENABLE,1             | VTOL obviously is enabled for the MiniHawk-VTOL            |
| Q_FRAME_CLASS,7        | Tricopter Configuration                                    |
| Q_FW_LND_APR_RAD,85    | 85 meters for Fixed-wing to VTOL threshold                 |
| Q_M_HOVER_LEARN,2      | Hover throttle setpoint learning                           |
| Q_M_PWM_TYPE,4         | DShot 150 is sufficient and noise-resistant                |
| Q_M_SPIN_ARM,0.05      | 5% Throttle when armed                                     |
| Q_M_SPIN_MAX,1         | 100% Throttle max ESC RPM command                          |
| Q_M_SPIN_MIN,0.1       | 10% Throttle for lowest ESC RPM                            |
| Q_M_SPOOL_TIME,0.5     | 500ms spool time                                           |
| Q_M_THST_EXPO,0.25     | Throttle Expo                                              |
| Q_M_YAW_HEADROOM,50    | 50us Yaw Headroom                                          |
| Q_M_YAW_SV_ANGLE,12    | "12" Degrees for Yaw lean angle                            |
| Q_OPTIONS,1056         | Allow yaw actuation when disarmed, QRTL behavior           |
| Q_RC_SPEED,490         | 490 Hz Motor Updates                                       |
| Q_RTL_ALT,40           | RTL Behaviors in VTOL                                      |
| Q_RTL_MODE,1           |                                                            |
| Q_TILT_MASK,3          | Which motors are being tilted                              |
| Q_TILT_MAX,55          | Transition angle while AirspeedWait is active              |
| Q_TILT_RATE_DN,15      | Tilt Up/Down rates                                         |
| Q_TILT_RATE_UP,75      |                                                            |
| Q_TILT_TYPE,2          | Vectored Yaw Tilt Type                                     |
| Q_TILT_YAW_ANGLE,14    | "14" degrees VTOL hover position                           |
| Q_TRANS_FAIL,0         | Transition Timeout is disabled                             |
| Q_TRANSITION_MS,1000   | Post-transition wait period                                |
| Q_TRIM_PITCH,9         | Pitch offset between forward-flight and hover stance       |
| Q_WVANE_GAIN,0.4       | 0.4 is a good value for this design                        |
| RC7_OPTION,41          | Arming Switch, will disable motors if in flight/hover!     |
| RCMAP_PITCH,2          | Roll/Pitch/Throttle/Yaw (AETR) controls ordering           |
| RCMAP_ROLL,1           |                                                            |
| RCMAP_THROTTLE,3       |                                                            |
| RCMAP_YAW,4            |                                                            |
| RLL_RATE_D,0           | Roll PIDs, these values are mild, AUTOTUNE will increase   |
| RLL_RATE_FF,0.345      |                                                            |
| RLL_RATE_FLTD,4        |                                                            |
| RLL_RATE_FLTE,7        |                                                            |
| RLL_RATE_FLTT,3        |                                                            |
| RLL_RATE_I,0.15        |                                                            |
| RLL_RATE_IMAX,0.666    |                                                            |
| RLL_RATE_P,0.08        |                                                            |
| RLL_RATE_SMAX,150      |                                                            |
| RLL2SRV_RMAX,90        |                                                            |
| RLL2SRV_TCONST,0.4     |                                                            |
| RTL_AUTOLAND,2         | Fixed-wing to VTOL landing behavior in RTL                 |
| RUDD_DT_GAIN,3         | Very mild differential thrust mixing on forward motors     |
| SCALING_SPEED,15       | 15 m/s should be default                                   |
| SCHED_LOOP_RATE,300    | 300 Hz was used in development                             |
| SERVO1_FUNCTION,33     | Right BLDC Motor                                           |
| SERVO2_FUNCTION,34     | Left BLCD Motor                                            |
| SERVO3_FUNCTION,0      | No Connection, 5V BEC connected here for mRo PixRacer Pro  |
| SERVO4_FUNCTION,36     | Rear BLCD Motor                                            |
| SERVO5_FUNCTION,75     | Left Tilt Servo                                            |
| SERVO5_MAX,1800        | MAX and MIN values are hand calibrated, close to 1920/1080 |
| SERVO5_MIN,1200        | Values of 1200/1800 here to prevent damage on new builds   |
| SERVO5_REVERSED,0      | Left Tilt is normal rotation direction                     |
| SERVO6_FUNCTION,76     | Right Tilt Servo                                           |
| SERVO6_MAX,1800        |                                                            |
| SERVO6_MIN,1200        |                                                            |
| SERVO6_REVERSED,1      | Right Tilt is reversed rotation direction                  |
| SERVO7_FUNCTION,77     | Left Elevon Servo                                          |
| SERVO7_REVERSED,1      | Left Elevon is reverse rotation direction                  |
| SERVO8_FUNCTION,78     | Right Elevon Servo                                         |
| SERVO8_REVERSED,0      | Right Elevon is normal rotation direction                  |
| STAB_PITCH_DOWN,2      | 2 should be default, pitch behavior on zero-throttle       |
| STALL_PREVENTION,0     | May be enabled, was disabled for development               |
| STICK_MIXING,1         | How pilot inputs are fused in autonomous modes             |
| TECS_PTCH_FF_V0,19     | 19 m/s cruise                                              |
| TRIM_ARSPD_CM,1900     | 19 m/s cruise                                              |
| TRIM_PITCH_CD,350      | Offset between level-flight pitch angle and tray angle     |
| TRIM_THROTTLE,55       | Typical 19 m/s cruise throttle                             |
| WP_LOITER_RAD,60       | 60 meter radius for loiter typical                         |
| WP_RADIUS,40           | 40 meter waypoint radius typical                           |
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="| Parameter,Value        | Notes                                                      |
| ---------------------- | ---------------------------------------------------------- |
| ARSPD_FBW_MAX,32       | Full-Throttle produces around 32 to 34 m/s sprint velocity |
| ARSPD_FBW_MIN,17       | Stall is near 15 m/s for a typical MiniHawk-VTOL           |
| ARSPD_RATIO,1.9936     | Make sure this is calibrated for your aircraft             |
| ARSPD_TUBE_ORDER,0     | While this can be automatic (3), manually set is better    |
| ARSPD_TYPE,1           | MS4525D0 Pressure Sensor, adjust as needed                 |
| ARSPD_USE,1            | Force the aircraft to use the pitot probe, no synthetic    |
| AUTOTUNE_LEVEL,7       | 7 or 8 works best for the MiniHawk-VTOL                    |
| EK2_ENABLE,0           | EKF2 is Disabled, in favor of EKF3                         |
| EK3_ENABLE,1           | EKF3 was used for most flight testing of the design        |
| FLTMODE_CH,5           | Flight Mode Channel                                        |
| FLTMODE1,5             | FBWA, 3-position switch &quot;Down&quot; detent                      |
| FLTMODE2,19            | QLOITER, 3-position switch &quot;Middle&quot; detent                 |
| FLTMODE3,17            | QSTABILIZE, 3-position switch &quot;Up&quot; detent                  |
| FLTMODE4,17            |                                                            |
| FLTMODE5,17            |                                                            |
| FLTMODE6,10            | AUTO, 2nd R/C switch that overrides the 3-position switch  |
| FS_LONG_ACTN,1         | Failsafe Settings used in development                      |
| FS_LONG_TIMEOUT,3      |                                                            |
| FS_SHORT_ACTN,1        |                                                            |
| FS_SHORT_TIMEOUT,1     |                                                            |
| KFF_RDDRMIX,0          | Remove any possible rudder mixing                          |
| LIM_PITCH_MAX,2000     | Pitch and Roll Angle Limits                                |
| LIM_PITCH_MIN,-2500    |                                                            |
| LIM_ROLL_CD,5500       |                                                            |
| MIXING_GAIN,0.5        | Elevon Stick Mixing, value here should be default          |
| NAVL1_PERIOD,11        | More aggressive navigation is possible, 11 to 14 tested    |
| PTCH_RATE_D,0          | Pitch PIDs, these values are mild, AUTOTUNE will increase  |
| PTCH_RATE_FF,0.345     |                                                            |
| PTCH_RATE_FLTD,4       |                                                            |
| PTCH_RATE_FLTE,7       |                                                            |
| PTCH_RATE_FLTT,1.5     |                                                            |
| PTCH_RATE_I,0.15       |                                                            |
| PTCH_RATE_IMAX,0.666   |                                                            |
| PTCH_RATE_P,0.04       |                                                            |
| PTCH_RATE_SMAX,150     |                                                            |
| PTCH2SRV_RLL,1         |                                                            |
| PTCH2SRV_RMAX_DN,90    |                                                            |
| PTCH2SRV_RMAX_UP,90    |                                                            |
| PTCH2SRV_TCONST,0.4    |                                                            |
| Q_A_ACCEL_P_MAX,110000 | VTOL R/P/Y Angular accelerations used in development       |
| Q_A_ACCEL_R_MAX,110000 |                                                            |
| Q_A_ACCEL_Y_MAX,27000  |                                                            |
| Q_A_RAT_PIT_D,0.0005   | VTOL Pitch PIDs                                            |
| Q_A_RAT_PIT_FF,0       |                                                            |
| Q_A_RAT_PIT_FLTD,15    |                                                            |
| Q_A_RAT_PIT_FLTE,0     |                                                            |
| Q_A_RAT_PIT_FLTT,20    |                                                            |
| Q_A_RAT_PIT_I,0.15     |                                                            |
| Q_A_RAT_PIT_IMAX,0.5   |                                                            |
| Q_A_RAT_PIT_P,0.15     |                                                            |
| Q_A_RAT_PIT_SMAX,0     |                                                            |
| Q_A_RAT_RLL_D,0.003    | VTOL Roll PIDs                                             |
| Q_A_RAT_RLL_FF,0       |                                                            |
| Q_A_RAT_RLL_FLTD,15    |                                                            |
| Q_A_RAT_RLL_FLTE,0     |                                                            |
| Q_A_RAT_RLL_FLTT,20    |                                                            |
| Q_A_RAT_RLL_I,0.25     |                                                            |
| Q_A_RAT_RLL_IMAX,0.5   |                                                            |
| Q_A_RAT_RLL_P,0.45     |                                                            |
| Q_A_RAT_RLL_SMAX,0     |                                                            |
| Q_A_RAT_YAW_D,0.02     | VTOL Yaw PIDs                                              |
| Q_A_RAT_YAW_FF,0.1     |                                                            |
| Q_A_RAT_YAW_FLTD,0     |                                                            |
| Q_A_RAT_YAW_FLTE,10    |                                                            |
| Q_A_RAT_YAW_FLTT,20    |                                                            |
| Q_A_RAT_YAW_I,0.1      |                                                            |
| Q_A_RAT_YAW_IMAX,0.5   |                                                            |
| Q_A_RAT_YAW_P,0.6      |                                                            |
| Q_A_RAT_YAW_SMAX,0     |                                                            |
| Q_ANGLE_MAX,3000       | VTOL Pitch and Roll Angle Limits                           |
| Q_ASSIST_ALT,0         | Disable VTOL Assist where possible                         |
| Q_ASSIST_ANGLE,0       |                                                            |
| Q_ASSIST_DELAY,0.5     |                                                            |
| Q_ASSIST_SPEED,0       |                                                            |
| Q_AUTOTUNE_AGGR,0.1    | VTOL Autotune settings used in development                 |
| Q_AUTOTUNE_AXES,2      |                                                            |
| Q_AUTOTUNE_MIN_D,0.001 |                                                            |
| Q_ENABLE,1             | VTOL obviously is enabled for the MiniHawk-VTOL            |
| Q_FRAME_CLASS,7        | Tricopter Configuration                                    |
| Q_FW_LND_APR_RAD,85    | 85 meters for Fixed-wing to VTOL threshold                 |
| Q_M_HOVER_LEARN,2      | Hover throttle setpoint learning                           |
| Q_M_PWM_TYPE,4         | DShot 150 is sufficient and noise-resistant                |
| Q_M_SPIN_ARM,0.05      | 5% Throttle when armed                                     |
| Q_M_SPIN_MAX,1         | 100% Throttle max ESC RPM command                          |
| Q_M_SPIN_MIN,0.1       | 10% Throttle for lowest ESC RPM                            |
| Q_M_SPOOL_TIME,0.5     | 500ms spool time                                           |
| Q_M_THST_EXPO,0.25     | Throttle Expo                                              |
| Q_M_YAW_HEADROOM,50    | 50us Yaw Headroom                                          |
| Q_M_YAW_SV_ANGLE,12    | &quot;12&quot; Degrees for Yaw lean angle                            |
| Q_OPTIONS,1056         | Allow yaw actuation when disarmed, QRTL behavior           |
| Q_RC_SPEED,490         | 490 Hz Motor Updates                                       |
| Q_RTL_ALT,40           | RTL Behaviors in VTOL                                      |
| Q_RTL_MODE,1           |                                                            |
| Q_TILT_MASK,3          | Which motors are being tilted                              |
| Q_TILT_MAX,55          | Transition angle while AirspeedWait is active              |
| Q_TILT_RATE_DN,15      | Tilt Up/Down rates                                         |
| Q_TILT_RATE_UP,75      |                                                            |
| Q_TILT_TYPE,2          | Vectored Yaw Tilt Type                                     |
| Q_TILT_YAW_ANGLE,14    | &quot;14&quot; degrees VTOL hover position                           |
| Q_TRANS_FAIL,0         | Transition Timeout is disabled                             |
| Q_TRANSITION_MS,1000   | Post-transition wait period                                |
| Q_TRIM_PITCH,9         | Pitch offset between forward-flight and hover stance       |
| Q_WVANE_GAIN,0.4       | 0.4 is a good value for this design                        |
| RC7_OPTION,41          | Arming Switch, will disable motors if in flight/hover!     |
| RCMAP_PITCH,2          | Roll/Pitch/Throttle/Yaw (AETR) controls ordering           |
| RCMAP_ROLL,1           |                                                            |
| RCMAP_THROTTLE,3       |                                                            |
| RCMAP_YAW,4            |                                                            |
| RLL_RATE_D,0           | Roll PIDs, these values are mild, AUTOTUNE will increase   |
| RLL_RATE_FF,0.345      |                                                            |
| RLL_RATE_FLTD,4        |                                                            |
| RLL_RATE_FLTE,7        |                                                            |
| RLL_RATE_FLTT,3        |                                                            |
| RLL_RATE_I,0.15        |                                                            |
| RLL_RATE_IMAX,0.666    |                                                            |
| RLL_RATE_P,0.08        |                                                            |
| RLL_RATE_SMAX,150      |                                                            |
| RLL2SRV_RMAX,90        |                                                            |
| RLL2SRV_TCONST,0.4     |                                                            |
| RTL_AUTOLAND,2         | Fixed-wing to VTOL landing behavior in RTL                 |
| RUDD_DT_GAIN,3         | Very mild differential thrust mixing on forward motors     |
| SCALING_SPEED,15       | 15 m/s should be default                                   |
| SCHED_LOOP_RATE,300    | 300 Hz was used in development                             |
| SERVO1_FUNCTION,33     | Right BLDC Motor                                           |
| SERVO2_FUNCTION,34     | Left BLCD Motor                                            |
| SERVO3_FUNCTION,0      | No Connection, 5V BEC connected here for mRo PixRacer Pro  |
| SERVO4_FUNCTION,36     | Rear BLCD Motor                                            |
| SERVO5_FUNCTION,75     | Left Tilt Servo                                            |
| SERVO5_MAX,1800        | MAX and MIN values are hand calibrated, close to 1920/1080 |
| SERVO5_MIN,1200        | Values of 1200/1800 here to prevent damage on new builds   |
| SERVO5_REVERSED,0      | Left Tilt is normal rotation direction                     |
| SERVO6_FUNCTION,76     | Right Tilt Servo                                           |
| SERVO6_MAX,1800        |                                                            |
| SERVO6_MIN,1200        |                                                            |
| SERVO6_REVERSED,1      | Right Tilt is reversed rotation direction                  |
| SERVO7_FUNCTION,77     | Left Elevon Servo                                          |
| SERVO7_REVERSED,1      | Left Elevon is reverse rotation direction                  |
| SERVO8_FUNCTION,78     | Right Elevon Servo                                         |
| SERVO8_REVERSED,0      | Right Elevon is normal rotation direction                  |
| STAB_PITCH_DOWN,2      | 2 should be default, pitch behavior on zero-throttle       |
| STALL_PREVENTION,0     | May be enabled, was disabled for development               |
| STICK_MIXING,1         | How pilot inputs are fused in autonomous modes             |
| TECS_PTCH_FF_V0,19     | 19 m/s cruise                                              |
| TRIM_ARSPD_CM,1900     | 19 m/s cruise                                              |
| TRIM_PITCH_CD,350      | Offset between level-flight pitch angle and tray angle     |
| TRIM_THROTTLE,55       | Typical 19 m/s cruise throttle                             |
| WP_LOITER_RAD,60       | 60 meter radius for loiter typical                         |
| WP_RADIUS,40           | 40 meter waypoint radius typical                           |" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">评论：</font></font><a name="user-content-arduplane-remarks"></a></h2><a id="user-content-remarks-" class="anchor" aria-label="永久链接： 备注：" href="#remarks-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ArduPlane v4.1.0 和 v4.2.0dev 用于开发版本 2 MiniHawk-VTOL。“开箱即用”，ArduPlane 支持这种设计的三旋翼倾转旋翼机，并且只需设置参数即可启用 VTOL 行为。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此固件版本中，处理 VTOL 飞行行为的某些方面有些违反直觉。其中最令人讨厌的是，无论是有人驾驶还是自主飞行，都无法直接控制 VTOL 飞行状态。VTOL 状态机无法直接控制前进飞行状态，而是需要空速估计值（合成或通过皮托管测量）来驱动前进 VTOL 过渡到固定翼飞行。这使得人类飞行员只是过渡过程中的投票成员，累积空速决定何时允许倾斜旋翼完全向前倾斜以及后部电机停止。开发人员的心态将悬停状态视为默认的后备，并且如果在一定时间内无法累积空速，则该过程将通过 恢复为悬停作为故障保护</font></font><code>Q_TRANS_FAIL</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。如果禁用此转换失败超时，AirspeedWait 状态将持续，并且车辆将无限期地以三旋翼和固定翼飞行的半混合方式飞行。对于像 MiniHawk-VTOL 这样的飞行器设计，功率过大且速度非常快，超时导致强制向前飞行比将飞行器置于这种混合行为更有意义，或者如果使用转换失败计时器，则将飞行器置于电池电量有限且极限航程和高度悬停的状态，但这是另一天的拉取请求。因此，对于当前的固件状态，有必要了解这种行为并知道它为什么会卡在混合模式中。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">前向转换 VTOL 行为的另一个后果是，在解除武装时，即使选择前向飞行模式（例如 FBWA）会导致旋翼倾斜到向前位置，但在武装后，飞行器将立即进入 AirspeedWait 状态，前旋翼向上倾斜，后旋翼旋转。油门设置显然决定了悬停和前向飞行空速等待之间的混合，但如果您尝试像传统固定翼一样手动发射，更好的解决方案是“撞”入 MANUAL 模式片刻。这会强制 VTOL 状态机越过 AirspeedWait 状态，并允许您在 FWBA 模式下武装，让前旋翼保持在向前位置，同时在手动发射时享受升降副翼稳定和调平。只需确保从 MANUAL 模式翻转回 FBWA，除非您打算完全手动手动发射而没有稳定或调平。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在有人驾驶的情况下，从固定翼飞行到悬停的过渡通常很平稳，但在自动驾驶模式下，存在一个已知问题，即在反向垂直起降过渡到悬停时，飞行器会机头下沉然后猛地拉起。如果负重力或突然的颠簸运动导致零件分离，这可能会对飞行器造成危险。问题可能出在 TECS 调整参数中，或者是固件 4.1 或 4.2 的本地问题。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font><a name="user-content-license-brief"></a></h1><a id="user-content-license-" class="anchor" aria-label="永久链接：许可证" href="#license-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本作品根据 Creative Commons Attribution-NonCommercial-ShareAlike 4.0 国际许可协议授权。要查看此许可协议的副本，请访问</font></font><a href="http://creativecommons.org/licenses/by-nc-sa/4.0/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://creativecommons.org/licenses/by-nc-sa/4.0/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或致函 Creative Commons, PO Box 1866, Mountain View, CA 94042, USA。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处提供的 Ardupilot 和 Betaflight 软件配置文本文件可能属于 GPL-3.0；在撰写本文时，这两个项目均根据 GPL-3.0 获得许可。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MiniHawk VTOL - 设计、文档、图像和所有其他艺术品；作者：Steve Carlson </font></font><br>
<a href="https://github.com/StephenCarlson/MiniHawk-VTOL"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/StephenCarlson/MiniHawk-VTOL</font></font></a></p>
</article></div>
