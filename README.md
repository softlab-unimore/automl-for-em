# AutoML for Entity Matching

This project provides an approach for applying automated machine learning techniques (AutoML) for addressing the problem of Entity Matching (EM), i.e. the task of identifying which records in a dataset refer to the same real-world entity. This would make the existing, highly effective, Machine Learning (ML) and Deep Learning (DL) based approaches for EM usable also by non-expert users, who do not have the expertise to train and tune such complex systems.

The proposed approach leverages an **EM Adapter**, to be pipelined with standard AutoML systems, that preprocesses the EM datasets to make them usable by automated approaches and provides greater effectiveness in solving EM tasks. This component relies on the most recent transformer architectures, such as BERT and variants (DistilBERT, ALBERT, RoBERTa and XLNet), and a representation of the entire pipeline is provided in the following figure.

![EMAdapterArchitecture](doc/figures/EMAdapterArchitecture.jpg)

For a detailed description of the work please read [our paper](https://openproceedings.org/2021/conf/edbt/p260.pdf). Please cite the paper if you use the code from this repository in your work.

```
@inproceedings{DBLP:conf/edbt/PaganelliBP0V21,
  author    = {Matteo Paganelli and
               Francesco Del Buono and
               Marco Pevarello and
               Francesco Guerra and
               Maurizio Vincini},
  title     = {Automated Machine Learning for Entity Matching Tasks},
  booktitle = {{EDBT}},
  pages     = {325--330},
  publisher = {OpenProceedings.org},
  year      = {2021}
}
```

## License
[MIT License](LICENSE)
