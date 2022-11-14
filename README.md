# VAE
This is the simple implementation of variational autoencoder. Check ae.ipynb for the standard autoencoder and vae.ipynb for the variational autoencoder.  The latent code is more densely distributed in variational autoencoder because of the KL divergence with the prior distribution that is normal distribution.   

## Contribution
Simple implementation of variational autoencoder.  The differences with the references are following. 

- [Pytorch VAE tutorial](https://github.com/AntixK/PyTorch-VAE/blob/master/models/vanilla_vae.py) I use ipynb and added a plot showing the distribution of the latent codes.  
- [VAE tutorial by Alexander Van de Kleut](https://avandekleut.github.io/vae/) The reference uses the mean square error. I use the binary cross entropy because it is what original reference uses.  

## Reference 
-  https://avandekleut.github.io/vae/

## Output sample
![Auto encoder latent code distribution](output/ae_distribution.png)
Latent code distribution of the autoencoder

![Auto encoder sampling](output/ae_sampling.png)
Sampling of the autoencoder

![Variational autoencoder](output/vae_distribution.png)
Latent code distribution of the variational autoencoder



![Variational autoencoder sampling](output/vae_sampling.png)
Sampling of the autoencoder
