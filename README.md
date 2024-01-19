<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://github.com/nuclio/nuclio/actions/workflows/periodic.yaml"><img src="https://github.com/nuclio/nuclio/actions/workflows/periodic.yaml/badge.svg?branch=development" alt="定期" style="max-width: 100%;"></a>
<a href="https://nuclio.readthedocs.io/en/latest/?badge=latest" rel="nofollow"><img src="https://camo.githubusercontent.com/1d9e8eb7f05bd72e83395f072eb80554a1e36d1fdfb9921a998dbf9994bc482e/68747470733a2f2f72656164746865646f63732e6f72672f70726f6a656374732f6e75636c696f2f62616467652f3f76657273696f6e3d6c6174657374" alt="文件状态" data-canonical-src="https://readthedocs.org/projects/nuclio/badge/?version=latest" style="max-width: 100%;"></a>
<a href="https://goreportcard.com/report/github.com/nuclio/nuclio" rel="nofollow"><img src="https://camo.githubusercontent.com/15b6557d162af50143fd04366015e07088eeff41d40721b2dfa8c39a452a0226/68747470733a2f2f676f7265706f7274636172642e636f6d2f62616467652f6769746875622e636f6d2f6e75636c696f2f6e75636c696f" alt="去报告卡" data-canonical-src="https://goreportcard.com/badge/github.com/nuclio/nuclio" style="max-width: 100%;"></a>
<a href="https://nuclio-io.slack.com" rel="nofollow"><img src="https://camo.githubusercontent.com/5530b6871d92c6c59c686eeda9e80cfbfed56b207e706144c4dd56937a2aaaab/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f736c61636b2d636861742d626c756576696f6c65742e7376673f6c6162656c3d536c61636b266c6f676f3d736c61636b" alt="松弛" data-canonical-src="https://img.shields.io/badge/slack-chat-blueviolet.svg?label=Slack&amp;logo=slack" style="max-width: 100%;"></a>
<a href="https://artifacthub.io/packages/search?repo=nuclio" rel="nofollow"><img src="https://camo.githubusercontent.com/e8a24c658efeba047d59c6ead289dc20a0384db68a5f096c0b3fed95c4f217e5/68747470733a2f2f696d672e736869656c64732e696f2f656e64706f696e743f75726c3d68747470733a2f2f61727469666163746875622e696f2f62616467652f7265706f7369746f72792f6e75636c696f" alt="神器中心" data-canonical-src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/nuclio" style="max-width: 100%;"></a>
<a href="https://www.iguazio.com/careers" rel="nofollow"><img src="https://camo.githubusercontent.com/30a44305058e41c38a9c70e6ae6eb175260bebab5fad71bc4bbae21507f9b9e5/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636172656572732d5765277265253230486972696e67212d696e666f726d6174696f6e616c3f7374796c653d7371756172652d666c61742d737175617265" alt="伊瓜齐奥职业生涯" data-canonical-src="https://img.shields.io/badge/careers-We're%20Hiring!-informational?style=square-flat-square" style="max-width: 100%;"></a></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer" href="/nuclio/nuclio/blob/development/docs/assets/images/logo.png"><img src="/nuclio/nuclio/raw/development/docs/assets/images/logo.png" width="180" alt="努克利奥" style="max-width: 100%;"></a></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-nuclio---serverless-framework-for-real-time-events-and-data-processing" class="anchor" aria-hidden="true" tabindex="-1" href="#nuclio---serverless-framework-for-real-time-events-and-data-processing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio - 用于实时事件和数据处理的“无服务器”框架</font></font></h1>
<h2 tabindex="-1" dir="auto"><a id="user-content-in-this-document" class="anchor" aria-hidden="true" tabindex="-1" href="#in-this-document"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在本文档中</font></font></h2>
<ul dir="auto">
<li><a href="#overview"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述</font></font></a></li>
<li><a href="#why-another-serverless-project"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么另一个“无服务器”项目？</font></font></a></li>
<li><a href="#quick-start-steps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速启动步骤</font></font></a></li>
<li><a href="#how-it-works"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">怎么运行的</font></font></a></li>
<li><a href="#function-examples"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能示例</font></font></a></li>
<li><a href="#further-reading"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进一步阅读</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">翻译：</font></font></p>
<ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/README_zh.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">简体中文</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-overview" class="anchor" aria-hidden="true" tabindex="-1" href="#overview"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio 是一个高性能“无服务器”框架，专注于数据、I/O 和计算密集型工作负载。</font><font style="vertical-align: inherit;">它与流行的数据科学工具很好地集成，例如</font></font><a href="https://jupyter.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Jupyter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://www.kubeflow.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubeflow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">；</font><font style="vertical-align: inherit;">支持多种数据和流媒体源；</font><font style="vertical-align: inherit;">并支持通过 CPU 和 GPU 执行。</font><font style="vertical-align: inherit;">Nuclio项目于2017年启动，并不断快速发展；</font><font style="vertical-align: inherit;">许多初创企业和企业现在都在生产中使用 Nuclio。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://kubernetes.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以将 Nuclio 用作独立的 Docker 容器或在现有Kubernetes</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集群之上使用</font><font style="vertical-align: inherit;">；</font><font style="vertical-align: inherit;">请参阅 Nuclio 文档中的部署说明。</font></font><a href="https://www.iguazio.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以通过Iguazio 数据科学平台</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中完全托管的应用程序服务（在云端或本地）使用 Nuclio </font><font style="vertical-align: inherit;">，您可以</font></font><a href="https://go.iguazio.com/start-your-free-trial" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免费试用</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您希望通过代码创建和管理 Nuclio 函数（例如，从 Jupyter Notebook 中），请参阅</font></font><a href="https://github.com/nuclio/nuclio-jupyter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio Jupyter 项目</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，该项目提供一个 Python 包和 SDK，用于从 Jupyter Notebook 创建和部署 Nuclio 函数。</font><font style="vertical-align: inherit;">Nuclio 也是用于数据科学自动化和跟踪的</font><font style="vertical-align: inherit;">新开源</font></font><a href="https://github.com/mlrun/mlrun"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MLRun库以及用于构建和部署可移植、可扩展的 ML 工作流程的开源</font></font></a><font style="vertical-align: inherit;"></font><a href="https://www.kubeflow.org/docs/components/pipelines/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubeflow Pipelines</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">框架的组成部分。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio 速度极快：单个函数实例每秒可以处理数十万个 HTTP 请求或数据记录。</font><font style="vertical-align: inherit;">这比其他一些框架快 10-100 倍。</font><font style="vertical-align: inherit;">要了解有关 Nuclio 工作原理的更多信息，请参阅 Nuclio</font></font><a href="/nuclio/nuclio/blob/development/docs/concepts/architecture.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">架构文档、阅读</font></font></a><font style="vertical-align: inherit;"></font><a href="https://theburningmonk.com/2019/04/comparing-nuclio-and-aws-lambda/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio 与 AWS Lambda</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的评论</font><font style="vertical-align: inherit;">，或观看</font></font><a href="https://www.youtube.com/watch?v=pTCx569Kd4A" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio 无服务器和 AI 网络研讨会</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="https://nuclio.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在Nuclio 网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上找到其他文章和教程的链接</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/GoogleContainerTools/kaniko"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio 是安全的：Nuclio 与Kaniko</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集成，</font><font style="vertical-align: inherit;">允许在运行时以安全且可用于生产的方式构建 Docker 映像。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如需更多问题和支持，</font></font><a href="https://lit-oasis-83353.herokuapp.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请单击加入</font></font></a><font style="vertical-align: inherit;"></font><a href="https://nuclio-io.slack.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio Slack</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作</font><font style="vertical-align: inherit;">区。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-why-another-serverless-project" class="anchor" aria-hidden="true" tabindex="-1" href="#why-another-serverless-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为什么另一个“无服务器”项目？</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现有的云和开源无服务器解决方案都无法满足无服务器框架的所有所需功能：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以最小的 CPU/GPU 和 I/O 开销以及最大的并行度进行实时处理</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与各种数据源、触发器、处理模型和 ML 框架的本机集成</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有数据路径加速功能的有状态函数</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">跨低功耗设备、笔记本电脑、边缘和本地集群以及公共云的可移植性</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开源但专为企业设计（包括日志记录、监控、安全性和可用性）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio 的创建就是为了满足这些要求。</font><font style="vertical-align: inherit;">它被有意设计为一个可扩展的开源框架，使用模块化和分层的方法，支持不断添加触发器和运行时，希望许多人能够加入到为 Nuclio 开发新模块、开发人员工具和平台的努力中。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-quick-start-steps" class="anchor" aria-hidden="true" tabindex="-1" href="#quick-start-steps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速启动步骤</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">探索 Nuclio 最简单的方法是运行 Nuclio 仪表板的图形用户界面 (GUI)。</font><font style="vertical-align: inherit;">运行仪表板所需的只是 Docker：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run -p 8070:8070 -v /var/run/docker.sock:/var/run/docker.sock --name nuclio-dashboard quay.io/nuclio/dashboard:stable-amd64</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -p 8070:8070 -v /var/run/docker.sock:/var/run/docker.sock --name nuclio-dashboard quay.io/nuclio/dashboard:stable-amd64" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/nuclio/nuclio/blob/development/docs/assets/images/dashboard.png"><img src="/nuclio/nuclio/raw/development/docs/assets/images/dashboard.png" alt="仪表板" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">浏览到</font></font><a href="http://localhost:8070" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://localhost:8070</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，创建一个项目并添加一个函数。</font><font style="vertical-align: inherit;">当在编排平台（例如 Kubernetes）外部运行时，仪表板将简单地部署到本地 Docker 守护进程。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">假设您正在使用 Docker 运行 Nuclio，作为示例，创建一个项目并部署预先存在的模板“dates (nodejs)”。</font><font style="vertical-align: inherit;">使用</font></font><code>docker ps</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您应该看到该函数已部署在其自己的容器中。</font><font style="vertical-align: inherit;">然后您可以使用curl调用您的函数；</font></font><code>docker ps</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（使用Nuclio 仪表板</font><font style="vertical-align: inherit;">检查端口号是否正确）：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>curl -X POST -H <span class="pl-s"><span class="pl-pds">"</span>Content-Type: application/text<span class="pl-pds">"</span></span> -d <span class="pl-s"><span class="pl-pds">'</span>{"value":2,"unit":"hours"}<span class="pl-pds">'</span></span> http://localhost:37975</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="curl -X POST -H &quot;Content-Type: application/text&quot; -d '{&quot;value&quot;:2,&quot;unit&quot;:&quot;hours&quot;}' http://localhost:37975" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如需通过仪表板 UI 或 Nuclio 命令行界面 ( ) 在 Kubernetes 上使用 Nuclio 的完整分步指南</font></font><code>nuctl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，请探索以下学习途径：</font></font></p>
<ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/docs/setup/k8s/getting-started-k8s.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubernetes 上的 Nuclio 入门</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/setup/gke/getting-started-gke.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google Kubernetes Engine (GKE) 上的 Nuclio 入门</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/setup/aks/getting-started-aks.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Azure 容器服务 (AKS) 上的 Nuclio 入门</font></font></a></li>
<li><a href="https://katacoda.com/javajon/courses/kubernetes-serverless/nuclio" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实际操作 Kubernetes 沙箱和 Nuclio 指导说明，在 Katacoda 上免费</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-how-it-works" class="anchor" aria-hidden="true" tabindex="-1" href="#how-it-works"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">怎么运行的</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“当这种情况发生时，就这样做”。</font><font style="vertical-align: inherit;">Nuclio 试图抽象出围绕发生的事件（例如，一条记录写入 Kafka、发出 HTTP 请求、计时器到期）的所有支架，并将该信息传递给一段代码进行处理。</font><font style="vertical-align: inherit;">为此，Nuclio 希望用户（至少）提供有关什么可以触发事件以及此类事件发生时要运行的代码的信息。</font><font style="vertical-align: inherit;">用户通过命令行实用程序 ( </font></font><code>nuctl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">)、REST API 或通过 Web 应用程序直观地向 Nuclio 提供此信息。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/nuclio/nuclio/blob/development/docs/assets/images/architecture-3.png"><img src="/nuclio/nuclio/raw/development/docs/assets/images/architecture-3.png" alt="建筑学" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio 获取此信息（即 function</font></font><code>handler</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和 function </font></font><code>configuration</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）并将其发送给构建器。</font><font style="vertical-align: inherit;">该构建器将制作函数的容器映像，其中包含用户的处理程序和一个软件，该软件可以在收到事件时执行该处理程序（稍后会详细介绍）。</font><font style="vertical-align: inherit;">然后，构建器将通过将其推送到容器注册表来“发布”该容器映像。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布后，即可部署功能容器镜像。</font><font style="vertical-align: inherit;">部署者将从功能的配置中制作编排器特定的配置。</font><font style="vertical-align: inherit;">例如，如果部署到 Kubernetes，部署程序将获取配置参数，例如副本数量、自动缩放计时参数、函数请求的 GPU 数量，并将其转换为 Kubernetes 资源配置（即部署、服务、入口等）。</font></font></p>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：部署者不会直接创建 Kubernetes 本机资源，而是创建“NuclioFunction”自定义资源 (CRD)。</font><font style="vertical-align: inherit;">称为“控制器”的 Nuclio 服务侦听 NuclioFunction CRD 上的更改，并创建/修改/销毁适用的 Kubernetes 本机资源（部署、服务等）。</font><font style="vertical-align: inherit;">这遵循标准 Kubernetes 运算符模式</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，编排器将从已发布的容器映像中启动容器并执行它们，为它们提供功能配置。</font><font style="vertical-align: inherit;">这些容器的入口点是“处理器”，负责读取配置、监听事件触发器（例如连接到Kafka、监听HTTP）、在事件发生时读取事件并调用用户的处理程序。</font><font style="vertical-align: inherit;">处理器负责许多其他事情，包括处理指标、整理响应、优雅地处理崩溃等。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-scaling-to-zero" class="anchor" aria-hidden="true" tabindex="-1" href="#scaling-to-zero"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">缩放至零</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一旦构建并部署到 Kubernetes 这样的编排器，Nuclio 函数（即处理器）就可以处理事件、根据性能指标进行扩展和缩减、发送日志和指标 - 所有这些都无需任何外部实体的帮助。</font><font style="vertical-align: inherit;">部署后，您可以终止 Nuclio 仪表板和控制器服务，Nuclio 功能仍将完美运行和扩展。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然而，缩放到零并不是他们自己能够做到的。</font><font style="vertical-align: inherit;">相反，一旦缩放到零，当新事件到达时，Nuclio 函数就无法自行扩展。</font><font style="vertical-align: inherit;">为此，Nuclio 提供了“Scaler”服务。</font><font style="vertical-align: inherit;">这处理了缩放到零，更重要的是从零缩放的所有问题。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-function-examples" class="anchor" aria-hidden="true" tabindex="-1" href="#function-examples"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能示例</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下示例函数实现使用</font></font><code>Event</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>Context</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口来处理输入和日志，返回结构化 HTTP 响应；</font><font style="vertical-align: inherit;">（也可以使用简单的字符串作为返回值）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在围棋中</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> handler

