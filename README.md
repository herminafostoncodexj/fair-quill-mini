# fair-quill-mini

Cloud engineer · AWS and CDK

处理日常小任务的工具

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 备注

就是给自己省点事，没做太多抽象。

## 安装

```bash
git clone https://github.com/USER/fair-quill-mini.git
cd fair-quill-mini
cargo build --release
```

## License

MIT
