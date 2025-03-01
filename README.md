Dataset Link - https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection?select=no



# THESIS-G56

1. Scratched CNN:

AdaBoost accuracy: 0.9116666666666666
AdaBoost log loss: 0.646517030096395
KNN accuracy: 0.9033333333333333
KNN log loss: 0.7070116376925559
RF accuracy: 0.93
RF log loss: 0.2523321375372628
SVM accuracy: 0.8933333333333333
Softmax accuracy: 0.965
Softmax log loss: 0.13604219361893874

Average Accuracy: 0.9206666666666667  
Average Log Loss: 0.43547574973628816


2. Xception: *******
AdaBoost log loss: 0.6430836191270892
AdaBoost accuracy: 0.91
KNN log loss: 0.19625383741746483
KNN accuracy: 0.9683333333333334
RF log loss: 0.2246693413830423
RF accuracy: 0.9483333333333334
SVM accuracy: 0.965
Softmax log loss: 0.05024118038015941
Softmax accuracy: 0.9816666666666667

Average Accuracy: 0.9546666666666667 
Average Log Loss: 0.278561994576939


3. InceptionV3: *******

AdaBoost log loss: 0.6421245399700052
AdaBoost accuracy: 0.9283333333333333
KNN log loss: 0.30897467781745463
KNN accuracy: 0.9633333333333334
RF log loss: 0.24625304437395504
RF accuracy: 0.9583333333333334
SVM accuracy: 0.9766666666666667
Softmax log loss: 0.05919000638942234
Softmax accuracy: 0.9866666666666667

Average Accuracy: 0.9626666666666667
Average Log Loss: 0.3141355671377093


4. ResNet50:

AdaBoost log loss: 0.6684940965888408
AdaBoost accuracy: 0.845
KNN log loss: 0.7235951727064569
KNN accuracy: 0.895
RF log loss: 0.2803952444263075
RF accuracy: 0.9166666666666666
SVM log loss: 0.4885371582376547
SVM accuracy: 0.7466666666666667
Softmax log loss: 0.2321642370077517
Softmax accuracy: 0.9483333333333334

Average Accuracy: 0.8703333333333333
Average Log Loss: 0.47863718179340226


5. EfficientNetB0:  *******

AdaBoost accuracy: 0.9433333333333334
AdaBoost log loss: 0.6019790878904286
KNN accuracy: 0.985
KNN log loss: 0.213250641535461
RF accuracy: 0.9716666666666667
RF log loss: 0.19731102974301248
SVM accuracy: 0.995
Softmax accuracy: 0.9983333333333333
Softmax log loss: 0.01582060232280801

Average Accuracy: 0.9786666666666667
Average Log Loss: 0.25709034037292755

6. VGG19: 

AdaBoost accuracy: 0.8116666666666666
AdaBoost log loss: 0.6680632833738435
KNN accuracy: 0.88
KNN log loss: 0.9067050405190171
RF accuracy: 0.9183333333333333
RF log loss: 0.26654753044913854
SVM accuracy: 0.7116666666666667
Softmax accuracy: 0.8083333333333333
Softmax log loss: 0.4524531363136041

Average Accuracy: 0.826
Average Log Loss: 0.5734422476639008








1. InceptionV3 + EfficientNetB0 => 
AdaBoost accuracy: 0.9383333333333334, log loss: 0.625064170248433
KNN accuracy: 0.9633333333333334, log loss: 0.30897467781745463
RF accuracy: 0.945, log loss: 0.2083767015147035
SVM accuracy: 0.96, log loss: 0.09053887534166741
Softmax accuracy: 0.9866666666666667, log loss: 0.059066748479041635

Average Accuracy: 0.9586666666666666
Average Log Loss: 0.2584042346802601


2.EfficientNetB0 + Xception    *******  
AdaBoost accuracy: 0.9233333333333333, log loss: 0.6283838979671037
KNN accuracy: 0.97, log loss: 0.1372099395236089
RF accuracy: 0.9633333333333334, log loss: 0.18008833282410772
SVM accuracy: 0.95, log loss: 0.1355488547327469
Softmax accuracy: 0.9883333333333333, log loss: 0.03632919606052738

Average Accuracy: 0.959 
Average Log Loss: 0.2235120442216189



3. InceptionV3 + Xception    =>  *******
AdaBoost accuracy: 0.9466666666666667, log loss: 0.621810179346457
KNN accuracy: 0.9733333333333334, log loss: 0.17411617953197223
RF accuracy: 0.96, log loss: 0.20486897867292206
SVM accuracy: 0.975, log loss: 0.051380443381658175
Softmax accuracy: 0.9883333333333333, log loss: 0.044646459459649186

Average Accuracy: 0.9686666666666668 
Average Log Loss: 0.21936444807853173


1. InceptionV3 + EfficientNetB0 + EfficientNetB0 + Xception =>
AdaBoost accuracy: 0.9466666666666667, log loss: 0.6189339508948936
KNN accuracy: 0.9733333333333334, log loss: 0.17411617953197223
RF accuracy: 0.9633333333333334, log loss: 0.17776344745566736
SVM accuracy: 0.975, log loss: 0.061273398733576144
Softmax accuracy: 0.9866666666666667, log loss: 0.04439643648403736

Average Accuracy: 0.969
Average Log Loss: 0.21529668262002932
3. InceptionV3 + Xception           => 	Average Accuracy: 0.9493333333333333    ************
					Average Log Loss: 0.28463496868478366


**1. InceptionV3 + EfficientNetB0 + InceptionV3 + Xception  => Average Accuracy: 0.932
							     Average Log Loss: 0.38647054195308417**
