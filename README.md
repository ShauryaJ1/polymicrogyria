## Evaluating the Effectiveness of Vision Transformers for Pediatric Polymicrogyria Detection

### Submitted by Jason Hao, Shaurya Jain

Polymicrogyria (PMG) is a rare neurological con-
dition characterized by abnormal cerebral cortex development,
leading to excessive small, malformed gyri. With clinical manifestations including seizures, developmental delays, and intellectual
difficulties, accurate diagnosis is crucial yet often reliant on
subjective interpretation of MRI scans by radiologists. This study
explores the application of machine learning (ML) techniques,
particularly fine-tuned Vision Transformers, to automate the
detection of PMG in pediatric neuroimaging data. Utilizing the
publicly available PPMR dataset, consisting of 4,517 PMG scan
slices and 10,539 normal slices, we developed a scalable and
reliable diagnostic tool that significantly enhances the accuracy
and efficiency of PMG identification. Our results demonstrate
that the BEiT and DeiT models outperform existing benchmarks,
achieving high precision and recall while maintaining robustness
against unseen data. Our best scores were achieved using the Microsoft BEiT model, having reached an accuracy, recall, precision,
and accuracy of 0.999, 0.998, 1.000, and 0.999 respectively, on the
entire dataset. This work highlights the potential of ML in clinical
neurology, offering a path towards more timely interventions.

Trained Models for this project can be found here:
https://huggingface.co/sha000/ppmr-classifier-google-vit-base-patch16-224-in21k-8-epochs-full-balanced<br />
https://huggingface.co/sha000/ppmr-classifier-facebook-deit-base-patch16-224-8-epochs-full-balanced<br />
https://huggingface.co/sha000/ppmr-classifier-microsoft-beit-base-patch16-224-pt22k-ft22k-8-epochs-full-balanced
