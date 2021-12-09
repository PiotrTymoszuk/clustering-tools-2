# clustering-tools-2
An updated, comprehensive toolbox of component analysis and clustering tools based on base R, factoextra, kohonen and pcaPP package functions. A set of functions and methods (predict, cv, impact) allows for semi-superivised clustering (kNN-driven label propagation), cross-validation of the cluster stability and determining of clustering variable importance by noising.

In contrast to the previous version of clustering tools (maintenance stopped), the new toolbox implements S3 OOP with a clearer plot/summary/extract API and 'lazier' evaluation, which may work better with large data sets. Additional distance kernels for SOM and combined (e.g. SOM + k-means) clustering accepted as custom distances by the kohonen::som function are provided now as a separate Rcpp-based package ('somKernels.tar').

A further development as a standalone package planned.
