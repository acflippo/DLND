# Project 5 - Face Generation

Using Generative Adversarial Networks to generate new images of faces.

I have uploaded 3 different notebooks:

- dlnd_face_generation.ipynb (plain vanilla one that can generate MNIST and face images with GANs)
  - this model worked fine but learning was slow and images were slow to converge to realistic images.

- dlnd_face_gen_control_dependencies.ipynb (includes control_dependencies in the model_opt(), model optimization function)
  - control_dependencies really helped generate realistic images within 1 epoch
  - it was faster than the plain vanilla model

- dlnd_face_gen_control_dep_label_smooth.ipynb (includes control_dependencies and label smoothing in the training process)
  - for this application, I didn't find applying label smoothing helped or hindered in generating realistic images
