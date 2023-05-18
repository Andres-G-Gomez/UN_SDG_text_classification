
<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

We present a comparative study of four well-known machine learning algorithms, Multinomial Naïve Bayes (MNB), Support Vector Machine (SVM), Logistic Regression (LR), and Random Forest (RF), for text classification using the Open Software Development Governance - Code Dataset (OSDG-CD). We determined the key words for each class and evaluated the performance of each algorithm on the task of SDG classification. Our comparative study showed promising results, with SVM achieving the highest accuracy of 89.4%. We also compared our results with other models such as BERT and Label Powerset with SVM, which have achieved higher accuracies on this task, and discussed the advantages and disadvantages of these models. 

You can find the paper here: [Text Classification and Keyword Identification of the Sustainable Development Goals](https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez/blob/main/project_submission.pdf)
The PowerPoint presentation is located [here](https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez/blob/main/Presentation.pptx) and a YouTube video of the presentation can be found [here](https://youtu.be/lxnQjeFpG8U)

<!-- GETTING STARTED -->
## Getting Started

Contained are three scripts, [tdifd.ipynb](https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez/blob/main/tdifd.ipynb) where the hyperparameter search took place, [evaluate_tfidf.ipynb](https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez/blob/main/evaluate_tfidf.ipynb) where the optimal models were evaluated on the test test, and [evaluate_tfidf.ipynb](https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez/blob/main/evaluate_tfidf.ipynb) where keywords were extracted. 

### Dependencies

For example, this is how you would list them:
* numpy 1.23.5
  ```sh
  conda install -c anaconda numpy=1.23.5
  ```
* pandas 1.5.3
  ```sh
  conda install -c anaconda pandas=1.5.3
  ```
 * nltk 3.7
 ```sh
 conda install -c anaconda nltk=3.7
 ```
 * scikit-learn 1.2.2
 ```sh
 conda install -c anaconda scikit-learn=1.2.2
 ```
 * Matplotlib 3.7.1
 ```sh
 conda install -c conda-forge matplotlib=3.7.1
 ```
### Alternative: Export your Environment

Alternatively, here is my Python working [environment](https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez/blob/main/project_eel6825.yml)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez
   ```
 2. Setup (and activate) your environment
   ```sh
   conda env create -f project_eel6825.yml
   ```

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/catiaspsilva/README-template/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- Authors -->
## Authors

Andres Gomez - [@AndresG0508](https://twitter.com/AndresG0508) - Andresggomez@ufl.edu


Project Link: [https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez](https://github.com/uf-eel6825-sp23/final-project-code-Andres-G-Gomez)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

You can acknowledge any individual, group, institution or service.
* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)

## Thank you

<!-- If this is useful: [![Buy me a coffee](https://www.buymeacoffee.com/andresgg)](https://www.buymeacoffee.com/andresgg) -->
