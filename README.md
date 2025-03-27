![image](Figures/green+orange-full-color_lrg.jpg) 

# Beyond Public Access: Uncovering non-public book content in OpenAI's pre-training data


The official GitHub repository for the paper "Beyond Public Access: Uncovering non-public book content in OpenAI's pre-training data" by [The AI Disclosures Project](https://www.ssrc.org/programs/ai-disclosures-project/).

Using a legally obtained dataset of 34 copyrighted O'Reilly Media books, we apply the DE-COP membership inference attack method to investigate whether OpenAI's large language models were trained on copyrighted content without consent. Our AUROC scores show that GPT-4o, OpenAI's more recent and capable model, demonstrates strong recognition of paywalled O'Reilly book content, compared to OpenAI's earlier model GPT-3.5 Turbo. In contrast, GPT-3.5 Turbo shows greater relative recognition of publicly accessible O'Reilly book samples. While GPT 4o-Mini, as a much smaller model, shows no knowledge of public or private O'Reilly Media content. Testing multiple models, with the same cutoff date, helps us account for potential language shifts over time that might bias our findings. These results highlight the need for increased corporate transparency regarding pre-training data sources to foster equitable content remuneration ecosystems

An anonymized version of our datasets could be found [here](https://drive.google.com/drive/folders/10A3FIe6hjb_pURaDULWSSJwUXS-gUSgG?usp=sharing).