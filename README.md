# Support_Vector_Regression
# I need to make feature scaling on my "X" and "y" """X = sc_X.fit_transform(X)""" """Y = sc_Y.fit_transform(Y)"""
# Then i import my "SVR" model and set kernel to "rbf" """SVR(kernel = 'rbf')""", then train my model """regressor.fit(X,Y)"""
# I use my "scaler" to predict results, use "sc_Y.inverse_transform" on my "y" and "sc_X.transform" on my "X" 
