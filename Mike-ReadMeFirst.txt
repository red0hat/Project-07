There are some serious problems with the TSNE module in sklearn.  It is producing an error about "nans and inf" in the array, even though the matrix is fully populated with floats. 

I've spent a couple of hours stymied by this error.  Scott Tarlow thought he isolated the problem to being based on the verion of scikit-learn.  I don't think that is accurate.  When I updated the libraries, the error persisted.  My current theory is the error comes at load time.  There my be interactions between libraries or the order of loading the librariesmay cause the error.  But the error is inconsistent and intermitant.  

Also, the using t-SNE on top of PSA seems to be be very confusing. 

I'll continue to work on project, because I didn't reach any conclusions.


