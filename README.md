# skore and skrub demo

My demos of the skore python library that I co-maintain, as well as skrub.

Links:
- skore: [GitHub repository](https://github.com/probabl-ai/skore), [documentation](https://skore.probabl.ai/), [demo videos](https://youtube.com/playlist?list=PLSIzlWDI17bTpixfFkooxLpbz4DNQcam3)
- skrub: [GitHub repository](https://github.com/skrub-data/skrub), [documentation](https://skrub-data.org/stable/)
- [Get to know Probabl](https://probabl.notion.site/Get-to-know-Probabl-127ef76d36b9804d8ca8e264e42f0cee)
- Contact: [Sylvain Combettes](https://www.linkedin.com/in/sylvain-combettes/) at `sylvain@probabl.ai`

## Setup

Execute the following bash commands:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

*Note*: For now, I have fixed the version of skore to v0.8.3 in `requirements.txt`, while the latest version is:

[![pypi](https://img.shields.io/pypi/v/skore)](https://pypi.org/project/skore/)

## Using this repo

The `demo.ipynb` notebook is already executed.

You can visualize a static version of this notebook on [nbviewer](https://nbviewer.org/github/sylvaincom/skore_demo/blob/main/demo.ipynb).

## Recommended resources

- Probabl: présentation des librairies skore et skrub [[YouTube video](https://www.youtube.com/live/cy4cDEHX4-E?si=o0ex01Uv35qNJrj_&t=1662)] → Probabl presentation and Skore Lib demo by Sylvain Combettes at a seminar of the CNRS in April 2025, in French, from 27:42 to 58:47 including Q&A.
-   Developments in the Scikit-Learn Ecosystem: Going Beyond `.fit(X, y).predict(X)` [[YouTube video](https://www.youtube.com/live/0AdocmpDr84?si=65jvUhz81_cOYmcA&t=450)] → great talk by Probablrs at PyData Milano in March 2025, presenting scikit-learn, skrub, skops, and skore.
    <details>
    <summary><i>Toggle for the timeline of the video!</i></summary>
    0:00 - 7:30 → general introduction of PyData Milan<br>
    7:30 - 9:25 → brief presentations of Guillaume Lemaitre and Marie Sacksick from Probabl<br>
    9:25 - 21:15 → What scikit-learn allows you to do<br>
    21:15 - 32:54 → skrub - less wrangling, more machine learning<br>
    32:54 - 43:51 → skops - scikit-learn models in production<br>
    43:51 - 52:05 → skore - an abstraction to ease data science projects
    </details>