### Judge a model on its variance, not on its best run

I'm a data scientist working on forecasting and optimisation in energy and
industry. Buildings were my laboratory: until May 2026 that meant industrial
R&D, and the systems that control them. The problems get interesting once a
model has to survive contact with someone who didn't build it.

Most of that work belongs to a former employer, so the write-ups live on
[shpetimgashi.com](https://shpetimgashi.com). What sits in this account is what
I can publish in full.

[model-factory-heart-diseases](https://github.com/sg-Ikigai/model-factory-heart-diseases)
is a controlled ablation on a small tabular classifier. The dataset is the
point: 723 of its 1,025 rows are exact duplicates, so 70.5% of it has to go
before any score means anything. Every configuration is reported with its
standard deviation across folds and seeds, because a model that scores well
once and differently on retrain has not scored well.

### What I build

- **Reinforcement Learning for Comfort Conditions in Buildings**  
  Project lead on a research project applying reinforcement learning to comfort
  conditions in buildings. I ran the workstream: coordinating the activities,
  steering the technical direction, and building the simulation-based
  experimentation pipeline with PPO, Gymnasium and stable-baselines3.

- **Manufacturing optimisation and scenario planning**  
  Formulated a constrained optimisation problem as a linear program in Python
  and PuLP, then wrapped it in something people could actually use: the
  recommendation first, scenario comparison underneath, packaged to run without
  a Python install.

- **Time-series forecasting**  
  A pipeline comparing ARIMA and SARIMA baselines against LSTM models in
  TensorFlow. The baseline existed to answer whether the extra complexity was
  justified at all, which is a question worth asking early rather than after
  you have paid for the answer.

### How I work

Judge a model on its variance, not on its best run. A model whose headline
error looks competitive but that behaves differently every time you retrain it
is not dependable, and saying so is more useful than shipping it. A result does
not get better because a lot of effort has gone into it.

### Stack

**Languages and data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-0A6B94?style=flat&logo=sqlite&logoColor=white)

**Machine learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-E70488?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-4D77CF?style=flat&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Delivery and reporting**

![Flask](https://img.shields.io/badge/Flask-4F4F4F?style=flat&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-C7A008?style=flat&logoColor=black)

### About the name

People ask, so: *ikigai* (生き甲斐) is roughly "what makes life feel worth
living". Mieko Kamiya wrote the foundational study in 1966, after years among
patients with Hansen's disease at Nagashima Aiseien.

What she found was modest. A life felt worth living less through achievement
than through being needed, and through moving forward a little at a time. She
also separated the thing that gives meaning from the felt sense that life has
any, a distinction most motivational writing skips.

Ken Mogi is what brought me to it. His five pillars are conditions under
which life feels worth getting up for, each one available to someone with
no success to point at.

![The five pillars of ikigai](ikigai-pillars.svg)

*After Ken Mogi, "The Little Book of Ikigai" (2017). The concept itself is set
out in Mieko Kamiya, "Ikigai ni tsuite" (生きがいについて, 1966).*

- **Starting small**  
  The small thing is not a stepping stone, it is where the meaning lives. A
  sushi chef's attention to the temperature of the rice is complete in itself
  rather than a means to a star. Value does not scale with size.

- **Releasing yourself**  
  The ego and the running self-commentary drop away inside an activity, so you
  are not doing the thing in order to be someone who did it. The same idea runs
  the other way too: you stop performing a version of yourself you think is
  required.

- **Harmony and sustainability**  
  Your ikigai sits inside a web of relationships and does not require you to
  beat anyone. It also has to be able to continue, so something that burns you
  out, or depends on conditions that will not hold, is not it.

- **The joy of little things**  
  The morning coffee, the light on the way to work. Not rewards earned by the
  work, but part of what makes a life worth living directly.

- **Being in the here and now**  
  Presence, and the absorption that comes with it. Ikigai is experienced in the
  present rather than collected from a future payoff.

What they share is that every one removes a dependency: on scale, on
recognition, on winning, on the future. None of them asks the work to have
succeeded first.

---

![Profile views](https://komarev.com/ghpvc/?username=sg-Ikigai&label=Profile%20views&color=0e75b6&style=flat)
