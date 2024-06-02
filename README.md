以下是 Repo 的目录结构：

```
.
├── README.md
├── docs
├── image
├── outline.md
├── slides.md
├── script.md
├── whisper
│   └── output
│       ├── large-v3
│       │   ├── fat-med-ts.txt
│       │   └── fat-med.txt
│       └── medium
│           ├── fat-med-ts.txt
│           └── fat-med.txt
└── wiki.md

7 directories, 8 files
```

其中:

- `docs` 目录存放我们需要参考的文献 (如果有的话), 或者其他一些资料
- `image` 目录存放我们需要在 Slides 中使用的图片
- `outline.md` 是我们的内容大纲
- `slides.md` 是我们的 Slides 源码 (依然使用 Marp 系统)
- `whisper` 目录存放的参考视频的 Whisper 转录文本 (便于利用 GPT 和快速查阅), 可以随时让我添加别的视频的转录文本
- `wiki.md` 是我们的 Wiki 文档, 里面依然是一个知识库
- `script.md` 是我们的讲稿
