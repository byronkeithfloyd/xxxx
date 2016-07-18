## XXXX

你知道我在干嘛吗？

### Plan

2016年07月01号，开始啃一块硬骨头了。

1. 资料与工具
  * OllyDbg教程：http://wenku.baidu.com/view/3e33df235901020207409cf7.html
  * 看雪软件安全文档：http://www.pediy.com/kssd/
  * 汇编语言

### Tools
* [批量下载crossdomain.xml的脚本](tools/hunt.py)
* [从Burp Suite生成的请求文件生成CSRF表单](tools/generate_csrf_form.py)
* [Google搜索找URL跳转XSS](tools/xss_via_redirect.py)
    ```bash
    $ python xss_via_redirect.py edu.cn
    [INFO] Searching links
    [INFO] Finding XSS ...
    [Potential XSS vulnerability] http://xxxx.xxx.edu.cn/go.asp?url=java%5Cu0073cript%5Cu003a%5Cu0061lert%281%29%3B
    ```

### Leagal Disclaimer

Usage of my scripts for attacking targets without prior mutual consent is illegal. It is the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program.
