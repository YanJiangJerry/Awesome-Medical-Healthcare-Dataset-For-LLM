# Awesome-Medical-Healthcare-Dataset-For-LLM
A curated list of popular Datasets, Models and Papers for LLMs in Medical/Healthcare.

## Datasets

| 数据集名称 | 内容概述 | 获取链接 | 数据大小 |
|------|------------|-----------------|-------------|
| MedDialog | MedDialog数据集（中文）包含了医生和患者之间的对话（中文）。它有110万个对话和400万个话语。数据还在不断增长，会有更多的对话加入。原始对话来自好大夫网。 | [下载链接](https://huggingface.co/datasets/medical_dialog) | 3.3GB |
|Chinese medical dialogue data 中文医疗对话数据集 | 数据中有六个科室的医学问答数据:<br/>**<Andriatria_男科>** 94596个问答对 **<IM_内科>** 220606个问答对 **<OAGD_妇产科>** 183751个问答对**<Oncology_肿瘤科>** 75553个问答对 **<Pediatric_儿科>** 101602个问答对 **<Surgical_外科>** 115991个问答对 总计 792099个问答对 | [下载链接](https://github.com/Toyhom/Chinese-medical-dialogue-data) | 800k 条，330MB |
| Huatuo-26M                        | Huatuo-26M 是迄今为止最大的中医问答数据集。该数据集包含超过2600万对高质量的医学问答对，涵盖疾病、症状、治疗和药物信息等广泛主题。                  | [下载链接](https://github.com/FreedomIntelligence/Huatuo-26M)            | 4.54GB |
| huatuo_encyclopedia_qa  | 该数据集共有364,420条医疗QA数据，其中一些数据以不同的方式包含多个问题。我们从纯文本(例如，医学百科全书和医学文章)中提取医学QA对。我们在中文维基百科上收集了8699个疾病百科条目和2736个药物百科条目。此外，我们还从钱文健康网站抓取了226432篇高质量的医学文章。| [下载链接](https://huggingface.co/datasets/FreedomIntelligence/huatuo_encyclopedia_qa) | 605MB |
| 中文医疗对话数据集(华佗项目) | 22万条中文医疗对话数据集(华佗项目)：FreedomIntelligence/HuatuoGPT-sft-data-v1 | [下载链接](https://huggingface.co/datasets/FreedomIntelligence/HuatuoGPT-sft-data-v1) | 333MB |
|医疗大模型数据集(包括预训练、指令微调和奖励数据集) | 240万条中文医疗数据集(包括预训练、指令微调和奖励数据集) | [下载链接](https://huggingface.co/datasets/shibing624/medical) | 2.1GB |
|外科问诊数据BillGPT/Chinese-medical-dialogue-data | 60.8K条外科问诊数据，示例："患者:新癀片有什么用,想问一下新癀片吃了有什么作用呀？ 医生:病情分析：您好：新癀片主要是可以清热解毒，活血化瘀，消肿止痛。用于热毒瘀血所致的咽喉肿痛、牙痛、痹痛、胁痛、黄疸、无名肿毒等症。指导意见：如果您有咽喉疼痛等症状服用效果是很好的，但是有胃炎的朋友尽量不要服用，有一定的胃肠反应，里面也含有对胃有刺激成分。" | [下载链接](https://huggingface.co/datasets/BillGPT/Chinese-medical-dialogue-data) | 936MB |
|中文医学指令精调/指令微调数据集(Instruct-tuning)| 采用了公开和自建的中文医学知识库，主要参考了cMeKG。 医学知识库围绕疾病、药物、检查指标等构建，字段包括并发症，高危因素，组织学检查，临床症状，药物治疗，辅助治疗等。利用GPT3.5接口围绕医学知识库构建问答数据，设置了多种Prompt形式来充分利用知识。 | [下载链接](https://github.com/SCIR-HI/Med-ChatGLM) | 7.6K条 |
|MeChat：中文心理健康支持对话大模型与数据集 | 数据集通过 ChatGPT 改写真实的心理互助 QA 为多轮的心理健康支持多轮对话（single-turn to multi-turn inclusive language expansion via ChatGPT），该数据集含有 56k 个多轮对话，其对话主题、词汇和篇章语义更加丰富多样，更加符合在长程多轮对话的应用场景。 | [下载链接](https://github.com/qiuhuachuan/smile) | 56k条 |
| CMB-Chinese Medical Benchmark |CMB是一个全方位多层次的中文医疗模型评估平台。它共包含280839道多项选择题和74例复杂病例问诊题，涵盖了所有医学临床工种和不同职业级别的考试，综合考察模型的医学知识和临床问诊能力 | [下载链接](https://github.com/FreedomIntelligence/CMB) | 30MB|
|ChatMed_Consult_Dataset  | ChatMed_Consult_Dataset 中的query(或者是prompt)来自于互联网上的医疗问诊问题(110,113)，反映了真实世界的不同用户/患者的医疗问诊需求。目前response都是由OpenAI GPT-3.5引擎回答的。我们后续会对互联网上的医生回答与患者回答进行筛选甄别，择优选择，构建质量更优的数据集。|  [下载链接](https://huggingface.co/datasets/michaelwzhu/ChatMed_Consult_Dataset)   | 395MB |
| 中医药指令数据集ChatMed_TCM_Dataset | 以开源的[中医药知识图谱] (https://github.com/ywjawmw/TCM_KG) 为基础，采用以实体为中心的自指令方法(entity-centric self-instruct)，调用ChatGPT得到11w+的围绕中医药的指令数据。 |  [下载链接](https://huggingface.co/datasets/michaelwzhu/ShenNong_TCM_Dataset) | 110MB |
| cMedQA中文社区医学问答数据集 |华人社区医疗问答的数据集，该数据集是1.0版本，提供方将不时更新和扩充数据库。为了保护隐私，数据是匿名的，不包括个人信息。| [下载链接](https://github.com/zhangsheng93/cMedQA2) | 80MB |
| WebMedQA 线上医学QA | WebMedQA是一个从百度医生和120Ask等在线健康咨询网站收集的真实中国医学问答数据集。用户首先填写个人信息表格，然后描述他们的疾病和健康问题。这些问题对所有注册的临床医生和用户开放，直到问题提出者选择最满意的答案并结束问题。医生和热心的用户可以在发布的问题下提供诊断和建议，他们的标题和专业与他们的答案一起显示。提问者也可以进一步询问他们是否对其中一个答案感兴趣。每个问题所属的类别也由其提出者选择。 | [下载链接](https://tianchi.aliyun.com/dataset/90202) | 75MB |
| ChineseBLUE基准 | ChineseBLUE基准由不同的带有语料库的生物医学文本挖掘任务组成。这些任务涵盖了各种文本类型(生物医学网络数据和临床笔记)、数据集大小和难度，更重要的是，突出了常见的生物医学文本挖掘挑战。 | [下载链接](https://github.com/CBLUEbenchmark/CBLUE) | 400MB |
| Yidu-S4K  | 命名实体识别,实体及属性抽取   | [下载链接](http://openkg.cn/dataset/yidu-s4k)     | 4K条 |
| Yidu-N7K  | 临床语标准化    | [下载链接](http://openkg.cn/dataset/yidu-n7k ) | 7K条 |
| HealthCareMagic-100k | 来自HealthCareMagic.com的10万次病人和医生之间的真实对话 | [下载链接](https://drive.google.com/file/d/1lyfqIwlLSClhgrCutWuEe_IACNq6XNUt/view?usp=sharing) |137MB|
| icliniq-10k | 来自icliniq.com网站的病人和医生之间的10K条真实对话 | [下载链接](https://drive.google.com/file/d/1ZKbqgYqWc7DJHs3N9TQYQVPdDQmZaClA/view) | 20MB |
| GenMedGPT-5k |5k从ChatGPT GenMedGPT-5k和疾病数据库中生成了患者和医生之间的对话。| [下载链接](https://drive.google.com/file/d/1nDTKZ3wZbZWTkFMBkxlamrzbNz0frugg/view?usp=sharing) | 5K条 |


## Models
| Title | Institute | Date | Code
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------: | :-----------: | :---------: |
|[DoctorGPT](https://huggingface.co/llSourcell/medllama2_7b) | Sirajraval, GPT School | 2023-08 | [Github](https://github.com/llSourcell/DoctorGPT) 
| [CoDoC: Enhancing the reliability and accuracy of AI-enabled diagnosis via complementarity-driven deferral to clinicians](https://www.nature.com/articles/s41591-023-02437-x) | DeepMind, Google <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:259939727?fields=citationCount&query=%24.citationCount&label=citations) | 2023-07 | [Github](https://github.com/deepmind/codoc/tree/main) <br> ![Star](https://img.shields.io/github/stars/deepmind/codoc?style=social&label=Stars)
| [Med-PaLM 2: Towards Expert-Level Medical Question Answering with Large Language Models](https://arxiv.org/pdf/2305.09617.pdf) | Google <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:258715226?fields=citationCount&query=%24.citationCount&label=citations) | 2023-05 | -
| [Capabilities of GPT-4 on Medical Challenge Problems](https://arxiv.org/pdf/2303.13375.pdf) | Microsoft, OpenAI <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:257687695?fields=citationCount&query=%24.citationCount&label=citations) | 2023-03 | -
| [BioMedLM-PubMedGPT: A purpose-built AI model trained to interpret biomedical language](https://crfm.stanford.edu/2022/12/15/biomedlm.html) | Stanford CRFM, MosaicML | 2022-12 | [HuggingFace](https://huggingface.co/stanford-crfm/BioMedLM) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/stanford-crfm/BioMedLM&query=%24.likes&label=🤗+Likes)
| [Med-PaLM: Large Language Models Encode Clinical Knowledge](https://arxiv.org/pdf/2212.13138.pdf) | Google <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:255124952?fields=citationCount&query=%24.citationCount&label=citations) | 2022-12 | [Github](https://github.com/conceptofmind/PaLM) <br> ![Star](https://img.shields.io/github/stars/conceptofmind/PaLM?style=social&label=Stars)
| [ClinicalT5: A Generative Language Model for Clinical Text](https://aclanthology.org/2022.findings-emnlp.398.pdf) | University of Oregon, Baidu <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:256631112?fields=citationCount&query=%24.citationCount&label=citations) | 2022-12 | [HuggingFace](https://huggingface.co/luqh/ClinicalT5-large) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/luqh/ClinicalT5-large&query=%24.likes&label=🤗+Likes)
| [GatorTron: A large language model for electronic health records](https://www.nature.com/articles/s41746-022-00742-2) | University of Florida, NVIDIA <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:255175535?fields=citationCount&query=%24.citationCount&label=citations) | 2022-12 | [HuggingFace](https://huggingface.co/UFNLP/gatortron-base) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/UFNLP/gatortron-base&query=%24.likes&label=🤗+Likes)
| [BioGPT: Generative Pre-trained Transformer for Biomedical Text Generation and Mining](https://aclanthology.org/2020.clinicalnlp-1.17/) | Microsoft Research <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:252542956?fields=citationCount&query=%24.citationCount&label=citations) | 2022-09 | [HuggingFace](https://huggingface.co/microsoft/biogpt) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/microsoft/biogpt&query=%24.likes&label=🤗+Likes)
| [BioBART: Pretraining and Evaluation of A Biomedical Generative Language Model](https://arxiv.org/pdf/2204.03905.pdf) | Tsinghua University <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:248069469?fields=citationCount&query=%24.citationCount&label=citations) | 2022-04 | [HuggingFace](https://huggingface.co/GanjinZero/biobart-v2-base) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/GanjinZero/biobart-v2-base&query=%24.likes&label=🤗+Likes)
| [KeBioLM: Improving Biomedical Pretrained Language Models with Knowledge](https://aclanthology.org/2021.bionlp-1.20.pdf) | Tsinghua, Alibaba <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:233324564?fields=citationCount&query=%24.citationCount&label=citations) | 2021-04 | [Github](https://github.com/GanjinZero/KeBioLM) <br> ![Star](https://img.shields.io/github/stars/GanjinZero/KeBioLM?style=social&label=Stars)
| [Pretrained Language Models for Biomedical and Clinical Tasks: Understanding and Extending the State-of-the-Art](https://aclanthology.org/2020.clinicalnlp-1.17/) | Meta <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:226283910?fields=citationCount&query=%24.citationCount&label=citations) | 2020-11 | [Github](https://github.com/facebookresearch/bio-lm) <br> ![Star](https://img.shields.io/github/stars/facebookresearch/bio-lm?style=social&label=Stars)
| [BioMegatron: Larger Biomedical Domain Language Model](https://aclanthology.org/2020.emnlp-main.379.pdf) | NVIDIA <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:222310618?fields=citationCount&query=%24.citationCount&label=citations) | 2020-10 | [HuggingFace](https://huggingface.co/EMBO/BioMegatron345mUncased) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/EMBO/BioMegatron345mUncased&query=%24.likes&label=🤗+Likes)
| [PubMedBERT: Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing](https://arxiv.org/pdf/2007.15779.pdf) | Microsoft Research <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:220919723?fields=citationCount&query=%24.citationCount&label=citations) | 2020-07 | [HuggingFace](https://huggingface.co/microsoft/BiomedNLP-PubMedBERT-base-uncased-abstract-fulltext) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/microsoft/BiomedNLP-PubMedBERT-base-uncased-abstract-fulltext&query=%24.likes&label=🤗+Likes)
| [Publicly Available Clinical BERT Embeddings](https://arxiv.org/pdf/1904.03323.pdf) | MIT CSAIL <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:102352093?fields=citationCount&query=%24.citationCount&label=citations) | 2019-04 | [HuggingFace](https://huggingface.co/emilyalsentzer/Bio_ClinicalBERT) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/emilyalsentzer/Bio_ClinicalBERT&query=%24.likes&label=🤗+Likes)
| [ClinicalBERT: Modeling Clinical Notes and Predicting Hospital Readmission](https://arxiv.org/pdf/1904.05342.pdf) | Harvard, Princeton, NYU <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:119308351?fields=citationCount&query=%24.citationCount&label=citations) | 2019-04 | [Github](https://github.com/kexinhuang12345/clinicalBERT) <br> ![Star](https://img.shields.io/github/stars/kexinhuang12345/clinicalBERT?style=social&label=Stars)
| [BioBERT: a pre-trained biomedical language representation model for biomedical text mining](https://arxiv.org/pdf/1901.08746) | Korea University <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:59291975?fields=citationCount&query=%24.citationCount&label=citations) | 2019-01 | [Github](https://github.com/dmis-lab/biobert) <br> ![Star](https://img.shields.io/github/stars/dmis-lab/biobert?style=social&label=Stars)
<!--
| [Paper Name](arxiv link) | Institute Name <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:12345678?fields=citationCount&query=%24.citationCount&label=citations) | 20xx-xx | [HuggingFace](https://github.com) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/&query=%24.likes&label=🤗+Likes)
-->


## Papers

- Med-PaLM 2: Towards Expert-Level Medical Question Answering with Large Language Models [[Paper]](https://arxiv.org/pdf/2305.09617.pdf)
- KeBioLM: Improving Biomedical Pretrained Language Models with Knowledge [[Paper]](https://arxiv.org/abs/2104.10344)
- BioELMo: Probing Biomedical Embeddings from Language Models [[Paper]](https://arxiv.org/abs/1904.02181)
- BioBART: Pretraining and Evaluation of A Biomedical Generative Language Model [[Paper]](https://aclanthology.org/2022.bionlp-1.9.pdf)
- ClinicalT5: A Generative Language Model for Clinical Text [[Paper]](https://aclanthology.org/2022.findings-emnlp.398.pdf)
- GatorTron: A Large Clinical Language Model to Unlock Patient Information from Unstructured Electronic Health Records [[Paper]](https://arxiv.org/pdf/2203.03540v2.pdf)
- ChatCAD: Interactive Computer-Aided Diagnosis on Medical Image using Large Language Models [[Paper]](https://arxiv.org/pdf/2302.07257.pdf) [[Code]](https://github.com/zhaozh10/ChatCAD)
- DeID-GPT: Zero-shot Medical Text De-Identification by GPT-4 [[Paper]](https://arxiv.org/pdf/2303.11032.pdf)
- Capabilities of GPT-4 on Medical Challenge Problems [[Paper]](https://arxiv.org/pdf/2303.13375.pdf)
- BioBERT: a pre-trained biomedical language representation model for biomedical text mining [[Paper]](https://arxiv.org/pdf/1901.08746.pdf)
- Publicly Available Clinical BERT Embeddings [[Paper]](https://arxiv.org/pdf/1904.03323.pdf)
- BioMegatron: Larger Biomedical Domain Language Model [[Paper]](https://arxiv.org/pdf/2010.06060.pdf)
- Don’t Stop Pretraining: Adapt Language Models to Domains and Tasks [[Paper]](https://aclanthology.org/2020.acl-main.740.pdf)
- Med-BERT: pretrained contextualized embeddings on large-scale structured electronic health records for disease prediction [[Paper]](https://www.nature.com/articles/s41746-021-00455-y)
- DoctorGLM: Fine-tuning your chinese doctor is not a herculean task [[Paper]](https://arxiv.org/abs/2304.01097) [[Code]](https://github.com/xionghonglin/DoctorGLM)
- HuatuoGPT, Towards Taming Language Models To Be a Doctor [[Paper]](https://arxiv.org/abs/2305.15075) [[Code]](https://github.com/FreedomIntelligence/HuatuoGPT)
- BioELECTRA:Pretrained Biomedical text Encoder using Discriminators [[Paper]](https://aclanthology.org/2021.bionlp-1.16.pdf)
- LinkBERT: Pretraining Language Models with Document Links [[Paper]](https://arxiv.org/pdf/2203.15827.pdf)
- BioGPT: Generative Pre-trained Transformer for Biomedical Text Generation and Mining [[Paper]](https://arxiv.org/pdf/2210.10341.pdf)
- Large Language Models Encode Clinical Knowledge [[Paper]](https://arxiv.org/pdf/2212.13138.pdf)
- A large language model for electronic health records [[Paper]](https://www.nature.com/articles/s41746-022-00742-2)
- Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing [[Paper]](https://arxiv.org/pdf/2007.15779.pdf)
- BEHRT: Transformer for Electronic Health Records [[Paper]](https://www.nature.com/articles/s41598-020-62922-y)
- Federated Learning of Medical Concepts Embedding using BEHRT [[Paper]](https://arxiv.org/abs/2305.13052) [[Code]](https://github.com/nadavlab/FederatedBEHRT)
- RadBERT: Adapting Transformer-based Language Models to Radiology [[paper]](https://pubs.rsna.org/doi/epdf/10.1148/ryai.210258) [[HuggingFace]](https://huggingface.co/UCSD-VA-health/RadBERT-RoBERTa-4m)
- Highly accurate protein structure prediction with AlphaFold [[Paper]](https://www.nature.com/articles/s41586-021-03819-2) [[Code]](https://github.com/deepmind/alphafold)
- Accurate prediction of protein structures and interactions using a three-track neural network [[Paper]](https://www.science.org/doi/full/10.1126/science.abj8754?casa_token=tleEHPOOSr8AAAAA%3AT0eToIMPW0oN1jjIGLs8aPyQK8qbcFIByjT1x4k90tvBAj03SZUzpEinCPe_t-g4ECmjJ9wlj8OwQBs)
- Protein complex prediction with AlphaFold-Multimer [[Paper]](https://www.biorxiv.org/content/10.1101/2021.10.04.463034v2.abstract)
- FastFold: Reducing AlphaFold Training Time from 11 Days to 67 Hours [[Paper]](https://arxiv.org/abs/2203.00854) [[Code]](https://github.com/hpcaitech/fastfold)
- HelixFold: An Efficient Implementation of AlphaFold2 using PaddlePaddle [[Paper]](https://arxiv.org/abs/2207.05477) [[Code]](https://github.com/PaddlePaddle/PaddleHelix)
- Uni-Fold: An Open-Source Platform for Developing Protein Folding Models beyond AlphaFold [[Paper]](https://www.biorxiv.org/content/10.1101/2022.08.04.502811v3.abstract) [[Code]](https://github.com/dptech-corp/Uni-Fold)
- OpenFold: Retraining AlphaFold2 yields new insights into its learning mechanisms and capacity for generalization [[Paper]](https://www.biorxiv.org/content/10.1101/2022.11.20.517210v2.abstract) [[Code]](https://github.com/aqlaboratory/openfold)
- ManyFold: an efficient and flexible library for training and validating protein folding models [[Paper]](https://academic.oup.com/bioinformatics/article/39/1/btac773/6887136) [[Code]](https://github.com/instadeepai/manyfold)
- ColabFold: making protein folding accessible to all [[Paper]](https://www.nature.com/articles/s41592-022-01488-1) [[Code]](https://github.com/sokrypton/ColabFold)
- Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences [[Paper]](https://www.pnas.org/doi/abs/10.1073/pnas.2016239118) [[Code]](https://github.com/facebookresearch/esm)
- ProGen: Language Modeling for Protein Generation [[Paper]](https://arxiv.org/abs/2004.03497) [[Code]](https://github.com/lucidrains/progen)
- ProtTrans: Towards Cracking the Language of Life's Code Through Self-Supervised Deep Learning and High Performance Computing [[Paper]](https://arxiv.org/abs/2007.06225) [[Code]](https://github.com/agemagician/ProtTrans)
- Evolutionary-scale prediction of atomic level protein structure with a language model [[Paper]](https://www.science.org/doi/full/10.1126/science.ade2574)
- High-resolution de novo structure prediction from primary sequence [[Paper]](https://www.biorxiv.org/content/10.1101/2022.07.21.500999v1.abstract) [[Code]](https://github.com/HeliXonProtein/OmegaFold)
- Single-sequence protein structure prediction using a language model and deep learning [[Paper]](https://www.nature.com/articles/s41587-022-01432-w)
- Improved the Protein Complex Prediction with Protein Language Models [[Paper]](https://www.biorxiv.org/content/10.1101/2022.09.15.508065v2.abstract)
- MSA Transformer [[Paper]](http://proceedings.mlr.press/v139/rao21a.html) [[Code]](https://github.com/The-AI-Summer/self-attention-cv)
- Deciphering antibody affinity maturation with language models and weakly supervised learning [[Paper]](https://arxiv.org/abs/2112.07782)
- xTrimoABFold: De novo Antibody Structure Prediction without MSA [[Paper]](https://arxiv.org/abs/2212.00735)
- scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data [[Paper]](https://arxiv.org/abs/2212.00735) [[Code]](https://github.com/TencentAILabHealthcare/scBERT)
- Interpretable RNA Foundation Model from Unannotated Data for Highly Accurate RNA Structure and Function Predictions [[Paper]](https://www.biorxiv.org/content/10.1101/2022.08.06.503062v2.abstract) [[Code]](https://github.com/ml4bio/rna-fm)
- E2Efold-3D: End-to-End Deep Learning Method for accurate de novo RNA 3D Structure Prediction [[Paper]](https://www.biorxiv.org/content/10.1101/2022.08.06.503062v2.abstract) [[Code]](https://github.com/ml4bio/rna-fm)


## Licenses

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

本项目遵循 [MIT License](https://lbesson.mit-license.org/).

[![CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

本项目遵循 [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).



## 引用

如果本项目对您有帮助，请引用我们的项目。

```
@misc{medllmdata2023,
  author = {Jun Wang},
  title = {Awesome Dataset for Medical LLM: A curated list of popular Datasets, Models and Papers for LLMs in Medical/Healthcare},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/onejune2018/Awesome-Medical-Healthcare-Dataset-For-LLM}},
}
​```
