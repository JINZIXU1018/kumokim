# kumokim 机器学习
cross_val_score
sklearn.model_selection.cross_val_score(estimator, X, y=None, *, groups=None, scoring=None, cv=None, n_jobs=None, verbose=0, params=None, pre_dispatch='2*n_jobs', error_score=nan
from sklearn.model_selection import cross_val_predict # cross_val_predict：Generate cross-validated estimates for each input data point
y_train_pred = cross_val_predict(sgd_clf,X_train,y_train_5,cv=3)# y_train_pred其实是三次交叉验证的预测值的集合