<span class="pl-k">import</span> (
    <span class="pl-s">"github.com/nuclio/nuclio-sdk-go"</span>
)

<span class="pl-k">func</span> <span class="pl-en">Handler</span>(<span class="pl-s1">context</span> <span class="pl-c1">*</span>nuclio.<span class="pl-smi">Context</span>, <span class="pl-s1">event</span> nuclio.<span class="pl-smi">Event</span>) (<span class="pl-k">interface</span>{}, <span class="pl-smi">error</span>) {
    <span class="pl-s1">context</span>.<span class="pl-c1">Logger</span>.<span class="pl-en">Info</span>(<span class="pl-s">"Request received: %s"</span>, <span class="pl-s1">event</span>.<span class="pl-en">GetPath</span>())

    <span class="pl-k">return</span> nuclio.<span class="pl-smi">Response</span>{
        <span class="pl-c1">StatusCode</span>:  <span class="pl-c1">200</span>,
        <span class="pl-c1">ContentType</span>: <span class="pl-s">"application/text"</span>,
        <span class="pl-c1">Body</span>: []<span class="pl-smi">byte</span>(<span class="pl-s">"Response from handler"</span>),
    }, <span class="pl-c1">nil</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package handler

import (
    &quot;github.com/nuclio/nuclio-sdk-go&quot;
)

func Handler(context *nuclio.Context, event nuclio.Event) (interface{}, error) {
    context.Logger.Info(&quot;Request received: %s&quot;, event.GetPath())

    return nuclio.Response{
        StatusCode:  200,
        ContentType: &quot;application/text&quot;,
        Body: []byte(&quot;Response from handler&quot;),
    }, nil
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在Python中</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">def</span> <span class="pl-en">handler</span>(<span class="pl-s1">context</span>, <span class="pl-s1">event</span>):
    <span class="pl-s1">response_body</span> <span class="pl-c1">=</span> <span class="pl-s">f'Got <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">event</span>.<span class="pl-s1">method</span><span class="pl-kos">}</span></span> to <span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">event</span>.<span class="pl-s1">path</span><span class="pl-kos">}</span></span> with "<span class="pl-s1"><span class="pl-kos">{</span><span class="pl-s1">event</span>.<span class="pl-s1">body</span><span class="pl-kos">}</span></span>"'</span>

    <span class="pl-c"># log with debug severity</span>
    <span class="pl-s1">context</span>.<span class="pl-s1">logger</span>.<span class="pl-en">debug</span>(<span class="pl-s">'This is a debug level message'</span>)

    <span class="pl-c"># just return a response instance</span>
    <span class="pl-k">return</span> <span class="pl-s1">context</span>.<span class="pl-v">Response</span>(<span class="pl-s1">body</span><span class="pl-c1">=</span><span class="pl-s1">response_body</span>,
                            <span class="pl-s1">headers</span><span class="pl-c1">=</span><span class="pl-c1">None</span>,
                            <span class="pl-s1">content_type</span><span class="pl-c1">=</span><span class="pl-s">'text/plain'</span>,
                            <span class="pl-s1">status_code</span><span class="pl-c1">=</span><span class="pl-c1">201</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="def handler(context, event):
    response_body = f'Got {event.method} to {event.path} with &quot;{event.body}&quot;'

    # log with debug severity
    context.logger.debug('This is a debug level message')

    # just return a response instance
    return context.Response(body=response_body,
                            headers=None,
                            content_type='text/plain',
                            status_code=201)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><strong><a href="/nuclio/nuclio/blob/development/docs/examples/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多示例可以在示例页面</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中找到</font><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-further-reading" class="anchor" aria-hidden="true" tabindex="-1" href="#further-reading"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进一步阅读</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置
</font></font><ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/docs/setup/docker/getting-started-docker.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Docker 上的 Nuclio 入门</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/setup/minikube/getting-started-minikube.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Minikube 上的 Nuclio 入门</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/setup/k8s/getting-started-k8s.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kubernetes 上的 Nuclio 入门</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/setup/aks/getting-started-aks.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Azure Kubernetes 服务 (AKS) 上的 Nuclio 入门</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/setup/gke/getting-started-gke.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Google Kubernetes Engine (GKE) 上的 Nuclio 入门</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Raspberry Pi 上开始使用 Nuclio（即将推出）</font></font></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任务
</font></font><ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/docs/tasks/deploying-functions.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署功能</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/tasks/deploy-functions-from-dockerfile.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 Dockerfile 部署函数</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/tasks/deploying-pre-built-functions.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部署预建功能</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/tasks/configuring-a-platform.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置平台</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概念
</font></font><ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/docs/concepts/best-practices-and-common-pitfalls.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最佳实践和常见陷阱</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/concepts/architecture.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建筑学</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库伯内斯
</font></font><ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/docs/concepts/k8s/function-ingress.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Kubernetes Ingress 按名称调用函数</font></font></a></li>
</ul>
</li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参考
</font></font><ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/docs/reference/nuctl/nuctl.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">努特尔</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/reference/function-configuration/function-configuration-reference.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能配置参考</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/reference/triggers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">触发器</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/reference/runtimes/dotnetcore/writing-a-dotnetcore-function.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行时-.NET Core 7.0</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/reference/runtimes/shell/shell-reference.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行时 - 外壳</font></font></a></li>
</ul>
</li>
<li><a href="/nuclio/nuclio/blob/development/docs/examples/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">沙盒
</font></font><ul dir="auto">
<li><a href="https://katacoda.com/javajon/courses/kubernetes-serverless/nuclio" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 Nuclio 并运行函数。</font><font style="vertical-align: inherit;">在免费的 Kubernetes 集群上探索和实验。</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献
</font></font><ul dir="auto">
<li><a href="/nuclio/nuclio/blob/development/docs/devel/coding-conventions.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码约定</font></font></a></li>
<li><a href="/nuclio/nuclio/blob/development/docs/devel/contributing.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 Nuclio 做出贡献</font></font></a></li>
</ul>
</li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">媒体
</font></font><ul dir="auto">
<li><a href="https://www.slideshare.net/iguazio/running-highspeed-serverless-with-nuclio" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 nuclio 运行高速无服务器（幻灯片）</font></font></a></li>
<li><a href="https://www.youtube.com/watch?v=pTCx569Kd4A" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CNCF 网络研讨会 – 无服务器和人工智能（视频）</font></font></a></li>
<li><a href="https://dzone.com/articles/tutorial-faster-ai-development-with-serverless" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用无服务器加快 AI 开发（教程）</font></font></a></li>
<li><a href="https://thenewstack.io/whats-next-serverless/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nuclio 和无服务器计算的未来（博客）</font></font></a></li>
<li><a href="https://hackernoon.com/nuclio-the-new-serverless-superhero-3aefe1854e9a" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nuclio：新的无服务器超级英雄（博客）</font></font></a></li>
<li><a href="https://www.rtinsights.com/serverless-framework-for-real-time-apps-emerges/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实时应用程序的无服务器框架出现（博客）</font></font></a></li>
</ul>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如需支持和其他产品信息，</font></font><a href="https://lit-oasis-83353.herokuapp.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请加入</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">活动的</font></font><a href="https://nuclio-io.slack.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nuclio Slack</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">工作区。</font></font></p>
</article></div>
