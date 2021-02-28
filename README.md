# Deep learning : Computer Go
A deep residual network architecture, able to optimize policy estimations, in order to play to Go. (constraint : less than 1 million parameters).

## Architecture used
Architecture used : Mobile Networks.
We used 24 bottle neck blocks, with trunk composed by 64-filters convolutional layers, and expand-layers as Depth wise convolution with 256 filters.

cf our report to discover more about it.


## Results
We reached : 
- Policy accuracy : 51.35%
- MSE value : 0.1745
- Policy loss : 1.676
- Loss : 2.324

## References
- Cazenave, T. : Mobile networks for computer Go. IEEE Transactions on Games (2020) Cazenave, T. : Residual networks for computer Go. IEEE Transactions on Games 10(1), 107–110 (2018)
- Andrew G. Howard, et al. : MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications (2017)
- Cazenave, T., Chen, Y.C., Chen, G.W., Chen, S.Y., Chiu, X.D., Dehos, J., Elsa, M., Gong, Q., Hu, H., Khalidov, V., Cheng-Ling, L., Lin, H.I., Lin, Y.J., Martinet, X., Mella, V., Rapin, J., Roziere, B., Synnaeve, G., Teytaud, F., Teytaud, O., Ye, S.C., Ye, Y.J., Yen, S.J., Zagoruyko, S. : Polygames : Improved zero learning. ICGA Journal 42(4) (December 2020)
- Google Inc. : MobileNetV2: Inverted Residuals and Linear Bottlenecks
