# Deepfake_Image_detection
Distinguish between AI and NON-AI image

This project addresses the critical challenge of distinguishing AI-generated images from real ones, a growing concern in the digital age as generative AI technologies proliferate. Leveraging advanced deep learning architectures, specifically ResNet and CLIP, the project aims to develop a robust classification system capable of reliably identifying the source of an image. Using a dataset of 60,000 images, evenly split between AI-generated and real images, rigorous data preprocessing techniques were applied, including normalization and augmentation, to enhance model training. ResNet's deep residual learning capabilities and CLIP's multimodal feature extraction provide complementary strengths, enabling effective feature learning and classification.
The project implemented transfer learning and fine-tuning strategies to optimize model performance, achieving high accuracy, precision, recall, and F1 scores on validation and test datasets. These metrics highlight the models’ ability to generalize effectively, even with subtle and complex image patterns. The comparative analysis between ResNet and CLIP revealed that CLIP's multimodal architecture provides superior performance in nuanced scenarios, making it highly suitable for practical applications.

Results of ResNet
   ● Accuracy: ResNet has an accuracy of 91.20% which is quite impressive as it can differentiate between an AI generated image and a real one.
   ● Precision and Recall: The high precision indicated that the model did well in ensuring that false positives were at a minimum, while a decent recall showed that there was 
   reliability in the detection of true positives.
   ● Insights: The deeper architecture with skip connections helps ResNet to learn more complicated features optimized for AI generated images.

<img width="441" alt="Screenshot 2025-03-22 at 1 50 29 AM" src="https://github.com/user-attachments/assets/b0732ae8-9f16-444c-9180-268d667b84cc" />

Clip Results:
  ● Accuracy: The accuracy of CLIP is 95.00%, which means it has outperformed or matched ResNet.
  ● Precision and Recall: In this case, the precision played out in favour of CLIP, as it was able to avoid false positives, and the recall remained at a competitive level ensuring 
  positive detection of true positives.
  ● Insights: CLIP has performed exceptionally well as a result of its multimodal approach, vision encoder, and pre-trained embeddings. These factors exhibited the strongest results on 
  images that had no effective distinguishing features.
  
<img width="336" alt="Screenshot 2025-03-22 at 1 52 01 AM" src="https://github.com/user-attachments/assets/71741b4a-e635-4bff-abbc-3bebd887b923" />

  
