# academia_productivity

## Useful prompts

### Revise the arxiv citaions
Don't feed too many citations in 1 request; GPT4o will be "lazy". Feed 10 citations works for me
```

Below is the cite.bib from overleaf project. Some citations were drafts in arxiv and may have been published now. For every citation, check if the paper has been published somewhere else. If so, find out the new citation and replace the old one. Get BibTex from Google scholar. Keep the hyperlink, e.g. 2406.17322 the same. Output the resulting bib file. If you're rated or rejected by the google scholar or other websites, print out errors and proceed to the next citation.

For example, for the article: ALPBench: A Benchmark for Active Learning Pipelines on Tabular Data  The original arXiv citation is: 

@misc{2406.17322,
  author = {Valentin Margraf and Marcel Wever and Sandra Gilhuber and Gabriel Marques Tavares and Thomas Seidl and Eyke Hüllermeier},
  title = {ALPBench: A Benchmark for Active Learning Pipelines on Tabular Data},
  year = {2024},
  primaryClass = {cs.LG cs.AI},
  url = {https://arxiv.org/abs/2406.17322}

}

It should be replaced as:

@article{2406.17322,
  title={ALPBench: A Benchmark for Active Learning Pipelines on Tabular Data},
  author={Margraf, Valentin and Wever, Marcel and Gilhuber, Sandra and Tavares, Gabriel Marques and Seidl, Thomas and H{\"u}llermeier, Eyke},
  journal={arXiv preprint arXiv:2406.17322},
  year={2024}

}


Now process the citations below:

@misc{2106.15324,
  author = {Nathan Beck and Durga Sivasubramanian and Apurva Dani and Ganesh Ramakrishnan and Rishabh Iyer},
  title = {Effective Evaluation of Deep Active Learning on Image Classification Tasks},
  year = {2021},
  primaryClass = {cs.CV cs.AI cs.LG},
  url = {https://arxiv.org/abs/2106.15324}
}
...

