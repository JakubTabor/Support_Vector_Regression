# Support_Vector_Regression
# I need to make feature scaling on my "X" and "y" """X = sc_X.fit_transform(X)""" """Y = sc_Y.fit_transform(Y)"""
# Then i import my "SVR" model and set kernel to "rbf" """SVR(kernel = 'rbf')""", then train my model """regressor.fit(X,Y)"""
# I use my "scaler" to predict results, use "sc_Y.inverse_transform" on my "y" and "sc_X.transform" on my "X" 
# """sc_Y.inverse_transform(regressor.predict(sc_X.transform([[6.5]])).reshape(-1,1))""" end "SVR" to predict
# Then visualize my results to my "scatter" i put my "X" and "y" arguments """sc_X.inverse_transform(X), sc_Y.inverse_transform(Y)"""
# And to "plot" my "X" "sc_Y", So my prediction "regressor.predict(X)" but reshape """reshape(-1,1)"""
