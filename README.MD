# 从古诗文网获取诗词到Anki

## 使用

```
Usage: anki_chinese_poem_cards_generator.exe [OPTIONS] <URL>

Arguments:
  <URL>  需要爬取的古诗文网址，例如：https://www.gushiwen.cn/gushi/chuzhong.aspx

Options:
  -n, --name <NAME>          生成anki deck的名称
  -d, --desc <DESC>          生成anki deck的描述
  -f, --filename <FILENAME>  生成anki deck的文件名
  -t, --type <TYPE>          deck的类型（填空或正常，默认正常） [possible values: simple, cloze]
  -b, --bracket <BRACKET>    是否删除内容内的括号（默认删除<->true） [possible values: true, false]
  -w, --words <WORDS>        跳过长文依据字数（默认不跳过，可以用来跳过长文的填空）
  -h, --help                 Print help
  -V, --version              Print version
  ```
