---
title: "Encoding spatiotemporal priors with VAEs for small-area estimation"
date: 2021-10-20
publishDate: 2021-10-20T11:25:55.112672Z
authors: ["Elizaveta Semenova", "Yidan Xu", "Adam Howes", "Theo Rashid", "Samir Bhatt", "Swapnil Mishra", "Seth Flaxman"]
publication_types: ["3"]
abstract: "Gaussian processes (GPs), implemented through multivariate Gaussian distributions for a finite collection of data, are the most popular approach in small-area spatiotemporal statistical modelling. In this context they are used to encode correlation structures over space and time and can generalise well in interpolation tasks. Despite their flexibility, off-the-shelf GPs present serious computational challenges which limit their scalability and practical usefulness in applied settings. Here, we propose a novel, deep generative modelling approach to tackle this challenge: for a particular spatiotemporal setting, we approximate a class of GP priors through prior sampling and subsequent fitting of a variational autoencoder (VAE). Given a trained VAE, the resultant decoder allows spatiotemporal inference to become incredibly efficient due to the low dimensional, independently distributed latent Gaussian space representation of the VAE. Once trained, inference using the VAE decoder replaces the GP within a Bayesian sampling framework. This approach provides tractable and easy-to-implement means of approximately encoding spatiotemporal priors and facilitates efficient statistical inference. We demonstrate the utility of our VAE two stage approach on Bayesian, small-area estimation tasks."
featured: false
publication: "*arXiv*"
url_pdf: "https://arxiv.org/pdf/2110.10422.pdf"
tags: ["probabilistic programming", "modelling", "bayesian", "gaussian process", "variational autoencoder"]
---