# Application-of-Object-Detection-CBIR-in-E-commerce-Fashion-Industry

Here we are aiming to solve problems faced by sellers and buyers, in the E-commerce Fashion Industry.
This is my final year project and my thesis for 2 research papers in a team of 3.

- We have developed an automated apparel tagging system for the sellers, which is based on Ensemble of various trained Object Detection models, by making use of techniques like NMS and Weighted Fusion Box.
- And help the consumers/customers; by providing them with a recommendation engine based on CBIR by Image Query system using CNNs, Autoencoders and cosine similarity. Here the customer has to just click an image of the apparel one desires and the system will provide you with similar apparels.
- Performed robust data augmentation techniques like geometric, color space, and resolution transformations on the scraped data using OpenCV and Pillow. Using libraries like Tensorflow and Pytorch we designed a 256-layer deep CNN and inserted it into an Object Detection algorithm like Faster RCNN and SSD using transfer learning. Trained it on a dual GPU Linux server with 128GB VRAM using SSH remote connection and integrating Jupyter Notebook with it.
- Observing variational strengths in different model combinations, designed a new algorithm to ensemble results from OD multiple models into one superior output in a quadratic weighted function, named ‘Non-linear Maximal Weighted Box Integration ’. It outperforms all singular models as well as other integration techniques.
