# Reading Foundations

这是一份面向人工智能专业本科生、可持续使用 5–10 年的原文阅读地图。它不是“最短书单”，也不是摘要合集：目标是建立一条从短文本、可复述的问题，逐步通向技术基础、科学方法、伦理判断和政治经济学原典的路径。

> 核验说明：链接于 2026-09-12 实际请求验证。`200` 表示本次核验可打开；OUP、MIT Press 等少数官方页对自动请求返回 403，但 DOI/出版社入口本身有效，已另以 JSTOR、Internet Archive 或课程页交叉核验。Internet Archive 中标有 `access-restricted-item: true` 的条目统一写作“受控借阅”，绝不写成公版下载。中文版本若出版社年份无法从权威目录稳定确认，明确不写年份或标“未确认”。

## 阅读原则

1. **先读原文，再用 AI。** 每次先独立读 5–15 页，划出不懂处并写下自己的暂时解释；之后再让 AI 解释术语、历史语境或论证结构。
2. **让 AI 做脚手架，不做替身。** 适合交给 AI 的任务：术语表、背景时间线、相反观点、检查你的复述是否遗漏前提。不适合：在你没读之前生成“全书思想”、替你写读后感、把难段落改写到失去原句结构。
3. **每次只留三种笔记。** `原句/页码`、`我的复述`、`仍未解决的问题`。二次阅读时再补概念网络，不追求第一次就做百科全书式笔记。
4. **摘要放在阅读之后。** 读完一篇/一章，先关书写 150–300 字，再对照导读。若不能说出作者的问题、核心区分和一个反例，就回到原文。
5. **保留版本信息。** 笔记首页写明语言、译者、出版社/网址和章节或 Bekker/页码。Marx、Arendt、Aristotle、Kuhn 尤其依赖术语，跨译本讨论时必须能回到原文。
6. **允许“选读后搁置”。** 难书第一次只建立地形图；精读不等于从第一页匀速读到最后一页。

一个实用的 AI 提示模板：

> 我已读完第 X 章。以下是我的 200 字复述和三个疑问。请只做三件事：指出我漏掉的关键前提；给出一个最强反例；列出需要回到原文核查的 3 处。不要替我写摘要。

## 最适合现在开始的阅读路径

原定顺序总体合理：它从 Turing 的短论文进入，以文学打断纯技术视角，再经 Simon、Mill、Kuhn、Aristotle、Arendt 到 Marx，认知负荷是逐步增加的。只作三处小调整：把两篇 Borges 插在《地下室手记》之后；把 Wiener 放在 Simon 之后作为“控制—沟通—人的用途”的桥；把数学教材作为并行轨道，而不是等人文主线结束再开始。

| 顺序 | 阅读单元 | 第一次的最低完成标准 | 建议节奏 |
|---:|---|---|---|
| 1 | Turing, “Computing Machinery and Intelligence” | 全文；能列出模仿游戏、九类反对意见中的三类 | 2–3 次，每次 30–45 分钟 |
| 2 | *Notes from Underground* | 先第一部，再第二部；写下叙述者自我矛盾的两处 | 1–2 周 |
| 3 | Borges 两篇 | 各读两遍；第二遍只追踪“记忆/分类/无限” | 3–4 天 |
| 4 | Simon, *The Sciences of the Artificial* | 先第 1 章与 “The Science of Design”；版本章次不同，以标题为准 | 2 周 |
| 5 | Wiener, *The Human Use of Human Beings* | 序言、关于熵/进步/语言与法律的选章 | 1–2 周 |
| 6 | Mill, *On Liberty* | 第 1–3 章精读；第 4–5 章选读 | 2 周 |
| 7 | Kuhn, *The Structure of Scientific Revolutions* | 序言；第 II–III、IX–X、XIII 章 | 2–3 周 |
| 8 | Aristotle, *Nicomachean Ethics* | Book I、II、VI、X；其余先查问题再选读 | 4–6 周 |
| 9 | Arendt, *The Human Condition* | Prologue、I，以及 labor/work/action 三部分的开头和总结 | 4–6 周 |
| 10 | Marx, *Capital I* | 商品、工作日、机器与大工业、原始积累；不要首次通读 | 2–4 个月 |
| 11 | Marx, *Grundrisse* | 先 “Fragment on Machines” 所在段，再回读导言和资本章 | 3–5 周 |

