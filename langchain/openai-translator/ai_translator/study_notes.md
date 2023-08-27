采用langchain 框架开发PDF翻译程序，通读代码输出过程笔记。

## 功能入口分为两种形式

1、可视化界面 

1.1、用户界面 gradio_server

1.2、接口服务 flask_server

2、命令行 
main.py

## 主要功能
``code``
|-- book

|   |-- book.py

|   |-- content.py

|   `-- page.py

|-- flask_server.py

|-- gradio_server.py

|-- main.py

|-- translator

|   |-- exceptions.py

|   |-- pdf_parser.py

|   |-- pdf_translator.py

|   |-- translation_chain.py

|   |-- translation_config.py

|   `-- writer.py
``code``


## 用户使用序列图
