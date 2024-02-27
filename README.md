# ElecDeb60to20 Dataset

In this repository is available the dataset named **ElecDeb60to20** that is split in different annotation types:
 - Fallacy Annotation
 - Argument Component Annotations
 - Argument Relationship Annotations

This dataset is a collection of televised debates of the US presidential campaign debates from **1960** to **2020** [[1](https://aclanthology.org/2023.emnlp-main.684)], [[2](https://aclanthology.org/P19-1463)], [[3](https://www.debates.org/voter-education/debate-transcripts/)].

The guidelines used to annotate the fallacy are provided [here](https://github.com/pierpaologoffredo/ElecDeb60to20/blob/main/guidelines/fallacy.pdf), whereas for the argumentative component and relationship are [here](https://github.com/pierpaologoffredo/ElecDeb60to20/blob/main/guidelines/annotation_guidelines.pdf).

## Fallacy 

> In the pragma-dialectical theory of argumentation [[Eemeren and
> Grootendorst, 1992](https://www.routledge.com/Argumentation-Communication-and-Fallacies-A-Pragma-dialectical-Perspective/van-Eemeren-Grootendorst/p/book/9780805810691); [Eemeren, 2010](https://doi.org/10.1075/aic.2)], fallacies are defined as
> “derailments of strategic manoeuvring”, meaning speech acts that
> violate the rules of a rational argumentative discussion for assumed
> persuasive gains.

Focus on **six** category of main fallacies and three of them are further divided into **sub-categories**:

 1. **Ad Hominem**
	 1. General
	 2. Bias ad Hominem
	 3. Tu quoque
	 4. Name-calling, Labeling
 2. **Appeal to Emotion**
	 1. Appeal to Fear
	 2. Appeal to Pity
	 3. Loaded Language
	 4. Flag Waving
 3. **Appeal to Authority**
	 1. Without evidence
	 2. False authority
	 3. Popular Opinion
 4. **False Cause**
 5. **Slippery Slope**
 6. **Slogans**

## Argumentative Component

The components are split into:
 - Claims
 - Premises

 **Claims**
 
Being them the ultimate goal of an argument, in the context of political debates, claims can be a policy advocated by a party or a candidate to be undertaken which needs to be justified in order to be accepted by the audience.

**Premises**

Premises are assertions made by the debaters for supporting their claims (i.e., reasons
or justifications).

## Argumentative Relationship
The relationships are split into:
 - Support
 - Attack

**Support**

Links two components from a supporting argument component to a supported argument component. 

**Attack**

Holds when one argument component is in contradiction with another argument component


