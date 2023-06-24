# visual-similarity-recommendations-model
Product recommendations based on image similarity using Tensorflow, Keras vgg16 pertained model

## Inspiration:
Visual Similarity Product Recommendation system from Adobe Commerce - Adobe Sensei
https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/admin/type.html?lang=en#visualsim
<img width="1078" alt="image" src="https://github.com/GvsSriRam/visual-similarity-recommendations-model/assets/57980789/a1157bed-e384-4c7a-955a-6009165134aa">


## Work done:
- Developed a POC of the product recommendation model used in the Industry
- Utilised open source model (VGG-16) to extract the features from the images

## Pros:
  - The client's products images won't be publicly exposed if the model is comprimised
  - As the model is pre-trained on 1M images ImageNet dataset, it is accurate in extracting the features as the client's dataset is smaller in most cases

## Cons:
  - Model is not customizable, meaning, we cannot infer the features extracted as product attributes like color, category, texture, etc.
