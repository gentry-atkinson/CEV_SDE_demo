# CEV and SDE Example Applications

Algorithmic bias is of increasing concern, both to
the research community, and society at large. Bias in AI is more
abstract and unintuitive than traditional forms of discrimination
and can be more difficult to detect and mitigate. A clear gap exists
in the current literature on evaluating the relative bias in the
performance of multi-class classifiers. In this work, we propose
two simple yet effective metrics, Combined Error Variance (CEV)
and Symmetric Distance Error (SDE), to quantitatively evaluate
the class-wise bias of two models in comparison to one another.
By evaluating the performance of these new metrics and by
demonstrating their practical application, we show that they can
be used to measure fairness as well as bias. These demonstrations
show that our metrics can address specific needs for measuring
bias in multi-class classification.

## Definitions:

## Use Cases:

1) Selecting a pre-trained model by quickly and easily comparing the 
class-wise bias of several models. Demonstrated in: initial_data.ipynb

2) CEV and SDE can by used as a metric of binary fairness by comparing the
class-wise bias of a model on the full dataset to the bias of the same
model on a protected group. Demonstrated in: TitanicSexism_analysis.ipynb

3) The same technique for measuring fairness can be expanded to an arbitrary
number of classes and protected groups for any dataset. Demonstrated in:
celebA_training.ipynb
