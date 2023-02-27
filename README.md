# Anime Screenshot Pipeline
Semi-automatic pipeline to extract image training set from anime for generative model training.\
Colab version of: https://github.com/cyber-meow/anime_screenshot_pipeline

<details>
  <summary><big>Feature</big></summary>
<ul>
  <li>Can be found at cyber-meow github repo <a href='https://github.com/cyber-meow/anime_screenshot_pipeline#table-of-contents' target='_blank'>README.md</a></li>
</ul>
</details>

<details>
  <summary><big>Limitation</big></summary>
<ul>
  <li>Not all code tested</li>
  <li>Not all steps from github repo is implemented</li>
  <li>Since this notebook is combination of many steps, dependency or package conflict may occurs</li>
  <li>Bad english language spelling and grammar (english is not my primary language :#). Feel free to correct and Pull Request!</li>
</ul>
</details>

<details>
  <summary><big>Credits</big></summary>
<ul>
  <li>Author</li>
  <ul>
    <li><a href='https://github.com/TheSkinnyRat' target='_blank'>TheSkinnyRat</a></li>
  </ul>

  <li>Base Code Repo</li>
  <ul>
    <li><a href='https://github.com/cyber-meow/anime_screenshot_pipeline' target='_blank'>cyber-meow github repo</a></li>
  </ul>

  <li>Colab Template and Reference</li>
  <ul>
    <li><a href='https://github.com/Linaqruf/kohya-trainer' target='_blank'>Linaqruf/kohya-trainer</a></li>
  </ul>

  <li>Code Assistant</li>
  <ul>
    <li><a href='https://chat.openai.com/' target='_blank'>OpenAI ChatGPT</a></li>
  </ul>

  <li>Original cyber-meow repo credits</li>
  <ul>
    <li>This is a collection of many resources found on internet (credit to the orignal authors), and some python code written by myself and ChatGPT.</li>
  </ul>
</ul>
</details>

<details>
  <summary><big>Whats new?</big></summary>
<ul>
  <li>(02/27/23):</li>
  <ul>
    <li>Add <code>WANDB_MODE=disabled</code> to <code>[7.2] Begin Training</code></li>
    <li>Fix <code>cc_training_test_set</code> error in <code>[7.2] Begin Training</code></li>
    <li>Fix <code>fa_move_file</code> error in <code>[8.1] Only keep images with faces and resize</code></li>
    <li>Move <code>[6.3] Data Cleansing</code> to <code>[5.2] Data Cleansing</code> and change to <code>n_faces</code> instead <code>n_poeple</code></li>
  </ul>

  <li>(02/26/23):</li>
  <ul>
    <li>Initial First Release 🎉</li>
  </ul>
</ul>
</details>

| Notebook Name | Link | Repo |
| --- | --- | --- |
| [Anime Screenshot Pipeline](https://github.com/TheSkinnyRat/anime_screenshot_pipeline_colab/blob/main/anime_screenshot_pipeline.ipynb) | [![](https://img.shields.io/static/v1?message=Open%20in%20Colab&logo=googlecolab&labelColor=5c5c5c&color=0f80c1&label=%20&style=for-the-badge)](https://colab.research.google.com/github/TheSkinnyRat/anime_screenshot_pipeline_colab/blob/main/anime_screenshot_pipeline.ipynb) | [![](https://img.shields.io/static/v1?message=Github&logo=github&labelColor=5c5c5c&color=0f80c1&label=%20&style=for-the-badge)](https://github.com/TheSkinnyRat/anime_screenshot_pipeline_colab) |
