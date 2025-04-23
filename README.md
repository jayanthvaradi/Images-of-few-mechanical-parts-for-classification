Dataset link : https://www.kaggle.com/datasets/manikantanrnair/images-of-mechanical-parts-boltnut-washerpin

This project evaluates the performance of six popular deep learning models on a multi-class classification task involving mechanical components: bolt, locating pin, nut, and washer. Each model was assessed using precision, recall, F1-score, and overall accuracy on both validation and test datasets.


Model	    Validation Accuracy	      Test Accuracy	      Best Per-Class     F1-Score
AlexNet	           92%	                 94%	                Nut          (F1: 0.98)
VGG-16	           96%	                 95%	               Washer        (F1: 0.97)
GoogleNet	         96%	                 95%	               Washer        (F1: 1.00)
ResNet-18	         97%	                 96%	            Nut & Washer     (F1: 0.99)
DenseNet-121	     98%	                 95%	            Nut & Washer     (F1: 1.00)
EfficientNet-B0	   96%	                 96%	            Nut & Washer     (F1: 0.98+)
Key Insights :
DenseNet-121 achieved the highest validation accuracy at 98%, with perfect classification for nut and washer classes.

ResNet-18 and EfficientNet-B0 delivered consistently high test accuracies of 96%, with strong class-wise balance.

All models performed best on nut and washer, showing high consistency across architectures.

Locating pin class had slightly lower recall in most models, indicating a potential area for further improvement or data augmentation.
