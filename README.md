# ORAGEN page repository

The official repository for ORAGEN page

## Abstract
> Gender recognition and age estimation are essential tasks within soft biometric systems, where identifying these characteristics supports a wide range of applications. In real-world scenarios, challenges such as partial facial occlusion complicate these tasks by obscuring crucial voice and facial characteristics. These challenges highlight the importance of development of robust and efficient approaches for gender recognition and age estimation. In this study, we develop a novel audio-visual Occlusion-Robust Gender Recognition and Age Estimation (ORAGEN) approach. The proposed approach is based on intermediate features of unimodal transformer-based models and two Multi-Task Cross-Modal Attention (MTCMA) blocks, which predict gender, age, and protective mask type using voice and facial characteristics. We conduct detailed cross-corpus experiments on the TIMIT, aGender, CommonVoice, LAGENDA, IMDB-Clean, AFEW, VoxCeleb2, and BRAVE-MASKS corpora. The proposed unimodal models outperform State-of-the-Art approaches for gender recognition and age estimation. We investigate the impact of various protective mask types on the performance of audio-visual gender recognition and age estimation. The results show that the current large-scale data are still insufficient for a robust gender recognition and age estimation in partial facial occlusion conditions. On the Test subset of the VoxCeleb2 corpus, the proposed approach showed Unweighted Average Recall (UAR) of 99.51%, Mean Absolute Error (MAE) of 5.42, and UAR of 100% for gender recognition, age estimation, and protective mask type recognition, respectively, while on the Test subset of the BRAVE-MASKS corpus, it showed UAR=96.63%, MAE=7.52, and UAR=95.87%, for the same tasks. These results indicate that using data of people wearing protective masks, as well as including the protective mask type recognition task, yields performance gains on all tasks considered. ORAGEN can be integrated into the OCEAN-AI framework for optimizing HR processes, as well as into expert systems with practical applications in various domains including forensics, healthcare, and industrial safety.

## Acknowledgments

Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
