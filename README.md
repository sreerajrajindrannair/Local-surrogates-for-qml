# Local-surrogates-for-qml

Repository for generating the plots and tables for the paper: "Local surrogates for quantum machine learning models"

Authors: Sreeraj Rajindran Nair and Christopher Ferrie

Affiliation: Centre for Quantum Software and Information, University of Technology Sydney, Australia

Abstract: Surrogates have been proposed as classical simulations of the pretrained quantum learning models, which are capable of mimicking the input-output relation inherent in the quantum model. Quantum hardware within this framework is used for training and for generating the classical surrogates. Inference is relegated to the classical surrogate, hence alleviating the extra quantum computational cost once training is done. Taking inspiration from interpretable models, we introduce a local surrogation protocol based on reuploading-type quantum learning models, including local quantum surrogates as cost-efficient intermediate quantum learning models. When the training and inference are only concerned with a subregion of the data space, deploying a local quantum surrogate offers qubit cost reductions and the downstream local classical surrogate achieves dequantization of the inference phase. Several numerical experiments are presented.
