# Challenge-14

Basline SVC Performance

	•	Below is the graph of the results from the baseline SVC analysis.:
	⁃	This demonstrates a relatively strong performance as strategy returns are largely higher than the actual returns from the actual returns



Precision: 
For the label -1.0: 43% of the instances predicted as -1.0 were actually -1.0. This means there's a moderate level of correctness in identifying -1.0 instances among all predicted -1.0 instances. 
For the label 1.0: 56% of the instances predicted as 1.0 were actually 1.0. This indicates a relatively good ability to correctly identify instances labeled as 1.0 among all predicted 1.0 instances. 

Recall: 
For the label -1.0: Only 4% of the actual -1.0 instances were correctly predicted as -1.0. This suggests that the model performs poorly in capturing true -1.0 instances among all actual -1.0 instances. 
For the label 1.0: 96% of the actual 1.0 instances were correctly predicted as 1.0. The model is highly capable of capturing true 1.0 instances among all actual 1.0 instances.


![Baseline_SVM](https://github.com/LeftWing11/Challenge-14/assets/137566806/6b74e969-8247-4abf-ae02-3c1dfe9c087f)
￼


Tuning 

	•	Method 1: Increasing training range from 3-6 months
	⁃	This did not improve results much - > strategy returns flipped between 2019 and 2020 from being above actual returns to below actual returns


￼ 

	⁃	Report suggested limited improvments 

<img width="494" alt="Pasted Graphic" src="https://github.com/LeftWing11/Challenge-14/assets/137566806/474d5de1-f4af-4dbb-9904-5512c2c6e3a8">


￼

	•	Method 2: Chnaging SMA slow from 4-5 and fast from 100 - 105

	⁃	Looked as if it resulted in better convergance between actual returns and strategy returns. Thus suggesting limited improvments. 

￼
![2__#$!@%!#__Baseline_SVM](https://github.com/LeftWing11/Challenge-14/assets/137566806/d1fbc2b1-21df-4549-af05-eeb1bdebd648)



As such changing keeping the baseline is the best for returns. 






Logistic Regression

	⁃	Results from logistic regression. There is a much greater disparity between the two, with strategy returns largely out performing actual returns. In this way it performed better than the baseline model we created. 

<img width="618" alt="Pasted Graphic 1" src="https://github.com/LeftWing11/Challenge-14/assets/137566806/0dc9ca43-8ee3-4785-84f7-abd73107e969">

