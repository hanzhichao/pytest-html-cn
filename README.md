# pytest-html-cn
![Languate - Python](https://img.shields.io/badge/language-python-blue.svg)
![PyPI - License](https://img.shields.io/pypi/l/pytest-html-cn)
![PyPI](https://img.shields.io/pypi/v/pytest-html-cn)
![PyPI - Downloads](https://img.shields.io/pypi/dm/pytest-html-cn)

pytest-html中文版,用于pytest测试执行后，生成HTML测试报告。

## 安装方法
```shell
pip install pytest-html-cn
```
## 使用方式

**test_demo.py**
```python
def test_a():
    pass
    
def test_b():
    pass
```
使用方法
```shell
pytest test_demo.py --html=测试报告.html
```
生成报告如下

![pytest-html-cn](./docs/pytest-html-cn.png)
