# DrugComboRanker

Motivation: Currently there are no curative anticancer drugs, and drug
resistance is often acquired after drug treatment. One of the reasons is
that cancers are complex diseases, regulated by multiple signaling
pathways and cross talks among the pathways. It is expected that
drug combinations can reduce drug resistance and improve patients�
outcomes. In clinical practice, the ideal and feasible drug combinations
are combinations of existing Food and Drug Administrationapproved
drugs or bioactive compounds that are already used on
patients or have entered clinical trials and passed safety tests.
These drug combinations could directly be used on patients with
less concern of toxic effects. However, there is so far no effective
computational approach to search effective drug combinations from
the enormous number of possibilities.
Results: In this study, we propose a novel systematic computational
tool DrugComboRanker to prioritize synergistic drug combinations
and uncover their mechanisms of action. We first build a drug functional
network based on their genomic profiles, and partition the network
into numerous drug network communities by using a Bayesian
non-negative matrix factorization approach. As drugs within overlapping
community share common mechanisms of action, we next uncover
potential targets of drugs by applying a recommendation
system on drug communities. We meanwhile build disease-specific
signaling networks based on patients� genomic profiles and interactome
data. We then identify drug combinations by searching drugs
whose targets are enriched in the complementary signaling modules
of the disease signaling network. The novel method was evaluated on
lung adenocarcinoma and endocrine receptor positive breast cancer,
and compared with other drug combination approaches. These case
studies discovered a set of effective drug combinations top ranked in
our prediction list, and mapped the drug targets on the disease signaling
network to highlight the mechanisms of action of the drug
combinations.

Please cite the following paper when you use DrugComboRanker.

>DrugComboRanker: drug combination discovery based on target network analysis. Lei Huang, Fuhai Li, Jianting Sheng, Xiaofeng Xia, Jinwen Ma, Ming Zhan and Stephen T.C. Wong, 2014. 30:i228�i236


[![Alt text](https://raw.githubusercontent.com/methodistsmab/DrugComboExplorer/master/drug_combo_ranker_screenshot.png)](https://www.youtube.com/watch?v=wN4vHV6hoig)

# MacOS verison Download

>https://www.dropbox.com/s/1y1or8ougjkzu3x/CCCExplorer_MacOS.zip?dl=0

# How to use CCCExplorer

Youtube video URL:

>https://youtu.be/wN4vHV6hoig

# User Guide

>https://github.com/methodistsmab/CCCExplorer/blob/master/CCCExplorer_user_guide_v1.pdf

# License Agreement

>https://github.com/methodistsmab/CCCExplorer/blob/master/CCCExplorer_End_User_License_Agreement.pdf


# Contact

>Xiaohui Yu

>Email: xyu2@houstonmethodist.org

>Lei Huang

>Email: lhuang@houstonmethodist.org