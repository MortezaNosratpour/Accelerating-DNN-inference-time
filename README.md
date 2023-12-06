![image](https://github.com/MortezaNosratpour/Accelerating-DNN-inference-time/assets/45389014/92be7dc3-874c-4a7d-be9e-bc12335b05a8)![image](https://github.com/MortezaNosratpour/Accelerating-DNN-inference-time/assets/45389014/25779ac9-83c9-4f42-812d-405ba900814f)![image](https://github.com/MortezaNosratpour/Accelerating-DNN-inference-time/assets/45389014/07cffb81-eef9-4aae-819f-6f6752c68265)# Accelerating-DNN-inference-time
Accelerating inference time by adversarial training and caching intermediate representations. (Work is in progress)



Cross-layer similarities are amplified compared to standard training, also Adversarial representations are significantly similar to clean representations in networks trained through adversarial training:

![at](https://github.com/MortezaNosratpour/Accelerating-DNN-inference-time/assets/45389014/5a954b01-73fa-4448-a0a4-295b62d150af)




Increasing the strength of adversarial perturbations leads to a consistent presence of long-range similarity between layers:

![image](https://github.com/MortezaNosratpour/Accelerating-DNN-inference-time/assets/45389014/6ae22e0c-70ef-4f84-8ed7-aae0f98a7dbf)




According to investigated results; Incorporating adversarial training with caching intermediate representations:
- Will enhance the robustness of both the backbone network and cache networks by reducing disparities between clean and adversarial representations.
- Wil increase cross-layer representations similarities:
  *  So first representations will be similar to deep representations.
  * Consequently early exit will happen due to effective representations at first layers.
  * As attacks become stronger, the layers tend to become more similar. Therefore, based on the previous explanations, the likelihood of accurate early exit will increase.









