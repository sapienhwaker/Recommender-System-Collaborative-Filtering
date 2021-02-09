# Movie Recommeneder System (Netflix challenge 2010)
> Python implementation of item item collaborative filtering

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
[![Generic badge](https://img.shields.io/badge/Written%20in-Python-green.svg)](https://shields.io/)

Item-item collaborative filtering, or item-based, or item-to-item, is a form of collaborative filtering for recommender systems based on the similarity between items calculated using people's ratings of those items. Item-item collaborative filtering was invented and used by Amazon.com in 1998.

![](collaborative_filtering.png)

## Objectives:
* Read data and generate the matrix
* Compute cosine and adjusted cosine similarity
* Train the model and predict rating for specific user and movie pair
* Validate results by calculating the rmse value

## Input
Csv file containing users, movies and correspoing ratings. Training and testing dataset

## Output

Rating prediction for specific user and movie pair.

## Limitations of Collaborative filtering Algorithm

The limitation has been commonaly known as "the cold start problem". It's difficult to predict movie rating for a user who has been newly added to the dataset and which doesn't have history of rating anyother movie.

## Release History

* 0.1.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.1.0
    * The first proper release
* 0.0.1
    * Work in progress

## Meta

Author: [Prasad Hajare](https://www.itsprasad.com/), MS Computer Science.

Distributed under the [MIT License](LICENSE).

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
