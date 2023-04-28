# OpenAI Playbook For Noobs

提供 OpenAI API 的简单例子。

* [使用 Embeddings 来提升 GPT 回答问题的能力](playbooks/embeddings.ipynb)
* [利用上下文来使 GPT 的回复遵循固定格式](playbooks/generate_text_with_pattern.ipynb)

其它文档正在逐步添加中。

如何使用：

```bash
rye init
rye sync
rye run jupyter-lab
```

或者使用 pip：

```bash
python -m venv .venv
source .venv/bin/activate
(venv) python -m pip install openai pandas tiktoken scipy jupyterlab ipykernel
(venv) jupyter-lab
```

* License: [WTFPL](LICENSE)
* Author: GUAN Xiaoyu
