---
layout: publication
title: "SpikeNet: A Hybrid Model for Short-Term Load Forecasting using Spike Neural Network" # The publication/paper title
date: 2024-11-19 12:00:00 +0000 # The publication date, in the form YYYY-MM-DD HH-MM-SS +0000
authors: # A list of authors. Keep in list form, even if there is only one author.
- Ahsan Raza Khan
- Ubaid Ahmed
- Anzar Mahmood
- Poonam Yadav
- Amin Hammad
- Ahmed Zoha
venue: "TechRxiv" # OPTIONAL: The conference, journal or venue of publication
link: 'https://www.techrxiv.org/users/588110/articles/1240521-spikenet-a-hybrid-model-for-short-term-load-forecasting-using-spike-neural-network?commit=1743434fdb28e972eaa8e4e426f130d8da47c32d' # OPTIONAL: A link to an external site with the publication
preprint: true # OPTIONAL: Delete if the publication is not a preprint
---
Short-term load forecasting (STLF) is essential for efficient power system operations, including unit commitment and energy market operations. Traditional deep learning models like Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) networks have shown promise but often struggle with capturing complex temporal dependencies and nonlinearities in electricity load data. This paper introduces SpikeNet, a novel neural network architecture incorporating integrate-and-fire (IF) spiking neurons with Recurrent Neural Network (RNN) and LSTM layers to improve temporal dynamics modelling in STLF. Spiking neurons process information through discrete events, “spikes”, offering enhanced efficiency and the ability to model temporal patterns more effectively. We evaluate SpikeNet's performance against state-of-the-art models on three diverse datasets: Islamabad Electric Supply Company (IESCO), the IEEE data portal, and Panama City. Our results demonstrate that SpikeNet outperforms traditional models, achieving up to 33% improvement in mean absolute percentage error (MAPE) and up to 42% reduction in inference time. These findings highlight SpikeNet's potential as a more accurate and efficient solution for STLF, with significant implications for real-world power system applications.