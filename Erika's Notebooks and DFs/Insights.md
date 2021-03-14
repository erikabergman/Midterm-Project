## First Logistic Regression Baseline Model with Atlanta Weather
GridSearch with few params revealed:
- Best max_iter: 100, Best penalty: l2, Best l1_ratio: 0.01
- With weather feature: 0.7076390669059216
- Without weather feature: 0.707254550115355

- With weather only slight improvement

## First Random Forest Baseline Model with Atlanta Weather
- With weather feature = Accuracy: 0.7326326582927455
- Without weather feature = Accuracy : 0.7332735196103564

- Weather made it slightly worse

## Logistic Regression Model with Chicago Weather, penalty = l2, max_iter = 1000
- With weather Accuracy: 0.6212341807593236
- Without weather feature: 0.6114906484488745

## Random Forest with Chicago Weather
- With Weather Accuracy : 0.7215813640945234
- Without Weather Accuracy : 0.7111658640385261

## KNN with baseline DF (minus, fl_date, taxi_in, taxi_out) n_neighbors=3
- With smote, no scaling Accuracy : 0.7106768030139935
- With smote, with scaling Accuracy : 0.754978471474704

## KNN with baseline DF (minus, fl_date, taxi_in, taxi_out) n_neighbors=1
- With Smote, with scaling Accuracy : 0.7956808396124866

## KNN n_neighbors = 15 is the worst 
