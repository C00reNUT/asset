# ASSET Corpus 

Dataset for evaluating Text Simplification systems with multiple rewriting transformations.

If you use the corpus, please cite the following paper:
```
ASSET: A Dataset for Tuning and Evaluation of Sentence Simplification Models with Multiple Rewriting Transformations 
Fernando Alva-Manchego, Louis Martin, Antoine Bordes, Carolina Scarton, Benoît Sagot, Lucia Specia
```

The corpus is composed of 2000 validation and 359 test original sentences `asset/asset.{valid,test}.orig` that were each simplified 10 times by different annotators `asset/asset.{valid.test}.simp.{0,1,2,3,4,5,6,7,8,9}` (one sample per line).

We recommend that you evaluate your Text Simplification (TS) system using this dataset and traditional TS metrics with the [EASSE](https://github.com/feralvam/easse) package.


## Authors

If you have any question, please contact the authors:  
**Fernando Alva-Manchego** ([f.alva@sheffield.ac.uk](mailto:f.alva@sheffield.ac.uk))  
**Louis Martin** ([louismartincs@gmail.com](mailto:louismartincs@gmail.com))  

## Citation
If you use our work, please cite:

```bibtex
@inproceedings{alvamanchego2020asset,
  title={ASSET: A Dataset for Tuning and Evaluation of Sentence Simplification Models with Multiple Rewriting Transformations},
  author={Alva-Manchego, Fernando and Martin, Louis and Bordes, Antoine and Scarton, Carolina and Sagot, Benoît and Specia, Lucia},
  booktitle={Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics},
  year={2020}
}
```

## License

See the [LICENSE](LICENSE) file for more details.
