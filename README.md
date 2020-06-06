# How to run:
python3 main_propensity_dropout.py

# Dataset:
IHDP dataset will be found in the folder: "./Dataset"

# Abstract
"We propose a novel approach for inferring the individualized causal effects of a treatment (intervention) from observational data. Our approach conceptualizes causal inference as a multitask learning problem; we model a subject's potential outcomes using a deep multitask network with a set of shared layers among the factual and counterfactual outcomes, and a set of outcome-specific layers. The impact of selection bias in the observational data is alleviated via a propensity-dropout regularization scheme, in which the network is thinned for every training example via a dropout probability that depends on the associated propensity score. The network is trained in alternating phases, where in each phase we use the training examples of one of the two potential outcomes (treated and control populations) to update the weights of the shared layers and the respective outcome-specific layers. Experiments conducted on data based on a real-world observational study show that our algorithm outperforms the state-of-the-art." <br/>
<pre>                                               <i> • Ahmed M. Alaa • Michael Weisz • Mihaela van der Schaar</i></pre>

# Implementation of the paper "Deep Counterfactual Networks with Propensity-Dropout"(https://arxiv.org/pdf/1706.05966.pdf) in pytorch

# Details will be added soon
