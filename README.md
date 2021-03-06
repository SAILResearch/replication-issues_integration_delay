# Replication Package for "An Empirical Study of the Integration Time of Fixed Issues"

Daniel Alencar da Costa, Shane McIntosh, Uira Kulesza, Ahmed E. Hassan, Surafel Lemma Abebe  
**[Empirical Software Engineering Journal, 2017](https://doi.org/10.1007/s10664-017-9520-6)**

Abstract: Predicting the required time to fix an issue (i.e., a new feature, bug fix, or enhancement) has long been the goal of many software engineering researchers. However, after an issue has been fixed, it must be integrated into an official release to become visible to users. In theory, issues should be quickly integrated into releases after they are fixed. However, in practice, the integration of a fixed issue might be prevented in one or more releases before reaching users. For example, a fixed issue might be prevented from integration in order to assess the impact that this fixed issue may have on the system as a whole. While one can often speculate, it is not always clear why some fixed issues are integrated immediately, while others are prevented from integration. In this paper, we empirically study the integration of 20,995 fixed issues from the ArgoUML, Eclipse, and Firefox projects. Our results indicate that: (i) despite being fixed well before the release date, the integration of 34% to 60% of fixed issues in projects with traditional release cycle (the Eclipse and ArgoUML projects), and 98% of fixed issues in a project with a rapid release cycle (the Firefox project) was prevented in one or more releases; (ii) using information that we derive from fixed issues, our models are able to accurately predict the release in which a fixed issue will be integrated, achieving Areas Under the Curve (AUC) values of 0.62 to 0.93; and (iii) heuristics that estimate the effort that the team invests to fix issues is one of the most influential factors in our models. Furthermore, we fit models to study fixed issues that suffer from a long integration time. Such models, (iv) obtain AUC values of 0.82 to 0.96 and (v) derive much of their explanatory power from metrics that are related to the release cycle. Finally, we train regression models to study integration time in terms of number of days. Our models achieve R2 values of 0.39 to 0.65, and indicate that the time at which an issue is fixed and the resolver of the issue have a large impact on the number of days that a fixed issue requires for integration. Our results indicate that, in addition to the backlog of issues that need to be fixed, the backlog of issues that need to be released introduces a software development overhead, which may lead to a longer integration time. Therefore, in addition to studying the triaging and fixing stages of the issue lifecycle, the integration stage should also be the target of future research and tooling efforts in order to reduce the time-to-delivery of fixed issues.

## How to cite us?

```bibtex
@Article{daCosta2017,
author="da Costa, Daniel Alencar
and McIntosh, Shane
and Kulesza, Uir{\'a}
and Hassan, Ahmed E.
and Abebe, Surafel Lemma",
title="An empirical study of the integration time of fixed issues",
journal="Empirical Software Engineering",
year="2017",
month="May",
day="11",
issn="1573-7616",
doi="10.1007/s10664-017-9520-6",
url="https://doi.org/10.1007/s10664-017-9520-6"
}
```

## Data

You can find the latest version [here](https://github.com/SAILResearch/replication-issues_integration_delay/releases/latest)

