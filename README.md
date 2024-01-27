# Product_Detection_from_Packshots
Given a set of images captured in grocery stores(shelf image), and a set of close up images of products in those stores, your task is as follows.

1. For every product image, find the location of that product in all shelf images in which it appears.
2. For every shelf image, locate all products and assign the name from given set of product images.

Steps included :
1. Reading Product and Shelf Images
2. Labelling the Product Data
3. Splitting the Data for Training and Testing
4. Training pretrained Neural Network - MobileNetV2
5. Testing and accuracy Measure
6. Using a pre-trained YOLOv5 network that detects items from shelf images. 
7. Use similarity between products to match product in shelf image.
8. Writing in the soluction_1.txt file - For every product image, find the location of that product in all shelf images in which it appears.
9. Writing in the soluction_1.txt file - For every shelf image, locate all products and assign the name from given set of product images.
