# 👋 你好，欢迎来到我的数字空间

## 关于我 | About Me

我是 [智小骇]，一名坐标北京的「学术骇客」。

目前是中央民族大学（MUC）2023级统计学专业的本科生。不过，我更喜欢将自己定义为一个终身学习者和问题解决者。于我而言，统计学是理解世界不确定性的精妙语言，而代码则是将想法变为现实的魔法画笔。

我着迷于在数据、算法和模型之间寻找规律与洞见，并致力于探索**数据科学**、**深度学习**和**计算机编程**等领域。我相信，用技术驱动的好奇心，可以为世界带来一点点正向的改变。

这个小站是我记录学习、分享思考和展示项目的地方。希望我们能在这里相互启发，共同成长。

## 🚀 学术探索 | Academic & Skills

我的知识体系构建在数学的坚实基础上，并不断向计算机科学领域延伸。

- **主修专业:** 统计学 @ 中央民族大学 (2023 - 至今)
- **主攻领域:**
    - **数据科学:** 热衷于从海量数据中挖掘价值，探索其背后的商业与社会意义。
    - **深度学习:** 关注计算机视觉（CV）与生物信息学（Bioinformatics）的最新进展，对构建智能模型充满热情。
    - **计算机编程:** 享受用代码创造工具、解决复杂问题的过程。
    - **数学:** 痴迷于概率论、线性代数和微积分中的逻辑之美。

- **我的工具箱 (Toolbox):**
    - **编程语言:** Python, R, SQL
    - **框架与库:** Scikit-learn, TensorFlow, PyTorch, Pandas, NumPy
    - **其他工具:** Git, LaTeX, Generative AI
 
## 🎮 代码之外 | Beyond the Code

当我不与数据和算法为伴时，生活同样多姿多彩。

- **🏀 篮球是我的热爱之一。** 我是NBA金州勇士队的铁杆球迷，斯蒂芬·库里（Stephen Curry）是我心目中永远的MVP。他用三分球改变了篮球时代，这何尝不是一种“骇客精神”？

- **🧱 我是MC玩家。** 偶尔，我会在《我的世界》（Minecraft）里化身“创世神”，用一个个方块搭建属于自己的世界。那里是我的精神角落，能让创造力自由驰骋。

- **🎬 我也看番。** 在安静的时刻，一些~~抽象~~优秀的动漫作品能给我带来慰藉与思考。最近在追或很喜欢的有：
    - 《迷途之子》
    - 《孤独摇滚》
    - 《间谍过家家》
    - 《灵笼》

- **🕹️ 我也是《原神》和《崩坏·星穹铁道》的忠实玩家。** 喜欢原神中的**温迪**、**芙宁娜**、**队长**、**博士**；崩铁中最喜欢的角色是**银狼**、**乱破**、**螺丝咕姆**、**黑塔**、**阮·梅**。

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
