# Deprecation Warning

Do not request this data set anymore. REQUESTS WILL BE IGNORED.

This data set has been deprecated in favor of a new, soon-to-be-released data set.

## Numbering permanent and deciduous teeth via deep instance segmentation in panoramic X-rays
We presented our results at the 17th International Symposium on Medical Information Processing and Analysis (SIPAIM), and our paper was among the finalists of the best paper award.
To be notified of code releases, new data sets, and errata, please watch this repo.

## Data set statistics
The data set comprises 450 panoramic images, split into six folds, each containing 75 images.
The first five folds were used for cross-validation, while the remaining one constituted the test data set.
We cropped all images to the new 1876x1036 dimensions and converted them to PNG image files.
The table below summarizes the data used according to image categories.
These categories group the images according to the presence of 32 teeth, restoration, and dental appliances, revealing the high variability of the images.
Categories 5 and 6 are reserved for patients with dental implants and more than 32 teeth, respectively.


| Category |      32 Teeth      |     Restoration    |      Appliance     | Number and Inst. Segm. |
|:--------:|:------------------:|:------------------:|:------------------:|:----------------------:|
|     1    | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |           24           |
|     2    | :heavy_check_mark: | :heavy_check_mark: |                    |           66           |
|     3    | :heavy_check_mark: |                    | :heavy_check_mark: |           14           |
|     4    | :heavy_check_mark: |                    |                    |           41           |
|     7    |                    |      Implants      |                    |           36           |
|     8    |                    | More than 32 teeth |                    |           51           |
|     7    |                    | :heavy_check_mark: | :heavy_check_mark: |           35           |
|     8    |                    | :heavy_check_mark: |                    |           136          |
|     9    |                    |                    | :heavy_check_mark: |           13           |
|    10    |                    |                    |                    |           34           |
|          |                    |                    |        Total       |           450          |

## Citation

L. Pinheiro, B. Silva, B. Sobrinho, F. Lima, P. Cury, L. Oliveira, “Numbering permanent and deciduous teeth via deep instance segmentation in panoramic X-rays,” in Symposium on Medical Information Processing and Analysis (SIPAIM). SPIE, 2021.

```
@inproceedings{pinheiro2021numbering,
  title={Numbering permanent and deciduous teeth via deep instance segmentation in panoramic X-rays},
  author={Pinheiro, Laís and Silva, Bernardo and Sobrinho, Brenda and Lima, Fernanda and Cury, Patrícia and Oliveira, Luciano.}
  booktitle={Symposium on Medical Information Processing and Analysis (SIPAIM)},
  year={2021},
  organization={SPIE}
}
```

## Previous Works
This data set and its corresponding paper are a continuation of other works of our group.
Please, consider reading and citing:

- B. Silva, L. Pinheiro, L. Oliveira, and M. Pithon, “A study on tooth segmentation and numbering using end-to-end deep neural networks,” in Conference on Graphics, Patterns and Images. IEEE, 2020.

```
@inproceedings{silva2020study,
  title={A study on tooth segmentation and numbering using end-to-end deep neural networks},
  author={Silva, Bernardo and Pinheiro, Laís and Oliveira, Luciano and Pithon, Matheus}
  booktitle={Conference on Graphics, Patterns and Images (SIBGRAPI)},
  year={2020},
  organization={IEEE}
}
```

- G. Jader, J. Fontineli, M. Ruiz, K. Abdalla, M. Pithon, and L. Oliveira, “Deep instance segmentation of teeth in panoramic X-ray images,” in Conference on Graphics, Patterns and Images. IEEE, 2018.
```
@inproceedings{jader2018deep,
  title={Deep instance segmentation of teeth in panoramic X-ray images},
  author={Jader, Gil and Fontineli, Jefferson and Ruiz, Marco and Abdalla, Kalyf and Pithon, Matheus and Oliveira, Luciano},
  booktitle={Conference on Graphics, Patterns and Images (SIBGRAPI)},
  pages={400--407},
  year={2018},
  organization={IEEE}
}
```

- G. Silva, L. Oliveira, and M. Pithon, “Automatic segmenting teeth in X-ray images: Trends, a novel data set, benchmarking and future perspectives,” Expert Systems with Applications, Patterns and Images. vol. 107, pp. 15-31, 2018.
```
@article{silva2018automatic,
  title={Automatic segmenting teeth in X-ray images: Trends, a novel data set, benchmarking and future perspectives},
  author={Silva, Gil and Oliveira, Luciano and Pithon, Matheus},
  journal={Expert Systems with Applications},
  volume={107},
  pages={15--31},
  year={2018},
  publisher={Elsevier}
}
```
