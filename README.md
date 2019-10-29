# Actionable Ethics for Data Scientists

Repository for [workshop](https://odsc.com/training/portfolio/practical-data-ethics-with-deon/) at ODSC West 2019. See [abstract](#abstract) for a summary of the workshop contents.

Slides: To Be Added

## Installation Instructions

Clone this repository:

```shell
git clone https://github.com/drivendataorg/odsc-west-2019.git
cd odsc-west-2019
```

Set up environment:

```shell
conda create -n odsc-ethics
conda activate odsc-ethics
pip install -r requirements.txt
```

### Group Case Study Instructions

```shell
deon notebooks/group-qualitative-case-study/ethics.md
```

We encourage you to take notes in your `ethics.md` file. We also encourage you to contribute your groups notes to this repository through a pull request. Please name your file with your group number.

### Eviction Data Case Study Instructions

```shell
jupyter notebook
```

<a name="abstract"/>

## Workshop Abstract

> Our goal is for every data scientist to practice data ethics as part of their regular work. In this workshop, you will learn how to make data ethics actionable as a data scientist.
>
> We will present an approach to data ethics based on integrating an ethics checklist into your existing data science workflow. We will be using deon (http://deon.drivendata.org), a lightweight, open-source command line tool designed to easily create and incorporate an ethics checklist into your work. The goal is to enable teams to flexibly carry out the ethical discussions most relevant to them, and to preemptively address issues they may otherwise overlook. There has been much ongoing reflection and dialogue within the data science profession about what ethical principles to abide by, especially in the form of ethical codes and oaths. However, there is often still a gap between those principles and the day-to-day work of data scientists—tenets are either too abstract or too rigid to apply readily. Deon and the checklist framework we present encourages an upfront and ongoing dialogue about the different ethical aspects of your project. By closely integrating data ethics into an ongoing workflow, we as data scientists can cultivate ethical intentionality in our work.
>
> Throughout this interactive workshop, Casey and Jay will explain the rationale behind building deon, walk through the default checklist content, and provide concrete examples of times where overlooking topics on the ethics checklist has caused unnecessary headache or harm. Using real stories of improperly hashed NYC taxi data, skewed training sets used in crime prediction, biased geometry in embedding spaces, and more, you will consider and discuss a diverse set of ethical issues common in the course of data science work.
>
> In two hands-on case study exercises, you'll team up to navigate a set of scenarios. The first case study is a group activity focused on public and private sector uses of personal health data, where you will practice working through the checklist and examining the ethical implications of your team's design choices. Then, in the second case study using real-world eviction data, you will get to roll up your sleeves, make some models, and explore the trade-offs and nuance of data ethics.
>
> Come learn how to jumpstart the ethics conversation that all data science teams should be having.
>
> **Key takeaways:**
>
> - Checklists connect principle to practice and enable data scientists to exercise their data ethics muscles, becoming better at issue-spotting, mitigation, and navigating subtle discussions.
> - Having a structured process for data ethics makes it easier for teams to have tough conversations and helps ensure that important work doesn't get overlooked.
> - Working through the ethics checklist in deon can help preempt ethical problems down the line.
>
> **Target audience:**
>
> This workshop is intended for data scientists and managers—the practitioners that have influence over how data science gets done. This means anyone who spends their days working directly with data, in the realm of data collection, data storage, analysis, modeling and/or deployment.

## Repo Organization

```text
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   └── raw            <- The original, immutable data dump.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
└── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
                          generated with `pip freeze > requirements.txt`
```

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