如果某周注意力很差，不换成摘要；把任务缩成“读 4 页 + 写 1 个问题”。持续接触原文比完成虚假的进度更重要。

## 第一阶段：容易进入

### 1. Alan Turing — “Computing Machinery and Intelligence”

- **首次出版：** 1950，*Mind* 59(236), 433–460，DOI `10.1093/mind/LIX.236.433`。[^1]
- **推荐语言：** 两者皆可；至少把 §1–2、§6–7 与结尾读英文。
- **权威原文/官方页：** [Oxford Academic / DOI（期刊原页）](https://doi.org/10.1093/mind/LIX.236.433)〔来源类型：期刊/出版社；自动核验遇 403〕；[JSTOR 稳定记录](https://www.jstor.org/stable/2251299)〔来源类型：学术期刊库；已验证 200，可能要求机构登录〕。
- **合法免费完整版：** **未找到明确标注开放许可的官方免费完整版。** [UMBC 课程托管 PDF](https://courses.cs.umbc.edu/471/papers/turing.pdf)〔来源类型：大学课程材料；已验证 PDF 200〕可以阅读，但页面未标再发布许可，因此未本地保存，也不把它称为开放授权版本。
- **中文译本：** 常见篇名有《计算机器与智能》《机器能思考吗？》；未确认一个可稳定核验、适合作为唯一推荐的正式单行本译本。建议英文为准，中文只作对照。
- **辅助材料：** [SEP: The Turing Test](https://plato.stanford.edu/entries/turing-test/)〔哲学百科；已验证 200〕。
- **难度/顺序/方式：** 3/5；总顺序 1；**精读**。
- **第一次最值得问：** ① Turing 为什么把“机器能思考吗”改写成可操作的游戏？② 行为判准解决了什么，又排除了什么？③ “学习机器”是否已经预示现代机器学习，哪些地方并没有？

### 2. Fyodor Dostoevsky — *Notes from Underground*

- **首次出版：** 1864（俄文《Записки из подполья》）。
- **推荐语言：** 两者皆可；不懂俄语时，中文与英文各抽查关键段落可暴露译法差异。
- **权威/合法全文：** [Project Gutenberg #600](https://www.gutenberg.org/ebooks/600)〔公版库；Constance Garnett 英译；已验证 200〕；本地已保存 [EPUB](./dostoevsky_notes_from_underground_gutenberg_600.epub)。[^2]
- **中文译本：** 臧仲伦译《地下室手记》是常见可检索版本；同名版本较多，出版社与年份随版本变化，**此处不固定一个未充分核验的版次**。购买时核对译者及版权页。可从 [WorldCat 题名/译者检索](https://search.worldcat.org/search?q=%E5%9C%B0%E4%B8%8B%E5%AE%A4%E6%89%8B%E8%AE%B0+%E8%87%A7%E4%BB%B2%E4%BC%A6) 查馆藏。
- **辅助材料：** 先不读导论；读完第一部再查 Dostoevsky 与理性利己主义、自由意志的背景。
- **难度/顺序/方式：** 2/5；总顺序 2；**精读短篇**。
- **第一次最值得问：** ① 地下人反对的是理性本身，还是把人化约为可计算利益的理性主义？② 他何时在反抗，何时又享受自己的屈辱？③ 他的“自由”与 Turing 的行为判准会发生什么冲突？

### 3. Jorge Luis Borges — “Funes the Memorious” / “The Library of Babel”

- **作者：** Jorge Luis Borges。
- **首次出版：** “Funes el memorioso” 1942；“La biblioteca de Babel” 1941；二者后收入 *Ficciones*（1944）。
- **推荐语言：** 两者皆可；若不读西语，可把中文王永年译本与 Andrew Hurley 英译作少量对照。
- **官方/权威入口：** [Penguin Random House: *Ficciones*](https://www.penguinrandomhouse.com/books/16193/ficciones-by-jorge-luis-borges-introduction-by-john-sturrock/)〔出版社；已验证 200〕；[PRH: *Collected Fictions*, Andrew Hurley trans.](https://www.penguinrandomhouse.com/books/330909/collected-fictions-by-jorge-luis-borges-translated-by-andrew-hurley/)〔出版社〕；[Borges Center, University of Pittsburgh](https://www.borges.pitt.edu/)〔大学研究中心；本次自动请求被站点拒绝，保留为机构入口〕。
- **合法免费完整版：** **未找到合法免费完整版。** [Internet Archive: *Ficciones*](https://archive.org/details/ficciones0000borg)〔数字图书馆受控借阅；条目已验证 200，元数据标 `restricted=true`〕；[Google Books 书目/预览](https://books.google.com/books/about/Ficciones.html?id=_D9CAAAAYAAJ)〔商业图书预览〕。
- **中文译本：** 王永年译《虚构集》（上海译文出版社，多次再版）通常同时收入《博闻强记的富内斯/记忆的富内斯》和《巴别图书馆》；篇名随版次略异。可用 [WorldCat 检索](https://search.worldcat.org/search?q=%E8%99%9A%E6%9E%84%E9%9B%86+%E7%8E%8B%E6%B0%B8%E5%B9%B4) 核对馆藏。
- **辅助材料：** Borges Center 的书目、访谈和研究索引；第一次应先读小说，后读评论。
- **难度/顺序/方式：** 2/5；总顺序 3；**各精读两遍**。
- **第一次最值得问：** ① 完美记忆为什么可能毁掉抽象与思考？② 无限信息与知识之间缺了什么？③ 分类、索引和检索系统是否改变了“知道”的含义？

## 第二阶段：建立认知框架

### 4. Herbert A. Simon — *The Sciences of the Artificial*

- **首次出版：** 1969；后有 1981 第二版、1996 第三版。
- **推荐语言：** 两者皆可；“artificial / design / bounded rationality / hierarchy” 保留英文术语。
- **官方页：** [MIT Press（原版书目，ISBN 9780262690232）](https://mitpress.mit.edu/9780262690232/the-sciences-of-the-artificial/)〔出版社；搜索索引确认，自动请求 403〕；[MIT Press 1969 回顾](https://mitpress.mit.edu/1969-perceptrons-intro-and-1969-the-sciences-of-the-artificial/)〔出版社〕。
- **合法免费完整版：** **未找到合法免费完整版。** [Internet Archive 1969 版](https://archive.org/details/sciencesofartifi00simo)〔受控借阅；已验证 200，`restricted=true`〕；也可从图书馆借阅。
- **中文译本：** 《人工科学：复杂性面面观》（第三版），武夷山译，上海科技教育出版社，常见书目年份为 2004；建议用 [WorldCat](https://search.worldcat.org/search?q=%E4%BA%BA%E5%B7%A5%E7%A7%91%E5%AD%A6+%E6%AD%A6%E5%A4%B7%E5%B1%B1) 再核对所购版次。
- **辅助材料：** 先读 “Understanding the Natural and Artificial Worlds” 与 “The Science of Design”；不同版章号不同，以章名为准。
- **难度/顺序/方式：** 3/5；总顺序 4；**第一次选读，第二次精读设计与复杂性章节**。
- **第一次最值得问：** ① “人工物”为什么不能只用自然科学的因果语言解释？② 设计科学的规范性从何而来？③ 有限理性如何改变对最优算法和人类决策的想象？

### 5. Norbert Wiener — *The Human Use of Human Beings: Cybernetics and Society*

- **首次出版：** 1950；1954 有修订版。
- **推荐语言：** 两者皆可。
- **权威/借阅入口：** [Internet Archive 1950 版](https://archive.org/details/humanuseofhumanb00wien) 与 [1954 修订版](https://archive.org/details/humanuseofhuma1954wien)〔数字图书馆受控借阅；后者已验证 200，均 `restricted=true`〕；[WorldCat 检索](https://search.worldcat.org/search?q=ti%3AThe+Human+Use+of+Human+Beings+au%3ANorbert+Wiener)〔图书馆联合目录〕。
- **合法免费完整版：** **未找到合法免费完整版。** 不使用网上来源不明的扫描 PDF。
- **中文译本：** 《人有人的用处：控制论和社会》，陈步译，商务印书馆，多次重印；具体印次年份未在可稳定访问的出版社页确认。
- **辅助材料：** 与 Shannon 的信息概念对读；留意 Wiener 把“信息、熵、反馈”从技术语言移到社会语言时的跳跃。
- **难度/顺序/方式：** 3/5；总顺序 5；**选读后再通读**。
- **第一次最值得问：** ① 反馈控制何时是描述，何时变成社会规范？② 人的尊严为何会被自动化系统损害？③ “信息”能否承载意义，还是只描述统计结构？

### 6. John Stuart Mill — *On Liberty*

- **首次出版：** 1859。
- **推荐语言：** 两者皆可；英文句子较长，但核心术语值得核对。
- **权威/合法全文：** [Project Gutenberg #34901](https://www.gutenberg.org/ebooks/34901)〔公版库；已验证 200〕；本地已保存 [EPUB](./mill_on_liberty_gutenberg_34901.epub)。[^3]
- **中文译本：** 《论自由》，许宝骙译，商务印书馆“汉译世界学术名著丛书”，多次重印，是常见基准译本；可用 [WorldCat](https://search.worldcat.org/search?q=%E8%AE%BA%E8%87%AA%E7%94%B1+%E8%AE%B8%E5%AE%9D%E9%AA%99) 查馆藏。
- **辅助材料：** [SEP: John Stuart Mill](https://plato.stanford.edu/entries/mill/)〔哲学百科；已验证 200〕。
- **难度/顺序/方式：** 2/5；总顺序 6；**第 1–3 章精读，第 4–5 章选读**。
- **第一次最值得问：** ① “伤害原则”怎样区分自涉与涉他行为？② 言论自由的论证是否仍适用于算法推荐和平台治理？③ 个性发展为什么不仅是私人偏好，也具有社会价值？

### 7. Thomas S. Kuhn — *The Structure of Scientific Revolutions*

- **首次出版：** 1962；第二版 1970 增补 Postscript；第四版/50 周年版 2012 有 Ian Hacking 导言。
- **推荐语言：** 两者皆可；重点核对 paradigm、normal science、incommensurability。
- **官方页：** [University of Chicago Press, 50th Anniversary Edition](https://press.uchicago.edu/ucp/books/book/chicago/S/bo13179781.html)〔大学出版社；已验证 200〕。
- **合法免费完整版：** **未找到合法免费完整版。** [Internet Archive 1962 版](https://archive.org/details/structureofscie00kuhn)〔受控借阅；已验证 200，`restricted=true`〕。
- **中文译本：** 《科学革命的结构》（第四版），金吾伦、胡新和译，北京大学出版社，2012，ISBN 9787301214268；[WorldCat ISBN 检索](https://search.worldcat.org/search?q=bn%3A9787301214268) 已验证可打开。不要使用网上流传的未授权 PDF。
- **辅助材料：** [SEP: Thomas Kuhn](https://plato.stanford.edu/entries/thomas-kuhn/)〔已验证 200〕；先读原书后再读 Hacking 导言，避免导言替代原文。
- **难度/顺序/方式：** 4/5；总顺序 7；**关键章精读、其余选读**。
- **第一次最值得问：** ① 范式是理论、范例、共同体实践，还是三者的组合？② 不可通约是否等于“无法比较”？③ 当代 AI 的 benchmark 驱动研究更像常规科学还是前范式研究？

## 第三阶段：社会、价值与技术

### 8. Aristotle — *Nicomachean Ethics*

- **首次出版：** 公元前 4 世纪的讲稿/编纂文本；现代意义的“首次出版年份”不适用。
- **推荐语言：** 两者皆可；重要段落以 Bekker 编号记录，便于跨版本定位。
- **权威原文/合法全文：** [Perseus Digital Library: Greek/English](https://www.perseus.tufts.edu/hopper/text?doc=Perseus:text:1999.01.0054)〔Tufts University 数字古典库；已验证 200〕；[Project Gutenberg #8438](https://www.gutenberg.org/ebooks/8438)〔公版英译；已验证 200〕；本地已保存 [EPUB](./aristotle_nicomachean_ethics_gutenberg_8438.epub)。[^4]
- **中文译本：** 《尼各马可伦理学》，廖申白译注，商务印书馆，是常见学术译注本；[对外经济贸易大学图书馆书目](https://opac.uibe.edu.cn/opac/book/2251c73f859f663c4b9fae77620a30a6) 可作馆藏核验。版次很多，购买时核对译者。
- **辅助材料：** [SEP: Aristotle’s Ethics](https://plato.stanford.edu/entries/aristotle-ethics/)〔已验证 200〕。
- **难度/顺序/方式：** 4/5；总顺序 8；**先导论，再精读 I、II、VI、X**。
- **第一次最值得问：** ① eudaimonia 是“快乐”、幸福，还是完整实现的生活？② 德性为何是习惯而不是规则清单？③ phronesis 与算法优化中的目标函数有什么根本差别？

### 9. Hannah Arendt — *The Human Condition*

- **首次出版：** 1958。
- **推荐语言：** 两者皆可；labor / work / action 建议始终保留英文对照。
- **官方页：** [University of Chicago Press, Second Edition](https://press.uchicago.edu/ucp/books/book/chicago/H/bo29137972.html)〔大学出版社；已验证 200〕。
- **合法免费完整版：** **未找到合法免费完整版。** [Internet Archive 1958 版](https://archive.org/details/humancondition000aren)〔受控借阅；已验证 200，`restricted=true`〕。
- **中文译本：** 《人的境况》，王寅丽译，上海人民出版社，常见版本为 2009；[WorldCat 检索](https://search.worldcat.org/search?q=%E4%BA%BA%E7%9A%84%E5%A2%83%E5%86%B5+%E7%8E%8B%E5%AF%85%E4%B8%BD) 已验证可打开。
- **辅助材料：** [SEP: Hannah Arendt](https://plato.stanford.edu/entries/arendt/)〔已验证 200〕。
- **难度/顺序/方式：** 5/5；总顺序 9；**先读 SEP/导论，再选读，第二轮精读**。
- **第一次最值得问：** ① labor、work、action 为什么不能都译成一般的“劳动/活动”？② 自动化减少劳苦后，为何不自动带来自由？③ 公共世界和多元行动对数字平台意味着什么？

### 10. Karl Marx — *Capital: A Critique of Political Economy, Volume I*

- **首次出版：** 1867 德文第一版；1887 首个英文版。
- **推荐语言：** 两者皆可；以可靠中文译本为主，关键概念对照德/英术语。
- **原文/合法全文：** [Marxists Internet Archive: *Capital*, Vol. I](https://www.marxists.org/archive/marx/works/1867-c1/)〔专题档案；1887 英译为公版文本；已验证 200〕；[PDF](https://www.marxists.org/archive/marx/works/download/pdf/Capital-Volume-I.pdf) 已验证为 `application/pdf`，本地保存为 [Capital Volume I](./marx_capital_volume_i_1887_english.pdf)。[^5]
- **中文译本：** 人民出版社《资本论》第1卷，中共中央马克思恩格斯列宁斯大林著作编译局译，是中文学术引用的基准版本；常见单卷 2004 版 ISBN 9787010041155。建议通过高校馆藏或 [WorldCat 检索](https://search.worldcat.org/search?q=%E8%B5%84%E6%9C%AC%E8%AE%BA+%E7%AC%AC%E4%B8%80%E5%8D%B7+%E4%BA%BA%E6%B0%91%E5%87%BA%E7%89%88%E7%A4%BE) 获取，不用来源不明扫描版。
- **辅助材料：** [David Harvey, Reading Marx’s Capital](https://davidharvey.org/reading-capital/)〔作者公开课程；已验证 200〕；[SEP: Karl Marx](https://plato.stanford.edu/entries/marx/)〔已验证 200〕。
- **机器/自动化重点：** 先读第 1 章“商品”，第 10 章“工作日”，第 13–15 章协作、工场手工业、机器和大工业（不同译本章节编号应以目录为准），再读原始积累部分。
- **难度/顺序/方式：** 5/5；总顺序 10；**专题选读起步，长期精读**。
- **第一次最值得问：** ① 机器提高生产力时，为什么可能同时延长或强化劳动？② “价值”不是价格的同义词，那么它解释什么？③ 技术变迁的主动者是机器、资本家、工人还是制度关系？

### 11. Karl Marx — *Grundrisse: Foundations of the Critique of Political Economy (Rough Draft)*

- **写作/首次出版：** 手稿写于 1857–1858；德文首次完整出版于 1939–1941。Martin Nicolaus 英译本 1973。
- **推荐语言：** 两者皆可；这是笔记手稿，不要期待成书般线性。
- **官方/权威版本：** [Penguin Classics, Martin Nicolaus trans.](https://www.penguin.co.uk/books/35199/grundrisse-by-karl-marx-translated-with-a-foreword-by-martin-nicolaus/9780140445756)〔出版社；已验证 200〕。
- **合法免费完整版：** 英译本受版权保护，**未找到合法免费完整版**。[Internet Archive: Nicolaus translation](https://archive.org/details/grundrissefounda0000marx)〔受控借阅；已验证 200，`restricted=true`〕。[MIA HTML](https://www.marxists.org/archive/marx/works/1857/grundrisse/) 虽可访问（已验证 200），未见清晰开放许可，故不下载、不作为“合法免费完整版”推荐。
- **中文译本：** 优先人民出版社《马克思恩格斯全集》第46卷（上、下）所收《1857—1858年经济学手稿》；具体印次未确认。不要只找网上被截出的“机器论片段”。
- **机器/一般智力重点：** Nicolaus 英译约 pp. 690–712，常称 “Fragment on Machines”；搜索章节标题/首句并结合前后的固定资本讨论。`general intellect` 只出现于紧凑语境，不能直接等同于互联网、AI 或“集体智慧”。
- **辅助材料：** [SEP: Karl Marx](https://plato.stanford.edu/entries/marx/)；Harvey 课程用于先建立《资本论》的概念背景，不能替代 Grundrisse 原段落。
- **难度/顺序/方式：** 5/5；总顺序 11；**先读导论与片段，再回到完整手稿**。
- **第一次最值得问：** ① 固定资本吸收社会知识后，劳动时间作为财富尺度为何出现张力？② `general intellect` 是人的能力、社会关系还是机器系统？③ 手稿中的预测与分析应如何区分？

## AI/数学/计算机基础

这条轨道与人文主线并行。每周可安排两次 60–90 分钟：一次推导，一次做题。技术教材的“读过”标准不是翻页，而是能独立重做定义后的一个证明或习题。

### 12. Stephen Boyd & Lieven Vandenberghe — *Convex Optimization*

- **首次出版：** 2004，Cambridge University Press。
- **推荐语言：** **英文优先**，中文用于难段辅助。
- **作者官方页/合法免费全文：** [Stanford 作者课程书页](https://web.stanford.edu/~boyd/cvxbook/)〔作者/大学；已验证 200〕；[完整 PDF](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)〔作者公开；已验证 200，约 6.9 MB〕；本地已保存 [PDF](./boyd_vandenberghe_convex_optimization.pdf)。[^6]
- **中文译本：** 《凸优化》，王书宁、许鋆、黄晓霖译，清华大学出版社，常见版本 2013，ISBN 9787302297567；[WorldCat ISBN 检索](https://search.worldcat.org/search?q=bn%3A9787302297567) 已验证可打开。
- **辅助材料：** [Stanford EE364a](https://web.stanford.edu/class/ee364a/)〔大学课程、讲义与作业；已验证 200〕。
- **难度/顺序/方式：** 4/5；技术轨道先修线性代数、多元微积分；**第 2–5 章精读并做题，其余按研究需要选读**。
- **第一次最值得问：** ① 凸性究竟给全局最优与可计算性带来什么保证？② 对偶变量为什么可解释为敏感度/影子价格？③ 一个机器学习目标何时只是“写起来像凸”，实际并不凸？

### 13. Thomas M. Cover & Joy A. Thomas — *Elements of Information Theory*

- **首次出版：** 1991；第二版 2006。
- **推荐语言：** 两者皆可，英文优先统一术语。
- **官方页：** [Wiley, 2nd Edition](https://www.wiley.com/en-us/Elements+of+Information+Theory%2C+2nd+Edition-p-9780471241959)〔出版社；已验证 200〕。
- **合法免费完整版：** **未找到合法免费完整版。** [Internet Archive 1991 版](https://archive.org/details/elementsofinform0000cove)〔受控借阅；已验证 200，`restricted=true`〕。
- **中文译本：** 《信息论基础（原书第2版）》，阮吉寿、张华译，机械工业出版社，常见 ISBN 9787111220404；[WorldCat ISBN 检索](https://search.worldcat.org/search?q=bn%3A9787111220404) 已验证可打开。
- **辅助材料：** [MIT OCW 6.441 Information Theory](https://ocw.mit.edu/courses/6-441-information-theory-spring-2010/)〔公开课；已验证 200〕；[Stanford EE376A](https://web.stanford.edu/class/ee376a/)〔课程页；已验证 200〕。
- **难度/顺序/方式：** 4/5；先修概率论；**第 2、3、7、8 章优先精读并做题**。
- **第一次最值得问：** ① 熵为何是对数形式，它度量的不是哪种“意义”？② 典型集如何把概率论变成编码定理？③ 互信息在表示学习中被使用时，哪些条件常被忽略？

## 每本书的资源与入口

### 快速总表

| # | 文本 | 免费完整原文 | 合法借阅/购买 | 建议方式 | 难度 |
|---:|---|---|---|---|---:|
| 1 | Turing, “Computing Machinery and Intelligence” | 未找到明确开放许可的官方完整版 | OUP DOI / JSTOR | 精读 | 3 |
| 2 | *Notes from Underground* | Gutenberg；本地 EPUB | 多种现代译本 | 精读 | 2 |
| 3 | Borges 两篇 | 未找到 | PRH / IA 受控借阅 | 精读 | 2 |
| 4 | *The Sciences of the Artificial* | 未找到 | MIT Press / IA 受控借阅 | 先选读 | 3 |
| 5 | *The Human Use of Human Beings* | 未找到 | IA 受控借阅 | 先选读 | 3 |
| 6 | *On Liberty* | Gutenberg；本地 EPUB | 多种现代译本 | 关键章精读 | 2 |
| 7 | *The Structure of Scientific Revolutions* | 未找到 | Chicago / IA 受控借阅 | 关键章精读 | 4 |
| 8 | *Nicomachean Ethics* | Perseus / Gutenberg；本地 EPUB | 现代译注本 | 先导论 | 4 |
| 9 | *The Human Condition* | 未找到 | Chicago / IA 受控借阅 | 先导论 | 5 |
| 10 | *Capital, Vol. I* | 1887 公版英译；本地 PDF | 人民出版社中译 | 专题选读→长期精读 | 5 |
| 11 | *Grundrisse* | 未找到明确许可的完整现代英译 | Penguin / IA 受控借阅 | 先片段与导论 | 5 |
| 12 | *Convex Optimization* | 作者公开 PDF；本地 PDF | CUP / 清华中译 | 精读做题 | 4 |
| 13 | *Elements of Information Theory* | 未找到 | Wiley / IA 受控借阅 | 精读做题 | 4 |

### 本地合法公开文件

| 本地文件 | 来源与许可判断 | SHA-256 |
|---|---|---|
| `aristotle_nicomachean_ethics_gutenberg_8438.epub` | Project Gutenberg 公版英译 | `ABAAD0F5550E0DDBD03C5DA268DB78544C01A47D75EBC49F6EB87517E63E7748` |
| `mill_on_liberty_gutenberg_34901.epub` | Project Gutenberg 公版 | `743308C0CFFBFF91EADDFD29B70A0CAD5F615F54759808CCA21129582748DD10` |
| `dostoevsky_notes_from_underground_gutenberg_600.epub` | Project Gutenberg 公版 Garnett 英译 | `2F96EE7E1AA2A7DD3DD9815F5D517150777013C0B643D0E7857F69DAE3468AC8` |
| `marx_capital_volume_i_1887_english.pdf` | 1887 公版英译，MIA 托管 | `279C2D870A1B76C8944748B77052E3E492DEF7CA17F8AAD60385B211B5BDC6D5` |
| `boyd_vandenberghe_convex_optimization.pdf` | 作者在 Stanford 课程书页明确公开 | `40D976C83C18CCE1900EFF8C41BD5AD408C102B813AF39D05FF85678CCF8D76E` |

没有因为“网上能搜到”就保存 Turing、Simon、Kuhn 或 Wiener 的扫描件；以后确认许可的文件也直接保存在当前文件夹。

## 未来补充阅读

只补四项，并在当前路径稳定运行后再加入：

1. Claude E. Shannon, “A Mathematical Theory of Communication” (1948)：接在 Cover–Thomas 之前，直接看信息论如何从原论文生长出来。
2. Joseph Weizenbaum, *Computer Power and Human Reason* (1976)：接 Wiener 与 Arendt，讨论可计算与应当计算的边界。
3. Judea Pearl, *Causality* (2000)：概率、干预与解释的长期技术基础；先有概率论和线性代数再读。
4. Elinor Ostrom, *Governing the Commons* (1990)：给平台、公共资源和制度设计提供不同于“国家/市场二选一”的框架。

不要现在就把它们加入“待读总量”。当主路径至少完成 Turing、Dostoevsky、Borges、Simon、Mill，以及技术轨道任一教材的两个章节后，再选一项。

## 来源与核验记录

[^1]: A. M. Turing, “Computing Machinery and Intelligence,” *Mind*, Vol. LIX, No. 236 (1950), pp. 433–460, [DOI](https://doi.org/10.1093/mind/LIX.236.433); [JSTOR 2251299](https://www.jstor.org/stable/2251299).
[^2]: Project Gutenberg, [*Notes from the Underground*, eBook #600](https://www.gutenberg.org/ebooks/600). 页面和 EPUB 直链于 2026-09-12 验证为 200。
[^3]: Project Gutenberg, [*On Liberty*, eBook #34901](https://www.gutenberg.org/ebooks/34901). 页面和 EPUB 直链于 2026-09-12 验证为 200。
[^4]: Perseus Digital Library, [Aristotle, *Nicomachean Ethics*](https://www.perseus.tufts.edu/hopper/text?doc=Perseus:text:1999.01.0054); Project Gutenberg, [eBook #8438](https://www.gutenberg.org/ebooks/8438).
[^5]: Karl Marx, [*Capital*, Volume I](https://www.marxists.org/archive/marx/works/1867-c1/), 1887 English edition, Marxists Internet Archive. HTML 与 PDF 直链于 2026-09-12 验证为 200。
[^6]: Stephen Boyd and Lieven Vandenberghe, [*Convex Optimization* official book page](https://web.stanford.edu/~boyd/cvxbook/), Stanford University; [complete PDF](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf). 两者于 2026-09-12 验证为 200。

主要机构来源还包括：MIT Press（Simon）、University of Chicago Press（Kuhn、Arendt）、Wiley（Cover–Thomas）、Penguin（Marx *Grundrisse*）、Penguin Random House（Borges）、Stanford Encyclopedia of Philosophy、MIT OpenCourseWare、Stanford 课程页、Internet Archive 受控借阅元数据和 WorldCat 馆藏检索。Internet Archive 借阅条目的 `restricted=true` 已逐项通过公开 metadata API 复核。
